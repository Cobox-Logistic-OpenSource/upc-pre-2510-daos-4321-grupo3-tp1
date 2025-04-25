## Capítulo IV: Product Design <a id="c4"></a>

### 4.1. Style Guidelines
 A continuación, se especificará los parámetros implementados en la estructura del proyecto.
#### 4.1.1. General Style Guidelines
**Brand Overview**

La startup “Co-Box Logistics”, se enfoca en ofrecer una solución tecnológica avanzada al sector del transporte de carga en Perú. Para ello, implementa una plataforma web inteligente encargada de segmentar y optimizar los procesos logísticos en distintas fases. Estas comprenden el control de kilometraje de las unidades, la captura de evidencias fotográficas al momento de la entrega, la geolocalización en tiempo real y la generación automatizada de reportes e indicadores de desempeño.

**Brand Name**

El nombre de la propuesta de solución es Co-Box Logistics. La idea surge de la combinación de las palabras “Asistencia, Funcionalidad y Eficiencia”, elementos clave que definen el enfoque de la plataforma. Este concepto está directamente relacionado con el problema que busca resolver: la falta de control, trazabilidad y eficiencia en el sector del transporte de carga. En ese sentido, la aplicación se orienta al desarrollo de un sistema web inteligente que automatiza y optimiza la gestión de servicios logísticos en empresas de transporte, mejorando cada fase del proceso mediante el uso de tecnologías avanzadas como la geolocalización, el registro de kilometraje y la generación automática de reportes.

**Logo:** 

![Logo-Co-BoxLogistics.jpeg](..%2Fassets%2Fchapter-04%2FLogo-Co-BoxLogistics.jpeg)

**Typography**

La tipografía es necesaria para estructurar y organizar el lenguaje visual de todas las plataformas que se desarrollarán para cumplir con las características principales de la aplicación. Se ha tomado en cuenta que las fuentes deben ser legibles y deben aportar a la experiencia del usuario, por ello se optó por estos tipos de letra.

![Typography01.JPG](..%2Fassets%2Fchapter-04%2FTypography01.JPG)

**Head**

![Typography02.JPG](..%2Fassets%2Fchapter-04%2FTypography02.JPG)

**Body**

![Typography03.JPG](..%2Fassets%2Fchapter-04%2FTypography03.JPG)

**Colors**

![Colors.JPG](..%2Fassets%2Fchapter-04%2FColors.JPG)

**Spacing**

![Spacing.JPG](..%2Fassets%2Fchapter-04%2FSpacing.JPG)

**Tono de Comunicación y lenguaje aplicado**

Color primario: Este color representa la identidad visual de los operadores logísticos y técnicos de campo. A través de él, buscamos transmitir confianza, eficiencia y profesionalismo. Al interactuar con la plataforma, el usuario percibirá este tono como cercano y confiable, lo que se reflejará también en el contacto con los encargados de las entregas y supervisiones.
Color secundario: Despierta una sensación de movimiento y acción. Es un color que inspira energía, dinamismo y compromiso con el trabajo bien hecho. Este tono refuerza la visión de Co-Box Logistics como una solución que conecta tecnología y eficiencia para transformar el transporte de carga. 
Blanco: Refleja orden, simplicidad y transparencia. Es un color ampliamente utilizado en entornos tecnológicos y de gestión, pues facilita la legibilidad y aporta claridad a la interfaz de usuario.
Negro: Transmite seriedad, modernidad y autoridad. Sirve como contraste para resaltar funciones clave y elementos importantes de la plataforma.
En cuanto al lenguaje, se optará por un tono profesional, directo y respetuoso, acompañado de un enfoque entusiasta y resolutivo. Co-Box Logistics incluirá mensajes, recomendaciones y experiencias que motiven al usuario a tomar decisiones informadas, reforzando la confiabilidad del sistema. 

