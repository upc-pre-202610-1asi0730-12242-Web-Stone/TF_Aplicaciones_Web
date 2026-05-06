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

#### Pilares de KhipuTech:

- **Visibilidad Cultural:** Hacer visible lo que antes era invisible (el comportamiento del visitante).

- **Accesibilidad Radical:** Crear soluciones que funcionen con el hardware que el usuario ya posee (su smartphone) y con presupuestos realistas para el sector cultural.

- **Integridad de Datos:** Garantizar que la información del museo sea un activo privado y valioso para su crecimiento.

#### 1.1.2. Perfiles de los integrantes del equipo

| Nombre                                                                                             | Descripción                                                                                                                                                                                                                                                                                                                                                                          |
| -------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Luis Alonso Huaco Oliva (U202417743) ![Foto_Perfil](pegarURLaqui)                                  | Estudiante de Ingeniería de Software interesado en documentación técnica y aseguramiento de calidad. Tiene experiencia en testing de software y redacción de documentación clara para proyectos. Le motiva asegurar que el software funcione correctamente y que esté bien documentado para futuros desarrolladores.                                                                 |
| Fabian Jesus Sandoval Cueto (U20221A132) ![FotoPerfil](../assets/img/members/Fabian-perfil.png)    | Especialista en automatización de procesos mediante n8n e integración de APIs (Meta, Shopify). Aporta experiencia en la configuración de infraestructura en la nube (GCP) y contenedores Docker, además de liderar la estrategia de captación de datos y marketing analítico de la solución.                                                                                         |
| Oscar Diego Checa Burga (U20231E492)                                                               | Estudiante de Ingeniería de Software especializado en diseño de experiencia de usuario (UX/UI). Lidero la creación de wireframes, mockups y guías de estilo visual. Manejo herramientas como Figma para prototipado y conocimientos en diseño responsive y accesibilidad web (WCAG). Mi Objetivo es crear experiencias digitales que combinen funcionalidad con negocios de mercado. |
| Andrea Khristina Correa Rodriguez (U202412041)                                                     | Estudiante de Ingeniería de Software con enfoque en análisis de sistemas y arquitectura de software. Tiene conocimientos en modelado de procesos de negocio. Le motiva entender cómo funcionan los sistemas complejos y traducir requisitos en soluciones técnicas efectivas.                                                                                                        |
| Winnie Lisbeth Merino Ordinola(U20231E504) ![FotoPerfil](../assets/img/members/winnie-perfil.jpeg) | Soy estudiante de la carrera de Ingeniería de Software, actualmente en el quinto ciclo. Mis principales destrezas son las habilidades para trabajar en grupo, la creatividad y la investigación. Mi mayor interés es tanto proponer ideas innovadoras que solucionen problemas cercanos en nuestra realidad, como llevarlas a cabo a través del software.                            |

### 1.2. **Solution Profile.**

KhipuInsight es la plataforma centralizada de KhipuTech diseñada para la visualización de analíticas en tiempo real y la gestión de contenidos interactivos en museos. Actúa como el puente entre el hardware de conteo (sensores IoT) y la experiencia digital del usuario final.

**Características clave:**

- **Monitoreo de Afluencia en Tiempo Real:** Visualización precisa del número de visitantes por habitación mediante sensores infrarrojos de bajo costo, permitiendo detectar saturación de salas al instante.

- **Gestión de Contenido Dinámico vía QR:** Sistema de administración de subdominios que permite actualizar la información de las esculturas y pinturas de forma remota sin cambiar los códigos físicos.

- **Autenticación Invisible por Geolocalización:** Restricción de acceso al contenido premium basada en la ubicación del usuario, garantizando que el material exclusivo solo sea consumido dentro del recinto.

- **Dashboard de Permanencia Curatorial:** Reportes detallados sobre qué obras generan mayor interacción, ayudando a los curadores a tomar decisiones basadas en datos reales de interés.

#### 1.2.1. Antecedentes y Problemática

