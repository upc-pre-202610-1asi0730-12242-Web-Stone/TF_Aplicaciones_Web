## Capítulo III: Requirements Specification

### 3.1. User Stories

<table style="width: 100%; border-collapse: collapse;">
  <!-- BARRA DE ARRIBA -->
  <tr>
    <th style="text-align: center;">Epic/Story ID</th>
    <th style="text-align: center;">Título</th>
    <th style="text-align: center;">Descripción</th>
    <th style="text-align: center;">Criterios de Aceptación</th>
    <th style="text-align: center;">Relacionado con (Epic ID)</th>
  </tr>
<!-- EPICA 1 -->
<tr>
  <td style="text-align: center;">EP01</td>
  <td style="text-align: center;">Experiencia personalizada e interactiva</td>
  <td style="text-align: center;">
    Como museo privado, quiero ofrecer contenido digital accesible mediante códigos QR/NFC para enriquecer el recorrido y brindar una experiencia más atractiva e interactiva a los visitantes.
  </td>
  <td style="text-align: center;">
    - El sistema permite escanear códigos QR/NFC desde smartphones<br>
    - El contenido se carga en menos de 3 segundos<br>
    - Se registra la interacción del usuario<br>
    - No requiere instalación de aplicación<br>
  </td>
  <td style="text-align: center;">-</td>
</tr>
<!-- EPICA 2 -->
<tr>
  <td style="text-align: center;">
    EP02
  </td>
  <td style="text-align: center;">
    Inteligencia de negocio basada en comportamiento
  </td>
  <td style="text-align: center;">
    Como gestor de museo privado, quiero analizar el comportamiento e interacción de los visitantes con las exposiciones para identificar cuáles generan mayor interés y así tomar decisiones estratégicas de marketing y curaduría.
  </td>
  <td style="text-align: center;">
    - El sistema recopila datos de interacción por obra y exposición<br>
    - Se visualizan métricas como visitas, tiempo de permanencia y engagement<br>
    - Los datos pueden filtrarse por fecha y exposición<br>
    - Se generan dashboards visuales para análisis<br>
    - Es posible exportar reportes para uso estratégico
  </td>
  <td style="text-align: center;">
    -
  </td>
</tr>
<!-- EPICA 3 -->
<tr>
  <td style="text-align: center;">
    EP03
  </td>
  <td style="text-align: center;">
    Optimización de ingresos y operación del museo
  </td>
  <td style="text-align: center;">
    Como gestor de museo privado, quiero analizar el comportamiento de los visitantes y el uso de los recursos operativos para optimizar la asignación de recursos, maximizar los ingresos y mejorar la eficiencia del museo.
  </td>
  <td style="text-align: center;">
    - El sistema identifica patrones de flujo de visitantes en el museo<br>
    - Se visualiza el uso de recursos (salas, personal, horarios)<br>
    - Se generan métricas relacionadas a ingresos y rendimiento de exposiciones<br>
    - Se permite comparar desempeño entre diferentes periodos o exhibiciones<br>
    - Se brindan insights para optimizar la operación del museo
  </td>
  <td style="text-align: center;">
    -
  </td>
</tr>
<!-- EPICA 4 -->
<tr>
  <td style="text-align: center;">
    EP04
  </td>
  <td style="text-align: center;">
    Control de aforo y cumplimiento de normativas
  </td>
  <td style="text-align: center;">
    Como administrador de museo público, quiero monitorear y controlar el flujo de visitantes en tiempo real para garantizar el cumplimiento de las normativas de aforo y asegurar la seguridad de los visitantes dentro del museo.
  </td>
  <td style="text-align: center;">
    - El sistema muestra el número de visitantes en tiempo real<br>
    - Se configuran límites de aforo por sala o zona<br>
    - Se generan alertas cuando se supera el aforo permitido<br>
    - Los datos se capturan automáticamente mediante sensores de flujo<br>
    - El sistema mantiene funcionamiento ante fallas de conexión (modo resiliente)
  </td>
  <td style="text-align: center;">
    -
  </td>
<!-- EPICA 5 -->
<tr>
  <td style="text-align: center;">
    EP05
  </td>
  <td style="text-align: center;">
    Optimización de la experiencia del visitante
  </td>
  <td style="text-align: center;">
    Como administrador de museo público, quiero ofrecer a los visitantes acceso a contenido digital interactivo y orientación dentro del museo para mejorar su experiencia, facilitar el aprendizaje y aumentar su satisfacción durante la visita.
  </td>
  <td style="text-align: center;">
    - Los visitantes pueden acceder a información digital mediante QR<br>
    - El contenido está optimizado para dispositivos móviles<br>
    - Se ofrecen rutas o recorridos sugeridos dentro del museo<br>
    - El sistema soporta múltiples idiomas<br>
    - Se pueden medir niveles de interacción del visitante
  </td>
  <td style="text-align: center;">
    -
  </td>
</tr>
<!-- EPICA 6 -->
<tr>
  <td style="text-align: center;">
    EP06
  </td>
  <td style="text-align: center;">
    Toma de decisiones basada en datos
  </td>
  <td style="text-align: center;">
    Como administrador de museo público, quiero analizar datos de afluencia y comportamiento de los visitantes para tomar decisiones informadas sobre la gestión del museo y optimizar el uso de los recursos disponibles.
  </td>
  <td style="text-align: center;">
    - El sistema genera reportes de afluencia por día, semana y mes<br>
    - Se identifican horas pico y patrones de visita<br>
    - Se visualizan métricas de comportamiento de los visitantes<br>
    - Los datos pueden ser utilizados para planificación operativa<br>
    - Se permite exportar reportes para entidades gubernamentales
  </td>
  <td style="text-align: center;">
    -
  </td>
</tr>
<!-- EPICA 7 -->
<tr>
  <td style="text-align: center;">
    EP07
  </td>
  <td style="text-align: center;">
    Control de acceso y seguridad de la información
  </td>
  <td style="text-align: center;">
    Como administrador del museo, quiero controlar y gestionar el acceso a los datos del sistema para proteger la información de las exposiciones y garantizar un uso seguro y eficiente de la plataforma.
  </td>
  <td style="text-align: center;">
    - El sistema requiere autenticación para acceder a la información<br>
    - Existen roles de usuario (administrador, analista, etc.)<br>
    - Se controla el acceso a datos según permisos definidos<br>
    - Se registran logs de acceso al sistema<br>
    - Los datos sensibles están protegidos mediante mecanismos de seguridad
  </td>
  <td style="text-align: center;">
    -
  </td>
</tr>
<!-- US 1 -->
<tr>
  <td style="text-align: center;">
    US01
  </td>
  <td style="text-align: center;">
    Acceso a contenido mediante QR
  </td>
  <td style="text-align: center;">
    Como visitante, quiero escanear un código QR para acceder al contenido digital de una obra, para obtener información adicional de forma rápida durante mi recorrido.
  </td>
  <td style="text-align: center;">
    Criterios de aceptación:<br>
    Given que el visitante se encuentra frente a una obra con un código QR visible<br>
    When escanea el código QR con su dispositivo móvil<br>
    Then el contenido digital se abre correctamente en el navegador<br><br>
    Given que el visitante accede al contenido 
    <br>
    When el sistema carga la información<br>
    Then el tiempo de carga es menor a 3 segundos<br><br>
    Given que el visitante utiliza su dispositivo móvil<br>
    When accede al contenido mediante el QR<br>
    Then no es necesario instalar ninguna aplicación adicional
  </td>
  <td style="text-align: center;">
    EP01
  </td>
</tr>
 <!-- US 2 -->
<tr>
  <td style="text-align: center;">
    US02
  </td>
  <td style="text-align: center;">
    Acceso mediante NFC
  </td>
  <td style="text-align: center;">
    Como visitante, quiero acceder al contenido digital de una obra acercando mi dispositivo a un punto NFC, para obtener información de forma rápida y sin fricción durante mi recorrido.
  </td>
  <td style="text-align: center;">
    Criterios de aceptación:<br>
    Given que el visitante posee un dispositivo con NFC activado<br>
    When acerca su dispositivo al punto NFC<br>
    Then el contenido digital se abre automáticamente en el navegador<br><br>
    Given que el visitante interactúa con el punto NFC<br>
    When el sistema detecta el dispositivo<br>
    Then no se requieren pasos adicionales para acceder al contenido<br><br>
    Given que el visitante utiliza un dispositivo sin soporte NFC<br>
    When intenta interactuar con el punto NFC<br>
    Then se muestra un mensaje indicando que su dispositivo no es compatible
  </td>
  <td style="text-align: center;">
    EP01
  </td>
</tr>
 <!-- US 3 -->
