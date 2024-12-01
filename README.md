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
!(avance)[https://i.imgur.com/h0mFmD0.png]