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