## Capítulo III: Requirements Specification

### 3.1. User Stories.

<table border="1" style="border-collapse:collapse; width:100%; table-layout:fixed;">
  <tr><th style="width:15%;">Epic /<br> Story/<br>ID</th>    <th style="width:15%;">Título</th><th style="width:35%;">Descripción</th><th style="width:25%;">Criterios de Aceptación</th><th style="width:10%;">Relacionado con<br>(Epic ID)</th></tr>
  <!-- Epic 01 -->
  <tr>
    <td>EP01</td>
    <td>Registro y autenticación</td>
    <td>
      <b>Como usuario</b>, quiero poder registrar, iniciar sesión, recuperar mi contraseña y cambiarla,
      <p>para poder acceder a la plataforma y mantener mi cuenta segura.</p>
    </td>
    <td>-</td>
    <td>-</td>
  </tr>
  <!-- Epic 02 -->
  <tr>
    <td>EP02</td>
    <td>Roles y permisos</td>
    <td>
      <b>Como administrador</b>, quiero administrar los diferentes perfiles bajo mi cuenta y otorgarles los permisos pertinentes,
      <p>para que realicen sus trabajos sin que personal no autorizado acceda a información reservada.</p>
    </td>
    <td>-</td>
    <td>-</td>
  </tr>
  <!-- Epic 03 -->
  <tr>
    <td>EP03</td>
    <td>Suscripciones y organización</td>
    <td>
      <b>Como usuario</b>, quiero manejar y monitorear mis suscripciones,
      <p>para poder crear y gestionar una mayor cantidad de organizaciones y asignarles su respectivo personal.</p>
    </td>
    <td>-</td>
    <td>-</td>
  </tr>
  <!-- Epic 04 -->
  <tr>
    <td>EP04</td>
    <td>Gestión de clientes</td>
    <td>
      <b>Como administrador</b>, quiero controlar la información, estado y puntos de entrega de clientes frecuentes,
      <p>para agilizar la asignación de zonas de despacho a transportistas.</p>
    </td>
    <td>-</td>
    <td>-</td>
  </tr>
  <!-- Epic 05 -->
  <tr>
    <td>EP05</td>
    <td>Ubicaciones</td>
    <td>
      <b>Como administrador</b>, quiero registrar, organizar y gestionar ubicaciones relacionadas con las operaciones de transporte,
      <p>para optimizar la planificación de rutas y la logística de entregas.</p>
    </td>
    <td>-</td>
    <td>-</td>
  </tr>
  <!-- Epic 06 -->
  <tr>
    <td>EP06</td>
    <td>Flota y Recursos</td>
    <td>
      <b>Como administrador</b>, quiero gestionar el estado de los vehículos y los recursos de la flota,
      <p>para garantizar que las unidades estén disponibles, en buen estado y listas para operar.</p>
    </td>
    <td>-</td>
    <td>-</td>
  </tr>
  <!-- Epic 07 -->
  <tr>
    <td>EP07</td>
    <td>Monitoreo y control de ruta</td>
    <td>
      <b>Como transportista</b>, quiero actualizar los estados de cada pedido a lo largo de la ruta de distribución,
      <p>para proporcionar visibilidad sobre mi progreso y garantizar que administración reciba información actualizada.</p>
    </td>
    <td>-</td>
    <td>-</td>
  </tr>
  <!-- Epic 08 -->
  <tr>
    <td>EP08</td>
    <td>Incidencias</td>
    <td>
      <b>Como transportista</b>, quiero reportar eventos inesperados que afecten la operación de transporte (retrasos, problemas mecánicos, clientes ausentes),
      <p>para que los administradores reciban notificaciones y puedan resolver o mitigar los problemas oportunamente.</p>
    </td>
    <td>-</td>
    <td>-</td>
  </tr>
  <!-- Epic 09 -->
  <tr>
    <td>EP09</td>
    <td>Reportes y análisis</td>
    <td>
      <b>Como administrador</b>, quiero generar reportes y análisis detallados sobre el rendimiento de mis vehículos,
      <p>para optimizar la eficiencia, mejorar las rutas y aumentar la satisfacción del cliente.</p>
    </td>
    <td>-</td>
    <td>-</td>
  </tr>
  <!-- Epic 10 -->
  <tr>
    <td>EP10</td>
    <td>Landing Page e internacionalización</td>
    <td>
      <b>Como visitante</b>, quiero acceder a un sitio web estático bien diseñado, segmentado y disponible en múltiples idiomas,
      <p>para informarme sobre la plataforma y facilitar mi decisión de registrarme.</p>
    </td>
    <td>-</td>
    <td>-</td>
  </tr>
  </table>
  <table border="1" style="border-collapse:collapse; width:100%; table-layout:fixed;">
  <!-- Separador de secciones -->
  <tr>
    <th style="width:15%;">Epic /<br> Story/<br>ID</th>
    <th style="width:15%;">Título</th>
    <th style="width:35%;">Descripción</th>
    <th style="width:25%;">Criterios de Aceptación</th>
    <th style="width:10%;">Relacionado con<br>(Epic ID)</th>
  </tr>
  <!-- User Story 01 -->
  <tr>
    <td>US01</td>
    <td>Crear cuenta</td>
    <td>
      <b>Como usuario</b>, quiero crear una nueva cuenta,
      <p>para estar registrado en la plataforma.</p>
    </td>
    <td>
      <b>Escenario 1: Creación de usuario</b><br>
      Dado que el usuario selecciona la opción de registro de cuenta,<br>
      Cuando ingresa los datos correspondientes,<br>
      Entonces se le informa que su cuenta se creó con éxito.<br><br>
      <b>Escenario 2: Usuario ya registrado</b><br>
      Dado que el usuario selecciona la opción de registro de cuenta,<br>
      Cuando ingresa los datos correspondientes,<br>
      Entonces la aplicación le avisa que ya existe una cuenta con ese nombre o correo.
    </td>
    <td>EP01</td>
  </tr>
<!-- User Story 02 -->
<tr>
<td>US02</td>
<td>Ingreso a la plataforma</td>
<td>
<b>Como usuario</b>, quiero poder ingresar con mi cuenta,
<p>para acceder a la plataforma.</p>
</td>
<td>
<b>Escenario 1: Inicio de sesión</b><br>
Dado que el usuario selecciona la opción iniciar sesión,<br>
Cuando ingresa su cuenta y contraseña correcta,<br>
Entonces la plataforma le permite el acceso.<br><br>
<b>Escenario 2: Error en iniciar sesión</b><br>
Dado que el usuario selecciona la opción iniciar sesión,<br>
Cuando no ingresa la contraseña o nombre correctos,<br>
Entonces aparece un mensaje que le dice que el usuario o contraseña no son correctos.
</td>
<td>EP01</td>
</tr>
<!-- User Story 03 -->
<tr>
<td>US03</td>
<td>Creación de rol de equipo de transporte</td>
<td>
  <b>Como administrador</b>, quiero crear roles de equipo de transporte,
  <p>para organizar a los equipos.</p>
