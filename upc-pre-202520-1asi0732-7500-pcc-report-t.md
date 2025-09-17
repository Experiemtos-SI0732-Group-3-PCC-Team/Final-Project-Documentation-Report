# Capítulo V: Product Implementation

### 5.1. Software Configuration Management.

Esta sección establece las decisiones y convenciones para mantener la consistencia durante el ciclo de vida del proyecto Quadrapp. Incluye la gestión del código fuente, la configuración del entorno de desarrollo y el proceso de despliegue, considerando internacionalización (i18n) y accesibilidad (a11y) como principios transversales.

### 5.1.1. Software Development Environment Configuration. 

A continuación se detallan los productos de software utilizados por el equipo, su propósito y la ruta de referencia o descarga:

- **Project Management:** Trello (https://trello.com) – Gestión de tareas y sprints.
  <img src="assets/chapter-5-5.1/trello.png" alt="Trello" width="150"/>
- **Product UX/UI Design:** Figma (https://figma.com) – Prototipado y diseño de interfaces.
  <img src="assets/chapter-5-5.1/figma.png" alt="Figma" width="150"/>
- **Software Architecture:** Structurizr ([enlace](https://structurizr.com)), Vertabelo ([enlace](https://vertabelo.com))  
  <img src="assets/chapter-5-5.1/structurizr.png" alt="Structurizr" width="150"/>

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
      <img src="assets/chapter-5-5.1/azure.png" alt="Azure" width="150"/>
  - GitHub Actions (https://github.com/features/actions) – Integración y despliegue continuo.
      <img src="assets/chapter-5-5.1/github-actions.png" alt="GitHub Actions" width="150"/>
- **Software Documentation:** 
  - Markdown (https://www.markdownguide.org) – Documentación técnica.
  - Draw.io (https://app.diagrams.net) – Diagramas de arquitectura.
  - Swagger/OpenAPI (https://swagger.io) – Documentación de APIs RESTful.

## 5.1.2. Source Code Management.

El control de versiones se realiza con GitHub, bajo la organización [Experiemtos-SI0732-Group-3-PCC-Team](https://github.com/Experiemtos-SI0732-Group-3-PCC-Team):

- **Repositorios:**
  - [Quadrapp-Backend](https://github.com/Experiemtos-SI0732-Group-3-PCC-Team/Quadrapp-Backend)
  - [Quadrapp-Frontend-Web](https://github.com/Experiemtos-SI0732-Group-3-PCC-Team/Quadrapp-Frontend-Web)
  - [Quadrapp-Frontend-Mobile](https://github.com/Experiemtos-SI0732-Group-3-PCC-Team/Quadrapp-Frontend-Mobile)
  - [Landing-Page-Quadrapp](https://github.com/Experiemtos-SI0732-Group-3-PCC-Team/Landing-Page-Quadrapp)
  - [Final-Project-Documentation-Report](https://github.com/Experiemtos-SI0732-Group-3-PCC-Team/Final-Project-Documentation-Report)

- **Workflow GitFlow:**  
  <img src="assets/chapter-5-5.1/gitflow.png" alt="GitFlow" width="350"/>
  - Ramas principales: `main` (producción), `develop` (integración).
  - Ramas de features: `feature/nombre-descriptivo`.
  - Ramas de releases: `release/x.y.z` (Semantic Versioning 2.0.0).
  - Ramas de hotfixes: `hotfix/x.y.z`.
  - Convenciones de commits: Conventional Commits (ejemplo: `feat: add booking API`, `fix: correct payment bug`).


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

El despliegue de Quadrapp se realiza de la siguiente manera, asegurando la integración de internacionalización (i18n) y accesibilidad (a11y) en todos los productos:

- **Entornos:** 
  - **Desarrollo local:** Uso de Docker para estandarizar el entorno de desarrollo.
  - **Staging:** Azure App Service para pruebas previas a producción.
  - **Producción:** Azure App Service para backend y frontend, GitHub Pages para Landing Page.

- **CI/CD:** GitHub Actions automatiza la construcción, pruebas y despliegue de cada producto. Los pipelines están definidos en cada repositorio:
  - [Quadrapp-Backend](https://github.com/Experiemtos-SI0732-Group-3-PCC-Team/Quadrapp-Backend)
  - [Quadrapp-Frontend-Web](https://github.com/Experiemtos-SI0732-Group-3-PCC-Team/Quadrapp-Frontend-Web)
  - [Quadrapp-Frontend-Mobile](https://github.com/Experiemtos-SI0732-Group-3-PCC-Team/Quadrapp-Frontend-Mobile)
  - [Landing-Page-Quadrapp](https://github.com/Experiemtos-SI0732-Group-3-PCC-Team/Landing-Page-Quadrapp)

- **Landing Page:** 
  - Desplegada en GitHub Pages, asegurando soporte i18n (en_US, es_419) y a11y (atributos ARIA, contraste, navegación por teclado).
  - ![Landing Page Deployment](assets/chapter-5-5.1/github-pages.png)

- **Frontend Web y Mobile:** 
  - Build con Node.js/Vue CLI, despliegue en Azure Static Web Apps.
  - Soporte i18n y a11y implementado en la interfaz de usuario.
  - ![Frontend Deployment](assets/chapter-5-5.1/azure-static-web-apps.png)

- **Backend (Web Services):** 
  - Build y pruebas con Java Spring Boot, despliegue en Azure App Service.
  - Documentación de API con Swagger/OpenAPI, mensajes de error multilenguaje.
  - ![Backend Deployment](assets/chapter-5-5.1/azure-app-service.png)

- **Variables sensibles:** Gestionadas con Azure Key Vault y variables de entorno en los pipelines de GitHub Actions.

- **Rollback:** Versionado de despliegues y rollback automático en caso de error.

- **Monitoreo:** Azure Application Insights para trazabilidad y alertas.

- **Documentación:** Todo el ciclo de vida y la documentación técnica se gestiona en Markdown dentro del repositorio central:  
  [Final-Project-Documentation-Report](https://github.com/Experiemtos-SI0732-Group-3-PCC-Team/Final-Project-Documentation-Report)

Esta configuración asegura un despliegue seguro, inclusivo, repetible y eficiente para todos los componentes de Quadrapp.