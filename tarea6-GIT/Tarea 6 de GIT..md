# Tarea 6 de GIT.

En primer lugar creaos un fichero test.java con la clase test como sigue:

<img src=imagenes\1.png> 

Pasamos a preparado el fichero.

<img src=imagenes\2.png> 

Creamos el fichero Principal.java

<img src=imagenes\3.png> 

Pasamos a preparado el fichero y hacemos un commit con el comentario “Inicial clases test y principal”.

<img src=imagenes\4.png> 

<img src=imagenes\5.png> 

Comprobamos la salida del programa. (debéis compilar los .java y probar el Principal)

<img src=imagenes\6.png> 

Modificamos el fichero test eliminando el método toString().

<img src=imagenes\7.png> 

Pasamos a preparado el fichero y realizamos un segundo commit “Eliminada ToString()”.

<img src=imagenes\8.png>

<img src=imagenes\9.png>

Comprobamos de nuevo la salida del programa.

<img src=imagenes\10.png>

Volvemos atrás viendo los “log” y haciendo “checkout” necesarios para que la salida del programa sea la
del paso 6.

<img src=imagenes\11.png>

<img src=imagenes\12.png>

¿Qué creéis que hace el método toString? 

Pues combia todas las variales a string para mostrarlas por pantalla.

¿Qué
conseguimos con el @Override?

Simplemente se utiliza, para forzar al compilador a comprobar en tiempo de compilación que estás sobrescribiendo correctamente un método, y de este modo evitar errores en tiempo de ejecución, los cuales serían mucho más difíciles de detectar.