</td>
<td>
<b>Escenario 1: Creación exitosa</b><br>
Dado que el administrador entra a la opción de gestión de roles,<br>
Cuando ingresa un nombre y descripción válidos para un nuevo rol,<br>
Entonces el sistema registra el rol y confirma su creación.<br><br>
<b>Escenario 2: Falta de información</b><br>
Dado que el administrador entra a la opción de gestión de roles,<br>
Cuando intenta guardar un rol sin nombre o datos obligatorios,<br>
Entonces el sistema muestra un mensaje de error indicando la falta de información.
</td>
<td>EP02</td>
</tr>
<!-- User Story 04 -->
<tr>
<td>US04</td>
<td>Gestión de permisos</td>
<td>
<b>Como administrador con suscripción</b>, quiero dar permisos necesarios a los miembros de los equipos,
<p>para que tengan acceso solo a la información o acciones pertinentes a su rol laboral.</p>
</td>
<td>
<b>Escenario 1: Permiso asignado</b><br>
Dado que el administrador selecciona a un miembro del equipo,<br>
Cuando le asigna un permiso específico relacionado a su rol,<br>
Entonces el sistema registra la asignación y confirma que el permiso fue otorgado.<br><br>
<b>Escenario 2: Permiso denegado</b><br>
Dado que el administrador selecciona a un miembro del equipo,<br>
Cuando intenta asignar un permiso no permitido por la suscripción,<br>
Entonces el sistema muestra un mensaje informando que no es posible otorgar ese permiso.
</td>
<td>EP02</td>
</tr>
<!-- User Story 05 -->
<tr>
<td>US05</td>
<td>Gestión de roles del equipo de transporte</td>
<td>
<b>Como administrador</b>, quiero actualizar o modificar los diferentes roles del equipo de transporte,<br>
<p>para renombrar, deshabilitar o habilitar los roles pertinentes a cada equipo de trabajo.</p>
</td>
<td>
<b>Escenario 1: Rol renombrado</b><br>
Dado que el administrador selecciona un rol existente,<br>
Cuando edita su nombre y guarda los cambios,<br>
Entonces el sistema actualiza el rol y confirma la modificación.<br><br>
<b>Escenario 2: Rol habilitado</b><br>
Dado que un rol estaba deshabilitado,<br>
Cuando el administrador lo habilita nuevamente,<br>
Entonces el sistema cambia su estado a activo y lo deja disponible para asignación.<br><br>
<b>Escenario 3: Rol deshabilitado</b><br>
Dado que un rol está en uso o activo,<br>
Cuando el administrador lo deshabilita,<br>
Entonces el sistema cambia su estado a inactivo y lo bloquea para nuevas asignaciones.
</td>
<td>EP02</td>
</tr>
<!-- User Story 06 -->
<tr>
<td>US06</td>
<td>Suscripción a planes</td>
<td>
<b>Como usuario</b>, quiero suscribirme a un plan de suscripción,<br>
<p>para poder acceder a los beneficios que este ofrece (ej. más cuentas, plan mensual).</p>
</td>
<td>
<b>Escenario 1: Suscripción exitosa</b><br>
Dado que el usuario selecciona un tipo de plan,<br>
Cuando ingresa la información de pago y confirma la suscripción,<br>
Entonces el sistema activa el plan y habilita los beneficios asociados.<br><br>
<b>Escenario 2: Falta de información</b><br>
Dado que el usuario intenta suscribirse,<br>
Cuando omite información obligatoria de pago o selección de plan,<br>
Entonces el sistema muestra un mensaje de error indicando la falta de datos.
</td>
<td>EP03</td>
</tr>
<!-- User Story 07 -->
<tr>
<td>US07</td>
<td>Gestión de perfil de la empresa</td>
<td>
<b>Como usuario con suscripción</b>, quiero crear y modificar el perfil de la empresa,<br>
<p>para personalizar la aplicación en base a la información de esta.</p>
</td>
<td>
<b>Escenario 1: Empresa creada</b><br>
Dado que el usuario accede a la opción de perfil de empresa,<br>
Cuando completa la información requerida y guarda,<br>
Entonces el sistema registra el perfil de la empresa.<br><br>
<b>Escenario 2: Empresa modificada</b><br>
Dado que el usuario ya tiene un perfil registrado,<br>
Cuando actualiza la información de la empresa y guarda,<br>
Entonces el sistema confirma la actualización exitosa.<br><br>
<b>Escenario 3: Falta de información</b><br>
Dado que el usuario intenta registrar o modificar un perfil,<br>
Cuando omite datos obligatorios,<br>
Entonces el sistema muestra un mensaje indicando qué información falta.
</td>
<td>EP03</td>
</tr>
<!-- User Story 08 -->
<tr>
<td>US08</td>
<td>Asignación del personal</td>
<td>
<b>Como usuario</b>, quiero agregar al personal al perfil de la empresa,<br>
<p>para hacer un seguimiento de sus actividades.</p>
</td>
<td>
<b>Escenario 1: Asignación exitosa</b><br>
Dado que el usuario accede a la opción de gestión de personal,<br>
Cuando ingresa los datos de un miembro válido,<br>
Entonces el sistema lo asocia correctamente al perfil de la empresa.<br><br>
<b>Escenario 2: Asignación denegada</b><br>
Dado que el usuario intenta asignar a una persona,<br>
Cuando el sistema no encuentra la cuenta ingresada,<br>
Entonces el sistema muestra un mensaje de error indicando que el personal no existe.
</td>
<td>EP03</td>
</tr>
<!-- User Story 09 -->
<tr>
<td>US09</td>
<td>Registro de clientes</td>
<td>
<b>Como administrador</b>, quiero registrar clientes frecuentes con su punto de entrega y forma de contacto,<br>
<p>para mantener una lista organizada.</p>
</td>
<td>
<b>Escenario 1: Registro exitoso</b><br>
Dado que el administrador accede a la opción de registro de clientes,<br>
Cuando ingresa la información completa y válida,<br>
Entonces el sistema guarda al cliente y confirma el registro.<br><br>
<b>Escenario 2: Información insuficiente</b><br>
Dado que el administrador intenta registrar un cliente,<br>
Cuando no ingresa todos los campos requeridos,<br>
Entonces el sistema muestra un mensaje indicando qué información falta.
</td>
<td>EP04</td>
</tr>
<!-- User Story 10 --> <tr> <td>US10</td> <td>Gestión de clientes</td> <td> <b>Como administrador</b>, quiero manejar el estado de los clientes,<br> <p>para poder determinar si están o no disponibles.</p> </td> <td> <b>Escenario 1: Cliente habilitado</b><br> Dado que el cliente estaba inhabilitado,<br> Cuando el administrador lo habilita,<br> Entonces el sistema cambia su estado a activo y disponible.<br><br>
  <b>Escenario 2: Cliente deshabilitado</b><br>
  Dado que el cliente está activo,<br>
  Cuando el administrador lo deshabilita,<br>
  Entonces el sistema cambia su estado a inactivo y restringe su uso en procesos.
