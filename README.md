<div align="center">
    <h3>Universidad Peruana de Ciencias Aplicadas</h3>
    <img src="https://upload.wikimedia.org/wikipedia/commons/f/fc/UPC_logo_transparente.png"></img><br>
    <strong>Ingeniería de Software - 7mo Ciclo</strong><br>
    <strong>Fundamentos de Arquitectura de Software</strong><br>
    <strong>1ASI0657 - 3588</strong><br>
    <strong>Profesor: Ernesto Ocampo Tello</strong><br>
    <br><strong>Report</strong><br>
    <br><strong>ExploraYa</strong><br>
    <!--<strong>name startup</strong>-->
</div>

<h3> Team Members: </h3>

<div align="center">

| Member                              |    Code    |
| :---------------------------------- | :--------: |
| Paolo Gonzalo Párraga Gamarra       | u202219186 |
| Cama Salvatierra, Jimena Tamara     | u202210778 |
| Castillo Castillo, Jair Alexander   | u202211390 |
| Quezada Portalatino, Barbara Susana | u202211800 |

</div>

<h3 align="center">Abril, 2025</h3>

<br><br>

<div align="justify">

## Registro de Versiones del Informe

El objetivo de esta sección es resumir las modificaciones relevantes que se realizan al informe durante el ciclo de vida del proyecto. Esta sección inicia en una página nueva e incluye un cuadro con la siguiente estructura:

<table>
  <thead>
    <tr>
      <th>Versión</th>
      <th>Fecha</th>
      <th>Autor</th>
      <th>Descripción de modificación</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>0.1</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
    </tr>
    
  </tbody>
</table>


# Capítulo III: Requirements Specification

## 3.1. To-Be Scenario Mapping

[Contenido Pendiente]

## 3.2. User Stories

### Épicas de AventuraPe

| Epic ID | Detalle                                               |
| :------ | :---------------------------------------------------- |
| EP01    | Navegación y Acceso a la Plataforma Web               |
| EP02    | Interacción del Usuario Aventurero en la Plataforma Web |
| EP03    | Interacción del Empresario en la Plataforma Web       |
| EP04    | Gestión de Perfil de Usuario                          |
| EP05    | Sistema de Recomendación de Actividades               |
| EP06    | Analítica Avanzada para Empresarios                   |

### Navegación y Acceso (EP01)

| Story ID | Título                              | Descripción                                                                                                                  | Epic ID | Usuario   | Criterios de aceptación                                                                                                                                                              |
| :------- | :---------------------------------- | :--------------------------------------------------------------------------------------------------------------------------- | :------ | :-------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| US01     | Interacción con hipervínculos (Web) | El visitante necesita poder hacer clic en los enlaces de navegación para ir a las diferentes secciones de la plataforma web.      | EP01    | Visitante | **Escenario 1: Navegación exitosa**<br>**Dado que** el usuario se encuentra en una página de la plataforma web.<br>**Cuando** el usuario hace clic en un enlace del menú de navegación principal.<br>**Entonces** el sistema carga y muestra la página o sección correspondiente al enlace seleccionado. |
| US02     | Sección características (Web)         | El visitante necesita poder ver una sección de características para entender qué ofrece AventuraPe.                             | EP01    | Visitante | **Escenario 1: Visualización de características**<br>**Dado que** el visitante está en la página principal.<br>**Cuando** el visitante navega hasta la sección de características.<br>**Entonces** el sistema muestra un resumen claro y conciso de las funcionalidades clave de AventuraPe. |
| US03     | Sección preguntas frecuentes (Web)    | El visitante necesita poder consultar una sección de preguntas frecuentes para resolver sus dudas sobre la plataforma.        | EP01    | Visitante | **Escenario 1: Consulta de FAQ**<br>**Dado que** el visitante está en la plataforma.<br>**Cuando** el visitante accede a la sección de "Preguntas Frecuentes".<br>**Entonces** el sistema muestra una lista de preguntas comunes y permite al visitante expandir cada una para ver su respuesta. |

### Usuario Aventurero (EP02 / EP05)