<tr>
  <td style="text-align: center;">
    US03
  </td>
  <td style="text-align: center;">
    Visualización multimedia enriquecida
  </td>
  <td style="text-align: center;">
    Como visitante, quiero visualizar contenido multimedia (imágenes, audio y video) asociado a una obra, para comprender mejor su contexto y enriquecer mi experiencia durante el recorrido.
  </td>
  <td style="text-align: center;">
    Criterios de aceptación:
    <br>Given que el visitante accede al contenido de una obra
    <br>When el sistema muestra la información
    <br>Then se visualiza al menos texto e imagen correctamente
    <br><br>Given que el contenido incluye audio o video
    <br>When el visitante interactúa con el contenido
    <br>Then el audio o video se reproduce sin errores
    <br><br>Given que el visitante reproduce contenido multimedia
    <br>When utiliza los controles del reproductor
    <br>Then puede pausar y reanudar la reproducción correctamente
  </td>
  <td style="text-align: center;">
    EP01
  </td>
</tr>
<!-- US 4 -->
<tr>
  <td style="text-align: center;">
    US04
  </td>
  <td style="text-align: center;">
    Selección de idioma
  </td>
  <td style="text-align: center;">
    Como visitante, quiero seleccionar el idioma del contenido digital, para comprender la información de las obras en mi idioma preferido durante el recorrido.
  </td>
  <td style="text-align: center;">
    Criterios de aceptación:
    <br>Given que el visitante accede al contenido digital
    <br>When visualiza las opciones de idioma
    <br>Then se muestran al menos dos idiomas disponibles
    <br><br>Given que el visitante selecciona un idioma
    <br>When navega entre diferentes contenidos
    <br>Then el idioma seleccionado se mantiene durante la sesión
    <br><br>Given que el visitante cambia el idioma
    <br>When selecciona una nueva opción
    <br>Then el contenido se actualiza sin recargar la página
  </td>
  <td style="text-align: center;">
    EP01
  </td>
</tr>
<!-- US 5 -->
<tr>
  <td style="text-align: center;">
    US05
  </td>
  <td style="text-align: center;">
    Contenido contextual por sala
  </td>
  <td style="text-align: center;">
    Como visitante, quiero recibir contenido digital específico según la sala o ubicación en la que me encuentre, para obtener información relevante de las obras durante mi recorrido.
  </td>
  <td style="text-align: center;">
    Criterios de aceptación:
    <br>Given que el visitante escanea un código QR o interactúa con un punto NFC en una sala
    <br>When el sistema identifica la ubicación
    <br>Then se muestra el contenido correspondiente a esa sala
    <br><br>Given que el visitante se encuentra en diferentes salas
    <br>When accede al contenido digital
    <br>Then cada sala presenta contenido único y diferenciado
    <br><br>Given que el visitante accede al contenido de una sala
    <br>When el sistema carga la información
    <br>Then no se muestran contenidos de otras salas
  </td>
  <td style="text-align: center;">
    EP01
  </td>
</tr>
<!-- US 6 -->
<tr>
  <td style="text-align: center;">
    US06
  </td>
  <td style="text-align: center;">
    Historial de obras visitadas
  </td>
  <td style="text-align: center;">
    Como visitante, quiero visualizar el historial de las obras que he explorado durante mi recorrido, para poder revisarlas nuevamente y dar seguimiento a mi experiencia.
  </td>
  <td style="text-align: center;">
    Criterios de aceptación:
    <br>Given que el visitante interactúa con diferentes obras
    <br>When accede al historial
    <br>Then se muestra una lista de las obras visitadas durante la sesión
    <br><br>Given que el visitante accede al historial
    <br>When selecciona una obra previamente vista
    <br>Then puede volver a visualizar su contenido digital
    <br><br>Given que el visitante utiliza el sistema sin autenticación
    <br>When navega por las obras
    <br>Then el historial se guarda automáticamente sin requerir inicio de sesión
  </td>
  <td style="text-align: center;">
    EP01
  </td>
</tr>
 <!-- US 7 -->
<tr>
  <td style="text-align: center;">
    US07
  </td>
  <td style="text-align: center;">
    Recomendaciones de obras
  </td>
  <td style="text-align: center;">
    Como visitante, quiero recibir recomendaciones de obras relacionadas basadas en mis interacciones previas, para descubrir contenido relevante y enriquecer mi recorrido dentro del museo.
  </td>
  <td style="text-align: center;">
    Criterios de aceptación:
    <br>Given que el visitante ha interactuado con al menos una obra
    <br>When accede al contenido digital
    <br>Then se muestran al menos dos recomendaciones de obras relacionadas
    <br><br>Given que el sistema genera recomendaciones
    <br>When analiza el historial del visitante
    <br>Then las recomendaciones se basan en obras previamente vistas
    <br><br>Given que el visitante visualiza las recomendaciones
    <br>When selecciona una de ellas
    <br>Then puede navegar al contenido de la obra recomendada correctamente
  </td>
  <td style="text-align: center;">
    EP01
  </td>
</tr>
 <!-- US 8 -->
<tr>
  <td style="text-align: center;">
    US08
  </td>
  <td style="text-align: center;">
    Marcado de obras favoritas
  </td>
  <td style="text-align: center;">
    Como visitante, quiero marcar obras como favoritas, para guardarlas y poder revisarlas fácilmente durante mi recorrido.
  </td>
  <td style="text-align: center;">
    Criterios de aceptación:
    <br>Given que el visitante visualiza una obra
    <br>When selecciona la opción de marcar como favorita
    <br>Then la obra se guarda como favorita
    <br><br>Given que una obra está marcada como favorita
    <br>When el visitante vuelve a interactuar con ella
    <br>Then puede desmarcarla correctamente
    <br><br>Given que el visitante marca una obra como favorita
    <br>When navega por el contenido
    <br>Then el estado de favorito se mantiene durante la sesión y se refleja visualmente
  </td>
  <td style="text-align: center;">
    EP01
  </td>
</tr>
<!-- US 9 -->
<tr>
  <td style="text-align: center;">
    US09
  </td>
  <td style="text-align: center;">
    Visualización de interacciones por obra
  </td>
  <td style="text-align: center;">
    Como gestor del museo, quiero visualizar la cantidad de interacciones por cada obra, para identificar cuáles generan mayor interés en los visitantes.
  </td>
  <td style="text-align: center;">
    Criterios de aceptación:
    <br>Given que los visitantes interactúan con las obras mediante QR o NFC
    <br>When el sistema registra las interacciones
    <br>Then se almacena cada acceso correctamente
    <br><br>Given que el gestor accede al dashboard
    <br>When visualiza las métricas
    <br>Then se muestra el conteo de interacciones por obra
    <br><br>Given que existen nuevas interacciones
    <br>When el sistema actualiza los datos
    <br>Then la información se refleja en tiempo casi real
  </td>
  <td style="text-align: center;">
    EP02
  </td>
</tr>
<!-- US 10 -->
<tr>
  <td style="text-align: center;">
    US10
  </td>
  <td style="text-align: center;">
    Medición de tiempo de interacción por obra
  </td>
  <td style="text-align: center;">
    Como gestor del museo, quiero medir el tiempo de interacción de los visitantes en cada contenido, para evaluar el nivel de interés y mejorar la experiencia ofrecida.
  </td>
  <td style="text-align: center;">
    Criterios de aceptación:
    <br>Given que un visitante accede al contenido de una obra
    <br>When inicia y finaliza la interacción
    <br>Then el sistema registra el tiempo de permanencia por sesión
    <br><br>Given que existen múltiples interacciones registradas
    <br>When el gestor consulta las métricas
    <br>Then se calcula el tiempo promedio de interacción por obra
    <br><br>Given que se registran sesiones de muy corta duración
    <br>When el sistema procesa los datos
    <br>Then se excluyen las sesiones por debajo de un umbral definido
  </td>
  <td style="text-align: center;">
    EP02
  </td>
</tr>
<!-- US 11 -->
<tr>
  <td style="text-align: center;">
    US11
  </td>
  <td style="text-align: center;">
    Ranking de obras más populares
  </td>
  <td style="text-align: center;">
    Como gestor del museo, quiero visualizar un ranking de las obras más visitadas, para identificar cuáles generan mayor interés y optimizar la curaduría y estrategias de exhibición.
  </td>
  <td style="text-align: center;">
    Criterios de aceptación:
    <br>Given que existen datos de interacción de los visitantes
    <br>When el gestor accede al dashboard
    <br>Then se muestra una lista de obras ordenadas por número de visitas
    <br><br>Given que el gestor configura el ranking
    <br>When selecciona la cantidad de resultados
    <br>Then el sistema muestra un top configurable (ej. top 5, top 10)
    <br><br>Given que se registran nuevas interacciones
    <br>When el sistema actualiza los datos
    <br>Then el ranking se actualiza automáticamente en tiempo casi real
  </td>
  <td style="text-align: center;">
    EP02
  </td>
