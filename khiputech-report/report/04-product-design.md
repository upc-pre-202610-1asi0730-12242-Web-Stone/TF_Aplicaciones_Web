## Capítulo IV: Product Design

### 4.1. Style Guidelines

#### 4.1.1. General Style Guidelines

- **Branding:**

  - _Concepto:_ El nombre "KhipuTech" une el Khipu (sistema de registro incaico basado en nudos) con la tecnología moderna. Visualmente, buscamos transmitir conexión, datos y herencia cultural.
  - _Logotipo:_ Se utilizarán líneas minimalistas que emulen las cuerdas de un khipu, formando una red o nodo que simboliza los puntos de datos (sensores).

- **Typography**

  - _Títulos (H1 – H2):_ DM Sans Bold. Tamaño: 32px / 24px. Espaciado entre letras: -0.5px.
  - _Cuerpo de texto:_ DM Sans Regular. Tamaño: 16px. Altura de línea: 1.5.
  - _Datos / Labels:_ DM Sans SemiBold. Tamaño: 12px o 14px.
  - _Tipografía Adicional:_ DM Mono Regular/Medium. Tamaño: 10-12px. Uso: valores de aforo, timestamps, IDs de sala, métricas de sensores. Mantiene legibilidad en tablas densas.

- **Iconography**

  - Los iconos del sistema usarán Lucide Icons con stroke de 2px — coherente con la geometría limpia del logo.
  - Los iconos que representen sensores, zonas o puntos de conteo seguirán la estética de nodos conectados, alineada al concepto del Khipu: un nodo central con ramificaciones, sin relleno sólido, solo trazo.

- **Logo communication tone**

  - _Sustento:_
    |Decision de Diseño |Señal de Tono|
    | :---: | :--- |
    | Paleta dark navy + cyan eléctrico | Entorno tecnológico, dashboards, datos. Evita lo corporativo genérico |
    | Geometría de nodos con crosshair central | Precisión, monitoreo, tracking. No decorativo sino funcional |
    | Peso 600 / 300 en el logotipo | Autoridad sin rigidez. La palabra fuerte ("Khipu") ancla, la palabra ligera ("Tech") abre |
    | Tagline en caps espaciado | Claridad directa, sin adornos. Habla de lo que hace, no de lo que aspira |
    | Referencia al khipu como sistema de datos | Herencia intelectual + innovación. No es nostalgia, es reencuadre |

    El tono no es entusiasta ni cercano porque KhipuTech vende a tomadores de decisión (museos, espacios públicos, gestores) que necesitan confiar en la exactitud del dato antes que en la calidez de la marca. La emoción viene después, cuando el dashboard funciona.

