# Clon de starbucks

esta es una página que tiene como objetivo replicar la página oficial de [starbucks](https://www.starbucks.com.mx) usando css

puede que la página se vea mal en pantallas muy diferentes a la mía, ya que no está hecha con un diseño web responsivo, es por eso que dejo capturas de pantalla de como se ven en mi pantalla ambas páginas

## mi página:
![vista previa](https://i.imgur.com/Q9UQhdA.png)

## página original:
![vista previa](https://i.imgur.com/mawr6II.png)

también incluyo capturas de partes del código

## html
![vista previa](https://i.imgur.com/5A4sLhI.png)

## css
![vista previa](https://i.imgur.com/zIeinvA.png)


# entregable 4
a partir de este entregable comencé a construir la página de rewards, comentaré los commits que haga a partir de este momento

## commit "well arranged"
en este commit finalmente logré organizar las 2 secciones principales para que dividan la pantalla, a la izquierda le puse "position: fixed;" aregué algunos elementos para rellenar.
al agregar la imagen de la mano usé un justify-self y align-self con valor flex-end, pero la imagen flotaba un poco antes de llegar al final de la pagina, así que usé un position:relative; con top:10vh; y se puso al final

## commit "inner content arranged"
al intentar acomodar el contenido de dentro de los contenedores toda la pagina se deshizo, mas que nada por querer arreglar el alto del contenedor fixed y establecer el header como fixed, y al tener tantos problemas con el header, lo cambié por sticky y se arregló, solo falta ver que siga funcionando cuando se haga scroll
![avance](https://i.imgur.com/ffvAj7B.png)

## commit "rewards page finished" (entregable)
este es el ultimo commit para el entregable 4, donde he concluido la construccion de la página de rewards.
esta pagina tuvo 1 detalle, en mitad de la página origianl, hay una lista de elementos con su propio estilo de numerado, quise replicarlo pero aunque intenté con bastantes metodos como ::marker, ::after etc. no logré que ni siquiera los números se observaran, la verdad no comprendo que fue lo que paso con eso así que tuve que dejarlo asi.

### mi pagina:
![avance](https://i.imgur.com/JtwsuSQ.png)

### pagina original:
![avance](https://i.imgur.com/XY8xQtW.png)

### vista previa css
![css](https://i.imgur.com/vRjeRTo.png)

# entregable 5
a partir de aqui comienzo a hacer la página de menu, que relamente fue muy facil, mas de lo que esperaba
dividi la pagina en una seccion la cual contiene subsecciones que a su vez, contienen items del menu.
todos estos elementos fueron acomodados con flexbox, que fue de mucha ayuda y de adapta decentemente a los tamaños de pantalla gracias a que usé solamente unidades relativas.

## commit "menu added"
este es el primer y único commit para este entregable, osea que hacer esta página solo me llevo un commit.

### mi pagina:
![mipagina](https://i.imgur.com/bRkaOMT.png)

### pagina original:
![pagoriginal](https://i.imgur.com/U3aiT9H.png)

### css:
![codepreview](https://i.imgur.com/pyjESG2.png)

## commit "pages update forcing"
despues de hacer el commit anterior me di cuenta que no habia agregado la href hacia la pagina de menu desde el index, asi que la agregué e hice un commit pero parece no haberse subido al pages aunque si se actualizó en github, es por eso que estoy haciendo otro commit sin cambios en el código realmente, esperando que se arregle

## commit "footer fixed"
se arregló la href, pero me di cuenta que el footer estaba dentro de una seccion a la que no pertenecia, vi el codigo y todo se veia bien hasta que me di cuenta que me falto una etiqueda de cierre de un section y por eso la pagina lo interpretaba dentro de esa section, asi que en este commit arreglo ese error.

## commit "pages forcing again"
de nuevo no se subio el cambio a pages pero a github si, tuve que hacer otro commit de nuevo

# entregable 6
aqui es donde comienzo a adaptar las paginas a un estilo portrait y hacerlas responsivas con media queries

## commit "responsive index done"
en este commit finalicé la adaptación a dispositivos móviles de la página index.
usando media queries cambie algunos estilos de algunos elementos, por ejemplo, oculté ciertos elementos usando display: none; o hice aparecer algunos otros que no se veían por tener esa propiedad. cambié algunas mediciones que estaban en pixeles y las cambie por unidades de medida relativas como porcentaje o vw y vh. también cambie algunas horientaciones como flex direction column a row o viceversa.

### mi pagina:
![mipag](https://i.imgur.com/2vWAVtE.png)

### pagina original:
![pagoriginal](https://i.imgur.com/7DT41l1.png)

### css:
![css](https://i.imgur.com/oGW7Z1U.png)


## commit "responsive rewards done"
aqui ya termine la pagina de rewards para moviles, esta si fue bastante dificil ya que por haber puesto tantos css inline, tuve muchos problemas para cambiar varios estilos, asi que me costo mucho terminar esta pagina pero fue culpa mia por no haberla hecho bien desde un principio.
al convertir una pagina a moviles es muy notable el cambio de flex-direction row a column en la mayoria de contenedores.

### mi pagina:
![mipag](https://i.imgur.com/89jpbL1.png)

### pagina original
![pagoriginal](https://i.imgur.com/9eMtIRg.png)

### css ;-; :
![css](https://i.imgur.com/arMxvaU.png)


## commit "responsive menu done" (final para esta entrega)
aqui por fin termine las 3 paginas responsivas, la ultima pagina de menu fue bastante facil de convertir como pensé, porque cuando la hice siento que la organice de una forma muy logica y use puras unidades de medida relativas, nada de pixeles ni cosas absolutas, entonces fue muy facil que la pagina se adaptara a la pantalla, los unicos ajustes que hice fueron cambiar algunos widths y heights y tamaños de fuente.

### mi pagina:
![mipag](https://i.imgur.com/77I2kKh.png)

### pagina original:
![pagoriginal](https://i.imgur.com/jRD33TD.png)

### css:
este css fue una cosita de nada, solo 30 lineas, lo que me pone muy contento porque me doy cuenta de lo que mejoré a comparacion de las otras 2 paginas que no las hice tan responsivas desde un principio
![css](https://i.imgur.com/yXN09oL.png)

## disclaimer!!
al entrar en una vista de telefono las opciones de la navbar desaparecen y se van a un "menu lateral" que realmente no funciona porque no se hacerlo, asi que para navegar entre paginas habria que quitar la emulacion de la vista, cambiar de pagina y volver a activarla ya estando en la otra pagina.



# entregable 7

## commit "login page added"
aqui agrego la pagina de login ya terminada, no fue muy dificil hacerla pero si me lleve un ratillo, falta hacerla responsiva para moviles

### mi pagina:
![mipag](https://i.imgur.com/c0rb42P.png)

### pagina original:
![pagoriginal](https://i.imgur.com/Cn5wLw3.png)

### css:
![css](https://i.imgur.com/uC3FNDo.png)


## commit "readme update"
en el commit anterior se me olvido hacerle add a lo que agregue en el readme asi que este commit es solo para eso

## commit "readme update again !!"
otra vez se me olvido agregar lo del commit anterior xddd

## commit "login linked"
ahora se me olvido linkear la pagina de login en todas las demas en el header asi que en este commit es lo unico q agrego


## commit "responsive login page done"
en este commit agrego la media query para la pagina de login en  movil que fue muy sencillo de hacer, me llevo tal vez alrededor de media hora y no tuve que escribir mucho codigo, la verdad siento que he mejorado mucho en hacer las paginas para que sean adaptativas y que no me cueste cambiarlas en media queries, solo tuve que hacer algunos cambios de tamaño en imagenes, tamaños de fuente y distribucion de contenedores y ya quedó

### mi pagina
![mipag](https://i.imgur.com/fpVKkbG.png)

### pagina original
![vnjeusn](https://i.imgur.com/8n8XGL3.png)

### css:
![css](https://i.imgur.com/KZc8si2.png)


![yo](https://i.imgur.com/QK7hmqa.jpeg)
![yoagain](https://images-ext-1.discordapp.net/external/VhGyqtaXFNshw55Q4p2Bx-4zq0ZNyDr8hlaBeCZ1lfk/https/media.tenor.com/images/eb707bb9c16cce278309b806437de097/tenor.gif?width=92&height=112)