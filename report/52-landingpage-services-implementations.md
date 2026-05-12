### 5.2. Landing Page, Services & Applications Implementation
En esta sección se describe el proceso de implementación del producto FruitLogix, incluyendo el desarrollo, pruebas, documentación y despliegue del Landing Page.

Para este avance, se implementó la primera versión del Landing Page, orientada a presentar la propuesta de valor del sistema. El desarrollo se realizó utilizando tecnologías web y GitHub como herramienta de control de versiones.
#### 5.2.1. Sprint 1
En esta sección se presenta el avance del Sprint 1 en términos de desarrollo del producto y trabajo colaborativo del equipo.

Durante este sprint se realizó la implementación de la primera versión del Landing Page de FruitLogix, enfocada en presentar la propuesta de valor del sistema.

Asimismo, se incluyen las evidencias relacionadas con la planificación del sprint, la organización del equipo, el backlog definido, el desarrollo realizado, así como los resultados obtenidos y la colaboración durante el proceso.
##### 5.2.1.1. Sprint Planning 1
En esta sección se describen los principales acuerdos y definiciones realizadas durante el Sprint Planning del Sprint 1, enfocado en la implementación del Landing Page de FruitLogix.

| Campo | Detalle |
|------|--------|
| **Sprint #** | Sprint 1 |
| **Sprint Planning Background** |  |
| Date | 2026-04-22 |
| Time | 17:30 |
| Location | Reunión virtual (Google Meet) |
| Prepared By | Contreras Granados, Johan Alexis |
| Attendees (to planning meeting) | Contreras Granados, Johan Alexis - Chavez Bardales, Esteban Eduardo - Evangelista Ygnacio, Sergio Joaquín - Jaime Forcelledo, Gonzalo Alexander - Palomino Vilcañaupa, Daril Johan |
| **Sprint 1 – 1 Review Summary** | Al tratarse del primer sprint del proyecto, no se cuenta con una iteración previa. Sin embargo, se tomó como base el Product Backlog definido y los diseños del Landing Page elaborados en etapas anteriores. |
| **Sprint 1 – 1 Retrospective Summary** | No aplica para este sprint. No obstante, el equipo acordó enfocarse en una correcta distribución de tareas y comunicación constante desde el inicio del desarrollo. |
| **Sprint Goal & User Stories** |  |
| Sprint 1 Goal | Our focus is on developing a functional and responsive landing page that presents the value proposition of FruitLogix. We believe it delivers clear understanding of the product to potential users. This will be confirmed when users can visualize the landing page, navigate between its sections, and correctly view it across different devices. |
| User Stories incluidas en el Sprint | US31: Visualizar Landing Page; US32: Navegar entre secciones del Landing Page; US33: Visualización responsive del Landing Page |
| **Sprint 1 Velocity** | 9 Story Points |
| **Sum of Story Points** | 9 Story Points |

##### 5.2.1.2. Aspect Leaders and Collaborators

En esta sección se define la matriz de liderazgo y colaboración (LACX) del Sprint 1, la cual permite identificar claramente las responsabilidades de cada integrante del equipo en los distintos aspectos del desarrollo.

Para este sprint, los principales aspectos considerados están relacionados con la implementación del Landing Page, incluyendo la estructura visual, navegación entre secciones y adaptación responsive.

Estos aspectos fueron definidos en base a las funcionalidades abordadas en el sprint y permiten organizar de manera eficiente el trabajo del equipo.

| Team Member (Last Name, First Name) | GitHub Username | Estructura del Landing Page | Navegación entre secciones | Diseño Responsive |
|------------------------------------|-----------------|-----------------------------|----------------------------|-------------------|
| Contreras Granados, Johan Alexis | johancg04 | L | C | C |
| Evangelista Ygnacio, Sergio Joaquín | Sergi9017 | C | L | C |
| Chavez Bardales, Esteban Eduardo | ECEB0704 | C | C | L |
| Jaime Forcelledo, Gonzalo Alexander | gonzalojaimeforcelledo | C | C | C |
| Palomino Vilcañaupa, Daril Johan | Daroh19 | C | C | C |

##### 5.2.1.3. Sprint Backlog 1

El Sprint 1 tuvo como objetivo principal la implementación del Landing Page de FruitLogix, permitiendo presentar la propuesta de valor del sistema mediante una interfaz clara, estructurada y accesible.

Para la gestión del Sprint Backlog, se utilizó una herramienta de control de tareas basada en tableros (Trello), donde se organizaron los User Stories y sus respectivos tasks en columnas según su estado de avance.

A continuación, se presenta el tablero correspondiente al Sprint 1 junto con su enlace:

https://trello.com/invite/b/69e8591bc5e24c8aae6fefb7/ATTI43de960425182289c279df7734d6424548D550DA/developersteam-product-backlog

![SprintBacklog](../assets/images/trello.png)

