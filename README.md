# damuse-avf.github.io


My website by damuse


Cuando descargamos el repo haciendo un git clone, no olvidar descargar el submodule (el tema)
* git submodule update --init --recursive
* cd themes/blist/
* npm install

Iniciar el servidor de desarrollo
* hugo serve -D

Prepara archivos para publicar
* hugo -D -d docs

Subir cambio al repositorio
* git push origin main
