### 6.1. Testing Suites & Validation.

### 6.1.1. Core Entities Unit Tests.

**User Tests:**

![UserTest](./assets/chapter-6/usertest1.png)
![UserTest](./assets/chapter-6/usertest2.png)
![UserTest](./assets/chapter-6/usertest3.png)
![UserTest](./assets/chapter-6/usertest4.png)
![UserTest](./assets/chapter-6/usertest5.png)

**Role Tests:**

![RoleTest](./assets/chapter-6/roletest1.png)
![RoleTest](./assets/chapter-6/roletest2.png)
![RoleTest](./assets/chapter-6/roletest3.png)
![RoleTest](./assets/chapter-6/roletest4.png)
![RoleTest](./assets/chapter-6/roletest5.png)

**Role Enum Tests:**

![RoleTest](./assets/chapter-6/rolesenumtest1.png)

**Parking Spot Tests:**
![ParkingSpotTest](./assets/chapter-6/parkingspottest1.png)

**Parking Tests:**
![ParkingTest](./assets/chapter-6/parkingtest1.png)
![ParkingTest](./assets/chapter-6/parkingtest2.png)
![ParkingTest](./assets/chapter-6/parkingtest3.png)

**Parking Spot Manager Tests:**
![ParkingSpotManagerTest](./assets/chapter-6/parkingspotmanagertest1.png)
![ParkingSpotManagerTest](./assets/chapter-6/parkingspotmanagertest2.png)
![ParkingSpotManagerTest](./assets/chapter-6/parkingspotmanagertest3.png)

**Payment Tests:**
![PaymentTest](./assets/chapter-6/paymenttest1.png)
![PaymentTest](./assets/chapter-6/paymenttest2.png)

**Reservation Payment Tests:**
![ReservationPaymentTest](./assets/chapter-6/reservationpaymenttest1.png)
![ReservationPaymentTest](./assets/chapter-6/reservationpaymenttest2.png)

**Subscription Payment Tests:**
![SubscriptionPaymentTest](./assets/chapter-6/subscriptionpaymenttest1.png)

**Payment Status Tests:**
![PaymentStatusTest](./assets/chapter-6/paymentstatustest1.png)

**Driver Profile Tests:**
![DriverProfileTest](./assets/chapter-6/drivertest1.png)

**Parking Owner Profile Tests:**
![ParkingOwnerTest](./assets/chapter-6/parkingownertest1.png)

**DNI Validator Tests:**
![DNIValidatorTest](./assets/chapter-6/dnitest1.png)

**Phone Validator Tests:**
![PhoneValidatorTest](./assets/chapter-6/phonetest1.png)

**RUC Validator Tests:**
![RUCValidatorTest](./assets/chapter-6/ructest1.png)

### 6.1.2. Core Integration Tests.

**Authentication Integration Tests:**

![AuthIntegrationTest](./assets/chapter-6/AuthIntegrationTest1.png)
![AuthIntegrationTest](./assets/chapter-6/AuthIntegrationTest2.png)
![AuthIntegrationTest](./assets/chapter-6/AuthIntegrationTest3.png)
![AuthIntegrationTest](./assets/chapter-6/AuthIntegrationTest4.png)

### 6.1.3. Core Behavior-Driven Development.

En esta sección se muestran las pruebas BDD realizadas en base a las User Stories desarrolladas para nuestra solución haciendo uso del lenguaje Gherkin y de la herramienta Cucumber.

**Auth Test:**

![featureAuthTest](./assets/chapter-6/featureAuthTest.png)

![AuthTest](./assets/chapter-6/AuthTest.png)

<br>

**Driver Profile Test:**

![featureDriverProfileTest](./assets/chapter-6/featureDriverProfileTest.png)

![DriverProfileTest](./assets/chapter-6/DriverProfileTest.png)

<br>

**Parking Management Test:**

![featureParkingManagement](./assets/chapter-6/featureParkingManagement.png)

![ParkingManagementTest](./assets/chapter-6/ParkingManagementTest.png)

<br>

**Reservation Payment Test:**

![featureReservationPaymentTest](./assets/chapter-6/featureReservationPaymentTest.png)

![ReservationPaymentTest](./assets/chapter-6/ReservationPaymentTest.png)

### 6.1.4. Core System Tests.