En el ecosistema cultural actual, los museos enfrentan el reto de modernizar la experiencia del visitante sin perder la esencia de la contemplación artística. Actualmente, la mayoría de los museos medianos y pequeños operan con métodos de conteo manuales (libros de visitas o contadores de mano) y ofrecen información estática (fichas técnicas físicas) que no permite capturar datos sobre el comportamiento del usuario dentro de las salas.

**Los 5 'W' y 2 'H'**

- **1. What (Qué):**

  La falta de datos sobre el flujo de personas por sala y el bajo compromiso (engagement) con la información de las obras.

  - _¿Cuál es el problema?:_ La invisibilidad de los datos de comportamiento del visitante tras cruzar la taquilla. Los museos operan "a ciegas" dentro de sus propias salas, desconociendo qué piezas generan interés y cuáles pasan desapercibidas, sumado a una oferta informativa estática que no conecta con el público digital.
  - _¿Cuál es la relación con la persona en cuestión?:_ Para el administrador, es una pérdida de oportunidad estratégica y económica. Para el visitante, es una experiencia pasiva y limitada que no aprovecha la tecnología que ya lleva en su bolsillo (smartphone).

- **2. When (Cuándo):**

  Durante el horario de apertura al público, especialmente en horas pico donde la saturación de salas es un problema de seguridad y comodidad.

  - _¿Cuándo sucede el problema?:_ El problema de datos es constante, pero la crisis de gestión ocurre en las "horas pico" o durante exhibiciones temporales, donde la falta de métricas impide redistribuir al personal de seguridad o guías para evitar cuellos de botella.
  - _¿Cuándo utiliza el cliente el producto?:_ El museo utiliza el dashboard de analíticas de forma diaria para la toma de decisiones; el visitante interactúa con la solución durante todo el recorrido de la muestra, cada vez que desea profundizar en una obra.

- **3. Where (dónde):**

  Espacios cerrados de exhibición, galerías y museos con múltiples habitaciones.

  - _¿Dónde está el cliente cuando usa el producto?:_ El visitante se encuentra frente a las piezas de arte o circulando por los pasillos del museo. El administrador puede estar en la oficina técnica del museo o monitoreando de forma remota desde cualquier dispositivo con acceso a la red.
  - _¿A dónde se dirige?:_ El flujo del visitante es dinámico entre salas (Habitaciones 1, 2 y 3). El sistema busca guiarlo orgánicamente hacia las piezas menos concurridas o asegurar que complete el recorrido informativo diseñado por el curador.
  - _¿Dónde surge el problema?:_ En los puntos de transición (puertas y pasillos) donde el conteo manual falla, y en los puntos de contacto (fichas técnicas) donde el texto impreso es insuficiente o aburrido.

- **4. Who (quién):**

  Administradores de museos y centros culturales que carecen de analíticas precisas, y visitantes que buscan una experiencia interactiva sin fricciones tecnológicas

  - _¿Quiénes están involucrados?:_ Directores de museos, curadores de arte, personal de seguridad, encargados de marketing cultural y el público visitante (turistas y estudiantes).
  - _¿A quiénes le sucede el problema?:_ Principalmente a los gestores culturales que deben rendir cuentas sobre el éxito de una exposición y a los visitantes que se sienten abrumados en salas congestionadas.
  - _¿Quién lo utilizará?:_ Los visitantes escanearán los QR/NFC para el contenido exclusivo; los administradores y analistas de datos usarán la plataforma de KhipuTech para visualizar los reportes de tráfico.

- **5. Why (por qué):**

  Porque sin métricas de permanencia y flujo, el museo no puede optimizar sus recursos, mejorar sus curadurías ni justificar presupuestos basados en el impacto real de sus exhibiciones.

  - _¿Cuál es la causa del problema?:_ El alto costo de las soluciones tecnológicas tradicionales (cámaras con IA costosas) y la falta de infraestructura digital integrada que combine hardware de conteo con entrega de contenido en una sola plataforma económica.

