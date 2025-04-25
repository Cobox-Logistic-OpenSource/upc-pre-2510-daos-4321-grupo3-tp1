
## 3.1 To-Be Scenario Mapping
### Segmento 1: Gestores de Flota

| Phases                      | Planificación de rutas                           | Monitoreo en tiempo real                             | Evaluación y toma de decisiones                         |
|----------------------------|--------------------------------------------------|-----------------------------------------------------|---------------------------------------------------------|
| **Doing**                  | - Ingresan a la plataforma para asignar rutas a los conductores. <br> - Consultan el estado de los pedidos y la disponibilidad de unidades. | - Visualizan el avance en tiempo real de las unidades con geolocalización. <br> - Reciben alertas ante incidencias reportadas. | - Revisan los reportes automáticos generados por el sistema. <br> - Comparan indicadores clave de eficiencia y cumplimiento. |
| **Thinking**               | - ¿Están bien distribuidas las rutas para hoy?<br> - ¿Qué unidades requieren mantenimiento?         | - ¿Por qué esta unidad está detenida?<br> - ¿El conductor reportó el incidente a tiempo? | - ¿Estamos cumpliendo con los tiempos de entrega?<br> - ¿Qué rutas presentan mayor gasto de combustible? |
| **Feeling**                | - Confiado en que el sistema le da control sobre la operación.                        | - Atento y en constante supervisión.<br> - Preocupado si una unidad se desvía o se detiene sin razón. | - Seguro con la información disponible para tomar decisiones. <br> - Motivado a mejorar resultados semanales. |

### Segmento 2: Conductores de Transporte

| Phases                      | Inicio del día y revisión de ruta                      | Registro de entrega y recolección de evidencia     | Reporte de incidencias y mantenimiento                  |
|----------------------------|--------------------------------------------------------|---------------------------------------------------|----------------------------------------------------------|
| **Doing**                  | - Acceden a la aplicación y visualizan sus entregas del día.<br> - Verifican rutas y condiciones del vehículo. | - Toman fotos como evidencia de entrega.<br> - Registran kilometraje y observaciones desde la app. | - Reportan fallas o incidencias con solo unos clics.<br> - Solicitan revisión técnica desde el sistema. |
| **Thinking**               | - ¿Todas mis entregas están claras?<br> - ¿Está mi unidad en buenas condiciones para operar? | - ¿Las fotos están bien tomadas?<br> - ¿El cliente firmó correctamente? | - ¿Esta falla necesita reparación urgente?<br> - ¿La app notificó correctamente al gestor? |
| **Feeling**                | - Preparado para iniciar el día.<br> - Tranquilo con la ayuda de la app. | - Responsable y comprometido con el registro correcto. | - Aliviado por poder reportar problemas fácilmente.<br> - Apoyado por el sistema ante emergencias. |

## 3.2 User Stories
### Epics

