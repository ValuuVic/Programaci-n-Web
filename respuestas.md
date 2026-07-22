
PARTE 2 — Mida su propia imagen
Ahora mida la imagen que subio, que es la que va a estar en su sitio.
1.  Tome su foto original, sin tocar. Guarde el peso en kilobytes.
2.  Conviértala a JPG con calidad alta, a PNG, a WebP y a AVIF.
3.  Anote el peso real de cada una.
4.  Llene esta tabla en un archivo de texto o en el mismo repositorio:

Formato		Peso en KB	¿Se ve peor? ¿Dónde exactamente?
Original	35.1kb		La imagen original se encuentra en formato JPG
JPG		35.1kb		Imagen original
PNG		279kb		No se aprecia que cambie realmente a simple vista
WebP		36kb		No se aprecia que cambie realmente a simple vista 
AVIF		122kb		No se aprecia que cambie realmente a simple vista

Después responda en dos o tres líneas cada una:
5.  ¿Cuál eligió para su hoja de vida y por qué? La respuesta tiene que mencionar un número que usted midió.
	Utilice el formato AVIF ya que, aunque el peso era de 122kb garantiza la compatibilidad y calidad visual al momento de verse en diferentes navegadores, teniendo como respaldo el formato webp y jpg.
6.  ¿El resultado se parece al de la imagen de clase o salió distinto? Si salió distinto, ¿qué tiene su foto que la otra imagen no tenía?
	El resultado siempre variara dependiendo del contenido que se encuentre en cada foto, el numero de pixeles y el tamaño de la imagen. Además, el peso final dependerá de la imagen evaluada, por lo tanto los resultados al momento de convertir una imagen siempre serán diferentes.


PARTE 3 — Preparate para la próxima clase
Tres preguntas que hoy no puede responder con HTML. Investigue y traiga una respuesta escrita, corta, con la fuente que consultó.
Pregunta 1
Su formulario tiene un campo de fecha con un calendario que aparece al hacer clic. Averigüe si ese calendario se puede cambiar de color, de tamaño o de tipografía. Explique qué encontró y por qué es así.
No, no es posible estilizar directamente el calendario debido a que este componente lo genera e integra el navegador web y el sistema operativo de forma nativa, por lo que no se puede cambiar el diseño desde HTML y CSS por motivos de seguridad y para que siga teniendo una consistencia visual.
Fuente: https://stackoverflow.com/questions/14946091/are-there-any-style-options-for-the-html5-date-picker

Pregunta 2
En clase escribió required y min en su HTML. Averigüe qué son :valid e :invalid, y explique qué relación tienen con esos atributos que ya escribió.
Son pseudoclases que pertenecen a CSS que nos dice que dependiendo de una entrada generara una de estas dos respuestas, :valid significa que el contenido de un elemento se pudo validad de forma exitosa, permitiendo que se le pueda confirmar al usuario que los datos ingresados tienen el formato correcto. Mientras que :invalid significa lo contario, que los datos no se lograron validar correctamente con el objetivo de pedirle al usuario que ingrese los datos correctamente. Se relaciona con los atributos que ya utilizamos como required o min ya que al utilizar atributos restrictivos u obligatorios el navegador evalúa el contenido y dependiendo si cumple o no con el formato establecido se activa alguna de las mencionadas pseudoclases. 
Fuentes:
https://developer.mozilla.org/en-US/docs/Web/CSS/Reference/Selectors/:valid
https://developer.mozilla.org/en-US/docs/Web/CSS/Reference/Selectors/:invalid

Pregunta 3
Su img tiene width y height con las dimensiones reales del archivo. Si esa imagen se abre en un teléfono, va a salirse de la pantalla. Averigüe qué hace falta para que se adapte al ancho disponible, y por qué no alcanza con cambiar los números del width.
Para que se adapte al ancho posible debe aplicarse el diseño responsivo el cual tiene la función de que las imágenes y la pagina en general se adapten de forma automática a cualquier tamaño de pantalla, garantizando que la pagina sin importar en que dispositivo se abra se vea correctamente, esto se realiza por medio de CSS ya que no es suficiente con cambiar los números fijos del ancho en html ya que esos valores pueden llegar a no verse bien en diferentes tamaños de las pantallas.
Fuente: https://developer.mozilla.org/es/docs/Web/HTML/Guides/Responsive_images