- **6. How (cómo):**

  Implementando un sistema híbrido de sensores de hardware de bajo costo para el conteo de flujo y una capa de software accesible vía QR/NFC para la interacción con el contenido.

  - _¿En qué condiciones los clientes usan nuestro producto?:_ En un entorno de iluminación controlada (típico de museos) donde los sensores infrarrojos son altamente efectivos y donde se requiere un acceso rápido a la información sin necesidad de descargar aplicaciones pesadas (Web-based).
  - _¿Cómo nos conocieron los compradores?:_ A través de propuestas directas B2B (Business to Business), demostraciones de MVP en galerías locales o mediante la participación en ferias de innovación tecnológica aplicada a la cultura.
  - _¿Qué llevó a la persona a llegar a esta situación?:_ La necesidad de modernizar la institución bajo un presupuesto limitado y la presión por mejorar las métricas de satisfacción y seguridad del visitante tras la digitalización global.

- **7. How much (cuánto):**

  El proyecto debe ser viable con un presupuesto inicial de $500 USD para el desarrollo del MVP y escalable mediante suscripciones o licencias de bajo costo.

  - **Costo para el cliente:** Se plantea un modelo de implementación económica (pago único por hardware) + una suscripción mensual mínima (SaaS) por el mantenimiento del subdominio y el acceso al dashboard de datos.

#### 1.2.2. Lean UX Process

##### 1.2.2.1. Lean UX Problem Statements

El estado actual de la gestión en museos medianos y galerías presenta una desconexión crítica entre la presencia física del visitante y la recolección de datos analíticos.

- **Domain:** Tecnología aplicada al patrimonio cultural y analítica de espacios físicos (Smart Museums).

- **Customer Segments:** Directores de museos, curadores de arte y gestores de centros culturales que operan con presupuestos limitados.

- **Pain Points:**

  - Incapacidad de medir el tráfico interno por sala de forma automática.

  - Falta de métricas sobre qué obras específicas generan mayor interés o tiempo de permanencia.

  - Baja interacción del público joven con fichas técnicas estáticas y tradicionales.

- **Gap:** Existe una brecha entre el conteo masivo en taquilla y el comportamiento granular dentro de las exhibiciones, lo que impide una curaduría basada en datos.

- **Vision/Strategy:** Implementar una infraestructura de bajo costo ($500 MVP) que combine sensores IoT para el conteo de flujo y una plataforma web móvil para la entrega de contenido exclusivo, transformando la visita en un flujo de datos accionables.

- **Initial Segment:** Museos municipales y galerías de arte contemporáneo con al menos 3 salas de exhibición.

##### 1.2.2.2. Lean UX Assumptions

Para el desarrollo de KhipuTech, el equipo asume los siguientes puntos como verdaderos:

- **Usuarios:** Los visitantes están dispuestos a usar sus propios dispositivos (BYOD) para acceder a información si el proceso es instantáneo y el contenido es exclusivo.

- **Negocio:** Los administradores de museos valoran más los datos de flujo por sala que un simple conteo total de entradas para justificar sus presupuestos.

- **Tecnología**: Los sensores infrarrojos conectados a microcontroladores ESP32 son lo suficientemente precisos para el conteo de personas en interiores sin requerir cámaras costosas.

- **Conectividad:** El uso de una arquitectura basada en web (subdominios) es preferible a una aplicación nativa para reducir la fricción de descarga en el usuario.

- **Seguridad/Privacidad:** Los usuarios se sienten más cómodos con un sistema de conteo anónimo (sensores) que con uno basado en reconocimiento facial (cámaras).

##### 1.2.2.3. Lean UX Hypothesis Statements

Hemos definido las siguientes hipótesis para validar el modelo de negocio:

- **Hipótesis de Valor de Datos:** Creemos que proporcionarle al administrador un reporte semanal de "Mapas de Calor" y permanencia por sala, le permitirá optimizar la distribución de sus guías y personal de seguridad, ahorrando hasta un 15% en costos operativos mensuales.

