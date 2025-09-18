# Capítulo III: Requirements Specification

## 3.1. To-Be Scenario Mapping.

Para la elaboración del To-Be Scenario Mapping, el equipo definió el flujo de trabajo esperado después de la implementación de la solución EcoMovil, considerando ambos segmentos objetivos. Este artefacto tiene como finalidad contrastar los resultados deseados con los aspectos negativos identificados en el As-is Scenario, proporcionando una visión clara de las mejoras proyectadas.
<br>

**Segmento Conductores Particulares:**

En el caso de los Conductores Particulares, el To-Be Scenario Mapping describe los beneficios esperados para los usuarios que requieren un acceso ágil y eficiente a los estacionamientos. Se plantea un escenario óptimo en el que los conductores habituales puedan estacionar de manera rápida, sencilla y sin complicaciones, mejorando significativamente su experiencia de uso en comparación con la situación actual.

![ToBeScenarioMapping-Segmento1](assets/ToBeScenarioMapping-Segmento1.PNG)

<br>

**Propietarios de Estacionamientos:**

En relación con los Propietarios de Estacionamientos, el To-Be Scenario Mapping expone los resultados esperados tras la implementación de la solución Quadrapp, orientados a optimizar la gestión, el control de espacios y la eficiencia operativa. Este artefacto busca mostrar la manera en que se superan las limitaciones identificadas en el As-is Scenario, aportando mejoras tanto en la administración como en la experiencia de los usuarios.

El escenario ideal proyecta que los propietarios puedan administrar sus estacionamientos de forma ágil, rentable y sin complicaciones, garantizando un mayor aprovechamiento de los espacios y ofreciendo una experiencia de servicio más satisfactoria para los conductores.

![ToBeScenarioMapping-Segmento2](assets/ToBeScenarioMapping-Segmento2.PNG)

## 3.2. User Stories.

Las *User Stories* del proyecto **Quadrapp** están diseñadas para optimizar la experiencia del usuario final y facilitar las tareas del equipo de desarrollo. Estas historias abarcan diversos aspectos de la plataforma, incluyendo la landing page, la integración y optimización del backend, así como el desarrollo de interfaces de usuario eficientes para el frontend y la aplicación móvil. Cada historia se redacta de manera clara y comprensible, e incluye criterios de aceptación específicos que orientan el desarrollo y garantizan que las funcionalidades implementadas cumplan con los requisitos del negocio y las expectativas del usuario final.

<table border="1" cellspacing="0" cellpadding="5">
  <tr>
    <td>Story ID</td>
    <td>User</td>
    <td>Priority</td>
    <td>Epic</td>
  </tr>
  <tr>
    <td>US01</td>
    <td>Visitante</td>
    <td>Alta</td>
    <td>EP01</td>
  </tr>
  <tr>
    <td>Title</td>
    <td colspan="3">Navegación Intuitiva en la Landing Page</td>
  </tr>
  <tr>
    <td colspan="4">Description</td>
  </tr>
  <tr>
    <td colspan="4">Como visitante de Quadrapp, quiero que la landing page tenga una barra de navegación clara y accesible para encontrar fácilmente las secciones importantes.</td>
  </tr>
  <tr>
    <td colspan="4">Acceptance Criteria</td>
  </tr>
  <tr>
    <td colspan="4">Escenario 01: </strong>  Given que estoy en la landing page, When hago clic en el menú de navegación, Then debería ver opciones claras como "Inicio", "Características", "Reservar Espacio" y "Contáctenos". <br> Escenario 02: Given que navego por la página, When paso el mouse por los elementos del menú, Then deberían resaltarse para indicar que son interactivos.</td>
  </tr>

  <tr>
    <td>US02</td>
    <td>Visitante</td>
    <td>Alta</td>
    <td>EP04</td>
  </tr>
  <tr>
    <td>Title</td>
    <td colspan="3">Visualización de Ciudades con Servicio</td>
  </tr>
  <tr>
    <td colspan="4">Description</td>
  </tr>
  <tr>
    <td colspan="4">Como visitante, quiero ver en la landing page las ciudades donde Quadrapp está disponible para saber si puedo utilizar el servicio en mi ubicación.</td>
  </tr>
  <tr>
    <td colspan="4">Acceptance Criteria</td>
  </tr>
  <tr>
    <td colspan="4">Escenario 01: Given que estoy en la landing page, When desplazo hacia la sección de ciudades, Then debería ver información sobre las ciudades como Lima, Arequipa y Cusco. <br> Escenario 02: Given que selecciono una ciudad, When hago clic en la información de la ciudad, Then debería ver detalles adicionales de esa ubicación.
  </tr>

  <tr>
    <td>US03</td>
    <td>Visitante</td>
    <td>Alta</td>
    <td>EP05</td>
  </tr>
  <tr>
    <td>Title</td>
    <td colspan="3">Promociones Destacadas</td>
  </tr>
  <tr>
    <td colspan="4">Description</td>
  </tr>
  <tr>
    <td colspan="4">Como visitante, quiero ver promociones destacadas en la landing page para aprovechar descuentos y beneficios en las ciudades disponibles.</td>
  </tr>
  <tr>
    <td colspan="4">Acceptance Criteria</td>
  </tr>
  <tr>
    <td colspan="4">Escenario 01: Given que estoy en la landing page, When desplazo hacia la sección de promociones, Then debería ver promociones específicas como "Promoción en Lima" y "Promoción en Cusco". <br> Escenario 02: Given que hago clic en una promoción, When selecciono una promoción específica, Then debería llevarme a una página de detalles de la promoción.
  </tr>

  <tr>
    <td>US04</td>
    <td>Visitante</td>
    <td>Alta</td>
    <td>EP04</td>
  </tr>
  <tr>
    <td>Title</td>
    <td colspan="3">Beneficios para Conductores y Dueños de estacionamiento</td>
  </tr>
  <tr>
    <td colspan="4">Description</td>
  </tr>
  <tr>
    <td colspan="4">Como visitante, quiero ver una sección en la landing page que me explique los beneficios de usar Quadrapp para entender las ventajas que ofrece.</td>
  </tr>
  <tr>
    <td colspan="4">Acceptance Criteria</td>
  </tr>
  <tr>
    <td colspan="4">Escenario 01: Given que estoy en la landing page, When desplazo hacia la sección de beneficios, Then debería ver información sobre beneficios para conductores y dueños de estacionamiento. <br> Escenario 02: Given que quiero más detalles, When hago clic en un beneficio específico, Then debería expandirse con más información.
  </tr>

  <tr>
    <td>US05</td>
    <td>Visitante</td>
    <td>Alta</td>
    <td>EP06</td>
  </tr>
  <tr>
    <td>Title</td>
    <td colspan="3">Visualización de Misión de la Empresa</td>
  </tr>
  <tr>
    <td colspan="4">Description</td>
  </tr>
  <tr>
    <td colspan="4">Como visitante, quiero ver una sección en la landing page que me explique los beneficios de usar Quadrapp para entender las ventajas que ofrece.</td>
  </tr>
  <tr>
    <td colspan="4">Acceptance Criteria</td>
  </tr>
  <tr>
    <td colspan="4">Escenario 01: Given que estoy en la landing page, When desplazo hacia la sección de beneficios, Then debería ver información sobre beneficios para conductores y dueños de estacionamiento. <br> Escenario 02: Given que quiero más detalles, When hago clic en un beneficio específico, Then debería expandirse con más información.
  </tr>

  <tr>
    <td>US06</td>
    <td>Visitante</td>
    <td>Alta</td>
    <td>EP06</td>
  </tr>
  <tr>
    <td>Title</td>
    <td colspan="3">Visualización de Visión de la Empresa</td>
  </tr>
  <tr>
    <td colspan="4">Description</td>
  </tr>
  <tr>
    <td colspan="4">Como visitante, quiero ver la visión de Quadrapp en la landing page para conocer sus metas futuras y crecimiento.</td>
  </tr>
  <tr>
    <td colspan="4">Acceptance Criteria</td>
  </tr>
  <tr>
    <td colspan="4">Escenario 01: Given que estoy en la landing page, When desplazo hacia la sección de"Visión",Then debería ver una breve descripción de la visión de la empresa. <br> Escenario 02: Given que quiero conocer más detalles, When hago clic en "Leer más" en la sección de visión, Then debería ver una descripción completa de los objetivos futuros.
  </tr>

  <tr>
    <td>US07</td>
    <td>Visitante</td>
    <td>Alta</td>
    <td>EP04</td>
  </tr>
  <tr>
    <td>Title</td>
    <td colspan="3">Visualización del Equipo</td>
  </tr>
  <tr>
    <td colspan="4">Description</td>
  </tr>
  <tr>
    <td colspan="4">Como visitante, quiero ver una sección que muestre a los miembros del equipo de Quadrapp para conocer quiénes están detrás del proyecto.</td>
  </tr>
  <tr>
    <td colspan="4">Acceptance Criteria</td>
  </tr>
  <tr>
    <td colspan="4">Escenario 01: Given que estoy en la landing page, When desplazo hacia la sección "Our Team", Then debería ver fotos y descripciones de cada miembro del equipo. <br> Escenario 02: Given que estoy en la sección del equipo, When hago clic en la imagen de un miembro, Then debería ver información detallada sobre sus roles y experiencia. 
  </tr>

  <tr>
    <td>US08</td>
    <td>Visitante</td>
    <td>Alta</td>
    <td>EP07</td>
  </tr>
  <tr>
    <td>Title</td>
    <td colspan="3">Información de Contacto</td>
  </tr>
  <tr>
    <td colspan="4">Description</td>
  </tr>
  <tr>
    <td colspan="4">Como visitante, quiero ver una sección de contacto en la landing page para saber cómo comunicarme con Quadrapp si tengo preguntas o comentarios.</td>
  </tr>
  <tr>
    <td colspan="4">Acceptance Criteria</td>
  </tr>
  <tr>
    <td colspan="4">Escenario 01: Given que estoy en la landing page, When desplazo hacia la sección "Contact Us", Then debería ver un formulario para ingresar nombre, correo electrónico y mensaje. <br> Escenario 02: Given que estoy en la sección de contacto, When hago clic en "Enviar Mensaje" sin llenar todos los campos, Then debería ver un mensaje de error indicando que todos los campos son obligatorios. 
  </tr>

  <tr>
    <td>US09</td>
    <td>Visitante</td>
    <td>Alta</td>
    <td>EP07</td>
  </tr>
  <tr>
    <td>Title</td>
    <td colspan="3">Envío de Mensaje de Contacto</td>
  </tr>
  <tr>
    <td colspan="4">Description</td>
  </tr>
  <tr>
    <td colspan="4">Como visitante, quiero poder enviar un mensaje a Quadrapp desde la landing page para hacer preguntas o dar feedback.</td>
  </tr>
  <tr>
    <td colspan="4">Acceptance Criteria</td>
  </tr>
  <tr>
    <td colspan="4">Escenario 01: Given que estoy en la sección de contacto, When ingreso mi nombre, correo y mensaje y hago clic en "Enviar Mensaje", Then debería ver una confirmación de que el mensaje fue enviado exitosamente. <br> Escenario 02: Given que he enviado un mensaje, When el envío es exitoso, Then debería recibir un correo de confirmación indicando que Quadrapp ha recibido mi mensaje.
  </tr>

