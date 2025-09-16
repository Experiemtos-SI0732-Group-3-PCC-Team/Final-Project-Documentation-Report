# <center>COURSE PROJECT</center>

<p align="center">
    <strong>Universidad Peruana de Ciencias Aplicadas</strong><br>
    <img src="https://upload.wikimedia.org/wikipedia/commons/f/fc/UPC_logo_transparente.png"></img><br>
    <strong>Ingeniería de Software</strong><br>
    <strong>Curso: Diseño de Experimentos de Ingeniería de Software</strong><br>
    <strong>Profesor: Ivan Robles Fernández </strong><br>
    <br>INFORME TRABAJO FINAL
</p>

<center>

#### Startup: **PCC**
#### Product: **Quadrapp**

</center>

### <center>Team  Members:</center>
<center>

| Codigo                           | Miembro       |
|----------------------------------|------------|
|  U20211G163 | Solis Solis, Leonardo José|
|  U202215462 | Nanfuñay Liza, Pedro Jesús|
|  U202121935 | Calisaya Sánchez, Juan Jesús|
|  U202213423 | Oneglio De Paz, Beth Shantal|
|  U202121975 | Lagos Aguilar, Luis Eduardo|

<br> AGOSTO 2025
</center>  
<div style="page-break-after: always;"></div>

# Registro de Versiones del Informe
<center>

| Version | Fecha | Autor | Descripcion de Modificacion |
| ----------- | ----------- | ----------- | ----------- |
| 0.0 | 01/09/2025 |Grupo 1 |Se crea el documento |  

</center>