</td>
<td>EP04</td>
</tr> <!-- User Story 11 --> <tr> <td>US11</td> <td>Actualizar información de contacto</td> <td> <b>Como administrador</b>, quiero actualizar la información de contacto del cliente,<br> <p>para poder comunicarme con este en caso de algún incidente.</p> </td> <td> <b>Escenario 1: Información modificada</b><br> Dado que el administrador selecciona un cliente registrado,<br> Cuando actualiza la información de contacto y guarda,<br> Entonces el sistema confirma la actualización exitosa.<br><br>
  <b>Escenario 2: Falta de información</b><br>
  Dado que el administrador intenta actualizar un contacto,<br>
  Cuando omite datos obligatorios como teléfono o correo,<br>
  Entonces el sistema muestra un mensaje indicando la falta de información.
</td>
<td>EP04</td>
</tr>
<!-- User Story 12 -->
<tr>
<td>US12</td>
<td>Crear ubicación y asignarla a un cliente</td>
<td>
<b>Como administrador</b>, quiero crear una ubicación en el mapa y asignarla a un cliente,<br>
<p>para usarla luego en las rutas.</p>
</td>
<td>
  <b>Escenario 1: Guardar dirección al crear la ubicación</b><br>
  Dado que soy Administrador y seleccioné el cliente "ACME",<br>
  Cuando escojo la ubicación en el mapa en una posición válida,<br>
  Entonces se crea la ubicación con latitud y longitud,<br>
  Y el sistema obtiene la dirección por reverse geocoding,<br>
  Y guarda la dirección formateada y el placeId junto con la ubicación.<br><br>
  <b>Escenario 2: Bloqueo si no hay cliente seleccionado</b><br>
  Dado que soy Administrador en la pantalla de Ubicaciones,<br>
  Y no he seleccionado un cliente,<br>
  Cuando intento guardar la nueva ubicación creada,<br>
  Entonces veo el mensaje "Seleccione un cliente",<br>
  Y la ubicación no se guarda.<br><br>
  <b>Escenario 3: Falla de geocoding con fallback</b><br>
  Dado que soy Administrador y seleccioné el cliente "ACME",<br>
  Y el servicio de geocoding no responde,<br>
  Cuando creo un punto en el mapa en una posición válida,<br>
  Entonces se muestra "Dirección no disponible" con opción de reintentar o editar manualmente.
</td>
<td>EP05</td>
</tr>
<!-- User Story 13 -->
<tr>
<td>US13</td>
<td>Reubicar una ubicación existente</td>
<td>
  <b>Como administrador</b>, quiero mover el marcador de una ubicación,<br>
  <p>para corregir su posición sin perder la relación con el cliente.</p>
</td>
<td>
  <b>Escenario 1: Reubicar arrastrando el marcador</b><br>
  Dado una ubicación existente asociada al cliente "ACME",<br>
  Cuando arrastro el marcador a una nueva posición,<br>
  Entonces la latitud y longitud de la ubicación se actualizan,<br>
  Y el sistema guarda el cambio correctamente.<br><br>
  <b>Escenario 2: Validar coordenadas obligatorias</b><br>
  Dado una ubicación existente sin latitud o longitud válidas,<br>
  Cuando intento utilizarla en la planificación de una ruta,<br>
  Entonces el sistema impide seleccionarla,<br>
  Y veo el mensaje "La ubicación requiere coordenadas válidas".
</td>
<td>EP05</td>
</tr>
<!-- User Story 14 -->
<tr>
<td>US14</td>
<td>Inhabilitar ubicación</td>
<td>
  <b>Como administrador</b>, quiero marcar una ubicación como cerrada,<br>
  <p>para que no pueda usarse en nuevas rutas.</p>
</td>
<td>
  <b>Escenario 1: Marcar ubicación como cerrada</b><br>
  Dado una ubicación activa asociada al cliente "ACME",<br>
  Cuando la marco como "Cerrada",<br>
  Entonces su estado pasa a "Inhabilitada",<br>
  Y deja de aparecer en los listados por defecto,<br>
  Y no puede seleccionarse en formularios de planificación.
</td>
<td>EP05</td>
</tr>
<!-- User Story 15 -->
<tr>
<td>US15</td>
<td>Filtrar puntos por cliente en el mapa</td>
<td>
  <b>Como administrador</b>, quiero buscar un cliente por nombre y ver solo sus puntos en el pa,<br>
  <p>para seleccionar rápidamente los puntos correctos.</p>
</td>
<td>
  <b>Escenario 1: Filtrar puntos por nombre de cliente</b><br>
  Dado que estoy en la pantalla de planificación con el mapa visible,<br>
  Y escribo "ACME" en el buscador de clientes,<br>
  Cuando selecciono el cliente "ACME",<br>
  Entonces el mapa muestra solo los puntos de "ACME",<br>
  Y los demás puntos se atenúan o se ocultan.<br><br>
  <b>Escenario 2: Limpiar filtro</b><br>
  Dado que tengo aplicado el filtro del cliente "ACME",<br>
  Cuando presiono "Limpiar filtro",<br>
  Entonces el mapa vuelve a mostrar todos los puntos disponibles.
</td>
<td>EP05</td>
</tr>
<!-- User Story 16 -->
<tr>
<td>US16</td>
<td>Agregar/Quitar puntos en una ruta</td>
<td>
  <b>Como administrador</b>, quiero asignar o quitar puntos en la ruta del día,<br>
  <p>para crear entregas rápidamente.</p>
</td>
<td>
  <b>Escenario 1: Asignar punto disponible a la ruta en borrador</b><br>
  Dado una ruta en estado "borrador" para la fecha 2025-09-17,<br>
  Y un punto "P-001" disponible para esa fecha,<br>
  Cuando selecciono el punto "P-001",<br>
  Entonces se muestra la información del punto,<br>
  Y al presionar “Agregar a la ruta” el punto queda reservado para la fecha 2025-09-17.r><br>
  <b>Escenario 2: Impedir duplicado el mismo día</b><br>
  Dado que el punto "P-001" ya está reservado en otra ruta para 2025-09-17,<br>
  Cuando intento seleccionarlo,<br>
  Entonces veo el mensaje "Este punto ya está asignado a otra ruta hoy",<br>
  Y el punto no se agrega a la ruta activa.<br><br>
  <b>Escenario 3: Quitar punto de la ruta</b><br>
  Dado que el punto "P-002" está asignado a la ruta en borrador,<br>
  Cuando selecciono nuevamente "P-002",<br>
  Entonces se muestra la información del punto,<br>
  Y aparece el botón “Quitar de la ruta”.