<tr>
  <td>US10</td>
  <td>Visitante</td>
  <td>Alta</td>
  <td>EP04</td>
</tr>
<tr>
  <td>Title</td>
  <td colspan="3">Visualización de Información de Características</td>
</tr>
<tr>
  <td colspan="4">Description</td>
</tr>
<tr>
  <td colspan="4">Como visitante, quiero ver las características de Quadrapp en la landing page para entender qué ofrece el servicio.</td>
</tr>
<tr>
  <td colspan="4">Acceptance Criteria</td>
</tr>
<tr>
  <td colspan="4">Escenario 01: Given que estoy en la landing page, When desplazo hacia la sección de características, Then debería ver una descripción de las características principales de Quadrapp. <br> Escenario 02: Given que quiero conocer más detalles, When hago clic en una característica específica, Then debería abrirse una ventana emergente con información adicional.</td>
</tr>

<tr>
  <td>US11</td>
  <td>Visitante</td>
  <td>Alta</td>
  <td>EP02</td>
</tr>
<tr>
  <td>Title</td>
  <td colspan="3">Botón de Registro e Inicio de Sesión</td>
</tr>
<tr>
  <td colspan="4">Description</td>
</tr>
<tr>
  <td colspan="4">Como visitante, quiero ver botones destacados de "Registrarse" e "Iniciar Sesión" en la landing page para acceder a la plataforma o crear una cuenta fácilmente.</td>
</tr>
<tr>
  <td colspan="4">Acceptance Criteria</td>
</tr>
<tr>
  <td colspan="4">Escenario 01: Given que estoy en la landing page, When veo la sección superior de la página, Then deberían estar visibles los botones de "Iniciar Sesión" y "Registrarse". <br> Escenario 02: Given que hago clic en "Iniciar Sesión", When no tengo una cuenta creada, Then debería ver una opción para registrarme rápidamente.</td>
</tr>

<tr>
  <td>US12</td>
  <td>Visitante</td>
  <td>Media</td>
  <td>EP06</td>
</tr>
<tr>
  <td>Title</td>
  <td colspan="3">Enlace a Redes Sociales</td>
</tr>
<tr>
  <td colspan="4">Description</td>
</tr>
<tr>
  <td colspan="4">Como visitante, quiero ver enlaces a las redes sociales de Quadrapp en la landing page para seguir sus novedades y actualizaciones.</td>
</tr>
<tr>
  <td colspan="4">Acceptance Criteria</td>
</tr>
<tr>
  <td colspan="4">Escenario 01: Given que estoy en la landing page, When desplazo hacia el pie de página, Then debería ver íconos de redes sociales que me lleven a las cuentas oficiales de Quadrapp. <br> Escenario 02: Given que hago clic en un ícono de redes sociales, When selecciono Facebook, Then debería redirigirme a la página oficial de Quadrapp en Facebook.</td>
</tr>

<tr>
  <td>US13</td>
  <td>Visitante</td>
  <td>Media</td>
  <td>EP04</td>
</tr>
<tr>
  <td>Title</td>
  <td colspan="3">Visualización de Slogan</td>
</tr>
<tr>
  <td colspan="4">Description</td>
</tr>
<tr>
  <td colspan="4">Como visitante, quiero ver un slogan atractivo en la landing page de Quadrapp para entender de inmediato la propuesta del servicio.</td>
</tr>
<tr>
  <td colspan="4">Acceptance Criteria</td>
</tr>
<tr>
  <td colspan="4">Escenario 01: Given que estoy en la landing page, When veo la sección principal, Then debería encontrar un slogan o mensaje atractivo que me introduzca al servicio. <br> Escenario 02: Given que el slogan aparece en la sección principal, When paso a otra sección y vuelvo a la principal, Then el slogan debería mantenerse visible.</td>
</tr>

<tr>
  <td>US14</td>
  <td>Visitante</td>
  <td>Media</td>
  <td>EP13</td>
</tr>
<tr>
  <td>Title</td>
  <td colspan="3">Acceso a Información Legal</td>
</tr>
<tr>
  <td colspan="4">Description</td>
</tr>
<tr>
  <td colspan="4">Como visitante, quiero ver enlaces a la información legal y políticas de privacidad en la landing page para revisar los términos de uso y la protección de mis datos.</td>
</tr>
<tr>
  <td colspan="4">Acceptance Criteria</td>
</tr>
<tr>
  <td colspan="4">Escenario 01: Given que estoy en la landing page, When desplazo hacia el pie de página, Then debería ver enlaces a las políticas de privacidad y términos de servicio. <br> Escenario 02: Given que hago clic en el enlace de política de privacidad, When se abre el documento, Then debería ver la información completa de privacidad en una nueva página o ventana.</td>
</tr>

<tr>
  <td>US15</td>
  <td>Conductor</td>
  <td>Alta</td>
  <td>EP11</td>
</tr>
<tr>
  <td>Title</td>
  <td colspan="3">Inicio de Sesión para Conductores</td>
</tr>
<tr>
  <td colspan="4">Description</td>
</tr>
<tr>
  <td colspan="4">Como conductor interesado en usar Quadrapp, quiero iniciar sesión con mi cuenta registrada anteriormente para acceder a la aplicación.</td>
</tr>
<tr>
  <td colspan="4">Acceptance Criteria</td>
</tr>
<tr>
  <td colspan="4">Escenario 01: Given que el conductor ingresa su correo y contraseña, When hace clic en "Iniciar sesión", Then debe acceder a su dashboard de conductor si las credenciales son correctas. <br> Escenario 02: Given que el conductor ingresa credenciales incorrectas, When intenta iniciar sesión, Then debe mostrarse un mensaje de error indicando que las credenciales son inválidas.</td>
</tr>

<tr>
  <td>US16</td>
  <td>Conductor</td>
  <td>Alta</td>
  <td>EP02</td>
</tr>
<tr>
  <td>Title</td>
  <td colspan="3">Registro de Conductores</td>
</tr>
<tr>
  <td colspan="4">Description</td>
</tr>
<tr>
  <td colspan="4">Como conductor interesado en usar Quadrapp, quiero registrar mi cuenta para acceder a la plataforma.</td>
</tr>
<tr>
  <td colspan="4">Acceptance Criteria</td>
</tr>
<tr>
  <td colspan="4">Escenario 01: Given que un nuevo conductor quiere registrarse, When ingresa los datos necesarios y hace clic en "Registrarse", Then debe recibir un mensaje de confirmación de cuenta creada. <br> Escenario 02: Given que el conductor intenta registrarse sin llenar los campos requeridos, When intenta completar el registro, Then debe mostrarse un mensaje de error solicitando los datos faltantes.</td>
</tr>

<tr>
  <td>US17</td>
  <td>Propietario de estacionamiento</td>
  <td>Alta</td>
  <td>EP02</td>
</tr>
<tr>
  <td>Title</td>
  <td colspan="3">Registro de Propietarios de estacionamiento</td>
</tr>
<tr>
  <td colspan="4">Description</td>
