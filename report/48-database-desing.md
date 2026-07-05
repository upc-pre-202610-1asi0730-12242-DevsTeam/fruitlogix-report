### 4.8. Database Design
#### 4.8.1. Database Diagrams

El diagrama de base de datos traduce a nivel de persistencia los seis *Bounded Contexts* identificados en la arquitectura de software (sección 4.6), estableciendo las tablas, atributos, llaves primarias, llaves foráneas y relaciones necesarias para soportar la operación de **FruitLogix** sobre un modelo relacional.

---

## Bounded Context: Profiles & Vehicles Management

Administra la identidad de los usuarios y los recursos de transporte.

Incluye:

- **users:**  
  Identificador único, nombre, correo, contraseña encriptada, rol, teléfono, estado y fecha de creación.

- **vehicles:**  
  Identificador, placa, tipo, capacidad en kilogramos, propietario (FK a users), estado y fecha de registro.

---

## Bounded Context: Order Management

Es el núcleo transaccional del sistema.

Incluye:

- **distributors:** perfil especializado vinculado a users (FK)
- **producers:** perfil especializado vinculado a users (FK)
- **products:** catálogo de productos gestionados
- **orders:** pedido con distribuidor, producto, fecha, estado y monto total
- **order_items:** descomposición del pedido en ítems individuales
- **order_items_assignment:** asignación de ítems a productores según disponibilidad

Este contexto modela la relación uno a muchos entre pedidos e ítems.

---

## Bounded Context: Quality Control

Registra la validación de calidad previa al despacho.

Incluye:

- **batches:** lote de producto vinculado a una orden
- **quality_records:** inspecciones con fecha, calificación de calidad, temperatura, humedad y observaciones (FK a batches)
- **inspection_photos:** evidencia fotográfica asociada a cada registro de inspección

---

## Bounded Context: Payment Management

Soporta la facturación y el procesamiento financiero.

Incluye:

- **invoices:** comprobantes vinculados a órdenes, con monto y estado
- **billing_info:** datos de facturación del usuario (RUC/DNI, dirección fiscal)
- **transactions:** registro de intentos de pago con método, monto, estado y referencia externa de la pasarela

---

## Bounded Context: Logistics & Monitoring

Da seguimiento a la entrega física del pedido.

Incluye:

- **deliveries:** envío vinculado a orden, vehículo y estado de entrega
- **routes:** rutas calculadas con origen, destino, distancia y tiempo estimado (integración con Google Maps API)
- **notifications:** alertas y avisos enviados a los usuarios según eventos del sistema

---

## Bounded Context: Infrastructure & IoT

Gestiona la telemetría de los sensores.

Incluye:

- **iot_devices:** dispositivos asociados a vehículos (número de serie, tipo, estado)
- **telemetry_logs:** registros de temperatura, humedad y ubicación GPS en tiempo real, con indicador de alerta

---

## Relaciones entre contextos

Aunque cada *Bounded Context* mantiene su propio conjunto de tablas, existen relaciones mediante llaves foráneas que conectan el flujo completo del negocio:

- **Order Management ↔ Profiles & Vehicles:**  
  orders referencia a distributors y producers.

- **Logistics & Monitoring ↔ Order Management ↔ Profiles & Vehicles:**  
  deliveries referencia a orders y vehicles.

- **Payment Management ↔ Order Management:**  
  invoices referencia a orders.

---

Estas relaciones permiten la trazabilidad de extremo a extremo del ciclo del negocio: desde la creación del pedido hasta su entrega, monitoreo y pago. Esta trazabilidad soporta directamente los *Business Outcomes* definidos en el Lean UX Canvas (sección 1.2.2.4), especialmente en la reducción de errores y mejora de visibilidad operativa.

![Database Diagram](../assets/images/diagrams/database-diagram.png)