| Sprint # | User Story | Work-Item / Task | Descripción | Estimation (Hours) | Assigned To | Status |
|----------|------------|------------------|-------------|--------------------|-------------|--------|
| Sprint 1 | **US31 - Visualizar Landing Page** | TASK01 - Hero + Navbar | Implementación de la sección principal del Landing Page incluyendo barra de navegación, título y botones de acción. | 4 | Johan | Done |
| Sprint 1 | **US31 - Visualizar Landing Page** | TASK02 - Sección Beneficios | Desarrollo de la sección de beneficios mostrando funcionalidades principales del sistema | 3 | Sergio | Done |
| Sprint 1 | **US31 - Visualizar Landing Page** | TASK03 - Sección Clientes | Implementación de la sección de clientes objetivo del sistema | 3 | Esteban | Done |
| Sprint 1 | **US31 - Visualizar Landing Page** | TASK06 - Testimonios + Footer | Desarrollo de la sección de testimonios y pie de página del Landing Page | 2 | Daril | Done |
| Sprint 1 | **US32 - Navegar entre secciones del Landing Page** | TASK04 - Navegación entre secciones | Implementación del desplazamiento entre secciones del Landing Page | 2 | Johan | In-Process |
| Sprint 1 | **US33 - Visualizar Landing Page** | TASK05 - Responsive Landing | Adaptación del Landing Page a dispositivos móviles y tablets | 4 | Gonzalo | In-Process |

##### 5.2.1.4. Development Evidence for Sprint Review

En este Sprint se logró la implementación del Landing Page de FruitLogix, desarrollando su estructura principal en HTML y CSS, así como la navegación entre secciones y avances en el diseño responsive.

El desarrollo se organizó mediante ramas de tipo feature en GitHub, permitiendo trabajar de manera paralela en las distintas secciones del Landing Page. Los commits reflejan la construcción progresiva de la interfaz, incluyendo la implementación del Hero, secciones informativas y estilos visuales.

A continuación, se presentan los commits más relevantes asociados al desarrollo del Sprint 1.

| Repository | Branch | Commit id | Commit Message | Commit Message Body | Committed on (Date) |
|------------|--------|-----------|----------------|---------------------|----------------------|
| johancg04/fruitlogix-website | feature/landing-hero-navbar | b35e1c4 | feat: add navbar section into landing page. | Se implementa la estructura HTML y estilos CSS del Hero y barra de navegación del Landing Page | 22/04/2026 |
| johancg04/fruitlogix-website | feature/landing-hero-navbar | 2df11db | feat: add hero section in landing page. | Se implementa la estructura HTML y estilos CSS del Hero y barra de navegación del Landing Page | 22/04/2026 |
| Sergi9017/fruitlogix-website | feature/landing-benefits | 01fe667 | feat: add benefits section | Se desarrolla la sección de beneficios mostrando las funcionalidades principales del sistema | 23/04/2026 |
| ECEB0704/fruitlogix-website | feature/landing-client | 0bc60c3 | feat: add clients section | Implementación de la sección de clientes objetivo del sistema | 23/04/2026 |
| Daroh19/fruitlogix-website | feature/landing-testimonials-footer | 3382d87 | feat: add testimonials and footer | Se implementa la sección de testimonios y el footer del Landing Page | 23/04/2026 |
| johancg04/fruitlogix-website | feature/landing-navigation | - | feat: implement navigation scroll | Se implementa la navegación entre secciones mediante scroll | In Progress |
| gonzalojaimeforcelledo/fruitlogix-website | feature/landing-planes | - | feat: add section planes | Se implementa la sección de planes para nuestros usuarios | 23/04/2026 |

##### 5.2.1.5. Execution Evidence for Sprint Review

En el **Sprint 1** se logró implementar el *Landing Page* de **FruitLogix**, permitiendo presentar la propuesta de valor del sistema a través de una interfaz clara, organizada y accesible.

Se desarrollaron las principales secciones del *Landing Page*, incluyendo el **Hero**, **beneficios**, **clientes** y **testimonios**, así como la navegación entre secciones mediante *scroll*. Asimismo, se realizaron avances en la adaptación *responsive* para distintos dispositivos.

A continuación, se presentan evidencias visuales de las principales vistas implementadas en este Sprint.

Video de Demostración de Navegación (Landing Page): https://goo.su/TAKKGp

### Screenshots del Landing Page
### Vista general (Hero + Navbar)

![HeroNavBar](../assets/images/lp-hero-navbar.png)

### Seccion Beneficios

![Beneficios](../assets/images/lp-beneficios.png)

### Seccion Planes

![Planes](../assets/images/lp-planes.png)

### Seccion de Clientes

![Clientes](../assets/images/lp-clientes.png)

### Seccion de Testimonios

![Testimonios](../assets/images/lp-testimonios.png)

### Seccion de Footer

![Footer](../assets/images/lp-footer.png)


##### 5.2.1.6. Services Documentation Evidence for Sprint Review

En el presente Sprint no se implementaron Web Services ni endpoints funcionales, debido a que el alcance estuvo enfocado en el desarrollo del Landing Page como primera versión del producto.

Sin embargo, se definió como parte del análisis inicial la futura implementación de servicios RESTful correspondientes al Epic EP06, los cuales permitirán la integración entre el Landing Page y la Web Application en siguientes Sprints.

Estos servicios estarán orientados a funcionalidades como registro de usuarios, autenticación y gestión de pedidos, los cuales serán documentados utilizando el estándar OpenAPI en futuras iteraciones del proyecto.

##### 5.2.1.7. Software Deployment Evidence for Sprint Review

#### Despliegue de la Landing Page
El despliegue de la Landing Page de FruitLogix se realizó utilizando GitHub Pages, aprovechando sus capacidades para publicar sitios web estáticos directamente desde un repositorio. Este enfoque permitió una implementación sencilla, automatizada y accesible sin necesidad de servicios externos adicionales.

#### Infraestructura de Despliegue

- **Repositorio de código fuente:** GitHub
- **Plataforma de despliegue:** GitHub Pages
- **Tipo de aplicación:** Landing Page estática (HTML, CSS, JavaScript)
- **Acceso:** URL pública generada por GitHub

