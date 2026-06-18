## Capítulo V: Product Implementation, Validation & Deployment

### 5.1. Software Configuration Management

#### 5.1.1. Software Development Environment Configuration

| Producto           | Propósito en el proyecto                                 | Categoría                       | Ruta de descarga / acceso                       | Descripción                                                                                                   |
| ------------------ | -------------------------------------------------------- | ------------------------------- | ----------------------------------------------- | ------------------------------------------------------------------------------------------------------------- |
| HTML5              | Estructura base de las páginas web del sistema.          | Frontend Development            | https://developer.mozilla.org/es/docs/Web/HTML  | Lenguaje de marcado utilizado para definir la estructura y contenido de las páginas web.                      |
| CSS3               | Diseño visual y estilos de la interfaz de usuario.       | Frontend Development            | https://developer.mozilla.org/es/docs/Web/CSS   | Lenguaje utilizado para definir la presentación visual, incluyendo colores, layouts y diseño responsivo.      |
| Vue.js             | Desarrollo de interfaces dinámicas e interactivas.       | Frontend Development            | https://vuejs.org/guide/introduction.html       | Framework progresivo de JavaScript para construir interfaces de usuario de forma eficiente.                   |
| JetBrains WebStorm | Desarrollo y edición del código del frontend.            | Software Development            | https://www.jetbrains.com/webstorm/             | IDE especializado en desarrollo web con soporte para JavaScript, TypeScript y frameworks modernos.            |
| Git CLI (Git)      | Control de versiones y gestión de cambios en el código.  | Version Control                 | https://git-scm.com/                            | Sistema de control de versiones distribuido que permite trabajar con ramas y mantener historial del proyecto. |
| GitHub             | Almacenamiento y trabajo colaborativo del código fuente. | Collaboration & Version Control | https://github.com/                             | Plataforma para alojar repositorios, gestionar versiones y colaborar en equipo.                               |
| MySQL Workbench    | Diseño y gestión de la base de datos del sistema.        | Database Management             | https://dev.mysql.com/downloads/workbench/      | Herramienta visual para modelar bases de datos, ejecutar consultas SQL y administrar servidores MySQL.        |
| Docker Desktop     | Contenerización del sistema para facilitar despliegues.  | DevOps / Containerization       | https://www.docker.com/products/docker-desktop/ | Plataforma que permite crear y ejecutar contenedores, asegurando entornos consistentes.                       |
| Swagger UI         | Documentación y prueba de la API del sistema.            | API Documentation               | https://swagger.io/tools/swagger-ui/            | Herramienta que permite visualizar y probar endpoints de APIs REST de forma interactiva.                      |
| Structurizr        | Modelado de arquitectura basado en C4.                   | Software Architecture           | https://structurizr.com/                        | Herramienta para documentar y visualizar la arquitectura del sistema mediante el modelo C4.                   |
| UXPressia          | Diseño de experiencia de usuario (journeys y personas).  | UX/UI Design                    | https://uxpressia.com/                          | Plataforma para crear mapas de experiencia del usuario y analizar interacciones.                              |

#### 5.1.2. Source Code Management

El proyecto KhipuTech, desarrollado por el startup WebStone, consiste en una plataforma SaaS orientada a la analítica de flujo de visitantes y la gestión de contenido interactivo en museos y centros culturales. Este sistema se construye bajo un enfoque profesional que prioriza buenas prácticas de desarrollo, trabajo colaborativo y una arquitectura escalable, permitiendo integrar componentes de software con dispositivos IoT de bajo costo.

La configuración del entorno de desarrollo se basa en principios de separación de responsabilidades y modularidad, tomando como referencia el modelo C4 (Context, Container, Component, Code). Esto permite estructurar el sistema en diferentes capas, facilitando su mantenimiento, evolución y comprensión por parte del equipo. Asimismo, se busca garantizar la escalabilidad del proyecto, considerando futuras integraciones con sensores y servicios en tiempo real.

Para el desarrollo frontend, el equipo utiliza WebStorm como entorno principal, lo que permite mantener una configuración homogénea entre los integrantes. Este IDE ofrece soporte completo para tecnologías web modernas y facilita tareas como la navegación del código, depuración, refactorización y gestión de dependencias. Además, se integra de manera eficiente con Vue.js, framework seleccionado para la construcción de la interfaz de usuario.

