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

Todo esto es un ejemplo para que a la hora de leer, a la gente sea mas facil por tema de que esta mas ordenada la 

## Segundo Capítulo: HTML

HTML es el código que se utiliza para estructurar y desplegar una página web.

Para crear una buena pagina HTML, tiene que estar compuesta de:
<hr>
Un head - donde pondremos informacion sobre la pagina y algunos ajustes
<hr>
Un body - donde irá toda la información que le queramos añadir a nuestra pagina web
<hr>
Antes de empezar a diseñar el body, tenemos que ir al head y poner, html:5, lo cual nos rellenara con lo necesario que tiene que tener el head en un archivo html.
<hr>
En el apartado: ```<title>Documen</title>``` tenemos que poner el titulo que queremos que aparezca en la parte superior del documento (en el buscador aparecerá el nombre que le hemos puesto)
<br>
La etiqueta h1, se usa principalmente para poner los titulos, la cual cerramos con </h1>
<br>
La wtiqueta p, se usa para añadir informacion en forma de parrafo, y lo cerramos asi /p, y todo esto entre <>
<br>
Luego tenemos los enters, hr, que sirve para hacer un enter, metiendo una linea de separacion por en medio
<br>
Ahora vamos con un poco de diseño como strong, que es para remarcar una palabra en negrita, la letra i, que es para poner en cursiva algo, y la u, que es para subrayar alguna información
<hr>
<hr>
LISTAS:
<br>
Las listas las podemos hacer ordenadas o desordenadas:
<br>
ORDENADAS:
<br>
Abrimos con un li, que es la forma en la que decimos que queremos abrir una lista, y si la quieremos desordenada, dentro de la propia etiqueta li, ponemos ol. Dentro de la etiqueta ol, podemos empezar a decir los articulos que contiene la lista
<hr>
DEESORDENADAS:
<br>
Para hacer una lista desordenada hay que seguir los mismos pasos que para hacer una ordenada, salvo que hay que cambiar la etiqueta que metemos dentro del li, suplantando ol, por ul, y seguidamente dentro de la etiqueta ul, podemos comenzar a meter los articulos que queramos dentro de nuestra lista desordenada.
<hr>
<hr>
TABLAS:
<br>

Para empezar a crearuna tabla, primero habra que crear los bordes con: table border="borde1"
<br>
dentro de eso metemos el thead, y dentro metemos el tr, para crear una fila vertical.
<br>
Dentro de esa etiqueta, metemos el th, para crear una fila horizontal.
<br>
Todo estas etiquetas las cerramos como hemos dicho al principio, </"etiqueta que hayamos abierto"
<hr>
Seguimos conn el tbody, y repetimos el proceso con el tr para agregar filas verticales, dentro de ella agregamos td para añadir información.
<hr>
Y acabamos con el tfoot, donde meteremos dentro un tr para filas verticales y un th para filas horizontales.

  
## Tercer capítulo: CSS

El CSS probablemente es de lo mas importante a la hora de crear una pagina web, ya que es lo que le da todo el diseño a nustra pagina web.
<br>
Para hacer funcionar una hoja CSS, tenemos que añadir esta linea en el head: La etiqueta link rel="stylesheet" href="Ruta donde tengamos la hoja CSS" type="text/css
<br>
Esa hoja aparte de CSS su funcion es que no tengamos todo el CSS juntado con el HTML
<br>

***Selector general:**
<br>
Los selectores generales se representan con un *, y significa que seleccionas toda la pagina, esto es util por ejemplo para decidir ka tipografia de letra que quieres que tenga tu pagina web
*{

   font-family: "Nombre de la tipografia que queremos implementar"
}
<br>

**Selectores etiquetas:**
<br>
En este selector, lo usamos para concretar un poco mas, pero no mucho, este selector tiene la misma funcion que el anterior, aunque aplicandoselo a:
<br>
Head
<br>
Body
<br>
h1, h2, h3...
<br>
p
<br>
Aqui tenemos un ejemplo:
<br>
body{
    background-color red    
}
<br>