</tr>
<!-- US 12 -->
<tr>
  <td style="text-align: center;">
    US12
  </td>
  <td style="text-align: center;">
    Análisis por franjas horarias
  </td>
  <td style="text-align: center;">
    Como gestor del museo, quiero analizar las interacciones de los visitantes por franjas horarias, para identificar horas pico y optimizar la gestión operativa y de personal.
  </td>
  <td style="text-align: center;">
    Criterios de aceptación:
    <br>Given que existen datos de interacción de los visitantes
    <br>When el sistema procesa la información
    <br>Then los datos se agrupan por franjas horarias
    <br><br>Given que el gestor accede al dashboard
    <br>When visualiza las métricas
    <br>Then se muestra una visualización clara de las interacciones por hora
    <br><br>Given que el gestor desea analizar un periodo específico
    <br>When aplica filtros de fecha
    <br>Then los datos se actualizan según el rango seleccionado
  </td>
  <td style="text-align: center;">
    EP02
  </td>
</tr>
 <!-- US 13 -->
<tr>
  <td style="text-align: center;">
    US13
  </td>
  <td style="text-align: center;">
    Identificación de obras con baja interacción
  </td>
  <td style="text-align: center;">
    Como gestor del museo, quiero identificar las obras con baja interacción, para tomar decisiones informadas sobre su mejora, reubicación o reemplazo dentro de la exhibición.
  </td>
  <td style="text-align: center;">
    Criterios de aceptación:
    <br>Given que existen datos de interacción de las obras
    <br>When el sistema analiza la información
    <br>Then se muestra una lista de obras con menor número de interacciones
    <br><br>Given que el gestor configura un umbral mínimo de interacción
    <br>When el sistema aplica el filtro
    <br>Then se identifican las obras por debajo de ese umbral
    <br><br>Given que el gestor revisa las métricas
    <br>When compara el rendimiento de las obras
    <br>Then se muestran datos comparativos entre obras de alta y baja interacción
  </td>
  <td style="text-align: center;">
    EP02
  </td>
</tr>
 <!-- US 14 -->
<tr>
  <td style="text-align: center;">
    US14
  </td>
  <td style="text-align: center;">
    Dashboard en tiempo real
  </td>
  <td style="text-align: center;">
    Como gestor del museo, quiero visualizar métricas de interacción en tiempo real a través de un dashboard, para monitorear el comportamiento de los visitantes y tomar decisiones oportunas.
  </td>
  <td style="text-align: center;">
    Criterios de aceptación:
    <br>Given que existen datos de interacción de los visitantes
    <br>When el sistema recibe nueva información
    <br>Then el dashboard se actualiza automáticamente en tiempo casi real
    <br><br>Given que el gestor accede al dashboard
    <br>When visualiza las métricas
    <br>Then se muestran datos como visitas actuales, interacciones y tiempo de permanencia
    <br><br>Given que el gestor utiliza el dashboard
    <br>When navega por la interfaz
    <br>Then la información se presenta de forma clara, organizada y fácil de interpretar
  </td>
  <td style="text-align: center;">
    EP02
  </td>
</tr>
<!-- US 15 -->
<tr>
  <td style="text-align: center;">
    US15
  </td>
  <td style="text-align: center;">
    Exportación de reportes
  </td>
  <td style="text-align: center;">
    Como gestor del museo, quiero exportar los datos y métricas del sistema en formatos compatibles, para realizar análisis externos y compartir información con stakeholders.
  </td>
  <td style="text-align: center;">
    Criterios de aceptación:
    <br>Given que el gestor accede al dashboard
    <br>When selecciona la opción de exportar datos
    <br>Then el sistema genera un archivo en formato CSV o Excel
    <br><br>Given que el sistema genera el reporte
    <br>When el archivo es descargado
    <br>Then incluye métricas clave como visitas, tiempo de interacción y ranking de obras
    <br><br>Given que el gestor solicita la exportación
    <br>When el sistema procesa la solicitud
    <br>Then la descarga se realiza en un tiempo adecuado
  </td>
  <td style="text-align: center;">
    EP02
  </td>
</tr>
<!-- US 16 -->
<tr>
  <td style="text-align: center;">
    US16
  </td>
  <td style="text-align: center;">
    Segmentación por tipo de contenido
  </td>
  <td style="text-align: center;">
    Como gestor del museo, quiero analizar el engagement según el tipo de contenido (texto, imagen, audio, video), para identificar cuáles generan mayor interés y optimizar la estrategia de contenido digital.
  </td>
  <td style="text-align: center;">
    Criterios de aceptación:
    <br>Given que existen interacciones registradas con diferentes tipos de contenido
    <br>When el sistema procesa los datos
    <br>Then las interacciones se clasifican por tipo de contenido
    <br><br>Given que el gestor accede al dashboard
    <br>When visualiza las métricas
    <br>Then se muestran métricas separadas por cada tipo de contenido
    <br><br>Given que el gestor analiza el rendimiento
    <br>When compara los tipos de contenido
    <br>Then se visualiza una comparación clara del nivel de engagement entre ellos
  </td>
  <td style="text-align: center;">
    EP02
  </td>
</tr>
<!-- US 17 -->
<tr>
  <td style="text-align: center;">
    US17
  </td>
  <td style="text-align: center;">
    Visualización de métricas de ingresos
  </td>
  <td style="text-align: center;">
    Como gestor del museo, quiero visualizar métricas de ingresos generados por las exhibiciones, para identificar cuáles generan mayor rentabilidad y optimizar la estrategia comercial.
  </td>
  <td style="text-align: center;">
    Criterios de aceptación:
    <br>Given que existen datos de ingresos registrados
    <br>When el gestor accede al dashboard
    <br>Then se muestran los ingresos agrupados por periodo (día, semana, mes)
    <br><br>Given que el gestor analiza las exhibiciones
    <br>When visualiza las métricas
    <br>Then los ingresos se diferencian por cada exhibición
    <br><br>Given que el gestor consulta el dashboard
    <br>When revisa la información
    <br>Then los datos se presentan de forma clara, organizada y comprensible
  </td>
  <td style="text-align: center;">
    EP03
  </td>
</tr>
<!-- US 18 -->
<tr>
  <td style="text-align: center;">
    US18
  </td>
  <td style="text-align: center;">
    Identificación de obras más rentables
  </td>
  <td style="text-align: center;">
    Como gestor del museo, quiero identificar qué obras generan mayor interacción asociada a ingresos, para optimizar la selección y diseño de futuras exhibiciones.
  </td>
  <td style="text-align: center;">
    Criterios de aceptación:
    <br>Given que existen datos de interacción e ingresos
    <br>When el sistema analiza la información
    <br>Then se muestra un ranking de obras basado en su rentabilidad
    <br><br>Given que se registran nuevas interacciones o ingresos
    <br>When el sistema actualiza los datos
    <br>Then el ranking se actualiza automáticamente
    <br><br>Given que el gestor accede al dashboard
    <br>When visualiza las métricas
    <br>Then la información se presenta de forma clara y fácil de interpretar
  </td>
  <td style="text-align: center;">
    EP03
  </td>
</tr>
<!-- US 19 -->
<tr>
  <td style="text-align: center;">
    US19
  </td>
  <td style="text-align: center;">
    Optimización de distribución de recursos
  </td>
  <td style="text-align: center;">
    Como gestor del museo, quiero analizar el flujo de visitantes por sala, para redistribuir el personal y los recursos de manera eficiente y mejorar la operación del museo.
  </td>
  <td style="text-align: center;">
    Criterios de aceptación:
    <br>Given que existen datos de flujo de visitantes
    <br>When el sistema procesa la información
    <br>Then se muestran métricas de flujo por sala
    <br><br>Given que el gestor accede al dashboard
    <br>When visualiza las métricas
    <br>Then se presentan recomendaciones visuales para la redistribución de recursos
    <br><br>Given que el gestor necesita tomar decisiones operativas
    <br>When accede al sistema
    <br>Then puede consultar esta información desde el dashboard
  </td>
  <td style="text-align: center;">
    EP03
  </td>
</tr>
<!-- US 20 -->
<tr>
  <td style="text-align: center;">
    US20
  </td>
  <td style="text-align: center;">
    Generación de reportes de desempeño
  </td>
  <td style="text-align: center;">
    Como gestor del museo, quiero generar reportes de desempeño de las exhibiciones, para evaluar resultados y tomar decisiones estratégicas basadas en datos.
  </td>
  <td style="text-align: center;">
    Criterios de aceptación:
    <br>Given que el gestor solicita un reporte
    <br>When el sistema procesa la información
    <br>Then se genera un reporte que integra métricas de interacción, ingresos y rendimiento
    <br><br>Given que el reporte es generado
    <br>When el gestor lo visualiza o descarga
    <br>Then incluye tanto datos resumidos como detallados por exhibición
    <br><br>Given que el gestor accede al reporte
    <br>When revisa la información
    <br>Then el contenido se presenta en un formato claro, estructurado y legible
  </td>
  <td style="text-align: center;">
    EP03
  </td>