El uso de Vue.js permite desarrollar una interfaz dinámica basada en componentes reutilizables, favoreciendo una arquitectura modular. Gracias a su enfoque reactivo, se logra una mejor gestión del estado de la aplicación y una experiencia de usuario más fluida. Esta estructura también facilita el trabajo paralelo del equipo, permitiendo dividir responsabilidades sin afectar la coherencia del sistema.

En cuanto al control de versiones y colaboración, el equipo utiliza Git junto con GitHub, lo que permite gestionar cambios, trabajar con ramas y mantener un historial organizado del desarrollo. El repositorio principal del proyecto se encuentra disponible en el siguiente enlace:
https://github.com/upc-pre-202610-1asi0730-12242-Web-Stone/TF_Aplicaciones_Web.git

Este repositorio funciona como el núcleo del desarrollo colaborativo, donde se integran los avances del equipo y se gestionan las diferentes versiones del sistema. A través de este enfoque, KhipuTech asegura un flujo de trabajo ordenado, controlado y alineado con las necesidades del proyecto, permitiendo validar funcionalidades antes de su implementación final.

#### 5.1.3. Source Code Style Guide & Conventions

El uso de un estilo de código unificado y una arquitectura bien definida es clave para asegurar la escalabilidad, la mantenibilidad y la colaboración efectiva en el desarrollo de KhipuTech. Para ello, el proyecto incorpora prácticas de programación y convenciones estructurales que promueven la calidad técnica, la claridad y la consistencia en cada módulo del sistema, tomando como referencia estándares reconocidos de la industria.

En cuanto a la arquitectura, KhipuTech adopta el modelo C4, lo que permite visualizar el sistema en distintos niveles de abstracción, facilitando la comprensión de su estructura y funcionamiento. Asimismo, se basa en principios de Clean Architecture y Domain-Driven Design, lo que permite mantener una separación clara entre las distintas capas del sistema, reduciendo el acoplamiento y mejorando la mantenibilidad del código.

Para el desarrollo del frontend, se emplea Vue.js como framework principal, permitiendo la construcción de interfaces dinámicas basadas en componentes reutilizables. La estructura del proyecto se organiza en directorios como components, views y store, lo que facilita la modularidad del sistema. Además, se siguen convenciones de nomenclatura como el uso de PascalCase para componentes y kebab-case para archivos, en línea con las buenas prácticas recomendadas por la comunidad.

En relación con el control de versiones, el proyecto utiliza Git y GitHub para gestionar los cambios en el código fuente, permitiendo trabajar de manera colaborativa mediante el uso de ramas y manteniendo un historial organizado del desarrollo.

Finalmente, se emplean herramientas como WebStorm para el desarrollo del frontend, Docker para la contenerización del sistema, MySQL Workbench para la gestión de la base de datos y Swagger UI para la documentación de APIs. Estas herramientas contribuyen a mantener un flujo de trabajo ordenado, eficiente y alineado con prácticas profesionales de desarrollo de software.

#### 5.1.4. Software Deployment Configuration

Para gestionar el desarrollo de KhipuTech de manera colaborativa, el equipo utilizó la funcionalidad de forks en GitHub. Cada integrante creó una copia del repositorio principal en su cuenta personal, lo que permitió trabajar de forma independiente en nuevas funcionalidades o pruebas sin afectar el código base.

Este enfoque permitió mantener la estabilidad del repositorio principal, al mismo tiempo que facilitó la organización del trabajo en equipo y la validación de cambios antes de su integración final.

### 5.2. Landing Page, Services & Applications Implementation

#### 5.2.1. Sprint 1

##### 5.2.1.1. Sprint Planning 1

##### 5.2.1.2. Aspect Leaders and Collaborators

##### 5.2.1.3. Sprint Backlog 1

##### 5.2.1.4. Development Evidence for Sprint Review

##### 5.2.1.5. Execution Evidence for Sprint Review

##### 5.2.1.6. Services Documentation Evidence for Sprint Review

##### 5.2.1.7. Software Deployment Evidence for Sprint Review

##### 5.2.1.8. Team Collaboration Insights during Sprint

---

#### 5.2.2. Sprint 2

##### 5.2.2.1. Sprint Planning 2

### **Sprint Planning Background**

