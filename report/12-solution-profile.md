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
#### 1.2.2.1. Lean UX Problem Statements
El objetivo actual del negocio es ayudar a los distribuidores de frutas a gestionar de manera eficiente los pedidos y cumplir con los estándares exigidos por los clientes comerciales en cuanto a calidad y tiempos de entrega. Sin embargo, un problema es la gestión manual o el uso de herramientas aisladas, lo que genera errores operativos, desorganización y dificultades en la coordinación del proceso logístico. Ante ello, ¿Cómo podríamos diseñar una plataforma que optimice la gestión logística y reduzca los errores operativos en la distribución de frutas?

El objetivo actual del negocio es asegurar que los productos agrícolas cumplan con los requisitos de calidad establecidos por los clientes antes de su envío. No obstante, un problema es que la validación del estado de los productos depende del criterio humano, lo que puede generar inconsistencias y ocasionar pérdidas económicas debido a rechazos. Ante ello, ¿Cómo podríamos diseñar un sistema que permita validar la calidad de los productos antes de su entrega para reducir el riesgo de rechazo?

El objetivo actual del negocio es coordinar de manera eficiente la interacción entre distribuidores, productores y clientes comerciales dentro de la cadena de suministro. Sin embargo, un problema es la falta de trazabilidad y de información centralizada, lo que dificulta el seguimiento de los pedidos y reduce la capacidad de tomar decisiones oportunas. Ante ello, ¿Cómo podríamos diseñar una solución que permita centralizar la información y mejorar la trazabilidad en toda la cadena de distribución?

#### 1.2.2.2. Lean UX Assumptions
**Assumptions Worksheet**

**Business Assumptions:**

* **Domain:** Nos encontramos en el dominio de la logística agrícola y cadena de suministro de frutas, donde la digitalización es aún incipiente y los procesos manuales predominan entre productores, distribuidores y clientes comerciales en el Perú.


* **Customer Segments:** Nuestros usuarios principales son distribuidores de frutas medianos que operan en Lima, productores agrícolas en distintas zonas rurales, y clientes comerciales como supermercados, restaurantes y juguerías que requieren abastecimiento constante de productos frescos.


* **Pain Points:** Los distribuidores enfrentan desorganización en la gestión de pedidos, falta de trazabilidad y dependencia de procesos manuales propensos a errores. Los productores tienen dificultades para coordinar entregas y reciben retroalimentación tardía sobre la calidad de su producto. Los clientes comerciales sufren retrasos en las entregas, inconsistencia en la calidad recibida y ausencia de sistemas formales de seguimiento.


* **Gap:** Actualmente no existe una solución accesible y especializada en el mercado peruano que integre en una sola plataforma la gestión de pedidos, el control de calidad y la trazabilidad para la distribución de frutas entre estos tres actores.


* **Vision / Strategy:** Nuestra visión es convertirnos en la plataforma de referencia para la digitalización de la cadena de suministro frutícola en el Perú, comenzando con distribuidores medianos en Lima y expandiéndonos hacia otras regiones y productos agrícolas. La estrategia consiste en ofrecer una solución accesible con un modelo de suscripción basado en volumen de pedidos, conectando la aplicación con los tres segmentos identificados.


* **Initial Segment:** Nuestro segmento inicial son los distribuidores de frutas medianos con operaciones activas en Lima Metropolitana que abastecen a cadenas de retail o restaurantes, ya que son el actor central de la cadena y quienes más se benefician de una plataforma integrada.

**User Assumptions:**

* **¿Dónde encaja nuestro producto en su trabajo o vida?** Nuestro producto sería usado en su día a día durante la gestión de pedidos, coordinación con productores, validación de calidad y seguimiento de entregas dentro de la cadena de distribución de frutas.


* **¿Qué problemas tiene nuestro producto que debe resolver?** Limitaciones en la organización de pedidos, dependencia a los procesos manuales, falta de trazabilidad, y dificultades en la coordinación entre los actores de la cadena.


* **¿Cuándo y cómo es usado nuestro producto?** El producto será utilizado en la rutina diaria de trabajo de distribuidores y productores, especialmente en momentos de recepción de pedidos, preparación de productos, control de calidad y despacho. Se usará mediante una aplicación web donde los usuarios monitorean pedidos, calidad y entregas en tiempo real.


* **¿Qué características son importantes?** Registro y gestión de pedidos, monitoreo de calidad, trazabilidad de pedidos, integración con sensores IoT (a futuro), dashboard visual con indicadores claros, notificaciones y alertas, y comunicación entre actores.


* **¿Cómo debe verse nuestro producto y cómo comportarse?** El diseño debe ser intuitivo, visual y fácil de usar, permitiendo que usuarios con bajo nivel técnico comprendan rápidamente la información. Debe comportarse de manera confiable, rápida y precisa, asegurando la trazabilidad y el control del proceso logístico.

**Feature Assumptions:**

* Creemos que nuestros clientes necesitan una plataforma centralizada que elimine el uso de procesos manuales y herramientas aisladas para mejorar la organización y reducir errores operativos en la gestión logística.


* Estas necesidades se pueden resolver con una aplicación web que permita gestionar pedidos, coordinar proveedores y monitorear la calidad en tiempo real dentro de una sola plataforma.


* El valor #1 que un cliente quiere de nuestro servicio es mejorar la eficiencia en la gestión de pedidos y reducir los errores operativos en su proceso logístico.


* El cliente también puede obtener estos beneficios adicionales: mayor control de calidad, mejor trazabilidad de los productos, reducción de pérdidas económicas y mejor coordinación con proveedores y clientes.


* Vamos a adquirir la mayoría de nuestros clientes a través de contactos directos en el rubro, recomendaciones y demostraciones del sistema mostrando mejoras en sus procesos actuales.


