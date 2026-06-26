# sesión 10 - 15/05

Sesion-10 19/06

## SONIDO

PASO 01 : SUBIR SUS SONIDOS

Para subir un sonido en p5.js, primero se abre el menú de archivos
con la flecha ubicada en la parte superior izquierda del editor.
Luego se presiona el botón + o el menú de Files y se elige Upload file.
Después se arrastra el archivo de sonido, idealmente en formato .mp3 o .wav.
Se recomienda usar nombres cortos, en minúsculas y sin espacios.
También es buena idea crear una carpeta llamada assets para guardar los archivos.
PASO 02 : DECLARAR Y PRECARGAR EL SONIDO

Primero se crea una variable global para almacenar el sonido.
Luego, en la función preload(), se carga el archivo utilizando loadSound(). Esto permite que el audio esté listo antes de que el programa comience a ejecutarse.
PASO 03 : ACTIVAR MI SONIDO

Le damos play al sonido en el function setup con: (nombreVariable.play();)