| Campo           | Detalle                                                                                                                                   |
| :-------------- | :---------------------------------------------------------------------------------------------------------------------------------------- |
| **Sprint #**    | Sprint 2                                                                                                                                  |
| **Date**        | 2026-05-11                                                                                                                                |
| **Time**        | 23:00                                                                                                                                     |
| **Location**    | Google Meet (Virtual)                                                                                                                     |
| **Prepared By** | Sandoval Cueto, Fabian                                                                                                                    |
| **Attendees**   | Sandoval Cueto, Fabian / Huaco Oliva, Luis Alonso / Checa Burga, Oscar Diego / Correa Rodriguez, Andrea Khristina / Winnie Lisbeth Merino |

---

### **Sprint Review & Retrospective Summary**

| Campo                              | Detalle                                                                                                                                                                                        |
| :--------------------------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Sprint 1 Review Summary**        | Se finalizaron con éxito los entregables de diseño y validación: Landing Page (WO), Event Storming (FS), Mockups y User Flows (OB), e Inteligencia de Usuario con Entrevistas (LH).            |
| **Sprint 1 Retrospective Summary** | El equipo logró consolidar el Event Storming y establecer los Bounded Contexts. Se detectó la necesidad de refactorizar la lógica de negocio para distinguir entre Museos Privados y Públicos. |

---

### **Sprint Goal & User Stories**

| Campo                   | Detalle                                                                                                                           |
| :---------------------- | :-------------------------------------------------------------------------------------------------------------------------------- |
| **Sprint 2 Goal**       | Desarrollar las capacidades de análisis de engagement (US13), implementación de I18N (US04) y el monitoreo de interacción (US21). |
| **Sprint 2 Velocity**   | 25 Story Points                                                                                                                   |
| **Sum of Story Points** | 20 Story Points                                                                                                                   |

#### **User Stories Incluidas:**

- **US04 (WO):** Selección de idioma del contenido (I18N).
- **US13 (Admin):** Detección de obras con poco interés para toma de decisiones (Ranking de engagement).
- **US21 (Gestor):** Monitoreo de interacción con contenido digital.
- **US37 (AR):** Sugerencias de recorrido personalizadas para visitantes.

##### 5.2.2.2. Aspect Leaders and Collaborators

##### 5.2.2.3. Sprint Backlog 2

## **Sprint Backlog 2**

El objetivo principal de este Sprint es consolidar la arquitectura de software mediante la implementación de los **Bounded Contexts** y el desarrollo de funcionalidades críticas de personalización. Esto incluye la gestión multi-idioma (I18N), el sistema de ranking de engagement para la toma de decisiones administrativas y el monitoreo de la interacción digital de los visitantes.

d
| User Story | | Work-Item / Task | | | | | |
| :--------- | :------------------------------ | :--------------- | :--------------------------- | :------------------------------------------------------------------------- | :--------------------- | :------------------- | :----------- |
| **Id** | **Title** | **Id** | **Title** | **Description** | **Estimation (Hours)** | **Assigned To** | **Status** |
| US04 | Idioma del contenido | T3 | I18N implementation | Implementación técnica de librerías para soporte multi-idioma. | 6 | Winnie Merino (WO) | Doing |
| US13 | Detectar obras con poco interés | T1 | Implement engagement ranking | Desarrollar la lógica de backend para clasificar obras por interacción. | 8 | Oscar Checa (OB) | Stories Task |
| US13 | Detectar obras con poco interés | T2 | Apply filter button | Crear interfaz de filtrado en el dashboard administrativo para el ranking. | 4 | Oscar Checa (OB) | Stories Task |
| US37 | Sugerencias de recorrido | T1 | Routing logic | Definir algoritmos de sugerencia basados en la ubicación y flujo. | 8 | Andrea Correa (AR) | Stories Task |
| N/A | Refactor General | T1 | Refactor Private/Public | Reestructuración de la lógica de negocio para diferenciar tipos de museo. | 10 | Fabian Sandoval (FS) | To-do |
| N/A | Infraestructura | T2 | Firebase Routing | Configuración de rutas y navegación dentro de la plataforma Firebase. | 4 | Oscar Checa (OB) | To-do |

##### 5.2.2.4. Development Evidence for Sprint Review

##### 5.2.2.5. Execution Evidence for Sprint Review

Durante este Sprint, el equipo logró consolidar la arquitectura del sistema mediante la definición técnica de los **Bounded Contexts** y la evolución del **Event Storming** hacia un nivel de diseño funcional. En términos de desarrollo, se implementaron las bases para la personalización y análisis de datos, logrando los siguientes hitos:

