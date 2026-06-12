# sesión 10 - 12/06
DISEÑO RESPONSIVO
-
(windowResised)

¿CÓMO CREAR UN SKETCH
QUE SE ADAPTE A DIFERENTES
TAMAÑOS DE PANTALLA?
-

1 CREAR UN CANVAS CON DIMENSIONES DINÁMICAS
-
usar las variables integradas en el sistema:
(windowWidth, windowHeight) estas variables leen constantemente
el ancho y alto disponibles de la ventana del navegador.

function windowResised 
resizeCanvas (windowWidth, windowHeight)

usar valores relativos 
usar fraciones y proporciones para organizar mis elementos del sketch 
(width / 2, height / 2) división 
(width . 0.25) multiplicación

si solamente utilizo estos comandos se va a deformar el dibujo 

estos e usa para arreglar ese problema 
incluir factor de referencia 
let referencia 
referencia=min(width, height) 

para crear figuras que no se deformen se deben crear variables que determinen una medida especifica que se utilizara de referencia y luego se incorporan a los valores relativos 

tambine es mejor usar translate push y pop 