| Epics ID | Título                           | Descripción                                                                                     |
|----------|----------------------------------|-------------------------------------------------------------------------------------------------|
| EP01     | Gestión de flota                | Como gestor quiero tener control total de las unidades de transporte, rutas y mantenimientos. |
| EP02     | Gestión de entregas             | Como conductor quiero registrar y visualizar mis entregas para tener claridad en mis tareas.  |
| EP03     | Gestión de incidencias          | Como conductor o gestor quiero reportar y visualizar incidencias para actuar rápidamente.     |
| EP04     | Gestión de mantenimiento        | Como gestor quiero planificar y llevar control de los mantenimientos de cada vehículo.         |
| EP05     | Gestión de indicadores          | Como gestor quiero ver reportes e indicadores automáticos para evaluar el desempeño diario.    |
| EP-LP    | Sitio web estático              | Como visitante quiero conocer los servicios y características de la plataforma para decidir si contratar.|
| EP-API   | API RESTful                     | Como desarrollador quiero acceder a los servicios mediante endpoints para integrarlos con otras aplicaciones. |
### User Stories 
<table>
    <thead>
        <tr>
            <th>Epic/Story ID</th>
            <th>Título</th>
            <th>Descripción</th>
            <th>Criterios de Aceptación</th>
            <th>Relacionada con (Epic ID)</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>US-01</td>
            <td>Visualizar rutas asignadas</td>
            <td>Como gestor, quiero ver las rutas asignadas a cada unidad, para hacer seguimiento efectivo.</td>
            <td>
                Escenario 01: Visualización de rutas asignadas<br>
                Dado que el gestor accede al panel de unidades<br>
                Cuando selecciona una unidad específica<br>
                Entonces visualiza la ruta asignada con detalles de horarios y destinos.
            </td>
            <td>EP01</td>
        </tr>
        <tr>
            <td>US-02</td>
            <td>Asignar unidades a rutas</td>
            <td>Como gestor, quiero asignar unidades de transporte a rutas específicas, para controlar la operación.</td>
            <td>
                Escenario 01: Asignación de unidades a rutas<br>
                Dado que el gestor ha ingresado a la sección de asignaciones<br>
                Cuando selecciona una ruta y una unidad disponible<br>
                Entonces el sistema guarda la asignación y muestra confirmación.
            </td>
            <td>EP01</td>
        </tr>
        <tr>
            <td>US-03</td>
            <td>Registrar disponibilidad de unidad</td>
            <td>Como gestor, quiero marcar una unidad como disponible o en mantenimiento, para gestionar eficientemente.</td>
            <td>
                Escenario 01: Actualización de estado de unidad<br>
                Dado que el gestor selecciona una unidad en el panel<br>
                Cuando cambia su estado a "disponible" o "en mantenimiento"<br>
                Entonces el nuevo estado se refleja en el sistema.
            </td>
            <td>EP01</td>
        </tr>
        <tr>
            <td>US-04</td>
            <td>Visualizar historial de movimientos</td>
            <td>Como gestor, quiero ver el historial de movimientos de una unidad, para rastrear sus actividades.</td>
            <td>
                Escenario 01: Consulta del historial de una unidad<br>
                Dado que el gestor accede al detalle de una unidad<br>
                Cuando entra a "historial de movimientos"<br>
                Entonces se muestra una tabla con fechas y tipos de movimiento.
            </td>
            <td>EP01</td>
        </tr>
        <tr>
            <td>US-05</td>
            <td>Consultar entregas pendientes</td>
            <td>Como conductor, quiero ver las entregas asignadas del día, para planificar mi ruta.</td>
            <td>
                Escenario 01: Lista de entregas pendientes<br>
                Dado que el conductor inicia sesión<br>
                Cuando accede a su panel principal<br>
                Entonces visualiza las entregas asignadas con hora, cliente y dirección.
            </td>
            <td>EP02</td>
        </tr>
        <tr>
            <td>US-06</td>
            <td>Registrar entrega con evidencia</td>
            <td>Como conductor, quiero registrar entregas con foto y firma, para validar su cumplimiento.</td>
            <td>
                Escenario 01: Registro de entrega<br>
                Dado que el conductor finaliza una entrega<br>
                Cuando adjunta la foto y solicita la firma del cliente<br>
                Entonces el sistema guarda la evidencia con fecha, hora y ubicación.
            </td>
            <td>EP02</td>
        </tr>
        <tr>
            <td>US-07</td>
            <td>Visualizar entregas completadas</td>
            <td>Como conductor, quiero ver un historial de entregas completadas, para llevar control de mis actividades.</td>
            <td>
                Escenario 01: Consulta de entregas completadas<br>
                Dado que el conductor accede a "historial de entregas"<br>
                Cuando filtra por fecha<br>
                Entonces se muestra lista con información relevante.
            </td>
            <td>EP02</td>
        </tr>
        <tr>
            <td>US-08</td>
            <td>Confirmar inicio de ruta</td>
            <td>Como conductor, quiero confirmar el inicio de mi ruta, para registrar la hora de salida.</td>
            <td>
                Escenario 01: Inicio de ruta<br>
                Dado que el conductor tiene entregas asignadas<br>
                Cuando presiona el botón "Iniciar ruta"<br>
                Entonces se registra la hora de inicio en el sistema.
            </td>
            <td>EP02</td>
        </tr>
        <tr>
            <td>US-09</td>
            <td>Reportar incidente durante entrega</td>
            <td>Como conductor, quiero reportar un incidente, para alertar al gestor y agilizar la solución.</td>
            <td>
                Escenario 01: Reporte de incidente<br>
                Dado que el conductor encuentra un problema durante la entrega<br>
                Cuando selecciona "reportar incidente" y adjunta evidencia<br>
                Entonces el sistema notifica al gestor.
            </td>
            <td>EP03</td>
        </tr>
        <tr>
            <td>US-10</td>
            <td>Visualizar estado de incidencias</td>
            <td>Como gestor, quiero ver un listado de incidencias activas, para tomar acción rápidamente.</td>
            <td>
                Escenario 01: Consulta de incidencias<br>
                Dado que hay incidencias registradas<br>
                Cuando accede al panel de incidencias<br>
                Entonces se muestran con unidad, fecha y gravedad.
            </td>
            <td>EP03</td>
        </tr>
        <tr>
            <td>US-11</td>
            <td>Filtrar incidencias por gravedad</td>
            <td>Como gestor, quiero filtrar las incidencias según su gravedad, para priorizar las más urgentes.</td>
            <td>
                Escenario 01: Filtro por gravedad<br>
                Dado que existen múltiples incidencias<br>
                Cuando selecciona el filtro "Alta", "Media" o "Baja"<br>
                Entonces solo se muestran las incidencias del tipo seleccionado.
            </td>
            <td>EP03</td>
        </tr>
        <tr>
            <td>US-12</td>
            <td>Visualizar historial de incidencias</td>
            <td>Como gestor, quiero revisar el historial de incidencias pasadas, para tomar decisiones preventivas.</td>
            <td>
                Escenario 01: Consulta de historial<br>
                Dado que el gestor accede a la sección histórica<br>
                Cuando filtra por fechas<br>
                Entonces se muestra una tabla con detalles y estado de resolución.
            </td>
            <td>EP03</td>
        </tr>
        <tr>
            <td>US-13</td>
            <td>Programar mantenimiento preventivo</td>
            <td>Como gestor, quiero programar mantenimientos regulares, para evitar fallas inesperadas.</td>
            <td>
                Escenario 01: Programación de mantenimiento<br>
                Dado que el gestor selecciona una unidad<br>
                Cuando asigna una frecuencia (semanal, mensual)<br>
                Entonces se genera una programación en el calendario.
            </td>
            <td>EP04</td>
        </tr>
        <tr>
            <td>US-14</td>
            <td>Registrar mantenimiento realizado</td>
            <td>Como técnico, quiero registrar el mantenimiento con detalles, para dejar constancia de lo realizado.</td>
            <td>
                Escenario 01: Registro de mantenimiento<br>
                Dado que el técnico completó el mantenimiento<br>
                Cuando llena el formulario con partes revisadas<br>
                Entonces se guarda en el historial de la unidad.
            </td>
            <td>EP04</td>
        </tr>
        <tr>
            <td>US-15</td>
            <td>Ver próximas fechas de mantenimiento</td>
            <td>Como gestor, quiero ver en un calendario las fechas de mantenimiento, para no olvidar los programados.</td>
            <td>
                Escenario 01: Calendario de mantenimientos<br>
                Dado que hay mantenimientos programados<br>
                Cuando accede al calendario<br>
                Entonces se visualizan las fechas por unidad.
            </td>
            <td>EP04</td>
        </tr>
        <tr>
            <td>US-16</td>
            <td>Notificación de mantenimiento pendiente</td>
            <td>Como gestor, quiero recibir alertas de mantenimiento próximo, para actuar con anticipación.</td>
            <td>
                Escenario 01: Alerta de mantenimiento<br>
                Dado que se acerca la fecha programada<br>
                Cuando faltan 3 días<br>
                Entonces el sistema envía una notificación automática.
            </td>
            <td>EP04</td>
        </tr>
        <tr>
            <td>US-17</td>
            <td>Ver reporte semanal de entregas</td>
            <td>Como gestor, quiero ver un reporte semanal por conductor, para evaluar su rendimiento.</td>
            <td>
                Escenario 01: Reporte semanal<br>
                Dado que la semana ha finalizado<br>
                Cuando entra al módulo de reportes<br>
                Entonces ve cantidad de entregas y cumplimiento por conductor.
            </td>
            <td>EP05</td>
        </tr>
        <tr>
            <td>US-18</td>
            <td>Ver eficiencia por unidad</td>
            <td>Como gestor, quiero ver rendimiento por unidad, para tomar decisiones sobre el uso de la flota.</td>
            <td>
                Escenario 01: Eficiencia por unidad<br>
                Dado que se registran entregas y kilometraje<br>
                Cuando accede al análisis de flota<br>
                Entonces ve el rendimiento individual por unidad.
            </td>
            <td>EP05</td>
        </tr>
        <tr>
            <td>US-19</td>
            <td>Comparar rendimiento entre conductores</td>
            <td>Como gestor, quiero comparar eficiencia entre conductores, para fomentar buenas prácticas.</td>
            <td>
                Escenario 01: Ranking de conductores<br>
                Dado que hay varios registros de entregas<br>
                Cuando selecciona periodo de comparación<br>
                Entonces se muestra ranking con métricas clave.
            </td>
            <td>EP05</td>
        </tr>
        <tr>
            <td>US-20</td>
            <td>Visualizar alertas críticas en dashboard</td>
            <td>Como gestor, quiero ver alertas prioritarias en el dashboard, para atender eventos críticos de inmediato.</td>
            <td>
                Escenario 01: Visualización de alertas<br>
                Dado que existen eventos críticos<br>
                Cuando accede al dashboard<br>
                Entonces se muestran alertas con prioridad destacada.
            </td>
            <td>EP05</td>
        </tr>
        <tr>
            <td>US-21</td>
            <td>Visualizar información de servicio</td>
            <td>Como visitante, quiero conocer los servicios de gestión de flotas ofrecidos, para evaluar si satisface mis necesidades.</td>
            <td>
                Escenario 01: Acceso a información de servicios<br>
                Dado que un visitante accede al landing page<br>
                Cuando desplaza hacia la sección de servicios<br>
                Entonces visualiza descripciones claras e ilustrativas de cada servicio ofrecido.<br><br>
                Escenario 02: Visualización de características<br>
                Dado que el visitante está en la sección de servicios<br>
                Cuando hace clic en un servicio específico<br>
                Entonces se despliega información detallada con sus características.
            </td>
            <td>EP-LP</td>
        </tr>
        <tr>
            <td>US-22</td>
            <td>Registrar solicitud de demo</td>
            <td>Como visitante, quiero solicitar una demostración del sistema, para conocer la plataforma antes de contratar.</td>
            <td>
                Escenario 01: Registro exitoso<br>
                Dado que el visitante completa el formulario de solicitud de demo<br>
                Cuando envía el formulario con datos válidos<br>
                Entonces recibe una confirmación y es notificado del próximo paso.<br><br>
                Escenario 02: Error en formulario<br>
                Dado que el visitante completa el formulario con datos inválidos<br>
                Cuando intenta enviar el formulario<br>
                Entonces se muestran mensajes de error específicos.
            </td>
            <td>EP-LP</td>
        </tr>
        <tr>
            <td>US-23</td>
            <td>Visualizar planes y precios</td>
            <td>Como visitante, quiero conocer los diferentes planes disponibles y sus precios, para seleccionar el más adecuado a mis necesidades.</td>
            <td>
                Escenario 01: Comparación de planes<br>
                Dado que el visitante navega a la sección de precios<br>
                Cuando visualiza la tabla comparativa<br>
                Entonces puede ver claramente las características y precios de cada plan.<br><br>
                Escenario 02: Selección de plan<br>
                Dado que el visitante está revisando los planes<br>
                Cuando hace clic en "Seleccionar Plan"<br>
                Entonces es redirigido al formulario de registro con el plan preseleccionado.
            </td>
            <td>EP-LP</td>
        </tr>
        <tr>
            <td>US-24</td>
            <td>Contactar con soporte</td>
            <td>Como visitante, quiero contactar con el equipo de soporte, para resolver dudas sobre el servicio.</td>
            <td>
                Escenario 01: Envío de mensaje<br>
                Dado que el visitante completa el formulario de contacto<br>
                Cuando envía un mensaje<br>
                Entonces recibe confirmación de recepción con tiempo estimado de respuesta.<br><br>
                Escenario 02: Visualización de preguntas frecuentes<br>
                Dado que el visitante accede a la sección de contacto<br>
                Cuando revisa la sección de preguntas frecuentes<br>
                Entonces puede encontrar respuestas a consultas comunes.
            </td>
            <td>EP-LP</td>
        </tr>
        <tr>
            <td>US-25</td>
            <td>Visualizar casos de éxito</td>
            <td>Como visitante, quiero ver testimonios y casos de éxito, para evaluar la efectividad del sistema en casos reales.</td>
            <td>
                Escenario 01: Exploración de testimonios<br>
                Dado que el visitante accede a la sección de casos de éxito<br>
                Cuando selecciona un caso específico<br>
                Entonces ve detalles completos con métricas y resultados.<br><br>
                Escenario 02: Filtrado por industria<br>
                Dado que el visitante está en la sección de casos de éxito<br>
                Cuando filtra por tipo de industria<br>
                Entonces se muestran solo los casos relacionados con esa industria.
            </td>
            <td>EP-LP</td>
        </tr>
        <tr>
            <td>TS-01</td>
            <td>Autenticación API</td>
            <td>Como desarrollador, quiero implementar un sistema de autenticación JWT, para asegurar el acceso a los endpoints de la API.</td>
            <td>
                Escenario 01: Autenticación exitosa<br>
                Dado que se envían credenciales válidas al endpoint de login<br>
                Cuando la API procesa la solicitud<br>
                Entonces devuelve un token JWT con código 200.<br><br>
                Escenario 02: Autenticación fallida<br>
                Dado que se envían credenciales inválidas<br>
                Cuando la API procesa la solicitud<br>
                Entonces devuelve un mensaje de error con código 401.<br><br>
                Escenario 03: Token expirado<br>
                Dado que un token ha expirado<br>
                Cuando se realiza una petición autenticada con ese token<br>
                Entonces la API responde con código 401 y mensaje de expiración.
            </td>
            <td>EP-API</td>
        </tr>
        <tr>
            <td>TS-02</td>
            <td>Endpoints de unidades</td>
            <td>Como desarrollador, quiero implementar endpoints CRUD para unidades de transporte, para gestionar la flota desde aplicaciones externas.</td>
            <td>
                Escenario 01: Obtención de unidades<br>
                Dado que se realiza una petición GET autenticada a /api/units<br>
                Cuando la API procesa la solicitud<br>
                Entonces devuelve un array de unidades con código 200.<br><br>
                Escenario 02: Creación de unidad<br>
                Dado que se envía una petición POST a /api/units con datos válidos<br>
                Cuando la API procesa la solicitud<br>
                Entonces crea la unidad y devuelve código 201.<br><br>
                Escenario 03: Datos inválidos<br>
                Dado que se envía una petición POST con datos incorrectos<br>
                Cuando la API valida los datos<br>
                Entonces devuelve un mensaje de error con código 400.
            </td>
            <td>EP-API</td>
        </tr>
        <tr>
            <td>TS-03</td>
            <td>Endpoints de entregas</td>
            <td>Como desarrollador, quiero implementar endpoints para gestionar entregas, para permitir su registro y consulta desde aplicaciones móviles.</td>
            <td>
                Escenario 01: Registro de entrega<br>
                Dado que se envía una petición POST a /api/deliveries con datos válidos<br>
                Cuando la API procesa la solicitud<br>
                Entonces crea el registro y devuelve el ID con código 201.<br><br>
                Escenario 02: Listado de entregas por conductor<br>
                Dado que se realiza una petición GET a /api/deliveries con filtro de conductor<br>
                Cuando la API procesa la solicitud<br>
                Entonces devuelve solo las entregas del conductor especificado.<br><br>
                Escenario 03: Actualización de estado<br>
                Dado que se envía una petición PATCH a /api/deliveries/{id}/status<br>
                Cuando la API actualiza el estado<br>
                Entonces devuelve la entrega actualizada con código 200.
            </td>
            <td>EP-API</td>
        </tr>
        <tr>
            <td>TS-04</td>
            <td>Endpoints de incidencias</td>
            <td>Como desarrollador, quiero implementar endpoints para gestionar incidencias, para facilitar su reporte desde diversas plataformas.</td>
            <td>
                Escenario 01: Reporte de incidencia<br>
                Dado que se envía una petición POST a /api/incidents con datos válidos<br>
                Cuando la API procesa la solicitud<br>
                Entonces registra la incidencia y notifica a los usuarios correspondientes.<br><br>
                Escenario 02: Listado de incidencias activas<br>
                Dado que se realiza una petición GET a /api/incidents con filtro "active=true"<br>
                Cuando la API procesa la solicitud<br>
                Entonces devuelve solo las incidencias no resueltas.<br><br>
                Escenario 03: Resolución de incidencia<br>
                Dado que se envía una petición PATCH a /api/incidents/{id}/resolve<br>
                Cuando la API actualiza el estado<br>
                Entonces marca la incidencia como resuelta y notifica al reportante.
            </td>
            <td>EP-API</td>
        </tr>
        <tr>
            <td>TS-05</td>
            <td>Endpoints de estadísticas</td>
            <td>Como desarrollador, quiero implementar endpoints para obtener métricas y estadísticas, para facilitar la visualización de reportes.</td>
            <td>
                Escenario 01: Obtención de estadísticas<br>
                Dado que se realiza una petición GET a /api/stats con parámetros de filtrado<br>
                Cuando la API procesa la solicitud<br>
                Entonces devuelve los datos agregados según los filtros especificados.<br><br>
                Escenario 02: Exportación de reportes<br>
                Dado que se realiza una petición GET a /api/reports/export con formato especificado<br>
                Cuando la API genera el reporte<br>
                Entonces devuelve un archivo en el formato solicitado (CSV, PDF).<br><br>
                Escenario 03: Estadísticas en tiempo real<br>
                Dado que se realiza una petición GET a /api/stats/realtime<br>
                Cuando la API procesa la solicitud<br>
                Entonces devuelve métricas actualizadas en tiempo real.
            </td>
            <td>EP-API</td>
        </tr>
    </tbody>