- **Gestión Multi-idioma (I18N):** Se inició la implementación técnica para permitir al usuario elegir el idioma del contenido de forma variada (US04).
- **Análisis de Engagement:** Se desarrolló la lógica de backend y el filtrado para el ranking de obras basado en la interacción, permitiendo detectar piezas de poco interés para decisiones administrativas (US13).
- **Monitoreo de Interacción:** Se trabajó en la capacidad de supervisar cómo los visitantes interactúan con el contenido digital para mejorar la experiencia de usuario (US21).
- **Infraestructura y Navegación:** Se configuró el enrutamiento mediante Firebase y se realizó una refactorización de la lógica para diferenciar entre museos públicos y privados.
- **Validación y Diseño:** Se finalizaron los mockups, flujos de usuario y las entrevistas al segundo segmento objetivo para refinar las sugerencias de recorrido (US37).

![landing 1](/khiputech-report/assets/img/4_3_2-Landing-Mock-up/landing-page-1.jpeg)

![landing 2](/khiputech-report/assets/img/4_3_2-Landing-Mock-up/landing-page-2.jpeg)

![landing 3](/khiputech-report/assets/img/4_3_2-Landing-Mock-up/landing-page-3.jpeg)

![landing 4](/khiputech-report/assets/img/4_3_2-Landing-Mock-up/landing-page-4.jpeg)

![landing 5](/khiputech-report/assets/img/4_3_2-Landing-Mock-up/landing-page-5.jpeg)

![app web 1](/khiputech-report/assets/img/images/web-13.jpeg)

![app web 2](/khiputech-report/assets/img/images/web-2.jpeg)

![app web 3](/khiputech-report/assets/img/images/web-3.jpeg)

![app web 4](/khiputech-report/assets/img/images/web-4.jpeg)

![app web 5](/khiputech-report/assets/img/images/web-5.jpeg)

![app web 6](/khiputech-report/assets/img/images/web-6.jpeg)

![app web 7](/khiputech-report/assets/img/images/web-7.jpeg)

![app web 8](/khiputech-report/assets/img/images/web-8.jpeg)

![app web 9](/khiputech-report/assets/img/images/web-9.jpeg)

![app web 10](/khiputech-report/assets/img/images/web-10.jpeg)

![app web 11](/khiputech-report/assets/img/images/web-11.jpeg)

![app web 12](/khiputech-report/assets/img/images/web-12.jpeg)

##### 5.2.2.6. Services Documentation Evidence for Sprint Review

##### 5.2.2.7. Software Deployment Evidence for Sprint Review

##### 5.2.2.8. Team Collaboration Insights during Sprint

![github-pulse-sprint-2](../assets/img/0_01-collaboration-insights/01-AV1/01-github-pulse-sprint-2.png)

![github-network-sprint-2](../assets/img/0_01-collaboration-insights/01-AV1/02-github-network-sprint-2.png)

---

#### 5.2.3. Sprint 3

##### 5.2.3.1. Sprint Planning 3

### **Sprint Planning Background**

| Campo           | Detalle                                                                                                                                   |
| :-------------- | :---------------------------------------------------------------------------------------------------------------------------------------- |
| **Sprint #**    | Sprint 3:Our focus is on delivering the first version of the KhipuTech backend API across all five bounded contexts. We believe it delivers real-time museum management capabilities — including visitor capacity control, artwork maintenance tracking, QR content access and operational recommendations — to museum administrators, curators and visitors. This will be confirmed when all five bounded context endpoints (OPE, MAI, VIS, CAP, ANA) are deployed, accessible via Swagger, and the frontend and landing page reflect the latest updates.                                                                                                                                   |
| **Date**        | 2026-06-17                                                                                                                                |
| **Time**        | 23:00                                                                                                                                     |
| **Location**    | Google Meet (Virtual)                                                                                                                     |
| **Prepared By** | Sandoval Cueto, Fabian                                                                                                                    |
| **Attendees**   | Sandoval Cueto, Fabian / Huaco Oliva, Luis Alonso / Checa Burga, Oscar Diego / Correa Rodriguez, Andrea Khristina / Merino Ordinola, Winnie Lisbeth |

---

### **Sprint Review & Retrospective Summary**

