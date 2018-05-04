# Artículos de blog del sitio de meetup.js

[Blog](http://meetupjs.com.ar/blog.html)

## Colaboración

Lo bueno de que estos artículos estén en GitHub es que podamos _discutirlos, modificarlos y trabajarlos de una manera colaborativa_ antes de publicarlos.

## ¿Cómo escribir un artículo?

> Disclaimer: todo esto es muy manual, algún día se mejorará 😅

* Crear 2 archivos con el mismo nombre pero con diferente extensión (`.json` y `.md`). El nombre se compone de un número (que sirve para organizar los artículos en el listado) y el título del artículo separado por guiones.
* El archivo `.json` tiene información que sirve para generar el html del artículo: título, fecha de publicación, autores, etc.
* En el archivo `.md` usá _markdown_ para escribir tu artículo.

## Tips

* Si necesitás agregar un *video*, *imágen*, *documento para descargar*, *gif* o cualquier otro archivo, te recomendamos crear una carpeta con el mismo nombre del artículo y poner lo que necesites ahí adentro para poder referenciarlo, evitando usar una URL externa que puede dejar de estar disponible en algún momento.

    En el caso de las imágenes, podés usarlos de la siguiente manera desde _markdown_ `![alt de la imágen](https://raw.githubusercontent.com/meetupjs-ar/blog-articles/master/{nombre-de-la-carpeta}/{nombre-del-archivo}.{extensión})`