</tr>
<tr>
  <td colspan="4">Como propietario de estacionamiento, quiero registrar mi cuenta para hacer uso de las funcionalidades que me ofrece Quadrapp.</td>
</tr>
<tr>
  <td colspan="4">Acceptance Criteria</td>
</tr>
<tr>
  <td colspan="4">Escenario 01: Given que un dueño de estacionamiento quiere registrarse, When llena el formulario de registro y hace clic en "Registrarse", Then debe recibir un mensaje de confirmación de cuenta creada. <br> Escenario 02: Given que el formulario no está completo, When intenta registrarse, Then debe mostrarse un mensaje de error indicando los campos faltantes.</td>
</tr>

<tr>
  <td>US18</td>
  <td>Conductor</td>
  <td>Media</td>
  <td>EP04</td>
</tr>
<tr>
  <td>Title</td>
  <td colspan="3">Búsqueda de Reservas para Conductores</td>
</tr>
<tr>
  <td colspan="4">Description</td>
</tr>
<tr>
  <td colspan="4">Como conductor, quiero hacer uso de la búsqueda de reservas para visualizar mis reservas activas y pasadas.</td>
</tr>
<tr>
  <td colspan="4">Acceptance Criteria</td>
</tr>
<tr>
  <td colspan="4">Escenario 01: Given que el conductor quiere ver sus reservas, When ingresa al menú de reservas, Then debe ver una lista de todas sus reservas activas y completadas. <br> Escenario 02: Given que el conductor busca una reserva específica, When ingresa un criterio de búsqueda, Then debe mostrarse la reserva correspondiente si existe.</td>
</tr>

<tr>
  <td>US19</td>
  <td>Conductor</td>
  <td>Alta</td>
  <td>EP12</td>
</tr>
<tr>
  <td>Title</td>
  <td colspan="3">Pago de Reservas por Transacción</td>
</tr>
<tr>
  <td colspan="4">Description</td>
</tr>
<tr>
  <td colspan="4">Como conductor, quiero realizar el pago de mis reservas por transacción para completar mis reservas.</td>
</tr>
<tr>
  <td colspan="4">Acceptance Criteria</td>
</tr>
<tr>
  <td colspan="4">Escenario 01: Given que el conductor realiza una reserva, When selecciona "Pagar", Then debe ser dirigido a la pasarela de pago para completar la transacción. <br> Escenario 02: Given que el pago es exitoso, When se procesa el pago, Then debe recibir una confirmación de reserva y recibo de pago.</td>
</tr>

<tr>
  <td>US20</td>
  <td>Conductor</td>
  <td>Alta</td>
  <td>EP12</td>
</tr>
<tr>
  <td>Title</td>
  <td colspan="3">Confirmación de Reserva Registrada</td>
</tr>
<tr>
  <td colspan="4">Description</td>
</tr>
<tr>
  <td colspan="4">Como conductor, quiero que se muestre una pantalla de confirmación para asegurarme de que la reserva fue registrada correctamente.</td>
</tr>
<tr>
  <td colspan="4">Acceptance Criteria</td>
</tr>
<tr>
  <td colspan="4">Escenario 01: Given que el conductor completa una reserva, When el sistema confirma la transacción, Then debe ver una pantalla indicando que su reserva fue registrada con éxito. <br> Escenario 02: Given que el sistema no puede confirmar la reserva, When se produce un error en el pago, Then debe mostrarse un mensaje solicitando un nuevo intento de pago.</td>
</tr>

<tr>
  <td>US21</td>
  <td>Usuario</td>
  <td>Media</td>
  <td>EP11</td>
</tr>
<tr>
  <td>Title</td>
  <td colspan="3">Registro de Opiniones</td>
</tr>
<tr>
  <td colspan="4">Description</td>
</tr>
<tr>
  <td colspan="4">Como usuario, quiero registrar mis opiniones para dar mi retroalimentación sobre mis experiencias con las funcionalidades de la plataforma.</td>
</tr>
<tr>
  <td colspan="4">Acceptance Criteria</td>
</tr>
<tr>
  <td colspan="4">Escenario 01: Given que el usuario quiere dejar una opinión, When completa el formulario de opinión y hace clic en "Enviar", Then debe ver un mensaje de confirmación de que su opinión fue enviada. <br> Escenario 02: Given que el usuario intenta enviar una opinión sin completar los campos requeridos, When hace clic en "Enviar", Then debe recibir un mensaje indicando que los campos son obligatorios.</td>
</tr>

<tr>
  <td>US22</td>
  <td>Conductor</td>
  <td>Media</td>
  <td>EP09</td>
</tr>
<tr>
  <td>Title</td>
  <td colspan="3">Notificaciones en el Dashboard del Conductor</td>
</tr>
<tr>
  <td colspan="4">Description</td>
</tr>
<tr>
  <td colspan="4">Como conductor, quiero recibir notificaciones en mi dashboard para recibir alertas relevantes como ofertas o recordatorios de reservas.</td>
</tr>
<tr>
  <td colspan="4">Acceptance Criteria</td>
</tr>
<tr>
  <td colspan="4">Escenario 01: Given que el conductor ingresa a su dashboard, When hay notificaciones pendientes, Then debe ver un ícono indicando nuevas notificaciones. <br> Escenario 02: Given que el conductor visualiza una notificación, When hace clic en ella, Then debe acceder a detalles adicionales o redirigirse a la página correspondiente.</td>
</tr>

<tr>
  <td>US23</td>
  <td>Usuario</td>
  <td>Media</td>
  <td>EP08</td>
</tr>
<tr>
  <td>Title</td>
  <td colspan="3">Configuración de Preferencias de Usuario</td>
</tr>
<tr>
  <td colspan="4">Description</td>
</tr>
<tr>
  <td colspan="4">Como usuario, quiero configurar mis preferencias de uso para personalizar mi experiencia en la plataforma.</td>
</tr>
<tr>
  <td colspan="4">Acceptance Criteria</td>
</tr>
<tr>
  <td colspan="4">Escenario 01: Given que el usuario quiere modificar sus preferencias, When accede a "Configuración" y guarda los cambios, Then su perfil debe actualizarse con las nuevas preferencias. <br> Escenario 02: Given que el usuario cambia sus preferencias de notificación, When guarda la configuración, Then debe recibir notificaciones de acuerdo con sus preferencias.</td>
</tr>

<tr>
  <td>US24</td>
  <td>Conductor</td>
  <td>Media</td>
  <td>EP04</td>
</tr>
<tr>
  <td>Title</td>
  <td colspan="3">Historial de Reservas en el Dashboard del Conductor</td>
</tr>
<tr>
  <td colspan="4">Description</td>
</tr>
<tr>
  <td colspan="4">Como conductor, quiero visualizar mi historial de reservas para consultar mis reservas realizadas.</td>
</tr>
<tr>
  <td colspan="4">Acceptance Criteria</td>
</tr>
<tr>
  <td colspan="4">Escenario 01: Given que el conductor quiere revisar su historial, When accede a la sección de historial de reservas, Then debe ver una lista de todas sus reservas previas. <br> Escenario 02: Given que el conductor busca una reserva específica en el historial, When ingresa una fecha o nombre de estacionamiento, Then debería encontrar la reserva correspondiente.</td>
</tr>

<tr>
  <td>US25</td>
  <td>Conductor</td>
  <td>Media</td>
  <td>EP04</td>
</tr>
<tr>
  <td>Title</td>
  <td colspan="3">Alerta de Espacio Disponible</td>
</tr>
<tr>
  <td colspan="4">Description</td>
</tr>
<tr>
  <td colspan="4">Como conductor, quiero recibir alertas de disponibilidad de espacios para ser notificado cuando un espacio de mi interés esté disponible.</td>
</tr>
<tr>
  <td colspan="4">Acceptance Criteria</td>
</tr>
<tr>
  <td colspan="4">Escenario 01: Given que el conductor marca un estacionamiento como favorito, When un espacio en ese estacionamiento se desocupa, Then debería recibir una notificación en su dashboard. <br> Escenario 02: Given que el conductor recibe una alerta de disponibilidad, When hace clic en la notificación, Then debería ser redirigido a la página de reserva para ese espacio.</td>
</tr>

<tr> 
  <td>US26</td> 
  <td>Conductor</td> 
  <td>Alta</td> 
  <td>EP07</td> 
</tr> 
<tr> 
  <td>Title</td> 
  <td colspan="3">Soporte en Tiempo Real en el Dashboard del Conductor</td> 
</tr> 
<tr> 
  <td colspan="4">Description</td> 
</tr> 
<tr> 
  <td colspan="4">Como conductor, quiero un sistema de soporte en tiempo real para poder resolver mis dudas o problemas rápidamente.</td> 
</tr> 
<tr> 
  <td colspan="4">Acceptance Criteria</td> 
</tr> 
<tr> 
  <td colspan="4">Escenario 01: Given que el conductor necesita ayuda, When accede a la sección de soporte en el dashboard, Then debería ver opciones de contacto o un chat en tiempo real. <br> Escenario 02: Given que el conductor inicia una consulta de soporte, When envía su mensaje, Then debería recibir una respuesta o ver un mensaje de confirmación de recibido.</td> 
