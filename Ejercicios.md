# Ejercicios Emmet

## Ejercicio 1
Cuál es el código emmet para generar la siguiente estructura?
~~~
<ul>
<li></li>
<li></li>
<li></li>
</ul>
~~~
<b><b>Respuesta</b></b>:
~~~
ul>li*3
~~~

## Ejercicio 2
Cuál es el código emmet para generar una tabla con 10 filas y 2 columnas?<br>
<b><b>Respuesta</b></b>:
~~~
table>tr*10>td*2
~~~

## Ejercicio 3
Cuál es el código emmet para generar la siguiente estructura?
~~~
<h1 class="text text-titulo">Ola mundo</h1>
~~~
<b><b>Respuesta</b></b>:
~~~
h1.text.text-titulo{Ola mundo}
~~~

## Ejercicio 4
Cuál es el código emmet para generar la siguiente estructura?
~~~
<div>
<p>datos</p>
<p>datos</p>
</div>
~~~
<b><b>Respuesta</b></b>:
~~~
 div>p*2{datos}
~~~

## Ejercicio 5
Cuál es el código emmet para generar la siguiente estructura?
~~~
<div></div>
<p>
<span></span>
</p>
<p>
<span></span>
</p>
<p>
<span></span>
</p>
<p>
<span></span>
</p>
~~~
<b><b>Respuesta</b></b>:
~~~
div+p*4>span
~~~

## Ejercicio 6
Cuál es el código emmet para generar la siguiente estructura?
~~~
<div id="hola" class="principal">
<p>
<section id="seccion" class="seccion">
<h1>Ola mundo!</h1>
</section>
</p>
</div>
~~~
<b><b>Respuesta</b></b>:
~~~
div#hola.principal>p>section#seccion.seccion>h1{Ola mundo!}
~~~

## Ejercicio 7
Cuál es el código emmet para generar la siguiente estructura?
~~~
<ol>fora
<li>dentro</li>
<li>dentro</li>
<li>dentro</li>
<li>dentro</li>
</ol>
~~~
<b><b>Respuesta</b></b>:
~~~
ol>li*4{dentro}
~~~

## Ejercicio 8
Cuál es el código emmet para generar la siguiente estructura?
~~~
<p></p>
<div></div>
<p>
<div>
<div>
</div>
</div>
</p>
~~~
<b><b>Respuesta</b></b>:
~~~
p+div+p>div>div
~~~

## Ejercicio 9
Cuál es el código emmet para generar la siguiente estructura?
~~~
<nav class="menu">
<a href="">enlace1</a>
<a href="">enlace2</a>
<a href="">enlace3</a>
<a href="">enlace4</a>
</nav>
~~~
<b><b>Respuesta</b></b>:
~~~
nav.menu>a*4{enlace$}
~~~

## Ejercicio 10
Cuál es el código emmet para generar la siguiente estructura?
~~~
<ul class="lista">
<li class="item-1">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ea, voluptatibus!</li>
<li class="item-2">Eaque, impedit est tempora doloremque praesentium voluptatum quas nostrum consectetur.</li>
<li class="item-3">Illum, reprehenderit minus ex soluta adipisci aperiam explicabo modi sapiente.</li>
<li class="item-4">Nihil ratione voluptates iure cum eligendi dolores deleniti quos nostrum.</li>
</ul>
~~~
<b><b>Respuesta</b></b>:
~~~
ul.lista>li.item-$*4>lorem10
~~~