| Campo                              | Detalle                                                                                                                                                                                                          |
| :--------------------------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Sprint 2 Review Summary**        | Se finalizaron los artefactos de diseño, la primera versión del frontend Web Application y la Landing Page actualizada. Se definió la arquitectura DDD con los bounded contexts del sistema.                     |
| **Sprint 2 Retrospective Summary** | El equipo identificó la necesidad de distribuir mejor las responsabilidades del backend por bounded context. Se acordó que cada integrante sería líder de un BC para el Sprint 3.                               |

---

### **Sprint Goal & User Stories**

| Campo                   | Detalle                                                                                                                                                                                                          |
| :---------------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Sprint 3 Goal**       | Our focus is on delivering the first version of the backend RESTful API for KhipuTech. We believe it delivers core museum management capabilities to administrators and curators. This will be confirmed when the endpoints for Operation, Maintenance, Visiting, Capacity and Analytics bounded contexts are deployed and accessible via Swagger. |
| **Sprint 3 Velocity**   | 30 Story Points                                                                                                                                                                                                  |
| **Sum of Story Points** | 28 Story Points                                                                                                                                                                                                  |

##### 5.2.3.2. Aspect Leaders and Collaborators

En este Sprint, el equipo organizó su trabajo en torno a los cinco bounded contexts del backend de KhipuTech. Cada integrante asumió el liderazgo de un bounded context específico, siendo responsable de su implementación completa bajo la arquitectura DDD, mientras colaboraba en los demás aspectos según se requiriera.

| Team Member<br>(Last Name, First Name) | GitHub Username | Operation | Maintenance | Visiting | Capacity | Analytics |
| :--- | :--- | :---: | :---: | :---: | :---: | :---: |
| Sandoval Cueto, Fabian | JFabianSandoval | **L** | C | C | | |
| Huaco Oliva, Luis Alonso | perghormaru-pixel | C | **L** | | C | C |
| Checa Burga, Oscar Diego | OscarCheca | | C | | | **L** |
| Correa Rodriguez, Andrea Khristina | Daiko-07 | C | | **L** | | C |
| Merino Ordinola, Winnie Lisbeth | winniemerino | | | C | **L** | |

##### 5.2.3.3. Sprint Backlog 3

El objetivo principal de este Sprint es implementar la primera versión del backend RESTful de KhipuTech, organizado bajo los cinco bounded contexts definidos en la arquitectura DDD: Operation (OPE), Maintenance (MAI), Visiting (VIS), Capacity (CAP) y Analytics (ANA). Cada integrante del equipo lideró su bounded context asignado.

![foto-1-sprint-backlog-jira](../assets/img/5_2_3_3-sprint-backlog-3/)

> **[FOTO 1]** Captura del tablero de Sprint 3 en Jira mostrando las columnas Goal → Stories → Task Stories → To-Do → In-Process → To-Review → To-Fix → Done con las tarjetas distribuidas. Tomar screenshot completo del board en Jira con el sprint activo.

URL del board en Jira: [colocar URL público del board]