</table>

### Gestor de flota
![Gestor de flota](https://hackmd.io/_uploads/BJsJjr_Jge.png)


### Conductores de transporte

![conductores](https://hackmd.io/_uploads/BkrTcHu1le.png)

## 3.4 Product Backlog

<table>
    <thead>
        <tr>
            <th># Orden</th>
            <th>User Story ID</th>
            <th>Título</th>
            <th>Descripción</th>
            <th>Story Points (1/2/3/5/8)</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>1</td>
            <td>US-05</td>
            <td>Consultar entregas pendientes</td>
            <td>Como conductor, quiero ver las entregas asignadas del día, para planificar mi ruta.</td>
            <td>8</td>
        </tr>
        <tr>
            <td>2</td>
            <td>US-01</td>
            <td>Visualizar rutas asignadas</td>
            <td>Como gestor, quiero ver las rutas asignadas a cada unidad, para hacer seguimiento efectivo.</td>
            <td>8</td>
        </tr>
        <tr>
            <td>3</td>
            <td>US-09</td>
            <td>Reportar incidente durante entrega</td>
            <td>Como conductor, quiero reportar un incidente, para alertar al gestor y agilizar la solución.</td>
            <td>8</td>
        </tr>
        <tr>
            <td>4</td>
            <td>US-13</td>
            <td>Programar mantenimiento preventivo</td>
            <td>Como gestor, quiero programar mantenimientos regulares, para evitar fallas inesperadas.</td>
            <td>8</td>
        </tr>
        <tr>
            <td>5</td>
            <td>US-17</td>
            <td>Ver reporte semanal de entregas</td>
            <td>Como gestor, quiero ver un reporte semanal por conductor, para evaluar su rendimiento.</td>
            <td>5</td>
        </tr>
        <tr>
            <td>6</td>
            <td>US-03</td>
            <td>Registrar disponibilidad de unidad</td>
            <td>Como gestor, quiero marcar una unidad como disponible o en mantenimiento, para gestionar eficientemente.</td>
            <td>5</td>
        </tr>
        <tr>
            <td>7</td>
            <td>US-08</td>
            <td>Confirmar inicio de ruta</td>
            <td>Como conductor, quiero confirmar el inicio de mi ruta, para registrar la hora de salida.</td>
            <td>5</td>
        </tr>
        <tr>
            <td>8</td>
            <td>US-12</td>
            <td>Visualizar historial de incidencias</td>
            <td>Como gestor, quiero revisar el historial de incidencias pasadas, para tomar decisiones preventivas.</td>
            <td>5</td>
        </tr>
        <tr>
            <td>9</td>
            <td>US-04</td>
            <td>Visualizar historial de movimientos</td>
            <td>Como gestor, quiero ver el historial de movimientos de una unidad, para rastrear sus actividades.</td>
            <td>5</td>
        </tr>
        <tr>
            <td>10</td>
            <td>US-16</td>
            <td>Notificación de mantenimiento pendiente</td>
            <td>Como gestor, quiero recibir alertas de mantenimiento próximo, para actuar con anticipación.</td>
            <td>5</td>
        </tr>
        <tr>
            <td>11</td>
            <td>US-07</td>
            <td>Visualizar entregas completadas</td>
            <td>Como conductor, quiero ver un historial de entregas completadas, para llevar control de mis actividades.</td>
            <td>5</td>
        </tr>
        <tr>
            <td>12</td>
            <td>US-10</td>
            <td>Visualizar estado de incidencias</td>
            <td>Como gestor, quiero ver un listado de incidencias activas, para tomar acción rápidamente.</td>
            <td>5</td>
        </tr>
        <tr>
            <td>13</td>
            <td>US-14</td>
            <td>Registrar mantenimiento realizado</td>
            <td>Como técnico, quiero registrar el mantenimiento con detalles, para dejar constancia de lo realizado.</td>
            <td>3</td>
        </tr>
        <tr>
            <td>14</td>
            <td>US-19</td>
            <td>Comparar rendimiento entre conductores</td>
            <td>Como gestor, quiero comparar eficiencia entre conductores, para fomentar buenas prácticas.</td>
            <td>3</td>
        </tr>
        <tr>
            <td>15</td>
            <td>US-06</td>
            <td>Registrar entrega con evidencia</td>
            <td>Como conductor, quiero registrar entregas con foto y firma, para validar su cumplimiento.</td>
            <td>3</td>
        </tr>
        <tr>
            <td>16</td>
            <td>US-11</td>
            <td>Filtrar incidencias por gravedad</td>
            <td>Como gestor, quiero filtrar las incidencias según su gravedad, para priorizar las más urgentes.</td>
            <td>3</td>
        </tr>
        <tr>
            <td>17</td>
            <td>US-02</td>
            <td>Asignar unidades a rutas</td>
            <td>Como gestor, quiero asignar unidades de transporte a rutas específicas, para controlar la operación.</td>
            <td>2</td>
        </tr>
        <tr>
            <td>18</td>
            <td>US-18</td>
            <td>Ver eficiencia por unidad</td>
            <td>Como gestor, quiero ver rendimiento por unidad, para tomar decisiones sobre el uso de la flota.</td>
            <td>2</td>
        </tr>
        <tr>
            <td>19</td>
            <td>US-15</td>
            <td>Ver próximas fechas de mantenimiento</td>
            <td>Como gestor, quiero ver en un calendario las fechas de mantenimiento, para no olvidar los programados.</td>
            <td>2</td>
        </tr>
        <tr>
            <td>20</td>
            <td>US-20</td>
            <td>Visualizar alertas críticas en dashboard</td>
            <td>Como gestor, quiero ver alertas prioritarias en el dashboard, para atender eventos críticos de inmediato.</td>
            <td>1</td>
        </tr>
        <tr>
            <td>21</td>
            <td>US-21</td>
            <td>Visualizar información de servicio</td>
            <td>Como visitante, quiero conocer los servicios de gestión de flotas ofrecidos, para evaluar si satisface mis necesidades.</td>
            <td>3</td>
        </tr>
        <tr>
            <td>22</td>
            <td>US-22</td>
            <td>Registrar solicitud de demo</td>
            <td>Como visitante, quiero solicitar una demostración del sistema, para conocer la plataforma antes de contratar.</td>
            <td>5</td>
        </tr>
        <tr>
            <td>23</td>
            <td>US-23</td>
            <td>Visualizar planes y precios</td>
            <td>Como visitante, quiero conocer los diferentes planes disponibles y sus precios, para seleccionar el más adecuado a mis necesidades.</td>
            <td>3</td>
        </tr>
        <tr>
            <td>24</td>
            <td>US-24</td>
            <td>Contactar con soporte</td>
            <td>Como visitante, quiero contactar con el equipo de soporte, para resolver dudas sobre el servicio.</td>
            <td>2</td>
        </tr>
        <tr>
            <td>25</td>
            <td>US-25</td>
            <td>Visualizar casos de éxito</td>
            <td>Como visitante, quiero ver testimonios y casos de éxito, para evaluar la efectividad del sistema en casos reales.</td>
            <td>5</td>
        </tr>
        <tr>
            <td>26</td>
            <td>TS-01</td>
            <td>Autenticación API</td>
            <td>Como desarrollador, quiero implementar un sistema de autenticación JWT, para asegurar el acceso a los endpoints de la API.</td>
            <td>8</td>
        </tr>
        <tr>
            <td>27</td>
            <td>TS-02</td>
            <td>Endpoints de unidades</td>
            <td>Como desarrollador, quiero implementar endpoints CRUD para unidades de transporte, para gestionar la flota desde aplicaciones externas.</td>
            <td>5</td>
        </tr>
        <tr>
            <td>28</td>
            <td>TS-03</td>
            <td>Endpoints de entregas</td>
            <td>Como desarrollador, quiero implementar endpoints para gestionar entregas, para permitir su registro y consulta desde aplicaciones móviles.</td>
            <td>5</td>
        </tr>
        <tr>
            <td>29</td>
            <td>TS-04</td>
            <td>Endpoints de incidencias</td>
            <td>Como desarrollador, quiero implementar endpoints para gestionar incidencias, para facilitar su reporte desde diversas plataformas.</td>
            <td>5</td>
        </tr>
        <tr>
            <td>30</td>
            <td>TS-05</td>
            <td>Endpoints de estadísticas</td>
            <td>Como desarrollador, quiero implementar endpoints para obtener métricas y estadísticas, para facilitar la visualización de reportes.</td>
            <td>8</td>
        </tr>
    </tbody>
</table>