#### 4.1.2. Web Style Guidelines
Desarrollaremos una aplicación que se adecue a cualquier dispositivo tecnológico sin la necesidad de malograr el diseño del contenido. Por ello, se tendrá que tomar en cuenta cada tipo de dispositivo para que el contenido esté estructurado de la mejor manera para cada uno.

![Web-Style-Guidelines.jpeg](..%2Fassets%2Fchapter-04%2FWeb-Style-Guidelines.jpeg)

**Patrón Z**

![PatronZ.JPG](..%2Fassets%2Fchapter-04%2FPatronZ.JPG)

Se implementará el patrón Z, el punto de partida se sitúa en la esquina superior izquierda, donde estará visible nuestro logotipo, sirviendo como referencia inicial. Desde allí, la vista se dirige hacia la esquina superior derecha, zona en la que se ubicarán los accesos principales como “Sobre Nosotros”, “Reservas” y “Configuración”.

**Botones**

![Botones.JPG](..%2Fassets%2Fchapter-04%2FBotones.JPG)

**Elementos Grandes**

![Elementos-Grandes.JPG](..%2Fassets%2Fchapter-04%2FElementos-Grandes.JPG)

**Tarjetas**

![Tarjetas.JPG](..%2Fassets%2Fchapter-04%2FTarjetas.JPG)


Link para visualizar el figma con el Style Guidelines general:https://www.figma.com/design/wcyVOlGQfIERlEbFh3Ly2S/Style-Guidelines?node-id=1-2&t=rV25Yk6baCQtLWrD-1

### 4.2. Information Architecture
En esta sección, definiremos la estructuración de nuestro producto para cada uno de nuestros segmentos objetivo. Abarcaremos diversos componentes que permitirán al usuario a organizar y encontrar su contenido: Organization systems, Labeling systems, SEO Tags and Meta Tags, Searching systems y Navigation systems.

#### 4.2.1. Organization Systems
En esta sección, se detalla cómo la plataforma Co-Box Logistics estructura la información y funcionalidades clave, considerando las necesidades específicas de sus segmentos objetivo. Co-Box Logistics conecta a empresas de transporte con herramientas inteligentes que permiten un control preciso y automatizado de cada servicio, incluyendo kilometraje, geolocalización y evidencia fotográfica, facilitando una gestión logística más eficiente y moderna.

**Segmento 1: Gerentes / Encargados de flota**
**Jerárquica:**

- Panel de control de flota: Resume el estado actual de cada unidad. Organizado según prioridad operativa: unidades con alertas de mantenimiento, bajo rendimiento o uso excesivo de combustible aparecen primero.

- Historial de rutas y servicios: Registro cronológico de viajes completados con acceso a evidencias, kilometraje y ubicación. Permite evaluar la eficiencia por fechas o rutas específicas.

- Ficha técnica de unidades: Información detallada por vehículo, como placa, odómetro, consumo, alertas técnicas y próximas revisiones.


- Indicadores y reportes de desempeño: Métricas clave categorizadas por vehículo, conductor o ruta, con filtros personalizables para analizar eficiencia operativa.

**Secuencial:**
 - Programación de servicios: Flujo guiado paso a paso para asignar rutas y conductores. Se incluyen fases de planificación, validación de disponibilidad y confirmación de servicio.

 - Emisión de reportes automatizados: Tras cada servicio, se genera un reporte con kilometraje, ubicación, incidencias y rendimiento del conductor, en una estructura clara y secuencial.

 **Segmento 2: Conductores / Operadores de ruta**
**Jerárquica:**
 - Historial de viajes realizados: Lista de viajes anteriores categorizada cronológicamente, accesible desde el panel principal.
 - Resumen diario de tareas: Muestra rutas asignadas con filtros por estado (pendiente, en curso, finalizado).
 - Perfil del conductor: Sección con datos personales, métricas de desempeño y cumplimiento de reportes, organizado por relevancia.

