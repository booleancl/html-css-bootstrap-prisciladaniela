# HTML CSS BOOTSTRAP

Html CSS y Javascript son los pilares de toda aplicación o sitio web. Cualquier cosa que funcione dentro de un navegador web (chrome, mozilla, safari) utiliza estos pilares. Y no solo eso, hoy también se pueden hacer aplicaciones "nativas" con estas tecnologías.

## HTML

Significa **Hyper Text Markup Language**, que en castellano sería algo como Lenguaje de marcado de hyper texto. Lenguaje de marcado es por la *Etiquetas*. Dependiendo de su etiqueta el navegador lo procesa de diferente forma. Y el hyper texto se refiere a que estos documentos están enlazados por *links*.

Con HTML crearemos *documentos estructurados* mediante etiquetas que el navegador puede interpretar.

El documento principal de un sitio o aplicación de debe llamar **index.html**. Todo junto y en minúsculas.

### Doctype

Esta primera etiqueta indica al navegador la versión de HTML. En este caso indica que es la versión 5.
```html
  <!DOCTYPE html>
```

### html
Luego de eso viene la primera etiqueta que es parte del documento. la famosa etiqueta **html**:
```html
<html lang="es">
  ...
</html>
```

Del ejemplo anterior vemos que esta etiqueta se compone de 2 partes principales. La etiqueta de apertura `<html>` y la de cierre `</html>`.

Entremedio de las etiquetas de apertura y cierre irá el contenido.

Además vemos la etiqueta de apertura tiene el **atributo** `lang="es"`, lo que le indica al navegador en qué idioma está el contenido del documento.

>**ATENCIÓN**: Solo las etiquetas de apertura pueden tener atributos, Las etiquetas de cierre no.

### head

A continuación viene etiqueta `head`. Esta etiqueta entrega información al **Navegador** sobre como visualizar el contenido que vendrá en las siguientes secciones. Por ejemplo se indica mediante etiquetas `meta` el set de caracteres que utilizará la página. Ejemplo:

```html
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Hola Microsystem</title>
</head>
```

La tercera etiqueta `meta` que tiene el atributo `name="viewport"` permite que el contenido se cargue inicialmente considerando el tamaño de pantalla disponible, desde grandes a muy pequeños.

Además dentro del head se encuentra la etiqueta `title`, que es la encargada de mostrar el nombre del sitio en la pestaña del navegador.

Por otra parte dentro del `head` podemos cargar otros recursos que utilizará el documento como por ejemplo hojas de estilo CSS o archivos Javascript

### Estructura Jerárquica

Algo que es muy muy muy importante notar y que no es tan evidente, es que los documentos HTML forman una estructura jerárquica bien definida del tipo árbol. Donde la etiqueta raíz es la etiqueta `html`. Lo podemos visualizar de la siguiente forma

```html
  <html>
    <head></head>
    <body></body>
  </html>
``` 

Esto es muy importante de comprender ya que luego manejaremos las etiquetas pensando en su ubicación relativa dentro del árbol. Y pensaremos que las etiquetas son **nodos** que tienen **nodos padre**, **hermanos** y **nodos hijos**

## Etiquetas principales

## Titulos

Las etiquetas para hacer titulos son etiquetas **h** con numeros del 1 al 6. Ejemplo

```html




### Listas
### Ordenadas

 <ol>
        <li>Lunes</li>
        <li>Martes</li>
        <li>Miercoles</li>
        <li>Jueves</li>
        <li>Viernes</li>
    </ol>

## No ordenadas

    <ul>Pilares de la web
        <li>HTML</li>
        <li>CSS</li>
        <li>Javascrips</li>
    </ul>



