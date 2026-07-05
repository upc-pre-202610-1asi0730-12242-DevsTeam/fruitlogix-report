## 1.2 Solution Profile

### 1.2.1 Antecedentes y problemática

Desarrollando las preguntas clave usando el modelo de las 5W y 2H, ya que es importante para la identificación del problema y sus antecedentes.

| Preguntas | Pregunta formulada para el problema | Respuestas                                                                                                                                                                          |
|-----------|-------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Who?      | ¿Quiénes son los afectados?         | Supermercados, distribuidores, productores y mercados que participan en la cadena de suministro de frutas.                                                                          |
| What?     | ¿Cuál es el problema?               | La gestión logística se realiza de forma manual o con sistemas poco integrados, generando desorden en pedidos, falta de trazabilidad y riesgos en el control de calidad.            |
| Where?    | ¿Dónde ocurre?                      | En toda la cadena de distribución de frutas: desde el productor hasta el supermercado o mercado final.                                                                              |
| When?     | ¿Cuándo sucede?                     | Durante el proceso de distribución: registros de pedidos, asignaciones de pedidos, preparación del producto, etc.                                                                   |
| Why?      | ¿Por qué ocurre?                    | Ocurre por la falta de digitalización, el uso de herramientas aisladas y la ausencia de un control centralizado, lo que obliga a depender de procesos manuales propensos a errores. |
| How?      | ¿Cómo se manifiesta?                | En pedidos mal gestionados, retrasos en las entregas, productos en mal estado y pérdida de información, generando baja eficiencia operativa.                                        |
| How Much? | ¿Cuánto impacto tiene?              | Provoca pérdidas económicas, disminución de la calidad del producto, insatisfacción de los clientes y menor competitividad en el mercado.                                           |

### 1.2.2 Lean UX Process
### 1.2.2.1 Lean UX Problem Statements

Actualmente, la logística agrícola y la cadena de suministro de frutas en el Perú dependen en gran medida de procesos manuales, como hojas de cálculo, registros en papel y aplicaciones de mensajería, para coordinar las operaciones entre productores, distribuidores y clientes comerciales. Esta situación genera problemas como la desorganización en la gestión de pedidos, la falta de trazabilidad durante el proceso de distribución y retrasos que afectan la calidad del servicio y la toma de decisiones.

Las soluciones existentes no ofrecen una plataforma accesible y especializada que integre las necesidades de estos tres actores dentro de un mismo ecosistema digital. Como consecuencia, los distribuidores enfrentan dificultades para monitorear el estado de los pedidos, controlar la calidad de los productos y coordinar eficientemente la comunicación con productores y clientes.

**¿Cómo podríamos** reducir la desorganización y la falta de trazabilidad en la cadena de suministro de frutas, proporcionando una plataforma digital integrada para distribuidores medianos de Lima Metropolitana que abastecen a supermercados, mercados mayoristas y restaurantes, de manera que se logre reducir en un **30%** los errores operativos y en un **25%** los pedidos rechazados por problemas de calidad durante los primeros seis meses de uso?

### 1.2.2.2. Lean UX Assumptions

#### Business Assumptions

- Operamos en un dominio donde la digitalización de la logística agrícola y la cadena de suministro de frutas en el Perú aún es limitada, predominando procesos manuales mediante Excel, papel y WhatsApp.
- Los distribuidores medianos de Lima Metropolitana experimentan problemas de desorganización, falta de trazabilidad y errores operativos que justifican la adopción de una plataforma digital especializada.
- Los productores agrícolas presentan dificultades para coordinar entregas y reciben retroalimentación tardía sobre la calidad de sus productos, afectando su relación con los distribuidores.
- Los clientes comerciales (supermercados, restaurantes y juguerías) valoran la trazabilidad y la calidad constante de los productos, estando dispuestos a preferir distribuidores que utilicen herramientas digitales de seguimiento.
- Actualmente no existe en el mercado peruano una solución accesible y especializada que integre gestión de pedidos, control de calidad y trazabilidad para estos tres actores.
- Un modelo de negocio basado en suscripción según el volumen de pedidos gestionados resulta económicamente viable para distribuidores medianos.
- La integración de gestión logística, control de calidad y trazabilidad en una sola plataforma constituye una ventaja competitiva diferenciadora.
- Los distribuidores medianos que abastecen comercios de Lima Metropolitana representan el segmento más adecuado para validar el producto.

---

#### Business Outcomes

##### Impact Metric 1 – Reducción de errores operativos

**Meta:** Reducir en un **30%** los errores de registro, despacho y duplicidad durante los primeros seis meses.

**Asumimos que esto ocurrirá si:**

