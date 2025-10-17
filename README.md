En este ejercicio se nos pedía crear una página web que se asemejara lo máximo posible a la imagen de referencia, partiendo del código base proporcionado.
Además, de forma opcional, podíamos realizar la versión Advanced Level.

Carpetas: 

Archivos base en ./starter/
Hoja de estilos externa en ./starter/css/
Imágenes en ./starter/img/

Requisitos:

Utiliza una hoja de estilos externa para el CSS (por ejemplo, ./starter/css/style.css).
Incluye y utiliza reset.css.
Implementa un efecto parallax en las imágenes de fondo.
Los contenedores (div) que crean el efecto parallax deben tener:
width: 100vw
height: 20vh
Puedes añadir las clases o IDs que necesites para organizar el código.

Pistas técnicas (opcionales)

Parallax sencillo con CSS:

.parallax {
  background-image: url('./img/bg-01.jpg');
  background-attachment: fixed;
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
  width: 100vw;
  height: 20vw;
}
Recuerda colocar el reset antes del resto de estilos.

ADVANCED LEVEL
Haz que, cada vez que el ratón pase por encima de una de las imágenes de fondo, esta se muestre en blanco y negro.

Tip: 

filter: grayscale(100%);

Aplicarlo directamente al contenedor si la imagen está en background-image.