| Story ID | Título                                      | Descripción                                                                                                                                                                      | Epic ID | Usuario    | Criterios de aceptación                                                                                                                                                                                                                                                                                                                                                                                                                                                             |
| :------- | :------------------------------------------ | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :------ | :--------- | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| US04     | Iniciar sesión (Aventurero - Web)             | El usuario aventurero registrado necesita poder iniciar sesión con sus credenciales para acceder a su cuenta y funcionalidades personalizadas.                                     | EP02    | Aventurero | **Escenario 1: Inicio de sesión exitoso**<br>**Dado que** el aventurero registrado se encuentra en la página de inicio de sesión.<br>**Cuando** el aventurero ingresa su email y contraseña correctos y hace clic en el botón 'Iniciar Sesión'.<br>**Entonces** el sistema valida las credenciales y redirige al aventurero a su home personalizado.<br><br>**Escenario 2: Inicio de sesión fallido**<br>**Dado que** el aventurero registrado se encuentra en la página de inicio de sesión.<br>**Cuando** el aventurero ingresa un email o contraseña incorrectos y hace clic en el botón 'Iniciar Sesión'.<br>**Entonces** el sistema muestra un mensaje de error indicando "Credenciales inválidas" y permanece en la página de inicio de sesión. |
| US06     | Creación de perfil (Aventurero - Web)         | El nuevo usuario aventurero necesita poder crear una cuenta/perfil para usar las funciones personalizadas de la plataforma.                                                      | EP02    | Aventurero | **Escenario 1: Registro exitoso**<br>**Dado que** el visitante se encuentra en la página de registro para aventureros.<br>**Cuando** el visitante completa los campos obligatorios, acepta los términos y condiciones, y hace clic en el botón 'Registrar'.<br>**Entonces** el sistema crea la nueva cuenta de aventurero, inicia sesión automáticamente y redirige al usuario al home de aventurero.                                                                                   |
| US11     | Visualización de mapa (Aventurero - Web)      | El aventurero necesita poder ver un mapa interactivo con la ubicación de las actividades para explorar opciones cercanas geográficamente.                                         | EP02    | Aventurero | **Escenario 1: Visualización de mapa y marcadores**<br>**Dado que** el aventurero ha accedido a la sección del mapa dentro de la plataforma.<br>**Cuando** el mapa termina de cargar.<br>**Entonces** el sistema muestra un mapa centrado en la ubicación del usuario con marcadores indicando la posición de las actividades disponibles en el área visible.                                                                                                                          |
| US12     | Ver detalles de actividad (Aventurero - Web)  | El aventurero necesita poder seleccionar una publicación de la lista o el mapa para ver todos sus detalles antes de decidirse.                                                   | EP02    | Aventurero | **Escenario 1: Acceso a detalles**<br>**Dado que** el aventurero está viendo una lista de actividades o el mapa.<br>**Cuando** el aventurero hace clic en el título, imagen o marcador de una actividad específica.<br>**Entonces** el sistema carga y muestra una página dedicada con toda la información detallada de esa actividad.                                                                                                                                                |
| US13     | Búsqueda por filtro (Aventurero - Web)        | El aventurero necesita poder filtrar la lista de actividades por criterios específicos para encontrar rápidamente lo que busca.                                                  | EP02    | Aventurero | **Escenario 1: Aplicación de filtro**<br>**Dado que** el aventurero está viendo la lista completa o una categoría de actividades.<br>**Cuando** el aventurero selecciona y aplica un filtro disponible.<br>**Entonces** el sistema actualiza la lista de actividades mostrando únicamente aquellas que cumplen con los criterios del filtro aplicado.                                                                                                                                   |
| US14     | Calificación de publicación (Aventurero)        | El aventurero necesita poder asignar una calificación a una actividad en la que participó para compartir su valoración general rápidamente.                                          | EP02    | Aventurero | **Escenario 1: Registrar calificación**<br>**Dado que** el aventurero está viendo la página de detalles de una actividad en la que participó.<br>**Cuando** el aventurero selecciona un número de estrellas en el control de calificación y hace clic en 'Guardar Calificación'.<br>**Entonces** el sistema registra la calificación del usuario para esa actividad y actualiza la calificación promedio mostrada.                                                                       |
| US15     | Publicar reseña/comentario (Aventurero - Web) | El aventurero necesita poder escribir y publicar una reseña/comentario sobre una actividad en la que participó para compartir su experiencia detallada.                             | EP02    | Aventurero | **Escenario 1: Publicar comentario exitoso**<br>**Dado que** el aventurero está en la página de detalles de una actividad en la que participó.<br>**Cuando** el aventurero escribe un texto en el campo de reseña/comentario y hace clic en el botón 'Publicar'.<br>**Entonces** el sistema valida el comentario, lo guarda asociado a la actividad y lo muestra en la lista de comentarios/reseñas visibles para otros usuarios.                                                             |
| US17     | Guardar favoritos (Aventurero - Web)          | El aventurero necesita poder marcar una actividad como favorita para guardarla en una lista personal y encontrarla fácilmente más tarde.                                          | EP02    | Aventurero | **Escenario 1: Añadir a favoritos**<br>**Dado que** el aventurero está viendo la página de detalles o una tarjeta resumen de una actividad.<br>**Cuando** el aventurero hace clic en el icono o botón 'Marcar como Favorito'.<br>**Entonces** el sistema añade esa actividad a la lista personal de favoritos del aventurero y el icono/botón cambia para indicar que ya es favorita.                                                                                                   |
| US21     | Navegar interfaz home (Aventurero - Web)      | El aventurero necesita poder ver una pantalla principal (home) con una lista o resumen de actividades para tener una vista general al ingresar a la plataforma.               | EP02    | Aventurero | **Escenario 1: Vista del Home**<br>**Dado que** el aventurero ha iniciado sesión.<br>**Cuando** accede a la página principal (home) de la plataforma.<br>**Entonces** se le presenta una pantalla que muestra una lista o cuadrícula de actividades.                                                                                                                                                                                                 |