</tr>
<!-- US 21 -->
<tr>
  <td style="text-align: center;">
    US21
  </td>
  <td style="text-align: center;">
    Optimización de experiencia basada en interacción
  </td>
  <td style="text-align: center;">
    Como gestor del museo, quiero monitorear la interacción de los visitantes con el contenido digital, para identificar oportunidades de mejora y optimizar la experiencia ofrecida.
  </td>
  <td style="text-align: center;">
    Criterios de aceptación:
    <br>Given que existen datos de interacción de los visitantes
    <br>When el sistema procesa la información
    <br>Then se muestran métricas de interacción por obra
    <br><br>Given que el gestor analiza las métricas
    <br>When identifica patrones de bajo o alto engagement
    <br>Then puede detectar oportunidades de mejora en la experiencia
    <br><br>Given que el gestor accede al dashboard
    <br>When revisa la información
    <br>Then los datos se presentan en tiempo casi real y de forma clara
  </td>
  <td style="text-align: center;">
    EP03
  </td>
</tr>
<!-- US 22 -->
<tr>
  <td style="text-align: center;">
    US22
  </td>
  <td style="text-align: center;">
    Comparación de rendimiento entre exhibiciones
  </td>
  <td style="text-align: center;">
    Como gestor del museo, quiero comparar el rendimiento entre distintas exhibiciones, para identificar oportunidades de mejora y optimizar la planificación futura.
  </td>
  <td style="text-align: center;">
    Criterios de aceptación:
    <br>Given que existen datos de múltiples exhibiciones
    <br>When el gestor selecciona exhibiciones a comparar
    <br>Then el sistema muestra métricas comparativas entre ellas
    <br><br>Given que el gestor analiza el rendimiento
    <br>When visualiza la información
    <br>Then se presentan gráficos claros que facilitan la comparación
    <br><br>Given que el sistema procesa los datos
    <br>When genera la comparación
    <br>Then la información es consistente y corresponde a los periodos seleccionados
  </td>
  <td style="text-align: center;">
    EP03
  </td>
</tr>
<!-- US 23 -->
<tr>
  <td style="text-align: center;">
    US23
  </td>
  <td style="text-align: center;">
    Análisis de tendencias de visitantes
  </td>
  <td style="text-align: center;">
    Como gestor del museo, quiero analizar tendencias de visitas a lo largo del tiempo, para anticipar picos de demanda y planificar mejor los recursos y la operación.
  </td>
  <td style="text-align: center;">
    Criterios de aceptación:
    <br>Given que existen datos históricos de visitas
    <br>When el sistema procesa la información
    <br>Then se generan gráficos de tendencias por fechas
    <br><br>Given que el gestor analiza las tendencias
    <br>When visualiza los datos
    <br>Then se identifican patrones como horas o días de mayor afluencia
    <br><br>Given que se registran nuevas visitas
    <br>When el sistema actualiza la información
    <br>Then las tendencias se actualizan automáticamente
  </td>
  <td style="text-align: center;">
    EP03
  </td>
</tr>
<!-- US 24 -->
<tr>
  <td style="text-align: center;">
    US24
  </td>
  <td style="text-align: center;">
    Optimización de contenido premium
  </td>
  <td style="text-align: center;">
    Como gestor del museo, quiero ajustar el contenido premium en función del interés de los visitantes, para aumentar su valor percibido y mejorar la experiencia digital.
  </td>
  <td style="text-align: center;">
    Criterios de aceptación:
    <br>Given que el gestor accede al panel de administración
    <br>When edita el contenido premium
    <br>Then los cambios se guardan correctamente en el sistema
    <br><br>Given que el contenido ha sido actualizado
    <br>When los visitantes acceden al contenido
    <br>Then se visualiza la versión más reciente en tiempo casi real
    <br><br>Given que existen usuarios accediendo al contenido
    <br>When se realizan actualizaciones
    <br>Then no se interrumpen ni afectan los accesos existentes
  </td>
  <td style="text-align: center;">
    EP03
  </td>
</tr>
<!-- US 25 -->
<tr>
  <td style="text-align: center;">
    US25
  </td>
  <td style="text-align: center;">
    Monitoreo de aforo en tiempo real
  </td>
  <td style="text-align: center;">
    Como gestor de museo público, quiero monitorear el número de visitantes en tiempo real, para controlar el aforo permitido y garantizar la seguridad dentro del recinto.
  </td>
  <td style="text-align: center;">
    Criterios de aceptación:
    <br>Given que existen sensores de conteo de visitantes
    <br>When las personas ingresan o salen del museo
    <br>Then el sistema registra automáticamente el número de visitantes
    <br><br>Given que se actualiza el flujo de visitantes
    <br>When el sistema procesa los datos
    <br>Then el conteo de aforo se actualiza en tiempo casi real
    <br><br>Given que el gestor accede al sistema
    <br>When visualiza el dashboard
    <br>Then el aforo actual se muestra de forma clara, indicando capacidad máxima y ocupación actual
  </td>
  <td style="text-align: center;">
    EP04
  </td>
</tr>
<!-- US 26 -->
<tr>
  <td style="text-align: center;">
    US26
  </td>
  <td style="text-align: center;">
    Alertas por exceso de aforo
  </td>
  <td style="text-align: center;">
    Como gestor de museo público, quiero recibir alertas cuando se supere el aforo permitido, para tomar acciones inmediatas y garantizar la seguridad de los visitantes.
  </td>
  <td style="text-align: center;">
    Criterios de aceptación:
    <br>Given que el aforo máximo está configurado
    <br>When el número de visitantes supera ese límite
    <br>Then el sistema envía una notificación automática al gestor
    <br><br>Given que el gestor administra el sistema
    <br>When configura los límites de aforo
    <br>Then el sistema respeta los valores definidos para generar alertas
    <br><br>Given que ocurre un incremento en el número de visitantes
    <br>When se alcanza o supera el límite
    <br>Then la alerta se genera en tiempo casi real
  </td>
  <td style="text-align: center;">
    EP04
  </td>
</tr>
<!-- US 27 -->
<tr>
  <td style="text-align: center;">
    US27
  </td>
  <td style="text-align: center;">
    Control de flujo de visitantes por sala
  </td>
  <td style="text-align: center;">
    Como gestor de museo público, quiero controlar el flujo de visitantes entre salas, para evitar congestión y garantizar una circulación segura dentro del museo.
  </td>
  <td style="text-align: center;">
    Criterios de aceptación:
    <br>Given que existen sensores de conteo en cada sala
    <br>When los visitantes ingresan o salen de una sala
    <br>Then el sistema registra automáticamente las entradas y salidas
    <br><br>Given que el sistema procesa los datos de flujo
    <br>When el gestor accede al dashboard
    <br>Then se muestran métricas de ocupación por cada sala
    <br><br>Given que el gestor visualiza la información
    <br>When consulta el estado de las salas
    <br>Then los datos se presentan de forma clara, indicando posibles zonas de congestión
  </td>
  <td style="text-align: center;">
    EP04
  </td>
</tr>
<!-- US 28 -->
<tr>
  <td style="text-align: center;">
    US28
  </td>
  <td style="text-align: center;">
    Historial de aforo
  </td>
  <td style="text-align: center;">
    Como gestor de museo público, quiero acceder al historial de aforo registrado, para evaluar el cumplimiento de normativas y analizar el comportamiento de visitantes en distintos periodos.
  </td>
  <td style="text-align: center;">
    Criterios de aceptación:
    <br>Given que el sistema registra datos de aforo
    <br>When se almacenan las interacciones de entrada y salida
    <br>Then la información se guarda correctamente en el historial
    <br><br>Given que el gestor accede al sistema
    <br>When realiza una consulta por rango de fechas
    <br>Then el sistema muestra los datos históricos correspondientes
    <br><br>Given que el gestor necesita analizar o reportar información
    <br>When solicita la exportación de datos
    <br>Then el sistema permite descargar el historial en un formato compatible
  </td>
  <td style="text-align: center;">
    EP04
  </td>
</tr>
<!-- US 29 -->
<tr>
  <td style="text-align: center;">
    US29
  </td>
  <td style="text-align: center;">
    Visualización de zonas congestionadas
  </td>
  <td style="text-align: center;">
    Como gestor de museo público, quiero identificar zonas con alta concentración de visitantes mediante una visualización clara, para mejorar la distribución y evitar congestiones.
  </td>
  <td style="text-align: center;">
    Criterios de aceptación:
    <br>Given que existen datos de flujo de visitantes por sala
    <br>When el sistema procesa la información
    <br>Then se genera un mapa visual que representa la concentración de personas por zona
    <br><br>Given que se registran cambios en el flujo de visitantes
    <br>When el sistema actualiza los datos
    <br>Then la visualización se actualiza de forma periódica o en tiempo casi real
    <br><br>Given que el gestor accede al dashboard
    <br>When visualiza el mapa
    <br>Then las zonas de alta, media y baja concentración se diferencian claramente y son fáciles de interpretar
  </td>
  <td style="text-align: center;">
    EP04
  </td>
