### 3.1. User Stories

<table style="width: 100%; border-collapse: collapse;">
  
  <tr>
    <th style="text-align: center;">Epic/Story ID</th>
    <th style="text-align: center;">Título</th>
    <th style="text-align: center;">Descripción</th>
    <th style="text-align: center;">Criterios de Aceptación</th>
    <th style="text-align: center;">Relacionado con (Epic ID)</th>
  </tr>
  <!-- EPIC 1 -->
  <tr>
    <td style="text-align: center;">
    EP01
    </td>
    <td style="text-align: center;">
    Experiencia personalizada e interactiva
    </td>
    <td style="text-align: center;">
    Como museo privado, quiero acceder a contenido digital mediante códigos QR/NFC para enriquecer el recorrido y que sea una experiencia más atractiva y moderna.
    </td>
    <td style="text-align: center;">
    </td>
    <td style="text-align: center;">
    </td>
  </tr>
  <!-- EPIC 2 -->
  <tr>
    <td style="text-align: center;">
    EP02
    </td>
    <td style="text-align: center;">
    Inteligencia de negocio basada en comportamiento
    </td>
    <td style="text-align: center;">
    Como museo privado, quiero analizar cuáles exposiciones generan más interés y engagement para tomar decisiones estratégicas de marketing y curaduría.
    </td>
    <td style="text-align: center;">
    </td>
    <td style="text-align: center;">
    </td>
  </tr>
  <!-- EPIC 3 -->
  <tr>
    <td style="text-align: center;">
    EP03
    </td>
    <td style="text-align: center;">
    Optimización de ingresos y operación del museo
    </td>
    <td style="text-align: center;">
   Como gestor de museo privado, deseo gestionar y analizar el comportamiento de los visitantes y el uso de los recursos operativos, para maximizar los ingresos y mejorar la eficiencia de la operación del museo. 
    </td>
    <td style="text-align: center;">
    </td>
    <td style="text-align: center;">
    </td>
  </tr>
  <!-- EPIC 4 -->
  <tr>
    <td style="text-align: center;">
    EP04
    </td>
    <td style="text-align: center;">
    Control de aforo y cumplimiento de normativas
    </td>
    <td style="text-align: center;">
     Como administrador de un museo público, deseo monitorear y controlar el flujo de visitantes en tiempo real, para asegurar el cumplimiento de las normativas de aforo y garantizar la seguridad dentro del museo.
    </td>
    <td style="text-align: center;">
    </td>
    <td style="text-align: center;">
    </td>
  </tr>
  <!-- EPIC 5 -->
  <tr>
    <td style="text-align: center;">
    EP05
    </td>
    <td style="text-align: center;">
    Optimización de la experiencia del visitante
    </td>
    <td style="text-align: center;">
    Museo Público
    </td>
    <td style="text-align: center;">
    </td>
    <td style="text-align: center;">
    </td>
  </tr>
  <!-- EPIC 6 -->
  <tr>
    <td style="text-align: center;">
    EP06
    </td>
    <td style="text-align: center;">
    Toma de decisiones basada en datos
    </td>
    <td style="text-align: center;">
    Museo Público
    </td>
    <td style="text-align: center;">
    </td>
    <td style="text-align: center;">
    </td>
  </tr>
  <!-- EPIC 7 -->
  <tr>
    <td style="text-align: center;">
    EP07
    </td>
    <td style="text-align: center;">
    Usuarios dentro buscar información
    </td>
    <td style="text-align: center;">
    Como Museo, quiero que controlar quienes acceden a mis datos de mis exposiciones para no congestionar mi red
    </td>
    <td style="text-align: center;">
    </td>
    <td style="text-align: center;">
    </td>
  </tr>
 <!-- US01 -->
 <tr>
 <td style="text-align: center;">US01</td>
 <td style="text-align: center;">Acceso a contenido mediante QR</td>
 <td style="text-align: center;">Como museo privado, quiero que los visitantes escaneen un código QR para acceder al contenido digital de una obra.</td>
 <td style="text-align: center;">
 <br><br>Scenario 1: Acceso exitoso
 <br>Given un código QR válido
 <br>When el usuario lo escanea
 <br>Then el sistema muestra el contenido asociado
 <br><br>Scenario 2: QR inválido
 <br>Given un código QR inválido
 <br>When el usuario intenta acceder
 <br>Then el sistema muestra un error
 <br><br>Scenario 3: Rendimiento
 <br>Given una solicitud válida
 <br>When el sistema responde
 <br>Then el contenido carga en menos de 3 segundos
 </td>
 <td style="text-align: center;">EP01</td>
 </tr>
 <!-- US02 -->
 <tr>
 <td style="text-align: center;">US02</td>
 <td style="text-align: center;">Acceso mediante NFC</td>
 <td style="text-align: center;">Como museo privado, quiero que los visitantes accedan al contenido acercando su dispositivo a un punto NFC.</td>
 <td style="text-align: center;">
 <br><br>Scenario 1: Acceso válido
 <br>Given un dispositivo compatible
 <br>When el usuario acerca el dispositivo
 <br>Then el sistema muestra el contenido
 <br><br>Scenario 2: Dispositivo no compatible
 <br>Given un dispositivo no compatible
 <br>When intenta acceder
 <br>Then el sistema informa incompatibilidad
 <br><br>Scenario 3: Error de lectura
 <br>Given fallo en NFC
 <br>When se intenta acceder
 <br>Then el sistema no muestra contenido
 </td>
 <td style="text-align: center;">EP01</td>
 </tr>
 <!-- US03 -->
 <tr>
 <td style="text-align: center;">US03</td>
 <td style="text-align: center;">Visualización multimedia</td>
 <td style="text-align: center;">Como museo privado, quiero mostrar contenido multimedia para mejorar la comprensión.</td>
 <td style="text-align: center;">
 <br><br>Scenario 1: Visualización básica
 <br>Given contenido disponible
 <br>When el usuario accede
 <br>Then el sistema muestra texto e imágenes
 <br><br>Scenario 2: Reproducción
 <br>Given contenido multimedia
 <br>When el usuario reproduce
 <br>Then funciona correctamente
 <br><br>Scenario 3: Control
 <br>Given reproducción activa
 <br>When el usuario interactúa
 <br>Then puede pausar o reanudar
 </td>
 <td style="text-align: center;">EP01</td>
 </tr>
 <!-- US04 -->
 <tr>
 <td style="text-align: center;">US04</td>
 <td style="text-align: center;">Selección de idioma</td>
 <td style="text-align: center;"> Como Museo privado, quiero dar a escoger el idioma del contenido para ser más variado.</td>
 <td style="text-align: center;">
 <br><br>Scenario 1: Selección
 <br>Given múltiples idiomas
 <br>When el usuario selecciona uno
 <br>Then el sistema muestra el contenido en ese idioma
 <br><br>Scenario 2: Persistencia
 <br>Given una sesión activa
 <br>When el usuario navega
 <br>Then el idioma se mantiene
 </td>
 <td style="text-align: center;">EP01</td>
 </tr>
 <!-- US05 -->
 <tr>
 <td style="text-align: center;">US05</td>
 <td style="text-align: center;">Contenido por sala</td>
 <td style="text-align: center;"> Como Museo Privado, quiero dar contenido específico según la sala para así hacerlo más interactivo.</td>
 <td style="text-align: center;">
 <br><br>Scenario 1: Contenido correcto
 <br>Given una sala identificada
 <br>When el usuario accede
 <br>Then el sistema muestra contenido correspondiente
 <br><br>Scenario 2: Diferenciación
 <br>Given múltiples salas
 <br>When se accede
 <br>Then el contenido es distinto
 </td>
 <td style="text-align: center;">EP01</td>
 </tr>
 <!-- US06 -->
 <tr>
 <td style="text-align: center;">US06</td>
 <td style="text-align: center;">Historial de obras visitadas</td>
 <td style="text-align: center;"> Como Museo Privado, quiero dar contenido específico según la sala para así hacerlo más interactivo.</td>
 <td style="text-align: center;">
 <br><br>Scenario 1: Registro
 <br>Given interacción
 <br>When el usuario accede
 <br>Then el sistema guarda historial
 <br><br>Scenario 2: Consulta
 <br>Given historial existente
 <br>When el usuario consulta
 <br>Then el sistema lo muestra
 </td>
 <td style="text-align: center;">EP01</td>
 </tr>
 <!-- US07 -->
 <tr>
 <td style="text-align: center;">US07</td>
 <td style="text-align: center;">Recomendaciones de obras</td>
 <td style="text-align: center;"> Como museo privado, quiero dar sugerencias de obras relacionadas para intentar mejorarlas. </td>
 <td style="text-align: center;">
 <br><br>Scenario 1: Generación
 <br>Given historial
 <br>When el sistema analiza
 <br>Then genera recomendaciones
 <br><br>Scenario 2: Acceso
 <br>Given recomendaciones
 <br>When el usuario accede
 <br>Then puede navegar
 </td>
 <td style="text-align: center;">EP01</td>
 </tr>
 <!-- US08 -->
 <tr>
 <td style="text-align: center;">US08</td>
 <td style="text-align: center;">Interacción</td>
 <td style="text-align: center;"> Como museo privado, quiero que se marquen las obras favoritas para que se guarden.</td>
 <td style="text-align: center;">
 <br><br>Scenario 1: Marcar
 <br>Given una obra
 <br>When se marca
 <br>Then el sistema la guarda
 <br><br>Scenario 2: Desmarcar
 <br>Given una obra marcada
 <br>When se desmarca
 <br>Then se elimina
 </td>
 <td style="text-align: center;">EP01</td>
 </tr>
 <!-- US09 -->
 <tr>
 <td style="text-align: center;">US09</td>
 <td style="text-align: center;">Conteo</td>
 <td style="text-align: center;"> Como museo privado, quiero ver cuántas veces se accede a cada obra para tener información.</td>
 <td style="text-align: center;">
 <br><br>Scenario 1
 <br>Given acceso
 <br>When ocurre
 <br>Then se registra
 <br><br>Scenario 2
 <br>Given datos
 <br>When se consultan
 <br>Then se muestran
 </td>
 <td>EP02</td>
 </tr>
 <!-- US10 -->
 <tr>
 <td style="text-align: center;">US10</td>
 <td style="text-align: center;">Tiempo de interacción</td>
 <td style="text-align: center;"> Como museo privado, quiero medir cuánto tiempo pasan los usuarios en cada contenido para el feedback de la experiencia. </td>
 <td style="text-align: center;">
 <br><br>Scenario 1: Registro de tiempo
 <br>Given una sesión activa
 <br>When el usuario interactúa con el contenido
 <br>Then el sistema registra la duración
 <br><br>Scenario 2: Cálculo promedio
 <br>Given múltiples sesiones
 <br>When se procesan los datos
 <br>Then el sistema calcula el promedio
 <br><br>Scenario 3: Filtrado
 <br>Given sesiones atípicas
 <br>When se analizan
 <br>Then el sistema las excluye
 </td>
 <td style="text-align: center;">EP02</td>
 </tr>
 <!-- US11 -->
 <tr>
 <td style="text-align: center;">US11</td>
 <td style="text-align: center;">Ranking de obras</td>
 <td style="text-align: center;"> Como museo privado, quiero ver un ranking de obras más visitadas para mejorar la experiencia. </td>
 <td style="text-align: center;">
 <br><br>Scenario 1: Generación de ranking
 <br>Given datos de visitas
 <br>When se procesan
 <br>Then el sistema ordena las obras
 <br><br>Scenario 2: Actualización
 <br>Given nuevos datos
 <br>When se registran
 <br>Then el ranking se actualiza
 </td>
 <td style="text-align: center;">EP02</td>
 </tr>
 <!-- US12 -->
 <tr>
 <td style="text-align: center;">US12</td>
 <td style="text-align: center;">Análisis por horario</td>
 <td style="text-align: center;"> Como museo privado, quiero ver en qué horas hay más interacción para mejorar la gestión. </td>
 <td style="text-align: center;">
 <br><br>Scenario 1: Agrupación
 <br>Given datos registrados
 <br>When se agrupan
 <br>Then el sistema los organiza por hora
 <br><br>Scenario 2: Consulta
 <br>Given datos agrupados
 <br>When se consultan
 <br>Then se muestran correctamente
 </td>
 <td style="text-align: center;">EP02</td>
 </tr>
 <!-- US13 -->
 <tr>
 <td style="text-align: center;">US13</td>
 <td style="text-align: center;">Baja interacción</td>
 <td style="text-align: center;"> Como museo privado, quiero detectar obras con poco interés para decisiones administrativas.</td>
 <td style="text-align: center;">
 <br><br>Scenario 1: Identificación
 <br>Given un umbral definido
 <br>When una obra no lo alcanza
 <br>Then el sistema la identifica
 <br><br>Scenario 2: Consulta
 <br>Given obras identificadas
 <br>When se consultan
 <br>Then se muestran
 </td>
 <td style="text-align: center;">EP02</td>
 </tr>
 <!-- US14 -->
 <tr>
 <td style="text-align: center;">US14</td>
 <td style="text-align: center;">Dashboard en tiempo real</td>
 <td style="text-align: center;"> Como museo privado, quiero visualizar métricas en tiempo real para acciones a tiempo real. </td>
 <td style="text-align: center;">
 <br><br>Scenario 1: Actualización
 <br>Given datos en flujo
 <br>When cambian
 <br>Then el sistema se actualiza automáticamente
 <br><br>Scenario 2: Consulta
 <br>Given métricas
 <br>When se accede
 <br>Then se muestran actualizadas
 </td>
 <td style="text-align: center;">EP02</td>
 </tr>
 <!-- US15 -->
 <tr>
 <td style="text-align: center;">US15</td>
 <td style="text-align: center;">Exportación de reportes</td>
 <td style="text-align: center;"> Como museo privado, quiero exportar datos para análisis externo.</td>
  <td style="text-align: center;">
 <br><br>Scenario 1: Exportación válida
 <br>Given datos disponibles
 <br>When se solicita exportación
 <br>Then el sistema genera un archivo
 <br><br>Scenario 2: Contenido
 <br>Given un archivo generado
 <br>When se revisa
 <br>Then contiene información correcta
 </td>
 <td style="text-align: center;">EP02</td>
 </tr>
 <!-- US16 -->
 <tr>
 <td style="text-align: center;">US16</td>
 <td style="text-align: center;">Segmentación por tipo de contenido</td>
 <td style="text-align: center;"> Como museo privado, quiero saber qué tipo de contenido genera más engagement para darle más cuidados.</td>
 <td style="text-align: center;">
 <br><br>Scenario 1: Clasificación
 <br>Given diferentes tipos
 <br>When se analizan
 <br>Then el sistema los clasifica
 <br><br>Scenario 2: Comparación
 <br>Given datos segmentados
 <br>When se consultan
 <br>Then se muestran diferencias
 </td>
 <td style="text-align: center;">EP02</td>
 </tr>
 <!-- US17 -->
 <tr>
 <td style="text-align: center;">US17</td>
 <td style="text-align: center;">Visualizar metricas de ingresos</td>
 <td style="text-align: center;"> Como gestor de museo privado, quiero visualizar métricas de ingresos generados por las exhibiciones, para identificar cuáles generan mayor rentabilidad.</td>
 <td style="text-align: center;">
 <br><br>Scenario 1: Visualización
 <br>Given datos financieros
 <br>When se consultan
 <br>Then el sistema muestra ingresos
 <br><br>Scenario 2: Detalle
 <br>Given datos disponibles
 <br>When se revisan
 <br>Then se diferencian por exhibición
 </td>
 <td style="text-align: center;">EP03</td>
 </tr>
 <!-- US18 -->
 <tr>
 <td style="text-align: center;">US18</td>
 <td style="text-align: center;">Identificar obras mas rentables</td>
 <td style="text-align: center;"> Como gestor, quiero identificar qué obras generan mayor interacción pagada, para optimizar futuras exhibiciones.</td>
 <td style="text-align: center;">
 <br><br>Scenario 1: Ranking
 <br>Given datos de ingresos
 <br>When se analizan
 <br>Then el sistema genera ranking
 <br><br>Scenario 2: Actualización
 <br>Given nuevos datos
 <br>When se registran
 <br>Then se actualiza ranking
 </td>
 <td style="text-align: center;">EP03</td>
 </tr>
 <!-- US19 -->
 <tr>
 <td style="text-align: center;">US19</td>
 <td style="text-align: center;">Recursos</td>
 <td style="text-align: center;"> Como gestor, quiero analizar el flujo de visitantes, para redistribuir personal y recursos de manera eficiente.</td>
 <td style="text-align: center;">
 <br><br>Scenario 1: Análisis
 <br>Given datos de flujo
 <br>When se analizan
 <br>Then el sistema genera recomendaciones
 <br><br>Scenario 2: Consulta
 <br>Given recomendaciones
 <br>When se revisan
 <br>Then se muestran
 </td>
 <td style="text-align: center;">EP03</td>
 </tr>
 <!-- US20 -->
 <tr>
 <td style="text-align: center;">US20</td>
 <td style="text-align: center;">Reportes</td>
 <td style="text-align: center;"> Como gestor, quiero generar reportes de desempeño de las exhibiciones, para evaluar resultados y tomar decisiones estratégicas.</td>
 <td style="text-align: center;">
 <br><br>Scenario 1: Generación
 <br>Given datos disponibles
 <br>When se solicita reporte
 <br>Then el sistema genera documento
 <br><br>Scenario 2: Contenido
 <br>Given un reporte
 <br>When se revisa
 <br>Then contiene datos correctos
 </td>
 <td style="text-align: center;">EP03</td>
 </tr>
 <!-- US21 -->
 <tr>
 <td style="text-align: center;">US21</td>
 <td style="text-align: center;">Monitoreo de interacción</td>
 <td style="text-align: center;"> Como gestor, quiero monitorear la interacción de los visitantes con el contenido digital, para mejorar la experiencia.</td>
 <td style="text-align: center;">
 <br><br>Scenario 1: Registro de interacción
 <br>Given un visitante accede al contenido
 <br>When interactúa con la obra
 <br>Then el sistema registra la interacción
 <br><br>Scenario 2: Consulta de datos
 <br>Given datos registrados
 <br>When el gestor consulta
 <br>Then el sistema muestra la información
 </td>
 <td style="text-align: center;">EP03</td>
 </tr>
 <!-- US22 -->
 <tr>
 <td style="text-align: center;">US22</td>
 <td style="text-align: center;">Comparación rendimiento de exhibiciones</td>
 <td style="text-align: center;"> Como gestor, quiero comparar el rendimiento entre exhibiciones, para identificar oportunidades de mejora. </td>
 <td style="text-align: center;">
 <br><br>Scenario 1: Comparación
 <br>Given dos o más exhibiciones
 <br>When se analizan datos
 <br>Then el sistema muestra diferencias
 <br><br>Scenario 2: Visualización
 <br>Given resultados comparados
 <br>When se consultan
 <br>Then se muestran gráficos claros
 </td>
 <td style="text-align: center;">EP03</td>
 </tr>
 <!-- US23 -->
 <tr>
 <td style="text-align: center;">US23</td>
 <td style="text-align: center;"> Visualizar tendencias de visitantes. </td>
 <td style="text-align: center;"> Como administrador, quiero visualizar tendencias de visitas, para anticipar picos de demanda. </td>
 <td style="text-align: center;">
 <br><br>Scenario 1: Identificación de patrones
 <br>Given datos históricos
 <br>When se analizan
 <br>Then el sistema muestra tendencias
 <br><br>Scenario 2: Actualización
 <br>Given nuevos datos
 <br>When se registran
 <br>Then las tendencias se actualizan
 </td>
 <td style="text-align: center;">EP03</td>
 </tr>
 <!-- US24 -->
 <tr>
 <td style="text-align: center;">US24</td>
 <td style="text-align: center;"> Optimizar contenido premium </td>
 <td style="text-align: center;"> Como gestor, quiero ajustar el contenido premium según el interés del visitante, para aumentar su valor percibido. </td>
 <td style="text-align: center;">
 <br><br>Scenario 1: Edición
 <br>Given contenido premium
 <br>When el gestor lo modifica
 <br>Then el sistema actualiza el contenido
 <br><br>Scenario 2: Acceso
 <br>Given contenido actualizado
 <br>When el usuario accede
 <br>Then se muestra correctamente
 </td>
 <td style="text-align: center;">EP03</td>
 </tr>
 <!-- US25 -->
 <tr>
 <td style="text-align: center;">US25</td>
 <td style="text-align: center;"> Monitorear aforo en tiempo real </td>
 <td style="text-align: center;"> Como gestor de museo público, quiero monitorear el número de visitantes en tiempo real, para controlar el aforo permitido. </td>
 <td style="text-align: center;">
 <br><br>Scenario 1: Conteo en tiempo real
 <br>Given visitantes ingresan o salen
 <br>When el sistema registra movimientos
 <br>Then calcula el aforo actual
 <br><br>Scenario 2: Consulta
 <br>Given datos de aforo
 <br>When se consultan
 <br>Then se muestran actualizados
 </td>
 <td style="text-align: center;">EP04</td>
 </tr>
 <!-- US26 -->
 <tr>
 <td style="text-align: center;">US26</td>
 <td style="text-align: center;">Alertas de aforo</td>
 <td style="text-align: center;"> Como gestor, quiero recibir alertas cuando se supere el aforo permitido, para tomar acciones inmediatas. </td>
 <td style="text-align: center;">
 <br><br>Scenario 1: Alerta automática
 <br>Given un límite definido
 <br>When se supera el aforo
 <br>Then el sistema envía una alerta
 <br><br>Scenario 2: Configuración
 <br>Given límites configurados
 <br>When se actualizan
 <br>Then el sistema los aplica
 </td>
 <td style="text-align: center;">EP04</td>
 </tr>
 <!-- US27 -->
 <tr>
 <td style="text-align: center;">US27</td>
 <td style="text-align: center;">Flujo entre salas</td>
 <td style="text-align: center;"> Como gestor, quiero controlar el flujo de visitantes entre salas, para evitar congestión. </td>
 <td style="text-align: center;">
 <br><br>Scenario 1: Registro de movimiento
 <br>Given un visitante cambia de sala
 <br>When el sistema registra el evento
 <br>Then se actualiza el flujo
 <br><br>Scenario 2: Consulta
 <br>Given datos de flujo
 <br>When se consultan
 <br>Then se muestran por sala
 </td>
 <td style="text-align: center;">EP04</td>
 </tr>
 <!-- US28 -->
 <tr>
 <td style="text-align: center;">US28</td>
 <td style="text-align: center;">Historial de aforo</td>
 <td style="text-align: center;"> Como gestor, quiero acceder al historial de aforo, para evaluar el cumplimiento de normativas.</td>
 <td style="text-align: center;">
 <br><br>Scenario 1: Registro histórico
 <br>Given datos de aforo
 <br>When se almacenan
 <br>Then quedan registrados
 <br><br>Scenario 2: Consulta
 <br>Given historial disponible
 <br>When se consulta
 <br>Then el sistema muestra datos
 </td>
 <td style="text-align: center;">EP04</td>
 </tr>
 <!-- US29 -->
 <tr>
 <td style="text-align: center;">US29</td>
 <td style="text-align: center;">Zonas congestionadas</td>
 <td style="text-align: center;"> Como administrador, quiero identificar zonas con alta concentración de visitantes, para mejorar la distribución. </td>
 <td style="text-align: center;">
 <br><br>Scenario 1: Identificación
 <br>Given datos de ubicación
 <br>When se analizan
 <br>Then el sistema detecta congestión
 <br><br>Scenario 2: Visualización
 <br>Given zonas identificadas
 <br>When se consultan
 <br>Then se muestran claramente
 </td>
 <td style="text-align: center;">EP04</td>
 </tr>
 <!-- US30 -->
 <tr>
 <td style="text-align: center;">US30</td>
 <td style="text-align: center;">Cumplimiento normativo</td>
 <td style="text-align: center;"> Como administrador, quiero asegurar el cumplimiento de normativas de seguridad, para evitar sanciones y garantizar la seguridad..</td>
 <td style="text-align: center;">
 <br><br>Scenario 1: Validación de reglas
 <br>Given normas definidas
 <br>When se monitorea el sistema
 <br>Then se valida cumplimiento
 <br><br>Scenario 2: Registro
 <br>Given eventos del sistema
 <br>When ocurren
 <br>Then se registran
 </td>
 <td style="text-align: center;">EP04</td>
 </tr>
 <!-- US31 -->
 <tr>
 <td style="text-align: center;">US31</td>
 <td style="text-align: center;">Acceso remoto al monitoreo</td>
 <td style="text-align: center;"> Como administrador, quiero acceder al sistema de monitoreo desde cualquier dispositivo, para supervisar el museo de forma remota.</td>
 <td style="text-align: center;">
 <br><br>Scenario 1: Acceso válido
 <br>Given credenciales válidas
 <br>When el administrador inicia sesión
 <br>Then el sistema permite acceso remoto
 <br><br>Scenario 2: Acceso desde dispositivo móvil
 <br>Given un dispositivo móvil
 <br>When el administrador accede
 <br>Then el sistema se adapta correctamente
 </td>
 <td style="text-align: center;">EP04</td>
 </tr>
 <!-- US32 -->
 <tr>
 <td style="text-align: center;">US32</td>
 <td style="text-align: center;">Seguridad del visitante</td>
 <td style="text-align: center;"> Como administrador, quiero garantizar una distribución segura de visitantes, para mejorar la experiencia y prevenir riesgos.</td>
 <td style="text-align: center;">
 <br><br>Scenario 1: Control de flujo activo
 <br>Given visitantes en el museo
 <br>When el sistema analiza el flujo
 <br>Then se reduce la congestión
 <br><br>Scenario 2: Prevención de riesgo
 <br>Given alta concentración
 <br>When se detecta saturación
 <br>Then el sistema ajusta el flujo
 </td>
 <td style="text-align: center;">EP04</td>
 </tr>
 <!-- US33 -->
 <tr>
 <td style="text-align: center;">US33</td>
 <td style="text-align: center;">Acceso QR visitante</td>
 <td style="text-align: center;">Como visitante, quiero escanear códigos QR para acceder al contenido de las obras.</td>
 <td style="text-align: center;">
 <br><br>Scenario 1: Acceso exitoso
 <br>Given un QR válido
 <br>When el visitante lo escanea
 <br>Then el sistema muestra el contenido
 <br><br>Scenario 2: Error de acceso
 <br>Given un QR inválido
 <br>When el visitante lo escanea
 <br>Then el sistema muestra un mensaje de error
 </td>
 <td style="text-align: center;">EP05</td>
 </tr>
 <!-- US34 -->
 <tr>
 <td style="text-align: center;">US34</td>
 <td style="text-align: center;">Acceso sin descarga</td>
 <td style="text-align: center;"> Como visitante, quiero acceder al contenido sin descargar aplicaciones para una experiencia rápida. </td>
 <td style="text-align: center;">
 <br><br>Scenario 1: Acceso web
 <br>Given un enlace de contenido
 <br>When el usuario accede
 <br>Then el sistema muestra contenido sin instalación
 <br><br>Scenario 2: Compatibilidad de dispositivos
 <br>Given un dispositivo móvil o desktop
 <br>When el usuario abre el enlace
 <br>Then el sistema adapta la interfaz automáticamente
 </td>
 <td style="text-align: center;">EP05</td>
 </tr>
 <!-- US35 -->
 <tr>
 <td style="text-align: center;">US35</td>
 <td style="text-align: center;">Visualización multimedia</td>
 <td style="text-align: center;">Como visitante, quiero visualizar contenido multimedia para enriqueder la experiencia.</td>
 <td style="text-align: center;">
 <br><br>Scenario 1: Reproducción
 <br>Given contenido multimedia
 <br>When el usuario lo abre
 <br>Then el sistema lo reproduce correctamente
 <br><br>Scenario 2: Control de reproducción
 <br>Given un video o audio en reproducción
 <br>When el usuario pausa o ajusta volumen
 <br>Then el sistema responde inmediatamente a los controles
 </td>
 <td style="text-align: center;">EP05</td>
 </tr>
 <td style="text-align: center;">EP05</td>
 </tr>
 <!-- US36 -->
 <tr>
 <td style="text-align: center;">US36</td>
 <td style="text-align: center;">Navegación entre obras</td>
 <td style="text-align: center;"> Como visitante, quiero navegar entre contenidos para mejorar mi recorrido. </td>
 <td style="text-align: center;">
 <br><br>Scenario 1: Cambio de obra
 <br>Given varias obras disponibles
 <br>When el usuario selecciona otra
 <br>Then el sistema carga el nuevo contenido
 <br><br>Scenario 2: Historial de navegación
 <br>Given múltiples obras visitadas
 <br>When el usuario retrocede
 <br>Then el sistema muestra la obra anterior visitada
 </td>
 <td style="text-align: center;">EP05</td>
 </tr>
 <!-- US37 -->
 <tr>
 <td style="text-align: center;">US37</td>
 <td style="text-align: center;">Recomendaciones de recorrido</td>
 <td style="text-align: center;"> Como visitante, quiero recibir sugerencias de recorrido para optimizar mi visita. </td>
 <td style="text-align: center;">
 <br><br>Scenario 1: Generación de sugerencias
 <br>Given datos de visitas
 <br>When el sistema analiza patrones
 <br>Then genera recomendaciones de recorrido
 <br><br>Scenario 2: Personalización de recomendaciones
 <br>Given el historial del usuario
 <br>When el sistema identifica preferencias
 <br>Then ajusta las recomendaciones según intereses
 </td>
 <td style="text-align: center;">EP05</td>
 </tr>
 <!-- US38 -->
 <tr>
 <td style="text-align: center;">US38</td>
 <td style="text-align: center;">Contenido exclusivo</td>
 <td style="text-align: center;"> Como visitante, quiero acceder a contenido exclusivo dentro del museo para enriquecer la experiencia. </td>
 <td style="text-align: center;">
 <br><br>Scenario 1: Acceso permitido
 <br>Given el usuario está dentro del museo
 <br>When solicita contenido exclusivo
 <br>Then el sistema lo habilita
 <br><br>Scenario 2: Acceso restringido
 <br>Given el usuario está fuera del museo
 <br>When solicita contenido exclusivo
 <br>Then el sistema lo bloquea
 </td>
 <td style="text-align: center;">EP05</td>
 </tr>
 <!-- US39 -->
 <tr>
 <td style="text-align: center;">US39</td>
 <td style="text-align: center;">Sistema de recompensas</td>
 <td style="text-align: center;"> Como visitante, quiero obtener insignias digitales al interactuar con obras para motivar mi recorrido.</td>
 <td style="text-align: center;">
 <br><br>Scenario 1: Otorgamiento de recompensa
 <br>Given interacción completada
 <br>When el usuario cumple condiciones
 <br>Then el sistema otorga una insignia
 <br><br>Scenario 2: Visualización de insignias
 <br>Given insignias otorgadas al usuario
 <br>When el usuario accede a su perfil
 <br>Then el sistema muestra todas las insignias obtenidas
 </td>
 <td style="text-align: center;">EP05</td>
 </tr>
 <!-- US40 -->
 <tr>
 <td style="text-align: center;">US40</td>
 <td style="text-align: center;">Carga rápida de contenido</td>
 <td style="text-align: center;"> Como visitante, quiero que el contenido se cargue rápido para no perder tiempo. </td>
 <td style="text-align: center;">
 <br><br>Scenario 1: Rendimiento
 <br>Given una solicitud de contenido
 <br>When el sistema responde
 <br>Then la carga es menor a 3 segundos
 <br><br>Scenario 2: Optimización de recursos
 <br>Given múltiples usuarios accediendo simultáneamente
 <br>When el sistema distribuye la carga
 <br>Then mantiene tiempos de respuesta óptimos
 </td>
 <td style="text-align: center;">EP05</td>
 </tr>
 <!-- US41 -->
 <tr>
 <td style="text-align: center;">US41</td>
 <td style="text-align: center;">Dashboard de afluencia</td>
 <td style="text-align: center;"> Como administrador, quiero visualizar la afluencia por sala para tomar decisiones rápidas. </td>
 <td style="text-align: center;">
 <br><br>Scenario 1: Visualización en tiempo real
 <br>Given sensores activos en el museo
 <br>When el sistema recibe datos
 <br>Then el dashboard muestra la afluencia por sala
 <br><br>Scenario 2: Actualización de datos
 <br>Given cambios en la afluencia
 <br>When ocurren movimientos de visitantes
 <br>Then la información se actualiza automáticamente
 </td>
 <td style="text-align: center;">EP06</td>
 </tr>
 <!-- US42 -->
 <tr>
 <td style="text-align: center;">US42</td>
 <td style="text-align: center;">Permanencia en obras</td>
 <td style="text-align: center;"> Como administrador, quiero conocer el tiempo de permanencia por obra para medir el engagement.</td>
 <td style="text-align: center;">
 <br><br>Scenario 1: Registro de permanencia
 <br>Given interacción del usuario con una obra
 <br>When el usuario permanece en la obra
 <br>Then el sistema registra el tiempo
 <br><br>Scenario 2: Cálculo promedio
 <br>Given múltiples interacciones
 <br>When se analizan los datos
 <br>Then se calcula el tiempo promedio
 </td>
 <td style="text-align: center;">EP06</td>
 </tr>
 <!-- US43 -->
 <tr>
 <td style="text-align: center;">US43</td>
 <td style="text-align: center;">Ranking de obras</td>
 <td style="text-align: center;"> Como curador, quiero identificar las obras más visitadas para optimizar las exhibiciones. </td>
 <td style="text-align: center;">
 <br><br>Scenario 1: Generación de ranking
 <br>Given datos de visitas
 <br>When el sistema los procesa
 <br>Then genera un ranking ordenado
 <br><br>Scenario 2: Actualización del ranking
 <br>Given nuevas visitas registradas
 <br>When el sistema actualiza los datos
 <br>Then el ranking se recalcula automáticamente
 </td>
 <td style="text-align: center;">EP06</td>
 </tr>
 <!-- US44 -->
 <tr>
 <td style="text-align: center;">US44</td>
 <td style="text-align: center;">Detección de baja interacción</td>
 <td style="text-align: center;"> Como curador, quiero detectar obras con baja interacción para replantear su presentación.</td>
 <td style="text-align: center;">
 <br><br>Scenario 1: Identificación automática
 <br>Given un umbral de interacción definido
 <br>When una obra no lo cumple
 <br>Then el sistema la marca como baja interacción
 <br><br>Scenario 2: Notificación al curador
 <br>Given una obra detectada con baja interacción
 <br>When el sistema valida la condición
 <br>Then envía una alerta al curador responsable
 </td>
 <td style="text-align: center;">EP06</td>
 </tr>
 <!-- US45 -->
 <tr>
 <td style="text-align: center;">US45</td>
 <td style="text-align: center;">Exportación de reportes</td>
 <td style="text-align: center;"> Como administrador, quiero exportar reportes para presentarlos a patrocinadores. </td>
 <td style="text-align: center;">
 <br><br>Scenario 1: Exportación exitosa
 <br>Given datos disponibles
 <br>When el usuario solicita exportación
 <br>Then el sistema genera archivo PDF o Excel
 <br><br>Scenario 2: Selección de formato
 <br>Given múltiples formatos disponibles
 <br>When el usuario elige un formato específico
 <br>Then el sistema exporta el reporte en el formato seleccionado
 </td>
 <td style="text-align: center;">EP06</td>
 </tr>
 <!-- US46 -->
 <tr>
 <td style="text-align: center;">US46</td>
 <td style="text-align: center;">Alertas de saturación</td>
 <td style="text-align: center;"> Como administrador, quiero recibir alertas cuando una sala esté saturada para actuar rápidamente. </td>
 <td style="text-align: center;">
 <br><br>Scenario 1: Alerta automática
 <br>Given una sala supera el límite de capacidad
 <br>When el sistema detecta la saturación
 <br>Then envía una notificación inmediata
 <br><br>Scenario 2: Resolución de saturación
 <br>Given una alerta de saturación activa
 <br>When el personal reduce el flujo de visitantes
 <br>Then la alerta se desactiva automáticamente
 </td>
 <td style="text-align: center;">EP06</td>
 </tr>
 <!-- US47 -->
 <tr>
 <td style="text-align: center;">US47</td>
 <td style="text-align: center;">Análisis histórico</td>
 <td style="text-align: center;"> Como administrador quiero comparar los datos históricos para mejorar la planificación. </td>
 <td style="text-align: center;">
 <br><br>Scenario 1: Comparación de periodos
 <br>Given datos históricos almacenados
 <br>When el usuario selecciona fechas
 <br>Then el sistema muestra métricas comparativas
 <br><br>Scenario 2: Filtrado de datos históricos
 <br>Given múltiples variables disponibles
 <br>When el usuario aplica filtros
 <br>Then el sistema muestra resultados segmentados
 </td>
 <td style="text-align: center;">EP06</td>
 </tr>
 <!-- US48 -->
 <tr>
 <td style="text-align: center;">US48</td>
 <td style="text-align: center;">Distribución de visitantes</td>
 <td style="text-align: center;"> Como administrador, quiero visualizar la distribución de visitantes en las diferentes salas del museo, para entender el flujo y tomar decisiones informadas. </td>
 <td style="text-align: center;">
 <br><br>Scenario 1: Visualización de distribución
 <br>Given datos de visitantes
 <br>When el sistema procesa la información
 <br>Then muestra la distribución por sala
 <br><br>Scenario 2: Actualización en tiempo real
 <br>Given sensores activos en salas
 <br>When entran nuevos visitantes
 <br>Then el sistema actualiza la distribución automáticamente
 </td>
 <td style="text-align: center;">EP06</td>
 </tr>
 <!-- US49 -->
 <tr>
 <td style="text-align: center;">US49</td>
 <td style="text-align: center;">Acceso sin registro</td>
 <td style="text-align: center;"> Como museo privado, quiero que el acceso al contenido sin registro obligatorio para que todos puedan entrar rapidamente. </td>
 <td style="text-align: center;">
 <br><br>Scenario 1: Acceso libre
 <br>Given un usuario nuevo
 <br>When accede al sistema
 <br>Then puede visualizar contenido sin autenticación
 <br><br>Scenario 2: Restricción de funciones avanzadas
 <br>Given un usuario sin registro
 <br>When intenta acceder a funciones administrativas
 <br>Then el sistema restringe el acceso y solicita autenticación
 </td>
 <td style="text-align: center;">EP01</td>
 </tr>
 <!-- US50 -->
 <tr>
 <td style="text-align: center;">US50</td>
 <td style="text-align: center;">Accesibilidad del contenido</td>
 <td style="text-align: center;"> Como visitante, quiero que el contenido sea accesible para que sea más atractivo al público en general. </td>
 <td style="text-align: center;">
 <br><br>Scenario 1: Legibilidad
 <br>Given contenido disponible
 <br>When el usuario accede
 <br>Then el texto es legible y claro
 <br><br>Scenario 2: Compatibilidad
 <br>Given diferentes dispositivos
 <br>When se accede al sistema
 <br>Then el contenido es adaptable
 </td>
 <td style="text-align: center;">EP07</td>
 </tr>
 <!-- US51 -->
 <tr>
 <td style="text-align: center;">US51</td>
 <td style="text-align: center;">Alertas de comportamiento</td>
 <td style="text-align: center;"> Como administrador, quiero recibir alertas cuando una obra tenga alta o baja interacción para acciones más precisas. </td>
 <td style="text-align: center;">
 <br><br>Scenario 1: Activación de alerta
 <br>Given umbrales definidos
 <br>When se detecta comportamiento anómalo
 <br>Then el sistema genera una alerta
 <br><br>Scenario 2: Desactivación de alertas
 <br>Given una alerta activa
 <br>When el administrador ajusta o desactiva los umbrales
 <br>Then el sistema deja de generar alertas para ese caso
 </td>
 <td style="text-align: center;">EP02</td>
 </tr>
 <!-- US52 -->
 <tr>
 <td style="text-align: center;">US52</td>
 <td style="text-align: center;">Tendencias históricas</td>
 <td style="text-align: center;"> Como administrador, quiero ver la evolución del interés en el tiempo para reportes más precisos. </td>
 <td style="text-align: center;">
 <br><br>Scenario 1: Análisis histórico
 <br>Given datos almacenados en el tiempo
 <br>When el usuario selecciona un periodo
 <br>Then el sistema muestra tendencias de comportamiento
 <br><br>Scenario 2: Comparación de periodos
 <br>Given dos rangos de fechas seleccionados
 <br>When el usuario solicita comparación
 <br>Then el sistema muestra diferencias de tendencia entre ambos periodos
 </td>
 <td style="text-align: center;">EP02</td>
 </tr>
 </table>