**Registro e Inicio de de sesión del Usuario:**

![SignUpCoreTest](./assets/chapter-6/SignUpCoreTest.png)

![SignInCoreTest](./assets/chapter-6/SignInCoreTest.png)

<br>

**Listado de usuarios:**

![GetUsersCoreTest](./assets/chapter-6/GetUsersCoreTest.png)

<br>

**Registro, actualización de estado y listado de Pago por Reserva de Espacio de Estacionamiento:**

![AddReservationPaymentCoreTest](./assets/chapter-6/AddReservationPaymentCoreTest.png)

![PutReservationPaymentStatusCoreTest](./assets/chapter-6/PutReservationPaymentStatusCoreTest.png)

![GetReservationPaymentsCoreTest](./assets/chapter-6/GetReservationPaymentsCoreTest.png)

<br>

**Registro de perfiles de Propietario de Estacionamiento:**

![CreateParkingOwnerProfileCoreTest](./assets/chapter-6/CreateParkingOwnerProfileCoreTest.png)

<br>

**Registro de perfiles de Conductor:**

![CreateDriverProfileCoreTest](./assets/chapter-6/CreateDriverProfileCoreTest.png)

<br>

**Registro de Estacionamientos y espacios disponibles:**

![CreateParkingCoreTest](./assets/chapter-6/CreateParkingCoreTest.png)

![CreateParkingSpotCoreTest](./assets/chapter-6/CreateParkingSpotCoreTest.png)

![GetParkingsCoreTest](./assets/chapter-6/GetParkingsCoreTest.png)


## 6.2. Static testing & Verification

### 6.2.1. Static Code Analysis

Se realizó un proceso de verificación de estándares de codificación para garantizar que todo el código cumpla con estándares que mantengan la calidad, consistencia y buenas prácticas. En el desarrollo de nuestra solución, nos aseguramos de que el frontend en Angular cumpla con las reglas de ESLint y las guías oficiales de Angular. Para la aplicación móvil desarrollado con Flutter (Dart) seguimos las convenciones del Dart Style Guide. En el backend desarrollado con Java y Spring Boot, se siguieron convenciones de codificación de Java (como las definidas por Oracle) y las buenas prácticas recomendadas por Spring Framework, manteniendo una correcta organización de paquetes, uso adecuado de anotaciones y una clara documentación del código.

Esta verificación nos permite identificar a tiempo errores comunes, malas prácticas o inconsistencias, garantizando que el código sea legible, mantenible y cumpla con los estándares definidos para cada tecnología antes de su integración o despliegue.

#### 6.2.1.1. Coding standard & Code conventions.

Para garantizar la consistencia, mantenibilidad y escalabilidad en el desarrollo de nuestra solución, establecimos estándares y convenciones de codificación alineados con las mejores prácticas de cada tecnología empleada. Estos lineamientos abarcan desde la estructura de archivos hasta el uso de patrones de diseño, con el objetivo de mantener un código limpio, legible y coherente en todo el proyecto.

**Domain-Driven Design (DDD):** Se aplicó arquitectura DDD orientada a dominios para estructurar el código por bounded contexts. Implementamos agregados como Driver y un lenguaje ubicuo que refleja los conceptos del negocio, facilitando la comprensión y evolución del sistema.

**Convenciones de Nomenclatura:**

- **Frontend (Angular):** Usamos KebabCase para componentes (ej: parking-profile), sufijos como .service.ts para servicios, y organizamos módulos por funcionalidades.

- **Mobile (Flutter - Dart):** Aplicamos SnakeCase para clases (ej: loading_spinner), lowerCamelCase para variables y métodos, siguiendo las guías oficiales del Dart Style Guide.

- **Backend (Java - Spring Boot):** Adoptamos PascalCase para clases (ej: DriverProfileControlller), camelCase para variables y métodos, y empaquetamos el código por dominio (ej: com.quadrapp.profile).

**Principios SOLID:** Nos aseguramos de aplicar los principios SOLID en todas las capas, promoviendo la modularidad y la extensibilidad. Ejemplos incluyen clases con una sola responsabilidad (DriverProfileCommandServiceImpl), el uso de inyección de dependencias (Spring DI y Angular DI) y la creación de interfaces extensibles para favorecer la reutilización y el bajo acoplamiento.