</tr>
<!-- US 30 -->
<tr>
  <td style="text-align: center;">
    US30
  </td>
  <td style="text-align: center;">
    Cumplimiento de normativas de aforo y seguridad
  </td>
  <td style="text-align: center;">
    Como gestor de museo público, quiero asegurar el cumplimiento de las normativas de aforo y seguridad, para evitar sanciones y garantizar la protección de los visitantes.
  </td>
  <td style="text-align: center;">
    Criterios de aceptación:
    <br>Given que el gestor configura las reglas de aforo y seguridad
    <br>When el sistema monitorea el flujo de visitantes
    <br>Then se valida automáticamente el cumplimiento de las normativas definidas
    <br><br>Given que el sistema está en funcionamiento
    <br>When se registran cambios en el aforo
    <br>Then el monitoreo se realiza de forma continua en tiempo casi real
    <br><br>Given que el gestor accede al sistema
    <br>When visualiza el estado de cumplimiento
    <br>Then se muestra la última hora de actualización y el estado actual (cumple/no cumple)
    <br><br>Given que ocurren eventos relacionados al aforo
    <br>When el sistema registra la información
    <br>Then se almacena un historial de cumplimiento para auditoría
  </td>
  <td style="text-align: center;">
    EP04
  </td>
</tr>
  <!-- US 31 -->
<tr>
  <td style="text-align: center;">
    US31
  </td>
  <td style="text-align: center;">
    Acceso remoto al sistema de monitoreo
  </td>
  <td style="text-align: center;">
    Como gestor del museo, quiero acceder al sistema de monitoreo desde cualquier dispositivo con conexión a internet, para supervisar el estado del museo de forma remota y en tiempo real.
  </td>
  <td style="text-align: center;">
    Criterios de aceptación:
    <br>Given que el gestor dispone de un dispositivo con acceso a internet
    <br>When accede al sistema mediante un navegador web
    <br>Then puede visualizar el dashboard de monitoreo sin necesidad de instalación
    <br><br>Given que el gestor accede desde distintos dispositivos
    <br>When visualiza la interfaz
    <br>Then el sistema es compatible con dispositivos móviles y de escritorio (diseño responsive)
    <br><br>Given que el gestor accede al sistema
    <br>When inicia sesión
    <br>Then el acceso se realiza de forma segura mediante autenticación válida
  </td>
  <td style="text-align: center;">
    EP04
  </td>
</tr>
<!-- US 32 -->
<tr>
  <td style="text-align: center;">
    US32
  </td>
  <td style="text-align: center;">
    Redirección de flujo para prevención de congestión
  </td>
  <td style="text-align: center;">
    Como gestor del museo, quiero aplicar acciones de control cuando se detecten zonas congestionadas, para redistribuir a los visitantes y garantizar su seguridad dentro del museo.
  </td>
  <td style="text-align: center;">
    Criterios de aceptación:
    <br>Given que el sistema detecta una zona con alta congestión
    <br>When se supera el umbral definido
    <br>Then el sistema genera una recomendación o acción para redirigir el flujo de visitantes
    <br><br>Given que el gestor recibe la recomendación
    <br>When consulta el dashboard
    <br>Then puede visualizar acciones sugeridas para reducir la congestión
    <br><br>Given que se aplican medidas de redistribución
    <br>When el flujo de visitantes cambia
    <br>Then el sistema actualiza los datos en tiempo casi real
  </td>
  <td style="text-align: center;">
    EP04
  </td>
</tr>
<!-- US 33 -->
<tr>
  <td style="text-align: center;">
    US33
  </td>
  <td style="text-align: center;">
    Acceso a contenido mediante QR
  </td>
  <td style="text-align: center;">
    Como visitante del museo, quiero escanear códigos QR para acceder a información digital de las obras de forma rápida y sin fricción.
  </td>
  <td style="text-align: center;">
    Criterios de aceptación:
    <br>Given que el visitante se encuentra dentro del museo
    <br>When escanea un código QR válido
    <br>Then se muestra el contenido digital correspondiente a la obra
    <br><br>Given que el visitante escanea un código QR inválido o dañado
    <br>When intenta acceder al contenido
    <br>Then el sistema muestra un mensaje de “Contenido no disponible”
    <br><br>Given que el visitante accede al contenido
    <br>When se carga la información
    <br>Then el contenido se muestra en menos de 3 segundos sin necesidad de instalar una aplicación
  </td>
  <td style="text-align: center;">
    EP05
  </td>
</tr>
<!-- US 34 -->
<tr>
  <td style="text-align: center;">
    US34
  </td>
  <td style="text-align: center;">
    Acceso a contenido sin instalación de aplicaciones
  </td>
  <td style="text-align: center;">
    Como visitante del museo, quiero acceder al contenido digital directamente desde mi navegador sin necesidad de descargar aplicaciones, para tener una experiencia rápida y accesible.
  </td>
  <td style="text-align: center;">
    Criterios de aceptación:
    <br>Given que el visitante accede a un enlace de contenido
    <br>When lo abre desde su navegador móvil o de escritorio
    <br>Then el contenido se visualiza correctamente sin requerir instalación de aplicaciones
    <br><br>Given que el visitante utiliza distintos dispositivos
    <br>When accede al contenido
    <br>Then la experiencia es compatible con los navegadores más comunes
    <br><br>Given que el visitante accede al contenido
    <br>When se carga la página
    <br>Then el tiempo de carga es menor a 3 segundos en condiciones normales
  </td>
  <td style="text-align: center;">
    EP05
  </td>
</tr>
<!-- US 35 -->
<tr>
  <td style="text-align: center;">
    US35
  </td>
  <td style="text-align: center;">
    Visualización de contenido multimedia
  </td>
  <td style="text-align: center;">
    Como visitante del museo, quiero visualizar contenido multimedia (imágenes, audio y video) asociado a las obras, para enriquecer mi experiencia durante el recorrido.
  </td>
  <td style="text-align: center;">
    Criterios de aceptación:
    <br>Given que el contenido de una obra incluye elementos multimedia
    <br>When el visitante accede al contenido
    <br>Then se muestran correctamente imágenes, audio o video asociados
    <br><br>Given que el contenido incluye audio o video
    <br>When el visitante reproduce el contenido
    <br>Then este se reproduce sin errores y con controles de reproducción (play/pausa)
    <br><br>Given que el visitante accede desde un dispositivo móvil o de escritorio
    <br>When visualiza el contenido multimedia
    <br>Then este se adapta correctamente al tamaño de pantalla
  </td>
  <td style="text-align: center;">
    EP05
  </td>
</tr>
<!-- US 36 -->
<tr>
  <td style="text-align: center;">
    US36
  </td>
  <td style="text-align: center;">
    Navegación entre contenidos de obras
  </td>
  <td style="text-align: center;">
    Como visitante del museo, quiero navegar fácilmente entre los contenidos de distintas obras, para mejorar mi recorrido y explorar el museo de forma continua.
  </td>
  <td style="text-align: center;">
    Criterios de aceptación:
    <br>Given que el visitante se encuentra visualizando una obra
    <br>When selecciona otra obra desde la interfaz
    <br>Then el sistema carga el contenido correspondiente a la nueva obra
    <br><br>Given que el visitante navega entre contenidos
    <br>When cambia de una obra a otra
    <br>Then la transición se realiza sin recargar completamente la página
    <br><br>Given que el visitante accede a múltiples obras
    <br>When utiliza la navegación
    <br>Then puede identificar claramente en qué obra se encuentra actualmente
  </td>
  <td style="text-align: center;">
    EP05
  </td>
</tr>
<!-- US 37 -->
<tr>
  <td style="text-align: center;">
    US37
  </td>
  <td style="text-align: center;">
    Recomendaciones de recorrido personalizadas
  </td>
  <td style="text-align: center;">
    Como visitante del museo, quiero recibir sugerencias de recorrido basadas en la disponibilidad de las salas y mi interacción, para optimizar mi visita y evitar zonas congestionadas.
  </td>
  <td style="text-align: center;">
    Criterios de aceptación:
    <br>Given que el sistema dispone de datos de afluencia por sala
    <br>When el visitante accede al contenido
    <br>Then se muestran sugerencias de salas con menor congestión
    <br><br>Given que el visitante ha interactuado con ciertas obras
    <br>When el sistema analiza su comportamiento
    <br>Then se recomiendan obras o salas relacionadas
    <br><br>Given que el visitante visualiza las recomendaciones
    <br>When selecciona una sugerencia
    <br>Then puede navegar directamente al contenido de la obra o sala recomendada
  </td>
  <td style="text-align: center;">
    EP05
  </td>
