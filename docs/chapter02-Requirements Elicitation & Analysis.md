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
    <td colspan="4">Para identificar cómo otras soluciones gestionan rutas, odómetro, combustible, prueba fotográfica y reportes, y descubrir oportunidades de diferenciación para AFE‑SERVICE.</td>
  </tr>
  <tr>
    <td colspan="2">Productos</td>
    <td>AFE‑SERVICE</td>
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


### 2.1.2. Estrategias y tácticas frente a competidores

- **Flujo Unificado:** AFE‑SERVICE unifica foto del odómetro, consumo de combustible y geolocalización en un solo proceso, a diferencia de Sendd (solo última milla) o Samsara (requiere hardware extra).

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
