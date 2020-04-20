Para empezar, se creó una cabecera y un pie de página nuevo que será el general para todas las paginas, estas con respecto al formato dado para la página principal.

Para la cabecera se usó una imagen como logo relacionada a cada página, se coloco un cuadro para ingresar texto en conjunto con 3 iconos; y para finalizar, se usó una barra de menú para la navegación entre las páginas existentes.

![img1](/otros/i1.jpg)

El pie de pagina se dividió en 3 partes, usando la etiqueta fieldset, el formato de estas etiquetas van concorde al pie de pagina propuesto en la práctica, y su contenido tiene información general.  

![img2](/otros/i2.jpg)

# Pagin CSS:

## formatos.css

Este archivo es el que contiene formatos generales acerca de los estilos en artículos, secciones, etiquetas de texto, imágenes, entre otras.

Para empezar, se implementaron distintas fuentes para los formatos dentro de las paginas, para esto, se descargaros diferentes fuentes de https://fonts.google.com/.

![img3](/otros/i3.jpg)

Luego, se aplica una imagen como fondo de la página, además de esto, se indica que la imagen no se repetirá, sino se extiende para cubrir toda la página, además de que se mantendrá quieta mientras se navega por la página.

![img4](/otros/i4.jpg)

Se le da una indicación de que todas las imágenes dentro de una cabecera tendrán un borde redondeado.

![img5](/otros/i5.jpg)

Luego, se da forma a la parte inicial de la cabecera, en este caso, se indica las proporciones la una etiqueta a con una id “por” que hace referencia a la imagen de portada de la página, también se le indica las dimensiones que todas las etiquetas pertenecientes a la clase “icono” tendrán y para finalizar se indican las dimensiones del cuadro de texto.

![img6](/otros/i6.jpg)

Para finalizar el encabezado, se da un formato al menú de navegación, primero, a los hipervínculos con la etiqueta a se le otorga una fuente especial, se le cambia el color, tamaño y otros estilos.

![img7](/otros/i7.jpg)

Luego, se indica un formato especial a todas las etiquetas nav que pertenecen a una clase “menú”, este formato indica el color de fondo que tendrá en su estado normal, las dimensiones que tendrán y el alineamiento de su contenido.

![img8](/otros/i8.jpg)

Además, se aplico un estilo especial para cuando estas etiquetas se están señalando, se le agrego un color de fondo distinto al original.

![img9](/otros/i9.jpg)

Esto concluye con los estilos pertenecientes a la cabecera de todas las paginas, el resultado aplicando estos estilos con una de las paginas html queda de la siguiente forma:

![img10](/otros/i10.jpg)

Luego, se indica a que etiqueta pertenece cada fuente y se le otorga un color.

![img11](/otros/i11.jpg)

De aquí, se agregó un estilo especial para paginas que tienen el formato de dos y tres columnas, de igual manera que el menú, se le otorga una fuente y distintos estilos para los vínculos con etiqueta a.

![img12](/otros/i12.jpg)

Luego, se otorga estilos para las etiquetas nav que pertenezcan a la clase “vinculo”, además, se aplico un fondo diferente para cuando el cursor pase por estas etiquetas.

![img13](/otros/i13.jpg)

La implementación de este estilo en una pagina html de dos o tres columnas queda igual a lo siguiente:

![img14](/otros/i14.jpg)

También, se generó una clase para que cualquier etiqueta que lo use, envíe su contenido al su centro.

![img15](/otros/i15.jpg)

Se especificaron estilos generales para todas las paginas, estos estilos son con respecto a las secciones y a los artículos, se indica que tendrá un borde redondeado y un color de fondo especial.

![img16](/otros/i16.jpg)

Se decidió tener una clase separador, la cual pertenecerán a la etiqueta div, esto con el propósito de otorgar separaciones especificas entre diversas etiquetas, esto con un fin estético.

![img17](/otros/i17.jpg)

Para finalizar este archivo, se dieron especificaciones para el pie de página, especialmente una fuente en especifico y el color del texto dentro del pie de página.

![img18](/otros/i18.jpg)

Se da un estilo específico para las imágenes dentro del pie de página, se le otorga un porcentaje de anchura con respecto a su contenedor, además se otorgo una altura especifica en conjunto con un margen de espaciado.

![img19](/otros/i19.jpg)

También, se otorgo un estilo para las etiquetas fieldset, en el pie de pagina existen tres, por lo que se otorgo un margen izquierto para un espaciado, se le otorgo un tamaño de 25% con respecto al tamaño total de la pagina y se otorgo un pading de 40 pixeles.

**Nota:** A pesar de que la etiqueta <fieldset> es usada para formularios, es uso para que vaya de acuerto al pie de pagina propuesta por la página.

![img20](/otros/i20.jpg)

Y para finalizar el pie de página, se otorgo un estilo a una etiqueta span que tenga la id “derechos”, esto para ubicar el texto sobre los derechos reservados a la derecha.

![img21](/otros/i21.jpg)

Y esto concluye con este archivo de estilos css. Al aplicar estos estilos en una de las paginas html, el pie de pagina queda de esta forma:

![img22](/otros/i22.jpg)

## dosColumnas.css

Este archivo css consiste en dar un estilo de dos columnas a las paginas html, en el caso de esta práctica, este estilo se le aplico a las paginas pequeñas, sin mucho contenido. 

Primero, a los archivos html se les agrego etiquetas aside con un id para poder identificar si se coloca a la izquierda o a la derecha. Para el primer caso, si la etiqueta <aside> tiene el id que indica que es la columna de la izquierda, se le otorga una anchura correspondiente al 19% de la pagina total, se le coloca un color de fondo y se lo ubica a la izquierda.