**Secuencial:**
 - Inicio de servicio: Flujo intuitivo:
   - Paso 1: “Iniciar viaje”.
   - Paso 2: Captura de foto del odómetro.
   - Paso 3: Registro de paradas vía geolocalización.
   - Paso 4: “Finalizar viaje” con carga automática de datos al sistema.
 - Registro de combustible: Formulario simple con captura fotográfica del ticket, litros cargados y comentario opcional.

#### 4.2.2. Labeling Systems
El sistema de etiquetado de  Co-Box Logistics ha sido diseñado para facilitar la navegación rápida, clara y accesible, optimizando la experiencia de cada tipo de usuario.
**Web App - Gerentes/Encargados de flota**

**Menú lateral con etiquetas funcionales y directas:**
 - Inicio: Vista general de la operación diaria (servicios activos, alertas, resumen de desempeño).
 - Rutas asignadas: Gestión y control de entregas en curso y próximas.
 - Unidades: Información técnica y estado de cada vehículo.
 - Reportes: Acceso a KPIs e informes personalizables.
 - Configuración: Ajustes del sistema, alertas automáticas y permisos.

**App Móvil - Conductores/Operadores de ruta**

**Menú principal con botones de acción y navegación sencilla, pensada para el entorno móvil en ruta:**
 - Iniciar viaje: Comienza el servicio con geolocalización activa.
 - Foto odómetro: Captura rápida del estado inicial del vehículo.
 - Finalizar viaje: Cierra el servicio e ingresa observaciones.
 - Mi historial: Consulta de viajes previos y métricas.
 - Perfil: Datos personales y desempeño.
 - Soporte: Acceso rápido a ayuda y contacto.

#### 4.2.3. SEO Tags and Meta Tags

**Landing Page**
-Title: 
-Meta Description: 
-Meta Keywords: 
-Meta Author: 

**Aplicación Web**
-Title: 
-Meta Description: 
-Meta Keywords: 
-Meta Author: 

#### 4.2.4. Searching Systems


**Opciones de Búsqueda**  
**Barra de Búsqueda**

**Categorías**

**Etiquetas Populares**  


**Filtros Disponibles**  


**Apariencia de los Datos Después de la Búsqueda**  
**Listados de Resultados**  


**Resumen y Descripción**  


**Opciones de Ordenación y Filtros Aplicados**  


**Revisiones y Comentarios**  


#### 4.2.5. Navigation Systems



1. **Páginas Principales**

2. **Opciones de Usuario**

3. **Búsqueda y Navegación**

4. **Branding y Identidad**


### 4.3. Landing Page UI Design
#### 4.3.1. Landing Page Wireframe


#### 4.3.2. Landing Page Mockup


## 4.4. Web Applications UX/UI Design

#### 4.4.1. Web Applications Wireframes

#### 4.4.2. Web Applications Wireflow Diagrams

#### 4.4.3. Web Applications Mock-ups

#### 4.4.4. Web Applications User Flow Diagrams

### 4.5. Web Applications Prototyping

### 4.6 Domain Driven Software Architecture
En esta sección se presenta la arquitectura de software basada en el dominio para Cobox-Logistic. Se detallan los diferentes diagramas que ilustran la estructura y organización del sistema, así como los componentes clave que lo integran, mostrando cómo se interconectan para proporcionar una solución eficiente y escalable.

#### 4.6.1. Software Architecture Context Diagram

![ContextDiagram.png](..%2Fassets%2Fchapter-04%2FContextDiagram.png)

#### 4.6.2. Software Architecture Container Diagrams



#### 4.6.3. Software Architecture Components Diagrams



### 4.7. Software Object-Oriented Design
En esta sección se presenta el diseño de software orientado a objetos para OsitoPolar. Se incluyen diagramas de clases y un diccionario de clases que detallan la estructura y los atributos de las principales entidades del sistema, ofreciendo una visión clara de cómo se organizan y gestionan los componentes clave dentro de la plataforma.