</td>
<td>EP05</td>
</tr>
<!-- User Story 17 -->
<tr>
<td>US17</td>
<td>Registrar vehículo</td>
<td>
<b>Como administrador</b>, quiero registrar un vehículo con placa y capacidad,<br>
<p>para poder asignarlo a una ruta.</p>
</td>
<td>
<b>Escenario 1: Registro exitoso</b><br>
Dado que soy Administrador en la pantalla de Vehículos,<br>
Cuando registro un vehículo con placa "ABC-123" y capacidad 1500 kg,<br>
Entonces el vehículo queda creado en estado "habilitado".<br><br>
<b>Escenario 2: Placa duplicada</b><br>
Dado que existe un vehículo con placa "ABC-123",<br>
Cuando intento registrar otro vehículo con la misma placa,<br>
Entonces veo el mensaje "La placa ya está registrada",<br>
Y el vehículo no se crea.
</td>
<td>EP06</td>
</tr>
<!-- User Story 18 -->
<tr>
<td>US18</td>
<td>Inhabilitar vehículo</td>
<td>
<b>Como administrador</b>, quiero inhabilitar un vehículo,<br>
<p>para evitar que se use en nuevas rutas.</p>
</td>
<td>
<b>Escenario 1: Inhabilitar evita nuevas asignaciones</b><br>
Dado un vehículo "ABC-123" en estado "habilitado",<br>
Cuando lo cambio a estado "inhabilitado",<br>
Entonces el sistema impide asignarlo a rutas nuevas,<br>
Y al intentar publicar una ruta que lo incluye,<br>
Entonces veo el mensaje "El vehículo está inhabilitado" y la publicación se bloquea.
</td>
<td>EP06</td>
</tr>
<!-- User Story 19 -->
<tr>
<td>US19</td>
<td>Publicar ruta bloquea edición</td>
<td>
<b>Como administrador</b>, quiero bloquear cambios al publicar,<br>
<p>para evitar modificaciones después de la planificación.</p>
</td>
<td>
<b>Escenario 1: Bloquear edición tras publicar</b><br>
Dado una ruta en estado "borrador" con entregas asignadas,<br>
Cuando publico la ruta,<br>
Entonces el estado cambia a "publicada",<br>
Y ya no puedo añadir ni quitar puntos.<br><br>
<b>Escenario 2: Impedir agregar punto en ruta publicada</b><br>
Dado una ruta en estado "publicada",<br>
Cuando intento asignar un nuevo punto desde el mapa,<br>
Entonces veo "La ruta está publicada y no admite cambios",<br>
Y el punto no se agrega.<br><br>
<b>Escenario 3: Publicación incompleta</b><br>
Dado que he creado una ruta sin vehículo o sin entregas,<br>
Cuando intento publicarla,<br>
Entonces veo el mensaje "Asigne un vehículo y al menos una entrega para publicar",<br>
Y la ruta permanece en estado "borrador".
</td>
<td>EP06</td>
</tr>
<!-- User Story 20 -->
<tr>
<td>US20</td>
<td>Crear una ruta en borrador</td>
<td>
<b>Como administrador</b>, quiero crear una ruta del día y guardarla como borrador,<br>
<p>para que los transportistas aún no vean la ruta antes de publicarla.</p>
</td>
<td>
<b>Escenario 1: Crear ruta en borrador</b><br>
Dado que soy Administrador en la pantalla de Rutas,<br>
Cuando ingreso la fecha "2025-09-18" y un nombre de ruta válido,<br>
Entonces se crea la ruta con estado "borrador",<br>
Y queda disponible para asignar vehículo y puntos.<br><br>
<b>Escenario 2: Validar fecha obligatoria</b><br>
Dado que no ingreso una fecha al crear la ruta,<br>
Cuando intento guardar,<br>
Entonces veo el mensaje "Debe ingresar una fecha válida",<br>
Y la ruta no se crea.
</td>
<td>EP07</td>
</tr>
<!-- User Story 21 -->
<tr>
<td>US21</td>
<td>Transportista actualiza estado de entrega</td>
<td>
<b>Como transportista</b>, quiero marcar una entrega como entregada o rechazada con motivo,br>
<p>para dejar constancia del resultado.</p>
</td>
<td>
<b>Escenario 1: Marcar entrega como finalizada</b><br>
Dado una ruta publicada que ha sido iniciada,<br>
Y una entrega en estado "pendiente",<br>
Cuando marco la entrega como "entregada",<br>
Entonces la entrega cambia a estado "entregada",<br>
Y se registra la hora de confirmación y se actualiza su progreso de entrega.<br><br>
<b>Escenario 2: Marcar entrega como rechazada con motivo</b><br>
Dado una ruta publicada que ha sido iniciada,<br>
Y una entrega en estado "pendiente",<br>
Cuando marco la entrega como "rechazada" e ingreso el motivo "Destinatario ausente",<br>
Entonces la entrega cambia a estado "rechazada",<br>
Y el motivo queda guardado y se actualiza el progreso de entregas con rechazo.
</td>
<td>EP07</td>
</tr>
<!-- User Story 22 -->
<tr>
<td>US22</td>
<td>Cierre de ruta con y sin pendientes</td>
<td>
<b>Como transportista</b>, quiero cerrar la ruta al finalizar y reprogramar pendientes,<br>
<p>para visualizar deudas y continuar al día siguiente.</p>
</td>
<td>
<b>Escenario 1: Cierre normal sin pendientes</b><br>
Dado una ruta iniciada cuyas entregas están todas en estado terminal,<br>
Cuando cierro la ruta,<br>
Entonces el estado de la ruta cambia a "completada".<br><br>
<b>Escenario 2: Cierre forzado con pendientes y reprogramación</b><br>
Dado una ruta iniciada con entregas en estado "pendiente",<br>
Cuando cierro la ruta en modo "forzado",<br>
Entonces el estado de la ruta cambia a "cerrada con pendientes",<br>
Y las entregas pendientes se listarán en la ruta como entregas pendientes.
</td>
<td>EP07</td>
</tr>
<!-- User Story 23 -->
<tr>
<td>US23</td>
<td>Vista previa de la ruta</td>
<td>
<b>Como administrador</b>, quiero una vista previa que resalte solo los puntos asignados,br>
<p>para validar la selección antes de publicar.</p>
</td>
<td>
<b>Escenario 1: Mostrar solo los puntos asignados</b><br>
Dado una ruta en borrador con puntos asignados,<br>
Cuando activo la "Vista previa",<br>
Entonces el mapa centra y resalta únicamente los puntos de la ruta,<br>
Y se muestra una lista lateral con los puntos seleccionados.
</td>
<td>EP07</td>
</tr>
<!-- User Story 24 -->
<tr>
<td>US24</td>
<td>Visualización de progreso</td>
<td>
<b>Como administrador</b>, quiero ver el progreso de las entregas en tiempo real,<br>
<p>para saber exactamente cuánto falta por completar y tomar decisiones oportunas.</p>
</td>
<td>
<b>Escenario 1: Estado actualizado</b><br>
Dado que un pedido está en tránsito,<br>
Cuando el transportista avanza en la ruta,<br>
Entonces el administrador puede ver los avances en el panel de monitoreo mediante líneas de progreso.<br><br>
<b>Escenario 2: Notificación automática</b><br>
Dado que el pedido cambia de estado,<br>
Cuando pasa a "Rechazo",<br>
Entonces el administrador recibe una alerta en el sistema de gestión para registrar el  y tomar acción si es necesario.
</td>
<td>EP07</td>
</tr>
<!-- User Story 25 -->
<tr>
<td>US25</td>
<td>Visualizar rutas asignadas</td>
<td>
<b>Como transportista</b>, quiero quiero ver las rutas que me han sido asignadas para el día,<br>
<p>para conocer mis entregas pendientes y planificar mi recorrido.</p>
</td>
<td>
<b>Escenario 1: Ver ruta del día</b><br>
Dado que he iniciado sesión en la aplicación,<br>
Cuando ingreso a la sección “Mis rutas”,<br>
Entonces veo una lista con las rutas asignadas del día y su estado (en progreso, completadas o rechazadas).
<br><br>
<b>Escenario 2: Detalle de ruta seleccionada</b><br>
Dado que selecciono una ruta,<br>
Cuando entro al detalle,<br>
Entonces se muestra el mapa con los puntos de entrega, el progreso (X/Y completadas) y el listado de clientes con dirección.
</td>
<td>EP07</td>
</tr>
<!-- User Story 26 -->
<tr>
<td>US26</td>
<td>Filtrar entregas por estado</td>
<td>
<b>Como transportista</b>, quiero filtrar mis entregas según su estado (in progress, completed, rejected),<br>
<p>para organizar mejor mi jornada.</p>
</td>
<td>
<b>Escenario 1: Filtro aplicado</b><br>
Dado que estoy en la vista de mis entregas,<br>
Cuando selecciono un filtro de estado,<br>
Entonces se muestran únicamente las entregas correspondientes a ese estado.<br><br>
<b>Escenario 2: Filtro limpio</b><br>
Dado que tengo un filtro activo,<br>
Cuando presiono “Todos”,<br>
Entonces vuelvo a ver la lista completa de entregas.
</td>
<td>EP07</td>
</tr>
<!-- User Story 27 -->
<tr>
<td>US27</td>
<td>Marcar entrega como completada</td>
<td>
<b>Como transportista</b>, quiero marcar una entrega como completada,<br>
<p>para registrar su cumplimiento y actualizar el progreso total de la ruta.
</p>
</td>
<td>
<b>Escenario 1:  Entrega completada exitosamente</b><br>
Dado que tengo una entrega en estado “in progress”,<br>
Cuando presiono el botón “Complete”,<br>
Entonces la entrega cambia a estado “Completed” y se actualiza la barra de progreso.<br><br>
<b>Escenario 2: Actualización del progreso total</b><br>
Dado que completo una entrega,<br>
Cuando el sistema recalcula el total,<br>
Entonces el progreso se muestra actualizado (por ejemplo, “3/8 completadas – 37%”).
</td>
<td>EP07</td>
</tr>
<!-- User Story 28 -->
<tr>
<td>US28</td>
<td>Rechazar entrega y registrar motivo</td>
<td>
<b>Como transportista</b>, quiero poder rechazar una entrega e indicar el motivo del rechazo,<br>
<p>para que el administrador conozca la causa.
</p>
</td>
<td>
<b>Escenario 1: Selección de motivo predefinido</b><br>
Dado que selecciono “Reject”,<br>
Cuando se abre el modal de rechazo,<br>
Entonces puedo elegir entre los motivos predefinidos (cliente ausente, dirección incorrecta, cliente rechazó entrega, otro motivo).
<br><br>
<b>Escenario 2: Ingreso de detalle adicional</b><br>
Dado que selecciono “Otro motivo”,<br>
Cuando escribo una descripción,<br>
Entonces el sistema guarda el texto junto al registro del rechazo.
<br><br>
<b>Escenario 3: Estado actualizado</b><br>
Dado que confirmo el rechazo,<br>
Cuando cierro el modal,<br>
Entonces la entrega cambia a estado “Rejected” y el progreso se actualiza automáticamente.
</td>
<td>EP07</td>
</tr>
<!-- User Story 30 -->
<tr>
<td>US29</td>
<td>Asignación de flota a la ruta</td>
<td>
<b>Como administrador</b>, quiero asignar vehículos y transportistas disponibles a una ruta planificada,<br>
<p>para asegurar que cada vehiculo tenga un equipo asignado y las entregas puedan ejecutarse sin retrasos.</p>
</td>
<td>
<b>Escenario 1: Selección de ruta para asignar flota</b><br>
Dado que el administrador se encuentra en la vista Routes List,<br>
Cuando selecciona una ruta con estado “Pending assignment” y presiona el botón “Assign”,<br>
Entonces el sistema abre el módulo Locations mostrando los puntos de entrega asociados a esa ruta.<br><br>
<b>Escenario 2: Asignación de equipo de transporte</b><br>
Dado que el administrador ha visualizado las ubicaciones y detalles de la ruta,<br>
Cuando accede a la sección Teams y selecciona un transportista y vehículo disponibles,<br>
Entonces el sistema asigna automáticamente esa flota a la ruta seleccionada, mostrando su estado como “Assigned”.
</td>
<td>EP07</td>
</tr>
<!-- User Story 31 -->
<tr>
<td>US30</td>
<td>Adjuntar evidencia</td>
<td>
<b>Como transportista</b>, quiero adjuntar fotos al registrar una incidencia,<br>
<p>para que Administración tenga pruebas claras de la situación.</p>
</td>
<td>
<b>Escenario 1: Foto como evidencia</b><br>
Dado que el transportista reporta "Cliente ausente",<br>
Cuando adjunta una foto de la ubicación y la tienda cerrada,<br>
Entonces la evidencia queda registrada junto a la incidencia.
</td>
<td>EP08</td>
</tr>
<!-- User Story 32 -->
<tr>
<td>US31</td>
<td>Etiquetado de incidencias por prioridad</td>
<td>
<b>Como administrador</b>, quiero que las incidencias reportadas por los transportistas se etiqueten según su nivel de prioridad,<br>
<p>para identificar rápidamente cuáles requieren atención inmediata y gestionarlas de manera eficiente.</p>
</td>
<td>
<b>Escenario 1: Priorización de incidencia etiquetada como urgente</b><br>
Dado que hay múltiples incidencias registradas en el sistema,<br>
Cuando un transportista reporta una incidencia y la etiqueta como "Urgente" (ej. avería grave del vehículo),<br>
Entonces el sistema destaca la incidencia en la interfaz del administrador (ej. con alerta visual o en la parte superior de la lista),<br>
Y se envía al apartado de incidencias.<br><br>
<b>Escenario 2: Rechazo de entrega por mercadería dañada</b><br>
Dado que un transportista reporta una incidencia de "Cliente no acepta el pedido" por mercadería dañada,<br>
Cuando el transportista etiqueta la incidencia como "Media" y adjunta evidencia (ej. foto del daño),<br>
Entonces el sistema registra la incidencia con la etiqueta "Media" y la evidencia,<br>
Y se adjunta en el apartado de incidencias para coordinar la reposición o reprogramación de la entrega.
</td>
<td>EP08</td>
</tr>
<!-- User Story 33 -->
<tr>
<td>US32</td>
<td>Generación de reportes operativos</td>
<td>
<b>Como administrador</b>, quiero generar reportes de entregas completadas, fallidas y pendientes,<br>
<p>para evaluar el desempeño logístico y tomar decisiones de mejora.</p>
</td>
<td>
<b>Escenario 1: Reporte diario</b><br>
Dado que finaliza la jornada de entregas,<br>
Cuando el administrador genera el reporte,<br>
Entonces se visualizan métricas de pedidos entregados, fallidos y pendientes.<br><br>
<b>Escenario 2: Exportación de reporte</b><br>
Dado que el administrador consulta un reporte en el sistema,<br>
Cuando selecciona la opción "Exportar",<br>
Entonces se descarga el archivo en formato Excel.
</td>
<td>EP09</td>
</tr>
<!-- User Story 34 -->
  <tr>
    <td>US33</td>
    <td>Diseño responsivo y navegación</td>
    <td>
      <b>Como visitante</b>, quiero que la landing page se adapte a cualquier dispositivo y tenga navegación clara,
      <p>para explorar fácilmente la información sin importar si uso móvil, tablet o escritorio.</p>
    </td>
    <td>
      <b>Escenario 1: Vista en dispositivos móviles</b><br>
      Dado que el visitante abre la landing page en un celular,<br>
      Cuando navega entre secciones,<br>
      Entonces el contenido se adapta sin perder legibilidad ni usabilidad.<br><br>
      <b>Escenario 2: Navegación intuitiva</b><br>
      Dado que el visitante ingresa al sitio,<br>
      Cuando usa el menú principal,<br>
      Entonces puede acceder rápidamente a las secciones principales sin confusión.
    </td>
    <td>EP10</td>
  </tr>
  <!-- User Story 35 -->
  <tr>
    <td>US34</td>
    <td>Secciones segmentadas</td>
    <td>
      <b>Como visitante del segmento empresa de transporte</b>, quiero ver una sección dedicada con beneficios y planes,
      <p>para evaluar si la plataforma se ajusta a las necesidades de mi negocio.</p>
    </td>
    <td>
      <b>Escenario 1: Visualización de planes</b><br>
      Dado que el visitante navega a la sección de empresas de transporte,<br>
      Cuando revisa el contenido,<br>
      Entonces visualiza información sobre los planes premium y sus beneficios.<br><br>
      <b>Escenario 2: Segmento correcto</b><br>
      Dado que existen diferentes tipos de visitantes,<br>
      Cuando un visitante del segmento "transportista independiente" ingresa,<br>
      Entonces ve una sección adaptada a sus necesidades específicas.
    </td>
    <td>EP10</td>
  </tr>
  <!-- User Story 30 -->
  <tr>
    <td>US35</td>
    <td>Internacionalización (i18n)</td>
    <td>
      <b>Como visitante internacional</b>, quiero poder seleccionar el idioma de la landing page (ej. español o inglés),
      <p>para comprender claramente la propuesta de valor sin barreras idiomáticas.</p>
    </td>
    <td>
      <b>Escenario 1: Selección de idioma</b><br>
      Dado que el visitante está en la landing page,<br>
      Cuando selecciona "Inglés" en el selector de idioma,<br>
      Entonces todo el contenido se muestra en inglés.<br><br>
      <b>Escenario 2: Idioma por defecto</b><br>
      Dado que un visitante abre la página sin seleccionar idioma,<br>
      Cuando el sistema detecta la configuración de su navegador,<br>
      Entonces la landing page se muestra en el idioma más adecuado automáticamente.
    </td>
    <td>EP10</td>
  </tr>
