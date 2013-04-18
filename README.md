comicreader
===========

Uso:

Para mostrar una serie de imagenes como comic, hay que encerrar las imagenes en un div cuya clase sea "comic" 

`<div class="comic">`<br/>
  `<img src=01.jpg></img>`<br/>
  `<img src=02.jpg></img>`<br/>
  `<img src=03.jpg></img>`<br/>
  ...<br/>
  `<img src=0n.jpg></img>`<br/>
`</div>`<br/>

Cuando se carga el js, el contenido de ese div es reemplazado por un boton que al hacerle click comienza a mostrar
las imagenes en tamanio grande, ocupando todo el area de la pagina, el texto que muestra el boton sera "Read comic",
para cambiarlo hay que usar la propiedad name del div, asi:


`<div class="comic"  name="Leer comic">`<br/>
  `<img src=01.jpg></img>`<br/>
  `<img src=02.jpg></img>`<br/>
  `<img src=03.jpg></img>`<br/>
  ...<br/>
  `<img src=0n.jpg></img>`<br/>
`</div>`<br/>


Si las imagenes que queremos mostrar, estan en enlaces, entonces se usa la clase "comic-a", asi:

`<div class="comic-a">`<br/>
  `<a href=01.jpg></a>`<br/>
  `<a href=02.jpg></a>`<br/>
  `<a href=03.jpg></a>`<br/>
  ...<br/>
  `<a href=0n.jpg></a>`<br/>
`</div>`<br/>

Blogspot
========

Este js esta pensado para su uso en blogspot, para mostrar un comic, basta con agregar las imagenes en un articulo
y con el editor de html agregar el div de manera que encierre a todas la imagenes

Para incluir el script+estilo en el blog, el metodo mas practico que encontre fue crear un widget de HTML+js y
ponerlo todo ahi, si alguien sabe algun metodo mas practico y/o prolijo avisen por favor

