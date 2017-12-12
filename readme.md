# Manual de Cinta Blanca Devf
### Índice

* HTML
    * [Etiquetas](###Variables)
    * 
    * 
    * 

## HTML
Hyper Text Markup Languaje 

### Etiquetas
Son las estructuras fundamentales de HTML, las etiquetas tienen diferentes funciones dentro de un archivo así como una sintaxis establecida.

##### Sintaxis
Las mayoría de etiquetas constan de dos partes, la etiqueta de apertura y la etiqueta de cierre; ambas comienzan con el símbolo `<` y terminan con el símbolo `>`; la etiqueta de cierre se diferencia por tenener la estructura `</` al principio.   
```html
<html>
</html>
```
Algunas etiquetas tienen ciertas variaciones en su sintaxis por ejemplo, la etiqueta `<img />` se emplea para insertar una imagen en la página web, pero por si sola no funciona correctamente. Necesita que le incorporemos un parámetro en el que indiquemos qué imagen será la que se muestre. Quedaría así:
```html
    <img src=""/>
```

Hay etiquetas más sencillas como `<br>` que sirve para dar un salto de línea. 

##### Estructura básica para un archivo HTML
En `HTML5` necesitamos la siguiente estructura básica para poder crear un sitio web.

```html
<!DOCTYPE> <!--indica al navegador que estamos usando HTML5-->
<html>
<head>
    <title>Hello, world!</title>
    <meta charset="utf-8">
</head>
<body>

</body>
</html>
```

##### Etiqueta head
Contiene información acerca de la página web como el idioma, el título que aparecerá en la pestaña del navegador, archivos externos como hojas de estilos, etc. 
> La información que se pone en head no es visible para los usuarios dentro del cuerpo de la página

##### Etiquetas básicas para el head
```html
<head>
    <!-- titulo del sitio web -->
    <title>Website</title> 
    <!-- Permite visualizar correctamente caracteres como los acentos y las Ñ -->
    <meta charset="utf-8">
    <!-- las etiquetas meta le permiten a los buscadores utilizar la información para un mejor posicionamiento en los resultados de busquedas -->
    <meta name="author" content="angeloLuna">
    <meta name="description" content="Mi primer sitio web">
    <meta name="keywords" content="HTML">
</head>
```
##### Etiqueta body
Dentro de esta etiqueta va todo el contenido que los usuarios van a ver a través de su navegador, como la barra de navegación, imagenes, botones, texto, etc.

##### Etiquetas más comunes
---
**h1**
```html
<!--para encabezados, van desde h1 a h6 en orden descendente de importancia, se usan para estructurar títulos y subtitulos -->
<h1>texto</h1>
<h2>texto</h2>
```
**p**
```html
<!-- Parrafos -->
<p>Esto es un parrafo de ejemplo</p>
```
**span**
```html
<!--para agrupar texto y poder darle estilos dentro de un parrafo -->
<p>esto es un parrafo de ejemplo <span>Esto es texto dentro de un parrafo</span></p>
```
**img**
```html
<!-- Insertar una imagen en el sitio web, necesita como parametro la ubicación de la imagen, ya sea en el equipo o una direccion url -->
<img src="url">
```
**a**
```html
<!-- Convierte al contenido de la etiqueta "a" en un hipervinculo a donde est´é especificado dentro del parametro "href" -->
<a href="link">Esto es ahora un link</a>
```
**ul**
```html
<!-- Lista desordenada, es una etiqueta de tipo bloque que va a contener elementos de lista -->
<ul>
</ul>
```
**li**
```html
<!-- Elementos de lista van siempre dentro de una etiqueta ol o ul  -->
<ul>
    <li>Primer elemento</li>
    <li>Segundo</li>
    <li>Tercero</li>
    <li>Cuarto</li>
</ul>
```






### Variables

###### Asignación de variables y tipos de datos
Una variable es un elemento al que le damos un nombre y puede contener datos.
Para definir una variable se usa la palabra reservada `var` seguida del nombre que le queremos dar y usando el simbolo de igual `=` le asignamos el valor 