#### Proceso de Despliegue

1. **Creación del repositorio**
    - Se creó un repositorio en GitHub que contiene todos los archivos de la Landing Page (HTML, CSS, imágenes y scripts).
    - Se organizó el proyecto asegurando que el archivo principal sea `index.html`, requerido por GitHub Pages.

   ![Deployment](../assets/images/Deployment-Create-Repository.png)

2. **Subida del código**
    - Se realizó el `push` del proyecto a la rama principal (`main`) del repositorio.
    - Se verificó que todos los recursos estén correctamente enlazados (rutas relativas).

   ![Deployment](../assets/images/Deployment-Push.png)

3. **Configuración de GitHub Pages**
    - En la sección *Settings* del repositorio, se habilitó **GitHub Pages**.
    - Se seleccionó la rama `main` como fuente de despliegue.
    - Se definió la carpeta raíz (`/root`) como directorio de publicación.

   ![Deployment](../assets/images/Deployment-GHPages.png)

4. **Publicación automática**
    - GitHub Pages procesó automáticamente el contenido del repositorio.
    - En pocos minutos, generó una URL pública donde la Landing Page quedó disponible.

   ![Deployment](../assets/images/Deployment-URL.png)

5. **Actualizaciones**
    - Cada vez que se realiza un nuevo `push` a la rama `main`, GitHub Pages actualiza automáticamente la página.
    - Esto permite mantener la Landing Page sincronizada con los cambios del repositorio sin intervención manual adicional.

#### Resultado
La Landing Page de FruitLogix fue desplegada exitosamente mediante GitHub Pages, permitiendo su acceso público a través de una URL estable. Esto facilita la presentación del producto a usuarios potenciales y valida la propuesta de valor del sistema de manera rápida y efectiva.

URL: https://upc-pre-202610-1asi0730-12242-devsteam.github.io/fruitlogix-website/

##### 5.2.1.8. Team Collaboration Insights during Sprint

Durante el **Sprint 1**, el equipo trabajó de manera colaborativa en la implementación del *Landing Page* de **FruitLogix**, organizando las tareas por secciones de la interfaz para permitir el desarrollo en paralelo.

Cada integrante asumió la responsabilidad de una parte específica del *Landing Page* (como **Hero**, **beneficios**, **clientes** y **testimonios**), lo que permitió avanzar de forma eficiente y reducir conflictos en el código. Asimismo, se utilizó **GitHub** como herramienta principal de control de versiones, gestionando el trabajo mediante ramas (*feature branches*) y *commits* individuales.

La integración del trabajo se realizó de manera progresiva, consolidando las distintas secciones en una única versión funcional del *Landing Page*.

![Insights](../assets/images/Insights-Contributors.png)

### 5.2.2. Sprint 2

#### 5.2.2.1 Sprint Planning 2
En esta sección se describen los principales acuerdos y definiciones realizadas durante el Sprint Planning del Sprint 2, enfocado en la implementación de los módulos de gestión de pedidos, productores y seguimiento logístico de FruitLogix.

| Sprint # | Sprint 2 |
|---|---|
| **Sprint Planning Background** | |
| Date | 2026-05-10 |
| Time | 19:00 |
| Location | Reunión virtual (Google Meet) |
| Prepared By | Evangelista Ygnacio, Sergio Joaquín |
| Attendees (to planning meeting) | Contreras Granados, Johan Alexis - Chavez Bardales, Esteban Eduardo - Evangelista Ygnacio, Sergio Joaquín - Jaime Forcelledo, Gonzalo Alexander - Palomino Vilcañaupa, Daril Johan |
| **Sprint 1 Review Summary** | Durante el Sprint 1 se logró implementar correctamente el Landing Page responsive de FruitLogix, incluyendo navegación entre secciones, adaptación móvil y soporte multilenguaje. Además, el equipo consolidó la estructura base del frontend y definió estándares iniciales de trabajo colaborativo utilizando GitFlow y Trello para la gestión de tareas. |
| **Sprint 1 Retrospective Summary** | El equipo identificó como principal fortaleza la buena distribución de tareas y la comunicación constante durante el desarrollo del Sprint 1. Sin embargo, se detectaron pequeños retrasos en la integración de componentes y validaciones responsive, por lo que para este sprint se acordó mejorar la coordinación durante los merges y aumentar la frecuencia de revisiones entre integrantes. |
| **Sprint 2 Goal** | Our focus is on developing the order and producer management modules, IoT infrastructure, logistics monitoring and payment processing for FruitLogix. We believe it delivers better logistics organization, real-time quality control and centralized operational control for distributors. This will be confirmed when users can register, edit, visualize and manage orders and producers correctly, IoT devices send and evaluate sensor readings, shipments are tracked in real time, and payments are processed and confirmed within the platform. |
| **Sprint 2 Velocity** | 38 Story Points |
| **Sum of Story Points** | 38 Story Points |


