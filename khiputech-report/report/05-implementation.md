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

##### 5.2.2.2. Aspect Leaders and Collaborators

##### 5.2.2.3. Sprint Backlog 2

##### 5.2.2.4. Development Evidence for Sprint Review

##### 5.2.2.5. Execution Evidence for Sprint Review

##### 5.2.2.6. Services Documentation Evidence for Sprint Review

##### 5.2.2.7. Software Deployment Evidence for Sprint Review

##### 5.2.2.8. Team Collaboration Insights during Sprint

---

#### 5.2.3. Sprint 3

##### 5.2.3.1. Sprint Planning 3

##### 5.2.3.2. Aspect Leaders and Collaborators

##### 5.2.3.3. Sprint Backlog 3

##### 5.2.3.4. Development Evidence for Sprint Review

##### 5.2.3.5. Execution Evidence for Sprint Review

##### 5.2.3.6. Services Documentation Evidence for Sprint Review

##### 5.2.3.7. Software Deployment Evidence for Sprint Review

##### 5.2.3.8. Team Collaboration Insights during Sprint

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
