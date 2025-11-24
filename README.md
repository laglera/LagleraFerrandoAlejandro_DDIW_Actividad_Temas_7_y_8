Ejercicio Temas 7-8: Integración Multimedia
Alejandro Laglera Ferrando
Índice
  - Subtítulo del encabezado
Ejercicio Temas 7-8: Integración Multimedia
Selección de formatos de audio y video
Audio de fondo:
Video de presentación:
Configuraciones de reproducción
Desafios técnicos
Capturas de pantalla
Subtítulo del encabezado 3^
1. Selección de formatos de audio y video
Audio de fondo:
MP3 (192 kbps) + OGG (q7)
Razon: MP3 alcanza el 98% de navegadores, OGG cubre FIrefox/Chrome en Linux sin
licencias
Accesibilidad: Se ofrece un botón “Silenciar” visible desde el primer momento y un
modal de consentimiento al entrar, evitando molestias a usuarios con déficit de
atención o lectores de pantalla
Video de presentación:
MP4 H.264 (baseline, 720p, 1 Mbps) + OGG Theora + WebM VP
Razon: MP4 es compatible con Safari iOS/macOS, WebM cubre Chrome/Firefox/Edge,
OGG asegura soporte en navegadores open-source antiguos
Accesibilidad: Subtítulos no necesarios al ser video mudo (Solo música de fondo), se
incluye poster para indicar contenido antes de pulsar “Reproducir”.
2. Configuraciones de reproducción
Elemento Propiedad Valor Justificacion UX
Audio preload=”none” No descarga hasta
aceptar modal
Ahorra datos
móviles
Audio loop + volume=0,05 Bucle a 5% volumen Ambiente sin
distracción
Video preload=”none” No carga hasta
hacer clic
Reduce 800 kB de
entrada
Video controls Nativos visibles Usuario decide
pausar o saltar
Video poster=”img/poste
r.jpg”
Portada profesional
Subtítulo del encabezado 4^
3. Desafios técnicos
Problema Solucion

Los navegadores bloquean el autoplay Puse un modal que pregunta si quieren
activar audio, tras aceptar, suena

El audio suena demasiado fuerte Baje el volumen a 0,05 nada más
reproducirlo

El video pesa mucho Dejé preload=”none” y lo comprimi en
MP4, WebM y OGG para que solo se
descargue si deciden verlo

El botón flotante estorbaba Lo pase a la esquina inferior izquierda y lo
hice mas pequeño

Smart-TV y moviles viejos Usé H.264 baseline, para que se
reproduzca en cualquier dispositivo

Subtítulo del encabezado 5^
4. Capturas de pantalla
Modal que pide consentimiento para reproducir el audio

Collapse en la sección de contacto

Video Portfolio con botón para reproducirlo

Subtítulo del encabezado 6^
Boton flotante para activar/desactivar el audio de fondo