![img23](/otros/i23.jpg)

Así mismo, el estilo de un <aside> con un identificador para que se coloque a la derecha, se le dio una anchura de un 80% de la página completa, además de un relleno de 10 pixeles para separarlo de la izquierda. 

![img24](/otros/i24.jpg)

Luego, para las imágenes, videos y videos bajo la etiqueta iframe dentro de un artículo, se le otorgo un margen de espacio para la izquierda de 100 pixeles, también se cambio su borde por uno redondeado de 20 pixeles y también, se otorgo un 40% de anchura con respecto a su contenedor.

![img25](/otros/i25.jpg)

Luego, se creó una clase .ita para las etiquetas no pertenecientes a texto que estén dentro de una etiqueta aside, esto con el propósito de redimensionar la anchura de una imagen dentro de esta etiqueta por estética.

![img26](/otros/i26.jpg)

Y para finalizar, se agrego un estilo para las etiquetas aside dentro de una etiqueta article en donde se indica los rellenos izquierdo y derecho, una anchura correspondiente a un 45% de su contenedor y se indica su posición ubicado a la izquierda.

![img27](/otros/i27.jpg)

## tresColumnas

Para empezar, Se agrego una fuente especial correspondiente al tipo de texto con el que se va a trabajar dentro de las tablas.

![img28](/otros/i28.jpg)

La tabla existente en esta pagina fue generada por una aplicación externa, por lo que todos los estilos se movieron hacia este archivo css, luego, se modificaron ciertos componentes para que estén acorde al estilo de la página, este proceso y estos cambios quedaron, en el archivo css, quedaron así.

![img29](/otros/i29.jpg)

Se generaron id para las etiquetas aside las cuales permitirán dividir por columnas al contenido de la página, estos id son: izq, cen, der. Las proporciones de anchura de las columnas tienen un 15% de la pagina para las columnas laterales y una anchura de 68% del total de la pagina para la columna central.

![img30](/otros/i30.jpg)

Se creo un estilo especial para un video con una id “vsolo” dentro de la columna central, este video tiene la característica de tener un mayor tamaño, puesto que es el único contenido de un artículo, entonces debe abarcar un mayor espacio de lo normal.

![img31](/otros/i31.jpg)

También se implemento un estilo para imágenes y videos dentro de artículos que pertenecen a la columna central, esto con el fin de otorgar proporciones de anchura de un 40% de su contenedor y también dando un margen redondeado a estos componentes.

![img32](/otros/i32.jpg)

Al igual que en las paginas de dos columnas, existe un estilo especial para las etiquetas que tienen la clase .ita, esto con el propósito de otorgar dimensiones diferentes a los componentes que están dentro de una etiqueta aside, pertenecientes a la columna central de la página, aparte, se indicó que estas especificaciones son importantes, sobreponiéndolas sobre algunos otros estilos anteriormente especificados.

![img33](/otros/i33.jpg)

También se da un estilo a las etiquetas aside dentro de la columna central, el estilo especial que se implemento a esta etiqueta es que su anchura poseerá el 45% de su contenedor.

![img34](/otros/i34.jpg)

Y para finalizar, se indicó que las imágenes que estén dentro de la columna central tendrán una anchura de casi el total de su contenedor, además que tendrán una altura de 150 pixeles.

![img35](/otros/i35.jpg)

## formulario.html

La creación de esta pagina contiene una cabecera y un pie de pagina igual al de todas las páginas. Pero, esta página contiene una sección con una imagen y una etiqueta aside la cual contiene un formulario (etiqueta form) con etiquetas label e input.

![img36](/otros/i36.jpg)

Visualmente esto se representa de la siguiente manera:

![img37](/otros/i37.jpg)

## formulario.css

Para este archivo, se agrego una fuente especial para los textos que estén dentro del formulario.

![img38](/otros/i38.jpg)

Se indico que los textos dentro de las secciones usaran esta fuente, también se indica que color usara (color general usado en todas las paginas) y quita el color de fondo que se había otorgado en formatos.css.

![img39](/otros/i39.jpg)

Se indico que las etiquetas de texto label tendrán texto en negrita y también se indica que tendra un estilo (display: block;) para que así, este label sea el único que este en la línea, y que los cuadros de texto estén abajo.

![img40](/otros/i40.jpg)

Para las etiquetas input, se agrego un color de letra, además de que se indica un margen de espaciado de 15 pixeles, además de que se puso un borde redondeado, a parte de que se indico un margen inferior de 10 pixeles para asignar un espaciado con el borde de la etiqueta fieldset.

![img41](/otros/i41.jpg)

Además, se asigno un cambio de color para cuando el texto es seleccionado.

![img42](/otros/i42.jpg)

Para la etiqueta input, del tipo botón, se asigno un margen de 260 pixeles para alinearlo con el final del textarea usado.

![img43](/otros/i43.jpg)

Para el textarea, perteneciente al comentario que puede introducir un usuario, se le otorgan los mismos valores de dimensión que los input de tipo text, a diferencia de su altura, puesto que se asigno una altira de 150 pixeles.

![img44](/otros/i44.jpg)

Y al igual que los inputs anteriores, se otorgo un color de fondo igual, para cuando un usuario interactúe con el textarea.

![img45](/otros/i45.jpg)

Y para finalizar, se indico que un aside dentro de esta página tendrá un espaciado izquierdo de un 38% con respecto al tamaño total de la pantalla.

![img46](/otros/i46.jpg)
