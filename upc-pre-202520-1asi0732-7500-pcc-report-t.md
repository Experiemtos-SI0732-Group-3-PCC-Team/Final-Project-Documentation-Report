# Capítulo V: Product Implementation

### 5.1. Software Configuration Management.

Esta sección establece las decisiones y convenciones para mantener la consistencia durante el ciclo de vida del proyecto Quadrapp. Incluye la gestión del código fuente, la configuración del entorno de desarrollo y el proceso de despliegue, considerando internacionalización (i18n) y accesibilidad (a11y) como principios transversales.

### 5.1.1. Software Development Environment Configuration. 

A continuación se detallan los productos de software utilizados por el equipo, su propósito y la ruta de referencia o descarga:

- **Project Management:** Trello (https://trello.com) – Gestión de tareas y sprints.
- **Requirements Management:** Google Drive (https://drive.google.com) – Documentación y almacenamiento colaborativo.
- **Product UX/UI Design:** Figma (https://figma.com) – Prototipado y diseño de interfaces.
- **Personas, Empathy Maps, Journey Maps, Impact Maps:** UXPressia (https://uxpressia.com)
- **Scenario Maps:** LucidChart (https://lucidchart.com) / Miro (https://miro.com)
- **Wireflows y User Flows:** LucidChart / Overflow (https://overflow.io)
- **Software Architecture Diagrams:** Structurizr (https://structurizr.com) para C4 Model, LucidChart para UML, Vertabelo (https://vertabelo.com) para diseño de base de datos.
- **Software Development:** 
  - Visual Studio Code (https://code.visualstudio.com) – Editor principal de código.
  - Node.js (https://nodejs.org) – Entorno de ejecución para JavaScript y herramientas de frontend.
  - Java JDK 17+ (https://adoptium.net) – Desarrollo de servicios backend con Spring Boot.
  - Spring Boot (https://spring.io/projects/spring-boot) – Framework para desarrollo de Web Services en Java.
  - Docker Desktop (https://www.docker.com/products/docker-desktop) – Contenedores para desarrollo y pruebas locales.
- **Software Testing:** 
  - Jest (https://jestjs.io) – Pruebas unitarias para frontend.
  - JUnit (https://junit.org) – Pruebas unitarias para backend Java.
- **Software Deployment:** 
  - Azure Portal (https://portal.azure.com) – Despliegue en la nube.
  - GitHub Actions (https://github.com/features/actions) – Integración y despliegue continuo.
- **Software Documentation:** 
  - Markdown (https://www.markdownguide.org) – Documentación técnica.
  - Draw.io (https://app.diagrams.net) – Diagramas de arquitectura.
  - Swagger/OpenAPI (https://swagger.io) – Documentación de APIs RESTful.

## 5.1.2. Source Code Management.

El control de versiones se realiza con GitHub, utilizando la siguiente organización:

- **Repositorios:**
  - Landing Page: [https://github.com/Quadrapp/landing-page](https://github.com/Quadrapp/landing-page)
  - Web Services: [https://github.com/Quadrapp/web-services](https://github.com/Quadrapp/web-services)
  - Frontend Web Application: [https://github.com/Quadrapp/frontend-app](https://github.com/Quadrapp/frontend-app)

- **Workflow GitFlow:**
  - Ramas principales: `main` (producción), `develop` (integración).
  - Ramas de features: `feature/nombre-descriptivo`.
  - Ramas de releases: `release/x.y.z` (siguiendo Semantic Versioning 2.0.0).
  - Ramas de hotfixes: `hotfix/x.y.z`.
  - Convenciones de commits: Se utiliza Conventional Commits (por ejemplo, `feat: add booking API`, `fix: correct payment bug`).

### 5.1.3. Source Code Style Guide & Conventions.

Se adoptan las siguientes guías y convenciones:

- **HTML/CSS:** Google HTML/CSS Style Guide.
- **JavaScript:** Google JavaScript Style Guide, MDN JavaScript guidelines, ESLint.
- **Java:** Google Java Style Guide, Spring Boot Best Practices, Checkstyle.
- **Gherkin:** Gherkin Conventions for Readable Specifications.
- **Nomenclatura:** Todo el código y los identificadores se escriben en inglés.
- **Internacionalización (i18n):** Todos los productos soportan inglés (en_US) y español latinoamericano (es_419) como idiomas configurables. El idioma por defecto es inglés.
- **Accesibilidad (a11y):** Se implementan atributos ARIA y buenas prácticas de accesibilidad en Landing Page y Frontend Web Applications.
- **Herramientas de linting:** ESLint para JavaScript, Checkstyle para Java.

### 5.1.4. Software Deployment Configuration. 

El despliegue de Quadrapp se realiza de la siguiente manera:

- **Entornos:** Desarrollo local (Docker), Staging (Azure), Producción (Azure).
- **CI/CD:** GitHub Actions automatiza la construcción, pruebas y despliegue de cada producto.
- **Landing Page y Frontend:** Build con Node.js/Vue CLI, despliegue en Azure Static Web Apps. Se asegura soporte i18n y a11y.
- **Web Services:** Build y pruebas con Spring Boot, despliegue en Azure App Service. Documentación de API con Swagger/OpenAPI y soporte i18n en mensajes de error y respuestas.
- **Variables sensibles:** Gestionadas con Azure Key Vault y variables de entorno.
- **Rollback:** Versionado de despliegues y rollback automático en caso de error.
- **Monitoreo:** Azure Application Insights para trazabilidad y alertas.

Esta configuración asegura un despliegue seguro, inclusivo, repetible y eficiente para todos los componentes de Quadrapp.