De esta forma, garantizamos un código coherente, mantenible y fácil de escalar, asegurando que cada parte del sistema pueda evolucionar sin comprometer la calidad ni la estabilidad general del proyecto.

#### 6.2.1.2. Code Quality & Code Security.

Para asegurar la confiabilidad, mantenibilidad y robustez de nuestra solución Quadrapp, se realizaron verificaciones sobre la calidad y seguridad de todo el código, donde se establecieron prácticas y herramientas que nos permiten detectar problemas tempranos y garantizar un código limpio y seguro antes de su despliegue.

**Calidad del Código:**
Evaluamos la calidad mediante métricas como complejidad ciclomática, duplicación, mantenibilidad y cobertura de pruebas. Se emplearon herramientas de análisis estático como SonarQube y SonarLint para identificar code smells, secciones duplicadas y violaciones de principios SOLID tanto en el backend (Spring Boot) como en el frontend (Angular).

Además, en los entornos de deesarrollo (IntelliJ y VsCode), integramos extensiones que nos permiten detectar y corregir problemas en tiempo real, lo que ayudó a mantener un código consistente y alineado con los estándares definidos.

**Seguridad del Código:**
Para proteger los datos y prevenir vulnerabilidades críticas, seguimos las recomendaciones del estándar OWASP Top 10.

Implementamos:

- Validaciones estrictas de entrada en formularios para evitar inyecciones de datos o ataques XSS.

- Autenticación y autorización mediante JWT, asegurando que los endpoints sensibles solo sean accesibles por usuarios autorizados.

- Uso de parámetros enlazados en Spring Data JPA, previniendo inyecciones SQL.

- Cifrado y manejo seguro de datos sensibles, como contraseñas y tokens.

Estas medidas, junto con el análisis continuo de calidad y seguridad, nos permitieron construir un sistema robusto, con bajo nivel de vulnerabilidades y alta mantenibilidad, fortaleciendo la confianza y estabilidad del producto final.


### 6.2.2. Reviews

---

## 6.3. Validation Interviews.

### 6.3.1. Diseño de Entrevistas.

### 6.3.2. Registro de Entrevistas.

#### Entrevistas Segmento Conductor:

**Entrevista 1**:

Datos del entrevistado

- Nombres y apellidos:
- Edad:
- Recidencia:
- Enlace de la entrevista:
- Duración de la entrevista:

[Imagen](link)

- Resumen de la entrevista:

**Entrevista 2**:

Datos del entrevistado

- Nombres y apellidos:
- Edad:
- Recidencia:
- Enlace de la entrevista:
- Duración de la entrevista:

[Imagen](link)

- Resumen de la entrevista:

**Entrevista 3**:

Datos del entrevistado

- Nombres y apellidos:
- Edad:
- Recidencia:
- Enlace de la entrevista:
- Duración de la entrevista:

[Imagen](link)

- Resumen de la entrevista:

#### Entrevistas Segmento Propietario de Estacionamiento:

**Entrevista 1**:

Datos del entrevistado

- Nombres y apellidos:
- Edad:
- Recidencia:
- Enlace de la entrevista:
- Duración de la entrevista:

[Imagen](link)

- Resumen de la entrevista:

**Entrevista 2**:

Datos del entrevistado

- Nombres y apellidos:
- Edad:
- Recidencia:
- Enlace de la entrevista:
- Duración de la entrevista:

[Imagen](link)

- Resumen de la entrevista:

**Entrevista 3**:

Datos del entrevistado

- Nombres y apellidos:
- Edad:
- Recidencia:
- Enlace de la entrevista:
- Duración de la entrevista:

[Imagen](link)

- Resumen de la entrevista:

### 6.3.3. Evaluaciones según heurísticas.


## 6.4. Auditoría de Experiencias de Usuario.

### 6.4.1. Auditoría realizada.

#### 6.4.1.1. Información del grupo auditado.

#### 6.4.1.2. Cronograma de auditoría realizada.

#### 6.4.1.3. Contenido de auditoría realizada.

### 6.4.2. Auditoría recibida.

#### 6.4.2.1. Información del grupo auditor.

#### 6.4.2.2. Cronograma de auditoría recibida.

#### 6.4.2.3. Contenido de auditoría recibida.

#### 6.4.2.4. Resumen de modificaciones para subsanar hallazgos.

