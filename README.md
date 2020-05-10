# P3_StreamingServiceDash An adaptative streaming player client based in dash.js with video digital right management.

El video es un modo de comunicación muy extendido ahora, tanto para contenido multimedia de ocio (películas, series o videoclips musicales),
como para contenido educativo. Para permitir el streaming, se suele usar servicios de visualización de streaming como YouTube o Vimeo, o
para material educativo propio, Udemy o Teachable. Bien, para no depender de estos servicios de terceros para publicar contenido propio 
(por ejemplo, por la posible desmonetización casi aleatoria sobre los videos de youtube o el coste de las páginas de difusión de contenido 
educativo), cobra importancia entender cómo visualizar un streaming de video con una aceptable calidad de experiencia.  La librería 
Dash.js, que implementa el estándar MPEG dash, hace esto posible para visualizar streaming en una interfaz web.

El objetivo de esta práctica es prototipar *un servicio de streaming de video*. Arquitecturalmente,
este servicio se descompone en: un proceso servidor y un proceso cliente. En particular, en este proyecto se
describe cómo se han cumplido tres requisitos en ambos procesos: en la primera sección, se prototipa una interfaz web
cliente con la librería dash.js para poder visualizar el contenido en esta como un stream que se adapte a la calidad. 
En la segunda sección, se discute cómo generar estos videos para este streaming y se visualizan las métricas de calidad 
de la experiencia del servicio de streaming. En la tercera sección, se describe cómo gestionar los derechos del contenido
digital con dash.js: es decir, cifrándo lso videos para que sólo se puedan ver por ciertos usuarios.


By Jose Manuel Valbuena, Xuan Chen, Laura Zarandieta and Adrián Blázquez

