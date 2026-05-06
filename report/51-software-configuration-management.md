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
En esta sección se describe la configuración del despliegue de la solución FruitLogix, detallando los pasos necesarios para publicar los productos digitales a partir de sus repositorios de código fuente.

Para el presente proyecto, el despliegue se realiza utilizando GitHub como plataforma de alojamiento, aprovechando el servicio de **GitHub Pages** para la publicación de contenido estático.

#### Landing Page

El despliegue de la Landing Page y del reporte del proyecto se realiza mediante GitHub Pages, siguiendo los siguientes pasos:

1. Creación del repositorio en GitHub bajo la organización del equipo.
2. Configuración de la rama de despliegue (main o gh-pages).
3. Subida del código fuente mediante commits y push al repositorio remoto.
4. Activación de GitHub Pages desde la configuración del repositorio.
5. Selección de la rama y carpeta raíz como fuente de publicación.
6. Generación automática de la URL pública del sitio.

Una vez configurado, cada actualización enviada al repositorio se refleja automáticamente en la versión publicada del sitio.

#### Consideraciones

- El despliegue está orientado a contenido estático (HTML, CSS, JavaScript).
- No se requiere infraestructura adicional ni servidores externos.
- El acceso al sitio es público mediante una URL generada por GitHub Pages.