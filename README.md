#clase 15
## configuracion inicial (solo se hace una vez)
git config --global user.name ""<--#(# todos ven este nombre)
git config --global user.email "pablojoaquin2560@gmail.com"
git config --get-regexp user <-- (comprueba los git existentes)
#crear un repositorio 
git init
## el estado de los archivos en el repoitorio 
area del repositorio GIT
*working directory(carpeta principal)(WD):directorio de trabajo donde se van  agregando oquitando archivos durante el desarrollo.
*staging area (SA):Area de control de cambio (Area intermedia/temoporal).
*local repo (LR):una caja donde van a estar todas las fotos en el orden que fueron sacadas.

## el estado de los archivos independientes
* untrack:git lo tiene en cuenta pero no le esta haciendo un seguimiento
* unmodify: git esta siguiendo este archivo y el WD no fue modificado
* modified: git esta siguiendo este archivo y el WD Fue modificado (no se actualizo)
* staged: Archivos que estan en el area temporal o intermedia
## saber estado actua de los archivos
git status
git add (nombre del archivo)
git commit -m "mensaje explicativo"
git log(veo la caja de fotos, la info que tengo en el local repo) 
version corta de git log --oneline