</tr>
<!-- US 38 -->
<tr>
  <td style="text-align: center;">
    US38
  </td>
  <td style="text-align: center;">
    Acceso a contenido exclusivo dentro del museo
  </td>
  <td style="text-align: center;">
    Como visitante del museo, quiero acceder a contenido exclusivo únicamente dentro del recinto, para enriquecer mi experiencia durante la visita.
  </td>
  <td style="text-align: center;">
    Criterios de aceptación:
    <br>Given que el visitante se encuentra dentro del museo
    <br>When accede al contenido mediante QR o NFC
    <br>Then el sistema desbloquea el contenido exclusivo
    <br><br>Given que el visitante intenta acceder al contenido fuera del museo
    <br>When abre el enlace
    <br>Then el sistema restringe el acceso y muestra un mensaje indicando que el contenido es exclusivo del recinto
    <br><br>Given que el sistema valida la ubicación o contexto de acceso
    <br>When el visitante solicita contenido exclusivo
    <br>Then se verifica correctamente si cumple las condiciones de acceso
  </td>
  <td style="text-align: center;">
    EP05
  </td>
</tr>
<!-- US 39 -->
<tr>
  <td style="text-align: center;">
    US39
  </td>
  <td style="text-align: center;">
    Sistema de recompensas e insignias digitales
  </td>
  <td style="text-align: center;">
    Como visitante del museo, quiero obtener insignias digitales al interactuar con las obras, para motivar mi recorrido y hacer la experiencia más dinámica.
  </td>
  <td style="text-align: center;">
    Criterios de aceptación:
    <br>Given que el visitante interactúa con una obra (QR/NFC)
    <br>When completa la visualización del contenido
    <br>Then recibe una insignia digital asociada a esa obra
    <br><br>Given que el visitante obtiene insignias
    <br>When accede a su historial de interacción
    <br>Then puede visualizar las insignias obtenidas durante su recorrido
    <br><br>Given que el visitante interactúa con múltiples obras
    <br>When cumple ciertos criterios (ej: número de obras visitadas)
    <br>Then el sistema puede otorgar insignias adicionales o logros especiales
  </td>
  <td style="text-align: center;">
    EP05
  </td>
</tr>

  <!-- US 40 -->
  <tr>
  <td style="text-align: center;">
    US40
  </td>
  <td style="text-align: center;">
    Carga rápida de contenido
  </td>
  <td style="text-align: center;">
    Como visitante del museo, quiero que el contenido digital cargue rápidamente, para no interrumpir mi experiencia durante el recorrido.
  </td>
  <td style="text-align: center;">
    Criterios de aceptación:
    <br>Given que el visitante accede a contenido digital
    <br>When el sistema carga la información
    <br>Then el tiempo de carga es menor a 3 segundos en condiciones normales de red
    <br><br>Given que el visitante accede desde un dispositivo móvil
    <br>When visualiza el contenido
    <br>Then la carga es eficiente y optimizada para conexiones móviles
    <br><br>Given que el contenido incluye elementos multimedia
    <br>When se carga la página
    <br>Then los elementos se muestran progresivamente sin bloquear la interacción
  </td>
  <td style="text-align: center;">
    EP05
  </td>
</tr>
<!-- US 41 -->
<tr>
  <td style="text-align: center;">
    US41
  </td>
  <td style="text-align: center;">
    Dashboard de afluencia por sala
  </td>
  <td style="text-align: center;">
    Como gestor del museo, quiero visualizar la afluencia de visitantes por sala en un dashboard interactivo, para tomar decisiones rápidas y mejorar la gestión del flujo dentro del museo.
  </td>
  <td style="text-align: center;">
    Criterios de aceptación:
    <br>Given que los sensores de flujo están activos
    <br>When el sistema recibe datos de visitantes
    <br>Then el dashboard muestra la afluencia por sala en tiempo casi real
    <br><br>Given que el gestor accede al dashboard
    <br>When visualiza la información
    <br>Then se presentan gráficos claros que facilitan la interpretación de los datos
    <br><br>Given que el flujo de visitantes cambia
    <br>When el sistema actualiza los datos
    <br>Then la información se refresca automáticamente sin necesidad de recargar la página
  </td>
  <td style="text-align: center;">
    EP06
  </td>
</tr>
 <!-- US 42 -->
<tr>
  <td style="text-align: center;">
    US42
  </td>
  <td style="text-align: center;">
    Análisis de permanencia por obra
  </td>
  <td style="text-align: center;">
    Como gestor del museo, quiero conocer el tiempo de permanencia de los visitantes en cada obra, para medir el nivel de engagement y evaluar el interés del público.
  </td>
  <td style="text-align: center;">
    Criterios de aceptación:
    <br>Given que los visitantes interactúan con el contenido de una obra
    <br>When el sistema registra la duración de la interacción
    <br>Then se calcula el tiempo de permanencia por visita
    <br><br>Given que el gestor accede al dashboard
    <br>When consulta una obra específica
    <br>Then se muestra el tiempo promedio de permanencia
    <br><br>Given que existen múltiples registros de interacción
    <br>When el sistema procesa los datos
    <br>Then se presentan métricas agregadas (promedio, máximo y mínimo) de permanencia
  </td>
  <td style="text-align: center;">
    EP06
  </td>
</tr>
 <!-- US 43 -->
<tr>
  <td style="text-align: center;">
    US43
  </td>
  <td style="text-align: center;">
    Ranking de obras más visitadas
  </td>
  <td style="text-align: center;">
    Como curador del museo, quiero identificar las obras más visitadas mediante un ranking, para optimizar la disposición y planificación de las exhibiciones.
  </td>
  <td style="text-align: center;">
    Criterios de aceptación:
    <br>Given que existen datos de visitas por obra
    <br>When el sistema procesa la información
    <br>Then se genera un ranking ordenado de mayor a menor número de visitas
    <br><br>Given que el curador accede al dashboard
    <br>When visualiza el ranking
    <br>Then puede identificar fácilmente las obras más populares
    <br><br>Given que el curador necesita analizar diferentes periodos
    <br>When aplica filtros por fecha
    <br>Then el ranking se actualiza según el rango seleccionado
  </td>
  <td style="text-align: center;">
    EP06
  </td>
</tr>
<!-- US 44 -->
<tr>
  <td style="text-align: center;">
    US44
  </td>
  <td style="text-align: center;">
    Detección de obras con baja interacción
  </td>
  <td style="text-align: center;">
    Como curador del museo, quiero identificar obras con baja interacción mediante métricas de visitas y permanencia, para replantear su presentación y mejorar el interés del público.
  </td>
  <td style="text-align: center;">
    Criterios de aceptación:
    <br>Given que existen datos de visitas y permanencia por obra
    <br>When el sistema analiza las métricas
    <br>Then identifica las obras con valores por debajo de un umbral definido como baja interacción
    <br><br>Given que el curador accede al dashboard
    <br>When consulta las obras con bajo rendimiento
    <br>Then se muestra una lista clara de obras clasificadas como baja interacción
    <br><br>Given que el sistema permite configuración
    <br>When el curador ajusta el umbral de interacción
    <br>Then la lista de obras se actualiza según los nuevos criterios
  </td>
  <td style="text-align: center;">
    EP06
  </td>
</tr>
 <!-- US 45 -->
<tr>
  <td style="text-align: center;">
    US45
  </td>
  <td style="text-align: center;">
    Exportación de reportes analíticos
  </td>
  <td style="text-align: center;">
    Como administrador del museo, quiero exportar reportes analíticos de las exhibiciones, para presentarlos a patrocinadores y respaldar la toma de decisiones.
  </td>
  <td style="text-align: center;">
    Criterios de aceptación:
    <br>Given que existen datos analíticos disponibles
    <br>When el administrador solicita la exportación
    <br>Then el sistema genera un archivo descargable en formato PDF o Excel
    <br><br>Given que el administrador configura filtros (fecha, sala, obra)
    <br>When genera el reporte
    <br>Then el archivo contiene únicamente la información filtrada
    <br><br>Given que el reporte ha sido generado
    <br>When el administrador descarga el archivo
    <br>Then este incluye métricas clave como visitas, permanencia y ranking de obras
  </td>
  <td style="text-align: center;">
    EP06
  </td>
