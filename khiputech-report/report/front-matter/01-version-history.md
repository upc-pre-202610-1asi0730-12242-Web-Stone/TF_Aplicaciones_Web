### Registro de Versiones del Informe

#### Tabla de Versiones

| Versión   | Fecha      | Autor(es) Principal(es) | Descripción de Cambios                                                                                                                                                                                                                               |
| --------- | ---------- | ----------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **1.0.0** | 16/04/2026 | Fabian Sandoval         | Avance del Capitulo I y Capitulo IV, Registro de Versiones, Collaboration Insights y Student Outcome                                                                                                                                                 |
| **1.0.0** | 16/04/2026 | Oscar Checa             | Avance del Capitulo III , User Stories y Aplicacion Web                                                                                                                                                                                              |
| **1.0.0** | 16/04/2026 | Winnie Merino           | Avance del Capitulo I y Capitulo II                                                                                                                                                                                                                  |
| **1.0.0** | 16/04/2026 | Luis Huaco              | Avance del Capitulo III y User Stories                                                                                                                                                                                                               |
| **1.0.0** | 16/04/2026 | Andrea Correa           | Avance del Capitulo IV y User Stories                                                                                                                                                                                                                |
| **1.0.1** | 06/05/2026 | Fabian Sandoval         | <ul><li>Mejora del Front- Matter<ul><li>00-Cover = Caratula</li><li>01-version-history = registro de versiones</li><li>02-collaboration-insights = Project Report Collaboration Insights</li><li>03-student-outcome = student outcome</li></ul></li> |
| **1.0.1** | 06/05/2026 | Oscar Checa             | <ul><li>Mejorando User Stories segun los criterios de aceptación de los US</li></ul>                                                                                                                                                                 |
| **1.0.1** | 06/05/2026 | Winnie Merino           | <ul><li>Actualizando:<ul><li>Formato de Resumen de cada entrevista</li><li>Análisis de entrevista del segmento</li><li>Segmentos Objetivos</li></ul></li>                                                                                            |
| **1.0.1** | 06/05/2026 | Luis Huaco              | <ul><li>Mejora del Capitulo I<ul><li>Analisis 5 W y 2 H</li><li>Lean UX Process</li><li>lean UX Hypothesis Statement</li></ul></li></ul>                                                                                                             |
| **1.0.1** | 06/05/2026 | Andrea Correa           | <ul><li>Actualizaciones: <ul><li>proceso needfinding</li><li>Lean UX</li></ul> </li></ul>                                                                                                                                                            |

---

#### Convención de Versionado

Este proyecto sigue **Semantic Versioning (SemVer)**:

```
MAJOR.MINOR.PATCH
|     |     |
|     |     └─ Correcciones menores, typos, ajustes
|     └─────── Nuevas funcionalidades, capítulos adicionales
└───────────── Entregas mayores (TB1, TB2, TF)
```

**Ejemplos:**

- `1.0.0` → AV1 (entrega completa de base)
- `1.0.1` → Corrección de errores post-feedback AV1

---

#### Changelog Detallado

##### v1.0.0 - AV1 (16/04/2026)

**Agregado:**

- ✅ Capítulo I: Introducción (Startup Profile, Solution Profile, Segmentos Objetivo)
- ✅ Capítulo II: Requirements (Competidores, Entrevistas, Needfinding, Event Storming)
- ✅ Capítulo III: Specification (52 User Stories, Impact Mapping, Product Backlog)
- ✅ Capítulo IV: Product Design (Style Guidelines, Wireframes, Arquitectura DDD)
- ✅ General Style Guidelines con logo KhipuTech
- ✅ Web Style Guidelines con componentes UI
- ✅ Estructura Docs-as-Code con Pandoc
- ✅ 2 entrevistas a gestores culturales documentadas
- ✅ Capítulo V: Implementation (Configuration Management, primeros commits)

**Modificado:**

**Eliminado:**

##### v1.0.1 - post-feedback AV1 (06/05/2026)

**Agregado:**

- ✅ Capítulo V: Implementation (Configuration Management, primeros commits)
- ✅ Ubiquitous Language definido

**Modificado:**

- ✅ Capítulo I: Introducción (Startup Profile, Solution Profile, Segmentos Objetivo)
- ✅ Capítulo II: Requirements (Competidores, Entrevistas, Needfinding, Event Storming)
- ✅ Capítulo III: Specification (52 User Stories, Impact Mapping, Product Backlog)
- ✅ Capítulo IV: Product Design (Style Guidelines, Wireframes, Arquitectura DDD)
- ✅ General Style Guidelines con logo KhipuTech
- ✅ Web Style Guidelines con componentes UI
- ✅ Estructura Docs-as-Code con Pandoc
- ✅ 2 entrevistas a gestores culturales documentadas
  **Eliminado:**

#### Proceso de Actualización de Versiones

1. **Desarrollo en rama feature:** Todo cambio se desarrolla en `feature/lastname`
2. **Pull Request:** Se crea PR hacia `develop` con descripción de cambios
3. **Code Review:** Mínimo 2 revisores aprueban cambios
4. **Merge a develop:** Integración en rama de desarrollo
5. **Testing:** Compilación de PDF de prueba con `make pdf`
6. **Merge a main:** Solo para entregas oficiales (TB1, TB2, TF)
7. **Tag de versión:** Se crea tag Git con número de versión (`git tag v1.0.0`)
8. **Actualizar este documento:** Se registra la versión en esta tabla

---

**Última actualización:** 06/05/2026
