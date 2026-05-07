## Capítulo I: Introducción

### 1.1. **Startup Profile.**

#### 1.1.1. Descripción del startup

KhipuTech es una startup tecnológica dedicada a la transformación digital de la experiencia museística y cultural. Se desarrolla soluciones híbridas que integran infraestructura IoT de bajo costo con plataformas web dinámicas, permitiendo a los gestores culturales obtener métricas precisas sobre el comportamiento del visitante en tiempo real.

El modelo de negocio de KhipuTech se basa en la optimización del flujo interno de los recintos a través de sensores automatizados, superando las limitaciones de los métodos tradicionales de conteo manual. Simultáneamente, la compañía facilita el acceso a experiencias de contenido exclusivas mediante tecnologías de interacción móvil inmediata como QR y NFC. Al convertir al visitante en un participante activo, KhipuTech no solo enriquece la visita cultural, sino que también dota a las instituciones de datos estratégicos de permanencia e interés, optimizando la gestión de recursos y mejorando el engagement entre las obras y su audiencia.

Con un enfoque en la viabilidad económica y la escalabilidad tecnológica, KhipuTech redefine la relación entre el patrimonio histórico y las herramientas digitales del siglo XXI.

#### Misión:

Empoderar a las instituciones culturales mediante tecnología accesible para transformar el flujo de visitantes en datos estratégicos, enriqueciendo la conexión entre las personas y el patrimonio a través de experiencias digitales exclusivas y seguras

#### Visión:

Convertirnos en el estándar tecnológico de gestión y analítica para museos en Latinoamérica, siendo reconocidos por democratizar el acceso a la inteligencia de datos y por revolucionar la narrativa interactiva en espacios culturales.

#### 1.1.2. Perfiles de los integrantes del equipo

| Nombre                                                                                             | Descripción                                                                                                                                                                                                                                                                                                                                                                          |
| -------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Luis Alonso Huaco Oliva (U202417743) ![](../assets/img/1_1_2-Perfiles/Luis-perfil.jpeg)                                  | Estudiante de Ingeniería de Software interesado en documentación técnica y aseguramiento de calidad. Tiene experiencia en testing de software y redacción de documentación clara para proyectos. Le motiva asegurar que el software funcione correctamente y que esté bien documentado para futuros desarrolladores.                                                                 |
| Fabian Jesus Sandoval Cueto (U20221A132) ![](../assets/img/1_1_2-Perfiles/Fabian-perfil.png)    | Especialista en automatización de procesos mediante n8n e integración de APIs (Meta, Shopify). Aporta experiencia en la configuración de infraestructura en la nube (GCP) y contenedores Docker, además de liderar la estrategia de captación de datos y marketing analítico de la solución.                                                                                         |
| Oscar Diego Checa Burga ![](../assets/img/1_1_2-Perfiles/Oscar-perfil.jpeg)(U20231E492)                                                               | Estudiante de Ingeniería de Software especializado en diseño de experiencia de usuario (UX/UI). Lidero la creación de wireframes, mockups y guías de estilo visual. Manejo herramientas como Figma para prototipado y conocimientos en diseño responsive y accesibilidad web (WCAG). Mi Objetivo es crear experiencias digitales que combinen funcionalidad con negocios de mercado. |
| Andrea Khristina Correa Rodriguez (U202412041)                                                     | Estudiante de Ingeniería de Software con enfoque en análisis de sistemas y arquitectura de software. Tiene conocimientos en modelado de procesos de negocio. Le motiva entender cómo funcionan los sistemas complejos y traducir requisitos en soluciones técnicas efectivas.                                                                                                        |
| Winnie Lisbeth Merino Ordinola(U20231E504) ![](../assets/img/1_1_2-Perfiles/winnie-perfil.jpeg) | Soy estudiante de la carrera de Ingeniería de Software, actualmente en el quinto ciclo. Mis principales destrezas son las habilidades para trabajar en grupo, la creatividad y la investigación. Mi mayor interés es tanto proponer ideas innovadoras que solucionen problemas cercanos en nuestra realidad, como llevarlas a cabo a través del software.                            |

### 1.2. **Solution Profile.**

#### 1.2.1. Antecedentes y Problemática

En el ecosistema cultural actual, los museos enfrentan el reto de modernizar la experiencia del visitante sin perder la esencia de la contemplación artística. Actualmente, la mayoría de los museos medianos y pequeños operan con métodos de conteo manuales (libros de visitas o contadores de mano) y ofrecen información estática (fichas técnicas físicas) que no permite capturar datos sobre el comportamiento del usuario dentro de las salas.

**ANALISIS 5 'W' y 2 'H'**

