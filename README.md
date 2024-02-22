# Proyecto de Programación Web Unidad 2
**García Galaz Rodolfo**
El Blog esta divido en 6 secciones principales: Titulo, Links a artículos, sección de About Me, formulario para suscribirte, adicionales y el pie de página.

- Titulo. Contiene un logo y el título del blog.
- Links de Artículos. Contiene 3 ligas a artículos del blog con un breve preview del mismo.
- Abu Me. Da información general sobre el blog.
- Formulario para subscribirte. Contiene un input para introducir tu correo electrónico.
- Adicionales. Contiene un link a una pagina de Wordpress con Ebooks de letras de albums, un reproductor embedido de SoundCloud y una playlist de Spotify embebida.
- Pie de Pagina. Contiene un mensaje de copyright y autor de la pagina.

La pagina esta diseñada para cambiar su estructura de acuerdo a 3 rangos de dimensiones de la ventana del navegador por el cual se accesa. Se tienen 3 categorías: móvil, escritorio y tableta. Tambien se esta configurado para mantener la estructura en caso de que el dispositivo este en modo Portrait o Landscape.

Existe un archivo principal llamado _main.html_, el cual contiene la estructura de la pagina principal. Ademas, tenemos 3 HTML adicionales contenidos en la carpeta _pages_ llamados _blog1.html_,_blog2.html_ y _blog3.html_ que contienen paginas simples con articulos escritos y algunos elementos embebidos.

Los estilos de los cuatro archivos HTML están contenidos dentro de la carpeta _CSS_ en el archivo _styles.css_ de tal manera que todas las paginas tienen un estilo coherente.

El comportamiento de las secciones se controla principalmente a través de las etiquetas *display: block* para asegurar el salto de línea y cuando se deseaba mostrar múltiples elementos en la misma línea se utiliza un contenedor que contiene los elementos que podrían ser parte del grid y hace uso de la etiqueta *display: grid;* junto con *grid-template-columns: 1fr 1fr;* para crear una cuadricula. En este ejemplo se utilizan 2 columnas representadas por cada numero acompañado por *fr*, el número indicando la relación de tamaño entre las columnas.

Mayormente los valores dados de márgenes y tamaño se configuraron basados en porcentajes de forma que sean flexibles en tamaño y se adapten al tamaño de la pantalla.