</table>

### 3.2. Impact Mapping.

A continuación se presenta el Impact Map de Rutana, el cual permite visualizar de manera clara
cómo las funcionalidades clave de la aplicación se alinean con los objetivos de negocio, considerando
a los actores involucrados y los impactos esperados en su comportamiento.

![impact mapping](./Resources/Capitulo_3/impact%20mapping.png)

### 3.3. Product Backlog.

<table border="1" style="border-collapse:collapse; width:100%; table-layout:fixed;">
  <tr>
    <th style="width:4%; word-wrap:break-word; white-space:normal;"># Orden</th>
    <th style="width:10%; word-wrap:break-word; white-space:normal;">User Story Id</th>
    <th style="width:24%; word-wrap:break-word; white-space:normal;">Título</th>
    <th style="width:42%; word-wrap:break-word; white-space:normal;">Descripción</th>
    <th style="width:20%; word-wrap:break-word; white-space:normal;">Story Points <br> (1 / 2 / 3 / 5 / 8)</th>
  </tr>
  <!-- US28 -->
  <tr>
    <td>1</td>
    <td>US33</td>
    <td>Diseño responsivo y navegación</td>
    <td><b>Como visitante</b>, quiero que la landing se adapte y sea clara,<br><p>para explorar en móvil/tablet/desktop.</p>
        <b>Escenario 1:</b> Vista móvil usable. <br>
        <b>Escenario 2:</b> Navegación intuitiva.</td>
    <td>5</td>
  </tr>
  <!-- US29 -->
  <tr>
    <td>2</td>
    <td>US34</td>
    <td>Secciones segmentadas</td>
    <td><b>Como empresa de transporte</b>, quiero una sección dedicada con beneficios y planes,<br><p>para evaluar si se ajusta a mi negocio.</p>
        <b>Escenario 1:</b> Visualización de planes. <br>
        <b>Escenario 2:</b> Segmento correcto por tipo de visitante.</td>
    <td>5</td>
  </tr>
  <!-- US30 -->
  <tr>
    <td>3</td>
    <td>US35</td>
    <td>Internacionalización (i18n)</td>
    <td><b>Como visitante internacional</b>, quiero seleccionar idioma (ES/EN),<br><p>para entender la propuesta sin barreras.</p>
        <b>Escenario 1:</b> Selector de idioma. <br>
        <b>Escenario 2:</b> Idioma por defecto según navegador.</td>
    <td>5</td>
  </tr>
  <!-- US01 -->
  <tr>
    <td>4</td>
    <td>US01</td>
    <td>Crear cuenta</td>
    <td><b>Como usuario</b>, quiero crear una nueva cuenta,<br><p>para estar registrado en la plataforma.</p>
        <b>Escenario 1:</b> Creación de usuario. <br>
        <b>Escenario 2:</b> Usuario ya registrado.</td>
    <td>3</td>
  </tr>
  <!-- US05 -->
  <tr>
    <td>5</td>
    <td>US02</td>
    <td>Ingreso a la plataforma</td>
    <td><b>Como usuario</b>, quiero poder ingresar con mi cuenta,<br><p>para acceder a la plataforma.</p>
        <b>Escenario 1:</b> Inicio de sesión. <br>
        <b>Escenario 2:</b> Error en iniciar sesión.</td>
    <td>3</td>
  </tr>
  <!-- US06 -->
  <tr>
    <td>6</td>
    <td>US03</td>
    <td>Creación de rol de equipo de transporte</td>
    <td><b>Como administrador</b>, quiero crear roles de equipo de transporte,<br><p>para organizar a los equipos.</p>
        <b>Escenario 1:</b> Creación exitosa. <br>
        <b>Escenario 2:</b> Falta de información.</td>
    <td>3</td>
  </tr>
  <!-- US07 -->
  <tr>
    <td>7</td>
    <td>US04</td>
    <td>Gestión de permisos</td>
    <td><b>Como administrador con suscripción</b>, quiero dar permisos a los miembros,<br><p>para limitar el acceso según su rol.</p>
        <b>Escenario 1:</b> Permiso asignado. <br>
        <b>Escenario 2:</b> Permiso denegado por plan.</td>
    <td>5</td>
  </tr>
  <!-- US08 -->
  <tr>
    <td>8</td>
    <td>US05</td>
    <td>Gestión de roles del equipo de transporte</td>
    <td><b>Como administrador</b>, quiero actualizar/renombrar/deshabilitar roles,<br><p>para mantenerlos vigentes por equipo.</p>
        <b>Escenario 1:</b> Rol renombrado. <br>
        <b>Escenario 2:</b> Rol habilitado. <br>
        <b>Escenario 3:</b> Rol deshabilitado.</td>
    <td>3</td>
  </tr>
  <!-- US09 -->
  <tr>
    <td>9</td>
    <td>US06</td>
    <td>Suscripción a planes</td>
    <td><b>Como usuario</b>, quiero suscribirme a un plan,<br><p>para acceder a beneficios (más cuentas, plan mensual).</p>
        <b>Escenario 1:</b> Suscripción exitosa. <br>
        <b>Escenario 2:</b> Falta de información.</td>
    <td>8</td>
  </tr>
  <!-- US10 -->
  <tr>
    <td>10</td>
    <td>US07</td>
    <td>Gestión de perfil de la empresa</td>
    <td><b>Como usuario con suscripción</b>, quiero crear/modificar el perfil de empresa,<br><p>para personalizar la aplicación.</p>
        <b>Escenario 1:</b> Empresa creada. <br>
        <b>Escenario 2:</b> Empresa modificada. <br>
        <b>Escenario 3:</b> Falta de información.</td>
    <td>3</td>
  </tr>
  <!-- US11 -->
  <tr>
    <td>11</td>
    <td>US08</td>
    <td>Asignación del personal</td>
    <td><b>Como usuario</b>, quiero agregar personal al perfil de empresa,<br><p>para dar seguimiento a sus actividades.</p>
        <b>Escenario 1:</b> Asignación exitosa. <br>
        <b>Escenario 2:</b> Asignación denegada (usuario no existe).</td>
    <td>3</td>
  </tr>
  <!-- US12 -->
  <tr>
    <td>12</td>
    <td>US09</td>
    <td>Registro de clientes</td>
    <td><b>Como administrador</b>, quiero registrar clientes frecuentes,<br><p>para mantener una lista organizada.</p>
        <b>Escenario 1:</b> Registro exitoso. <br>
        <b>Escenario 2:</b> Información insuficiente.</td>
    <td>3</td>
  </tr>
  <!-- US13 -->
  <tr>
    <td>13</td>
    <td>US10</td>
    <td>Gestión de clientes</td>
    <td><b>Como administrador</b>, quiero habilitar/inhabilitar clientes,<br><p>para controlar su disponibilidad.</p>
        <b>Escenario 1:</b> Cliente habilitado. <br>
        <b>Escenario 2:</b> Cliente deshabilitado.</td>
    <td>2</td>
  </tr>
  <!-- US14 -->
  <tr>
    <td>14</td>
    <td>US11</td>
    <td>Actualizar información de contacto</td>
    <td><b>Como administrador</b>, quiero actualizar contactos del cliente,<br><p>para comunicar incidentes.</p>
        <b>Escenario 1:</b> Información modificada. <br>
        <b>Escenario 2:</b> Falta de información.</td>
    <td>2</td>
  </tr>
  <!-- US15 -->
  <tr>
    <td>15</td>
    <td>US12</td>
    <td>Crear ubicación y asignarla a un cliente</td>
    <td><b>Como administrador</b>, quiero crear una ubicación en el mapa,<br><p>para usarla luego en rutas.</p>
        <b>Escenario 1:</b> Guardar dirección (reverse geocoding). <br>
        <b>Escenario 2:</b> Bloqueo sin cliente seleccionado. <br>
        <b>Escenario 3:</b> Falla de geocoding con fallback.</td>
    <td>8</td>
  </tr>
  <!-- US16 -->
  <tr>
    <td>16</td>
    <td>US13</td>
    <td>Reubicar una ubicación existente</td>
    <td><b>Como administrador</b>, quiero mover el marcador de una ubicación,<br><p>para corregir su posición.</p>
        <b>Escenario 1:</b> Reubicar arrastrando. <br>
        <b>Escenario 2:</b> Validar coordenadas obligatorias.</td>
    <td>3</td>
  </tr>
  <!-- US17 -->
  <tr>
    <td>17</td>
    <td>US14</td>
    <td>Inhabilitar ubicación</td>
    <td><b>Como administrador</b>, quiero marcar una ubicación como cerrada,<br><p>para no usarla en nuevas rutas.</p>
        <b>Escenario 1:</b> Marcar como cerrada e impedir selección.</td>
    <td>2</td>
  </tr>
  <!-- US18 -->
  <tr>
    <td>18</td>
    <td>US15</td>
    <td>Filtrar puntos por cliente en el mapa</td>
    <td><b>Como administrador</b>, quiero ver solo los puntos de un cliente,<br><p>para seleccionar rápidamente.</p>
        <b>Escenario 1:</b> Filtrar por nombre. <br>
        <b>Escenario 2:</b> Limpiar filtro.</td>
    <td>3</td>
  </tr>

  <!-- US19 -->
  <tr>
    <td>19</td>
    <td>US16</td>
    <td>Agregar/Quitar puntos en una ruta</td>
    <td><b>Como administrador</b>, quiero asignar o quitar puntos en la ruta del día,<br><p>para crear entregas rápidamente.</p>
        <b>Escenario 1:</b> Asignar y reservar punto. <br>
        <b>Escenario 2:</b> Impedir duplicado el mismo día. <br>
        <b>Escenario 3:</b> Quitar punto.</td>
    <td>5</td>
  </tr>

  <!-- US20 -->
  <tr>
    <td>20</td>
    <td>US17</td>
    <td>Registrar vehículo</td>
    <td><b>Como administrador</b>, quiero registrar un vehículo con placa y capacidad,<br><p>para asignarlo a una ruta.</p>
        <b>Escenario 1:</b> Registro exitoso. <br>
        <b>Escenario 2:</b> Placa duplicada.</td>
    <td>2</td>
  </tr>

  <!-- US21 -->
  <tr>
    <td>21</td>
    <td>US18</td>
    <td>Inhabilitar vehículo</td>
    <td><b>Como administrador</b>, quiero inhabilitar un vehículo,<br><p>para evitar su uso en nuevas rutas.</p>
        <b>Escenario 1:</b> Bloquea nuevas asignaciones/publicación.</td>
    <td>3</td>
  </tr>

  <!-- US22 -->
  <tr>
    <td>22</td>
    <td>US19</td>
    <td>Publicar ruta bloquea edición</td>
    <td><b>Como administrador</b>, quiero bloquear cambios al publicar,<br><p>para evitar modificaciones posteriores.</p>
        <b>Escenario 1:</b> Bloquear edición tras publicar. <br>
        <b>Escenario 2:</b> Impedir agregar punto en publicada. <br>
        <b>Escenario 3:</b> Validar requisitos mínimos.</td>
    <td>3</td>
  </tr>
  <!-- US23 -->
  <tr>
    <td>23</td>
    <td>US20</td>
    <td>Crear una ruta en borrador</td>
    <td><b>Como administrador</b>, quiero crear una ruta del día en borrador,<br><p>para ocultarla hasta publicar.</p>
        <b>Escenario 1:</b> Crear borrador. <br>
        <b>Escenario 2:</b> Validar fecha obligatoria.</td>
    <td>3</td>
  </tr>
  <!-- US24 -->
  <tr>
    <td>24</td>
    <td>US21</td>
    <td>Transportista actualiza estado de entrega</td>
    <td><b>Como transportista</b>, quiero marcar entregada o rechazada con motivo,<br><p>para dejar constancia.</p>
        <b>Escenario 1:</b> Entrega finalizada. <br>
        <b>Escenario 2:</b> Rechazada con motivo.</td>
    <td>5</td>
  </tr>
  <!-- US25 -->
  <tr>
    <td>25</td>
    <td>US22</td>
    <td>Cierre de ruta con y sin pendientes</td>
    <td><b>Como transportista</b>, quiero cerrar la ruta y reprogramar pendientes,<br><p>para continuar al día siguiente.</p>
        <b>Escenario 1:</b> Cierre normal. <br>
        <b>Escenario 2:</b> Cierre forzado con pendientes.</td>
    <td>5</td>
  </tr>
  <!-- US26 -->
  <tr>
    <td>26</td>
    <td>US23</td>
    <td>Vista previa de la ruta</td>
    <td><b>Como administrador</b>, quiero una vista previa con solo puntos asignados,<br><p>para validar antes de publicar.</p>
        <b>Escenario 1:</b> Mostrar y resaltar puntos asignados.</td>
    <td>3</td>
  </tr>
  <!-- US27 -->
  <tr>
    <td>27</td>
    <td>US24</td>
    <td>Visualización de progreso</td>
    <td><b>Como administrador</b>, quiero ver progreso en tiempo real y alertas,<br><p>para tomar decisiones oportunas.</p>
        <b>Escenario 1:</b> Estado actualizado en panel. <br>
        <b>Escenario 2:</b> Notificación automática.</td>
    <td>8</td>
  </tr>
  <!-- User Story 25 -->
