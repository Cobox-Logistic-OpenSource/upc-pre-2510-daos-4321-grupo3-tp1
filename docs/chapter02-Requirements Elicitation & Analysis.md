## Capítulo II: Requirements Elicitation & Analysis <a id="cap2"></a>

### 2.1. Competidores

**Competidor 1: Samsara**  
Samsara es una plataforma de IoT y telemática para gestión de flotas que ofrece GPS en tiempo real, registro automático de odómetro y combustible, programación de rutas, alertas de mantenimiento y reportes detallados de eficiencia operativa. Está presente en LATAM y cuenta con integraciones fáciles de desplegar en vehículos.

---

**Competidor 2: Fleet Complete**  
Fleet Complete proporciona soluciones de rastreo GPS, monitoreo de consumo de combustible, gestión de conductores y planificación de servicios. Su enfoque está en la eficiencia de la operación diaria, con dashboards personalizables y API para conectar con ERPs.

---

**Competidor 3: Sendd**  
Sendd es una startup peruana de última milla que permite programar rutas de entrega, hacer seguimiento en tiempo real y capturar prueba de entrega (fotos, firmas). Aunque no controla combustible, su fortaleza está en la experiencia local y en la usabilidad de su app móvil.

#### 2.1.1. Análisis competitivo

<table>
  <tr>
    <th colspan="6">Competitive Analysis Landscape</th>
  </tr>
  <tr>
    <td colspan="2" rowspan="2">¿Por qué llevar a cabo este análisis?</td>
    <td colspan="4">Pregunta</td>
  </tr>
  <tr>
    <td colspan="4">Para identificar cómo otras soluciones gestionan rutas, odómetro, combustible, prueba fotográfica y reportes, y descubrir oportunidades de diferenciación para CO-BOX LOGISTICS</td>
  </tr>
  <tr>
    <td colspan="2">Productos</td>
    <td>CO-BOX Logistic</td>
    <td>Samsara</td>
    <td>Fleet Complete</td>
    <td>Sendd</td>
  </tr>
  <tr>
    <td rowspan="2">Perfil</td>
    <td>Overview</td>
    <td>Programación de servicios, captura de odómetro (foto), registro de combustible y geolocalización, reportes web & móvil.</td>
    <td>IoT + telemática: GPS en tiempo real, odómetro automático, control de combustible, alertas de mantenimiento.</td>
    <td>Rastreo GPS, monitoreo de combustible, gestión de conductores, planificación de rutas.</td>
    <td>Rutas de última milla, seguimiento en tiempo real, proof of delivery (foto/firmas).</td>
  </tr>
  <tr>
    <td>Ventaja competitiva</td>
    <td>Flujo completo: unifica foto del odómetro, combustible y ruta en un solo proceso adaptado a transporte de carga.</td>
    <td>Madurez de producto y hardware plug-and-play fácil de instalar.</td>
    <td>Dashboards personalizables y API robusta para integraciones.</td>
    <td>Experiencia local en Perú y UX optimizada para conductores.</td>
  </tr>
  <tr>
    <td rowspan="2">Perfil de Marketing</td>
    <td>Mercado Objetivo</td>
    <td>Empresas de transporte de carga refrigerada o seca, supermercados, laboratorios y distribución general.</td>
    <td>Flotas medianas y grandes de transporte en LATAM.</td>
    <td>Flotas corporativas que requieren integración con ERPs.</td>
    <td>Negocios de e‑commerce y paquetería en Lima y alrededores.</td>
  </tr>
  <tr>
    <td>Estrategias de Marketing</td>
    <td>Marketing B2B digital, demos gratuitas, alianzas con talleres y gremios de transporte.</td>
    <td>Ferias de logística y partnerships con fabricantes de vehículos.</td>
    <td>Partnerships con proveedores de ERP y consultoras.</td>
    <td>Promociones locales y boca a boca en cooperativas de delivery.</td>
  </tr>
  <tr>
    <td rowspan="3">Perfil de Producto</td>
    <td>Productos & Servicios</td>
    <td>Programación de viajes, captura de odómetro, combustible y temperatura, reportes analíticos.</td>
    <td>GPS tracking, scheduling, alertas de mantenimiento, reporte de combustible.</td>
    <td>Rastreo GPS, monitoreo de combustible, gestión de conductores, planificación de rutas.</td>
    <td>Prueba de entrega con foto/firmas, seguimiento en ruta.</td>
  </tr>
  <tr>
    <td>Precios & Costos</td>
    <td>USD 25/equipo/mes + USD 100 instalación única.</td>
    <td>Desde USD 30/vehículo/mes, hardware incluido.</td>
    <td>Desde USD 28/vehículo/mes, descuentos anuales.</td>
    <td>USD 5/entrega + comisión, sin hardware ni suscripción fija.</td>
  </tr>
  <tr>
    <td>Canales de distribución</td>
    <td>Web & App móvil (iOS/Android).</td>
    <td>Web, App móvil y dispositivo plug‑and‑play.</td>
    <td>Web, App móvil e integraciones API.</td>
    <td>App móvil y portal web liviano.</td>
  </tr>
  <tr>
    <td rowspan="4">Análisis SWOT</td>
    <td>Fortalezas</td>
    <td>Integración odómetro + combustible + geolocalización en un solo sistema.</td>
    <td>Hardware plug‑and‑play y ecosistema IoT completo.</td>
    <td>Dashboards a medida y API robusta.</td>
    <td>Proof of delivery con foto y firmas.</td>
  </tr>
  <tr>
    <td>Debilidades</td>
    <td>MVP en fase temprana; base de usuarios pequeña.</td>
    <td>Costo inicial alto y curva de configuración.</td>
    <td>Requiere integración técnica y tiempo de onboarding.</td>
    <td>No registra combustible ni odómetro.</td>
  </tr>
  <tr>
    <td>Oportunidades</td>
    <td>Integrar alertas predictivas y expandir a flotas generales.</td>
    <td>Añadir módulos de foto del odómetro y proof of delivery.</td>
    <td>Ofrecer paquetes para pymes sin ERP.</td>
    <td>Expandir a gestión de combustible.</td>
  </tr>
  <tr>
    <td>Amenazas</td>
    <td>Competidores consolidados añadiendo funciones similares.</td>
    <td>Startups más ágiles con UX simplificado.</td>
    <td>Soluciones todo‑en‑uno emergentes.</td>
    <td>Plataformas integrales en LATAM.</td>
  </tr>
