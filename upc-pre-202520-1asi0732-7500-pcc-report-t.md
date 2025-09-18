# Capítulo V: Product Implementation

### 5.1. Software Configuration Management

En esta sección se establecen las decisiones técnicas y convenciones fundamentales adoptadas para garantizar la consistencia y calidad durante todo el ciclo de vida del proyecto Quadrapp. Abarcamos tres aspectos cruciales: la gestión efectiva del código fuente, la configuración estandarizada del entorno de desarrollo y el proceso robusto de despliegue. Como ejes transversales, implementamos principios de internacionalización (i18n) y accesibilidad (a11y) en todos los componentes del sistema.

### 5.1.1. Software Development Environment Configuration

A continuación, presentamos el ecosistema completo de herramientas y tecnologías seleccionadas estratégicamente por el equipo. Cada elemento ha sido escogido considerando su propósito específico, integración con el flujo de trabajo y facilidad de uso. Se incluyen las rutas de referencia o descarga para asegurar la consistencia en la configuración del entorno de desarrollo:

#### Herramientas de Gestión y Diseño

- **Project Management**

  - Trello ([https://trello.com](https://trello.com))
  - Propósito: Gestión ágil de tareas y sprints

  <BR>
  
  <img src="assets/chapter-5-5.1/trello.png" alt="Trello" width="150"/>
  <br>

- **Product UX/UI Design**

  - Figma ([https://figma.com](https://figma.com))
  - Propósito: Prototipado y diseño de interfaces
<BR>
  <img src="assets/chapter-5-5.1/figma.png" alt="Figma" width="150"/>

- **Software Architecture**

  - Structurizr ([https://structurizr.com](https://structurizr.com))
  - Vertabelo ([https://vertabelo.com](https://vertabelo.com))
  - Propósito: Modelado de arquitectura y base de datos
<BR>
  <img src="assets/chapter-5-5.1/structurizr.png" alt="Structurizr" width="150"/>


#### Herramientas de UX Research

- **Investigación de Usuario**
  - UXPressia ([https://uxpressia.com](https://uxpressia.com))
  - Propósito: Creación de Personas, Empathy Maps, Journey Maps e Impact Maps
  - Alcance: Investigación y análisis de usuarios
<br>

- **Mapeo de Escenarios**
  - LucidChart ([https://lucidchart.com](https://lucidchart.com))
  - Miro ([https://miro.com](https://miro.com))
  - Propósito: Visualización de escenarios de usuario y flujos de trabajo
<br>

- **Flujos de Usuario**
  - LucidChart ([https://lucidchart.com](https://lucidchart.com))
  - Overflow ([https://overflow.io](https://overflow.io))
  - Propósito: Documentación de Wireflows y User Flows interactivos

#### Herramientas de Desarrollo

- **Entorno de Desarrollo**
  - Visual Studio Code ([https://code.visualstudio.com](https://code.visualstudio.com))
  - Propósito: IDE principal con soporte para múltiples lenguajes y extensiones
<br>

- **Stack Frontend**
  - Node.js ([https://nodejs.org](https://nodejs.org))
  - Propósito: Runtime JavaScript y gestión de dependencias frontend
<br>

- **Stack Backend**
  - Java JDK 17+ ([https://adoptium.net](https://adoptium.net))
  - Spring Boot ([https://spring.io/projects/spring-boot](https://spring.io/projects/spring-boot))
  - Propósito: Desarrollo de APIs RESTful y lógica de negocio
<br>

- **Virtualización**
  - Docker Desktop ([https://www.docker.com/products/docker-desktop](https://www.docker.com/products/docker-desktop))
  - Propósito: Contenedorización y orquestación de servicios

#### Herramientas de Testing

- **Testing Frontend**
  - Jest ([https://jestjs.io](https://jestjs.io))
  - Propósito: Framework de testing unitario para JavaScript/TypeScript
<br>

- **Testing Backend**
  - JUnit ([https://junit.org](https://junit.org))
  - Propósito: Framework de testing unitario para Java

#### Herramientas de Despliegue

- **Plataforma Cloud**
  - Azure Portal ([https://portal.azure.com](https://portal.azure.com))
  - Propósito: Infraestructura y servicios cloud
  <img src="assets/chapter-5-5.1/azure.png" alt="Azure" width="150"/>
<br>

- **Automatización CI/CD**
  - GitHub Actions ([https://github.com/features/actions](https://github.com/features/actions))
  - Propósito: Pipelines de integración y despliegue continuo
  <img src="assets/chapter-5-5.1/github-actions.png" alt="GitHub Actions" width="150"/>

#### Herramientas de Documentación

- **Documentación de Código**
  - Markdown ([https://www.markdownguide.org](https://www.markdownguide.org))
  - Propósito: Documentación técnica y guías de desarrollo
<br>

- **Documentación Visual**
  - Draw.io ([https://app.diagrams.net](https://app.diagrams.net))
  - Propósito: Diagramas técnicos y de arquitectura
<br>

- **Documentación de API**
  - Swagger/OpenAPI ([https://swagger.io](https://swagger.io))
  - Propósito: Documentación interactiva de endpoints REST

## 5.1.2. Source Code Management

La gestión del código fuente se centraliza en GitHub, implementando un sistema robusto de control de versiones bajo la organización [Experiemtos-SI0732-Group-3-PCC-Team](https://github.com/Experiemtos-SI0732-Group-3-PCC-Team). Esta estructura nos permite mantener un flujo de trabajo colaborativo y organizado:

- **Repositorios:**
  - [Quadrapp-Backend](https://github.com/Experiemtos-SI0732-Group-3-PCC-Team/Quadrapp-Backend)
  - [Quadrapp-Frontend-Web](https://github.com/Experiemtos-SI0732-Group-3-PCC-Team/Quadrapp-Frontend-Web)
  - [Quadrapp-Frontend-Mobile](https://github.com/Experiemtos-SI0732-Group-3-PCC-Team/Quadrapp-Frontend-Mobile)
  - [Landing-Page-Quadrapp](https://github.com/Experiemtos-SI0732-Group-3-PCC-Team/Landing-Page-Quadrapp)
  - [Final-Project-Documentation-Report](https://github.com/Experiemtos-SI0732-Group-3-PCC-Team/Final-Project-Documentation-Report)
  <br>

- **Workflow GitFlow:** 
 
  - Ramas principales: `main` (producción), `develop` (integración).
  - Ramas de features: `feature/nombre-descriptivo`.
  - Ramas de releases: `release/x.y.z` (Semantic Versioning 2.0.0).
  - Ramas de hotfixes: `hotfix/x.y.z`.
  - Convenciones de commits: Conventional Commits (ejemplo: `feat: add booking API`, `fix: correct payment bug`).

  <BR>
<img src="assets/chapter-5-5.1/gitflow.png" alt="GitFlow" width="350"/>

### 5.1.3. Source Code Style Guide & Conventions

Para mantener la consistencia y calidad del código a través de todo el proyecto, hemos adoptado un conjunto integral de guías de estilo y convenciones estandarizadas. Estas normas facilitan la colaboración efectiva entre los miembros del equipo y aseguran la mantenibilidad del código:

- **HTML/CSS:** Google HTML/CSS Style Guide.
- **JavaScript:** Google JavaScript Style Guide, MDN JavaScript guidelines, ESLint.
- **Java:** Google Java Style Guide, Spring Boot Best Practices, Checkstyle.
- **Gherkin:** Gherkin Conventions for Readable Specifications.
- **Nomenclatura:** Todo el código y los identificadores se escriben en inglés.
- **Internacionalización (i18n):** Todos los productos soportan inglés (en_US) y español latinoamericano (es_419) como idiomas configurables. El idioma por defecto es inglés.
- **Accesibilidad (a11y):** Se implementan atributos ARIA y buenas prácticas de accesibilidad en Landing Page y Frontend Web Applications.
- **Herramientas de linting:** ESLint para JavaScript, Checkstyle para Java.

### 5.1.4. Software Deployment Configuration

La estrategia de despliegue de Quadrapp ha sido diseñada para garantizar un proceso confiable, seguro y automatizado. Implementamos una arquitectura cloud-native que asegura alta disponibilidad y escalabilidad, mientras mantenemos la integración consistente de internacionalización (i18n) y accesibilidad (a11y) en todos los componentes del sistema:

#### Configuración de Entornos

- **Desarrollo Local**
  - Tecnología: Docker Desktop
  - Propósito: Estandarización del entorno de desarrollo
  - Beneficios: Consistencia entre desarrolladores y aislamiento de dependencias
<br>

- **Staging**
  - Plataforma: Azure App Service
  - Propósito: Validación de cambios previa a producción
  - Características: Entorno espejo de producción para pruebas de integración
<br>

- **Producción**
  - Plataforma: Azure App Service y GitHub Pages
  - Propósito: Despliegue de aplicaciones en producción
  - Configuración: Alta disponibilidad y escalado automático

#### Pipeline de CI/CD

- **Automatización**
  - Tecnología: GitHub Actions
  - Propósito: Integración y despliegue continuo
  - Repositorios con Pipelines:
    - [Quadrapp-Backend](https://github.com/Experiemtos-SI0732-Group-3-PCC-Team/Quadrapp-Backend) - Servicios REST
    - [Quadrapp-Frontend-Web](https://github.com/Experiemtos-SI0732-Group-3-PCC-Team/Quadrapp-Frontend-Web) - Aplicación Web
    - [Quadrapp-Frontend-Mobile](https://github.com/Experiemtos-SI0732-Group-3-PCC-Team/Quadrapp-Frontend-Mobile) - App Móvil
    - [Landing-Page-Quadrapp](https://github.com/Experiemtos-SI0732-Group-3-PCC-Team/Landing-Page-Quadrapp) - Página Principal

#### Componentes del Sistema

- **Landing Page**
  - Plataforma: GitHub Pages
  - Características:
    - Soporte multilenguaje (en_US, es_419)
    - Accesibilidad WCAG 2.1
    - Optimización SEO
  <img src="assets/chapter-5-5.1/github-pages.png" alt="Landing Page Deployment" width="150"/>
<br>

- **Frontend (Web y Mobile)**
  - Tecnologías: Node.js/Vue CLI
  - Plataforma: Azure Static Web Apps
  - Características:
    - Interfaces adaptativas
    - Internacionalización i18n
    - Accesibilidad ARIA
  <img src="assets/chapter-5-5.1/azure-static-web-apps.png" alt="Frontend Deployment" width="150"/>
<br>

- **Backend (Web Services)**
  - Framework: Spring Boot
  - Plataforma: Azure App Service
  - Características:
    - APIs RESTful documentadas
    - Mensajes multilenguaje
    - Logging estructurado
  <img src="assets/chapter-5-5.1/azure-app-service.png" alt="Backend Deployment" width="150"/>

#### Seguridad y Monitoreo

- **Gestión de Secretos**
  - Herramienta: Azure Key Vault
  - Alcance: Credenciales y configuraciones sensibles
  - Integración: Variables de entorno en CI/CD
<br>

- **Control de Versiones**
  - Sistema: Git tags y releases
  - Capacidad: Rollback automático
  - Estrategia: Blue-Green Deployment
<br>

- **Observabilidad**
  - Plataforma: Azure Application Insights
  - Características:
    - Monitoreo en tiempo real
    - Alertas automatizadas
    - Análisis de rendimiento

#### Gestión de Documentación

- **Documentación Técnica**
  - Formato: Markdown
  - Ubicación: Repositorio centralizado
  - Repositorio: [Final-Project-Documentation-Report](https://github.com/Experiemtos-SI0732-Group-3-PCC-Team/Final-Project-Documentation-Report)
  - Alcance:
    - Guías de desarrollo
    - Procedimientos de despliegue
    - Documentación de arquitectura

Esta arquitectura de despliegue integral garantiza que Quadrapp opere de manera segura, inclusiva y eficiente. La automatización de procesos, junto con las prácticas de DevOps implementadas, asegura despliegues consistentes y repetibles, minimizando errores humanos y facilitando la recuperación ante posibles incidencias. La monitorización continua y la gestión centralizada de la configuración nos permiten mantener un alto nivel de calidad y disponibilidad en todos los componentes del sistema.
