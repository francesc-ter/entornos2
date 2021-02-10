# Practica 3 de Git.

Empezamos entrando en el directorio de la práctica2 (gitpractica2) y a partir de ahí realizaremos esta práctica. Luego creamos la carpeta "unidades" y dentro de ella un fichero llamado windows1.txt.
Entra en el directorio de la práctica2 (practica2git) y a partir de ahí realizaremos esta práctica.

Haciendo un "git status" que se han creado.

<img src="imagenes\1.png">

Añadimos los cambios realizados a la zona de preparado.

<img src="imagenes\2.png">

Hacemos un commit con el comentario "Añadido fichero windows1"

<img src="imagenes\3.png">

Mostramos de nuevo el historial de cambios del repositorio

<img src="imagenes\4.png">

Creamos el fichero "windows2.txt" dentro de "unidades".

<img src="imagenes\5.png">

y añadimos los cambios a la zona de preparado.

<img src="imagenes\6.png">

Hacemos el commit de cambios con el comentario "añadido windows2.txt"

<img src="imagenes\7.png">

Mostramos las diferencias entre los dos últimos commits, para ello usaremos el comado "git log --oneline" para mostrar la id del commit y luego usamos "git dif (id commit)" (sin parentesis).

<img src="imagenes\8.png">

Añadimos al fichero windows2.txt unas lineas.

<img src="imagenes\9.png">

Añadimos los cambios a la zona de preparado y usamos commit de los cambios con el comentario "Añadidas versiones a windows2.txt"

<img src="imagenes\10.png">

Mostramos quien ha hecho cambios en el fichero windows2.txt. Para eso usamos el comando "git annotate (nombre del fichero)".

<img src="imagenes\11.png">