<tr>
 <td>28</td>
<td>US25</td>
<td>Visualizar rutas asignadas</td>
<td>
<b>Como transportista</b>, quiero quiero ver las rutas que me han sido asignadas para el día,<br>
<p>para conocer mis entregas pendientes y planificar mi recorrido.</p>
<b>Escenario 1: Ver ruta del día</b><br>
<b>Escenario 2: Detalle de ruta seleccionada</b><br>
</td>
<td>5</td>
</tr>
<!-- User Story 26 -->
<tr>
 <td>29</td>
<td>US26</td>
<td>Filtrar entregas por estado</td>
<td>
<b>Como transportista</b>, quiero filtrar mis entregas según su estado (in progress, completed, rejected),<br>
<p>para organizar mejor mi jornada.</p>
<b>Escenario 1: Filtro aplicado</b><br>
<b>Escenario 2: Filtro limpio</b><br>
</td>
<td>8</td>
</tr>
<!-- User Story 27 -->
<tr>
 <td>30</td>
<td>US27</td>
<td>Marcar entrega como completada</td>
<td>
<b>Como transportista</b>, quiero marcar una entrega como completada,<br>
<p>para registrar su cumplimiento y actualizar el progreso total de la ruta.
</p>
<b>Escenario 1:  Entrega completada exitosamente</b><br>
zación del progreso total</b><br>
</td>
<td>8</td>
</tr>
<!-- User Story 28 -->
<tr>
 <td>31</td>
