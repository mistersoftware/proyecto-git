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

Como se puede ver, solo funciona la etiqueta de encabezados <h2>, las correspondientes a <h1> <h3> <h4> <h5> y <h6> no son interpretadas de igual manera. Me gustaría editar la publicación pero no es posible y considero que reenviarla seria tomado como spam así que la dejare como esta.

¿Qué temas te gustaría que fueran tratados en este curso?

Empieza hoy a desarrollar tecnología de punta con IBM Watson (Sigue estos pasos para crear tu cuenta y obtén un bono de 1200 USD para consumir en IBM Cloud)



Empieza hoy a desarrollar tecnología de punta con IBM Watson (Sigue estos pasos para crear tu cuenta y obtén un bono de 1200 USD para consumir en IBM Cloud)


Hola amigo, bienvenido a mi primer tutorial de inteligencia artificial. Mi nombre es Luis Carlos, y me gustaría compartir contigo algunos temas relacionados a este maravilloso campo de investigación ~~mal~~ conocido como inteligencia artificial (ciencia de datos).
Antes de empezar, te informo que IBM está invirtiendo miles de millones de dólares actualmente para impulsar la adopción de estas nuevas tecnologías. Como puedes ver, aquí en platzi el curso es gratuito y de igual manera están apoyando diferentes iniciativas académicas para facilitar el aprendizaje por parte de la gente común como tú y como yo. Ellos lo llaman, la democratización de los servicios cognitivos, lo que se traduce en la oportunidad para que personas autónomas e independientes puedan desarrollar soluciones sin tener que pertenecer a una empresa gigante. 
Sin embargo, algo que aprenderás a medida que vayas avanzando en este campo de estudio, es que la línea de aprendizaje puede verse cortada en el momento en que no cuentes con el dinero necesario para pagar por el consumo de los servicios cognitivos. 
Por esta razón durante un tiempo me dedique a buscar cupones, descuentos, bonos y todo lo relacionado para financiar mi investigación. Fue en ese momento cuando encontré una página llamada [cognitive class]( https://cognitiveclass.ai/) donde he encontrado un complemento ideal que junto con platzi me han permitido avanzar mucho en mi aprendizaje.
En este punto debo resaltar que no tengo ninguna relación contractual con dicha pagina, es decir que no gano nada al invitarte a que te registres allí, simplemente te informo que si te registras siguiendo los siguientes pasos, recibirás un bono de consumo por un valor de 1200 US para ser consumidos en la nube de IBM.
¿Por qué lo comparto? Pues la respuesta más simple es: ¿Y porque no? No me cuesta nada, y entre más personas aprendamos de estos temas, podremos realizar proyectos más interesantes, y he de confesarte que en el tiempo que llevo estudiando esto, siempre me he sentido muy _forever alone_ pues hay mucho _postureo_ por ahí en el mercado, pero personas con quienes debatir y de quienes aprender de estos temas muy pocas (o ninguna).
Entonces, si ha quedado clara mi declaración de intención, pongámonos manos a la obra. Sigue los pasos que te indicare a continuación y así tendrás todo lo necesario para continuar con los tutoriales que publicare después y para sacar el máximo provecha de las clases aquí en platzi. ¡Comencemos!
## Paso 0
**Crear tu cuenta en platzi.**
>Esto debería ser obvio pero si no lo has hecho, ¿qué esperas? Es gratuito.
## Paso 1
**Crear tu cuenta en [IBM Cloud]( https://cocl.us/CC_SIGNUP_IBM_PROMO)  haciendo click en el enlace anterior.** No olvides ir a tu correo electrónico y activar tu cuenta haciendo click en el enlace que te enviaran. __Nota: solo realiza el registro, si ves un código promocional por 200US no lo tomes pues solo es válido un código promocional por cuenta, y si aplicas a esa promoción no podrás aprovechar el bono de 1200US del que trata este tutorial). Simplemente crea la cuenta y vuelve aquí para continuar con los demás pasos. En la configuración de tu cuenta deberá decir que tu cuenta es **LITE Gratuita** para que los siguientes pasos funcionen sin problemas.__
![ Paso 1 Crear tu cuenta en IBM Cloud](https://mrsoftware.work/tutoriales/bono1200/01-Registrese-en-IBM-Cloud.jpg)


## Paso2
**Crear tu cuenta en [cognitive class](https://courses.cognitiveclass.ai/register) haciendo click en el enlace anterior.** No olvides ir a tu correo electrónico y activar tu cuenta haciendo click en el enlace que te enviaran.
![ Paso 2 Crear tu cuenta en cognitive class](https://mrsoftware.work/tutoriales/bono1200/02-Registrese-en-Cognitive-class.jpg)


## Paso 3
**Regístrate en un curso.** Después de activar tu cuenta, deberás elegir un curso cualquiera para que sea generado tu código promocional.
![ Paso 3 Regístrate en un curso](https://mrsoftware.work/tutoriales/bono1200/03-inscribete-en-un-curso.jpg)


**Paso 3ª**
**Elige el curso**
![ Paso 3a Regístrate en un curso](https://mrsoftware.work/tutoriales/bono1200/03a-inscribete-en-un-curso.jpg)



## Paso 4
**Indica que no eres un robot.**
![ Paso 4 Indica que no eres un robot](https://mrsoftware.work/tutoriales/bono1200/04-indica-que-no-eres-un-robot.jpg)


## Paso 5
**Copia tu código promocional desde cognitive class.** Una vez hayas copiado el código dirígete a la nube de IBM donde ya has creado y activado tu cuenta.
![ Paso 5 Copia tu código promocional](https://mrsoftware.work/tutoriales/bono1200/ 05-copia-y-pega-tu-codigo.jpg)

## Paso 6
**Pega tu código promocional en IBM Cloud.** Para hacerlo deberas ir al [panel de control](https://cloud.ibm.com/)  allí deberas hacer click donde dice **Gestionar**, luego donde dice **Cuenta** y en la ventana nueva en el menu lateral izquierdo elegir **Configuración de la cuenta** y una vez allí, desplazarte hasta donde dice **Códigos de características (Promocionales) ** y hacer click donde dice **Aplicar código**
![ Paso 6 Pega tu código promocional](https://mrsoftware.work/tutoriales/bono1200/06-copia-y-pega-tu-codigo.jpg)
![ Paso 6b Pega tu código promocional](https://mrsoftware.work/tutoriales/bono1200/06b-copia-y-pega-tu-codigo.jpg)
![ Paso 6b Pega tu código promocional](https://mrsoftware.work/tutoriales/bono1200/06c-copia-y-pega-tu-codigo.jpg)

## Terminamos
¿Preguntas o comentarios? Déjalos en el sistema de discusiones. Feliz resto de día. 

Platzi es una de las soluciones que encontré, pues es un sitio en español donde puedes aprender gratuitamente todo lo necesario para iniciarte en este mundo, y luego cuando deseas profundizar mas, con una suscripción muy económica puedes hacerlo. 


Teniendo en cuenta que cualquier tipo de imagen digital es en últimas una cadena de unos y ceros, ósea nada más y nada menos que un simple numero, no hay razón para pensar que el tipo de archivo implique un obstáculo para un análisis desde la perspectiva de la ciencia de datos. 
Pregúntate que es lo que esperas obtener de dicho análisis y dale una ojeada a lo siguiente, puede que te sirva como un punto de partida en tu investigación.
[Fast-track Geospatial AI Applications with Watson Data Platform and Esri ArcGIS](https://medium.com/ibm-data-science-experience/fast-track-geospatial-ai-applications-with-ibm-data-science-experience-and-esri-arcgis-a1bd86392e1c) 

@[youtube](ooOYMFKkuxw|https://www.youtube.com/watch?v=ooOYMFKkuxw)

@[youtube](fk49hw4OrN4|https://www.youtube.com/watch?v=fk49hw4OrN4)