| Sprint # | Nano Sprint |
|---|---|
| **Sprint Planning Background** | |
| Date | 2026-05-11 |
| Time | 10:00 - 12:30 |
| Location | Reunión física en clase |
| Prepared By | Velasquez Nuñez, Angel Augusto |
| Attendees (to planning meeting) | Contreras Granados, Johan Alexis - Chavez Bardales, Esteban Eduardo - Evangelista Ygnacio, Sergio Joaquín - Palomino Vilcañaupa, Daril Johan |
| **Sprint 2 Review Summary** | Durante el Sprint 2 se logró implementar los módulos de gestión de pedidos y productores de FruitLogix, incluyendo el formulario de registro, validaciones, tabla de pedidos, edición, eliminación lógica y lista de productores. Además, el equipo avanzó en la integración de Vue Router para la navegación entre vistas y consolidó el uso del validador externo separado en la capa de aplicación. |
| **Sprint 2 Retrospective Summary** | El equipo identificó como principal fortaleza la correcta separación de responsabilidades entre capas (presentation, application) siguiendo la arquitectura DDD definida en el event storming. Sin embargo, se detectaron retrasos en la conexión entre componentes vía Vue Router y en la gestión de los emits entre vistas, por lo que para el Nano Sprint se acordó priorizar la integración completa del flujo de navegación y aumentar la frecuencia de revisiones entre integrantes antes de los merges. |
| **Nano Sprint Goal** | Our focus is on developing the order and producer management modules for FruitLogix. We believe it delivers better logistics organization and centralized operational control for distributors. This will be confirmed when users can register, edit, visualize and manage orders and producers correctly within the platform. |
| **Nano Sprint Velocity** | 9 Story Points |
| **Sum of Story Points** | 9 Story Points |

#### 5.2.2.2. Aspect Leaders and Collaborators.

En esta sección se define la matriz de liderazgo y colaboración (LACX) del Sprint 2, la cual permite identificar claramente las responsabilidades de cada integrante del equipo en los distintos aspectos del desarrollo.

| Team Member (Last Name, First Name) | GitHub Username | Gestión de Pedidos | Gestión de Productores | Seguimiento de Entregas y Estados |
|---|---|---|---|---|
| Contreras Granados, Johan Alexis | johancg04 | C | C | L |
| Evangelista Ygnacio, Sergio Joaquín | Sergi9017 | L | C | C |
| Chavez Bardales, Esteban Eduardo | ECEB0704 | C | L | C |
| Jaime Forcelledo, Gonzalo Alexander | gonzalojaimeforcelledo | C | C | C |
| Palomino Vilcañaupa, Daril Johan | Daroh19 | C | C | C |

#### 5.2.2.3. Sprint Backlog 2
El Sprint 2 tuvo como objetivo principal la implementación de las funcionalidades relacionadas con la gestión de pedidos y productores dentro de la plataforma FruitLogix, permitiendo centralizar la información logística y mejorar el seguimiento operativo de los pedidos en tiempo real.

A continuación, se presenta el tablero correspondiente al Sprint 2 junto con su enlace:

URL: https://goo.su/XA06