### 3.2. Impact Mapping

![Impact-Mapping](../assets/img/3_2-Impact/Impact%20Mapping.jpg)

Nota: Este gráfico de Impact Mapping define como objetivo principal convertir el flujo de visitantes en inteligencia estratégica y experiencias interactivas, con el fin de optimizar la gestión cultural. Identifica tres actores clave: los gestores de museos privados, interesados en obtener datos que respalden inversiones y atraigan patrocinadores; los administradores públicos, enfocados en la seguridad y la justificación del presupuesto; y el personal de TI y seguridad, encargado de gestionar una plataforma centralizada que garantice la protección y el uso eficiente de la información.

### 3.3. Product Backlog

| **# Orden** | **User Story Id** | **Título** | **Descripción** | **Story Points (1/2/3/5/8)** |
|-------------|-------------------|------------|-----------------|------------------------------|
| 1 | US01 | Acceso a contenido mediante QR | Como visitante quiero escanear un código QR para acceder al contenido digital de una obra para obtener información inmediata durante el recorrido. | 3 |
| 2 | US02 | Acceso sin instalación | Como visitante quiero acceder al contenido desde mi navegador sin instalar aplicaciones para tener una experiencia rápida y sin fricción. | 2 |
| 3 | US03 | Visualización multimedia | Como visitante quiero visualizar contenido multimedia de las obras para comprender mejor su contexto y enriquecer mi experiencia. | 3 |
| 4 | US04 | Contenido exclusivo | Como visitante quiero acceder a contenido exclusivo dentro del museo para vivir una experiencia diferenciada. | 3 |
| 5 | US05 | Selección de idioma | Como visitante quiero seleccionar el idioma del contenido para entender la información en mi idioma preferido. | 2 |
| 6 | US06 | Navegación entre obras | Como visitante quiero navegar entre contenidos de distintas obras para explorar el museo de forma continua. | 3 |
| 7 | US07 | Acceso sin registro | Como visitante quiero acceder al contenido sin necesidad de registrarme para ingresar rápidamente al sistema. | 2 |
| 8 | US08 | Carga rápida | Como visitante quiero que el contenido cargue en menos de 3 segundos para no perder tiempo durante mi recorrido. | 3 |
| 9 | US09 | Historial de obras | Como visitante quiero ver las obras que ya visité para revisarlas nuevamente durante mi recorrido. | 3 |
| 10 | US10 | Obras favoritas | Como visitante quiero marcar obras como favoritas para acceder fácilmente a ellas después. | 2 |
| 11 | US11 | Recomendaciones de obras | Como visitante quiero recibir recomendaciones basadas en mis interacciones para descubrir nuevas obras relevantes. | 5 |
| 12 | US12 | Rutas sugeridas | Como visitante quiero recibir sugerencias de recorrido para optimizar mi visita dentro del museo. | 5 |
| 13 | US13 | Accesibilidad del contenido | Como visitante quiero que el contenido sea accesible (audio, texto claro) para mejorar mi experiencia. | 3 |
| 14 | US14 | Registro de interacciones | Como gestor quiero registrar las interacciones de los visitantes para analizar su comportamiento. | 5 |
| 15 | US15 | Dashboard en tiempo real | Como gestor quiero visualizar métricas en tiempo real para monitorear el comportamiento de los visitantes. | 5 |
| 16 | US16 | Ranking de obras | Como gestor quiero visualizar las obras más visitadas para identificar cuáles generan mayor interés. | 3 |
| 17 | US17 | Tiempo de interacción | Como gestor quiero medir el tiempo de permanencia en cada obra para evaluar el nivel de engagement. | 5 |
| 18 | US18 | Baja interacción | Como gestor quiero detectar obras con bajo interés para tomar decisiones de mejora. | 3 |
| 19 | US19 | Exportación de reportes | Como gestor quiero exportar reportes para analizarlos y compartirlos con stakeholders. | 3 |
| 20 | US20 | Análisis por horarios | Como gestor quiero analizar visitas por franjas horarias para identificar horas pico. | 5 |
| 21 | US21 | Tendencias históricas | Como gestor quiero analizar tendencias en el tiempo para mejorar la planificación. | 5 |
| 22 | US22 | Control de aforo | Como gestor quiero monitorear la cantidad de visitantes en tiempo real para garantizar la seguridad. | 5 |
| 23 | US23 | Alertas de aforo | Como gestor quiero recibir alertas cuando se supere el límite de visitantes para actuar rápidamente. | 3 |
| 24 | US24 | Flujo por salas | Como gestor quiero visualizar el flujo de visitantes por sala para evitar congestión. | 5 |
| 25 | US25 | Zonas congestionadas | Como gestor quiero identificar zonas con alta concentración para mejorar la distribución de visitantes. | 5 |
| 26 | US26 | Recomendaciones operativas | Como gestor quiero recibir recomendaciones para optimizar recursos y flujo del museo. | 5 |
| 27 | US27 | Reportes de desempeño | Como gestor quiero generar reportes integrales para evaluar resultados del museo. | 5 |
| 28 | US28 | Comparación de exhibiciones | Como gestor quiero comparar exhibiciones para identificar oportunidades de mejora. | 5 |
| 29 | US29 | Métricas de ingresos | Como gestor quiero visualizar ingresos por exhibición para optimizar la rentabilidad. | 5 |
| 30 | US30 | Control de acceso | Como administrador quiero gestionar accesos y roles para proteger la información del sistema. | 3 |
| 31 | US31 | Acceso remoto | Como gestor quiero acceder al sistema desde cualquier dispositivo para monitorear el museo en tiempo real. | 3 |
| 32 | US32 | Redirección de flujo | Como gestor quiero redirigir visitantes en caso de congestión para mejorar la circulación. | 5 |
| 33 | US33 | Acceso alternativo QR | Como visitante quiero acceder al contenido mediante QR de forma confiable para evitar errores. | 2 |
| 34 | US34 | Compatibilidad dispositivos | Como visitante quiero que el sistema funcione en cualquier dispositivo para acceder sin problemas. | 2 |
| 35 | US35 | Multimedia adaptable | Como visitante quiero que el contenido multimedia se adapte a mi pantalla para mejorar la visualización. | 3 |
| 36 | US36 | Navegación fluida | Como visitante quiero cambiar entre obras sin recargar la página para una mejor experiencia. | 3 |
| 37 | US37 | Recomendaciones inteligentes | Como visitante quiero recomendaciones según afluencia para evitar zonas congestionadas. | 5 |
| 38 | US38 | Validación de contenido exclusivo | Como visitante quiero que el contenido exclusivo solo funcione dentro del museo para mantener su valor. | 3 |
| 39 | US39 | Insignias digitales | Como visitante quiero obtener logros por interactuar con obras para motivar mi recorrido. | 3 |
| 40 | US40 | Rendimiento del sistema | Como visitante quiero que el sistema responda rápido para no afectar mi experiencia. | 3 |
| 41 | US41 | Dashboard de afluencia | Como administrador quiero ver la afluencia por sala para tomar decisiones rápidas. | 5 |
| 42 | US42 | Permanencia en obras | Como administrador quiero conocer el tiempo de permanencia para medir engagement. | 5 |
| 43 | US43 | Ranking curatorial | Como curador quiero identificar obras populares para optimizar exhibiciones. | 3 |
| 44 | US44 | Detección de baja interacción | Como curador quiero detectar obras con bajo interés para mejorarlas. | 3 |
| 45 | US45 | Exportación avanzada | Como administrador quiero exportar reportes en varios formatos para presentaciones. | 3 |
| 46 | US46 | Alertas de saturación | Como administrador quiero recibir alertas de saturación para actuar rápidamente. | 3 |
| 47 | US47 | Análisis histórico | Como administrador quiero comparar datos históricos para mejorar decisiones. | 5 |
| 48 | US48 | Distribución de visitantes | Como administrador quiero visualizar la distribución para entender el flujo del museo. | 5 |
| 49 | US49 | Acceso sin fricción | Como museo quiero permitir acceso rápido sin login para mejorar la adopción. | 2 |
| 50 | US50 | Accesibilidad | Como visitante quiero contenido accesible para mejorar la experiencia general. | 3 |
| 51 | US51 | Alertas de comportamiento | Como administrador quiero recibir alertas de interacción para tomar decisiones. | 3 |
| 52 | US52 | Tendencias de comportamiento | Como administrador quiero analizar tendencias para mejorar la planificación. | 5 |