### Usuario Empresario (EP03 / EP06)

| Story ID | Título                                      | Descripción                                                                                                                                                                 | Epic ID | Usuario    | Criterios de aceptación                                                                                                                                                                                                                                                                                                                                                                                                                       |
| :------- | :------------------------------------------ | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :------ | :--------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| US05     | Iniciar sesión (Empresario - Web)             | El usuario empresario registrado necesita poder iniciar sesión con sus credenciales para acceder al panel de gestión de su negocio.                                            | EP03    | Empresario | **Escenario 1: Inicio de sesión exitoso**<br>**Dado que** el empresario registrado se encuentra en la página de inicio de sesión.<br>**Cuando** el empresario ingresa su email y contraseña correctos y hace clic en el botón 'Iniciar Sesión'.<br>**Entonces** el sistema valida las credenciales y redirige al empresario a su panel de gestión.<br><br>**Escenario 2: Inicio de sesión fallido**<br>**Dado que** el empresario registrado se encuentra en la página de inicio de sesión.<br>**Cuando** el empresario ingresa un email o contraseña incorrectos y hace clic en el botón 'Iniciar Sesión'.<br>**Entonces** el sistema muestra un mensaje de error indicando "Credenciales inválidas" y permanece en la página de inicio de sesión. |
| US07     | Creación de perfil (Empresario - Web)         | El nuevo usuario empresario necesita poder crear una cuenta/perfil de negocio para publicar actividades y gestionar su presencia en la plataforma.                           | EP03    | Empresario | **Escenario 1: Registro exitoso**<br>**Dado que** el visitante se encuentra en la página de registro para empresarios.<br>**Cuando** el visitante completa los campos obligatorios, acepta los términos y condiciones, y hace clic en el botón 'Registrar'.<br>**Entonces** el sistema crea la nueva cuenta de empresario, inicia sesión automáticamente y redirige al usuario al panel de gestión.                                                  |
| US08     | Publicar actividad (Empresario - Web)         | El empresario necesita poder publicar los detalles de una nueva actividad o experiencia que ofrece para atraer clientes aventureros.                                         | EP03    | Empresario | **Escenario 1: Publicación exitosa**<br>**Dado que** el empresario ha iniciado sesión y se encuentra en su panel de gestión.<br>**Cuando** el empresario navega a la opción 'Publicar Nueva Actividad', completa todos los campos requeridos del formulario y hace clic en 'Publicar'.<br>**Entonces** el sistema valida los datos, guarda la nueva actividad y esta se vuelve visible en la plataforma para los aventureros.                    |
| US09     | Edición de actividad (Empresario - Web)       | El empresario necesita poder editar los detalles de una actividad ya publicada para corregir información o actualizarla.                                                      | EP03    | Empresario | **Escenario 1: Edición exitosa**<br>**Dado que** el empresario ha iniciado sesión y está viendo la lista de sus actividades publicadas.<br>**Cuando** el empresario selecciona una actividad, hace clic en 'Editar', modifica uno o más campos y hace clic en 'Guardar Cambios'.<br>**Entonces** el sistema valida y guarda los cambios, y la información actualizada de la actividad se refleja en la plataforma.                                  |
| US10     | Borrar actividad (Empresario - Web)           | El empresario necesita poder borrar una actividad publicada que ya no está disponible o fue un error para mantener su oferta actualizada.                                     | EP03    | Empresario | **Escenario 1: Borrado exitoso**<br>**Dado que** el empresario ha iniciado sesión y está viendo la lista de sus actividades publicadas.<br>**Cuando** el empresario selecciona una actividad, hace clic en 'Borrar', y confirma la acción en el diálogo de confirmación.<br>**Entonces** el sistema elimina la actividad de la plataforma y de la lista de actividades activas del empresario.                                              |
| US16     | Ver comentarios de mis publicaciones (Empresario)| El empresario necesita poder acceder a una sección donde vea todos los comentarios/reseñas dejados en sus publicaciones para monitorear el feedback.                         | EP03    | Empresario | **Escenario 1: Visualización de comentarios**<br>**Dado que** el empresario ha iniciado sesión y está en su panel de gestión.<br>**Cuando** el empresario selecciona una de sus publicaciones y navega a la sección 'Comentarios'.<br>**Entonces** el sistema muestra una lista de todos los comentarios/reseñas asociados a esa publicación, incluyendo el texto, la calificación y el nombre del aventurero que lo dejó.                   |
| US19     | Visualización de estadísticas (Empresario)    | El empresario necesita poder ver estadísticas sobre sus publicaciones para entender su rendimiento y popularidad.                                                           | EP06    | Empresario | **Escenario 1: Consulta de estadísticas generales**<br>**Dado que** el empresario ha iniciado sesión y está en su panel de gestión.<br>**Cuando** el empresario navega a la sección de 'Estadísticas'.<br>**Entonces** el sistema muestra un resumen o dashboard con métricas clave agregadas sobre el rendimiento de todas sus publicaciones.<br><br>**Escenario 2: Consulta de estadísticas por actividad**<br>**Dado que** el empresario está viendo la sección de 'Estadísticas'.<br>**Cuando** el empresario selecciona una actividad específica.<br>**Entonces** el sistema muestra métricas detalladas para esa actividad en particular. |
| US20     | Verificación de cuenta empresarial          | El empresario necesita poder solicitar y obtener una marca de verificación en su perfil para aumentar la confianza de los aventureros.                                         | EP03    | Empresario | **Escenario 1: Visualización de estado verificado**<br>**Dado que** un empresario ha completado exitosamente el proceso de verificación.<br>**Cuando** cualquier usuario visualiza el perfil de este empresario o una de sus publicaciones.<br>**Entonces** el sistema muestra una insignia o marca distintiva junto al nombre del negocio indicando que la cuenta está verificada.                                                              |

