## Capítulo V: Product Implementation, Validation & Deployment
### 5.1. Software Configuration Management
#### 5.1.1. Software Development Environment Configuration
Con el objetivo de garantizar un desarrollo fluido, estandarizado y consistente entre todos los miembros del equipo DeverlopersTeam, se ha definido el siguiente entorno de desarrollo para el ecosistema FruitLogix:

| Actividad                              | Producto                 | Propósito / Uso                                                                 |
|---------------------------------------|--------------------------|----------------------------------------------------------------------------------|
| Project Management                    | Trello                   | Gestión del Product Backlog, planificación de Sprints y seguimiento de tareas.  |
| Requirements Management               | UXPressia                | Elaboración de artefactos de descubrimiento (User Personas, Empathy Maps, Journey Maps) para la definición de requisitos. |
| UX/UI Design                          | Figma                    | Diseño de la guía de estilo, prototipos de baja fidelidad (wireframes) y alta fidelidad (mockups). |
| User Flows & Wireflows                | LucidChart               | Elaboración de Wireflows y User Flows.                                          |
| Class Diagrams & Data Base Design     | PlantUML                 | Elaboración de diagramas de clases y diseño de base de datos.                   |
| Software Development (Backend)        | JetBrains Rider          | IDE para el desarrollo de Web Services bajo estilo RESTful utilizando ASP.NET Core y C#. |
| Software Development (Frontend)       | JetBrains WebStorm       | IDE para el desarrollo de la Web Application con Vue Framework, PrimeVue (HTML5, CSS3, JS). |
| Software Development (Landing Page)   | Visual Studio Code       | IDE para el desarrollo de la Landing Page con HTML5, CSS y JS.                  |
| Version Control                       | GitHub                   | Alojamiento de repositorios y gestión de versiones aplicando GitFlow y Conventional Commits. |
| Documentation                         | Markdown                 | Documentación del reporte del proyecto.                                         |

#### 5.1.2. Source Code Management

El código fuente del proyecto se gestionará utilizando **Git** como sistema de control de versiones y **GitHub** como plataforma de alojamiento, bajo una organización pública. Se adoptará un enfoque estructurado que favorezca la colaboración, la modularidad y el despliegue continuo mediante repositorios independientes para cada componente del sistema.

#### Estrategia de Ramas (GitFlow)

Se implementará un flujo de trabajo basado en GitFlow con el objetivo de garantizar la estabilidad y trazabilidad del desarrollo:

- **main**: Rama principal que contiene únicamente código estable, probado y desplegado en producción. Cada versión liberada deberá estar debidamente etiquetada.

- **develop**: Rama de integración continua donde se consolidan los avances del desarrollo antes de su liberación a producción.

- **feature/[nombre]**: Ramas temporales creadas a partir de *develop* para el desarrollo de nuevas funcionalidades o User Stories  
  (ej. *feature/order-registration*). Una vez finalizadas, se integran nuevamente a *develop* mediante un Pull Request (PR).

- **hotfix/[nombre]**: Ramas destinadas a la corrección de errores críticos detectados en producción (*main*), que requieren una solución inmediata.

#### Convención de Commits (Conventional Commits)

Para mantener un historial claro, consistente y facilitar la generación automática de *changelogs*, todos los commits deberán seguir el estándar de **Conventional Commits**:

#### Tipos permitidos

- **feat**: Nueva funcionalidad  
  (ej. *feat(ordering): add automated order validation policy*)

- **fix**: Corrección de errores  
  (ej. *fix(auth): resolve token expiration on mobile devices*)

- **docs**: Cambios en documentación  
  (ej. *docs(interviews): update stakeholder interview records*)

- **style**: Cambios de formato que no afectan la lógica del código (espacios, indentación, etc.)

#### 5.1.3. Source Code Style Guide & Conventions

Para garantizar la legibilidad, mantenibilidad y calidad del código en todo el equipo de desarrollo de FruitLogix, se adoptan las siguientes guías de estilo:

#### Para el Frontend (Vue / JavaScript)

Se seguirán buenas prácticas alineadas al ecosistema de Vue y la guía oficial de estilo.

**Nomenclatura:**
- Componentes: PascalCase (ej. `OrderCard.vue`)
- Variables y funciones: camelCase (ej. `getOrderList`)
- Archivos: kebab-case (ej. `order-list.component.vue`)

**Estructura:**
- Separación clara por carpetas: `components`, `views`, `services`, `store`.
- Uso de componentes reutilizables para mantener la modularidad.

**Formateo:**
- Uso de Prettier con indentación de 2 espacios.
- Uso de ESLint para mantener consistencia y evitar malas prácticas en JavaScript.

#### Para el Backend (ASP.NET Core / C#)

Se adoptarán las convenciones estándar de C# y buenas prácticas de desarrollo en .NET.

**Nomenclatura:**
- Clases y métodos: PascalCase (ej. `OrderService`, `GetOrders`)
- Variables: camelCase (ej. `orderList`)
- Interfaces: prefijo `I` (ej. `IOrderRepository`)

**Arquitectura:**
- Separación en capas:
    - Controllers
    - Services
    - Repositories
    - Models (Entities / DTOs)
- Aplicación del principio de responsabilidad única (SRP).

**APIs RESTful:**
- Uso de sustantivos en plural para endpoints.
- Uso correcto de métodos HTTP:
    - `GET` → obtener recursos
    - `POST` → crear recursos
    - `PUT/PATCH` → actualizar recursos
    - `DELETE` → eliminar recursos


#### 5.1.4. Software Deployment Configuration
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