- Al menos el **90%** de los pedidos se registran directamente en la plataforma.
- El **80%** de los usuarios activos utiliza diariamente el sistema para gestionar sus operaciones.

##### Impact Metric 2 – Disminución de rechazos por calidad

**Meta:** Reducir en un **25%** los pedidos rechazados por problemas de calidad.

**Asumimos que esto ocurrirá si:**

- Los productores reportan el estado de calidad de cada lote antes del despacho en al menos el **80%** de los envíos.

##### Impact Metric 3 – Mejora de la eficiencia logística

**Meta:** Reducir progresivamente el tiempo promedio de preparación de pedidos.

**Asumimos que esto ocurrirá si:**

- El tiempo entre la creación del pedido y su confirmación por parte del productor disminuye gracias a notificaciones automáticas.

##### Impact Metric 4 – Mayor confianza y trazabilidad

**Meta:** Reducir significativamente las consultas manuales de los clientes comerciales.

**Asumimos que esto ocurrirá si:**

- Los clientes pueden consultar el estado y la trazabilidad de sus pedidos directamente desde la plataforma, reduciendo en un **50%** las llamadas y mensajes de seguimiento.

---

#### User Assumptions

### Carlos – Distribuidor

**Rol:** Gestiona pedidos y coordina productores y clientes comerciales.

**Características**

- Utiliza smartphone o computadora durante su jornada laboral.
- Necesita reducir errores y controlar todo el flujo de pedidos.
- Actualmente depende de herramientas dispersas como Excel, papel y WhatsApp.

### Rosa – Productora

**Rol:** Gestiona la disponibilidad y entrega de frutas.

**Características**

- Posee conocimientos digitales básicos.
- Requiere una interfaz simple e intuitiva.
- Necesita recibir retroalimentación inmediata sobre la calidad de sus productos.

### Miguel – Cliente Comercial

**Rol:** Compra frutas para supermercados, restaurantes o juguerías.

**Características**

- Gestiona varios proveedores simultáneamente.
- Busca trazabilidad y entregas puntuales.
- Actualmente depende de llamadas y mensajes para conocer el estado de sus pedidos.

---

#### Early Validation Assumptions

Se asume que:

- Carlos representa adecuadamente al segmento objetivo de distribuidores medianos de Lima Metropolitana.
- Rosa y Miguel experimentan los problemas identificados durante la investigación.
- Los tres actores están dispuestos a reemplazar procesos manuales por una plataforma digital si esta demuestra beneficios claros.

---

#### User Outcomes and Benefits

### Carlos – Distribuidor

**Objetivo**

- Gestionar todos sus pedidos desde una única plataforma.

**Beneficios esperados**

- Reducir en un **40%** el tiempo dedicado al registro y seguimiento de pedidos.
- Detectar incidencias antes del despacho.
- Obtener mayor control operativo.

### Rosa – Productora

**Objetivo**

- Coordinar entregas y conocer oportunamente los resultados del control de calidad.

**Beneficios esperados**

- Recibir retroalimentación inmediata.
- Reducir pérdidas ocasionadas por rechazos tardíos.
- Mejorar la coordinación con distribuidores.

### Miguel – Cliente Comercial

**Objetivo**

- Recibir productos de calidad y conocer el estado de sus pedidos.

**Beneficios esperados**

- Consultar la trazabilidad en tiempo real.
- Disminuir la incertidumbre durante el proceso de entrega.
- Reducir la necesidad de realizar llamadas de seguimiento.

---

#### Proposed Solution

La plataforma **FruitLogix** integra los procesos más importantes de la cadena de suministro mediante los siguientes módulos:

- **Gestión de pedidos:** Registro, seguimiento y actualización del estado de pedidos.
- **Control de calidad:** Validación de productos antes del despacho.
- **Trazabilidad:** Seguimiento completo desde el productor hasta el cliente comercial.
- **Notificaciones automáticas:** Alertas sobre cambios importantes del proceso.
- **Comunicación integrada:** Canal único entre distribuidores, productores y clientes.
- **Dashboard de indicadores:** Visualización de métricas para la toma de decisiones.

**Propuesta de valor**

Mejorar la eficiencia logística mediante la reducción de errores operativos, incrementando la trazabilidad, el control de calidad y la coordinación entre todos los participantes de la cadena de suministro.

---

#### Additional Business Assumptions

- El modelo de suscripción por volumen de pedidos permitirá capturar el valor generado por la plataforma.
- Las notificaciones proactivas tendrán mayor impacto que un dashboard pasivo.
- La interfaz destinada a los productores debe requerir la menor cantidad posible de interacciones para garantizar la actualización constante de la información.

---

#### Business Context

**Modelo de adquisición**

- Contacto directo con distribuidores.
- Demostraciones del sistema.
- Recomendaciones dentro del sector agrícola.