</tr>
<!-- US 46 -->
<tr>
  <td style="text-align: center;">
    US46
  </td>
  <td style="text-align: center;">
    Alertas inteligentes de saturación por sala
  </td>
  <td style="text-align: center;">
    Como gestor del museo, quiero recibir alertas inteligentes cuando una sala alcance niveles críticos de ocupación, para tomar decisiones rápidas y optimizar la distribución de visitantes.
  </td>
  <td style="text-align: center;">
    Criterios de aceptación:
    <br>Given que existe un umbral de ocupación definido por sala
    <br>When el número de visitantes supera el límite establecido
    <br>Then el sistema genera una alerta en tiempo casi real
    <br><br>Given que el gestor recibe una alerta
    <br>When accede al dashboard
    <br>Then puede visualizar la sala afectada y su nivel de ocupación
    <br><br>Given que el sistema registra datos históricos de afluencia
    <br>When analiza patrones de saturación
    <br>Then puede anticipar posibles picos y generar alertas preventivas
  </td>
  <td style="text-align: center;">
    EP06
  </td>
</tr>
<!-- US 47 -->
<tr>
  <td style="text-align: center;">
    US47
  </td>
  <td style="text-align: center;">
    Análisis histórico comparativo
  </td>
  <td style="text-align: center;">
    Como gestor del museo, quiero comparar datos históricos de visitas e interacción entre diferentes periodos, para mejorar la planificación y toma de decisiones estratégicas.
  </td>
  <td style="text-align: center;">
    Criterios de aceptación:
    <br>Given que existen datos históricos de visitas e interacción
    <br>When el gestor selecciona diferentes rangos de fechas
    <br>Then el sistema muestra métricas comparativas entre los periodos seleccionados
    <br><br>Given que el gestor accede al dashboard
    <br>When visualiza el análisis histórico
    <br>Then se presentan gráficos claros que permiten identificar tendencias
    <br><br>Given que existen variaciones en los datos
    <br>When el sistema analiza los periodos
    <br>Then se destacan incrementos o disminuciones en las métricas clave
  </td>
  <td style="text-align: center;">
    EP06
  </td>
</tr>
<!-- US 48 -->
<tr>
  <td style="text-align: center;">
    US48
  </td>
  <td style="text-align: center;">
    Análisis de distribución y flujo de visitantes por sala
  </td>
  <td style="text-align: center;">
    Como gestor del museo, quiero visualizar la distribución y el flujo de visitantes entre las diferentes salas, para entender los patrones de movimiento y optimizar la organización del espacio.
  </td>
  <td style="text-align: center;">
    Criterios de aceptación:
    <br>Given que existen datos de visitantes por sala
    <br>When el sistema procesa la información
    <br>Then se muestra la distribución de visitantes en cada sala mediante una visualización clara
    <br><br>Given que el gestor accede al dashboard
    <br>When visualiza la información
    <br>Then puede identificar las salas con mayor y menor concentración de visitantes
    <br><br>Given que existen datos de movimiento entre salas
    <br>When el sistema analiza los patrones de flujo
    <br>Then se representan los recorridos o transiciones más frecuentes entre salas
  </td>
  <td style="text-align: center;">
    EP06
  </td>
</tr>
 <!-- US 49 -->
<tr>
  <td style="text-align: center;">
    US49
  </td>
  <td style="text-align: center;">
    Acceso rápido sin registro obligatorio
  </td>
  <td style="text-align: center;">
    Como visitante del museo, quiero acceder al contenido digital sin necesidad de registrarme, para tener una experiencia rápida y sin fricción.
  </td>
  <td style="text-align: center;">
    Criterios de aceptación:
    <br>Given que el visitante accede al contenido mediante QR o enlace
    <br>When abre el contenido en su dispositivo
    <br>Then puede visualizarlo sin necesidad de iniciar sesión o registrarse
    <br><br>Given que el visitante navega por el contenido
    <br>When interactúa con las obras
    <br>Then el sistema no bloquea funcionalidades básicas por falta de registro
    <br><br>Given que el sistema ofrece registro opcional
    <br>When el visitante decide registrarse
    <br>Then puede hacerlo sin afectar su acceso inmediato al contenido
  </td>
  <td style="text-align: center;">
    EP05
  </td>
</tr>
<!-- US 50 -->
<tr>
  <td style="text-align: center;">
    US50
  </td>
  <td style="text-align: center;">
    Accesibilidad del contenido digital
  </td>
  <td style="text-align: center;">
    Como visitante del museo, quiero que el contenido digital sea accesible (texto legible, audio y adaptación a dispositivos), para comprender mejor la información y tener una experiencia inclusiva.
  </td>
  <td style="text-align: center;">
    Criterios de aceptación:
    <br>Given que el visitante accede al contenido
    <br>When visualiza la información
    <br>Then el texto es legible y con tamaño adecuado en distintos dispositivos
    <br><br>Given que el contenido incluye opciones de accesibilidad
    <br>When el visitante lo requiere
    <br>Then puede reproducir audio asociado a la obra
    <br><br>Given que el visitante accede desde un dispositivo móvil
    <br>When navega por el contenido
    <br>Then la interfaz se adapta correctamente al tamaño de pantalla
  </td>
  <td style="text-align: center;">
    EP05
  </td>
</tr>
 <!-- US 51 -->
<tr>
  <td style="text-align: center;">
    US51
  </td>
  <td style="text-align: center;">
    Alertas de comportamiento por interacción
  </td>
  <td style="text-align: center;">
    Como administrador del museo, quiero recibir alertas cuando una obra tenga niveles altos o bajos de interacción, para tomar acciones más precisas en la gestión de exhibiciones.
  </td>
  <td style="text-align: center;">
    Criterios de aceptación:
    <br>Given que existen umbrales configurables de interacción
    <br>When una obra supera o cae por debajo de los valores definidos
    <br>Then el sistema genera automáticamente una alerta
    <br><br>Given que el administrador recibe una alerta
    <br>When accede al sistema
    <br>Then puede visualizar qué obra generó la alerta y su nivel de interacción
    <br><br>Given que el sistema detecta cambios en la interacción
    <br>When se actualizan los datos
    <br>Then las alertas se activan en tiempo casi real
  </td>
  <td style="text-align: center;">
    EP02
  </td>
</tr>
<!-- US 52 -->
<tr>
  <td style="text-align: center;">
    US52
  </td>
  <td style="text-align: center;">
    Análisis de tendencias históricas de interacción
  </td>
  <td style="text-align: center;">
    Como administrador del museo, quiero visualizar la evolución del interés de los visitantes a lo largo del tiempo, para identificar tendencias y mejorar la planificación de exhibiciones.
  </td>
  <td style="text-align: center;">
    Criterios de aceptación:
    <br>Given que el sistema almacena datos históricos de interacción
    <br>When el administrador accede al dashboard
    <br>Then se muestran gráficos que reflejan la evolución de las métricas a lo largo del tiempo
    <br><br>Given que el administrador selecciona un rango de fechas
    <br>When el sistema procesa la información
    <br>Then se visualizan tendencias (incremento o disminución) en las métricas clave
    <br><br>Given que existen variaciones significativas en los datos
    <br>When el sistema analiza la información histórica
    <br>Then se destacan patrones relevantes que facilitan la interpretación
  </td>
  <td style="text-align: center;">
    EP02
  </td>
</tr>
<!-- US 53 -->
<tr>
  <td style="text-align: center;">
    US53
  </td>
  <td style="text-align: center;">
    Acceso temporal a contenido
  </td>
  <td style="text-align: center;">
    Como visitante del museo, quiero acceder al contenido digital por un tiempo limitado, para disfrutar de la experiencia durante mi visita sin necesidad de un acceso permanente.
  </td>
  <td style="text-align: center;">
    Criterios de aceptación:
    <br>Given que el visitante accede al contenido mediante QR o NFC
    <br>When el sistema valida el acceso
    <br>Then se habilita el contenido por un tiempo limitado definido
    <br><br>Given que el tiempo de acceso ha expirado
    <br>When el visitante intenta acceder nuevamente
    <br>Then el sistema restringe el acceso y muestra un mensaje informativo
    <br><br>Given que el sistema gestiona accesos temporales
    <br>When se registra una sesión
    <br>Then el tiempo de acceso se controla automáticamente
  </td>
  <td style="text-align: center;">
    EP07
  </td>
</tr>
<!-- US 54 -->
<tr>
  <td style="text-align: center;">
    US54
  </td>
  <td style="text-align: center;">
    Acceso permanente mediante suscripción
  </td>
  <td style="text-align: center;">
    Como visitante del museo, quiero acceder de forma permanente al contenido digital mediante una suscripción, para consultar las obras en cualquier momento sin restricciones de tiempo.
  </td>
  <td style="text-align: center;">
    Criterios de aceptación:
    <br>Given que el visitante cuenta con una suscripción activa
    <br>When accede al contenido digital
    <br>Then el sistema permite el acceso sin limitación de tiempo
    <br><br>Given que la suscripción ha expirado
    <br>When el visitante intenta acceder al contenido
    <br>Then el sistema restringe el acceso y solicita renovación
    <br><br>Given que el sistema valida el estado de la suscripción
    <br>When el visitante inicia acceso
    <br>Then se verifica automáticamente la vigencia de la suscripción
  </td>
  <td style="text-align: center;">
    EP07
  </td>