| User Story | | Work-Item / Task | | | | | |
| :--------- | :------------------------------------- | :--------------- | :------------------------------------------- | :------------------------------------------------------------------------- | :--------------------- | :------------------- | :----------- |
| **Id** | **Title** | **Id** | **Title** | **Description** | **Estimation (Hours)** | **Assigned To** | **Status** |
| TS-OPE-US26-01 | GET /recommendations/operations | SCRUM-258 | OperationRecommendation model in database | Definición del aggregate y configuración EF Core para recomendaciones operativas. | 4 | Sandoval Cueto, Fabian | Done |
| TS-OPE-US26-02 | GET /recommendations/operations | SCRUM-259 | GET /recommendations/operations endpoint | Implementación del endpoint bajo arquitectura DDD con Query/Handler/Repository. | 6 | Sandoval Cueto, Fabian | Done |
| TS-OPE-US26-03 | GET /recommendations/operations | SCRUM-260 | AppDbContext update for OPE | Registro del DbSet y ApplyOperationConfiguration en el AppDbContext compartido. | 2 | Sandoval Cueto, Fabian | Done |
| TS-OPE-US26-04 | GET /recommendations/operations | SCRUM-261 | Swagger documentation for OPE endpoint | Documentación del endpoint con SwaggerOperation, ProducesResponseType y ejemplos. | 2 | Sandoval Cueto, Fabian | Done |
| TS-MAI-USMA-01 | Schedule artwork maintenance | SCRUM-262 | MaintenanceSchedule model and migration | Modelo de programación de mantenimiento con fechas y FK a Artwork. | 5 | Huaco Oliva, Luis Alonso | Done |
| TS-MAI-USMA-02 | Schedule artwork maintenance | SCRUM-263 | POST /maintenance endpoint | Endpoint para crear programaciones de mantenimiento. | 5 | Huaco Oliva, Luis Alonso | Done |
| TS-MAI-USMA-03 | Schedule artwork maintenance | SCRUM-264 | Database update and release | Actualización de la base de datos con tablas de mantenimiento y release del proyecto. | 4 | Huaco Oliva, Luis Alonso | Done |
| TS-VIS-US01-01 | GET /artifacts/{qr_id} | SCRUM-265 | Artwork model in database | Creación y migración del modelo de base de datos para obras de arte. | 6 | Correa Rodriguez, Andrea | Done |
| TS-VIS-US01-02 | GET /artifacts/{qr_id} | SCRUM-266 | GET /artifacts/{qr_id} endpoint | Endpoint para retornar contenido de obra mediante QR bajo arquitectura DDD. | 8 | Correa Rodriguez, Andrea | Done |
| TS-VIS-US01-03 | GET /artifacts/{qr_id} | SCRUM-267 | Unit and integration testing | Pruebas unitarias y de integración del endpoint de obras. | 4 | Correa Rodriguez, Andrea | Done |
| TS-VIS-US01-04 | GET /artifacts/{qr_id} | SCRUM-268 | Swagger documentation for VIS endpoint | Documentación técnica del endpoint con Swagger. | 2 | Correa Rodriguez, Andrea | Done |
| TS-CAP-US22-01 | GET /rooms/capacity | SCRUM-269 | RoomCapacity model | Definición del modelo con sala, capacidad máxima y contador actual. | 6 | Merino Ordinola, Winnie | Done |
| TS-CAP-US22-02 | GET /rooms/capacity | SCRUM-270 | GET /rooms/capacity endpoint | Endpoint para consultar el estado de capacidad de salas en tiempo real. | 6 | Merino Ordinola, Winnie | Done |
| TS-CAP-US22-03 | GET /rooms/capacity | SCRUM-271 | Alert trigger logic | Lógica de disparo de alerta cuando contador >= aforo máximo. | 4 | Merino Ordinola, Winnie | Done |
| TS-CAP-US22-04 | GET /rooms/capacity | SCRUM-272 | Swagger documentation for CAP endpoints | Documentación formal de endpoints de capacidad en Swagger. | 2 | Merino Ordinola, Winnie | Done |
| TS-ANA-US15-01 | GET /dashboard/metrics | SCRUM-273 | ArtworkStat and VisitorStat models | Definición de agregados de estadísticas para el dashboard analítico. | 5 | Checa Burga, Oscar | Done |
| TS-ANA-US15-02 | GET /dashboard/metrics | SCRUM-274 | GET /dashboard/metrics endpoint | Endpoint de métricas con agregación por obra y sala. | 6 | Checa Burga, Oscar | Done |
| TS-ANA-US15-03 | GET /dashboard/metrics | SCRUM-275 | Frontend updates for analytics | Actualización del frontend para consumir los endpoints del dashboard. | 5 | Checa Burga, Oscar | Done |

##### 5.2.3.4. Development Evidence for Sprint Review

En este Sprint se implementó la primera versión del backend RESTful de KhipuTech. Los commits corresponden a los cinco bounded contexts desarrollados bajo arquitectura DDD en el repositorio de Web Services.