**Identificadores y clases:**
<br>
Los identificadores, se usan para un elemento el cual es unico en la pagina html, es decir que solo existe ese h2 o ese h5 etc. Los identificadores a la hora de implementarlos son tal que asi, siempre con un #:
<br>
#nombredelID{
    elementos que queramos aplicarle
}
<br>
Por otro lado, las clases, se utilizan para cuando en una misma pagina web, hay varios h2 o varios h5, para seleccionar especificamente cual queremos modificar. A la hora de implementarlas son así, siempre con un . :
<br>
.nombredelaclase{
    elementos que le queramos aplicar
}

**Descendientes y hijos:**

Descendientes: Los descendientes son cualquier elemento que este anidado dentro de otro, dando igual a que profundidad de jerarquía está


ol li{
    elemento que queramos poner
}


Aquí tenemos el ejemplo mas claro, los elementos que esten dentro de ol, se les aplicará lo que le queramos poner.

Hijos: Los hijos, son aquel elemento que esta anidado directamente a otro elemento superior


p > strong{
    elemento que queramos poner
}

Aqui vemos que tenemos > esta flecha que indica que se le aplicará a todos los strong.

**Dentro de archivo HTML**

Si que es verdad que tambien podemos poner todo esto, dentro del archivo HTML, pero con algunas condiciones, y es que los ID, clases y * deben ir dentro del Head 
<br>
De igual manera que colores, formato de texto, y colores de background, va todo dentro de la misma etiqueta


## Cuarto Capitulo: DISEÑO RESPONSIVE

Aqui tambien implementamos CSS, aunque aqui es mas para poner medidas, ocultar elementos...
<br>
El diseño responsive, es mucho mas util de lo que parece, ya que hace que no importe desde donde ves la pagina web, ya que te ajusta automaticamente las medidas y la resolución. Cabe destacar, que en Diseño responsive, el uso de etiquetas como section y como div, es bastante frecuente.
<br>
También es bastante frecuente usar comandos, como los que te voy a mostrar a continuación:

**FLOAT**
<br>
Este comando, se usa para alinear el elemento hacia la derecha o hacia la izquierda, obviamente sin modificar lo de alrededor, es decir que se ajusta automaticamente:

#right{
    float: right;
}

**DISPLAY**
<br>
Este comando podemos decir que "transforma" los DIV en celdas:

.flex{
    display: flex;
}

**BOX-SIZING**
<br>
Este comando se usa para modificar tanto borde y ancho y ajusta la medida al tamaño del contenido de la pagina:

*{
    box-sizing: border-box;     
}

**FLEX-DIRECTION**
<br>
Comando bastante util, y esque su funcionalidad es que mueve los elementos de la pagina, en base hacia donde movamos nosotros la pantalla

.box {
  display: flex;
  flex-direction: column;
}

**ALIGN**
<br>
Como podemos tener en aplicaciones como Word, aqui también tenemos, y es el:

.flex{
    align-items: center;
}

Su principal funcion, es alinear los elementos a donde tu le pidas

**JUSTIFY-CONTENT**
<br>
Otro comando que nos podemos encontrar en Word, y nada diferente, sirve para justificar el contenido de la pagina web, poniendole un start, es para que lo justifique al borde inicial:

.box{
    justify-content: start;
}

**IMAGENES**
<br>
Esta parte es importante si queremos que las imagenes se ajusten automaticamente al ancho de la pagina y decirle que altura queremos que tenga:

header{
    height: 100vh;
    background-image: url(ruta donde tenemos al imagen);
    background-size: cover;
    background-position: center;
    background-attachment: fixed;
}

El background image, como su nombre dice, es para poner una imagen de fondo.
<br>
El background size cover, es para que la imagen de fondo de ajuste automaticamente al tamaño
<br>
El background position center tambien como su propio nombre indica, es para que el fondo esté centrado al contenedor
<br>
El background attachment fixed, significa que la imagen de fondo, se queda fijada en la posicion, haciendo que por mas que nos movamos, el fondo se quedará fijo en su puesto
<hr>
ESTOS SON LOS APUNTES DE JAVIER MARTINEZ CESPEDES