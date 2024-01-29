# practica_evaluable
En este ejercicio hemos creado un repositorio inicial en el que hemos creado archivos, inicialmente 2 y luego le añadimos uno más, hemos modificado los archivos y después hemos devuelto al estado inicial el documento2.txt. Hemos sincronizado Git con GitHub y hemos estado subiendo los archivos del repositorio local al repositorio remoto, hemos modificado los archivos varias veces los hemos metido al estado de preparación y después hemos realizado un commit seguido de “git push” para subirlos al repositorio remoto. También hemos creado una etiqueta. Hemos creado variar ramas en las que hemos creado o modificado archivos y después las hemos borrado. Hemos clonado el repositorio y hemos trabajado en la copia.
Comandos utilizados:
	-cd documents para acceder a la carpeta
	-mkdir practica_evaluable para crear una carpeta
	-git init para hacer la carpeta repositorio de git
	-echo “crear archivo” > documento1.txt para crear un archivo de texto
	-echo “crear archivo” >> documento1.txt para añadir texto
	-git add . Para pasar el archivo del estado trabajo al preparado
	-git commit -m “comentario” para crear un commit
	-git reset para volver al estado inicial de un commit
	-git log –oneline para ver el historial de los commits
	-git checkout <rama> para cambiar de rama
	-git status para ver es estado de los ficheros
	-git branch <nombre> para crear una rama
	-git branch -d <nombre> para eliminar la rama
	-git branch para ver las ramas actuales
	-ls -la ver los archivos ocultos
	-git push añadir los cambios al repositorio remoto
