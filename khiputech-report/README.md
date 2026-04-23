# KhipuTech — Documentación del Proyecto

![Logo UPC](https://images.seeklogo.com/logo-png/40/2/universidad-peruana-de-ciencias-aplicadas-upc-logo-png_seeklogo-402620.png)

## 📱 Producto: KhipuTech
**Real-Time Visitor Analytics para Museos y Espacios Culturales**

Plataforma de analítica en tiempo real que combina infraestructura IoT de bajo costo con experiencias digitales interactivas mediante QR/NFC.

---

## 👥 Equipo: WebStone

| Nombre | Código |
|--------|--------|
| Fabian Jesus Sandoval Cueto | U20221a132 |
| Oscar Diego Checa Burga | U20231E492 |
| Andrea Khristina Correa Rodriguez | U202412041 |

---

## 📚 Índice del Informe

### Front Matter
- [Student Outcome](report/front-matter/01-student-outcome.md)

---

### [Capítulo I: Introducción](report/01-introduction.md)
- 1.1. Startup Profile
  - 1.1.1. Descripción del Startup
  - 1.1.2. Perfiles de los Integrantes del Equipo
- 1.2. Solution Profile
  - 1.2.1. Antecedentes y Problemática
  - 1.2.2. Lean UX Process
- 1.3. Segmento Objetivo

---

### [Capítulo II: Requirements Elicitation & Analysis](report/02-requirements.md)
- 2.1. Competidores
  - 2.1.1. Análisis Competitivo
  - 2.1.2. Estrategias y Tácticas frente a Competidores
- 2.2. Entrevistas
  - 2.2.1. Diseño de Entrevistas
  - 2.2.2. Registro de Entrevistas
  - 2.2.3. Análisis de Entrevistas
- 2.3. Needfinding
  - 2.3.1. User Personas
  - 2.3.2. User Task Matrix
  - 2.3.3. User Journey Mapping
  - 2.3.4. Empathy Mapping
- 2.4. Big Picture Event Storming
- 2.5. Ubiquitous Language

---

### [Capítulo III: Requirements Specification](report/03-specification.md)
- 3.1. User Stories
- 3.2. Impact Mapping
- 3.3. Product Backlog

---

### [Capítulo IV: Product Design](report/04-product-design.md)
- 4.1. Style Guidelines
  - 4.1.1. General Style Guidelines
  - 4.1.2. Web Style Guidelines
- 4.2. Information Architecture
  - 4.2.1. Organization Systems
  - 4.2.2. Labeling Systems
  - 4.2.3. SEO Tags and Meta Tags
  - 4.2.4. Searching Systems
  - 4.2.5. Navigation Systems
- 4.3. Landing Page UI Design
  - 4.3.1. Landing Page Wireframe
  - 4.3.2. Landing Page Mock-up
- 4.4. Web Applications UX/UI Design
  - 4.4.1. Web Applications Wireframes
  - 4.4.2. Web Applications Wireflow Diagrams
  - 4.4.3. Web Applications Mock-ups
  - 4.4.4. Web Applications User Flow Diagrams
- 4.5. Web Applications Prototyping
- 4.6. Domain-Driven Software Architecture
  - 4.6.1. Design-Level Event Storming
  - 4.6.2. Software Architecture Context Diagram
  - 4.6.3. Software Architecture Container Diagrams
  - 4.6.4. Software Architecture Components Diagrams
- 4.7. Software Object-Oriented Design
  - 4.7.1. Class Diagrams
- 4.8. Database Design
  - 4.8.1. Database Diagram

---

### [Capítulo V: Product Implementation, Validation & Deployment](report/05-implementation.md)
- 5.1. Software Configuration Management
  - 5.1.1. Software Development Environment Configuration
  - 5.1.2. Source Code Management
  - 5.1.3. Source Code Style Guide & Conventions
  - 5.1.4. Software Deployment Configuration
- 5.2. Landing Page, Services & Applications Implementation
  - 5.2.1. Sprint 1
  - 5.2.2. Sprint 2
  - 5.2.3. Sprint 3
  - 5.2.4. Sprint 4
- 5.3. Validation Interviews
  - 5.3.1. Diseño de Entrevistas
  - 5.3.2. Registro de Entrevistas
  - 5.3.3. Evaluaciones según Heurísticas
- 5.4. Video About-the-Product

---

### Secciones Finales
- [Bibliografía](report/99-bibliography.md)
- [Anexos](report/99-bibliography.md#anexos)

---

## 📄 Entregables de Diseño

### Recursos Visuales
- 🎨 [Web Style Guide](assets/deliverables/khiputech-web-style-guide.html) — Guía de estilos interactiva con componentes UI
- 🗺️ [Navigation Systems](assets/deliverables/khiputech-navigation-systems.pdf) — Sistemas de navegación documentados
- 🔍 [Searching Systems](assets/deliverables/khiputech-searching-systems.pdf) — Sistemas de búsqueda y filtrado
- 🎭 [Logo KhipuTech](assets/deliverables/khiputech-logo.svg) — Logo oficial en formato SVG

### Documento Consolidado
- 📖 **[TB1-Report.pdf](build/TB1-Report.pdf)** — Informe completo en PDF (generado con Pandoc)

---

## 🔧 Compilación del Documento (Opcional)

Este proyecto utiliza **Pandoc** con **Docs-as-Code** para compilación reproducible.

### Requisitos
- [Pandoc](https://pandoc.org/installing.html) >= 3.0
- LuaLaTeX (incluido en [TeX Live](https://www.tug.org/texlive/) o [MiKTeX](https://miktex.org/))

### Compilar el PDF

```bash
# Opción 1: Usando Make
make pdf

# Opción 2: Comando directo
pandoc --defaults=config/defaults.yaml
```

El PDF se genera en `build/TB1-Report.pdf`.

---

## 📁 Estructura de Archivos