</tr>

<tr> 
  <td>US27</td> 
  <td>Conductor</td> 
  <td>Alta</td> 
  <td>EP04</td> 
</tr> 
<tr> 
  <td>Title</td> 
  <td colspan="3">Favoritos para Conductores</td> 
</tr> 
<tr> 
  <td colspan="4">Description</td> 
</tr> 
<tr> 
  <td colspan="4">Como conductor, quiero marcar estacionamientos de mi interés como favoritos para facilitar futuras reservas.</td> 
</tr> 
<tr> 
  <td colspan="4">Acceptance Criteria</td> 
</tr> 
<tr> 
  <td colspan="4">Escenario 01: Given que el conductor quiere agregar un estacionamiento a sus favoritos, When hace clic en el botón "Favorito" en el detalle del estacionamiento, Then debería ver el estacionamiento en su lista de favoritos. <br> Escenario 02: Given que el conductor quiere reservar un estacionamiento favorito, When accede a su lista de favoritos, Then debería ver una opción para hacer la reserva directamente.</td> 
</tr>

<tr> 
  <td>US28</td> 
  <td>Conductor</td> 
  <td>Alta</td> 
  <td>EP05</td> 
</tr> 
<tr> 
  <td>Title</td> 
  <td colspan="3">Verificación de Reserva en el Dashboard del Conductor</td> 
</tr> 
<tr> 
  <td colspan="4">Description</td> 
</tr> 
<tr> 
  <td colspan="4">Como conductor, quiero verificar el estado de mi reserva para confirmar si el espacio que deseo está listo para ocuparse.</td> 
</tr> 
<tr> 
  <td colspan="4">Acceptance Criteria</td> 
</tr> 
<tr> 
  <td colspan="4">Escenario 01: Given que el conductor quiere verificar el estado de su reserva, When accede a la sección de reservas activas, Then debe ver un estado que indique si la reserva está confirmada o en proceso. <br> Escenario 02: Given que el estado de la reserva cambia, When el conductor accede a la reserva, Then debe ver la información actualizada de inmediato.</td> 
</tr>

<tr> 
  <td>US29</td> 
  <td>Conductor</td> 
  <td>Alta</td> 
  <td>EP05</td> 
</tr> 
<tr> 
  <td>Title</td> 
  <td colspan="3">Cancelación de Reserva en el Dashboard</td> 
</tr> 
<tr> 
  <td colspan="4">Description</td> 
</tr> 
<tr> 
  <td colspan="4">Como conductor, quiero acceder a la opción de cancelar mi reserva para evitar inconvenientes en caso de cambio de planes.</td> 
</tr> 
<tr> 
  <td colspan="4">Acceptance Criteria</td> 
</tr> 
<tr> 
  <td colspan="4">Escenario 01: Given que el conductor tiene una reserva activa, When selecciona la opción de cancelación, Then debería ver una confirmación de cancelación y una notificación de reembolso si aplica. <br> Escenario 02: Given que el conductor cancela una reserva, When intenta reservar el mismo espacio de nuevo, Then el sistema debe permitir la nueva reserva si el espacio sigue disponible.</td> 
</tr>

<tr> 
  <td>US30</td> 
  <td>Conductor</td> 
  <td>Alta</td> 
  <td>EP09</td> 
</tr> 
<tr> 
  <td>Title</td> 
  <td colspan="3">Gestión de Alertas para Conductores</td> 
</tr> 
<tr> 
  <td colspan="4">Description</td> 
</tr> 
<tr> 
  <td colspan="4">Como conductor, quiero visualizar las alertas en mi dashboard para gestionar mis alertas de seguridad o disponibilidad.</td> 
</tr> 
<tr> 
  <td colspan="4">Acceptance Criteria</td> 
</tr> 
<tr> 
  <td colspan="4">Escenario 01: Given que el conductor tiene alertas pendientes, When accede a la sección de alertas en su dashboard, Then debe ver una lista de alertas recientes. <br> Escenario 02: Given que el conductor revisa una alerta específica, When hace clic en ella, Then debería ver detalles adicionales o sugerencias de acción.</td> 
</tr>

<tr> 
  <td>US31</td> 
  <td>Conductor</td> 
  <td>Alta</td> 
  <td>EP08</td> 
</tr> 
<tr> 
  <td>Title</td> 
  <td colspan="3">Personalización de Notificaciones para Conductores</td> 
</tr> 
<tr> 
  <td colspan="4">Description</td> 
</tr> 
<tr> 
  <td colspan="4">Como conductor, quiero personalizar mis preferencias de notificación para recibir solo las alertas que me interesan.</td> 
</tr> 
<tr> 
  <td colspan="4">Acceptance Criteria</td> 
</tr> 
<tr> 
  <td colspan="4">Escenario 01: Given que el conductor quiere personalizar sus notificaciones, When ajusta sus preferencias en la configuración, Then solo debería recibir las notificaciones seleccionadas. <br> Escenario 02: Given que el conductor cambia sus preferencias, When guarda la configuración, Then las futuras notificaciones deberían respetar estas preferencias.</td> 
</tr>

<tr> 
  <td>US32</td> 
  <td>Conductor</td> 
  <td>Alta</td> 
  <td>EP10</td> 
</tr> 
<tr> 
  <td>Title</td> 
  <td colspan="3">Visualización de Mapa en el Dashboard del Conductor</td> 
</tr> 
<tr> 
  <td colspan="4">Description</td> 
</tr> 
<tr> 
  <td colspan="4">Como conductor, quiero acceder a un mapa interactivo en el dashboard para ver ubicaciones de estacionamientos cercanos en tiempo real.</td> 
</tr> 
<tr> 
  <td colspan="4">Acceptance Criteria</td> 
</tr> 
<tr> 
  <td colspan="4">Escenario 01: Given que el conductor accede a su dashboard, When abre la sección de mapa, Then debería ver ubicaciones de estacionamientos cercanos con disponibilidad en tiempo real. <br> Escenario 02: Given que el conductor selecciona una ubicación en el mapa, When hace clic en ella, Then debería ver opciones para realizar una reserva en esa ubicación.</td> 
</tr>

<tr> 
  <td>US33</td> 
  <td>Conductor</td> 
  <td>Alta</td> 
  <td>EP05</td> 
</tr> 
<tr> 
  <td>Title</td> 
  <td colspan="3">Seguimiento de Reserva en Tiempo Real</td> 
</tr> 
<tr> 
  <td colspan="4">Description</td> 
</tr> 
<tr> 
  <td colspan="4">Como conductor, quiero hacer seguimiento en tiempo real de mi reserva para ver el estado del mismo en todo momento.</td> 
</tr> 
<tr> 
  <td colspan="4">Acceptance Criteria</td> 
</tr> 
<tr> 
  <td colspan="4">Escenario 01: Given que el conductor tiene una reserva activa, When accede a la sección de seguimiento, Then debería ver el estado en tiempo real de su reserva. <br> Escenario 02: Given que el estado de la reserva cambia, When el conductor revisa la reserva, Then debería ver el cambio reflejado de inmediato.</td> 
</tr>

<tr> 
  <td>TS01</td> 
  <td>Developer</td> 
  <td>Gestión de Clientes en Servicio al Cliente</td> 
  <td>EP07</td> 
</tr> 
<tr> 
  <td>Title</td> 
  <td colspan="3">Gestión de Clientes en Servicio al Cliente</td> 
</tr> 
<tr> 
  <td colspan="4">Description</td> 
</tr> 
<tr> 
  <td colspan="4">Como developer, quiero crear un endpoint para gestionar consultas y solicitudes de servicio al cliente para permitir soporte eficaz a los usuarios.</td> 
</tr> 
<tr> 
  <td colspan="4">Acceptance Criteria</td> 
</tr> 
<tr> 
  <td colspan="4">Escenario 01: Given que se recibe una consulta de un cliente, When el administrador accede al endpoint `/api/client-service`, Then debería ver todas las solicitudes pendientes con detalles. <br> Escenario 02: Given que un cliente envía una nueva solicitud, When se crea una nueva consulta en el endpoint, Then debería notificarse al equipo de servicio al cliente.</td> 
</tr>

<tr> 
  <td>TS02</td> 
  <td>Developer</td> 
  <td>Notificación de Cambios en la Disponibilidad de Espacios</td> 
  <td>EP09</td> 
</tr> 
<tr> 
  <td>Title</td> 
  <td colspan="3">Notificación de Cambios en la Disponibilidad de Espacios</td> 
</tr> 
<tr> 
  <td colspan="4">Description</td> 
</tr> 
<tr> 
  <td colspan="4">Como developer, quiero implementar un endpoint que envíe notificaciones automáticas cuando un espacio cambie de estado para mantener a los usuarios informados en tiempo real.</td> 
</tr> 
<tr> 
  <td colspan="4">Acceptance Criteria</td> 
</tr> 
<tr> 
  <td colspan="4">Escenario 01: Given que un espacio de estacionamiento se desocupa, When el sistema detecta el cambio en el endpoint `/api/space-notifications`, Then debería enviar una notificación a los usuarios interesados. <br> Escenario 02: Given que un usuario tiene una reserva, When su espacio cambia de estado, Then debería recibir una notificación push y por correo electrónico.</td> 