<td>US28</td>
<td>Rechazar entrega y registrar motivo</td>
<td>
<b>Como transportista</b>, quiero poder rechazar una entrega e indicar el motivo del rechazo,<br>
<p>para que el administrador conozca la causa.
</p>
<b>Escenario 1: Selección de motivo predefinido</b><br>
<b>Escenario 2: Ingreso de detalle adicional</b><br>
<b>Escenario 3: Estado actualizado</b><br>
</td>
<td>8</td>
</tr>
<!-- User Story 30 -->
<tr>
 <td>33</td>
<td>US29</td>
<td>Asignación de flota a la ruta</td>
<td>
<b>Como administrador</b>, quiero asignar vehículos y transportistas disponibles a una ruta planificada,<br>
<p>para asegurar que cada vehiculo tenga un equipo asignado y las entregas puedan ejecutarse sin retrasos.</p>
<b>Escenario 1: Selección de ruta para asignar flota</b><br>
<b>Escenario 2: Asignación de equipo de transporte</b><br>
</td>
<td>8</td>
</tr>
  <!-- US28 -->
  <tr>
    <td>34</td>
    <td>US30</td>
    <td>Adjuntar evidencia</td>
    <td><b>Como transportista</b>, quiero adjuntar fotos en incidencias,<br><p>para brindar pruebas claras.</p>
        <b>Escenario 1:</b> Foto como evidencia.</td>
    <td>5</td>
  </tr>
  <!-- US29 -->
  <tr>
    <td>31</td>
    <td>US32</td>
    <td>Etiquetado de incidencias por prioridad</td>
    <td><b>Como administrador</b>, quiero etiquetar incidencias por prioridad,<br><p>para gestionar lo urgente primero.</p>
        <b>Escenario 1:</b> Incidencia urgente destacada. <br>
        <b>Escenario 2:</b> Rechazo por mercadería dañada con evidencia.</td>
    <td>5</td>
  </tr>
  <!-- US30 -->
  <tr>
    <td>30</td>
    <td>US32</td>
    <td>Generación de reportes operativos</td>
    <td><b>Como administrador</b>, quiero reportes de entregas y exportación a Excel,<br><p>para evaluar desempeño.</p>
        <b>Escenario 1:</b> Reporte diario. <br>
        <b>Escenario 2:</b> Exportación a Excel.</td>
    <td>5</td>
  </tr>
</table>