| User Story ID | User Story Title | Task ID | Task Title | Description | Estimation (Hours) | Assigned To |
|---|---|---|---|---|---|---|
| US01 | Formulario de registro de pedidos | TASK008 | Formulario registro de pedidos | Desarrollo de la interfaz para registrar nuevos pedidos en la plataforma. | 5 | Johan |
| US01 | Validaciones de pedido | TASK009 | Validaciones de pedido | Implementación de validaciones para campos obligatorios en pedidos. | 3 | Sergio |
| US04 | Listar pedidos | TASK010 | Tabla de pedidos | Creación de la vista para listar y visualizar pedidos registrados. | 4 | Esteban |
| US02 | Edición de pedidos | TASK011 | Edición de pedidos | Desarrollo de la funcionalidad para modificar información de pedidos existentes. | 4 | Gonzalo |
| US02 | Restricción de modificación | TASK022 | Restricción de modificación | Valida el pedido y en caso contrario muestra un mensaje de restricción al Distribuidor cuando intente editar el pedido. | 3 | Daril |
| US03 | Eliminación de pedidos | TASK012 | Eliminación de pedidos | Implementación de la eliminación lógica de pedidos dentro del sistema. | 3 | Johan |
| US04 | Tabla de pedidos | TASK010 | Tabla de pedidos | Creación de la vista para listar y visualizar pedidos registrados. | 5 | Sergio |
| US04 | Comprobación de registro de pedidos | TASK021 | Comprobación de registro de pedidos | Validar que el sistema muestre correctamente mensaje informativo cuando no existan datos registrados. | 2 | Esteban |
| US05 | Registro de productores | TASK013 | Registro de productores | Desarrollo del formulario para registrar productores en la plataforma. | 5 | Gonzalo |
| US05 | Validación de datos | TASK020 | Validación de datos | Desarrollo del registro del productor pero en caso falte algún dato, el sistema resalta los datos con error y muestra mensaje de validación. | 3 | Daril |
| US06 | Lista de productores | TASK014 | Lista de productores | Implementación de la visualización de productores registrados. | 4 | Johan |
| US013 | ID inválida | TASK023 | ID inválida | Implementación de la validación de códigos de pedido inexistentes al realizar una consulta de rastreo. | 2 | Sergio |
| US014 | Actualización de estados | TASK016 | Actualización de estados | Implementación de cambios manuales en el estado logístico de pedidos. | 4 | Sergio |
| TS004 | Crear endpoint registro de pedidos API | TASK017 | Crear endpoint registro de pedidos API | Desarrollo del endpoint REST para registrar pedidos desde el backend. | 5 | Johan |
| TS005 | Crear endpoint consulta de pedidos API | TASK018 | Crear endpoint consulta de pedidos API | Implementación del endpoint REST para consultar pedidos registrados. | 4 | Esteban |
| TS008 | Gestión de productores API | TASK019 | Gestión de productores API | Desarrollo de endpoints para registrar y consultar productores. | 5 | Daril |
| US015 | Endpoint de ubicación en tiempo real | TASK024 | Implementar endpoint de ubicación en tiempo real | Crear el endpoint que retorna la última lectura de ubicación registrada por el dispositivo GPS_TRACKER asociado a un pedido. | 6 | Sergio |
| US015 | Calibración de dispositivos IoT | TASK025 | Implementar calibración de dispositivos IoT | Desarrollar la funcionalidad calibrate() de la clase IoTDevice para permitir el ajuste de parámetros de los sensores desde la plataforma. | 5 | Johan |
| US017 | Notificación de retraso por GPS Tracker | TASK026 | Implementar notificación de retraso por GPS Tracker | Desarrollar el servicio que consume las lecturas del GPS_TRACKER para detectar retrasos y generar notificación al Cliente Comercial. | 6 | Esteban |
| US018 | Crear entidad IoTDevice | TASK027 | Crear entidad IoTDevice | Implementar la clase IoTDevice con atributos deviceId, deviceType, location, status y lastReading, incluyendo los métodos connect(), sendData() y calibrate(). | 4 | Daril |
| US018 | Crear entidad SensorReading | TASK028 | Crear entidad SensorReading | Implementar la clase SensorReading con atributos readingId, deviceId, timestamp, value y unit, incluyendo los métodos validateRange() y generateAlert(). | 4 | Sergio |
| US018 | Crear entidad AlertRule | TASK029 | Crear entidad AlertRule | Implementar la clase AlertRule con atributos ruleId, deviceType, minThreshold, maxThreshold y alertMessage, incluyendo el método evaluate(reading). | 3 | Johan |
| US018 | Crear enumeración DeviceType | TASK030 | Crear enumeración DeviceType | Implementar el enum DeviceType con los valores TEMPERATURE_SENSOR, HUMIDITY_SENSOR, GPS_TRACKER y WEIGHT_SCALE. | 2 | Esteban |
| US018 | Crear enumeración DeviceStatus | TASK031 | Crear enumeración DeviceStatus | Implementar el enum DeviceStatus con los valores ACTIVE, OFFLINE, MAINTENANCE y BATTERY_LOW. | 2 | Daril |
| US018 | Repositorio de dispositivos IoT | TASK032 | Implementar repositorio de dispositivos IoT | Crear el repositorio para la persistencia de IoTDevice, SensorReading y AlertRule, incluyendo operaciones de registro, consulta y actualización. | 5 | Sergio |
| US018 | Lógica de evaluación de alertas | TASK033 | Implementar lógica de evaluación de alertas de calidad | Desarrollar el servicio que ejecuta evaluate(reading) de AlertRule para comparar lecturas contra umbrales y generar alertas automáticas. | 5 | Johan |
| US018 | Endpoint de registro de lectura de sensor | TASK034 | Implementar endpoint de registro de lectura de sensor | Crear el endpoint que recibe lecturas de dispositivos IoT, las persiste como SensorReading y dispara la evaluación de AlertRule. | 5 | Esteban |
| US021 | Generación de Invoice en PDF | TASK035 | Generación de Invoice en PDF | Desarrollar la funcionalidad generatePDF() de la clase Invoice para exportar la factura en formato PDF con los datos del pedido y monto total. | 5 | Daril |
| US021 | Endpoint de consulta de facturas | TASK036 | Implementar endpoint de consulta de facturas | Crear el endpoint que retorna el historial de facturas generadas por rango de fechas para el módulo de reportes del Distribuidor. | 4 | Sergio |
| US030 | Crear entidad BillingInfo | TASK037 | Crear entidad BillingInfo | Implementar la clase BillingInfo con atributos billingId, clientId, creditCardToken y paymentMethodType, incluyendo processPayment() y updatePaymentMethod(). | 3 | Johan |
| US030 | Crear entidad Invoice | TASK038 | Crear entidad Invoice | Implementar la clase Invoice con atributos invoiceId, orderId, issueDate, totalAmount y paymentStatus, incluyendo generatePDF() y markAsPaid(). | 3 | Esteban |
| US030 | Crear entidad Transaction | TASK039 | Crear entidad Transaction | Implementar la clase Transaction con atributos transactionId, invoiceId, amount, timestamp y externalReference, incluyendo confirm() y reverse(). | 3 | Daril |
| US030 | Crear enumeración PaymentStatus | TASK040 | Crear enumeración PaymentStatus | Implementar el enum PaymentStatus con los valores PENDING, PAID, FAILED, REFUNDED y PARTIALLY_PAID. | 2 | Sergio |
| US030 | Repositorio de pagos | TASK041 | Implementar repositorio de pagos | Crear el repositorio para la persistencia de BillingInfo, Invoice y Transaction, incluyendo operaciones de creación y consulta. | 4 | Johan |
| US030 | Integración con pasarela externa | TASK042 | Integración con pasarela externa | Desarrollar el servicio de integración con Culqi o Izipay para procesar pagos y recibir confirmación o rechazo de la transacción. | 8 | Esteban |
| US030 | Endpoint de procesamiento de pago | TASK043 | Implementar endpoint de procesamiento de pago | Crear el endpoint que recibe la solicitud de pago, llama al servicio de la pasarela externa y actualiza el estado del pedido a "Pagado". | 5 | Daril |
| US030 | Manejo de pago rechazado | TASK044 | Implementar manejo de pago rechazado | Desarrollar la lógica que gestiona la respuesta negativa de la pasarela, mantiene el pedido en "Pendiente de pago" y retorna el mensaje de error. | 4 | Sergio |
| US030 | Confirmación de pago por correo | TASK045 | Enviar confirmación de pago por correo | Implementar el envío automático de correo de confirmación al cliente cuando la transacción es aprobada, incluyendo detalle del pedido y comprobante. | 4 | Johan |