</tr>

<tr> 
  <td>TS03</td> 
  <td>Developer</td> 
  <td>Historial de Transacciones para Usuarios</td> 
  <td>EP13</td> 
</tr> 
<tr> 
  <td>Title</td> 
  <td colspan="3">Historial de Transacciones para Usuarios</td> 
</tr> 
<tr> 
  <td colspan="4">Description</td> 
</tr> 
<tr> 
  <td colspan="4">Como developer, quiero desarrollar un endpoint para consultar el historial de transacciones de cada usuario para permitir la revisión de pagos y reservas anteriores.</td> 
</tr> 
<tr> 
  <td colspan="4">Acceptance Criteria</td> 
</tr> 
<tr> 
  <td colspan="4">Escenario 01: Given que un usuario desea ver su historial de transacciones, When accede al endpoint `/api/user-transactions`, Then debería ver una lista de todas sus transacciones ordenadas por fecha. <br> Escenario 02: Given que el administrador necesita revisar las transacciones de un usuario específico, When ingresa el ID del usuario en el endpoint, Then debería obtener el historial detallado del usuario.</td> 
</tr>

<tr> 
  <td>TS04</td> 
  <td>Developer</td> 
  <td>Gestión de Ocupación de Espacios en Tiempo Real</td> 
  <td>EP09</td> 
</tr> 
<tr> 
  <td>Title</td> 
  <td colspan="3">Gestión de Ocupación de Espacios en Tiempo Real</td> 
</tr> 
<tr> 
  <td colspan="4">Description</td> 
</tr> 
<tr> 
  <td colspan="4">Como developer, quiero implementar un endpoint para actualizar automáticamente la disponibilidad de espacios para reflejar cambios en tiempo real según las cámaras de monitoreo visual.</td> 
</tr> 
<tr> 
  <td colspan="4">Acceptance Criteria</td> 
</tr> 
<tr> 
  <td colspan="4">Escenario 01: Given que un espacio cambia de estado, When el sistema detecta el cambio mediante las cámaras de monitoreo visual en el endpoint `/api/space-occupancy`, Then el sistema debería reflejar el estado actualizado en tiempo real. <br> Escenario 02: Given que se ocupa un espacio sin reserva, When las cámaras detectan la ocupación, Then el sistema debería generar una alerta automática al administrador.</td> 
</tr>

<tr> 
  <td>TS05</td> 
  <td>Developer</td> 
  <td>Configuración de Alertas de Seguridad</td> 
  <td>EP13</td> 
</tr> 
<tr> 
  <td>Title</td> 
  <td colspan="3">Configuración de Alertas de Seguridad</td> 
</tr> 
<tr> 
  <td colspan="4">Description</td> 
</tr> 
<tr> 
  <td colspan="4">Como developer, quiero implementar un endpoint para que los administradores configuren alertas de seguridad para responder rápidamente a eventos sospechosos en los espacios de estacionamiento.</td> 
</tr> 
<tr> 
  <td colspan="4">Acceptance Criteria</td> 
</tr> 
<tr> 
  <td colspan="4">Escenario 01: Given que un administrador configura alertas, When ingresa criterios de alerta en el endpoint `/api/security-alerts`, Then debería poder definir parámetros específicos como hora, ubicación y tipo de alerta. <br> Escenario 02: Given que se detecta un evento de seguridad, When se activa una alerta, Then el sistema debe enviar notificaciones automáticas a los responsables.</td> 
</tr>

<tr> 
  <td>TS06</td> 
  <td>Developer</td> 
  <td>Administración de Tarifas por Ubicación</td> 
  <td>EP12</td> 
</tr> 
<tr> 
  <td>Title</td> 
  <td colspan="3">Administración de Tarifas por Ubicación</td> 
</tr> 
<tr> 
  <td colspan="4">Description</td> 
</tr> 
<tr> 
  <td colspan="4">Como developer, quiero implementar un endpoint para configurar tarifas de estacionamiento basadas en la ubicación para que los administradores ajusten precios según la demanda.</td> 
</tr> 
<tr> 
  <td colspan="4">Acceptance Criteria</td> 
</tr> 
<tr> 
  <td colspan="4">Escenario 01: Given que un administrador necesita ajustar tarifas, When accede al endpoint `/api/parking-rates`, Then debería poder configurar tarifas por ciudad o zona. <br> Escenario 02: Given que una tarifa es modificada, When se actualiza en el sistema, Then todos los precios de los espacios correspondientes deberían reflejar el cambio automáticamente.</td> 
</tr>

<tr> 
  <td>TS07</td> 
  <td>Developer</td> 
  <td>Registro de Alertas de Seguridad</td> 
  <td>EP13</td> 
</tr> 
<tr> 
  <td>Title</td> 
  <td colspan="3">Registro de Alertas de Seguridad</td> 
</tr> 
<tr> 
  <td colspan="4">Description</td> 
</tr> 
<tr> 
  <td colspan="4">Como developer, quiero un endpoint para registrar todas las alertas de seguridad detectadas en los estacionamientos para que los administradores revisen incidentes pasados.</td> 
</tr> 
<tr> 
  <td colspan="4">Acceptance Criteria</td> 
</tr> 
<tr> 
  <td colspan="4">Escenario 01: Given que ocurre un incidente de seguridad, When el sistema lo registra en el endpoint `/api/security-log`, Then debería almacenar la fecha, hora, ubicación y tipo de incidente. <br> Escenario 02: Given que un administrador revisa el historial de alertas, When solicita los registros, Then debería ver una lista cronológica de los eventos de seguridad.</td> 
</tr>

<tr> 
  <td>TS08</td> 
  <td>Developer</td> 
  <td>Gestión de Datos de Vehículos</td> 
  <td>EP10</td> 
</tr> 
<tr> 
  <td>Title</td> 
  <td colspan="3">Gestión de Datos de Vehículos</td> 
</tr> 
<tr> 
  <td colspan="4">Description</td> 
</tr> 
<tr> 
  <td colspan="4">Como developer, quiero un endpoint para almacenar y gestionar información de los vehículos registrados para poder hacer seguimiento y gestionar accesos.</td> 
</tr> 
<tr> 
  <td colspan="4">Acceptance Criteria</td> 
</tr> 
<tr> 
  <td colspan="4">Escenario 01: Given que un usuario registra un vehículo, When ingresa los detalles en el endpoint `/api/vehicle-management`, Then debería guardarse en la base de datos. <br> Escenario 02: Given que un administrador necesita actualizar datos de un vehículo, When accede a este endpoint, Then debería poder editar o eliminar la información del vehículo.</td> 
</tr>

<tr> 
  <td>TS09</td> 
  <td>Developer</td> 
  <td>Reportes de Promociones Utilizadas</td> 
  <td>EP05</td> 
</tr> 
<tr> 
  <td>Title</td> 
  <td colspan="3">Reportes de Promociones Utilizadas</td> 
</tr> 
<tr> 
  <td colspan="4">Description</td> 
</tr> 
<tr> 
  <td colspan="4">Como developer, quiero un endpoint para generar reportes de promociones utilizadas para analizar la efectividad de las promociones y optimizar futuras campañas.</td> 
</tr> 
<tr> 
  <td colspan="4">Acceptance Criteria</td> 
</tr> 
<tr> 
  <td colspan="4">Escenario 01: Given que un administrador solicita un reporte de promociones, When accede al endpoint `/api/promotion-reports`, Then debería ver un resumen con el uso de cada promoción. <br> Escenario 02: Given que se requiere un reporte detallado, When el administrador filtra por fecha y ubicación, Then debería obtener un desglose por cada categoría seleccionada.</td> 
</tr>

<tr> 
  <td>TS10</td> 
  <td>Developer</td> 
  <td>Auditoría de Acciones en la Plataforma</td> 
  <td>EP13</td> 
</tr> 
<tr> 
  <td>Title</td> 
  <td colspan="3">Auditoría de Acciones en la Plataforma</td> 
</tr> 
<tr> 
  <td colspan="4">Description</td> 
</tr> 
<tr> 
  <td colspan="4">Como developer, quiero un endpoint para registrar y auditar todas las acciones críticas de los usuarios y administradores para garantizar la seguridad y trazabilidad de las operaciones.</td> 
</tr> 
<tr> 
  <td colspan="4">Acceptance Criteria</td> 
</tr> 
<tr> 
  <td colspan="4">Escenario 01: Given que un usuario realiza una acción crítica, When el sistema registra la acción en el endpoint `/api/audit-log`, Then debería almacenarse con detalles de la fecha, hora, usuario y tipo de acción. <br> Escenario 02: Given que un auditor revisa el historial, When filtra por tipo de acción o usuario, Then debería obtener un listado preciso de todas las acciones que cumplen con los filtros.</td> 
</tr>

<tr> 
  <td>TS11</td> 
  <td>Developer</td> 
  <td>Historial de Opiniones de Usuarios</td> 
  <td>EP11</td> 
</tr> 
<tr> 
  <td>Title</td> 
  <td colspan="3">Historial de Opiniones de Usuarios</td> 