<table style="width: 100%; border-collapse: collapse;">
  <tr>
    <th style="text-align: center;">Pregunta</th>
    <th style="text-align: center;">Descripción (WebStone - KhipuTech)</th>
  </tr>
  <tr>
    <td style="text-align: center;">What (Qué)</td>
    <td style="text-align: left;">
      En los museos no existe visibilidad en tiempo real del comportamiento del visitante dentro de las salas. 
      Esto genera una gestión basada en suposiciones, con bajo conocimiento del engagement por obra y una 
      experiencia informativa estática y poco interactiva.
    </td>
  </tr>
  <tr>
    <td style="text-align: center;">When (Cuándo)</td>
    <td style="text-align: left;">
      El problema ocurre durante todo el horario de atención, pero se intensifica en horas pico y exhibiciones 
      temporales, donde la falta de datos impide tomar decisiones oportunas sobre flujo, seguridad y distribución de recursos.
    </td>
  </tr>
  <tr>
    <td style="text-align: center;">Where (Dónde)</td>
    <td style="text-align: left;">
      Se presenta dentro de salas de exhibición, pasillos y puntos de transición del museo. 
      El visitante interactúa frente a las obras, mientras que el administrador monitorea desde un 
      dashboard local o remoto.
    </td>
  </tr>
  <tr>
    <td style="text-align: center;">Who (Quién)</td>
    <td style="text-align: left;">
      Administradores, curadores y gestores culturales que necesitan datos para la toma de decisiones, 
      y visitantes (turistas y estudiantes) que buscan experiencias más dinámicas. 
      También intervienen personal de seguridad y marketing.
    </td>
  </tr>
  <tr>
    <td style="text-align: center;">Why (Por qué)</td>
    <td style="text-align: left;">
      • Falta de herramientas accesibles de analítica en tiempo real.<br>
      • Dependencia de métodos manuales o estimaciones.<br>
      • Alto costo de soluciones tradicionales (ej. cámaras con IA).<br>
      • Desconexión entre contenido físico y digital.
    </td>
  </tr>
  <tr>
    <td style="text-align: center;">How (Cómo)</td>
    <td style="text-align: left;">
      • Acceso a contenido digital vía QR/NFC sin instalación.<br>
      • Registro automático de interacciones y permanencia.<br>
      • Sensores de bajo costo para medición de aforo y flujo.<br>
      • Dashboard en tiempo real con métricas y alertas.<br>
      • Plataforma web accesible desde cualquier dispositivo.
    </td>
  </tr>
  <tr>
    <td style="text-align: center;">How much (Cuánto)</td>
    <td style="text-align: left;">
      MVP estimado en ~$500 USD. Modelo basado en pago inicial por hardware (sensores) 
      más suscripción SaaS mensual para acceso al dashboard y analítica. 
      Escalable según número de salas y funcionalidades.
    </td>
  </tr>
</table>

#### 1.2.2. Lean UX Process

##### 1.2.2.1. Lean UX Problem Statements

- El estado actual de la gestión en museos y galerías depende principalmente de **conteos generales de visitantes y contenido informativo estático**, sin visibilidad sobre el comportamiento del usuario dentro de las salas.
- Esto genera una **falta de datos sobre el flujo por sala**, una **baja comprensión del engagement por obra** y una **experiencia limitada para el visitante**, especialmente en públicos jóvenes que no interactúan con formatos tradicionales.
- Creemos que al implementar una **solución digital accesible basada en QR/NFC y sensores de bajo costo**, que permita registrar interacciones y analizar el comportamiento en tiempo real, podremos **mejorar la toma de decisiones del museo y enriquecer la experiencia del visitante**.
- Sabremos que esto es cierto cuando observemos **un aumento en la interacción con el contenido digital**, **una reducción de zonas congestionadas**, y **una mayor disponibilidad de métricas accionables para la gestión del museo**.


##### 1.2.2.2. Lean UX Assumptions

##### **a) Supuestos de Negocio (Business Assumptions)**

- Los museos y centros culturales necesitan **datos más granulares (por sala y obra)** para justificar presupuestos y mejorar la toma de decisiones.
- Un modelo basado en **hardware accesible + suscripción SaaS** es viable para instituciones con presupuesto limitado.
- La mejora en métricas de engagement y flujo de visitantes incentivará la **adopción de soluciones digitales** en el sector cultural.

##### **b) Supuestos de Usuario (User Assumptions)**

- Los visitantes están dispuestos a usar sus propios dispositivos (**BYOD**) para acceder a contenido digital si el proceso es **rápido y sin fricción**.
- Los visitantes valoran contenido **interactivo, visual y dinámico** frente a fichas técnicas tradicionales.
- Los administradores y curadores necesitan **visualizaciones claras y en tiempo real** para comprender el comportamiento del visitante.


##### **c) Supuestos de Valor (Value Assumptions)**

- El acceso a contenido digital mediante QR/NFC **aumenta el engagement del visitante** con las obras.
- La disponibilidad de métricas en tiempo real permite **mejorar la gestión del flujo y reducir la congestión** en salas.
- La analítica basada en datos permite a los museos **optimizar sus exhibiciones y tomar decisiones estratégicas más informadas**.


##### **d) Supuestos de Funcionalidad (Feature Assumptions)**

