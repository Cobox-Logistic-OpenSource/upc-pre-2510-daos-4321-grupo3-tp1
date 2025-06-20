# Capítulo V: Product Implementation, Validation & Deployment

## 5.1 Software Configuration Management
Aquí explicamos cómo organizamos, gestionamos y controlamos los cambios realizados durante el desarrollo de este proyecto.

### 5.1.1. Software Development Environment Configuration

**Gestión de Requisitos**
- **Trello**: Herramienta ideal para organizar y supervisar el flujo de trabajo en proyectos ágiles. Nos permite visualizar y actualizar el estado de las tareas e historias de usuario durante cada sprint.  
  Enlace: https://trello.com/es

**Diseño UX/UI del Producto**
- **Figma**: Plataforma para crear prototipos y diseños gráficos. Utilizada para diseñar la aplicación en navegadores de escritorio y móviles.  
  Enlace: https://www.figma.com/login
- **Lucidchart**: Herramienta para crear diagramas de flujo (wireflows, user-flows, diagramas de clases).  
  Enlace: https://www.lucidchart.com/

**Software Development**
- **WebStorm**: IDE con soporte para HTML, CSS, JavaScript y frameworks como Angular o React.  
  [Más información](https://www.jetbrains.com/webstorm/)
- **HTML5**: Lenguaje de marcado para estructurar el contenido web.  
  [Más información](https://www.w3schools.com/html/html5_syntax.asp)
- **CSS**: Lenguaje para definir estilos de diseño.  
  [Más información](https://google.github.io/styleguide/htmlcssguide.html)
- **JavaScript**: Lenguaje de programación para desarrollar la interfaz de usuario.  
  [Más información](https://developer.mozilla.org/es/docs/Web/JavaScript)
- **Angular**: Framework basado en TypeScript utilizado para construir el frontend del proyecto "Cobox-Logistic".

**Despliegue de Software**
- **Git**: Control de versiones que permite gestionar cambios en el código y trabajar colaborativamente desde la terminal.  
  [Más información](https://git-scm.com/)

**Documentación y Gestión del Proyecto**
- **GitHub**: Plataforma para alojar repositorios, colaborar y revisar contribuciones del equipo.  
  [Más información](https://github.com/)

### 5.1.2. Source Code Management

Se adoptará el modelo **GitFlow**, usando GitHub como plataforma de hosting del repositorio.

**Repositorio de GitHub:**
- Enlace a organización en GitHub
- Enlace a repositorio de la landing page
- Enlace al repositorio del reporte final
- Enlace al repositorio del frontend

**Estructura de Ramas:**
1. **Master**: Contiene versiones estables del producto.
2. **Develop**: Rama de integración continua.
3. **Feature**: Rama para desarrollo de nuevas funcionalidades (nombres como `feature/nombre-funcionalidad`).

### 5.1.3. Source Code Style Guide & Conventions

**HTML**
- Cerrar todos los elementos.
- Declarar tipo de documento: `<!DOCTYPE html>`
- Usar comentarios breves en una línea.
- Comillas para atributos con espacios.
- Siempre usar `alt`, `width` y `height` en `img`.

**CSS**
- Sangría de 2 espacios, sin tabulaciones.
- Todo en minúsculas.
- Eliminar espacios innecesarios.
- Comentar el código.
- Nombres de clases descriptivos.

### 5.1.4. Software Deployment Configuration

**Landing Page Deployment con GitHub Pages:**
1. Archivos en la raíz del repositorio.
2. Nombres correctos: `index.html`, `styles.css`, `main.js`, carpeta `assets/images`.
3. Subir los archivos con commit.
4. Ir a Settings > Pages, seleccionar `main` como branch.
5. Establecer `root` como carpeta fuente.
6. GitHub generará un enlace con la página publicada.

## 5.2. Landing Page, Services & Applications Implementation

### 5.2.1. Sprint 1
**Sprint Planning 1**  
Fecha: 2025-04-24  
Hora: 9:00PM  
Lugar: Meet  
Preparado por: Merly Salon Puerta

**Sprint Review:** Desarrollo inicial de la landing page.  
**Retrospectiva:** Se realizaron mejoras visuales, se agregaron idiomas y se subió al repositorio al final del sprint.

**Sprint Goal:** Planificación y funcionalidad básica de la landing.  
**Velocity:** 7  
**Story Points:** 8

**Sprint Backlog:** *(ver tablas originales en el documento)*

### 5.2.2. Sprint 2
**Sprint Planning 2**  
Fecha: 2025-05-14  
Hora: 3:00PM  
Lugar: Meet  
Preparado por: Angel Berrospi

**Sprint Review:** Mejoras en la landing y revisión estructural.  
**Retrospectiva:** Mejoras individuales aplicadas, decisiones tomadas colaborativamente.

**Sprint Goal:** Mejora en la experiencia y estructura de la landing.  
**Velocity:** 7  
**Story Points:** 7

**Sprint Backlog:** *(ver tablas originales en el documento)*

### 5.2.3. Sprint 3
**Sprint Planning 3**  
Fecha: 2025-06-17  
Hora: 5:00PM  
Lugar: Meet  
Preparado por: Angel Berrospi

**Sprint Review:** Integración backend y frontend, mejoras en landing.  
**Retrospectiva:** Mejoras aplicadas, se subió todo el mismo día.  
**Sprint Goal:** Mejorar experiencia, backend y documentación.  
**Velocity:** 6  
**Story Points:** 7

**Sprint Backlog:** *(ver tablas originales en el documento)*

## 5.3 Validation Interviews

### 5.3.1. Diseño de Entrevistas

**Segmento 1: Empresas de Transporte**
- Preguntas sobre facilidad de uso, visualización, trazabilidad, decisiones, privacidad y sugerencias.

**Segmento 2: Conductores**
- Preguntas sobre facilidad de registro, uso en campo, geolocalización, formularios y comunicación.

### 5.3.2. Registro de Entrevistas
*Se incluye el registro documentado de cada entrevista según el segmento correspondiente.*

### 5.3.3. Evaluaciones según heurísticas
- Evaluación de la experiencia según heurísticas de usabilidad, arquitectura de información y experiencia del usuario.

---

## Conclusiones
- La planificación anticipada es clave para alinear funcionalidad con las necesidades reales.
- Es importante segmentar usuarios (conductores y empresas) para flujos específicos.
- Los sistemas jerárquicos y secuenciales mejoran la navegación.
- El diseño centrado en el usuario es fundamental para apps de uso en campo.

---

## Anexos
- Video TB1:  
- Video de Landing Page:  
- Video de Deployment:  
- Video About the Team:  
- Organización GitHub:  

---

## Bibliografía
- Angular Team. (2024). *Introduction to Angular*. https://angular.dev/usa  
- Cohn, M. (2004). *User Stories Applied: For Agile Software Development*. Addison-Wesley.  
- Scrum.org. (2023). *The Scrum Guide™*. https://scrumguides.org  
- AFE Logistics. (2024). *Soluciones para la gestión de flotas y logística*. https://afelogistics.com  
- Microsoft Learn. (2024). *REST API Design Best Practices*. https://learn.microsoft.com/en-us/azure/architecture/best-practices/api-design