| Repository | Branch | Commit Id | Commit Message | Commit Message Body | Committed on (Date) |
| :--------- | :----- | :-------- | :------------- | :------------------ | :------------------ |
| khiputech-platform | feature/get-recommendations-operations | a1b2c3d | feat(operation): add get recommendations operations endpoint | Implementa GET /recommendations/operations con estructura DDD completa (Domain, Application, Infrastructure, Interfaces) | 2026-06-17 |
| khiputech-platform | feature/get-recommendations-operations | e4f5g6h | feat(shared): update AppDbContext to register OperationRecommendation DbSet and apply operation configuration | Agrega DbSet<OperationRecommendation> y descomenta ApplyOperationConfiguration() | 2026-06-17 |
| khiputech-platform | feature/post-maintenance | i7j8k9l | feat(maintenance): add schedule maintenance endpoint | Implementa POST /maintenance con modelo MaintenanceSchedule y lógica de bloqueo QR | 2026-06-17 |
| khiputech-platform | feature/get-artifact-by-qr | m1n2o3p | feat(visiting): add get artifact by qr endpoint | Implementa GET /artifacts/{qr_id} con modelo Artwork y repositorio DDD | 2026-06-17 |
| khiputech-platform | feature/get-rooms-capacity | q4r5s6t | feat(capacity): add get rooms capacity endpoint | Implementa GET /rooms/capacity con modelo RoomCapacity y lógica de alertas | 2026-06-17 |
| khiputech-platform | feature/get-dashboard-metrics | u7v8w9x | feat(analytics): add get dashboard metrics endpoint | Implementa GET /dashboard/metrics con agregados ArtworkStat y VisitorStat | 2026-06-17 |
| khiputech-platform | develop | y1z2a3b | feat(shared): update AppDbContext with all bounded context configurations | Activa ApplyCapacityConfiguration, ApplyMaintenanceConfiguration en OnModelCreating | 2026-06-17 |
| TF_Aplicaciones_Web (frontend) | develop | c4d5e6f | fix(frontend): update routing and responsive fixes | Corrige routing SPA y breakpoints de dispositivos móviles | 2026-06-17 |
| TF_Aplicaciones_Web (landing) | develop | g7h8i9j | fix(landing): optimize images and update QR redirect | Optimización de imágenes y corrección de URL de redirección QR | 2026-06-17 |

> **Nota:** Reemplazar los Commit Ids con los IDs reales obtenidos desde GitHub (primeros 7 caracteres del hash de cada commit).

##### 5.2.3.5. Execution Evidence for Sprint Review

En este Sprint se desplegó la primera versión del backend RESTful de KhipuTech. Los cinco bounded contexts (OPE, MAI, VIS, CAP, ANA) fueron implementados bajo arquitectura DDD y expuestos como endpoints REST documentados en Swagger. Adicionalmente se realizaron correcciones en el frontend y la landing page.

![foto-2-swagger-ui-general](../assets/img/5_2_3_3-sprint-backlog-3/foto-2-swagger-ui-general.jpg)

> **[FOTO 2]** Captura de la interfaz de Swagger UI mostrando todos los endpoints disponibles del backend agrupados por bounded context (Operation, Maintenance, Visiting, Capacity, Analytics). Acceder a `https://localhost:{puerto}/swagger` con el proyecto corriendo y tomar screenshot del listado completo de endpoints.

![foto-3-endpoint-operation-alerts]

> **[FOTO 3]** Captura de Swagger UI mostrando el endpoint `GET /api/v1/operation/alerts` expandido con su descripción, parámetros y respuesta de ejemplo. Hacer clic en el endpoint para expandirlo y ejecutar una prueba con "Try it out".

##### 5.2.3.6. Services Documentation Evidence for Sprint Review

En este Sprint se documentaron los endpoints del backend de KhipuTech utilizando OpenAPI Specification a través de Swagger. A continuación se presenta la relación de endpoints implementados y documentados durante el Sprint 3.

| Bounded Context | Endpoint | HTTP Verb | Descripción | Parámetros | Response ejemplo |
| :-------------- | :------- | :-------- | :---------- | :--------- | :--------------- |
| Operation (OPE) | /api/v1/recommendations | GET | Retorna lista de recomendaciones operativas basadas en métricas actuales del museo | Ninguno | `[{"id":1,"roomName":"Sala A","issue":"Ocupación > 80%","suggestedAction":"Redistribuir visitantes","generatedAt":"2026-06-17T23:00:00Z"}]` |
| Operation (OPE) | /api/v1/operation/alerts/active | GET | Retorna alertas activas del sistema | Ninguno | `[{"id":1,"roomName":"Sala B","type":"critica","message":"Aforo superado","status":"active"}]` |
| Operation (OPE) | /api/v1/operation/configuration | GET | Retorna la configuración de umbrales de alerta | Ninguno | `{"moderateThreshold":80,"criticalThreshold":100,"notifyEmail":true}` |
| Maintenance (MAI) | /api/v1/maintenance | POST | Crea una programación de mantenimiento para una obra | Body: `{artworkId, startDate, endDate, reason}` | `{"id":1,"artworkId":5,"startDate":"2026-06-20","endDate":"2026-06-25","status":"scheduled"}` |
| Maintenance (MAI) | /api/v1/maintenance | GET | Lista mantenimientos activos y futuros | Ninguno | `[{"id":1,"artworkId":5,"startDate":"2026-06-20","status":"scheduled"}]` |
| Visiting (VIS) | /api/v1/artifacts/{qr_id} | GET | Retorna contenido digital de una obra mediante su código QR | Path: `qr_id` (string) | `{"id":1,"title":"La Última Cena","artist":"Da Vinci","description":"...","mediaUrls":["..."]}` |
| Capacity (CAP) | /api/v1/rooms/capacity | GET | Retorna estado de capacidad de todas las salas en tiempo real | Ninguno | `[{"roomName":"Sala A","maxCapacity":50,"currentCount":42,"occupancyRate":84}]` |
| Analytics (ANA) | /api/v1/dashboard/metrics | GET | Retorna métricas agregadas del dashboard (visitas, ranking, engagement) | Ninguno | `{"totalVisits":1250,"topArtwork":"La Última Cena","avgDwellTime":180}` |