- Los sensores infrarrojos conectados a microcontroladores (ESP32) son **suficientemente precisos para el conteo de personas en interiores**.
- Una plataforma **web-based (sin descarga)** reduce la fricción y facilita el acceso del visitante.
- Los dashboards con métricas en tiempo real permiten a los administradores **identificar patrones y tomar acciones inmediatas**.
- Un sistema de conteo **anónimo (sin cámaras)** mejora la aceptación del usuario al respetar su privacidad.

##### 1.2.2.3. Lean UX Hypothesis Statements

##### **a) Hipótesis de Negocio (Business)**

Creemos que los **administradores de museos y gestores culturales** adoptarán KhipuTech si **les permite optimizar recursos operativos mediante datos de flujo y comportamiento del visitante**.
Sabremos que esto es cierto cuando observemos **implementaciones piloto activas** y **reducciones medibles en costos operativos (≈15%) o mejoras en la distribución del personal**.



##### **b) Hipótesis de Usuario (User)**

Creemos que los **visitantes del museo** utilizarán la solución si **pueden acceder fácilmente a contenido digital mediante QR sin fricción y obtener una experiencia interactiva**.
Sabremos que esto es cierto cuando observemos que **≥40% de los visitantes escanean al menos 3 obras durante su recorrido**.



##### **c) Hipótesis de Valor (Value)**

Creemos que proporcionar **mapas de calor y métricas de permanencia por sala** permitirá a los administradores **tomar decisiones más eficientes sobre la distribución del flujo y recursos**.
Sabremos que esto es cierto cuando observemos **cambios en la distribución de visitantes (reducción de congestión)** y **uso recurrente del dashboard para toma de decisiones**.



##### **d) Hipótesis de Funcionalidad (Feature)**

Creemos que implementar **gamificación mediante insignias digitales por interacción (QR escaneados)** incrementará el **tiempo de permanencia del visitante dentro del museo**.
Sabremos que esto es cierto cuando observemos **un incremento ≥25% en el tiempo promedio de recorrido por visitante**.

#### 1.2.2.4. Lean UX Canvas

<center><strong>Figura 1</strong></center>
<center>Lean UX Canvas</center>

![FotoLeanUXCanvas](../assets/img/1_2_2_4-Lean-UX-Canvas/1_2_2_4_Lean_UX_Canvas.png)

Nota: La siguiente imagen presenta un Lean UX Canvas que plantea digitalizar museos usando sensores y códigos QR para medir el interés de los visitantes y mejorar la interacción.
Propone como beneficio reducir costos y modernizar la experiencia, iniciando con una prueba piloto en una sola sala antes de expandirse.

### 1.3. Segmento Objetivo

El proyecto **KhipuTech** se enfoca en dos segmentos principales dentro del sector cultural, identificados a partir de la necesidad de modernizar la experiencia del visitante y mejorar la gestión basada en datos.

##### **1.3.1. Segmento Objetivo #1 — Museos Privados y Galerías de Arte Contemporáneo**

* **Perfil:** Instituciones culturales privadas, galerías de arte contemporáneo y espacios expositivos independientes, con alta rotación de exhibiciones y enfoque en innovación.

* **Necesidades / Problemas:**

  * Falta de métricas precisas sobre interacción del público con las obras.
  * Dificultad para demostrar el impacto real de las exhibiciones a patrocinadores.
  * Baja interacción del visitante con contenido tradicional.

* **Contexto de Uso:**
  Espacios de exhibición donde los visitantes recorren salas de forma libre, utilizando sus dispositivos móviles para acceder a contenido digital complementario.

* **Hallazgo Clave:**
  Estas instituciones necesitan evidencias cuantificables del comportamiento del visitante para justificar decisiones curatoriales y fortalecer relaciones con patrocinadores.

* **Beneficio con KhipuTech:**
  Acceso a dashboards con métricas de interacción y mapas de calor, permitiendo validar el impacto de las exhibiciones y mejorar la experiencia del visitante mediante contenido digital interactivo.

##### **1.3.2. Segmento Objetivo #2 — Museos Públicos y Centros Culturales Municipales**

* **Perfil:** Instituciones culturales gestionadas por entidades públicas, enfocadas en educación, acceso cultural y manejo de grandes volúmenes de visitantes.

* **Necesidades / Problemas:**

  * Falta de control en tiempo real del aforo y flujo de visitantes.
  * Dificultad para gestionar la seguridad en horas pico.
  * Uso ineficiente de recursos humanos (seguridad, guías).

* **Contexto de Uso:**
  Museos con múltiples salas y alta afluencia, especialmente en eventos gratuitos o fechas festivas, donde el flujo de personas es variable e impredecible.

* **Hallazgo Clave:**
  La ausencia de herramientas de monitoreo en tiempo real limita la capacidad de respuesta ante situaciones de congestión o riesgo.

* **Beneficio con KhipuTech:**
  Implementación de sensores de flujo y dashboards en tiempo real que permiten monitorear el aforo, generar alertas y optimizar la distribución del personal.

---