</tr> 
<tr> 
  <td colspan="4">Description</td> 
</tr> 
<tr> 
  <td colspan="4">Como developer, quiero implementar un endpoint para registrar y consultar el historial de opiniones de los usuarios para mejorar la experiencia de usuario a través del feedback.</td> 
</tr> 
<tr> 
  <td colspan="4">Acceptance Criteria</td> 
</tr> 
<tr> 
  <td colspan="4">Escenario 01: Given que un usuario deja una opinión, When el sistema la guarda en el endpoint `/api/user-reviews`, Then debería incluir detalles del usuario, calificación y comentario. <br> Escenario 02: Given que un administrador consulta el historial de opiniones, When accede al endpoint, Then debería ver una lista cronológica de todas las opiniones con detalles.</td> 
</tr>

<tr> 
  <td>TS12</td> 
  <td>Developer</td> 
  <td>Integración con el Sistema de Pago</td> 
  <td>EP13</td> 
</tr> 
<tr> 
  <td>Title</td> 
  <td colspan="3">Integración con el Sistema de Pago</td> 
</tr> 
<tr> 
  <td colspan="4">Description</td> 
</tr> 
<tr> 
  <td colspan="4">Como developer, quiero un endpoint para procesar pagos y verificar transacciones para asegurar que todos los pagos de reservas se realicen de forma segura.</td> 
</tr> 
<tr> 
  <td colspan="4">Acceptance Criteria</td> 
</tr> 
<tr> 
  <td colspan="4">Escenario 01: Given que un usuario realiza un pago, When procesa la transacción en el endpoint `/api/payment-processing`, Then debería generar una respuesta de éxito o error según el resultado. <br> Escenario 02: Given que ocurre un error en el pago, When el sistema detecta la falla, Then debería enviar un mensaje de error detallado y sugerencias de resolución.</td> 
</tr>

<tr> 
  <td>TS13</td> 
  <td>Developer</td> 
  <td>Generación de Reportes de Ocupación</td> 
  <td>EP06</td> 
</tr> 
<tr> 
  <td>Title</td> 
  <td colspan="3">Generación de Reportes de Ocupación</td> 
</tr> 
<tr> 
  <td colspan="4">Description</td> 
</tr> 
<tr> 
  <td colspan="4">Como developer, quiero un endpoint para generar reportes de ocupación de los estacionamientos para analizar el uso y optimizar la disponibilidad de espacios.</td> 
</tr> 
<tr> 
  <td colspan="4">Acceptance Criteria</td> 
</tr> 
<tr> 
  <td colspan="4">Escenario 01: Given que un administrador solicita un reporte, When accede al endpoint `/api/occupancy-reports`, Then debería ver el porcentaje de ocupación por ubicación y fecha. <br> Escenario 02: Given que se necesita un análisis de tendencias, When el administrador filtra por período, Then debería obtener una representación gráfica de la ocupación.</td> 
</tr>

<tr> 
  <td>TS14</td> 
  <td>Developer</td> 
  <td>Configuración de Opciones de Notificaciones</td> 
  <td>EP09</td> 
</tr> 
<tr> 
  <td>Title</td> 
  <td colspan="3">Configuración de Opciones de Notificaciones</td> 
</tr> 
<tr> 
  <td colspan="4">Description</td> 
</tr> 
<tr> 
  <td colspan="4">Como developer, quiero implementar un endpoint para que los usuarios configuren sus preferencias de notificaciones para personalizar los avisos que desean recibir.</td> 
</tr> 
<tr> 
  <td colspan="4">Acceptance Criteria</td> 
</tr> 
<tr> 
  <td colspan="4">Escenario 01: Given que un usuario ajusta sus preferencias de notificaciones, When accede al endpoint `/api/notification-preferences`, Then debería poder activar o desactivar tipos de notificación específicos. <br> Escenario 02: Given que el sistema envía notificaciones, When las preferencias están activadas, Then el usuario debería recibir solo las notificaciones configuradas en su perfil.</td> 
</tr>

<tr> 
  <td>TS15</td> 
  <td>Developer</td> 
  <td>API de Feedback Automático</td> 
  <td>EP11</td> 
</tr> 
<tr> 
  <td>Title</td> 
  <td colspan="3">API de Feedback Automático</td> 
</tr> 
<tr> 
  <td colspan="4">Description</td> 
</tr> 
<tr> 
  <td colspan="4">Como developer, quiero implementar un endpoint para recopilar feedback de los usuarios al finalizar su reserva para obtener insights sobre su experiencia de usuario.</td> 
</tr> 
<tr> 
  <td colspan="4">Acceptance Criteria</td> 
</tr> 
<tr> 
  <td colspan="4">Escenario 01: Given que un usuario completa una reserva, When el sistema solicita feedback en el endpoint `/api/automatic-feedback`, Then debería almacenar los comentarios para análisis posterior. <br> Escenario 02: Given que el administrador consulta el feedback, When revisa los comentarios en el endpoint, Then debería ver un resumen con estadísticas de satisfacción.</td> 
</tr>

<tr> 
  <td>TS16</td> 
  <td>Developer</td> 
  <td>Gestión de Reembolsos</td> 
  <td>EP13</td> 
</tr> 
<tr> 
  <td>Title</td> 
  <td colspan="3">Gestión de Reembolsos</td> 
</tr> 
<tr> 
  <td colspan="4">Description</td> 
</tr> 
<tr> 
  <td colspan="4">Como developer, quiero implementar un endpoint para gestionar solicitudes de reembolso para asegurar que los usuarios puedan solicitar reembolsos fácilmente en caso de problemas.</td> 
</tr> 
<tr> 
  <td colspan="4">Acceptance Criteria</td> 
</tr> 
<tr> 
  <td colspan="4">Escenario 01: Given que un usuario solicita un reembolso, When el sistema procesa la solicitud en el endpoint `/api/refunds`, Then debería generar una respuesta de éxito o error según el caso. <br> Escenario 02: Given que se requiere seguimiento de reembolsos, When el administrador consulta el historial de reembolsos, Then debería ver un listado con detalles de cada solicitud.</td> 
</tr>

<tr> 
  <td>TS17</td> 
  <td>Developer</td> 
  <td>Auditoría de Cambios de Tarifas</td> 
  <td>EP12</td> 
</tr> 
<tr> 
  <td>Title</td> 
  <td colspan="3">Auditoría de Cambios de Tarifas</td> 
</tr> 
<tr> 
  <td colspan="4">Description</td> 
</tr> 
<tr> 
  <td colspan="4">Como developer, quiero un endpoint para auditar todas las modificaciones de tarifas en la plataforma para asegurar un control y seguimiento sobre los cambios de precios.</td> 
</tr> 
<tr> 
  <td colspan="4">Acceptance Criteria</td> 
</tr> 
<tr> 
  <td colspan="4">Escenario 01: Given que un administrador modifica una tarifa, When se registra el cambio en el endpoint `/api/rate-audit`, Then debería almacenar la fecha, hora y detalles de la tarifa modificada. <br> Escenario 02: Given que un auditor revisa el historial de cambios de tarifas, When solicita un reporte, Then debería obtener un listado con todas las modificaciones realizadas.</td> 
</tr>

<tr>
  <td>SP01</td>
  <td>Developer</td>
  <td>Alta</td>
  <td>EP15</td>
</tr>
<tr>
  <td>Title</td>
  <td colspan="3">Investigación sobre integración de OAuth2</td>
</tr>
<tr>
  <td colspan="4">Description</td>
</tr>
<tr>
  <td colspan="4">
    Como developer, quiero investigar bibliotecas de autenticación OAuth2 disponibles, con el fin de garantizar una integración segura y compatible con la arquitectura del sistema.
  </td>
</tr>
<tr>
  <td colspan="4">Acceptance Criteria</td>
</tr>
<tr>
  <td colspan="4">
    Escenario 01: <br>
    Given que el developer debe evaluar opciones de autenticación, When se evaluán criterios de compatilidad, seguridad y facilidad de integración y se realizan al menos dos pruebas de librerías OAuth2, Then se debe documentar su compatibilidad y facilidad de integración.<br> Escenario 02: <br>
    Given que se implementa un prototipo mínimo, When se realiza un inicio de sesión de prueba,<br>
    Then el sistema debe autenticar correctamente y emitir un token válido.
  </td>
</tr>

<tr>
  <td>SP02</td>
  <td>Developer</td>
  <td>Alta</td>
  <td>EP19</td>
</tr>
<tr>
  <td>Title</td>
  <td colspan="3">Evaluación de pasarelas de pago</td>
</tr>
<tr>
  <td colspan="4">Description</td>
</tr>
<tr>
  <td colspan="4">
    Como developer, quiero investigar distintas pasarelas de pago (PayPal, MercadoPago, Yape), para identificar la opción más adecuada para la plataforma.
  </td>
</tr>
<tr>
  <td colspan="4">Acceptance Criteria</td>
</tr>
<tr>
  <td colspan="4">
    Escenario 01: <br> Given que se seleccionan al menos dos pasarelas de pago, When se simula un pago exitoso en cada una, Then la transacción debe completarse correctamente y quedar registrada. <br> Escenario 02: <br> Given que se comparan las APIs de las pasarelas, When se revisa documentación y costos, Then se debe entregar un informe con ventajas y desventajas de cada una.<br>
  </td>
