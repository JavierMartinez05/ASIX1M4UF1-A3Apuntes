# ASIX1M4UF1-A3Apuntes
Apuntes M4

<hr>
<hr>

## Primer capitulo: MARKDOWN...
ok
este texto esta en *cursiva*
este texto esta en _cursiva_
este texto esta en **negrita**
este texto esta en __negrita__
este texto esta en **_negrita y cursiva_**
1. primera opción de menú
2. segunda opción de menú
3. tercera opción de menú

* Primera opción de lista desordenada
* Segunda opción de lista desordenada
- Tercera opción de lista desordenada
    1. Primer submenú
    2. Segundo submenú
- Cuarta opción de lista desordenada
    * Tercer submenú
    * Cuarto submenú
+ Quinta opción de lista desordenada
+ Sexta opción de lista desordenada

<hr>
<hr>

<h4>Para hacer un parrafo:</h4>
```Lo podemos hacer poniendo lo siguiente: <p>Esto es un parrafo</p>```

<hr>
<hr>

<h4>Para crear un enlace</h4>
[Esto es un enlace](http://joan23.fje.edu "Enlace a la web del cole")

![Esto es una imagen](https://github.com/JavierMartinez05/ASIX1M4UF1-A3Apuntes/blob/main/diagrama.jpg "Titulo opcional de la imagen")

<hr>
<hr>


## Primer Capítulo: MARKDOWN

Ahora pasamos a los comandos y claves que nos sirven en MarkDown, primero para tener este lenguaje de programación en Visual Studio Code debemos insertalo, hacemos clic en Extensiones y buscamos markdownlint, por último lo instalamos.

Con este lenguaje podemos modificar nuestro texto. Para poder poner nuestro texto en cursiva, *Hay dos formas una es con asteriscos* (*texto*), usando dos asteriscos uno al inicio y otro al final del texto, este se pondra en cursiva automaticamente y _la segunda manera es con guiones bajos_ (_texto_), la otra forma es usando guiones bajos como en los asteriscos uno al inicio y otro al final del texto.

Otro formato para dar al texto es ponerlo en negrita. **También haydos formas de poner en negrita**(**texto**), usando dos veces seguidas el asterisco al inicio y final del texto lo pone en negrita y __esta otra forma también puede funcionar__ (__texto__), con doble guiones bajos al inicio y final del texto sirve para poner en negrita.

También se le puede poner el texto en negrita y cursiva al mismo tiempo ***como este ejemplo de negrita y cursiva*** (***texto***), de esta manera el texto saldrá en negrita y cursiva con tres astericos al inicio y final. ___De esta otra manera también se puede hacer las dos___ (___texto___), de esta otra fomra se puede hacer el texto en cursiva y negrita al inicio y final con tres guiones bajos.

1. Primera opción de menú.
2. Segunda opción de menú.
3. Tercera opción de menú.

De esta forma se puede crear una lista ordenada. Poniendo en orden de secuencia cada uno de los temas.

* Primera opción de lista desordenada.
* Segunda opción de lista desordenada.

_ Tercera opción de lista desordenada.
    1. Primer submenú.
    2. Segundo submenú.

_ Cuarta opción de lista desordenada.
    * Tercer submenú.
    * Cuarto submenú.
+ Quinta opción de lista desordenada.
+ Sexta opción de lista desordenada.

Este es un ejemplo de lista desordenada, en ves de usar números para dar un orden a la lista. Para la lista desordenada se usa (*, _, +), estos simbolos se usa una vez al inicio para comenzar la lista desordenada y dentro de las lista tanto ordenada y desordenada se puede poner submenús, dando al tabulador y también se puede usar partes de una lista ordenada o desordenada como (1, 2, 3, etc, o *, +, _), con estas características podemos abrir en submenús.

```
    <html>
    <head>
    </head>
    <body>
        <p>Esto es un párrafo</p>
    </body>
<html>

<h3>Tablas</h3>
<h4>CSS</h4>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        .textovioleta{
            color: black;
            background-color: blueviolet;
        }
        #primerafila{
            color: black;
            background-color: red;
        }
    </style>
</head>
<body>
    <table borde="1" style="color: red; text-align: center;">
        <thead>
            <tr id="primerafila">
                <th>Puesto</th>
                <th>Atleta</th>
                <th>Tiempo</th>
            </tr>
        </thead>
        <tbody style="background-color: rgb(0, 0, 255); color:white">
            <tr class="textovioleta">
                <td>1r</td>
                <td>Michael Phelps</td>
                <td>15:01</td>
            </tr>
            <tr class="textovioleta">
                <td>2n</td>
                <td>Pedro benito</td>
                <td>16:00</td>
            </tr>
            <tr>
                <td>3r</td>
                <td>Gerard Romero</td>
                <td>16:34</td>
            </tr>
        </tbody>
        <tfoot>
            <tr>
                <th></th>
                <th></th>
                <th></th>
            </tr>
        </tfoot>
    </table>
  
<h2>Cuarto</h2> 

  </body>