### Gestión de Perfil (EP04 - Ambos Usuarios)

| Story ID | Título                    | Descripción                                                                                                                                  | Epic ID | Usuario | Criterios de aceptación                                                                                                                                                                                                                                                                                               |
| :------- | :------------------------ | :------------------------------------------------------------------------------------------------------------------------------------------- | :------ | :------ | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| US07     | Edición de perfil (Web)   | El usuario registrado (Aventurero o Empresario) necesita poder editar la información de mi perfil para mantenerla actualizada.                  | EP04    | Ambos   | **Escenario 1: Edición exitosa**<br>**Dado que** el usuario registrado ha iniciado sesión y ha navegado a la página de 'Editar Perfil'.<br>**Cuando** el usuario modifica uno o más campos editables y hace clic en el botón 'Guardar Cambios'.<br>**Entonces** el sistema valida y guarda la información actualizada, y muestra un mensaje de confirmación. Los cambios son visibles al volver a ver el perfil. |
| US18     | Eliminación de perfil (Web)| El usuario registrado (Aventurero o Empresario) necesita poder eliminar su cuenta y perfil de la plataforma para dejar de usar el servicio. | EP04    | Ambos   | **Escenario 1: Eliminación exitosa**<br>**Dado que** el usuario registrado ha iniciado sesión y ha navegado a la sección de 'Configuración de Cuenta'.<br>**Cuando** el usuario hace clic en el botón 'Eliminar Cuenta' y confirma su intención mediante un diálogo de confirmación.<br>**Entonces** el sistema elimina permanentemente la cuenta del usuario y todos sus datos asociados, cierra la sesión del usuario y muestra un mensaje indicando que la cuenta ha sido eliminada. |

## 3.3. Impact mapping.

[Contenido Pendiente]

## 3.4. Product Backlog.