#### 4.7.1. Class Diagrams
![Diagrama_Clases.png](..%2Fassets%2Fchapter-04%2FDiagrama_Clases.png)

#### 4.7.2. Class Dictionary

<h3>Usuario</h3>
<p><strong>Descripción:</strong> Clase base que representa a cualquier usuario del sistema.</p>
<p><strong>Atributos:</strong></p>
<ul>
  <li><code>id</code>: Identificador único del usuario</li>
  <li><code>nombre</code>, <code>apellido</code>, <code>email</code>, <code>telefono</code></li>
  <li><code>password</code>: Contraseña encriptada</li>
  <li><code>tipo</code>: Tipo de usuario (Gestor, Conductor, Técnico)</li>
  <li><code>fechaCreacion</code>, <code>activo</code></li>
</ul>
<p><strong>Métodos:</strong></p>
<ul>
  <li><code>autenticar()</code>: Verifica credenciales</li>
  <li><code>actualizarPerfil()</code>: Actualiza información personal</li>
</ul>

<h3>Gestor</h3>
<p><strong>Descripción:</strong> Usuario que administra la flota.</p>
<ul>
  <li><strong>Atributo:</strong> <code>cargo</code></li>
  <li><strong>Métodos:</strong> <code>asignarRuta()</code>, <code>generarReporte()</code>, <code>visualizarDashboard()</code></li>
</ul>

<h3>Conductor</h3>
<p><strong>Descripción:</strong> Usuario que ejecuta rutas y registra entregas.</p>
<ul>
  <li><strong>Atributos:</strong> <code>licencia</code>, <code>categoria</code>, <code>fechaVencimientoLicencia</code>, <code>disponible</code></li>
  <li><strong>Métodos:</strong> <code>iniciarRuta()</code>, <code>finalizarRuta()</code>, <code>reportarIncidencia()</code>, <code>registrarEntrega()</code></li>
</ul>

<h3>Técnico</h3>
<p><strong>Descripción:</strong> Encargado del mantenimiento de vehículos.</p>
<ul>
  <li><strong>Atributo:</strong> <code>especialidad</code></li>
  <li><strong>Método:</strong> <code>registrarMantenimiento()</code></li>
</ul>

<h3>Vehículo</h3>
<p><strong>Descripción:</strong> Representa un vehículo de la flota.</p>
<ul>
  <li><strong>Atributos:</strong> <code>id</code>, <code>placa</code>, <code>marca</code>, <code>modelo</code>, <code>anio</code>, <code>tipo</code>, <code>capacidadCarga</code>, <code>capacidadTanque</code>, <code>estado</code>, <code>kilometrajeActual</code>, <code>ultimoMantenimiento</code>, <code>activo</code></li>
  <li><strong>Métodos:</strong> <code>actualizarKilometraje()</code>, <code>cambiarEstado()</code></li>
</ul>

<h3>Ruta</h3>
<p><strong>Descripción:</strong> Trayecto planificado entre dos puntos.</p>
<ul>
  <li><strong>Atributos:</strong> <code>id</code>, <code>origen</code>, <code>destino</code>, <code>distancia</code>, <code>fechaProgramada</code>, <code>estado</code>, <code>consumoEstimado</code></li>
  <li><strong>Métodos:</strong> <code>actualizarEstado()</code>, <code>calcularEficiencia()</code></li>
</ul>

<h3>Servicio</h3>
<p><strong>Descripción:</strong> Representa una operación logística completa.</p>
<ul>
  <li><strong>Atributos:</strong> <code>id</code>, <code>fechaCreacion</code>, <code>fechaInicio</code>, <code>fechaFin</code>, <code>estado</code>, <code>observaciones</code></li>
  <li><strong>Métodos:</strong> <code>iniciarServicio()</code>, <code>finalizarServicio()</code>, <code>calcularDuracion()</code></li>
</ul>

