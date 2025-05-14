# Capítulo V: Product Implementation, Validation & Deployment

## 5.1 Software Configuration Management
Aquí explicamos cómo organizamos, gestionamos y controlamos los cambios realizados durante el desarrollo de este proyecto.
### 5.1.1. Configuración del Entorno de Desarrollo de Software### 5.1.1. Software Development Environment Configuration.
**Gestión de Requisitos**
1. Trello: Herramienta ideal para organizar y supervisar el flujo de trabajo en proyectos ágiles. Nos permitirá visualizar y actualizar el estado de las tareas e historias de usuario durante cada sprint.  
   Enlace: https://trello.com/es

**Diseño UX/UI del Producto**

1. Figma: Plataforma utilizada para crear prototipos y diseños gráficos. En este proyecto, se empleará para diseñar las versiones de la aplicación tanto en navegadores de escritorio como móviles.  
   Enlace: https://www.figma.com/login
2. Lucidchart: Herramienta para crear diagramas de flujo. Será utilizada para diseñar wireflows, user-flows y el diagrama de clases de la aplicación.  
   Enlace: https://www.lucidchart.com/

**Software Development**
1. **WebStorm**: Un IDE destacado por su soporte integral para tecnologías web como JavaScript, HTML, CSS y frameworks como React y Angular. Ofrece herramientas avanzadas como refactorización, depuración, integración con Git y soporte para plugins, lo que lo hace ideal para el trabajo en equipo en diferentes sistemas operativos.

   [Más información](https://www.jetbrains.com/webstorm/)
   <br>
2. **HTML5**: Lenguaje de marcado utilizado para estructurar y presentar contenido en la web. Será clave en el desarrollo de la aplicación.

   [Más información](https://www.w3schools.com/html/html5_syntax.asp)   
   <br>
3. **CSS**: Lenguaje de estilos que define la apariencia y diseño de las páginas web, complementando el uso de HTML.

   [Más información](https://google.github.io/styleguide/htmlcssguide.html)
   <br>
   <br>
4. **JavaScript**: Lenguaje de programación orientado a objetos que se usará para desarrollar la interfaz de usuario de la aplicación.

   [Más información](https://developer.mozilla.org/es/docs/Web/JavaScript)
   <br>
   <br>

5. **Angular**: Framework de JavaScript basado en TypeScript que utilizamos para construir el front-end del proyecto "Cobox-Logistic". El código está disponible en nuestro repositorio.

   <br>

**Despliegue de Software**
1. **Git**: Herramienta de control de versiones que permite registrar y gestionar los cambios en el código. Es fundamental para mantener un historial de modificaciones y facilitar la corrección de errores. El equipo trabajará con Git desde la línea de comandos.

   [Más información](https://git-scm.com/)
   <br>
   <br>
**Documentación y Gestión del Proyecto**
2. **GitHub**: Plataforma en la nube donde se alojarán los repositorios del proyecto. Facilita la colaboración en tiempo real y la revisión de contribuciones del equipo, accesible desde cualquier navegador.

   [Más información](https://github.com/)

### 5.1.2. Source Code Management.
El proyecto adoptará las convenciones del modelo GitFlow para la gestión del control de versiones, utilizando GitHub como plataforma principal para alojar y organizar el código. GitFlow es un enfoque estructurado que facilita la colaboración en equipo y la gestión de múltiples versiones de software, asegurando que cada etapa de desarrollo esté debidamente aislada y controlada.

A continuación, se explicará en detalle cómo se implementará este flujo de trabajo, destacando la creación y gestión de ramas para las distintas fases de desarrollo. Además, se proporcionará un enlace al repositorio de GitHub, donde se podrá acceder al reporte del proyecto, la landing page y el avance del frontend de la aplicación, permitiendo un seguimiento claro del progreso y las actualizaciones del código.

**Repositorio de GitHub:**
- Enlace para acceder a la organización en github
- Enlace para acceder al repositorio de la landing page
- Enlace para acceder al repositorio del reporte final
- Enlace para acceder al repositorio del frontend

**Flujo de trabajo GitFlow**

El flujo de trabajo a ser implementado para el desarrollo del proyecto se basará en el modelo propuesto por Vincent Driessen en "A successful Git branching model".


**Estructura de branches (Ramas):**


1. **Master branch (Rama principal):** Esta rama servirá como la principal para la aplicación, albergando versiones estables y finales del desarrollo. Únicamente se aceptarán cambios que hayan sido previamente probados y verificados en las ramas de funcionalidad y, posteriormente, en la rama de desarrollo.

2. **Develop Branch (Rama de Desarrollo):** Esta rama facilita el trabajo colaborativo del equipo y organiza el desarrollo continuo. Aquí se integran las funcionalidades en proceso y se realizan pruebas antes de su fusión con la rama principal, asegurando que el código se mantenga funcional y estable.

3. **Feature branch (Ramas de funcionalidad):** Cada funcionalidad desarrollada por el equipo, o que se aparte del enfoque actual del desarrollo, tendrá su propia rama. Una vez que una funcionalidad esté completamente implementada, se fusionará con la rama de desarrollo del proyecto. Las convenciones para nombrar las ramas de funcionalidad seguirán un patrón descriptivo y único, por ejemplo, "feature".

### 5.1.3. Source Code Style Guide & Conventions.
**HTML:** Algunas de las prácticas que deben de seguirse para alcanzar un código coherente, sostenible y ordenado son las
siguientes:
1. Cerrar todos los elementos HTML: Por ejemplo, ```<p>Esto es un párrafo.</p>```
2. Siempre declarar el tipo de documento en la primera línea del documento, para
   HTML es "<!DOCTYPE html>”.
3. Escribir en una línea los comentarios cortos.
4. Utilizar comillas en caso de que los atributos contengan espacios entre sí.
5. Procurar especificar el texto alt y las dimensiones width y height de las imágenes, ya que de esta manera se facilitará la
   disponibilidad del contenido. Por ejemplo:   ```<img src="abc.img" alt="image name"  
   style="width:128px;height:128px">```
6. Se nos recomienda no usar el espacio al momento de utilizar los signos porque
   es más fácil de leerlo de esta forma.  
   <br>
   HTML: (https://www.w3schools.com/html/html5_syntax.asp)

**CSS:** Entre las prácticas empleadas se menciona:

1. Se nos recomienda tener una sangría por 2 espacios a la vez, no debemos
   utilizar tabulaciones ni mezclarlas tabulaciones con espacios para la sangría.
2. Todo el código debe estar en minúscula.
3. Eliminar los espacios en blanco.
4. Usar comentarios para explicar el código.
5. Utilizar nombres de clase significativos o genéricos, nombres que reflejen el
   propósito de su elemento.  
   <br>

   CSS: (https://google.github.io/styleguide/htmlcssguide.html)



### 5.1.4. Software Deployment Configuration.
### Landing page deployment:
Para desplegar la landing page es necesario contar con una serie de requisitos, entre ellos, es necesario contar con una cuenta personal, una organización y un repositorio al cual cargar los documentos. A partir de lo anterior, es posible comenzar el despliegue de la landing page. A continuación se enuncian los pasos a seguir:

1. Asegurarse de que los archivos estén en la raíz (root) del repositorio.
2. Asegurarse de que los archivos sigan las nomenclaturas: "index.html" para la landing page, "styles.css" para los estilos, "main.js" para los scripts, y una carpeta llamada "assets/images" para las imágenes.
3. Cargar los archivos al repositorio mediante un commit.
4. Dirigirse a Settings > Pages y seleccionar el branch correspondiente, en este caso el "main".
5. Especificar la carpeta raíz (root) como la fuente de la página.
6. Esperar a que GitHub realice las comprobaciones necesarias. Una vez culminado el proceso, se obtendrá un enlace que llevará a la landing page desplegada.

## GithubPages

Verificamos la URL generada por GitHub Pages para asegurarnos de que la landing page se haya desplegado correctamente. Una vez confirmada, la página estará disponible públicamente a través de este enlace y podrá ser accedida por cualquier usuario.

De esta manera, la landing page quedará publicada utilizando GitHub Pages, siendo accesible para todos aquellos que cuenten con el enlace correspondiente.

### 5.2. Landing Page, Services & Applications Implementation.


## 5.2. Landing Page, Services & Applications Implementation
En esta sección se explicará y evidenciará el proceso de implementación, pruebas,
documentación y despliegue del Landing Page.

### 5.2.1. Sprint 1

### 5.2.1.1. Sprint Planning 1

Para este primer sprint nos enfocaremos en los tasks para la
elaboración de la Landing Page. Nos dividiremos entre nosotros cada
una de las tareas identificadas para el sprint.
<table>
<tr>
    <th colspan="5">Sprint 1</th>
    <th colspan="9">Sprint 1</th>
  </tr>
      <tr>
    <td colspan="13">Sprint Planning Background</td>
  </tr>
  <tr>
    <td colspan="5">Date</td>
    <td colspan="8">2025-04-24</td>
</tr>
  <tr>
    <td colspan="5">Time</td>
    <td colspan="8">9:00PM</td>
  </tr>
  <tr>
    <td colspan="5">Location</td>
    <td colspan="8">Via Meet</td>
<tr>
    <td colspan="5">Prepared By</td>
    <td colspan="8">Merly Salon Puerta</td>
</tr>
<tr>
    <td colspan="5">Attendees (to planning meeting)</td>
    <td colspan="8">Stephano Espinoza, Joseph Rodriguez, Raul Sanchez Cruz, Merly Salon Puerta, Angel Berrospi Marin</td>
</tr>
<tr>
    <td colspan="5">Sprint  1 Review Summary</td>
    <td colspan="8">En esta primera sección se planteó el desarrollo y mejora de la Landing page antes de subirse a un repositorio.</td>
</tr>
<tr>
    <td colspan="5">Sprint 1 Retrospective Summary</td>
    <td colspan="8">En esta sesión todos los participantes, opinaron, mejoraron sus habilidades pero finalmente uno se encargó de la integración de los idiomas y finalmente decidieron subir el landing mejor en el último día</td>
</tr>
<tr>
    <td colspan="13">Sprint Goal & User Stories</td>
</tr>
<tr>
    <td colspan="5">Sprint 1 Goal</td>
    <td colspan="8"> La meta de este Sprint 1 es la correcta planificación del desarrollo de la documentación y que nuestra Landing Page tenga una correcta funcionalidad para el usuario  

</td>
</tr>
<tr>
    <td colspan="5">Sprint 1 Velocity</td>
    <td colspan="8">velocity 7</td> 
</tr>
<tr>
    <td colspan="5">Sum of Story Points</td>
    <td colspan="8">8 story points</td>
</tr>
</table>

### 5.2.1.2. Aspect Leaders and Collaborators
En esta sección el equipo que incluye la elaboración de un artefacto Leadership-andCollaboration Matrix (LACX), que indique por cada aspecto dentro del alcance del Sprint, quién es el líder y quién o quiénes son colaboradores en dicho aspecto, con el fin de brindar mayor claridad y efectividad en la comunicación al interior del equipo.

![image](https://github.com/user-attachments/assets/40a67922-811d-4496-b285-115ceff67ca5)


### 5.2.1.3. Sprint Backlog 1

<table>
<tr>
    <th colspan="3">Sprint #</th>
    <th colspan="10">Sprint 1</th>
</tr>
<tr>
    <td colspan="3">User Story</td>
    <td colspan="10">Work-Item/Task</td>
</tr>
<tr>
    <td colspan="1">Id</td>
    <td colspan="2">Title</td>
    <td colspan="1">Id</td>
    <td colspan="2">Title</td>
    <td colspan="3">Description</td>
    <td colspan="1">Estimation</td>
    <td colspan="2">Assigned To</td>
    <td colspan="1">Status (To-do / InProcess / To-Review / Done)</td>
</tr>
<tr>
    <td colspan="1">US01</td>
    <td colspan="2">Encontrar información del propósito de la aplicación</td>
    <td colspan="1">UT01</td>
    <td colspan="2">Crear sección "Acerca de nosotros"</td>
    <td colspan="3">Estructurar y agregar información sobre el propósito de la aplicación.</td>
    <td colspan="1">2</td>
    <td colspan="2">Stephano Espinoza</td>
    <td colspan="1">Done</td>
</tr>
<tr>
    <td colspan="1">US02</td>
    <td colspan="2">Encontrar información del propósito de la aplicación</td>
    <td colspan="1">UT02</td>
    <td colspan="2">Crear sección "Acerca de nosotros"</td>
    <td colspan="3">Estructurar y agregar información sobre el propósito de la aplicación.</td>
    <td colspan="1">2</td>
    <td colspan="2">Joseph Rodriguez</td>
    <td colspan="1">Done</td>
</tr>
<tr>
    <td colspan="1">US02</td>
    <td colspan="2">Encontrar información del propósito de la aplicación</td>
    <td colspan="1">UT03</td>
    <td colspan="2">Implementar estilos en la landing page</td>
    <td colspan="3">Implementar los estilos y diseño de la landing page.</td>
    <td colspan="1">3</td>
    <td colspan="2">Angel Berrospi</td>
    <td colspan="1">Done</td>
</tr>
<tr>
    <td colspan="1">US03</td>
    <td colspan="2">Encontrar información del propósito de la aplicación</td>
    <td colspan="1">UT04</td>
    <td colspan="2">Implementar funcionalidad en la landing page</td>
    <td colspan="3">Implementar la funcionalidad de la landing page</td>
    <td colspan="1">4</td>
    <td colspan="2">Raul Sanchez</td>
    <td colspan="1">Done</td>
</tr>
<tr>
    <td colspan="1">US04</td>
    <td colspan="2">Visualización de imágenes y gráficos relevantes</td>
    <td colspan="1">UT05</td>
    <td colspan="2">Añadir imágenes de alta calidad</td>
    <td colspan="3">Incorporar nuevas imágenes de alta calidad que sean relevantes para el contenido.</td>
    <td colspan="1">2</td>
    <td colspan="2">Merly Salon</td>
    <td colspan="1">Done</td>
</tr>
</table>

### 5.2.1.4. Development Evidence for Sprint Review
![Implementation2](https://github.com/user-attachments/assets/9f82b837-35dc-40bd-8b1a-f1f0d2fd23f0)

### 5.2.1.5. Execution Evidence for Sprint Review
Esta sección se centrará en la ejecución de la aplicación durante el sprint. Se describirá cómo los usuarios han interactuado con la plataforma, incluyendo su experiencia de usuario y cualquier problema o retroalimentación que hayan proporcionado. Además, se destacarán las mejoras en la usabilidad y la interfaz de usuario.
![Implementation5](https://github.com/user-attachments/assets/877cb95a-b75b-45f3-b18f-77e70e0f8a01)


### 5.2.1.6. Services Documentation Evidence for Sprint Review
Aquí se presentará la documentación relacionada con los servicios de atención médica ofrecidos a través de la plataforma. Esto puede incluir perfiles de profesionales de salud, detalles sobre las tarifas de consulta y paquetes disponibles, así como información sobre las referencias de pacientes anteriores.
![Implementation6](https://github.com/user-attachments/assets/fd6b280d-2fff-4203-91c2-66640a471205)


### 5.2.1.7. Software Deployment Evidence for Sprint Review
En esta sección, se describirá el proceso de implementación del software en un entorno de producción o pruebas. Se destacarán los hitos clave alcanzados en términos de despliegue y disponibilidad de la plataforma para los usuarios finales.
![SprintBacklog1](https://github.com/user-attachments/assets/a30b2936-1e7d-4f61-8efd-93f1ea32e30a)


### 5.2.1.8. Team Collaboration Insights during Sprint
Se proporcionarán detalles sobre la colaboración y la comunicación dentro del equipo de desarrollo durante el sprint. Esto incluirá la coordinación de esfuerzos entre los miembros del equipo, la resolución de problemas y la gestión de tareas. También se destacarán las lecciones aprendidas y las oportunidades de mejora en la colaboración.
![f87e7986-5421-4c6c-bb39-8f4bb6fc00a7](https://github.com/user-attachments/assets/fc7a14bc-12c5-4e3a-abde-87ecd5bf8997)

### 5.2.2. Sprint 2

### 5.2.2.1. Sprint Planning 2

Para este primer sprint nos enfocaremos en los tasks para la
elaboración de la Landing Page. Nos dividiremos entre nosotros cada
una de las tareas identificadas para el sprint.
<table>
<tr>
    <th colspan="5">Sprint 2</th>
    <th colspan="9">Sprint 2</th>
  </tr>
      <tr>
    <td colspan="13">Sprint Planning Background</td>
  </tr>
  <tr>
    <td colspan="5">Date</td>
    <td colspan="8">2025-05-14</td>
</tr>
  <tr>
    <td colspan="5">Time</td>
    <td colspan="8">3:00PM</td>
  </tr>
  <tr>
    <td colspan="5">Location</td>
    <td colspan="8">Via Meet</td>
<tr>
    <td colspan="5">Prepared By</td>
    <td colspan="8">Angel Guillermo Berrospi</td>
</tr>
<tr>
    <td colspan="5">Attendees (to planning meeting)</td>
    <td colspan="8">Stephano Espinoza, Joseph Rodriguez, Raul Sanchez Cruz, Merly Salon Puerta, Angel Berrospi Marin</td>
</tr>
<tr>
    <td colspan="5">Sprint  2 Review Summary</td>
    <td colspan="8">En esta segunda sección se planteó el mejormiento del desarrollo y estructura de la Landing page antes de subirse al repositorio.</td>
</tr>
<tr>
    <td colspan="5">Sprint 2 Retrospective Summary</td>
    <td colspan="8">En esta sesión todos los participantes, opinaron, mejoraron sus habilidades y cada uno se encargó de las mejoras dadas en la retroalimentación, también en el desarrollo de la landing y finalmente se decidió subir el landing en el último día</td>
</tr>
<tr>
    <td colspan="13">Sprint Goal & User Stories</td>
</tr>
<tr>
    <td colspan="5">Sprint 2 Goal</td>
    <td colspan="8"> La meta de este Sprint 2 es la mejora tanto en planteamiento y desarrollo de la documentación y que nuestra Landing Page tenga una correcta funcionalidad para el usuario de forma amigable.  

</td>
</tr>
<tr>
    <td colspan="5">Sprint 2 Velocity</td>
    <td colspan="8">velocity 7</td> 
</tr>
<tr>
    <td colspan="5">Sum of Story Points</td>
    <td colspan="8">7 story points</td>
</tr>
</table>

### 5.2.2.2. Aspect Leaders and Collaborators

![image](https://github.com/user-attachments/assets/85e7f5df-2f58-475a-abac-ff20ec6dbea3)


### 5.2.2.3. Sprint Backlog 2

<table>
<tr>
    <th colspan="3">Sprint #</th>
    <th colspan="10">Sprint 2</th>
</tr>
<tr>
    <td colspan="3">User Story</td>
    <td colspan="10">Work-Item/Task</td>
</tr>
<tr>
    <td colspan="1">Id</td>
    <td colspan="2">Title</td>
    <td colspan="1">Id</td>
    <td colspan="2">Title</td>
    <td colspan="3">Description</td>
    <td colspan="1">Estimation</td>
    <td colspan="2">Assigned To</td>
    <td colspan="1">Status (To-do / InProcess / To-Review / Done)</td>
</tr>
<tr>
    <td colspan="1">US05</td>
    <td colspan="2">Documentar mejoras en el desarrollo</td>
    <td colspan="1">UT05</td>
    <td colspan="2">Documentar mejoras técnicas"</td>
    <td colspan="3">Crear una documentación clara sobre decisiones y mejoras implementadas en el desarrollo</td>
    <td colspan="1">3</td>
    <td colspan="2">Angel Berrospi</td>
    <td colspan="1">Done</td>
</tr>
<tr>
    <td colspan="1">US06</td>
    <td colspan="2">Mejorar usabilidad de la landing page</td>
    <td colspan="1">UT06</td>
    <td colspan="2">Optimizar experiencia de usuario</td>
    <td colspan="3">Ajustar la estructura visual para mejorar la navegación y accesibilidad.</td>
    <td colspan="1">5</td>
    <td colspan="2">Joseph Rodriguez</td>
    <td colspan="1">Done</td>
</tr>
<tr>
    <td colspan="1">US07</td>
    <td colspan="2">Añadir mejoras en el frontend de la landing</td>
    <td colspan="1">UT07</td>
    <td colspan="2">Implementar mejores diseños a la landing page</td>
    <td colspan="3">Incluir ayudas visuales y mensajes emergentes para guiar al nuevo usuario en la landing.</td>
    <td colspan="1">5</td>
    <td colspan="2">Stephano Espinoza</td>
    <td colspan="1">Done</td>
</tr>
<tr>
    <td colspan="1">US08</td>
    <td colspan="2">Mejorar accesibilidad visual de la landing</td>
    <td colspan="1">UT08</td>
    <td colspan="2">Ajustar contraste y etiquetas</td>
    <td colspan="3">Aplicar mejoras de accesibilidad como mayor contraste de colores y etiquetas semánticas.</td>
    <td colspan="1">5</td>
    <td colspan="2">Raul Sanchez</td>
    <td colspan="1">Done</td>
</tr>
<tr>
    <td colspan="1">US09</td>
    <td colspan="2">Diseño de Documentación</td>
    <td colspan="1">UT09</td>
    <td colspan="2">Añadir diseños de alta calidad a la documentación</td>
    <td colspan="3">Incorporar nuevas estructuras, apoyar en la mejora de la documentación y su presentación de alta calidad para que sean relevantes en el contenido.</td>
    <td colspan="1">3</td>
    <td colspan="2">Merly Salon</td>
    <td colspan="1">Done</td>
</tr>
</table>

### 5.2.2.4. Development Evidence for Sprint Review
![Implementation2](https://github.com/user-attachments/assets/9f82b837-35dc-40bd-8b1a-f1f0d2fd23f0)

### 5.2.2.5. Execution Evidence for Sprint Review
Esta sección se centrará en la ejecución de la aplicación durante el sprint. Se describirá cómo los usuarios han interactuado con la plataforma, incluyendo su experiencia de usuario y cualquier problema o retroalimentación que hayan proporcionado. Además, se destacarán las mejoras en la usabilidad y la interfaz de usuario.
![Implementation5](https://github.com/user-attachments/assets/877cb95a-b75b-45f3-b18f-77e70e0f8a01)


### 5.2.2.6. Services Documentation Evidence for Sprint Review
Aquí se presentará la documentación relacionada con los servicios de atención médica ofrecidos a través de la plataforma. Esto puede incluir perfiles de profesionales de salud, detalles sobre las tarifas de consulta y paquetes disponibles, así como información sobre las referencias de pacientes anteriores.
![Implementation6](https://github.com/user-attachments/assets/fd6b280d-2fff-4203-91c2-66640a471205)


### 5.2.2.7. Software Deployment Evidence for Sprint Review
En esta sección, se describirá el proceso de implementación del software en un entorno de producción o pruebas. Se destacarán los hitos clave alcanzados en términos de despliegue y disponibilidad de la plataforma para los usuarios finales.
![SprintBacklog2](https://github.com/user-attachments/assets/6166521d-5254-49b6-a631-cd8993250e14)


### 5.2.2.8. Team Collaboration Insights during Sprint
Se proporcionarán detalles sobre la colaboración y la comunicación dentro del equipo de desarrollo durante el sprint. Esto incluirá la coordinación de esfuerzos entre los miembros del equipo, la resolución de problemas y la gestión de tareas. También se destacarán las lecciones aprendidas y las oportunidades de mejora en la colaboración.
![f87e7986-5421-4c6c-bb39-8f4bb6fc00a7](https://github.com/user-attachments/assets/fc7a14bc-12c5-4e3a-abde-87ecd5bf8997)





# Conclusiones
- La planificación previa es clave para el desarrollo estructurado del sistema:
Durante el proceso se evidenció la necesidad de una coordinación anticipada entre las áreas de diseño, desarrollo y análisis de usuarios para alinear correctamente la funcionalidad con las necesidades reales del público objetivo.

- Se requiere mayor tiempo de organización interna para segmentar correctamente:
La diferenciación entre gerentes de flota y conductores permitió establecer flujos específicos para cada uno, lo cual resalta la importancia de organizar sesiones de trabajo más detalladas por segmento antes de definir la arquitectura de información final.

- Los sistemas jerárquicos y secuenciales mejoran la experiencia del usuario:
La combinación de ambos tipos de organización facilita una navegación más intuitiva, lo que contribuye directamente a una mayor adopción por parte de los usuarios y a un uso más eficiente de la plataforma.

- El diseño centrado en el usuario es esencial para aplicaciones en campo:
Particularmente en el caso de los conductores, se concluye que los flujos deben ser extremadamente simples, directos y visuales, ya que los usuarios interactúan en contextos de movilidad y bajo presión de tiempo.
# Anexos

Video TB1: 

Video de Landing Page: 

Video de Deployment: 

Video de About the team: 

Video de About the team: 

Organizacion GitHub: 


# Bibliografia