- **Logo Use**

  - _Área de Reserva:_ Se debe mantener un espacio mínimo de seguridad equivalente al 20% del ancho del logo en todos sus lados para evitar interferencias visuales.
  - _Uso en Fondos:_ Sobre fondos oscuros (Blue #1A2B48), se usará la versión en "Inca Gold" o blanco. Sobre fondos claros, se usará la versión azul marino.
  - _Prohibiciones:_ No se permite deformar la relación de aspecto, cambiar los colores fuera de la paleta oficial o aplicar sombras paralelas internas.

- **Color Palette**

  | Color             |   HEX   |      RGB      |      CMYK      |
  | :---------------- | :-----: | :-----------: | :------------: |
  | **Dark Navy**     | #0B1A3E |  11, 26, 62   | 91, 80, 42, 45 |
  | **Electric Blue** | #00C8FF |  0, 200, 255  |  65, 5, 0, 0   |
  | **Ice Blue**      | #E8F0FF | 232, 240, 255 |   8, 4, 0, 0   |
  | **Sky Blue**      | #62B1FF | 98, 177, 255  |  54, 24, 0, 0  |
  | **Inca Gold**     | #C8A84B | 200, 168, 75  | 22, 31, 62, 21 |
  | **Steel Blue**    | #4A7ABA | 74, 122, 186  | 74, 49, 11, 1  |

#### 4.1.2. Web Style Guidelines

Define los estándares visuales y de interacción para las interfaces web de KhipuTech, asegurando una experiencia óptima tanto en el Dashboard administrativo como en la Web App del visitante.

A continuación todos los puntos exigidos:

- **Grid & Spacing**
  Grid de 12 columnas para desktop (máx. 1440px) y 4 columnas para mobile. Unidad base 8px. Todos los márgenes y paddings son múltiplos de 8.

- **UI Components**
  Botones (primario/secundario/ghost/danger en 3 tamaños + disabled), Cards KPI con hover animado, Alert cards, Inputs con todos los estados (default/hover/focus/error/disabled), Selects, Toggles, Checkboxes, Badges de estado, Navegación con ítem activo, Barras de progreso por aforo, Tabla de datos, y Tooltip, Mapa visual de distribución de salas (room-card con estados crítico/moderado/seguro).

- **Responsive**
  Tres breakpoints documentados (mobile 320–480px / tablet 481–1024px / desktop 1025px+) con mockups visuales de cada dispositivo y reglas de adaptación.

- **Interacción & Feedback**
  Skeleton screen animado con shimmer, Toasts (success/error/info), Indicador EN VIVO con pulso, tabla de especificaciones de transición por componente, y tabla de contraste WCAG AA con los ratios reales de la paleta (Navy+Cyan = 8.5:1, ideal para salas con luz tenue).

#### 4.2. Information Architecture
Esta sección describe la estructura de la información, estilos y sistemas que se utilizarán en la plataforma web de KhipuTech. Se consideran los sistemas de organización, etiquetado, búsqueda, navegación y SEO, con el fin de garantizar una experiencia clara y enfocada en la visualización de datos.

#### 4.2.1. Organization Systems

Tópico | Definición  
---|---  
Home | La página de inicio muestra una vista general del sistema, destacando métricas clave y accesos rápidos al dashboard.  
Dashboard | La página principal de análisis donde se visualizan datos en tiempo real del flujo de visitantes.  
Sensores | La página donde se visualizan y gestionan los dispositivos IoT instalados en el recinto.  
Zonas | La página que representa las áreas monitoreadas mediante mapas o nodos conectados.  
Reportes | La página que permite visualizar análisis históricos y exportar datos.  
Contact | La página que permite a los usuarios comunicarse con soporte técnico.  
Log In | La página donde el usuario puede iniciar sesión o registrarse para acceder al sistema.  


### Página de Dashboard  

Tópico | Definición  
---|---  
Métricas en tiempo real | Muestra datos actualizados sobre flujo y permanencia de visitantes.  
Visualización gráfica | Presenta gráficos y diagramas para facilitar la interpretación de datos.  


### Página de Sensores  

Tópico | Definición  
---|---  
Lista de sensores | Muestra todos los dispositivos IoT activos en el sistema.  
Estado de sensores | Indica el funcionamiento y estado de cada sensor.  


### Página de Reportes  

Tópico | Definición  
---|---  
Lista de reportes | Muestra los reportes generados por el sistema.  
Detalles de reportes | Permite visualizar análisis detallados y exportar información.  


### Página de Contact  

Proporciona información de contacto y soporte técnico para consultas.  

Tópico | Definición  
---|---  
Formulario de contacto | Permite enviar consultas directamente al equipo de soporte.  
Información de contacto | Muestra canales como correo o asistencia técnica.  


### Registro y autenticación  

La página permite a los usuarios acceder al sistema mediante credenciales seguras o registrarse como nuevos usuarios.  


### Otras páginas y funciones  

Tópico | Definición  
---|---  
Perfil de usuario | Permite gestionar la información personal y accesos del usuario.  
Configuraciones | Permite ajustar preferencias del sistema y parámetros de visualización.  
Página acerca de nosotros | Información sobre KhipuTech y su propuesta tecnológica.  
Ayuda y soporte | Recursos de ayuda, preguntas frecuentes y asistencia técnica.  


Barra de navegación:  
Una barra de navegación clara y consistente en la parte superior permite acceder a las secciones principales del sistema.  

Responsive design:  
La plataforma se adapta a dispositivos de escritorio y móviles, manteniendo la claridad en la visualización de datos.  



#### 4.2.2. Labeling Systems

Para los sistemas de etiquetado, se organiza el contenido mediante encabezados claros que agrupan las secciones disponibles dentro de la plataforma. Esto permite al usuario identificar fácilmente dónde acceder.  

Tópico | Definición  
---|---  
Home | Sección principal donde el usuario visualiza el resumen general del sistema.  
Dashboard | Sección donde se muestran métricas en tiempo real.  
Sensores | Sección donde se gestionan los dispositivos IoT.  
Zonas | Sección donde se visualizan las áreas monitoreadas.  
Reportes | Sección donde se consultan análisis e información histórica.  
Contacto | Sección donde el usuario puede comunicarse con soporte técnico.  

#### 4.2.3. SEO Tags and Meta Tags

- **Landing Page**
  Esta página está optimizada para que los directores, gestores y curadores de museos encuentren la solución en Google.

  - _Título:_ KhipuTech | Analítica de Bajo Costo para Museos y Galerías

  - _Descripción:_ Transforma tu museo con analítica de visitantes en tiempo real. Sensores IoT de bajo costo y experiencias interactivas mediante QR sin suscripciones mensuales.
  - _Intenciones de Búsqueda:_ analítica de museos, conteo de personas, sensores IoT perú, gestión cultural digital, métricas de exhibición.

  - _Autor:_ KhipuTech Team.

```html
<title>KhipuTech | Analítica de Bajo Costo para Museos y Galerías</title>
<meta
  name="description"
  content="Transforma tu museo con analítica de visitantes en tiempo real. Sensores IoT de bajo costo y experiencias interactivas sin suscripciones mensuales."
/>
<meta
  name="keywords"
  content="analítica de museos, conteo de personas, sensores IoT perú, gestión cultural digital, métricas de exhibición"
/>
<meta name="author" content="KhipuTech Team" />

<meta property="og:title" content="KhipuTech | Digitalización Cultural" />
<meta
  property="og:description"
  content="Mide el flujo de visitantes y mejora el engagement en tu galería."
/>
<meta property="og:image" content="https://khiputech.com/assets/og-image.png" />
<meta property="og:url" content="https://khiputech.com" />
```

- **Web Application**
  Esta página está optimizada para la funcionalidad y la carga rápida en dispositivos móviles.

  - _Título:_ KhipuTech | Analítica de Bajo Costo para Museos y Galerías
  - _Descripción 1:_ Descubre cómo KhipuTech ayuda a museos medianos a medir el flujo de visitantes con hardware de bajo costo.
  - _Descripción 2:_ Mejora el engagement de tu galería con contenido interactivo mediante QR y analítica de datos precisa.
  - _Descripción 3:_ Optimiza el aforo y la seguridad de tu centro cultural con nuestra solución de analítica de guerrilla.

  - _Intenciones de Búsqueda:_ dashboard interactivo, flujo de visitantes, métricas en tiempo real, gestión de sala.
  - _Autor:_ KhipuTech Software Division.

```html
<title id="dynamic-title">KhipuTech App | Dashboard</title>
<meta
  name="description"
  id="dynamic-desc"
  content="Panel de control de sensores y gestión de contenido interactivo."
/>
<meta name="author" content="KhipuTech Software Division" />
<meta name="robots" content="noindex, nofollow" />
```

#### 4.2.4. Searching Systems

KhipuTech maneja dos tipos de usuarios con necesidades de búsqueda distintas: el gestor/administrador que busca entre grandes volúmenes de datos analíticos, y el visitante que busca contenido de obras dentro del museo. Cada contexto tiene su propio sistema de búsqueda.

- **Búsqueda Global (Dashboard Administrativo):**

  Ubicada en la topbar, accesible desde cualquier vista del dashboard. Permite al administrador localizar salas, obras, reportes o métricas sin navegar por el menú.

  **Comportamiento**

  - Se activa con clic
  - Muestra resultados en tiempo real
  - Agrupa resultados por categoría: Salas, Obras, Reportes, Alertas

- **Filtros del Dashboard (Analítica y Afluencia)**

  Visibles en la topbar del boceto como selector de rango de fechas. Permiten acotar los datos mostrados en tablas, gráficos y rankings.
  | Filtro | Opciones | Ubicación en Mockups|
  | :--- | :--- | :---: |
  |**Rango de fechas**|Hoy / Esta semana / Este mes / Rango personalizado|Topbar|
  |**Sala / Zona**|Todas las salas / Sala Inca / Sala Virreinal / Sala Republicana / Sala Contemporánea|Header de sección|
  |**Tipo de contenido**|Todos / QR / NFC / Audio / Video / Imagen|Panel analítica|
  |**Estado de aforo**|Todos / Normal / Atención / Crítico|Panel afluencia|
  |**Exportación**|CSV / Excel · aplica los filtros activos|Botón topbar|

- **Ordenamiento en Tablas**

  La tabla de Top obras por interacción visible en el boceto permite al gestor reordenar segun distintos criterios. El criterio activo se indica con una fecha direccional junto al encabezado de columna.

  |         Criterio          |          Orden Default           |     Indicador Visual     |
  | :-----------------------: | :------------------------------: | :----------------------: |
  |    **Número de scans**    |   Descendente (mayor a menor)    |  Flecha abajo activa ⬇️  |
  | **Tiempo de permanencia** | Descendente (mas tiempo primero) |  Flecha abajo activa ⬇️  |
  |         **Sala**          |         Alfabético A - Z         | Flecha arriba activa ⬆️  |
  | **Estado de interacción** |         Alta>Media>Baja          | Badget de color ordenado |

- **Búsqueda de Obras**

  En la interfaz del visitante, accesible tras escanear un QR, la búsqueda se simplifica al mínimo para no interrumpir el recorrido:

  - _Barra de búsqueda:_ Por nombre de obra en la parte superior del interfaz.
  - _Filtro por sala:_ Mediante chips horizontales deslizables.
  - _Filtro por tipo:_ Chips contenido Audio, Video, Texto, Multimedia.

- **Límites del Sistema de Búsqueda**

  Para evitar sobrecarga cognitiva, KhipuTech no expone búsqueda de texto libre sobre datos crudos de sensores. Los sensores solo son consultables a través de los filtros estructurados de sala y fecha. Esto mantiene la interfaz orientada a decisiones, no a exploración técnica.

- **Resumen de Sistemas de Búsqueda**

  | Sistema                |   Usuario    |           Tipo           |     Filtros Principales     |
  | :--------------------- | :----------: | :----------------------: | :-------------------------: |
  | **Búsqueda Global**    | Gestor/Admin | Texto Libre + Categorias |    Salas, Obras, Alertas    |
  | **Filtros Dashboard**  | Gestor/Admin |  Filtros Estructurados   |  Fecha, Sala, Tipo, Estado  |
  | **Ordenamiento Tabla** | Gestor/Admin |   Click en Encabezado    | Scans, Tiempo, Sala, Estado |
  | **Búsqueda de Obras**  |  Visitante   |      Texto + Chips       |   Sala, Tipo de Contenido   |

#### 4.2.5. Navigation Systems

Explica las acciones y técnicas que guiarán a los Usuarios a traves del Landing Page y las aplicaciones, permitiendoles cumplir sus metas e interactuar de forma satisfactoria con el producto digital.

- **Superficies y Patrones de Navegación**

  | Superficie            |           Usuario            |          Patron Inicial          |        Patron Secundario        |
  | :-------------------- | :--------------------------: | :------------------------------: | :-----------------------------: |
  | **Landing Page**      | Visitante Potencial / Gestor |    Scroll lineal descendente     | Anclar (Anchor links) en navbar |
  | **Dashboard Admin**   |    Gestor / Administrador    | Sidebar fija + contenido central |        Breadcrumb + tabs        |
  | **Web App Visitante** |     Visitante del museo      |        Bottom nav mobile         |     Chips de filtro + Cards     |

  - _Landing Page — Navegacion Publica:_ La Landing Page usa scroll lineal descendente como tecnica principal. El usuario recorre las secciones de arriba hacia abajo sin necesidad de conocer la arquitectura del sitio. Una navbar fija con anchor links permite saltar directamente a cualquier seccion desde cualquier punto del scroll.

    - Navbar fija (sticky): Visible en todo momento. Contiene logo, anchor links a cada seccion y boton CTA primario 'Solicitar demo'. En mobile se colapsa en menu hamburguesa.

    - Scroll lineal: Las secciones se presentan en orden narrativo: problema -> solucion -> caracteristicas -> prueba social -> precio -> llamada a la accion.

    - Anchor links: Cada item del navbar hace scroll suave (smooth scroll) hacia la seccion correspondiente. La seccion activa se resalta en el navbar con subrayado cyan #00C8FF.

    - CTA flotante: Boton 'Solicitar demo' fijo en esquina inferior derecha en desktop. Aparece despues de que el usuario scrollea mas del 30% de la pagina.

    - Footer de navegacion: Repite los enlaces principales y agrega links secundarios (Politica de privacidad, Terminos, Contacto).

  - _Dashboard Administrativo — Navegacion por Sidebar:_ El Dashboard usa una sidebar fija de navegacion vertical como patron principal, visible en el boceto. Permite al gestor acceder a cualquier modulo sin perder el contexto de donde se encuentra. El patron secundario es el breadcrumb en la topbar, que indica la ruta exacta dentro del sistema.

        | Elemento      | Descripcion | Comportamiento de interaccion |
        | :------------ | :---------- | :---------------------------- |
        | Sidebar fija  | 240px de ancho. Agrupa items en secciones: Principal, Analitica, Contenido, Sistema. | |
        | **Breadcrumb** | En la topbar. Muestra ruta completa: KhipuTech > Analítica > Interacciones. | Cada nivel es clickeable y regresa al nivel superior. Separador chevron icon 12px. |
        | **Tabs internos** | Dentro de vistas con sub-secciones (ej: Hoy / Semana / Mes en gráficos). | Tab activo: pill con fondo cyan 15% y texto cyan. Transición instantánea de contenido. |

  - _Web App del Visitante — Navegacion Mobile-First:_ La Web App está diseñada para ser usada en movilidad dentro del museo. El patrón principal es la **navegación por cards** tras escanear un QR o NFC. Sidebar con 4 items: Escanear QR/NFC, Detalle de obra, Mapa de recorrido, Logros y XP.

    | Elemento               | Descripción                                                                  | Comportamiento                                                                     |
    | :--------------------- | :--------------------------------------------------------------------------- | :--------------------------------------------------------------------------------- |
    | **Entrada por QR/NFC** | El punto de entrada principal. No requiere navegación previa ni login.       | Carga el contenido de la obra en menos de 3 segundos directamente en el navegador. |
    | **Panel de obra**      | Detalle multimedia (imagen, audio, video) + obras relacionadas.              | Cards deslizables con filtro por sala. Historial de obras recientes.               |
    | **Mapa del museo**     | Vista de planta simplificada. Indica sala actual del visitante y congestión. | Tap en sala navega a las obras. Zonas en rojo indican alta ocupación.              |
    | **Gamificación**       | Ranking semanal de visitantes con sistema de XP y niveles.                   | Visualización de logros desbloqueados y progreso hacia siguiente nivel.            |

  - _Principios de Navegación KhipuTech:_
    - Máximo 3 clics: Cualquier acción o dato desde el Dashboard.
    - Máximo 2 taps (visitante): Nunca más de 2 taps para contenido de obra.
    - Contexto siempre visible: Breadcrumb en dashboard, indicador de panel activo en sidebar.
    - Sin login obligatorio: Web App del visitante accesible de forma inmediata.
    - Estado activo siempre señalado: Item activo resaltado con color cyan #00C8FF.

#### 4.3. Landing Page UI Design

#### 4.3.1. Landing Page Wireframe

#### 4.3.2. Landing Page Mock-up

### 4.4. Web Applications UX/UI Design

#### 4.4.1. Web Applications Wireframes

#### 4.4.2. Web Applications Wireflow Diagrams

#### 4.4.3. Web Applications Mock-ups

##### Descripción general

El mock-up presentado corresponde al Dashboard de monitoreo general del sistema, diseñado para administradores del museo. Su objetivo principal es ofrecer una visión centralizada, en tiempo real, del comportamiento de los visitantes, el uso de las exhibiciones y el estado operativo del museo.

Este diseño responde a las épicas relacionadas con:

- Analítica (EP02, EP06)
- Operación (EP03, EP04)
- Alertas inteligentes (US51)

#### Principios de diseño aplicados

#### 1. Jerarquía visual

Se prioriza la información más relevante en la parte superior:

- KPIs principales (visitantes, interacciones, permanencia, alertas)
- Luego gráficos y análisis
- Finalmente detalles (tablas y alertas)

#### 2. Consistencia

- Uso uniforme de colores (azules oscuros + acentos)
- Tipografía homogénea
- Componentes reutilizables (cards, tablas, alertas)

#### 3. Feedback visual

- Indicadores de crecimiento (+12%, +7%)
- Colores de estado:
  - 🔴 Saturación
  - 🟡 Atención
  - 🟢 Normal

#### 4. Minimalismo funcional

Se evita saturar la interfaz:

- Solo métricas clave visibles
- Espacios amplios
- Separación clara por secciones

#### Elementos de diseño

#### Cards de métricas (KPIs)

Ubicadas en la parte superior:

- Visitantes
- Interacciones QR/NFC
- Tiempo de permanencia
- Alertas activas

#### Gráfico de afluencia por hora

- Visualiza entradas y salidas
- Permite detectar picos de tráfico

####  Ocupación por sala

Panel lateral con:

- Capacidad vs ocupación
- Estado visual (color + etiqueta)

#### Alertas recientes

Lista de eventos relevantes:

- Aforo crítico
- Umbrales superados
- Baja interacción


#### Diseño inclusivo

El sistema considera accesibilidad mediante:

- Contraste alto (modo oscuro)
- Tipografía legible
- Uso de colores + texto (no solo color)
- Información jerárquica clara

Mejora la experiencia para:

- usuarios con fatiga visual
- entornos con poca iluminación
- distintos perfiles de usuarios

#### Arquitectura de la información

La navegación lateral está organizada en:

#### 1. Principal

- Dashboard
- Afluencia en vivo
- Mapa de salas

#### 2. Analítica

- Interacciones
- Permanencia
- Tendencias
- Exportar reportes

#### 3. Contenido

- QR / NFC
- Obras

#### 4. Sistema

- Acceso y roles
- Configuración

#### Relación con el Design System

El mock-up evidencia un sistema de diseño consistente:

#### Paleta:

  - Azul oscuro (base)
  - Verde (positivo)
  - Amarillo (advertencia)
  - Rojo (crítico)

#### Componentes reutilizables:

  - Cards
  - Tabs (Hoy / Semana / Mes)
  - Listas
  - Indicadores de estado
  - Espaciado uniforme
  - Bordes redondeados (modern UI)
#### Valor del diseño

Este dashboard permite:

- Monitoreo en tiempo real
- Toma de decisiones basada en datos
- Detección de problemas (aforo, interacción)
- Optimización de la experiencia del visitante

#### 4.4.4. Web Applications User Flow Diagrams

#### USER FLOW 1 — Visitante accede a contenido

#### User Persona

Visitante del museo

#### User Goal

Acceder al contenido digital de una obra de forma rápida y sin fricción.

#### 🟢 Happy Path

1. Escanea QR
2. Se abre contenido en navegador
3. Visualiza contenido multimedia
4. Navega a otra obra (opcional)

#### 🔴 Unhappy Paths

- QR inválido → “Contenido no disponible”
- Sin internet → mensaje de error
- Dispositivo no compatible → fallback

#### Pantallas involucradas

- Vista QR
- Vista contenido

#### Explicación

El flujo inicia cuando el visitante escanea un código QR ubicado en la obra. El sistema redirige automáticamente a una vista web donde se presenta contenido multimedia. El usuario puede explorar información adicional o navegar a otras obras. En caso de errores, el sistema muestra mensajes claros para mantener la experiencia.

#### 🟣 USER FLOW 2 — Administrador monitorea el museo

#### User Persona

Administrador del museo

#### User Goal

Supervisar en tiempo real el estado del museo para tomar decisiones rápidas.

#### 🟢 Happy Path

1. Accede al sistema
2. Ingresa al dashboard
3. Visualiza métricas principales
4. Revisa ocupación por sala
5. Identifica alertas
6. Toma decisión

#### 🔴 Unhappy Paths

- Datos no cargan → mensaje de error
- Sin datos → estado vacío
- Error en sensores → alerta técnica

#### Pantallas involucradas

- Dashboard

#### Explicación

El flujo comienza cuando el administrador accede al sistema y visualiza el dashboard principal. Este presenta métricas clave como afluencia, interacción y alertas. El usuario puede identificar rápidamente situaciones críticas y tomar decisiones operativas. En caso de fallos en los datos, el sistema informa el problema sin afectar la navegación.

#### 🟡 USER FLOW 3 — Acceso con suscripción

#### User Persona

Visitante recurrente

#### User Goal

Acceder a contenido premium sin restricciones mediante suscripción.

#### 🟢 Happy Path

1. Usuario accede al contenido
2. Sistema valida suscripción
3. Acceso permitido
4. Navega libremente

#### 🔴 Unhappy Paths

- Suscripción vencida → pedir renovación
- No suscrito → acceso limitado
- Error de validación → mensaje

#### Pantallas involucradas

- Vista contenido
- Pantalla de acceso/restricción

#### Explicación

El flujo inicia cuando el visitante intenta acceder a contenido digital. El sistema valida si cuenta con una suscripción activa. Si es válida, el acceso es ilimitado; de lo contrario, se restringe y se invita a renovar. Esto permite implementar un modelo de acceso controlado y monetización del contenido.

### 4.5. Web Applications Prototyping

#### 4.6. Domain-Driven Software Architecture

### 4.6.1. Design-Level Event Storming.

#### 4.6.2. Software Architecture Context Diagram

#### 4.6.3. Software Architecture Container Diagrams

#### 4.6.4. Software Architecture Components Diagrams

### 4.7. Software Object-Oriented Design

#### 4.7.1. Class Diagrams

### 4.8. Database Design

#### 4.8.1. Database Diagram

---