| #  | User Story ID | Título                                            | Descripción                                                                                                                                                         | Story Points |
|----|---------------|---------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------|----|
| 1  | US08          | Publicar actividad (Empresario - Web)             | El empresario necesita poder publicar los detalles de una nueva actividad   o experiencia que ofrece para atraer clientes aventureros.                              | 13 |
| 2  | US11          | Visualización de mapa (Aventurero - Web)          | El aventurero necesita poder ver un mapa interactivo con la ubicación de   las actividades para explorar opciones cercanas geográficamente.                         | 13 |
| 3  | US19          | Visualización de estadísticas (Empresario)        | El empresario necesita poder ver estadísticas sobre sus publicaciones   para entender su rendimiento y popularidad.                                                 | 13 |
| 4  | US12          | Ver detalles de actividad (Aventurero - Web)      | El aventurero necesita poder seleccionar una publicación de la lista o el   mapa para ver todos sus detalles antes de decidirse.                                    | 8  |
| 5  | US06          | Creación de perfil (Aventurero - Web)             | El nuevo usuario aventurero necesita poder crear una cuenta/perfil para   usar las funciones personalizadas de la plataforma.                                       | 8  |
| 6  | US07          | Creación de perfil (Empresario - Web)             | El nuevo usuario empresario necesita poder crear una cuenta/perfil de   negocio para publicar actividades y gestionar su presencia en la plataforma.                | 8  |
| 7  | US15          | Publicar reseña/comentario (Aventurero - Web)     | El aventurero necesita poder escribir y publicar una reseña/comentario   sobre una actividad en la que participó para compartir su experiencia   detallada.         | 8  |
| 8  | US13          | Búsqueda por filtro (Aventurero - Web)            | El aventurero necesita poder filtrar la lista de actividades por   criterios específicos para encontrar rápidamente lo que busca.                                   | 8  |
| 9  | US21          | Navegar interfaz home (Aventurero - Web)          | El aventurero necesita poder ver una pantalla principal (home) con una   lista o resumen de actividades para tener una vista general al ingresar a la   plataforma. | 8  |
| 10 | US20          | Verificación de cuenta empresarial                | El empresario necesita poder solicitar y obtener una marca de   verificación en su perfil para aumentar la confianza de los aventureros.                            | 5  |
| 11 | US04          | Iniciar sesión (Aventurero - Web)                 | El usuario aventurero registrado necesita poder iniciar sesión con sus   credenciales para acceder a su cuenta y funcionalidades personalizadas.                    | 5  |
| 12 | US05          | Iniciar sesión (Empresario - Web)                 | El usuario empresario registrado necesita poder iniciar sesión con sus   credenciales para acceder al panel de gestión de su negocio.                               | 5  |
| 13 | US09          | Edición de actividad (Empresario - Web)           | El empresario necesita poder editar los detalles de una actividad ya   publicada para corregir información o actualizarla.                                          | 5  |
| 14 | US14          | Calificación de publicación (Aventurero)          | El aventurero necesita poder asignar una calificación a una actividad en   la que participó para compartir su valoración general rápidamente.                       | 5  |
| 15 | US16          | Ver comentarios de mis publicaciones (Empresario) | El empresario necesita poder acceder a una sección donde vea todos los   comentarios/reseñas dejados en sus publicaciones para monitorear el feedback.              | 5  |
| 16 | US18          | Eliminación de perfil (Web)                       | El usuario registrado (Aventurero o Empresario) necesita poder eliminar   su cuenta y perfil de la plataforma para dejar de usar el servicio.                       | 5  |
| 17 | US07 (EP04)   | Edición de perfil (Web)                           | El usuario registrado (Aventurero o Empresario) necesita poder editar la   información de mi perfil para mantenerla actualizada.                                    | 5  |
| 18 | US02          | Sección características (Web)                     | El visitante necesita poder ver una sección de características para   entender qué ofrece AventuraPe.                                                               | 3  |
| 19 | US03          | Sección preguntas frecuentes (Web)                | El visitante necesita poder consultar una sección de preguntas frecuentes   para resolver sus dudas sobre la plataforma.                                            | 3  |
| 20 | US10          | Borrar actividad (Empresario - Web)               | El empresario necesita poder borrar una actividad publicada que ya no   está disponible o fue un error para mantener su oferta actualizada.                         | 3  |
| 21 | US17          | Guardar favoritos (Aventurero - Web)              | El aventurero necesita poder marcar una actividad como favorita para   guardarla en una lista personal y encontrarla fácilmente más tarde.                          | 3  |
| 22 | US01          | Interacción con hipervínculos (Web)               | El visitante necesita poder hacer clic en los enlaces de navegación para   ir a las diferentes secciones de la plataforma web.                                      | 2  |