<h3>Entrega</h3>
<p><strong>Descripción:</strong> Envío de mercancía a un cliente.</p>
<ul>
  <li><strong>Atributos:</strong> <code>id</code>, <code>cliente</code>, <code>direccion</code>, <code>referencia</code>, <code>fechaProgramada</code>, <code>fechaEntrega</code>, <code>estado</code>, <code>observaciones</code>, <code>pesoTotal</code></li>
  <li><strong>Métodos:</strong> <code>actualizarEstado()</code>, <code>validarEntrega()</code></li>
</ul>

<h3>RegistroKilometraje</h3>
<p><strong>Descripción:</strong> Lectura del odómetro.</p>
<ul>
  <li><strong>Atributos:</strong> <code>id</code>, <code>kilometrajeInicial</code>, <code>kilometrajeFinal</code>, <code>fecha</code></li>
  <li><strong>Método:</strong> <code>calcularDistancia()</code></li>
</ul>

<h3>RegistroCombustible</h3>
<p><strong>Descripción:</strong> Registro de cargas de combustible.</p>
<ul>
  <li><strong>Atributos:</strong> <code>id</code>, <code>cantidad</code>, <code>precioUnitario</code>, <code>total</code>, <code>tipoCombustible</code>, <code>fecha</code>, <code>estacionServicio</code></li>
  <li><strong>Métodos:</strong> <code>validarRegistro()</code>, <code>calcularRendimiento()</code></li>
</ul>

<h3>Incidencia</h3>
<p><strong>Descripción:</strong> Reporte de problema o evento inesperado.</p>
<ul>
  <li><strong>Atributos:</strong> <code>id</code>, <code>tipo</code>, <code>descripcion</code>, <code>fechaReporte</code>, <code>gravedad</code>, <code>estado</code></li>
  <li><strong>Métodos:</strong> <code>actualizarEstado()</code>, <code>asignarResponsable()</code></li>
</ul>

<h3>Mantenimiento</h3>
<p><strong>Descripción:</strong> Registro de acciones de mantenimiento.</p>
<ul>
  <li><strong>Atributos:</strong> <code>id</code>, <code>tipo</code>, <code>fechaProgramada</code>, <code>fechaRealizada</code>, <code>descripcion</code>, <code>costo</code>, <code>estado</code></li>
  <li><strong>Métodos:</strong> <code>actualizarEstado()</code>, <code>notificarProximidad()</code></li>
</ul>

<h3>Evidencia</h3>
<p><strong>Descripción:</strong> Archivo que sirve como prueba de acción (foto, firma, etc.).</p>
<ul>
  <li><strong>Atributos:</strong> <code>id</code>, <code>tipo</code>, <code>url</code>, <code>fecha</code>, <code>latitud</code>, <code>longitud</code></li>
  <li><strong>Método:</strong> <code>validarEvidencia()</code></li>
</ul>

<h3>Reporte</h3>
<p><strong>Descripción:</strong> Documento generado para análisis.</p>
<ul>
  <li><strong>Atributos:</strong> <code>id</code>, <code>tipo</code>, <code>fechaInicio</code>, <code>fechaFin</code>, <code>formato</code></li>
  <li><strong>Métodos:</strong> <code>generarReporteEficiencia()</code>, <code>generarReporteEntregas()</code>, <code>exportarReporte()</code></li>
</ul>

<h3>Dashboard</h3>
<p><strong>Descripción:</strong> Panel con indicadores clave.</p>
<ul>
  <li><strong>Atributo:</strong> <code>id</code></li>
  <li><strong>Métodos:</strong> <code>obtenerIndicadores()</code>, <code>obtenerAlertasCriticas()</code>, <code>actualizarDatos()</code></li>
</ul>


### 4.8. Database Design



#### 4.8.1. Database Diagram
![Diagrama_DB.png](..%2Fassets%2Fchapter-04%2FDiagrama_DB.png)