- **Hipótesis de Interacción:** Creemos que si el contenido de la obra está bloqueado fuera del museo y se accede mediante un "autologeo" por QR, el 40% de los visitantes escaneará al menos 3 obras para completar la experiencia informativa.

- **Hipótesis de Costo:** Creemos que podemos implementar un sistema funcional en un museo de 3 salas con un presupuesto de hardware de $200 USD (parte de los $500 totales), demostrando que la tecnología de punta no es exclusiva de museos con presupuestos millonarios.

- **Hipótesis de Retención:** Creemos que al ofrecer una "colección digital" de stickers o insignias por cada QR escaneado, el visitante promedio pasará un 25% más de tiempo dentro del museo para completar el recorrido.

#### 1.2.2.4. Lean UX Canvas

<center><strong>Figura 1</strong></center>
<center>Lean UX Canvas</center>

![FotoLeanUXCanvas](../assets/img/images/Lean%20UX%20Canvas%20de%20KhipuTech.png)

La siguiente imagen presenta un Lean UX Canvas que plantea digitalizar museos usando sensores y códigos QR para medir el interés de los visitantes y mejorar la interacción.
Propone como beneficio reducir costos y modernizar la experiencia, iniciando con una prueba piloto en una sola sala antes de expandirse.

### 1.3. Segmento Objetivo

KhipuTech enfoca su modelo de negocio en dos segmentos institucionales distintos dentro del sector cultural. Ambos comparten la necesidad de modernización, pero difieren en su gobernanza y objetivos estratégicos.

- **Segmento A - Museos Privados y Galerías de Arte Contemporáneo:**

  Este segmento agrupa a instituciones de gestión privada que dependen de la venta de entradas, patrocinios y la rotación constante de exhibiciones.

  - _Características:_
    - Perfil: Instituciones con alta agilidad en la toma de decisiones y un enfoque fuerte en la curaduría innovadora.
    - Necesidad: Requieren métricas exactas para demostrar el valor de sus exhibiciones a los artistas y patrocinadores (sponsors). Buscan exclusividad para fidelizar a su audiencia.
    - Información Estadística: Según informes de gestión cultural en Latinoamérica, las galerías privadas reportan que el 60% de sus ingresos por patrocinios dependen de la capacidad de demostrar el alcance y la interacción real del público con las obras.
  - _Valor de KhipuTech:_ Proporciona "Prueba de Impacto" para sus patrocinadores mediante el dashboard de analíticas.

- **Segmento B - Centros Culturales Municipales y Museos Públicos**

  Este segmento comprende espacios administrados por gobiernos locales o entidades del estado que buscan democratizar la cultura y gestionar grandes flujos de personas.

  - _Características:_
    - Perfil: Instituciones con presupuestos públicos anuales limitados, enfocadas en la educación y la seguridad del ciudadano.
    - Necesidad: Optimizar el gasto operativo. Necesitan sistemas de conteo automatizados para redistribuir a su personal de seguridad y guías de manera eficiente, especialmente en días de entrada gratuita.
    - Información Estadística: De acuerdo con el Ministerio de Cultura, los museos públicos reciben picos de afluencia que pueden superar el 300% de su capacidad normal en fechas festivas. La falta de sistemas de conteo en tiempo real genera riesgos de seguridad y deterioro del patrimonio.
  - _Valor de KhipuTech:_ Gestión de aforo y seguridad mediante sensores de flujo de bajo costo, facilitando el cumplimiento de normas de Defensa Civil.

- **Sustento de Selección del Segmento Inicial**

  Aunque ambos son viables, KhipuTech iniciará operaciones con el Segmento A (Galerías Privadas). La razón técnica es que su ciclo de venta es más rápido (no requiere licitaciones públicas complejas) y el presupuesto de $500 permite instalar una red completa en sus espacios, que suelen ser más compactos y controlados, ideales para validar las hipótesis de nuestro Lean UX Canvas.

---
