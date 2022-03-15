
La postal es un div con clase "postcard" que contiene un header, un body y un footer. Tiene margin auto para centrarla horizontalmente y un margin top para centrarla verticalmente.

El header tiene display flex para que muestre los elementos uno al lado de otro. Contiene 2 elementos: un h1 con el título de la postal y el logo de 4Geeks. Para que el logo se quede a la derecha hice el h1 más ancho de lo que el texto ocupa, así "empuja" el logo hacia la derecha.

Debajo está el body que está dividido en dos partes: body-left y body-right. Tiene display flex para que las dos partes estén una al lado de la otra.
Body-left tiene dos párafos con el contenido de la postal. Body-right tiene tres inputs para poner el nombre, email y un comentario de la persona que la envía. Los inputs tienen un placeholder que idica qué poner en cada uno. 

El footer contiene un botón de enviar tiene un text-align center para que esté centrado. El botón está hecho con una etiqueta button y tiene un padding de 5px para separa el texto de los bordes.


# ![4Geeks Logo](http://assets.breatheco.de/apis/img/images.php?blob&random&cat=icon&tags=4geeks,16) HTML Hello

[![Open in Gitpod](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io#https://github.com/4GeeksAcademy/html-hello.git)

The most basic boilerplate for any 4Geeks Academy student using the [gitpod.io](gitpod.io) coding editor.

[![How to open html/css preview of my project in gitpod](https://github.com/4GeeksAcademy/Templates-Boilerplates/blob/master/assets/hello-html-intro.png?raw=true)](https://youtu.be/dfbDCMu_p-0)

## What to do next?

Create an `index.html` file with the [basic HTML structure](http://content.breatheco.de/lesson/what-is-html-learn-html#page-structure) and see it live by running a web-server using the following command:

```sh
$ pip3 install flask && python3 server.py
```

- You can create as many HTML files as you want
- You can also create CSS files and import them into your website using a `<link>` tag placed between the `<head></head>` tags, like this:

```html
<head>
  ...
  <link rel="stylesheet" type="text/css" href="styles.css">
  ...
</head>
```