</table>


#### 2.1.2. Estrategias y tácticas frente a competidores

- **Flujo Unificado:** CO-BOX LOGISTICS unifica foto del odómetro, consumo de combustible y geolocalización en un solo proceso, a diferencia de Sendd (solo última milla) o Samsara (requiere hardware extra).

- **Onboarding Rápido:** Ofrecer instalación e integración en menos de 2 horas, frente a las 1–2 semanas típicas de Samsara o Fleet Complete.

- **Modelo de Precio Asequible:** Suscripción plana baja (USD 25/mes) versus los USD 30+ de los grandes, con opción freemium para flotas pequeñas.

- **Alianzas Locales:** Convenios con talleres mecánicos y estaciones de servicio en Lima para demos gratuitas y descuentos en hardware básico.

---

### 2.2. Entrevistas

#### 2.2.1. Diseño de entrevistas

**Segmento 1: Gerentes/encargados de flota**
1. ¿Cuál es su rol y responsabilidades principales?
2. ¿Cuántos vehículos administra y qué tipos de rutas realiza?
3. ¿Cómo registra hoy el odómetro y el consumo de combustible?
4. ¿Utiliza software o formularios en papel para programar y reportar servicios?
5. ¿Qué problemas más frecuentes encuentra en la gestión de rutas y consumo?
6. ¿Con qué frecuencia revisa los reportes de eficiencia de su flota?
7. ¿Qué datos le gustaría recibir automáticamente después de cada viaje?
8. ¿Cómo impactan las discrepancias de kilometraje o combustible en su operación diaria?
9. ¿Qué tan dispuesto estaría a adoptar una app que integre fotos de odómetro y reportes automáticos?
10. ¿Cuál es el presupuesto mensual aproximado que invertiría en este tipo de herramienta?

**Segmento 2: Conductores/operadores de ruta**
1. ¿Cuál es su experiencia conduciendo rutas de carga?
2. ¿Cómo registra actualmente el inicio y fin de cada viaje?
3. ¿Toma fotos del odómetro o anota el kilometraje manualmente?
4. ¿Cuánto tiempo le toma completar el registro de combustible y odómetro hoy?
5. ¿Qué dificultades tiene al usar apps o formularios para reportar su viaje?
6. ¿Preferiría usar una app móvil con botones claros para “Iniciar”, “Foto odómetro” y “Fin”?
7. ¿Qué tan útil le resultaría una geolocalización automática de cada parada?
8. ¿Le preocupa la precisión del kilometraje que ingresa?
9. ¿Qué comentarios o sugerencias tendría para que la app sea fácil de usar en ruta?
10. ¿Qué incentivos podrían motivarlo a completar su reporte diario a tiempo?

