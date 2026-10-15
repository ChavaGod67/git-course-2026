# Notas
## git branch 
 git branch nos permite crear nuevas ramas para probar cambios o funciones que puedan alterar el comportamiento del codigo
- git branch : Enlistado de todas las ramas
- git branch : "rama" Crea una rama nueva
- git branch : -D "rama" Elimina la rama seleccionada

## checkout 
sirve para movernos entre branchs y commits
- git switch "rama" : cambiar de rama

## git push
Por default git pus sube los cambios de nuestro upstream branch la cual es la branch default para sincronizar cambios.
sube los cambios al repositorio en la nube
- git push <remote> <branch> : Sube cambios de nuestro branch al servidor

## git add
- git add . : Añadir todo los archivos cambiados a staging. Incluyendo archivos nuevos
- git add -u : Añade solo los archivos cambiados al area de staging (Ignora archivos nuevos que no esten subidos)
- git add 

## git commit
Guarda los cambios del staging area
- git commit -m "comentario" : Hace un commit y anexa un comentario
- git commit -am "comentario" : es el equivalente a:
    ...bash
    git add -u
    git commit -m "comentario"
    ...