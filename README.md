# KhipuTech — Documentación del Proyecto

**Real-Time Visitor Analytics para Museos y Espacios Culturales**

Plataforma de analítica en tiempo real que combina infraestructura IoT de bajo costo con experiencias digitales interactivas mediante QR/NFC.

---

## 📚 Índice del Informe

### Front Matter

- [Portada Institucional](report/front-matter/00-cover.md)
- [Project Collaboration Insights](report/front-matter/01-collaboration-insights.md)
- [Registro de Versiones](report/front-matter/02-version-history.md)
- [Student Outcome](report/front-matter/03-student-outcome.md)

---

## Team members:

|                  Nombre                  |   Código   |
| :--------------------------------------: | :--------: |
|         Huaco Oliva, Luis Alonso         | U202417743 |
|       Sandoval Cueto, Fabian Jesus       | U20221A132 |
|         Oscar Diego Checa Burga          | U20231E492 |
| Andrea Khristina Esther Correa Rodriguez | U202412041 |
|      Winnie Lisbeth Merino Ordinola      | U20231E504 |

### [Capítulo I: Introducción](report/01-introduction.md)

- 1.1. Startup Profile
  - 1.1.1. Descripción del Startup
  - 1.1.2. Perfiles de los Integrantes del Equipo
- 1.2. Solution Profile
  - 1.2.1. Antecedentes y Problemática
  - 1.2.2. Lean UX Process
- 1.3. Segmentos Objetivo

---

### [Capítulo II: Requirements Elicitation & Analysis](report/02-requirements.md)

- 2.1. Competidores
- 2.2. Entrevistas
- 2.3. Needfinding
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
- 4.3. Landing Page UI Design
- 4.4. Web Applications UX/UI Design
- 4.5. Web Applications Prototyping
- 4.6. Domain-Driven Software Architecture
- 4.7. Software Object-Oriented Design
- 4.8. Database Design

---

### [Capítulo V: Product Implementation, Validation & Deployment](report/05-implementation.md)

- 5.1. Software Configuration Management
- 5.2. Landing Page, Services & Applications Implementation
- 5.3. Validation Interviews
- 5.4. Video About-the-Product

---

### Secciones Finales

- [Bibliografía y Anexos](report/99-bibliography.md)

---

## 📄 Entregables de Diseño

### Recursos Interactivos

- 🎨 [General Style Guide](assets/deliverables/khiputech-general-style-guide.html) — Branding, logo, tipografía, iconografía
- 🎨 [Web Style Guide](assets/deliverables/khiputech-web-style-guide.html) — Componentes UI, grid, responsive

### Documento Compilado

- 📖 **TB1-Report.pdf** — Informe completo en PDF (generado con Pandoc)

---

## 🔧 Compilación del Documento

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

Ver [guía completa de compilación](INSTRUCTIONS.md) _(si existe)_.

---

## 📁 Estructura de Archivos

```
khiputech-report/
├── README.md                    # Este archivo
├── report/                      # Contenido Markdown por capítulos
│   ├── front-matter/
│   ├── 01-introduction.md
│   ├── 02-requirements.md
│   ├── 03-specification.md
│   ├── 04-product-design.md
│   ├── 05-implementation.md
│   └── 99-bibliography.md
├── assets/                      # Recursos visuales
│   ├── img/
│   └── deliverables/
├── config/                      # Configuración de compilación
│   └── defaults.yaml
└── build/                       # PDF generado
    └── TB1-Report.pdf
```

---

## 📌 Información del Proyecto

**Versión:** 1.0.0 (TB1)  
**Fecha:** Abril 2026  
**Equipo:** WebStone (5 integrantes)  
**Estado:** ✅ Completado

Ver [registro de versiones completo](report/front-matter/02-version-history.md)

**© 2026 WebStone — KhipuTech**  
Universidad Peruana de Ciencias Aplicadas