---
#### 2.2.2. Registro de entrevistas

##### Segmento objetivo #1 Gestores de Flota

---
#### Entrevista 1:

- **Nombres y apellidos:** Maria Cabello Alzate
- **Edad:** 24
- **Distrito:** La Victoria, Chiclayo


![Interview-1-segment-1.png](..%2Fassets%2Fchapter-02%2FInterview-1-segment-1.png)


- **Inicio:** 0:02
- **Duración:** 5:00
- **URL:** https://upcedupe-my.sharepoint.com/:v:/g/personal/u202223286_upc_edu_pe/EbfrSfoaKmBLmAWoW4dG7GMBRdJp1aSl_qSph5-691KLNA?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=RsluV9
- **Resumen:** María Cabello Alzate, de 24 años y con cuatro años de experiencia en gestión de flotas en La Victoria (Chiclayo), supervisa alrededor de 25 camiones que cubren rutas regionales y de última milla. Actualmente, los choferes anotan el odómetro y el consumo de combustible en formularios impresos, envían fotos por WhatsApp y ella consolida manualmente todo en Excel, lo que provoca errores de transcripción, fotos de baja calidad o sin geolocalización y demoras de uno o dos días en disponer de información fiable. Para mejorar la eficiencia, María busca una plataforma que registre automáticamente el kilometraje, los litros cargados, la ubicación GPS de inicio y fin de ruta, y una fotografía clara del odómetro con fecha y hora. Revisa semanalmente un dashboard en Excel y presenta un informe mensual a la gerencia; estaría dispuesta a invertir entre USD 400 y USD 600 al mes si el sistema le permite ahorrar al menos esa misma cifra en tiempo y costos operativos, siempre y cuando la curva de aprendizaje sea mínima y los beneficios sean inmediatos.

---
#### Entrevista 2:
- **Nombres y apellidos:**
- **Edad:**
- **Distrito:**


- **Inicio:**
- **Duración:**
- **URL:*https://upcedupe-my.sharepoint.com/:v:/g/personal/u202218590_upc_edu_pe/ES7DItVYxuVDiv8R6DPypBIBSmYYE-p0Y8wgvfbQOqFBEw?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D&e=Vq9RzC*
- **Resumen:**

---
##### Segmento objetivo #2 Conductores de vehiculos de transporte de carga


#### Entrevista 1:

- **Nombres y apellidos**: Darikson Brito 
- **Edad:** 34
- **Distrito:** Surquillo  
![Interview-1-segment-2.png](..%2Fassets%2Fchapter-02%2FInterview-1-segment-2.png)
- **Inicio**: 0:00 
- **Duración**: 2:50 
- **URL**: https://upcedupe-my.sharepoint.com/:v:/g/personal/u202218590_upc_edu_pe/EeowBqDCW8RPqnFuulcCqSAB4DtZaLiMFMjBa4YxkOBf5Q?e=zeqcf2&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D* 
- **Resumen**: Daritzon un conductor de transporte pesado con 10 año de experiencia, trabaja en AFE Service SAC, actualmente a Darikson le parece un poco repetitivo el hecho de tener que registrar mediante fotos y formularios largos, extensos que le toman aproximadamente 7 minutos a más llenarlos, todo de manera manual. Al comentarlo nuestra idea a Darikson, le pareció interesante y tiene la iniciativa de poder usar la aplicación, para la tecnología ayudaría a reducir el tiempo en el que hace los registros. Él comenta que sería de gran ayuda la geolocalización porque siempre hace paradas largas. Darikson habla de que sería muy útil de que la aplicación se intuitiva y que automatice estos procesos para que se pueda enfocar más en su trabajo.
- 
---
#### 2.2.3. Análisis de entrevistas