URL del repositorio de Web Services: https://github.com/upc-pre-202610-1asi0730-12242-Web-Stone/khiputech-platform

##### 5.2.3.7. Software Deployment Evidence for Sprint Review

Durante este Sprint se realizó el primer despliegue del backend de KhipuTech como Web Service RESTful. A continuación se describen las actividades realizadas para el despliegue de los tres productos: Landing Page, Web Application y Web Services.

**Web Services (Backend)**

El backend fue desarrollado con ASP.NET Core (.NET 10) y desplegado con conexión a una base de datos MySQL. El proceso de despliegue incluyó la configuración del entorno, la ejecución de migraciones de Entity Framework Core y la verificación de endpoints mediante Swagger UI.

![foto-9-mysql-tables](../assets/img/5_2_3_3-sprint-backlog-3/foto-9-mysql-tables.png)

> **[FOTO 9]** Captura de MySQL Workbench mostrando las tablas creadas por las migraciones de EF Core: `operation_recommendations`, `alerts`, `alert_configurations`, `maintenance_schedules`, `artworks`, entre otras. Abrir MySQL Workbench, conectarse a la BD y expandir el schema de KhipuTech.

##### 5.2.3.8. Team Collaboration Insights during Sprint

Durante el Sprint 3, el equipo mantuvo una colaboración activa en los repositorios de GitHub. Cada integrante realizó commits en su bounded context asignado, siguiendo las convenciones de Conventional Commits y el flujo GitFlow con feature branches individuales por endpoint.

![foto-12-github-contributors](../assets/img/5_2_3_3-sprint-backlog-3/foto-12-github-contributors.png)

> **[FOTO 12]** Captura de la pestaña "Contributors" o "Insights > Contributors" del repositorio `khiputech-platform` en GitHub, mostrando el gráfico de contribuciones por integrante con número de commits. Ir a https://github.com/upc-pre-202610-1asi0730-12242-Web-Stone/khiputech-platform > pestaña "Insights" > "Contributors" y tomar screenshot.

![foto-13-github-network](../assets/img/5_2_3_3-sprint-backlog-3/foto-13-github-network.png)

> **[FOTO 13]** Captura del gráfico de red (Network graph) del repositorio mostrando los feature branches de cada bounded context confluyendo hacia develop. Ir a GitHub > repositorio khiputech-platform > "Insights" > "Network" y tomar screenshot del grafo con los branches visibles.
---

#### 5.2.4. Sprint 4

##### 5.2.4.1. Sprint Planning 4

##### 5.2.4.2. Aspect Leaders and Collaborators

##### 5.2.4.3. Sprint Backlog 4

##### 5.2.4.4. Development Evidence for Sprint Review

##### 5.2.4.5. Execution Evidence for Sprint Review

##### 5.2.4.6. Services Documentation Evidence for Sprint Review

##### 5.2.4.7. Software Deployment Evidence for Sprint Review

##### 5.2.4.8. Team Collaboration Insights during Sprint

---

#### 5.3. Validation Interviews

##### 5.3.1. Diseño de entrevistas

##### 5.3.2. Registro de entrevistas

##### 5.3.3. Evaluaciones según heurísticas

### 5.4. Video About-the-Product

---

---