</tr>

<tr>
  <td>SP03</td>
  <td>Developer</td>
  <td>Alta</td>
  <td>EP12</td>
</tr>
<tr>
  <td>Title</td>
  <td colspan="3">Investigación de mapas en tiempo real</td>
</tr>
<tr>
  <td colspan="4">Description</td>
</tr>
<tr>
  <td colspan="4">
    Como developer, quiero evaluar servicios de mapas en tiempo real (Google Maps, Mapbox, OpenStreetMap), para determinar cuál permite mostrar ubicaciones y trayectorias de reservas activas con mejor rendimiento.
  </td>
</tr>
<tr>
  <td colspan="4">Acceptance Criteria</td>
</tr>
<tr>
  <td colspan="4">
    Escenario 01: <br> Given que se integra una librería de mapas,<br> When se visualiza la ubicación de un dispositivo en tiempo real,<br>Then el mapa debe actualizarse sin retraso significativo.<br> Escenario 02: <br> Given que se prueban las opciones seleccionadas en un dispositivo, When se mide consumo de datos y rendimiento, Then se debe documentar cuál ofrece mejor balance entre costo y eficiencia.<br>
  </td>
</tr>

<tr>
  <td>SP04</td>
  <td>Developer</td>
  <td>Media</td>
  <td>EP11</td>
</tr>
<tr>
  <td>Title</td>
  <td colspan="3">Evaluación de notificaciones push y alertas</td>
</tr>
<tr>
  <td colspan="4">Description</td>
</tr>
<tr>
  <td colspan="4">
    Como developer, quiero investigar servicios de notificaciones push (Firebase, OneSignal, WebPush), con el fin de identificar la solución más confiable y con menor latencia para propietarios de estacionamiento y conductores.
  </td>
</tr>
<tr>
  <td colspan="4">Acceptance Criteria</td>
</tr>
<tr>
  <td colspan="4">
    Escenario 01: <br> Given que el sistema envía una notificación de prueba, When un usuario con dispositivo Android la recibe, Then la notificación debe mostrarse de forma inmediata. <br> Escenario 02: <br> Given que se configuran distintos proveedores de push notifications, When se ejecutan pruebas de latencia, Then se debe documentar cuál presenta mejor tiempo de entrega y personalización.<br>
  </td>
</tr>

<tr>
  <td>SP05</td>
  <td>Developer</td>
  <td>Alta</td>
  <td>EP18</td>
</tr>
<tr>
  <td>Title</td>
  <td colspan="3">Investigación de escalabilidad para múltiples reservas simultáneas</td>
</tr>
<tr>
  <td colspan="4">Description</td>
</tr>
<tr>
  <td colspan="4">
    Como developer, quiero analizar cómo manejar múltiples reservas simultáneas, con el fin de evitar conflictos en la asignación de reservas y garantizar la integridad de los datos.
  </td>
</tr>
<tr>
  <td colspan="4">Acceptance Criteria</td>
</tr>
<tr>
  <td colspan="4">
    Escenario 01: <br> Given que se simulan múltiples conductores solicitando reservas, When dos solicitudes intentan reservar el mismo espacio, Then solo una debe confirmarse y la otra ser rechazada. <br> Escenario 02: <br> Given que se utiliza una estrategia de concurrencia, When se ejecuta una prueba de carga, Then los resultados deben demostrar que los datos de las reservas se mantienen consistentes.<br>
  </td>
</tr>

<tr>
  <td>SP06</td>
  <td>Developer</td>
  <td>Alta</td>
  <td>EP15</td>
</tr>
<tr>
  <td>Title</td>
  <td colspan="3">Evaluación de seguridad y cifrado de datos sensibles</td>
</tr>
<tr>
  <td colspan="4">Description</td>
</tr>
<tr>
  <td colspan="4">
    Como developer, quiero implementar el cifrado de datos, para cumplir con los estándares de seguridad y proteger la información de usuarios y pagos.
  </td>
</tr>
<tr>
  <td colspan="4">Acceptance Criteria</td>
</tr>
<tr>
  <td colspan="4">
    Escenario 01: <br> Given que se configura cifrado en base de datos, When se guarda información sensible, Then los registros no deben almacenarse en texto plano. <br> Escenario 02: <br> Given que se activa protocolos TLS para las comunicaciones, When un cliente se conecta al servidor, Then la transferencia de datos debe estar encriptada de extremo a extremo.<br>
  </td>
</tr>

<tr>
  <td>SP07</td>
  <td>Developer</td>
  <td>Alta</td>
  <td>EP18</td>
</tr>
<tr>
  <td>Title</td>
  <td colspan="3">Pruebas de rendimiento de la aplicación</td>
</tr>
<tr>
  <td colspan="4">Description</td>
</tr>
<tr>
  <td colspan="4">
    Como developer, quiero realizar pruebas de rendimiento en la aplicación, para garantizar que el sistema soporte un alto volumen de usuarios concurrentes.
  </td>
</tr>
<tr>
  <td colspan="4">Acceptance Criteria</td>
</tr>
<tr>
  <td colspan="4">
    Escenario 01: <br> Given que se configuran pruebas de carga con al menos 500 usuarios simultáneos, When se ejecuta la simulación, Then el sistema debe responder sin errores críticos y manteniendo un tiempo de respuesta aceptable. <br> Escenario 02: <br> Given que se ejecutan pruebas bajo condiciones de red inestables, When el sistema procesa solicitudes de usuarios con pérdida de paquetes, Then debe seguir funcionando sin afectar la integridad de los datos.
  </td>
</tr>
</table>

## 3.3. Product Backlog.