<h3>Segmento 1: Gerentes/Encargados de Flota</h3>
<ul>
  <li><strong>Rol principal:</strong> 100% coordina rutas, supervisa unidades y gestiona costos.</li>
  <li><strong>Vehículos:</strong> Entre 8 y 12, camiones de 3 a 30 toneladas.</li>
  <li><strong>Herramientas actuales:</strong> 100% usa Excel y papel, 66% con WhatsApp.</li>
  <li><strong>Problemas comunes:</strong>
    <ul>
      <li>100%: discrepancias en consumo y kilometraje.</li>
      <li>66%: dificultad para consolidar datos.</li>
      <li>66%: falta de información en tiempo real.</li>
    </ul>
  </li>
  <li><strong>Frecuencia de revisión:</strong> 33% semanal, 33% quincenal, 33% mensual.</li>
  <li><strong>Datos deseados automáticamente:</strong> 100% desea kilometraje, consumo, tiempos, evidencia digital.</li>
  <li><strong>Adopción de app:</strong> 100% dispuesto si es intuitiva y económica.</li>
  <li><strong>Presupuesto estimado:</strong> S/ 30 - S/ 150 por unidad mensual.</li>
</ul>

<h3>Segmento 2: Conductores de Vehículos de Carga</h3>
<ul>
  <li><strong>Experiencia:</strong> 100% con más de 10 años.</li>
  <li><strong>Registro actual:</strong> 100% usa cuadernos.</li>
  <li><strong>Uso de fotos/apps:</strong> 100% ha usado WhatsApp ocasionalmente.</li>
  <li><strong>Dificultades:</strong>
    <ul>
      <li>66%: olvido o apuro.</li>
      <li>100%: apps lentas o sin señal.</li>
    </ul>
  </li>
  <li><strong>Preferencia:</strong> App simple, pocos botones, uso offline.</li>
  <li><strong>Geolocalización:</strong> 100% la considera útil.</li>
  <li><strong>Incentivos:</strong> 66% menciona bonos; 100% quiere facilidad de uso.</li>
</ul>

### 2.3. Needfinding

#### 2.3.1 User Personas.

<p><strong>User Persona 1: Jorge Perez</strong><br>
Rol: Gerente de Flota<br>
Edad: 44 años<br>
Educación: Técnico en logística<br>
Objetivos: Reducir costos, automatizar reportes, mejorar trazabilidad<br>
Frustraciones: Consolidar manualmente, falta de visibilidad<br>
Comportamiento: Analiza semanalmente, busca eficiencia<br>
Tecnología: Excel intermedio, WhatsApp</p>

<p><strong>User Persona 2: Darikson Brito</strong><br>
Rol: Conductor de camión<br>
Edad: 50 años<br>
Educación: Secundaria completa<br>
Objetivos: Cumplir rutas, evitar reclamos, reportar fácil<br>
Frustraciones: Apps lentas, sin señal, sistemas complejos<br>
Comportamiento: Rutinario, cumple objetivos<br>
Tecnología: Celular básico, WhatsApp, cámara</p>

#### 2.3.2 User Task Matrix

<table border="1" cellpadding="5" cellspacing="0">
  <tr>
    <th>Tareas / User Persona</th>
    <th>Jorge Perez (Frec.)</th>
    <th>Jorge Perez (Imp.)</th>
    <th>Darikson Brito (Frec.)</th>
    <th>Darikson Brito (Imp.)</th>
  </tr>
  <tr><td>Planificar rutas</td><td>Alta</td><td>Alta</td><td>N/A</td><td>N/A</td></tr>
  <tr><td>Coordinar entregas</td><td>Alta</td><td>Alta</td><td>Media</td><td>Alta</td></tr>
  <tr><td>Registrar kilometraje</td><td>Media</td><td>Alta</td><td>Alta</td><td>Alta</td></tr>
  <tr><td>Reportar combustible</td><td>Media</td><td>Alta</td><td>Alta</td><td>Alta</td></tr>
  <tr><td>Consolidar datos</td><td>Alta</td><td>Alta</td><td>N/A</td><td>N/A</td></tr>
  <tr><td>Generar reportes</td><td>Media</td><td>Alta</td><td>N/A</td><td>N/A</td></tr>
  <tr><td>Foto del odómetro</td><td>Baja</td><td>Media</td><td>Media</td><td>Alta</td></tr>
  <tr><td>Usar apps móviles</td><td>Media</td><td>Alta</td><td>Baja</td><td>Alta</td></tr>
  <tr><td>Verificar entregas</td><td>Alta</td><td>Alta</td><td>Media</td><td>Alta</td></tr>
  <tr><td>Atender reclamos</td><td>Media</td><td>Alta</td><td>Baja</td><td>Media</td></tr>
