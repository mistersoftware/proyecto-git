## ¿Qué es Markdown?
Markdown es una herramienta de conversión de texto a HTML para escritores web. Markdown le permite escribir **utilizando un formato de texto sin formato** fácil de leer y escribir, y luego convertirlo en XHTML (o HTML) estructuralmente válido.

Por lo tanto, "Markdown" es dos cosas: 
1.	una sintaxis de formato de texto sin formato; y 
2.	una herramienta de software, escrita en Perl, que convierte el formato de texto sin formato a HTML.

Tomado de [Git-hub]( https://guides.github.com/features/mastering-markdown/) 

Tutoriales

_Nota:_
> _Ojala esta publicación te resulte de utilidad, sin embargo no puedo garantizar que todo funcione correctamente pues este será mi primer tutorial publicado en Platzi. Personalmente prefiero usar Mozila Firefox pero he podido notar que el editor no funciona bien con algunas etiquetas en ese navegador como por ejemplo la de los encabezados y la de Youtube, por ende he realizado esta publicación en Google Chrome donde al parecer si funcionan bien (solo lo sabré al enviar esta publicación). Si sabes de alguna etiqueta que se me haya escapado por favor añádela en los comentarios. Gracias._

## Guía de uso 
## Encabezados
````## Esta es una etiqueta <h2> 
````
Produce:
## Esta es una etiqueta <h2> 
_Corrección:_
> _Después de haber enviado la publicación pude confirmar que la mayoría de etiquetas funcionan excepto las relacionadas a los encabezados, de las cuales solo funciona la etiqueta <h2>._



## Énfasis
````
*Este texto aparecerá en cursiva*
_Este texto también aparecerá en cursiva_
**Este texto aparecerá en negrilla**
__Este texto también aparecerá en negrilla__
~~Este texto aparecerá tachado~~
_También **puedes** combinarlos_
````
_**Producirá**_
*Este texto aparecerá en cursiva*
_Este texto también aparecerá en cursiva_
**Este texto aparecerá en negrilla**
__Este texto también aparecerá en negrilla__
~~Este texto aparecerá tachado~~
_También **puedes** combinarlos_


## Listas Ordenadas
````
1. Ítem 1
1. Ítem 2
1. Ítem 3
   1. Ítem 3a
   1. Ítem 3b
````
_**Producirá**_
1. Ítem 1
1. Ítem 2
1. Ítem 3
   1. Ítem 3a
   1. Ítem 3b

## Listas No ordenadas
````
* Ítem 1
* Ítem 2
  * Ítem 2a
  * Ítem 2b
````
_**Producirá**_
* Ítem 1
* Ítem 2
  * Ítem 2a
  * Ítem 2b
## Imágenes
````
![Platzi logo]( https://static.platzi.com/static/css/logo.a76b2a87162b3b46529c30d1cb91ccc6.png)
````
Producira
![Platzi logo]( https://static.platzi.com/static/css/logo.a76b2a87162b3b46529c30d1cb91ccc6.png)
El formato sigue la siguiente regla: Texto alternativo para la imagen entre corchetes cuadrados precedido por el símbolo de cierre de exclamación, seguido por la url donde se encuentra almacenada la imagen dentro de paréntesis.

## Enlaces
````
http://github.com – enlace creado de forma automática!
[Platzi](http://platzi.com)
````
_**Producirá**_
http://github.com – enlace creado de forma automática!
[Platzi](http://platzi.com)
El formato sigue la siguiente regla: El texto alternativo para el enlace entre corchetes cuadrados seguido de la url dentro de paréntesis. Si deseas que el texto mostrado sea igual al de la url solo debes escribir la url y será convertida automáticamente. 

## Citas
````
Como el famoso filosofo moderno Daddy Yanky dijo:
> Lo que paso
> Paso.
````
_**Producirá**_
Como el famoso filosofo moderno Daddy Yanky dijo:
> Lo que paso
> Paso.

## Resaltado de sintaxis para código
````
\````javascript
function fancyAlert(arg) {
  if(arg) {
    $.facebox({div:'#foo'})
  }
}
\````
````
_**Producirá**_
````javascript
function fancyAlert(arg) {
  if(arg) {
    $.facebox({div:'#foo'})
  }
}
````


## Listas de tareas
````
- [x] Tarea  realizada
- [x] Otra tarea realizada sin ordenar
- [ ] Tarea sin realizar
````
_**Producirá**_
- [x] Tarea  realizada
- [x] Otra tarea realizada sin ordenar
- [ ] Tarea sin realizar

## Tablas
````
Primer Encabezado | Segundo Encabezado
------------ | -------------
Contenido de la columna 1 fila 1 | Contenido de la columna 2 fila 1
Contenido de la columna 1 fila 2 | Contenido de la columna 2 fila 2
Contenido de la columna 1 fila 3 | Contenido de la columna 2 fila 3

````
_**Producirá**_
Primer Encabezado | Segundo Encabezado
------------ | -------------
Contenido de la columna 1 fila 1 | Contenido de la columna 2 fila 1
Contenido de la columna 1 fila 2 | Contenido de la columna 2 fila 2
Contenido de la columna 1 fila 3 | Contenido de la columna 2 fila 3

## Emojis
````
:kissing:
:laughing:
````
_**Producirá**_
:kissing:
:laughing:

Aquí puedes ver un listado completo de [emojis]( https://github.com/ikatyang/emoji-cheatsheet/blob/master/README.md) (no todos están soportados)

## Como escapar caracteres
_si necesitas escapar caracteres puedes hacerlo usando la barra invertida \\
por ejemplo_
````
- [ ] \(Si vas a incluir paréntesis después de corchetes cuadrados) será necesario escapar el primer paréntesis
````
_**Producirá**_
- [ ] \(Si vas a incluir paréntesis después de corchetes cuadrados) será necesario escapar el primer paréntesis
## BONUS: incrustar vídeos de Youtube
````
'@[youtube]( m_lEJyoWafo|https://www.youtube.com/watch?v=m_lEJyoWafo)'
````
_**Producirá**_
@[youtube]( m_lEJyoWafo|https://www.youtube.com/watch?v=m_lEJyoWafo)

Donde el formato es el siguiente @ [youtube] (id del video | url del video). 

_No aseguro que esto última regla de etiquetado funcione y debo añadir que incrustar un video pone lento el editor pues trata de renderizarlo en cada modificación, por ello sugiero que si vas a incrustar un video sea lo último que añadas al redactar tu comentario o tutorial._