# Project Report Collaboration Insights
[URL del repositorio](https://www.example.com)

(Imagenes de los commits cada entrega)


# Contenido



[Registro de Versiones del Informe](#registro-de-versiones-del-informe)

[Project Report Collaboration Insights](#project-report-collaboration-insights)

[Student Outcome](#student-outcome)

[Capítulo I: Introducción](#capítulo-i-introducción)

[1.1 Startup Profile](#11-startup-profile)  
[1.1.1. Descripción de la Startup](#111-descripción-de-la-startup)  
[1.1.2. Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)  

[1.2. Solution Profile](#12-solution-profile)  
[1.2.1 Antecedentes y problemática](#121-antecedentes-y-problemática)  
[1.2.2 Lean UX Process.](#122-lean-ux-process)  
[1.2.2.1. Lean UX Problem Statements.](#1221-lean-ux-problem-statements)  
[1.2.2.2. Lean UX Assumptions.](#1222-lean-ux-assumptions)  
[1.2.2.3. Lean UX Hypothesis Statements.](#1223-lean-ux-hypothesis-statements)  
[1.2.2.4. Lean UX Canvas.](#1224-lean-ux-canvas)  

[1.3. Segmentos objetivo.](#13-segmentos-objetivo)  

[Capítulo II: Requirements Elicitation & Analysis](#capítulo-ii-requirements-elicitation--analysis)  

[2.1. Competidores](#21-competidores)  
[2.1.1. Análisis competitivo](#211-análisis-competitivo)  
[2.1.2. Estrategias y tácticas frente a competidores](#211-análisis-competitivo)  

[2.2. Entrevistas](#22-entrevistas)  
[2.2.1. Diseño de entrevistas](#221-diseño-de-entrevistas)  
[2.2.2. Registro de entrevistas](#222-registro-de-entrevistas)  
[2.2.3. Análisis de entrevistas](#223-análisis-de-entrevistas)  

[2.3. Needfinding](#23-needfinding)  
[2.3.1. User Personas](#231-user-personas)  
[2.3.2. User Task Matrix](#232-user-task-matrix)  
[2.3.3. User Journey Mapping](#233-user-journey-mapping)  
[2.3.4. Empathy Mapping](#234-empathy-mapping)  
[2.3.5. As-is Scenario Mapping](#235-as-is-scenario-mapping) 
[2.4. Big Picture EventStorming.](#24-big-picture-eventstorming)

[2.5. Ubiquitous Language](#25-ubiquitous-language)  

[Capítulo III: Requirements Specificatio](#capítulo-iii-requirements-specification)  

[3.1. User Stories](#31-user-stories)  
[3.2. Impact Mapping](#32-impact-mapping)  
[3.3. Product Backlog](#33-product-backlog)  

## Capítulo IV: Product Design
[4.1. Style Guidelines](#41-style-guidelines)  
[4.1.1. General Style Guidelines](#411-general-style-guidelines)  
[4.1.2. Web Style Guidelines](#412-web-style-guidelines)  
[4.1.3. Mobile Style Guidelines](#413-mobile-style-guidelines)  
[4.1.3.1. iOS Mobile Style Guidelines](#4131-ios-mobile-style-guidelines)  
[4.1.3.2. Android Mobile Style Guidelines](#4132-android-mobile-style-guidelines)

[4.2. Information Architecture](#42-information-architecture)  
[4.2.1. Organization Systems](#421-organization-systems)  
[4.2.2. Labeling Systems](#422-labeling-systems)  
[4.2.3. SEO Tags and Meta Tags](#423-seo-tags-and-meta-tags)  
[4.2.4. Searching Systems](#424-searching-systems)  
[4.2.5. Navigation Systems](#425-navigation-systems)

[4.3. Landing Page UI Design](#43-landing-page-ui-design)  
[4.3.1. Landing Page Wireframe](#431-landing-page-wireframe)  
[4.3.2. Landing Page Mock-up](#432-landing-page-mock-up)

[4.4. Mobile Applications UX/UI Design](#44-mobile-applications-uxui-design)  
[4.4.1. Mobile Applications Wireframes](#441-mobile-applications-wireframes)  
[4.4.2. Mobile Applications Wireflow Diagrams](#442-mobile-applications-wireflow-diagrams)  
[4.4.3. Mobile Applications Mock-ups](#443-mobile-applications-mock-ups)  
[4.4.4. Mobile Applications User Flow Diagrams](#444-mobile-applications-user-flow-diagrams)

[4.5. Mobile Applications Prototyping](#45-mobile-applications-prototyping)  
[4.5.1. Android Mobile Applications Prototyping](#451-android-mobile-applications-prototyping)  
[4.5.2. iOS Mobile Applications Prototyping](#452-ios-mobile-applications-prototyping)

[4.6. Web Applications UX/UI Design](#46-web-applications-uxui-design)  
[4.6.1. Web Applications Wireframes](#461-web-applications-wireframes)  
[4.6.2. Web Applications Wireflow Diagrams](#462-web-applications-wireflow-diagrams)  
[4.6.3. Web Applications Mock-ups](#463-web-applications-mock-ups)  
[4.6.4. Web Applications User Flow Diagrams](#464-web-applications-user-flow-diagrams)

[4.7. Web Applications Prototyping](#47-web-applications-prototyping)

[4.8. Domain-Driven Software Architecture](#48-domain-driven-software-architecture)  
[4.8.1. Software Architecture Context Diagram](#481-software-architecture-context-diagram)  
[4.8.2. Software Architecture Container Diagrams](#482-software-architecture-container-diagrams)  
[4.8.3. Software Architecture Components Diagrams](#483-software-architecture-components-diagrams)

[4.9. Software Object-Oriented Design](#49-software-object-oriented-design)  
[4.9.1. Class Diagrams](#491-class-diagrams)  
[4.9.2. Class Dictionary](#492-class-dictionary)

[4.10. Database Design](#410-database-design)  
[4.10.1. Relational/Non-Relational Database Diagram](#4101-relationalnon-relational-database-diagram)


## Capítulo V: Product Implementation
[5.1. Software Configuration Management](#51-software-configuration-management)  
[5.1.1. Software Development Environment Configuration](#511-software-development-environment-configuration)  
[5.1.2. Source Code Management](#512-source-code-management)  
[5.1.3. Source Code Style Guide & Conventions](#513-source-code-style-guide--conventions)  
[5.1.4. Software Deployment Configuration](#514-software-deployment-configuration)

[5.2. Product Implementation & Deployment](#52-product-implementation--deployment)  
[5.2.1. Sprint Backlogs](#521-sprint-backlogs)  
[5.2.2. Implemented Landing Page Evidence](#522-implemented-landing-page-evidence)  
[5.2.3. Implemented Frontend-Web Application Evidence](#523-implemented-frontend-web-application-evidence)  
[5.2.4. Implemented Native-Mobile Application Evidence](#524-implemented-native-mobile-application-evidence)  
[5.2.5. Implemented RESTful API and/or Serverless Backend Evidence](#525-implemented-restful-api-andor-serverless-backend-evidence)  
[5.2.6. RESTful API Documentation](#526-restful-api-documentation)  
[5.2.7. Team Collaboration Insights](#527-team-collaboration-insights)

[5.3. Video About-the-Product](#53-video-about-the-product)

[Conclusiones](#conclusiones)  
[Conclusiones y recomendaciones](#conclusiones-y-recomendaciones)  
[Video About-the-Team](#video-about-the-team)  
[Bibliografía](#bibliografía)  
[Anexos](#anexos)  

# Student Outcome
|Criterio Especifico|Acciones Realizadas|Conclusiones|
|-|-|-|
|Trabaja en equipo para proporcionar liderazgo en forma conjunta.|Compañero1:<br> *TB1:*  <p>* texto etc.. </p> |TB1 <p>Conclusion</p>|
|Trabaja en equipo para proporcionar liderazgo en forma conjunta|Compañero1:<br> *TB1:*  <p>* texto etc.. </p> |TB1 <p>Conclusion</p>|
# Capítulo I: Introducción
## 1.1. Startup Profile
### 1.1.1. Descripción de la Startup
#### 1.1.2. Perfiles de integrantes del equipo
|Miembros del equipo | Codigo Estudiante | Carrera | Conocimientos / Habilidades |
|-|-|-|-|
|Compañero 1 	![Imagen del compañero](image.jpg)|U20...|Ingenieria de software|C++, piton .etc|

## 1.2. Solution Profile
### 1.2.1 Antecedentes y problemática
### 1.2.2 Lean UX Process.
#### 1.2.2.1. Lean UX Problem Statements.
#### 1.2.2.2. Lean UX Assumptions.
|Business Assumptions|User Assumptions|
|-|-|
|1. - 12. |1. - 6.|
#### 1.2.2.3. Lean UX Hypothesis Statements.
Texto
#### 1.2.2.4. Lean UX Canvas.
(imagen con texto)
## 1.3. Segmentos objetivo.
| | Segmento 1 | Segmento 2  |
| - | - |-|
| Variables                 |  |  |
| Geográfica                |  |  |
| Demográfica               |  |  |
| Psicológica               |  |  |
| Función de comportamiento |  |  |

---

# Capítulo II: Requirements Elicitation & Analysis
## 2.1. Competidores.
### 2.1.1. Análisis competitivo.

| Competitive Analysis Landscape                          |  |
| ------------------------------------------------------- | -|
| ¿Por qué llevar a cabo este análisis?                   | -- |


| |  | (Nosotros) | Competidor  | Comptdor |
|-|-|-|-|-|
| PERFIL| Overview | lorem | ipsum | lorem |
|| Ventaja competitiva ¿Qué valor ofrece a los clientes? |  ipsu | impuz |
|| Mercado Objetivo                                        | Jeda | asa | asa2 |
| Perfil de marketing                                     | Estrategia de Marketing | Redes Sociales | Redes Sociales | Televisión, Redes Sociales |
| Perfil del producto                                     | Productos y servicios | Elementos Gráficos Interactivos Enseñanza de Matemáticas Lúdica y Autodidacta Educación matemática interactiva Ámbito Freemium | Educación matemática interactiva Mas de 100 cursos en 28 idiomas diferentes | Educación general interactiva Contratos con Movistar |
|| Precios y costos                                        | Freemium (Cuenta Premium permite personalizar los juegos) Gratis | Gratuito | Gratuito |
|| Canales de distribución (Web y/o Móvil)                 | Web y Móvil Web | Móvil Web | Web y móvil Web |
### 2.1.2. Estrategias y tácticas frente a competidores.


|Competidores ->|  | Nosotros | Competidor2| Competidor3|
|-|-|-|-|-|
| Análisis SWOT | Fortalezas | lorem | Lorem | lorem |
|| Debilidades   | lorem | lorem | lorem | lorem | 
|| Oportunidades | lorem | lorem | lorem | lorem | 
|| Amenazas      | lorem | lorem | lorem | lorem |

## 2.2. Entrevistas.
### 2.2.1. Diseño de entrevistas.
**Preguntas generales:**

1. ¿Cuál es su nombre? 
2. ¿Qué edad tiene? 
3. ¿A qué se dedica? 
4. ¿[Opinion de idea de propuesta]? 

**Entrevistas usuario segmento 2**
1. ¿Lorem?
2. ¿Lorem?
3. ¿Lorem?
4. ¿Lorem?  
   
**Entrevistas usuario segmento 2**
1. ¿Lorem? 
2. ¿Lorem?
3. ¿Lorem?
4. ¿Lorem? 
### 2.2.2. Registro de entrevistas.
**Segmento 1**  
Nombre: _____
Edad: _ años 
Ocupación: _____  
![Imagen de entrevista](image.jpg)  
{texto mucho}

**Segmento 2**  
Nombre: _____
Edad: _ años 
Ocupación: _____  
![Imagen de entrevista](image.jpg)
{texto}

### 2.2.3. Análisis de entrevistas.
**Segmento 1:**
{texto}
**Segmento 2:**
{texto}
## 2.3. Needfinding.
### 2.3.1. User Personas.
**Segmento 1:**  
![Imagen User Persona 1](image.jpg)

**Segmento 2:**
![Imagen User Persona 1](image.jpg)

### 2.3.2. User Task Matrix.
| --- | ------ | Segmento 1  | ------/----- | Segmento 2  | ---------- |
| --- | ------ | ----------- | ------------ | ----------- | ---------- |
| ID  | Titulo | Importancia | Frecuencia   | Importancia | Frecuencia |
| U01X| {Texto}| Alta        | Alta         | Media       | Baja       |
### 2.3.3. User Journey Mapping.
**Registration:**
Why would they trust us?
- s
- s
- s
  
**Onboarding and first use:**
How can they feel successful?
- s
- s
- s  
  
**Sharing:**
Why would they invite others?
- s
- s
- s

### 2.3.4. Empathy Mapping.
**Segmento 1:**
![Empathy Map Segmento1](image.jpg)

**Segmento 2:**
![Empathy Map Segmento1](image.jpg)
### 2.3.5. As-is Scenario Mapping.

**Segmento 1**  
Escenario: {escenario}

As Is:
| Fases| Fase 1 | Fase 2| Fase 3| Fase 4|
| -------- | --------- | --------- | ------- | --------- |
| Doing | texto| texto | texto| texto|
| Thinking | texto| texto | texto| texto|
| Feeling  | texto| texto | texto| texto|

**Segmento 2**  
Escenario: Dificultad para entender Matemáticas

As Is:
| Fases| Fase 1 | Fase 2| Fase 3| Fase 4|
| -------- | --------- | --------- | ------- | --------- |
| Doing | texto| texto | texto| texto|
| Thinking | texto| texto | texto| texto|
| Feeling  | texto| texto | texto| texto|
## 2.4 Big Picture EventStorming.

## 2.5. Ubiquitous Language.
```
Texto ubiquo: Definicion de este
```

---

# Capítulo III: Requirements Specification

## 3.1. User Stories.

| HU0X | Historia Usuario | "Descripcion"  |
|-|-|-|

## 3.2. Impact Mapping.

![Impact Mapping](image.jpg)

## 3.3. Product Backlog.

| #Orden | User Story ID | Titulo| Descripción| Story Points (1/2/3/5/8) |
| ------ | ------------- | ----- | ---------- | ------------------------ |
| 1      | HU01          | titulo his | desc  | 5                        |

# Capítulo IV: Product Design
## 4.1. Style Guidelines
### Quadrapp - Lineamientos de Diseño

La aplicación **Quadrapp** se fundamenta en un **diseño intuitivo, limpio y accesible**, priorizando la **legibilidad** y la **simplicidad de interacción**.

Se busca una **experiencia consistente** en todas las plataformas, evitando la **sobrecarga visual** y utilizando los **espacios en blanco** de forma estratégica.

La **tipografía principal** será **Sans Serif moderna Roboto**, garantizando **claridad en pantallas de distinto tamaño**.
### 4.1.1. General Style Guidelines

##### Branding
El branding de **Quadrapp** busca proyectar **confianza, inclusión y eficiencia urbana**.  
La identidad evoluciona hacia una **paleta violeta–azul con acentos en naranja**, que comunica innovación cercana y resalta las llamadas a la acción, sobre fondos claros y alto contraste para favorecer la accesibilidad.

El resultado es una **marca moderna, consistente y orientada a la acción**, alineada con el propósito de ordenar y facilitar la movilidad del usuario.

---

##### Typography
La tipografía de **Quadrapp** adopta **Sans Serif moderna** por su legibilidad, disponibilidad multiplataforma y estética limpia.  

Se prioriza una **jerarquía clara**, un **interlineado generoso** y **tamaños mínimos accesibles** para asegurar una lectura cómoda en web y móvil.

###### Tamaño y estilos
- **H1:** 32 px · peso 600 · color violeta `#6B46C1`  
  *Uso: títulos de página y secciones principales.*

- **H2:** 24 px · peso 600 · color azul `#2563EB`  
  *Uso: subtítulos de secciones y bloques.*

- **H3:** 20 px · peso 600 · color violeta `#6B46C1`  
  *Uso: encabezados de tarjetas, módulos y tablas.*

- **Párrafo (p):** 16–18 px · peso 400 · color `#111827`  
  *Uso: cuerpo de texto, ayudas y descripciones.*

###### Ajustes móviles (guideline)
- **H1:** 28–32 px
- **H2:** 22–24 px
- **H3:** 18–20 px
- **P:** 16–18 px

###### Interlineado recomendado:
- H1 → 40 px
- H2 → 32 px
- H3 → 28 px
- P → 24–28 px

---

##### Colors
La paleta de **Quadrapp** integra tonos **violeta** y **azul** con **acentos en naranja**, priorizando:
- Accesibilidad (alto contraste)
- Modernidad
- Llamadas a la acción claras

###### Paleta aplicada a tipografía
- **Primario (violeta):** `#6B46C1`
- **Secundario (azul):** `#2563EB`
- **Texto principal:** `#111827` (gris muy oscuro, alta legibilidad)

# Quadrapp - Color Palette

| Color Name       | Hex Code | Uso Principal |
|------------------|----------|-------------------------------------------------------------------|
| **Violeta Claro**   | `#C4B5FD` | Fondos de tarjetas suaves, estados “hover” sutiles |
| **Violeta Primario**| `#6B46C1` | Encabezados destacados, énfasis de marca |
| **Violeta Oscuro**  | `#4C1D95` | Fondos de secciones clave, barras y overlays oscuros |
| **Azul Claro**      | `#93C5FD` | Badges informativos, resaltados secundarios |
| **Azul Primario**   | `#2563EB` | Enlaces, botones secundarios, títulos de módulo |
| **Azul Muy Oscuro** | `#1E3A8A` | Color primario de texto sobre fondos claros, iconografía sólida |
| **Naranja CTA**     | `#F59E0B` | Botones primarios de acción (Call To Action) |
| **Naranja (Hover)** | `#D97706` | Estados hover/pressed del CTA, advertencias suaves |
| **Éxito (Green)**   | `#16A34A` | Confirmaciones, estados OK, indicadores positivos |
| **Alerta (Red)**    | `#DC2626` | Errores, estados críticos, validación fallida |
| **Texto Principal** | `#111827` | Párrafos y contenidos largos (alta legibilidad) |
| **Texto Secundario**| `#4B5563` | Etiquetas, meta-información, placeholders |
| **Bordes/Divisores**| `#E5E7EB` | Líneas de separación, contornos de inputs |
| **Fondo**           | `#FFFFFF` | Fondo base de la interfaz |
| **Fondo Alt**       | `#F9FAFB` | Paneles alternos, listas, tarjetas |

![Quadrapp Color Palette](./assets/Quadrapp_Paleta_Colores.png)

##### Spacing
Usamos una **escala de 8 px** para asegurar ritmo visual, coherencia entre web y móvil y mejor legibilidad.  
La regla es construir márgenes, paddings y gaps con múltiplos de 8.

**Escala base:** `8 · 16 · 24 · 32 · 40 · 48 · 64 · 96 px`

###### Reglas generales
- **Márgenes y paddings estándar:** 8/16/24/32 px según jerarquía del contenido.
- **Separación entre bloques mayores (secciones, fold/hero, módulos):** 64–96 px (48–64 px en móvil).
- **Gaps entre componentes hermanos (tarjetas, gráficos, tablas):** 24–32 px (16–24 px en móvil).
- **Espacio negativo intencional:** prioriza respiración visual; evita valores improvisados.

---

##### Icons
- **Línea:** minimal, reconocible y consistente.
- **Tamaño mínimo:** 24 px (web) / 24–32 px (móvil).
- **Área táctil:** ≥ 44 px.
- **Peso trazo:** 1.5–2 px.
- **Contraste:** nivel AA.

###### Estados (color)
- **Default:** `#4B5563` (texto secundario)
- **Hover/focus:** `#2563EB` (azul primario)
- **Activo/seleccionado:** `#6B46C1` (violeta primario)
- **En botón CTA naranja:** `#F59E0B` → icono blanco `#FFFFFF`
- **Deshabilitado:** `#E5E7EB`

---

###### Paleta aplicada
- **Primarios:** violeta `#6B46C1`, azul `#2563EB`
- **Éxito:** `#16A34A`
- **Error:** `#DC2626`
- **Texto:** `#111827`

###### Quadrapp - Iconografía de Acciones

| Acción              | Icono (Material)   | Color por defecto             | Notas de uso |
|---------------------|--------------------|-------------------------------|--------------|
| **Guardar**         | `save`             | `#6B46C1`                     | En botones primarios: blanco sobre CTA. |
| **Reservar**        | `calendar_month`   | `#2563EB`                     | En “crear reserva” usar CTA naranja. |
| **Email**           | `mail`             | `#2563EB`                     | En enlaces/contacto. |
| **Buscar**          | `search`           | `#4B5563` → hover `#2563EB`   | Input con icono leading. |
| **Filtrar**         | `filter_list`      | `#4B5563`                     | Chips de filtro activos en `#6B46C1`. |
| **Lista/Mapa (toggle)** | `list` / `map` | `#4B5563`                     | Estado activo en `#6B46C1`. |
| **Parking**         | `local_parking`    | `#2563EB`                     | Marca/identificador de estacionamiento. |
| **Ubicación**       | `pin_drop`         | `#2563EB`                     | En cards y detalle. |
| **Disponibilidad libre** | `check_circle` | `#16A34A`                     | Ocupado: `block #DC2626`; Reservado: `schedule #D97706`. |
| **Reseñas/Rating**  | `star`             | `#F59E0B`                     | Media estrella: `star_half`. |
| **Notificaciones**  | `notifications`    | `#4B5563`                     | No leído en `#2563EB`. |
| **Perfil**          | `person`           | `#4B5563`                     | Activo en tab bar: `#6B46C1`. |
| **Dashboard**       | `dashboard`        | `#2563EB`                     | Tarjetas/resúmenes. |
| **QR**              | `qr_code_2`        | `#4B5563`                     | Acciones: descargar/mostrar. |
| **Editar**          | `edit`             | `#4B5563`                     | En tabla: acción secundaria. |
| **Eliminar**        | `delete`           | `#DC2626`                     | Confirmación obligatoria. |
| **Volver**          | `arrow_back`       | `#4B5563`                     | Navegación superior. |
| **Inicio**          | `home`             | `#2563EB`                     | Página principal. |
| **Pago**            | `credit_card`      | `#2563EB`                     | Éxito de pago: `check_circle #16A34A`. |

##### Quadrapp - Tone of Voice

###### Personalidad
- Claro, cercano y orientado a la acción
- Inclusivo y sereno
- Profesional sin ser frío

###### Objetivo
Que el usuario se sienta **acompañado y en control** (confianza + eficiencia).

---

###### Principios
1. **Claridad primero:** frases cortas, verbos en activo, sin tecnicismos.
2. **Cercanía respetuosa:** trato en segunda persona (“tú”) en móvil; tono profesional cercano en panel web (dueños/operadores).
3. **Honestidad y calma:** informa qué pasó, por qué y qué hacer después.
4. **Inclusivo y accesible:** lenguaje sencillo, sin jerga local ni género marcado.
5. **Consistencia:** *sentence case*, sin mayúsculas sostenidas; evita signos y emojis en exceso.

---

###### Guía de estilo
- **CTA concretos y accionables:**  
  Ejemplo: *“Reservar ahora”*, *“Pagar”*, *“Ver detalles”*.

- **Mensajes breves:** máx. 1–2 oraciones por bloque.

- **Prioriza lo útil:** primero la acción o la solución; luego el contexto.


### 4.1.2. Web Style Guidelines

Estas pautas definen cómo debe verse y comportarse la app web de **Quadrapp**, alineada al branding **violeta–azul con CTA naranja**, la **escala de 8 px** y la **accesibilidad AA**.

---

##### Diseño responsivo
- **Grid y ritmo:** escala 8 px (8/16/24/32/64), gutters:
    - 24 px desktop
    - 16 px tablet
    - 12–16 px móvil
- **Lectura en F/Z:** jerarquiza con títulos claros, subtítulos y párrafos de 16–18 px.
- **Breakpoints de referencia:**
    - ≥1280 px: 12 columnas (máx. ancho 1200–1280 px).
    - ≥960 px: 12 columnas (contenido centrado).
    - <960 px: 4–8 columnas, navegación colapsada.
- Imágenes y tablas responsivas; evita scroll horizontal.

---

##### Navegación
###### App shell (panel operador)
- **Top App Bar:** con título de módulo y acciones globales (Soporte, Cuenta).
- **Sidenav izquierdo (~280 px):** secciones → Dashboard, Reservas, Reseñas, Perfil (y otras definidas).
- **Estado activo de ítem:** violeta `#6B46C1` + fondo sutil.
- **Pantallas pequeñas:** botón hamburguesa para abrir/cerrar sidenav.
- **Profundidad:** breadcrumbs cuando haya >2 niveles.

###### Landing (marketing)
- **Navbar superior minimal:** Inicio, Beneficios, Planes, Contacto.
- **CTA visible** en todo momento.

---

##### Componentes UI (Angular Material)

###### Botones
- **Primario (CTA):** `mat-flat-button` naranja `#F59E0B` (texto blanco).
- **Secundario:** `mat-stroked-button` azul `#2563EB`.
- **Terciario/Ghost:** `mat-button` texto azul `#2563EB`.
- Estados hover/pressed/focus visibles.
- Deshabilitado con contraste suficiente.

###### Formularios
- `mat-form-field` con label arriba, ayuda breve y error bajo el campo.
- **Espaciado:**
    - Label → campo: 8 px
    - Entre campos: 16–24 px
    - Entre grupos: 32 px
- **Validación:** clara y oportuna (al blur o submit fallido).

###### Tablas
- `mat-table` con paginación, orden y filtros.
- Altura de fila: 44–48 px (cómoda) o 36–40 px (compacta).
- Columnas críticas fijas en desktop.
- Acciones al final con **icon buttons**.

###### Tarjetas
- `mat-card` fondo blanco, bordes 12–16 px, sombra sutil.
- Títulos **H3**: 20 px.

###### Chips / Filtros
- `mat-chip` con estado activo en `#6B46C1`.
- Texto con contraste suficiente.

###### Gráficos
- Paleta consistente (violeta/azul).
- Leyendas legibles.
- Líneas/áreas con suficiente contraste.

---

##### Accesibilidad
- **Contraste:** AA mínimo para texto/íconos; revisar combinaciones en botones pequeños.
- **Teclado:** focus visible en todos los controles; orden lógico de tabulación.
- **Semántica ARIA:**
    - Formularios con `aria-describedby` para errores/ayudas.
    - Tablas con `scope` en headers.
- “Skip to content” al inicio.
- Títulos únicos por página.
- Alt text en imágenes.
- **Motion:** respeta `prefers-reduced-motion`; transiciones sutiles 150–200 ms.

### 4.1.3. Mobile Style Guidelines
#### Objetivo
Ofrecer una **experiencia táctil rápida y clara**, con el mismo lenguaje visual que la web pero optimizada para pantallas pequeñas y uso en movimiento.

---

#### Principios generales
- **Touch-first y accesible:** objetivos táctiles ≥ 44 px, foco visible, contrastes AA.
- **Ritmo 8 px:** márgenes/paddings y gaps en múltiplos de 8 (8/16/24/32/64).
- **Prioridad de funciones:** acceso directo a *Explorar/Reservar*, *Mis reservas*, *Notificaciones* y *Perfil* desde **tab bar**.
- **Legibilidad:** Sans Serif (Inter/Roboto en Flutter).
    - Tamaños base: H1 28–32, H2 22–24, H3 18–20, P 16–18.
    - Interlineado cómodo.
- **Paleta Quadrapp:**
    - Primarios: violeta `#6B46C1`, azul `#2563EB`
    - CTA naranja `#F59E0B`
    - Texto `#111827`
- **Jerarquía visual:** tarjetas blancas con bordes 12–16 px, sombras suaves; CTA naranja destacado.
- **Motion sutil:** transiciones 150–200 ms; respeta *reduce motion*.
- **Safe areas y notch:** contenido evita recortes (status bar, gesto home) y respeta teclado (*scroll insets*).

---

#### Patrones de UI
- **Navegación:**
    - Tab bar inferior: Inicio/Explorar, Reservas, Notificaciones, Perfil.
    - Pila de navegación con gesto “back”.

- **Listas y detalle:**
    - Listas en tarjetas con icono/estado.
    - Detalle con CTA fijo (ej. “Reservar”).

- **Búsqueda y filtros:**
    - Campo de búsqueda con debounce.
    - Chips de filtros arriba.
    - Resultados en tiempo real.

- **Formularios:**
    - Labels claros, ayudas breves.
    - Errores bajo el campo (8 px).
    - Grupos separados (24–32 px).

- **Estados vacíos:** mensaje claro + CTA contextual.

- **Feedback:**
    - Toasts no intrusivos para éxito.
    - Diálogos solo para confirmaciones críticas.

---

#### Colores y estados (móvil)
- **Activos/selección:** violeta `#6B46C1` (tab activo, chips activos).
- **Enlaces/acciones secundarias:** azul `#2563EB`.
- **CTA:** naranja `#F59E0B` (texto blanco); hover/pressed `#D97706`.
- **Éxito/Error:** verde `#16A34A` / rojo `#DC2626`.
- **Fondos:** blanco `#FFFFFF` / alterno `#F9FAFB`.

#### 4.1.3.1. iOS Mobile Style Guidelines

#### Navegación
- **Tab bar inferior** con labels visibles; icono activo en violeta `#6B46C1`.
- **Large Title opcional** en vistas raíz (ej. “Explorar”); toolbar limpia.
- **Gesto back** desde el borde izquierdo habilitado en vistas apiladas.

---

#### Controles y listas
- **Botones filled** para acciones primarias (CTA naranja).
- **Botones plain** para acciones secundarias.
- **Listas con separación sutil**; chevrons para navegación a detalle.
- **Action Sheets / Bottom Sheets** para selecciones rápidas (horarios, métodos de pago).

---

#### Formularios
- Labels sobre el campo.
- Teclado adecuado al tipo (email, numérico).
- Botón **“Continuar” / “Pagar ahora”** siempre visible (*bottom anchored*) en pasos críticos.

---

#### Tipografía y espaciado
- Títulos: 28–32 px con interlineado amplio.
- Párrafos: 16–18 px.
- Espacios:
    - 8/16 px dentro de tarjetas.
    - 24–32 px entre secciones.

---

#### Haptics y microinteracciones
- **Light impact** al confirmar.
- **Warning** en errores críticos.

---

#### Accesibilidad
- Soporte **VoiceOver** (orden lógico, `semanticsLabel` en Flutter).
- Tamaños dinámicos (*text scaling*) sin romper layout.
- Focus visible para mandos de hardware / teclado externo.

#### 4.1.3.2. Android Mobile Style Guidelines
#### Navegación
- **Bottom navigation bar** con 3–4 destinos; icono y label siempre visibles.
- **Top App Bar** (center o small) con acciones contextuales (buscar, filtrar).
- **Back** mediante botón del sistema o App Bar.

---

#### Componentes M3
- **FAB:** solo si agrega valor (acción primaria contextual, ej. “Nueva reserva” en *Mis reservas*).
- **Cards:** elevación sutil y radios 12–16 px.
- **Chips:** para filtros.
- **Snackbars:** para confirmaciones.
- **Dialogs:** para confirmaciones destructivas.

---

#### Formularios
- **TextField** con label claro.
- **Helper/error:** en 8 px bajo el campo.
- **Grupos por pasos:**
    1. Resumen
    2. Método de pago
    3. Confirmación

---

#### Tipografía y espaciado
- **H1:** 28–32 px
- **H2:** 22–24 px
- **H3:** 18–20 px
- **P:** 16–18 px

**Gaps:**
- 16–24 px intra-sección
- 32 px entre grupos
- 64 px entre bloques mayores

---

#### Accesibilidad
- Soporte **TalkBack** y `semantics` en controles.
- Estados **enabled/disabled** con contraste suficiente.
- **Touch targets ≥44 px**.
- **Foco visible:** ripple + outline.

---

#### Motion y temas
- **Transiciones:** 150–200 ms (fade/slide).
- Respeta **Dynamic Color** si se habilita, manteniendo la identidad Quadrapp.
- Prioriza los **colores primarios definidos**.

## 4.2. Information Architecture
### 4.2.1. Organization Systems
#### Modelo híbrido
Jerárquico + orientado a tareas.

---

#### Módulos principales
- **Autenticación (Auth):** Sign In / Sign Up / Recuperar clave.
- **Explorar / Directorio:** búsqueda por lista ↔ mapa; filtros por distancia, precio, rating y horario.
- **Parking:** Home del parking, Perfil/Configuración, Tarifas/Horarios, Servicios.
- **Reservas:** listar, detalle, creación y pago.
- **Reseñas:** feed y creación de reseña.
- **Perfil de usuario/owner:** datos, seguridad, preferencias.
- **Dashboard & Analytics (web):** KPIs, tablas y gráficos.
- **IoT (futuro, solo mención):** monitoreo conceptual de dispositivos/ocupación.

---

#### Procesos secuenciales (task-flows)
- **Reserva:** Explorar → Detalle parking → Crear reserva → Pago → Comprobante/QR.
- **Gestión (web):** Registro/edición de parking → Tarifas → Publicación.

---

#### Estructura de contenidos
- **Web (operador/owner):**  
  App Shell con Top App Bar + Sidenav → Dashboard, Reservas, Reseñas, Perfil, Configuración.

- **Móvil (conductor):**  
  Tab bar → Inicio/Explorar, Reservas, Notificaciones, Perfil.

---

#### Sitemaps (resumen)

###### Web (Angular)
- `/sign-in`, `/sign-up`
- `/dashboard`
- `/reservations` (tabla + detalle/modal)
- `/parking/directory/:ownerId`
- `/parking/home/:parkingId`
- `/parking/profile`
- `/parking/registration`
- `/parking/reviews`
- `/profile/:ownerId`
- `/devices` (IoT conceptual)
- `/**` (404)

###### Móvil (Flutter)
- **Tabs:** Explorar | Reservas | Notificaciones | Perfil
- **Flujos:** Login/Registro → Explorar (lista/mapa) → Detalle → Reserva → Pago → Éxito → Mis reservas

### 4.2.2. Labeling Systems

#### Principios
- **Claridad y consistencia:** usar *sentence case*, sin tecnicismos.
- **Etiquetas cortas:** máximo 2–3 palabras, accionables cuando aplica.

---

#### Convenciones
- **Navegación global (web):** Dashboard, Reservas, Reseñas, Perfil, Configuración.
- **Móvil (tab bar):** Inicio, Reservas, Notificaciones, Perfil.
- **Acciones:** *Reservar ahora*, *Pagar*, *Ver detalle*, *Editar*, *Descargar*.
- **Formularios:**
    - Labels con sustantivo claro (*Correo electrónico*, *Contraseña*).
    - Ayudas breves (1 línea).
    - Errores directos (*Este campo es obligatorio.*).
- **Icono + texto siempre** (evitar *icon-only* en navegación principal).
- **i18n listo:**
    - No incrustar variables en medio de frases si se puede evitar.
    - Preferir placeholders al final:
        - Ejemplo: *“Reservas de {month}”*.

---

#### URLs y slugs (web)
- **Formato:** kebab-case, semánticos.
- **Ejemplos:**
    - `/parking/home/{id-o-slug}`
    - `/reservations?from=2025-09-01&to=2025-09-10&status=active`
    - `/parking/directory/{owner-id}`
- **Regla:** evitar IDs sensibles en query strings; usar slugs cuando haya nombres públicos.

### 4.2.3. SEO Tags and Meta Tags

#### Básicos
- **Title (≤60 caracteres):**  
  `Quadrapp | Reserva de estacionamiento fácil en [Ciudad]`

- **Meta description (≤160 caracteres):**  
  `Encuentra, reserva y paga estacionamientos cercanos en minutos. Disponibilidad en tiempo real, reseñas y comprobante QR.`

- **Viewport:**  
  `width=device-width, initial-scale=1`

- **Robots:**
    - `index, follow` → solo en landing y páginas públicas.
    - `noindex` → en `/app/*`.

---

#### Social (Open Graph / Twitter)
- **Open Graph:**
    - `og:title`
    - `og:description`
    - `og:image` (1200×630)
    - `og:type=website`
    - `og:url`

- **Twitter:**
    - `summary_large_image`

---

#### Canonical
- Usar etiqueta:  
  `<link rel="canonical" href="https://quadrapp.com/">`
- Aplicar en landing y listados con filtros para **evitar contenido duplicado**.

---

#### Estructurados (opcional)
- **JSON-LD:**
    - Organización / Marca.
    - Listado de parkings (si hay páginas públicas).
- Mantenerlo **simple y consistente**.

### 4.2.4. Searching Systems
#### Objetivo
Localizar estacionamientos y reservas **rápido y con pocos pasos**.

---

#### Patrones

###### Búsqueda principal (Explorar)
- Campo con **debounce (~300 ms)**.
- Sugerencias por barrio/avenida.
- Detección de ubicación (permiso explícito).
- Toggle **Lista/Mapa**.

###### Facetas / filtros (chips arriba)
- Distancia (cercanía).
- Precio/hora.
- Horario.
- Disponibilidad.
- Calificación (★).
- Servicios (techado, vigilancia).
- Método de pago.

###### Ordenar por
- Distancia.
- Precio.
- Mejor valorado.
- Más cercano.

###### Resultados
- Tarjetas con nombre, dirección, distancia, precio y estado.
- En mapa: **markers** + *bottom sheet* al seleccionar.

###### Estados
- **No results:** mostrar sugerencias → limpiar filtros, ampliar radio.

---

###### Reservas (web)
- Búsqueda por **ID / usuario / fecha**.
- Filtros por **estado** y **rango de fechas**.
- Exportación **CSV**.

---

###### Accesibilidad
- Campo con **label visible**.
- `aria-describedby` para ayudas/errores.
- Resultados **navegables por teclado**.
- **Foco visible** en chips y lista.

### 4.2.5. Navigation Systems
#### Web (Angular + Material)
- **Top App Bar:** título de módulo, acciones globales (Soporte, Cuenta).
- **Sidenav:** secciones principales (activo en violeta); colapsable en `<960 px` (hamburguesa).
- **Breadcrumbs:** cuando exista profundidad >2 (ej. *Reservas > Detalle*).
- **Enlaces profundos:** rutas directas a detalle de reserva/parking.
- **Estados de ruta:** loading skeletons al navegar; toasts para confirmaciones.

---

#### Móvil (Flutter)
- **Tab bar:** 4 destinos → Inicio/Explorar, Reservas, Notificaciones, Perfil.
- **Stack por tab:** gesto back y App Bar con acciones contextuales (buscar, filtrar).
- **Bottom sheet:** para selecciones rápidas (horarios, métodos de pago).
- **CTA anclado en detalle:** *Reservar / Pagar ahora*.

---

#### Reglas de navegación
- Mantener **consistencia cross-platform** en nombres y jerarquía.
- Minimizar pasos en flujos críticos (**reserva/pago**); CTA siempre visible.
- Evitar **callejones sin salida**: siempre ofrecer *Volver* o *Ir al inicio*.
- **404 y vacíos** con CTA de salida (ej. *Explorar parkings*).

---

#### IoT (mención escalable)
- En **web**, entrada de *Dispositivos* solo como vista conceptual:
    - Lista de sensores con estado (ON/OFF, última señal).
    - No se implementa lógica embebida en este alcance.
## 4.3. Landing Page UI Design
### 4.3.1. Landing Page Wireframe

En el marco del proyecto Quadrapp, se ha diseñado una landing page como puerta de entrada principal para los usuarios. Su propósito es transmitir la propuesta de valor, guiar al visitante hacia la acción de reservar estacionamientos y generar confianza en la aplicación. El diseño se inició con un wireframe en baja fidelidad, que definió estructura y jerarquía visual. Posteriormente, se aplicará la guía de estilos establecida para producir mockups en alta fidelidad. De esta manera, la landing integra coherencia estética y funcionalidad acorde al branding de Quadrapp.

![Quadrapp LandingPageWireframe](./assets/LandingPage-Experimentos.png)

---


![Quadrapp LandingPageWireframe](./assets/LandigPageWireframeResponsive.png)

### 4.3.2. Landing Page Mock-up

En el marco del proyecto Quadrapp, se desarrolló el mockup en alta fidelidad de la landing page, aplicando la guía de estilos definida (colores, tipografía, iconografía y componentes). Este mockup refleja de manera visual el branding de la aplicación, transmitiendo modernidad y confianza. A partir del wireframe inicial, se incorporaron mejoras en la jerarquía, usabilidad y atractivo visual. El resultado es una propuesta clara y coherente que guía al usuario hacia la acción de reservar estacionamientos. De esta forma, el mockup consolida la estética final y la experiencia esperada de Quadrapp.

![Quadrapp LandingPageMockup](./assets/LandingPageMockup-Experimentos.png)


---

![Quadrapp LandingPageMockup](./assets/LandingPageMockupResponsiv-Expermientos.png)


## 4.4. Mobile Applications UX/UI Design
### 4.4.1. Mobile Applications Wireframes

En el marco del proyecto Quadrapp, se elaboraron los wireframes móviles como base para la aplicación destinada a conductores. Estos prototipos en baja fidelidad permiten definir la estructura de navegación, distribución de pantallas y principales flujos de interacción. Se incluyen vistas clave como login, registro, búsqueda de estacionamientos, reservas y perfil de usuario. Su objetivo es validar la usabilidad y lógica de la aplicación antes de aplicar el diseño visual final. Así, los wireframes móviles sirven como punto de partida para los mockups en alta fidelidad.

Inicio de sesión:

---

![Quadrapp WireframeMovil](./assets/IniciarSesionWFmovil.png)

---
Crear cuenta:

---

![Quadrapp WireframeMovil](./assets/CreacionCuentaWFMovil.png)

---
Información de estacionamiento:

---
![Quadrapp WireframeMovil](./assets/InformacionReservaWfmovil.png)

---
Filtrar busqueda: 

---
![Quadrapp WireframeMovil](./assets/FiltrarEstacionamientoWFMovil.png)

---
Perfil de usuario:

---

![Quadrapp WireframeMovil](./assets/PerfilWfMovil.png)

  
### 4.4.2. Mobile Applications Wireflow Diagrams

En el desarrollo de Quadrapp, se diseñaron los wireflow diagrams móviles para representar de manera clara los flujos de navegación entre pantallas. Estos diagramas combinan wireframes con conexiones que muestran las acciones del usuario y sus posibles recorridos. Permiten visualizar cómo se realiza una reserva desde la búsqueda hasta el pago, incluyendo casos alternativos. Su propósito es validar la coherencia y simplicidad de la experiencia antes de la implementación. De este modo, los wireflows complementan a los wireframes y enriquecen el proceso de diseño de la app

Primeros pasos del usuario:

---

![Quadrapp FlujoFrame](./assets/FlujoPrimerosPasosWireFrame.png)

---
Reserva de estacionamiento:

---

![Quadrapp FlujoFrame](./assets/ReservaDeUnEstacionamientoWFmovil.png)

---

![Quadrapp FlujoFrame](./assets/ConfiguracionsdePerdilWFmovil.png)


### 4.4.3. Mobile Applications Mock-ups

En el marco del proyecto Quadrapp, se desarrollaron los mockups móviles en alta fidelidad como evolución de los wireframes iniciales. Estos prototipos incorporan el sistema de diseño definido (colores, tipografía, iconografía y componentes) para reflejar la identidad visual de la aplicación. Se presentan las vistas clave de login, registro, búsqueda de estacionamientos, reservas y perfil de usuario con un estilo consistente y atractivo. Su finalidad es mostrar cómo será la experiencia real del usuario en la app. De esta manera, los mockups móviles consolidan la propuesta final antes de la etapa de desarrollo.



### 4.4.4. Mobile Applications User Flow Diagrams

En el marco del proyecto Quadrapp, se elaboraron los User Flow Diagrams en mockups móviles, con el fin de representar los principales recorridos del usuario dentro de la aplicación. Estos diagramas muestran de manera visual y detallada cómo el usuario avanza desde el inicio de sesión, la búsqueda de estacionamientos y la reserva, hasta el pago y la visualización del pase QR. Al estar basados en los mockups de alta fidelidad, permiten validar la coherencia del diseño, la facilidad de navegación y la efectividad de los flujos planteados. Así, los User Flow Diagrams sirven como guía clara para el desarrollo e implementación de la experiencia de usuario en la app.




## 4.5. Mobile Applications Prototyping
### 4.5.1. Android Mobile Applications Prototyping
### 4.5.2. iOS Mobile Applications Prototyping

## 4.6. Web Applications UX/UI Design
### 4.6.1. Web Applications Wireframes
### 4.6.2. Web Applications Wireflow Diagrams
### 4.6.3. Web Applications Mock-ups
### 4.6.4. Web Applications User Flow Diagrams

## 4.7. Web Applications Prototyping

## 4.8. Domain-Driven Software Architecture
### 4.8.1. Software Architecture Context Diagram
En el marco del proyecto Quadrapp, se elaboró el Software Architecture Context Diagram, el cual muestra una visión de alto nivel de la plataforma y su relación con los actores externos. Este diagrama identifica a los principales usuarios (conductores, operadores y administradores), así como los sistemas externos con los que interactúa (autenticación, pasarela de pagos, mapas y notificaciones). Su objetivo es establecer los límites del sistema, evidenciar las dependencias tecnológicas y brindar una comprensión clara del ecosistema donde se desarrollará la solución.

![Quadrapp C4](./assets/C4QuadrappContext.PNG)

### 4.8.2. Software Architecture Container Diagrams
En el marco del proyecto Quadrapp, se desarrollaron los Container Diagrams, que descomponen el sistema en sus principales contenedores de software. Estos diagramas muestran cómo se organizan la aplicación web, la aplicación móvil, el backend API, los servicios de soporte y la base de datos. Su objetivo es detallar la responsabilidad de cada contenedor, las tecnologías empleadas y las interacciones entre ellos, brindando una visión clara de la arquitectura lógica y de despliegue de la solución.

![Quadrapp C4](./assets/C4QuadrappContainers.PNG)

### 4.8.3. Software Architecture Components Diagrams

En el marco del proyecto Quadrapp, se elaboraron los Component Diagrams con el fin de detallar la organización interna de los contenedores principales, en especial el API Backend. Estos diagramas permiten visualizar los componentes clave (controladores, servicios, repositorios y adaptadores) y su relación con los bounded contexts definidos (Bookings, Payments, Directory, Reviews, Auth, Notifications, etc.). El objetivo es mostrar cómo se implementan las reglas de negocio, la interacción entre capas y la comunicación con sistemas externos, aportando un nivel de detalle esencial para el diseño, desarrollo y mantenimiento del sistema.

Component IAM:

---

![Quadrapp C4](./assets/Digram-Component-IAM-QUADRAP.png)


---

Component Reservation:

---

![Quadrapp C4](./assets/Diagram-Component-Reservation-Quadrapp.png)

---

Component Profile:

---

![Quadrapp C4](./assets/Diagram-Component-Profile-Quadrapp.png)


---

Component Payment:

---

![Quadrapp C4](./assets/Diagram-Component-Payment-Quadrapp.png)

---

Component Review:

---
![Quadrapp C4](./assets/Diagram-Component-Review-Quadrapp.png)

---

Component Parking Management:

---
![Quadrapp C4](./assets/Diagram-Component-ParkingManagement-Quadrapp.png)

---

Component Notification:

---
![Quadrapp C4](./assets/Diagram-Component-Notification-Quadrapp.png)


---


## 4.9. Software Object-Oriented Design
### 4.9.1. Class Diagrams
En el marco del proyecto Quadrapp, se desarrollaron los Class Diagrams con el propósito de modelar las estructuras de datos y sus relaciones dentro de los distintos módulos de la aplicación. Estos diagramas representan las clases principales, sus atributos, métodos y asociaciones, permitiendo visualizar la lógica interna del sistema y cómo los objetos colaboran entre sí. De esta manera, los Class Diagrams sirven como puente entre el diseño conceptual y la implementación, asegurando consistencia, mantenibilidad y alineación con los bounded contexts previamente definidos.




### 4.9.2. Class Dictionary
En el marco del proyecto Quadrapp, se elaboró el Class Dictionary con el objetivo de documentar de manera precisa las clases definidas en el sistema. Este diccionario describe los nombres de las clases, sus atributos, tipos de datos, métodos principales y relaciones, brindando un nivel de detalle técnico que complementa a los Class Diagrams. Su función es servir como una guía de referencia clara y estructurada para el equipo de desarrollo, garantizando consistencia en la implementación y facilitando el mantenimiento del sistema a lo largo del tiempo.

## 4.10. Database Design
### 4.10.1. Relational/Non-Relational Database Diagram
En el marco del proyecto Quadrapp, se desarrolló el Relational Database Diagram (ERD) con el propósito de representar de forma estructurada las entidades del sistema, sus atributos y las relaciones entre ellas. Este diagrama permite visualizar la lógica de la base de datos, facilitando la comprensión de la arquitectura de datos que sustenta funcionalidades críticas como la gestión de usuarios, reservas, pagos, reseñas y administración de estacionamientos.



# Capítulo V: Product Implementation
## 5.1. Software Configuration Management
### 5.1.1. Software Development Environment Configuration
### 5.1.2. Source Code Management
### 5.1.3. Source Code Style Guide & Conventions
### 5.1.4. Software Deployment Configuration

## 5.2. Product Implementation & Deployment
### 5.2.1. Sprint Backlogs
### 5.2.2. Implemented Landing Page Evidence
### 5.2.3. Implemented Frontend-Web Application Evidence
### 5.2.4. Implemented Native-Mobile Application Evidence
### 5.2.5. Implemented RESTful API and/or Serverless Backend Evidence
### 5.2.6. RESTful API Documentation
### 5.2.7. Team Collaboration Insights

## 5.3. Video About-the-Product
# Conclusiones
{texto}
# Conclusiones y recomendaciones.
{texto}
# Video About-the-Team.
[URL del video about the team](https://www.example.com)

# Bibliografía
qoomon. (2021, 11 enero). Conventional Commit Messages. Gist.
Recuperado 20 de junio de 2022, de [LINK](https://gist.github.com/qoomon/5dfcdf8eec66a051ecd85625518cfd13)

LeaseIN. (2018). Importancia de contar con un equipo de soporte
técnico. [Entrada en blog]. Recuperado de:
[LINK](https://leasein.pe/blog/branding-empresarial-importanciasoporte-tecnico/)
``` 
formato

"Apellido", Ini.Ciales. & "otroAutor", O.A. (año). titulo del articulo.
        "nombre del articulo o lo q sea, Volumen(si es que tiene), numero  de pagina"#-#. https//link.org/eeeseneko

```
# Anexos

datos, gráficos, imágenes, esquemas, mapas o referencias de otros autores

![Imagen de algo no nuestro ](image.jpg)