#### 5.2.2.4. Development Evidence for Sprint Review

| Repository | Branch | Commit Id | Commit Message | Committed By | Committed On |
|---|---|--|---|---|---|
| fruitlogix-webapp | develop | e0c0c4a | Merge pull request #15 from feature/i18n | Daroh19 | 2026-05-12 |
| fruitlogix-webapp | feature/i18n | f1c3305 | feat(i18n): initialize i18n configuration with English and Spanish locales | Daroh19 | 2026-05-12 |
| fruitlogix-webapp | develop | b643f90 | Merge pull request #14 from feature/order-management | johancg04 | 2026-05-12 |
| fruitlogix-webapp | feature/order-management | 813a543 | refactor: rename order-management.js to order-management-api.js for clarity | johancg04 | 2026-05-12 |
| fruitlogix-webapp | develop | dc56b98 | Merge pull request #13 from feature/pinia | gonzalojaimeforcelledo | 2026-05-12 |
| fruitlogix-webapp | develop | b2b0278 | Merge pull request #12 from feature/locales | Daroh19 | 2026-05-12 |
| fruitlogix-webapp | feature/locales | 406d773 | feat(locales): add English and Spanish document json | Daroh19 | 2026-05-12 |
| fruitlogix-webapp | develop | 4554916 | Merge pull request #11 from feature/server | johancg04 | 2026-05-12 |
| fruitlogix-webapp | feature/server | 57bcf94 | feat: add initial database structure for orders, fruits, producers, clients, and deliveries | johancg04 | 2026-05-12 |
| fruitlogix-webapp | develop | 29079fc | Merge pull request #10 from feature/logistics-monitoring | Daroh19 | 2026-05-12 |
| fruitlogix-webapp | feature/pinia | d08df91 | docs(pinia): add .env.development | gonzalojaimeforcelledo | 2026-05-12 |
| fruitlogix-webapp | feature/pinia | 543b337 | docs(pinia): add .env.production | gonzalojaimeforcelledo | 2026-05-12 |
| fruitlogix-webapp | feature/logistics-monitoring | 45f3575 | feat(domain): add Alert entity for logistics monitoring alerts | Daroh19 | 2026-05-12 |
| fruitlogix-webapp | feature/logistics-monitoring | 7fdedc4 | feat(infrastructure): implement logistics monitoring API gateway for deliveries and alerts | Daroh19 | 2026-05-12 |
| fruitlogix-webapp | develop | 3b96a86 | Merge pull request #9 from feature/dashboard | johancg04 | 2026-05-12 |
| fruitlogix-webapp | feature/logistics-monitoring | 0261f4a | feat(presentation): add delivery card component | Daroh19 | 2026-05-12 |
| fruitlogix-webapp | develop | 9b872a1 | Merge pull request #2 from feature/pinia | johancg04 | 2026-05-12 |
| fruitlogix-webapp | feature/logistics-monitoring | a0e2d79 | feat(presentation): add analytics and incidents view for real-time monitoring | Daroh19 | 2026-05-12 |
| fruitlogix-webapp | develop | dd311cb | Merge pull request #5 from feature/payment-management | johancg04 | 2026-05-12 |
| fruitlogix-webapp | feature/logistics-monitoring | f907ac5 | feat(presentation): add delivery details view for real-time tracking and telemetry | Daroh19 | 2026-05-12 |
| fruitlogix-webapp | develop | 4e93fcf | Merge pull request #6 from feature/quality-control | johancg04 | 2026-05-12 |
| fruitlogix-webapp | feature/logistics-monitoring | f5d1b39 | feat(presentation): add logistics monitoring home page for real-time order tracking | Daroh19 | 2026-05-12 |
| fruitlogix-webapp | feature/logistics-monitoring | 510a014 | feat(presentation): add monitoring dashboard for real-time delivery tracking | Daroh19 | 2026-05-12 |
| fruitlogix-webapp | develop | 6bf366d | Merge pull request #8 from feature/shared | johancg04 | 2026-05-12 |
| fruitlogix-webapp | develop | 827149e | Merge pull request #7 from feature/order-management | johancg04 | 2026-05-12 |
| fruitlogix-webapp | feature/logistics-monitoring | 0118c6c | feat(presentation): add logistics monitoring routes for dashboard and tracking | Daroh19 | 2026-05-12 |
| fruitlogix-webapp | feature/logistics-monitoring | 0cc267c | feat(infrastructure): add TrackingLogAssembler for mapping TrackingLog entities | Daroh19 | 2026-05-12 |
| fruitlogix-webapp | develop | bb062c6 | Merge pull request #4 from feature/profiles-and-vehicles | ECEB0704 | 2026-05-12 |
| fruitlogix-webapp | feature/logistics-monitoring | 663b17b | feat(infrastructure): add DeliveryAssembler for mapping Delivery entities and API | Daroh19 | 2026-05-12 |
| fruitlogix-webapp | feature/quality-control | f23091a | feat: add routing for quality control home view | Sergi9017 | 2026-05-12 |
| fruitlogix-webapp | develop | 4bad8bd | Merge pull request #3 from feature/iot-infrastructure | ECEB0704 | 2026-05-12 |
| fruitlogix-webapp | feature/shared | 5ae5300 | feat: add 404 page not found component with styling and navigation | johancg04 | 2026-05-12 |
| fruitlogix-webapp | feature/quality-control | d3c14fe | feat: add placeholder view for quality control home | Sergi9017 | 2026-05-12 |
| fruitlogix-webapp | feature/shared | cc6594c | feat: implement main layout with sidebar and topbar components | johancg04 | 2026-05-12 |
| fruitlogix-webapp | feature/profiles-and-vehicles | 94d8d22 | feat: add Producer list view component for managing producers | ECEB0704 | 2026-05-12 |
| fruitlogix-webapp | feature/logistics-monitoring | 83b7222 | feat(domain): add logistics Service for delivery ETA calculation and route | Daroh19 | 2026-05-12 |
| fruitlogix-webapp | feature/profiles-and-vehicles | 8a67f1c | feat: add Producer registration form component | ECEB0704 | 2026-05-12 |
| fruitlogix-webapp | feature/quality-control | b729b17 | feat: implement QualityControlApi for batch and incident management | Sergi9017 | 2026-05-12 |
| fruitlogix-webapp | feature/profiles-and-vehicles | c1cf31f | feat: add lazy-loaded route definitions for Profiles & Vehicles context | ECEB0704 | 2026-05-12 |
| fruitlogix-webapp | feature/quality-control | e9c7ca5 | feat: add Incident entity for quality control context | Sergi9017 | 2026-05-12 |
| fruitlogix-webapp | feature/quality-control | f274e17 | feat: add HarvestBatch entity for quality control context | Sergi9017 | 2026-05-12 |
| fruitlogix-webapp | feature/logistics-monitoring | 04ad413 | feat(domain): add notification entity and type enumeration for alerts | Daroh19 | 2026-05-12 |
| fruitlogix-webapp | feature/profiles-and-vehicles | ccb200a | feat: implement ProfilesAndVehiclesApi for managing users, drivers, vehicles, and producers | ECEB0704 | 2026-05-12 |
| fruitlogix-webapp | feature/logistics-monitoring | 78df662 | feat(domain): add route entity for delivery path representation | Daroh19 | 2026-05-12 |
| fruitlogix-webapp | feature/profiles-and-vehicles | fe33df6 | feat: add ProducerAssembler for mapping Producer entity to API JSON | ECEB0704 | 2026-05-12 |
| fruitlogix-webapp | feature/logistics-monitoring | e0371af | feat(domain): add TrackingLog entity for sensor data recording | Daroh19 | 2026-05-12 |
| fruitlogix-webapp | feature/quality-control | e687e76 | feat: add quality control store with batch and incident fetching | Sergi9017 | 2026-05-12 |
| fruitlogix-webapp | feature/profiles-and-vehicles | 0dbf229 | feat: add Vehicle entity definition for Profiles & Vehicles context | ECEB0704 | 2026-05-12 |
| fruitlogix-webapp | feature/logistics-monitoring | e10904d | feat(domain): add Delivery entity and status enumeration for logistics | Daroh19 | 2026-05-12 |
| fruitlogix-webapp | feature/profiles-and-vehicles | 38fda5a | feat: add User entity definition for Profiles & Vehicles context | ECEB0704 | 2026-05-12 |
| fruitlogix-webapp | feature/i18n | 0a9b722 | feat: add language switcher component for locale selection | johancg04 | 2026-05-12 |
| fruitlogix-webapp | feature/profiles-and-vehicles | d66dcfe | feat: add Producer entity definition for Profiles & Vehicles context | ECEB0704 | 2026-05-12 |
| fruitlogix-webapp | feature/profiles-and-vehicles | 10defbd | feat: add Driver entity definition for Profiles & Vehicles context | ECEB0704 | 2026-05-12 |
| fruitlogix-webapp | feature/profiles-and-vehicles | eeda93f | feat: add entity definitions for Driver, Producer, User, and Vehicle | ECEB0704 | 2026-05-12 |
| fruitlogix-webapp | feature/shared | f39bdae | feat: add BaseEndpoint class for RESTful API interactions | johancg04 | 2026-05-12 |
| fruitlogix-webapp | feature/shared | f4d5ed1 | feat: add BaseApi class with pre-configured Axios instance | johancg04 | 2026-05-12 |
| fruitlogix-webapp | feature/profiles-and-vehicles | b88ccd4 | feat: implement Profiles & Vehicles store with CRUD operations for producers | ECEB0704 | 2026-05-12 |
| fruitlogix-webapp | feature/profiles-and-vehicles | 7458826 | feat: add producer form validation logic | ECEB0704 | 2026-05-12 |
| fruitlogix-webapp | feature/payment-management | c3e58b1 | feat: implement payment management views and entities | Sergi9017 | 2026-05-12 |
| fruitlogix-webapp | feature/iot-infrastructure | 095f843 | feat(routes): add IoT infrastructure routes for device management and calibration | ECEB0704 | 2026-05-12 |
| fruitlogix-webapp | feature/logistics-monitoring | f4d217c | feat(application): add logistics monitoring store for managing deliveries and tracking | Daroh19 | 2026-05-12 |
| fruitlogix-webapp | feature/iot-infrastructure | fc36c0a | feat(ui): create IoT device fleet management view with real-time tracking and calibration | ECEB0704 | 2026-05-12 |
| fruitlogix-webapp | feature/iot-infrastructure | 1cc581b | feat(ui): add placeholder view for IoT infrastructure overview | ECEB0704 | 2026-05-12 |
| fruitlogix-webapp | feature/iot-infrastructure | 44f1f19 | feat(ui): add IoT calibration view for device monitoring and rule configuration | ECEB0704 | 2026-05-12 |
| fruitlogix-webapp | feature/order-management | 65588a1 | feat: add lazy-loaded route definitions for order management | johancg04 | 2026-05-12 |
| fruitlogix-webapp | feature/iot-infrastructure | 6485700 | feat(ui): implement device-card component for IoT device display | ECEB0704 | 2026-05-12 |
| fruitlogix-webapp | feature/order-management | 8b139ff | feat: add ordering module with OrderList component for order management | johancg04 | 2026-05-12 |
| fruitlogix-webapp | feature/dashboard | 9bb52ac | docs(dashboard): add router.js | gonzalojaimeforcelledo | 2026-05-12 |
| fruitlogix-webapp | feature/order-management | a97456b | feat: add OrderSuccess component for displaying order confirmation in order management | johancg04 | 2026-05-12 |
| fruitlogix-webapp | feature/order-management | 89f897d9 | feat: add OrderStateDialog component for tracking order status in order management | johancg04 | 2026-05-12 |
| fruitlogix-webapp | feature/order-management | 062f2bc | feat: add OrderRegisterForm component for creating new orders in order management | johancg04 | 2026-05-12 |
| fruitlogix-webapp | feature/iot-infrastructure | 2a54e4d | feat(infra): implement SensorReading assembler for DTO transformation | ECEB0704 | 2026-05-12 |
| fruitlogix-webapp | feature/iot-infrastructure | 996b346 | feat(infra): add IoT infrastructure API service for external communication | ECEB0704 | 2026-05-12 |
| fruitlogix-webapp | feature/order-management | 4e8d46a | feat: enhance order management with order list component and PrimeVue integration | johancg04 | 2026-05-12 |
| fruitlogix-webapp | feature/iot-infrastructure | 0ea34bd | feat(infra): implement IoTDevice assembler for data mapping | ECEB0704 | 2026-05-12 |
| fruitlogix-webapp | feature/iot-infrastructure | cb5ee5d | feat(domain): create ThresholdRule entity for sensor limits | ECEB0704 | 2026-05-12 |
| fruitlogix-webapp | feature/order-management | 5c0afd9 | feat: add OrderEditDialog component for editing order details in order management | johancg04 | 2026-05-12 |
| fruitlogix-webapp | feature/order-management | 6ee5893 | feat: add FruitSelector component for selecting fruits in order management | johancg04 | 2026-05-12 |
| fruitlogix-webapp | feature/iot-infrastructure | a7eb430 | feat(domain): implement Sensor entity core structure define SensorReading entity for data collection | ECEB0704 | 2026-05-12 |
| fruitlogix-webapp | feature/dashboard | b4e0611 | docs(dashboard): add pinia.js | gonzalojaimeforcelledo | 2026-05-12 |
| fruitlogix-webapp | feature/order-management | ae914ed | feat: add AssignProducerDialog component for producer assignment in order management | johancg04 | 2026-05-12 |
| fruitlogix-webapp | feature/dashboard | 59b9f76 | docs(dashboard): add dashboard.store.js | gonzalojaimeforcelledo | 2026-05-12 |
| fruitlogix-webapp | feature/iot-infrastructure | a854d10 | feat(domain): add IoT enums for device states and types | ECEB0704 | 2026-05-12 |
| fruitlogix-webapp | feature/order-management | 418f1fc | feat: implement OrderManagementApi for CRUD operations on orders and related resources | johancg04 | 2026-05-12 |
| fruitlogix-webapp | feature/iot-infrastructure | 465256015 | feat(domain): create IoTDevice entity to represent physical hardware | ECEB0704 | 2026-05-12 |
| fruitlogix-webapp | feature/dashboard | efc4a7f | docs(dashboard): add dashboard-stats.entity.js | gonzalojaimeforcelledo | 2026-05-12 |
| fruitlogix-webapp | feature/iot-infrastructure | 323e2ca | feat(domain): define AlertRule entity for monitoring logic | ECEB0704 | 2026-05-12 |
| fruitlogix-webapp | feature/order-management | 6da92b3 | feat: add OrderAssembler for mapping Order entities to/from API payloads | johancg04 | 2026-05-12 |
| fruitlogix-webapp | feature/dashboard | 75806fa | docs(dashboard): add dashboard.assembler.js | gonzalojaimeforcelledo | 2026-05-12 |
| fruitlogix-webapp | feature/order-management | b40b473 | feat: implement order and fruit entities with order management store | johancg04 | 2026-05-12 |
| fruitlogix-webapp | feature/iot-infrastructure | 249b978 | feat(domain): define core models and business entities | ECEB0704 | 2026-05-12 |
| fruitlogix-webapp | feature/dashboard | 32c36ff | docs(dashboard): add dashboard-api.js | gonzalojaimeforcelledo | 2026-05-12 |
| fruitlogix-webapp | feature/iot-infrastructure | 35e27cd | chore: initial commit | ECEB0704 | 2026-05-12 |
| fruitlogix-webapp | feature/order-management | 55e162b | feat: add order form validation logic | johancg04 | 2026-05-12 |
| fruitlogix-webapp | feature/dashboard | b62605c | docs(dashboard): add dashboard-view.vue | gonzalojaimeforcelledo | 2026-05-12 |
| fruitlogix-webapp | develop | d08c2d8 | feat: initialize Vue.js project with basic structure and configuration | johancg04 | 2026-05-12 |
| fruitlogix-webapp | develop | 5b81dd5 | chore: initial commit | johancg04 | 2026-05-12 |