**Competencia**

- AgroData Perú.
- SAP Agri.
- TrazAgro.
- Procesos tradicionales mediante Excel, papel y WhatsApp.

**Diferenciador**

Plataforma especializada exclusivamente en la distribución de frutas que integra logística, control de calidad y trazabilidad en una única solución.

**Mayor riesgo**

La resistencia al cambio y la baja adopción tecnológica por parte de los usuarios.

**Mitigación**

- Entrevistas con usuarios.
- Validaciones tempranas.
- Pruebas de usabilidad.
- Diseño simple e intuitivo.
## 1.2.2.3 Lean UX Hypothesis Statements – FruitLogix

A continuación se presentan los *Hypothesis Statements* elaborados como parte del proceso Lean UX para el desarrollo del producto **FruitLogix**. Cada hipótesis establece la relación entre el resultado de negocio esperado (*Achieve*), el segmento de usuarios (*If*), el beneficio esperado (*Attain*) y la funcionalidad principal (*With*).

Las hipótesis están ordenadas según su nivel de riesgo y valor, siguiendo la lógica de la *Hypothesis Prioritization Canvas*: primero se validan las funcionalidades núcleo de mayor impacto y menor complejidad técnica, dejando para etapas posteriores aquellas que dependen de mayor adopción o complejidad (como IoT).

Estas hipótesis serán validadas mediante entrevistas con usuarios, pruebas de usabilidad y análisis de métricas de uso durante el ciclo de vida del producto.

---

## Statement 1

**Achieve:**  
Creemos que lograremos una reducción significativa de los errores operativos en los procesos de distribución de frutas, medida por una disminución del 30 % en los incidentes de pedidos incorrectos durante los primeros tres meses de uso.

**If:**  
Si los distribuidores de frutas que actualmente gestionan sus pedidos de forma manual o mediante herramientas aisladas adoptan FruitLogix como su plataforma central de gestión logística.

**Attain:**  
Alcanzarán una mejor organización de los pedidos, mayor visibilidad del estado de cada envío y una coordinación más rápida y precisa con sus proveedores agrícolas.

**With:**  
Con una plataforma web centralizada que integra la gestión de pedidos, el seguimiento logístico en tiempo real y la comunicación directa entre distribuidores y productores dentro de un único ecosistema digital.

---

## Statement 2

**Achieve:**  
Creemos que lograremos una disminución de al menos el 25 % en la tasa de rechazo de productos por problemas de calidad, reduciendo las pérdidas económicas asociadas a devoluciones y mermas durante el primer semestre de operación.

**If:**  
Si los productores agrícolas y los clientes comerciales que enfrentan inconsistencias en la validación manual de productos integran el módulo de control de calidad de FruitLogix en su flujo de trabajo habitual.

**Attain:**  
Alcanzarán una validación de calidad más confiable, estandarizada y trazable antes de cada entrega, con registros de inspección accesibles para todos los actores involucrados.

**With:**  
Con un módulo integrado de control y validación de calidad que permite registrar el estado de los lotes, adjuntar evidencia fotográfica y generar informes de conformidad que dan seguimiento al producto a lo largo de toda la cadena de suministro.

---

## Statement 3

**Achieve:**  
Creemos que lograremos una mejora sustancial en la visibilidad y trazabilidad de toda la cadena de suministro de frutas, logrando que el 80 % de los pedidos cuenten con un seguimiento completo desde su origen hasta la entrega final.

**If:**  
Si los distribuidores, productores y clientes comerciales que actualmente carecen de información centralizada y en tiempo real sobre el estado de sus operaciones adoptan activamente las funcionalidades de trazabilidad de FruitLogix.

**Attain:**  
Alcanzarán acceso en tiempo real al estado de los pedidos, la ubicación de los envíos y la trazabilidad completa del historial de cada lote de productos, permitiéndoles tomar decisiones más oportunas y reducir la incertidumbre operativa.

**With:**  
Con un sistema de monitoreo y trazabilidad en tiempo real que centraliza la información de todos los actores de la cadena de suministro, integrando actualizaciones automáticas del estado de los pedidos y un historial auditable de cada operación.

---

## Statement 4

**Achieve:**  
Creemos que lograremos una mejora en la eficiencia de la coordinación logística y la asignación de pedidos, reduciendo en un 40 % el tiempo promedio de confirmación de envíos en comparación con el proceso manual actual.

**If:**  
Si los distribuidores de frutas que coordinan manualmente la asignación de pedidos entre múltiples productores y puntos de entrega utilizan las funcionalidades de automatización de FruitLogix para gestionar sus operaciones diarias.

