### Registro de Versiones del Informe

Este documento mantiene un historial de todas las versiones del informe, siguiendo versionado semántico (SemVer).

---

#### Tabla de Versiones

| Versión   | Fecha       | Autor(es) Principal(es)                                                                                         | Descripción de Cambios                                                                                                                                                                                                                                             | Estado        |
| --------- | ----------- | --------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------- |
| **1.0.0** | 11/04/2026  | <ul><li>Fabian Sandoval</li><li>Oscar Checa</li><li>Winnie Merino</li><li>Luis Huaco</li><li>Andrea Correa</li> | **AV1 - Primera Entrega Completa**<br>• Capítulos I-V documentados<br>• 52 User Stories especificadas<br>• Wireframes de 3 aplicaciones<br>• Arquitectura DDD con 4 Bounded Contexts<br>• General & Web Style Guidelines<br>• Event Storming y Ubiquitous Language | ✅ Completado |
| **1.1.0** | [Pendiente] | Equipo WebStone                                                                                                 | **TP - Entrega Parcial**<br>• Sprints 2-4 completados<br>•Landing Page desplegada <br>• Testing completo y documentado<br>• Video About-the-Product                                                                                                                | 🚧 Pendiente  |
| **2.0.0** | [Pendiente] | Equipo WebStone                                                                                                 | **AV2 - Segunda Entrega**<br>• Sprint 1 implementado<br>• Aplicación desplegada<br>• Primeros componentes del Dashboard<br>• Validation Interviews registradas                                                                                                     | 🚧 Pendiente  |

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
- `1.0.1` → Corrección de errores post-feedback TB1
- `1.1.0` → TP1 (entrega parcial)
- `2.0.0` → AV2 (entrega segundo avance con cambios mayores)

---

#### Changelog Detallado

##### v1.0.0 - AV1 (23/04/2026)

**Agregado:**

- ✅ Capítulo I: Introducción (Startup Profile, Solution Profile, Segmentos Objetivo)
- ✅ Capítulo II: Requirements (Competidores, Entrevistas, Needfinding, Event Storming)
- ✅ Capítulo III: Specification (52 User Stories, Impact Mapping, Product Backlog)
- ✅ Capítulo IV: Product Design (Style Guidelines, Wireframes, Arquitectura DDD)
- ✅ Capítulo V: Implementation (Configuration Management, primeros commits)
- ✅ General Style Guidelines con logo KhipuTech
- ✅ Web Style Guidelines con componentes UI
- ✅ Estructura Docs-as-Code con Pandoc
- ✅ 2 entrevistas a gestores culturales documentadas
- ✅ Ubiquitous Language definido
- ✅ Sprint 1 Planning y Retrospective

**Modificado:**

- N/A (primera versión)

**Eliminado:**

- N/A (primera versión)

---

##### v1.1.0 - TP (Pendiente)

**Agregado (planeado):**

- 🚧 Landing Page HTML/CSS/JS desplegada
- 🚧 Primeros componentes React del Dashboard
- 🚧 Validation Interviews (3-5 usuarios)
- 🚧 Heuristic Evaluation

**Modificado (planeado):**

- 🚧 User Stories refinadas según feedback
- 🚧 Wireframes ajustados post-validación

---

##### v2.0.0 - AV2 (Pendiente)

**Agregado (planeado):**

- 🚧 Sprints 2, 3 y 4 completados
- 🚧 Aplicación completa funcionando (Frontend + Backend + IoT)
- 🚧 Testing completo (Unit, Integration, E2E)
- 🚧 Video About-the-Product
- 🚧 Deployment en producción

**Modificado (planeado):**

- 🚧 Arquitectura ajustada según implementación real
- 🚧 Database Design optimizado

---

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

**Última actualización:** 23/04/2026  
**Próxima entrega:** TP (Martes 12 Abril - 09:00:00)