</table>

<p><strong>Conclusiones:</strong><br>
Ambos valoran registrar kilometraje y consumo. Jorge Perez analiza y consolida; Darikson Brito ejecuta. La app debe enfocarse en estas tareas compartidas y críticas.</p>

#### 2.3.3 User Journey Mapping (AS-IS) 

<p><strong>Jorge Perez - Gerente de Flota</strong><br>
Etapas: Planificación → Coordinación → Recepción → Consolidación → Análisis → Reporte<br>
Pains: Pérdida de tiempo, errores, retrasos<br>
Oportunidades: Automatizar reportes, acceso en tiempo real, validación visual</p>

<p><strong>Darikson Brito - Conductor</strong><br>
Etapas: Asignación → Registro manual → Paradas → Entrega → Reporte final → Entrega papeles<br>
Pains: Olvido, apps lentas, papeleo<br>
Oportunidades: App simple, geolocalización automática, fotos como evidencia</p>

#### 2.3.4. Empathy Mapping

<p><strong>Jorge Perez (Gerente de Flota)</strong><br>
  
<strong>Piensa y siente:</strong> Presión por eficiencia<br>
<strong>Dice:</strong> "Necesito todo consolidado rápido"<br>
<strong>Hace:</strong> Usa Excel, revisa papeles<br>
<strong>Escucha:</strong> Clientes, gerencia<br>
<strong>Ve:</strong> Papeles desordenados<br>
<strong>Pains:</strong> Sin trazabilidad, pérdida de tiempo<br>
<strong>Gains:</strong> App que consolide y reduzca papeleo</p>

<p><strong>Darikson Brito (Conductor)</strong><br>
  
<strong>Piensa y siente:</strong> Quiere soluciones simples<br>
<strong>Dice:</strong> "Que sea rápido y simple"<br>
<strong>Hace:</strong> Maneja, anota, toma fotos<br>
<strong>Escucha:</strong> Jefes, quejas<br>
<strong>Ve:</strong> Poco tiempo, rutas complicadas<br>
<strong>Pains:</strong> Apps que fallan, presión<br>
<strong>Gains:</strong> App sencilla, botones grandes, offline</p>

#### 2.3.5. As-is Scenario Mapping.

#### Empresas de transporte con carga

![As-Is Empresas de Transporte de Carga .jpg](..%2Fassets%2Fchapter-02%2FAs-Is%20Empresas%20de%20Transporte%20de%20Carga%20.jpg)

#### Conductores de unidades de carga

![As-Is Conductores de Unidades de Carga.jpg](../assets/chapter-02/As-Is%20Conductores%20de%20Unidades%20de%20Carga.jpg)

#### 2.4. Ubiquitous Language.

Ubiquitous Language es un término que se refiere a un lenguaje común y compartido que se utiliza entre los miembros de un equipo de desarrollo de software, así como con los usuarios finales y otros interesados en el proyecto. Este lenguaje ayuda a asegurar que todos tengan una comprensión clara y coherente de los conceptos, términos y procesos involucrados en el desarrollo del software. A continuación, se presenta la lista de términos que se utilizarán en el desarrollo de la plataforma Co-box Logistic, junto con sus definiciones y ejemplos de uso.

- **Trazabilidad en tiempo real:** Monitoreo continuo de la ubicación y estado de la carga mediante GPS y actualizaciones automáticas.
- **Evidencia fotográfica de entrega:** Captura obligatoria de imágenes (firma, paquete, ubicación) al finalizar cada servicio.
- **Kilometraje automatizado:** Registro digital de kilómetros recorridos, calculado por el sistema sin intervención manual.
- **Odómetro:** Dispositivo que registra la distancia total recorrida por un vehículo a lo largo de su vida útil.
- **Reporte de desempeño (KPI):** Documento generado automáticamente con métricas como tiempo de entrega, rutas optimizadas y eficiencia del conductor.
- **Geocerca (Geofencing):** Límite virtual que activa alertas cuando un vehículo entra/sale de zonas predefinidas (ej: almacén, cliente).
- **Ruta optimizada:** Trayecto calculado por algoritmos para minimizar tiempo, combustible o costos.
- **Cliente final verificable:** Receptor de la carga que confirma la entrega mediante firma digital o código.
