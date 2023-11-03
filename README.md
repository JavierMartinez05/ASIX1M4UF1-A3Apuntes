# ASIX1M4UF1-A3Apuntes
Apuntes M4

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

<h4>Para hacer un parrafo:</h4>
```Lo podemos hacer poniendo lo siguiente: <p>Esto es un parrafo</p>```

<h4>Para crear un enlace</h4>
[Esto es un enlace](http://joan23.fje.edu "Enlace a la web del cole")

![Esto es una imagen](https://github.com/JavierMartinez05/ASIX1M4UF1-A3Apuntes/blob/main/diagrama.jpg "Titulo opcional de la imagen")

<hr>
<hr>
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
    <table border="1" style="color: red; text-align: center;">
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
</body>