| # Orden | User Story ID | Título | Descripción | Story Points |
| ------ | ------------- | ------ | ----------- | ------------------------ |
| 1 | US01 | Navegación Intuitiva en la Landing Page | Como visitante, quiero navegar la landing page para encontrar secciones importantes fácilmente. | 5 |
| 2 | US02 | Visualización de Ciudades con Servicio | Como visitante, quiero ver en qué ciudades está disponible Quadrapp para saber si puedo usar el servicio. | 3 |
| 3 | US03 | Promociones Destacadas | Como visitante, quiero ver promociones destacadas para aprovechar descuentos y beneficios. | 5 |
| 4 | US04 | Beneficios para Conductores y Dueños de Estacionamiento | Como visitante, quiero ver los beneficios de usar Quadrapp para entender sus ventajas. | 3 |
| 5 | US05 | Visualización de Misión de la Empresa | Como visitante, quiero ver la misión de Quadrapp para conocer sus objetivos. | 2 |
| 6 | US06 | Visualización de Visión de la Empresa | Como visitante, quiero conocer la visión de Quadrapp para entender su crecimiento futuro. | 2 |
| 7 | US07 | Visualización del Equipo | Como visitante, quiero ver quiénes forman el equipo para conocer al personal detrás del proyecto. | 3 |
| 8 | US08 | Información de Contacto | Como visitante, quiero ver información de contacto para comunicarme con Quadrapp fácilmente. | 3 |
| 9 | US09 | Envío de Mensaje de Contacto | Como visitante, quiero enviar un mensaje a Quadrapp para hacer preguntas o dar feedback. | 5 |
| 10 | US10 | Visualización de Información de Características | Como visitante, quiero ver las características del servicio para entender lo que ofrece Quadrapp. | 3 |
| 11 | US11 | Botón de Registro e Inicio de Sesión | Como visitante, quiero registrarme o iniciar sesión para acceder a la plataforma. | 5 |
| 12 | US12 | Enlace a Redes Sociales | Como visitante, quiero seguir a Quadrapp en redes sociales para recibir novedades y actualizaciones. | 2 |
| 13 | US13 | Visualización de Slogan | Como visitante, quiero ver un slogan atractivo para comprender la propuesta del servicio rápidamente. | 2 |
| 14 | US14 | Acceso a Información Legal | Como visitante, quiero revisar términos y políticas de privacidad para entender las reglas de uso y protección de datos. | 3 |
| 15 | US15 | Inicio de Sesión para Conductores | Como conductor, quiero iniciar sesión con mi cuenta para acceder a la aplicación. | 5 |
| 16 | US16 | Registro de Conductores | Como conductor, quiero registrar mi cuenta para poder usar la plataforma. | 5 |
| 17 | US17 | Registro de Propietarios de Estacionamiento | Como propietario, quiero registrar mi cuenta para acceder a las funcionalidades de Quadrapp. | 5 |
| 18 | US18 | Búsqueda de Reservas para Conductores | Como conductor, quiero buscar mis reservas para visualizarlas y gestionarlas fácilmente. | 3 |
| 19 | US19 | Pago de Reservas por Transacción | Como conductor, quiero pagar mis reservas por transacción para completar mis reservas. | 5 |
| 20 | US20 | Confirmación de Reserva Registrada | Como conductor, quiero recibir confirmación de mi reserva para asegurarme que fue registrada correctamente. | 3 |
| 21 | US21 | Registro de Opiniones | Como usuario, quiero registrar mis opiniones para dar retroalimentación sobre mi experiencia en la plataforma. | 3 |
| 22 | US22 | Notificaciones en el Dashboard del Conductor | Como conductor, quiero recibir notificaciones en mi dashboard para estar al tanto de ofertas y recordatorios. | 5 |
| 23 | US23 | Configuración de Preferencias de Usuario | Como usuario, quiero configurar mis preferencias para personalizar mi experiencia en la plataforma. | 3 |
| 24 | US24 | Historial de Reservas en el Dashboard del Conductor | Como conductor, quiero ver mi historial de reservas para consultar mis reservas pasadas. | 3 |
| 25 | US25 | Alerta de Espacio Disponible | Como conductor, quiero recibir alertas de disponibilidad de espacios para saber cuándo un espacio está libre. | 5 |
| 26 | US26 | Soporte en Tiempo Real en el Dashboard del Conductor | Como conductor, quiero un soporte en tiempo real para resolver dudas o problemas rápidamente. | 5 |
| 27 | US27 | Favoritos para Conductores | Como conductor, quiero marcar estacionamientos como favoritos para facilitar futuras reservas. | 3 |
| 28 | US28 | Verificación de Reserva en el Dashboard del Conductor | Como conductor, quiero verificar el estado de mi reserva para confirmar si el espacio está listo. | 3 |
| 29 | US29 | Cancelación de Reserva en el Dashboard | Como conductor, quiero cancelar mi reserva para evitar inconvenientes si cambian mis planes. | 5 |
| 30 | US30 | Gestión de Alertas para Conductores | Como conductor, quiero ver todas mis alertas en el dashboard para gestionarlas fácilmente. | 5 |
| 31 | US31 | Personalización de Notificaciones para Conductores | Como conductor, quiero personalizar mis notificaciones para recibir solo alertas relevantes. | 3 |
| 32 | US32 | Visualización de Mapa en el Dashboard del Conductor | Como conductor, quiero acceder a un mapa interactivo para ver ubicaciones de estacionamientos cercanos. | 5 |
| 33 | US33 | Seguimiento de Reserva en Tiempo Real | Como conductor, quiero hacer seguimiento de mi reserva en tiempo real para conocer su estado. | 5 |
| 34 | TS01 | Gestión de Clientes en Servicio al Cliente | Como developer, quiero crear un endpoint para gestionar consultas de servicio al cliente para permitir soporte eficaz. | 3 |
| 35 | TS02 | Notificación de Cambios en la Disponibilidad de Espacios | Como developer, quiero un endpoint que envíe notificaciones automáticas de cambios de estado de espacios para mantener a los usuarios informados. | 5 |
| 36 | TS03 | Historial de Transacciones para Usuarios | Como developer, quiero un endpoint para consultar el historial de transacciones para permitir la revisión de pagos y reservas. | 3 |
| 37 | TS04 | Gestión de Ocupación de Espacios en Tiempo Real | Como developer, quiero un endpoint que actualice la disponibilidad de espacios en tiempo real para reflejar cambios según sensores y cámaras. | 5 |
| 38 | TS05 | Configuración de Alertas de Seguridad | Como developer, quiero un endpoint para configurar alertas de seguridad para responder rápidamente a eventos sospechosos. | 5 |
| 39 | TS06 | Administración de Tarifas por Ubicación | Como developer, quiero un endpoint para configurar tarifas según ubicación para ajustar precios según demanda. | 5 |
| 40 | TS07 | Registro de Alertas de Seguridad | Como developer, quiero un endpoint que registre todas las alertas de seguridad para que los administradores revisen incidentes pasados. | 3 |
| 41 | TS08 | Gestión de Datos de Vehículos | Como developer, quiero un endpoint para almacenar y gestionar información de vehículos para hacer seguimiento y gestionar accesos. | 3 |
| 42 | TS09 | Reportes de Promociones Utilizadas | Como developer, quiero un endpoint que genere reportes de promociones usadas para analizar efectividad y optimizar campañas. | 3 |
| 43 | TS10 | Auditoría de Acciones en la Plataforma | Como developer, quiero un endpoint que registre todas las acciones críticas para garantizar seguridad y trazabilidad. | 5 |
| 44 | TS11 | Historial de Opiniones de Usuarios | Como developer, quiero un endpoint para registrar y consultar opiniones de usuarios para mejorar la experiencia con feedback. | 3 |
| 45 | TS12 | Integración con el Sistema de Pago | Como developer, quiero un endpoint para procesar pagos y verificar transacciones para garantizar pagos seguros. | 5 |
| 46 | TS13 | Generación de Reportes de Ocupación | Como developer, quiero un endpoint que genere reportes de ocupación para analizar el uso y optimizar la disponibilidad de espacios. | 3 |
| 47 | TS14 | Configuración de Opciones de Notificaciones | Como developer, quiero un endpoint para que los usuarios configuren sus preferencias de notificaciones para personalizar avisos. | 3 |
| 48 | TS15 | API de Feedback Automático | Como developer, quiero un endpoint para recopilar feedback de usuarios al finalizar reservas para obtener insights de experiencia. | 3 |
| 49 | TS16 | Gestión de Reembolsos | Como developer, quiero un endpoint para gestionar solicitudes de reembolso para asegurar que los usuarios puedan solicitarlos fácilmente. | 3 |
| 50 | TS17 | Auditoría de Cambios de Tarifas | Como developer, quiero un endpoint que audite todas las modificaciones de tarifas para asegurar control y seguimiento de precios. | 8 |
| 51 | SP01 | Investigación sobre integración de OAuth2 | Como developer, quiero investigar bibliotecas de autenticación OAuth2 para garantizar una integración segura y compatible con el sistema. | 5 |
| 52 | SP02 | Evaluación de pasarelas de pago | Como developer, quiero investigar distintas pasarelas de pago para identificar la opción más adecuada para la plataforma. | 5 |
| 53 | SP03 | Investigación de mapas en tiempo real | Como developer, quiero evaluar servicios de mapas en tiempo real para determinar cuál ofrece mejor rendimiento y visualización de reservas. | 8 |
| 54 | SP04 | Evaluación de notificaciones push y alertas | Como developer, quiero investigar servicios de notificaciones push para identificar la solución más confiable y con menor latencia. | 5 |
| 55 | SP05 | Investigación de escalabilidad para múltiples reservas simultáneas | Como developer, quiero analizar cómo manejar múltiples reservas simultáneas para evitar conflictos y garantizar integridad de datos. | 5 |
| 56 | SP06 | Evaluación de seguridad y cifrado de datos sensibles | Como developer, quiero implementar cifrado de datos para cumplir con estándares de seguridad y proteger información de usuarios y pagos. | 8 |
| 57 | SP07 | Pruebas de rendimiento de la aplicación | Como developer, quiero realizar pruebas de rendimiento en la aplicación para garantizar que soporte un alto volumen de usuarios concurrentes. | 8 |

Enlace: https://trello.com/invite/b/68cb76046c3ed8b6f0fc18c2/ATTI91035f3a2c18dc5abbb742838e8d0be8E6AB6959/quadrapp-product-backlog-tb1-sprint-1

## 3.4. Impact Mapping.

En esta sección, presentamos el Impact Mapping para el proyecto de Quadrapp, cuyo objetivo es desarrollar e implementar un mapa interactivo que facilite la localización. Este mapa es esencial para optimizar la experiencia de nuestros usuarios y alcanzar los objetivos comerciales.

El Impact Mapping ofrece una visión clara de cómo los objetivos de negocio, las necesidades de los usuarios y las funcionalidades propuestas se interconectan. Asegura que cada elemento del desarrollo esté alineado con nuestras metas, contribuyendo al éxito de Quadrapp y mejorando tanto la experiencia de los universitarios como la de los adquirientes.
<br>

- **Segmento Conductores Urbanos:**

El Impact Map de Quadrapp se centra en incrementar el número de conductores urbanos frecuentes que utilizan la plataforma, mejorando la seguridad y accesibilidad en los estacionamientos de zonas urbanas. El objetivo es aumentar el uso del servicio en un 30%, implementando soluciones como rutas de navegación más eficientes, cámaras de monitoreo en tiempo real y notificaciones automáticas sobre disponibilidad de espacios. Las historias de usuario están orientadas a optimizar rutas, garantizar la seguridad y gestionar alertas, brindando así una experiencia más fluida y confiable para los conductores.

![ImpactMapping-Segmento1](assets/Impact%20Mapping%20-%20%20Segmento1.png)

----

- **Segmento Propietarios de Estacionamiento:**

El Impact Map para propietarios de estacionamientos está diseñado para optimizar la gestión de sus espacios y aumentar la satisfacción de los clientes en un 30% durante los próximos seis meses. Las soluciones incluyen reservas en tiempo real, herramientas visuales de monitoreo mediante cámaras y funcionalidades para recopilar opiniones de los usuarios. Estas funciones permiten a los propietarios maximizar la ocupación de sus espacios, reducir los tiempos de espera y mejorar la calidad del servicio a partir del feedback directo de los clientes.

![ImpactMapping-Segmento2](assets/Impact%20Mapping%20-%20Segmento2.png)