</tr>
 
</table>

### 3.2. Impact Mapping

![Impact-Mapping](../assets/img/lean%20ux/Impact%20Mapping.jpg)

### 3.3. Product Backlog

| **# Orden** | **User Story Id** | **Título**                        | **Descripción**                                                                                                                                    | **Story Points (1/2/3/5/8)** |
| ----------- | ----------------- | --------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------- |
| 1           | US01              | Acceso a contenido mediante QR    | Como visitante quiero escanear un código QR para acceder al contenido digital de una obra para obtener información inmediata durante el recorrido. | 3                            |
| 2           | US02              | Acceso sin instalación            | Como visitante quiero acceder al contenido desde mi navegador sin instalar aplicaciones para tener una experiencia rápida y sin fricción.          | 2                            |
| 3           | US03              | Visualización multimedia          | Como visitante quiero visualizar contenido multimedia de las obras para comprender mejor su contexto y enriquecer mi experiencia.                  | 3                            |
| 4           | US04              | Contenido exclusivo               | Como visitante quiero acceder a contenido exclusivo dentro del museo para vivir una experiencia diferenciada.                                      | 3                            |
| 5           | US05              | Selección de idioma               | Como visitante quiero seleccionar el idioma del contenido para entender la información en mi idioma preferido.                                     | 2                            |
| 6           | US06              | Navegación entre obras            | Como visitante quiero navegar entre contenidos de distintas obras para explorar el museo de forma continua.                                        | 3                            |
| 7           | US07              | Acceso sin registro               | Como visitante quiero acceder al contenido sin necesidad de registrarme para ingresar rápidamente al sistema.                                      | 2                            |
| 8           | US08              | Carga rápida                      | Como visitante quiero que el contenido cargue en menos de 3 segundos para no perder tiempo durante mi recorrido.                                   | 3                            |
| 9           | US09              | Historial de obras                | Como visitante quiero ver las obras que ya visité para revisarlas nuevamente durante mi recorrido.                                                 | 3                            |
| 10          | US10              | Obras favoritas                   | Como visitante quiero marcar obras como favoritas para acceder fácilmente a ellas después.                                                         | 2                            |
| 11          | US11              | Recomendaciones de obras          | Como visitante quiero recibir recomendaciones basadas en mis interacciones para descubrir nuevas obras relevantes.                                 | 5                            |
| 12          | US12              | Rutas sugeridas                   | Como visitante quiero recibir sugerencias de recorrido para optimizar mi visita dentro del museo.                                                  | 5                            |
| 13          | US13              | Accesibilidad del contenido       | Como visitante quiero que el contenido sea accesible (audio, texto claro) para mejorar mi experiencia.                                             | 3                            |
| 14          | US14              | Registro de interacciones         | Como gestor quiero registrar las interacciones de los visitantes para analizar su comportamiento.                                                  | 5                            |
| 15          | US15              | Dashboard en tiempo real          | Como gestor quiero visualizar métricas en tiempo real para monitorear el comportamiento de los visitantes.                                         | 5                            |
| 16          | US16              | Ranking de obras                  | Como gestor quiero visualizar las obras más visitadas para identificar cuáles generan mayor interés.                                               | 3                            |
| 17          | US17              | Tiempo de interacción             | Como gestor quiero medir el tiempo de permanencia en cada obra para evaluar el nivel de engagement.                                                | 5                            |
| 18          | US18              | Baja interacción                  | Como gestor quiero detectar obras con bajo interés para tomar decisiones de mejora.                                                                | 3                            |
| 19          | US19              | Exportación de reportes           | Como gestor quiero exportar reportes para analizarlos y compartirlos con stakeholders.                                                             | 3                            |
| 20          | US20              | Análisis por horarios             | Como gestor quiero analizar visitas por franjas horarias para identificar horas pico.                                                              | 5                            |
| 21          | US21              | Tendencias históricas             | Como gestor quiero analizar tendencias en el tiempo para mejorar la planificación.                                                                 | 5                            |
| 22          | US22              | Control de aforo                  | Como gestor quiero monitorear la cantidad de visitantes en tiempo real para garantizar la seguridad.                                               | 5                            |
| 23          | US23              | Alertas de aforo                  | Como gestor quiero recibir alertas cuando se supere el límite de visitantes para actuar rápidamente.                                               | 3                            |
| 24          | US24              | Flujo por salas                   | Como gestor quiero visualizar el flujo de visitantes por sala para evitar congestión.                                                              | 5                            |
| 25          | US25              | Zonas congestionadas              | Como gestor quiero identificar zonas con alta concentración para mejorar la distribución de visitantes.                                            | 5                            |
| 26          | US26              | Recomendaciones operativas        | Como gestor quiero recibir recomendaciones para optimizar recursos y flujo del museo.                                                              | 5                            |
| 27          | US27              | Reportes de desempeño             | Como gestor quiero generar reportes integrales para evaluar resultados del museo.                                                                  | 5                            |
| 28          | US28              | Comparación de exhibiciones       | Como gestor quiero comparar exhibiciones para identificar oportunidades de mejora.                                                                 | 5                            |
| 29          | US29              | Métricas de ingresos              | Como gestor quiero visualizar ingresos por exhibición para optimizar la rentabilidad.                                                              | 5                            |
| 30          | US30              | Control de acceso                 | Como administrador quiero gestionar accesos y roles para proteger la información del sistema.                                                      | 3                            |
| 31          | US31              | Acceso remoto                     | Como gestor quiero acceder al sistema desde cualquier dispositivo para monitorear el museo en tiempo real.                                         | 3                            |
| 32          | US32              | Redirección de flujo              | Como gestor quiero redirigir visitantes en caso de congestión para mejorar la circulación.                                                         | 5                            |
| 33          | US33              | Acceso alternativo QR             | Como visitante quiero acceder al contenido mediante QR de forma confiable para evitar errores.                                                     | 2                            |
| 34          | US34              | Compatibilidad dispositivos       | Como visitante quiero que el sistema funcione en cualquier dispositivo para acceder sin problemas.                                                 | 2                            |
| 35          | US35              | Multimedia adaptable              | Como visitante quiero que el contenido multimedia se adapte a mi pantalla para mejorar la visualización.                                           | 3                            |
| 36          | US36              | Navegación fluida                 | Como visitante quiero cambiar entre obras sin recargar la página para una mejor experiencia.                                                       | 3                            |
| 37          | US37              | Recomendaciones inteligentes      | Como visitante quiero recomendaciones según afluencia para evitar zonas congestionadas.                                                            | 5                            |
| 38          | US38              | Validación de contenido exclusivo | Como visitante quiero que el contenido exclusivo solo funcione dentro del museo para mantener su valor.                                            | 3                            |
| 39          | US39              | Insignias digitales               | Como visitante quiero obtener logros por interactuar con obras para motivar mi recorrido.                                                          | 3                            |
| 40          | US40              | Rendimiento del sistema           | Como visitante quiero que el sistema responda rápido para no afectar mi experiencia.                                                               | 3                            |
| 41          | US41              | Dashboard de afluencia            | Como administrador quiero ver la afluencia por sala para tomar decisiones rápidas.                                                                 | 5                            |
| 42          | US42              | Permanencia en obras              | Como administrador quiero conocer el tiempo de permanencia para medir engagement.                                                                  | 5                            |
| 43          | US43              | Ranking curatorial                | Como curador quiero identificar obras populares para optimizar exhibiciones.                                                                       | 3                            |
| 44          | US44              | Detección de baja interacción     | Como curador quiero detectar obras con bajo interés para mejorarlas.                                                                               | 3                            |
| 45          | US45              | Exportación avanzada              | Como administrador quiero exportar reportes en varios formatos para presentaciones.                                                                | 3                            |
| 46          | US46              | Alertas de saturación             | Como administrador quiero recibir alertas de saturación para actuar rápidamente.                                                                   | 3                            |
| 47          | US47              | Análisis histórico                | Como administrador quiero comparar datos históricos para mejorar decisiones.                                                                       | 5                            |
| 48          | US48              | Distribución de visitantes        | Como administrador quiero visualizar la distribución para entender el flujo del museo.                                                             | 5                            |
| 49          | US49              | Acceso sin fricción               | Como museo quiero permitir acceso rápido sin login para mejorar la adopción.                                                                       | 2                            |
| 50          | US50              | Accesibilidad                     | Como visitante quiero contenido accesible para mejorar la experiencia general.                                                                     | 3                            |
| 51          | US51              | Alertas de comportamiento         | Como administrador quiero recibir alertas de interacción para tomar decisiones.                                                                    | 3                            |
| 52          | US52              | Tendencias de comportamiento      | Como administrador quiero analizar tendencias para mejorar la planificación.                                                                       | 5                            |