* Haremos dinero a través de un modelo de suscripción basado en la cantidad de pedidos gestionados mensualmente.


* Nuestra competencia principal en el mercado serán AgroData Perú, SAP Agri y TrazAgro, además de métodos tradicionales como Excel, papel, WhatsApp y sistemas logísticos genéricos no especializados.


* Los venceremos debido a que nuestra plataforma está especializada en la distribución de frutas, integrando gestión logística, control de calidad y trazabilidad en un solo sistema.


* Nuestro mayor riesgo de producto es que los usuarios no adopten la plataforma debido a resistencia al cambio o falta de familiaridad con herramientas digitales.


* Resolveremos esto a través de validaciones tempranas, entrevistas, pruebas de usuario y un diseño simple e intuitivo que facilite la adopción.


* Otra suposición es que los usuarios estarán dispuestos a digitalizar sus procesos. Si esto resulta falso, el sistema no será adoptado, lo que afectaría la viabilidad del proyecto.

**Business Outcomes:**

* Reducción de errores operativos en un 30% en los primeros 6 meses de uso.


* Disminución de rechazos de productos en un 25% tras la implementación del módulo de calidad.


* Mejora en la eficiencia del proceso logístico medida por reducción del tiempo promedio de preparación de pedidos.

#### 1.2.2.3. Lean UX Hypothesis Statements
### Statement 1
**Creemos que** al implementar una plataforma web centralizada para la gestión de pedidos, los distribuidores podrán reducir la desorganización y los errores operativos.

**Sabremos que hemos tenido éxito**

**Cuando** al menos el 30% de los errores en pedidos se reduzcan y el 70% de los usuarios adopten activamente la plataforma en los primeros 3 meses

---

### Statement 2
**Creemos que** al incluir un sistema de validación de calidad previo al envío, se reducirá el envío de productos defectuosos hacia los supermercados.

**Sabremos que hemos tenido éxito**

**Cuando** los rechazos por calidad disminuyan en un 40% y el 80% de los pedidos sean aceptados en la primera entrega

---

### Statement 3
**Creemos que** al integrar un sistema de trazabilidad en tiempo real, los usuarios podrán tener mayor visibilidad y control del estado de los pedidos.

**Sabremos que hemos tenido éxito**

**Cuando** el 75% de los usuarios consulte el estado de pedidos en la plataforma y los problemas de seguimiento se reduzcan en un 35%

---

### Statement 4
**Creemos que** al automatizar la asignación de pedidos entre distribuidores y productores, se mejorará la eficiencia en la coordinación logística.

**Sabremos que hemos tenido éxito**

**Cuando** el tiempo de asignación de pedidos se reduzca en un 25% y el 70% de los pedidos sean asignados en menos tiempo que el proceso manual

---

### Statement 5
**Creemos que** al integrar sensores IoT para monitorear temperatura y condiciones de transporte, se podrá garantizar la calidad del producto durante su traslado.

**Sabremos que hemos tenido éxito**

**Cuando** las pérdidas por deterioro se reduzcan en un 30% y el 85% de los envíos mantengan condiciones óptimas registradas

---
#### 1.2.2.4. Lean UX Canvas

| 1. Business Problem | 5. Solution Ideas | 2. Business Outcomes |
|--------------------|------------------|----------------------|
| La cadena de distribución de frutas entre productores, distribuidores y supermercados opera de forma manual y descoordinada, lo que genera errores en pedidos, rechazos por falta de calidad y pérdida de trazabilidad. Esto resulta en costos logísticos elevados, pérdidas económicas por devoluciones y baja satisfacción de los clientes finales. | - Plataforma web centralizada para el registro y seguimiento de pedidos. <br> - Módulo de validación de calidad con criterios estandarizados. <br> - Asignación automatizada de órdenes entre distribuidores y productores. <br> - Integración de sensores IoT para monitorear temperatura y humedad durante el transporte. <br> - Visualización de datos y reportes de trazabilidad en tiempo real. | - Reducir los errores operativos en la gestión de pedidos. <br> - Disminuir los rechazos por calidad en los centros de distribución. <br> - Mejorar la trazabilidad de los productos a lo largo de toda la cadena. <br> - Optimizar los tiempos de entrega y la coordinación entre actores. |

| 3. Users and Customers | 4. User Benefits |
|------------------------|------------------|
| - **Usuarios directos:** Distribuidores medianos que gestionan pedidos y coordinan con productores y supermercados. <br><br> - **Clientes finales:** Grandes cadenas de retail como Plaza Vea. <br><br> - **Usuarios indirectos:** Productores agrícolas que preparan y despachan pedidos según estándares. | - Acceso a información centralizada y en tiempo real. <br><br> - Reducción de rechazos gracias a validación previa. <br><br> - Planificación eficiente de rutas y asignación. <br><br> - Mayor confianza y transparencia en decisiones logísticas. |

| 6. Hypotheses | 7. Assumptions | 8. Experiments |
|--------------|--------------|----------------|
| - Creemos que una plataforma centralizada reducirá errores operativos y mejorará la adopción digital. <br><br> - Creemos que el módulo de calidad disminuirá los rechazos. <br><br> - Creemos que la trazabilidad en tiempo real dará mayor visibilidad. | - Asumimos acceso a computadoras o smartphones. <br><br> - Asumimos falta de herramientas centralizadas actuales. <br><br> - Asumimos disposición a adoptar soluciones digitales. <br><br> - Asumimos reducción de costos con mejor trazabilidad. | - Piloto con 3 distribuidores y 2 supermercados (4 semanas). <br><br> - Medir reducción de errores vs proceso manual. <br><br> - Validar adopción ≥70% en el primer mes. <br><br> - Recoger feedback de usabilidad y utilidad. |