**Attain:**  
Alcanzarán una coordinación más rápida y precisa con los productores, mediante una asignación optimizada de pedidos basada en criterios predefinidos de disponibilidad, capacidad y calidad.

**With:**  
Con una funcionalidad de asignación automatizada de pedidos y coordinación de entregas que sugiere el productor más adecuado para cada pedido, notifica en tiempo real a todas las partes involucradas y reduce la intervención manual en el proceso.

---

## Statement 5

**Achieve:**  
Creemos que lograremos una reducción de al menos el 20 % en las pérdidas de productos durante el transporte, gracias al monitoreo continuo de las condiciones ambientales a lo largo de la ruta de distribución.

**If:**  
Si los productores y distribuidores que transportan productos perecederos sin controles ambientales integran los sensores IoT de FruitLogix en sus unidades de transporte y utilizan el panel de monitoreo de la plataforma.

**Attain:**  
Alcanzarán un mayor control de las condiciones de transporte y almacenamiento de los productos, recibiendo alertas preventivas ante desviaciones de temperatura o humedad que les permitan actuar antes de que se produzcan pérdidas.

**With:**  
Con sensores IoT para el monitoreo de la temperatura y la humedad durante el transporte, integrados con el panel de control de FruitLogix, que envían alertas en tiempo real cuando los parámetros salen del rango óptimo definido para cada tipo de producto.


#### 1.2.2.4. Lean UX Canvas

| 1. Business Problem | 5. Solution Ideas | 2. Business Outcomes |
|--------------------|------------------|----------------------|
| La cadena de distribución de frutas entre productores, distribuidores y clientes comerciales opera de forma manual y descoordinada (Excel, papel, WhatsApp), lo que genera errores en pedidos, falta de trazabilidad, rechazos por calidad y retrasos en la entrega. Esto ocasiona costos logísticos elevados, pérdidas económicas por devoluciones y baja satisfacción del cliente final. | - Plataforma web centralizada para gestión de pedidos en tiempo real. <br> - Módulo de control de calidad con criterios estandarizados por lote. <br> - Sistema de trazabilidad de productos a lo largo de la cadena de suministro. <br> - Asignación automatizada de pedidos entre productores y distribuidores. <br> - Notificaciones automáticas y comunicación integrada entre actores. <br> - Dashboard de KPIs para monitoreo de desempeño logístico. | - Reducir en 30% los errores operativos en la gestión de pedidos. <br> - Disminuir en 25% los rechazos por problemas de calidad. <br> - Mejorar la trazabilidad de los productos de extremo a extremo. <br> - Reducir tiempos de coordinación y confirmación de pedidos. <br> - Disminuir la dependencia de llamadas y mensajes para seguimiento. |

| 3. Users and Customers | 4. User Benefits |
|------------------------|------------------|
| - **Carlos (Distribuidor):** gestiona pedidos y coordina productores y clientes. Necesita visibilidad total y reducir errores causados por Excel/WhatsApp. <br><br> - **Rosa (Productora):** prepara y despacha fruta. Necesita coordinación clara y feedback oportuno sobre calidad y entregas. <br><br> - **Miguel (Cliente comercial):** compra fruta para retail o restaurantes. Necesita trazabilidad y seguridad en la calidad del producto. | - Acceso a información centralizada y en tiempo real. <br><br> - Reducción de errores en pedidos y coordinación logística. <br><br> - Feedback inmediato sobre calidad de productos. <br><br> - Mayor confianza y transparencia en la cadena de suministro. <br><br> - Menor dependencia de llamadas y comunicación manual. |

| 6. Hypotheses | 7. Assumptions | 8. Experiments |
|--------------|--------------|----------------|
| - Creemos que una plataforma centralizada reducirá en 30% los errores operativos si los distribuidores gestionan pedidos en tiempo real. <br><br> - Creemos que el módulo de calidad reducirá en 25% los rechazos si los productores validan sus lotes antes del despacho. <br><br> - Creemos que la trazabilidad en tiempo real mejorará la confianza del cliente final si los pedidos pueden ser rastreados end-to-end. | - Asumimos que los usuarios tienen acceso a smartphone o computadora con internet estable. <br><br> - Asumimos que actualmente no existe una herramienta centralizada de gestión logística. <br><br> - Asumimos disposición de adopción de herramientas digitales si reducen errores y tiempos. <br><br> - Asumimos que mejorar la trazabilidad reduce costos por devoluciones y rechazos. | - Piloto con 3 distribuidores y 2 supermercados durante 4 semanas. <br><br> - Medición de reducción de errores vs proceso manual (línea base). <br><br> - Validación de adopción ≥70% de uso activo en el primer mes. <br><br> - Entrevistas post-piloto para evaluar usabilidad y valor percibido. |