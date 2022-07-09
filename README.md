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

# Comandos utiles GIT

Restaurar cambios hasta el ultimo commit subido al servidor
* git checkout .

Descargar utimos cambios desde el servidor remoto (Github)
* git pull origin main

Revisar mis ramas locales
* git branch

Eliminar una rama (con force)
* git branch -D

Como agregar un archivo para subir
* git add <nombre_archivo>

Agregar todos los archivos para subir
* git add .

Como hacer un comentario a los cambios por subir
* git commit -m "mi mensaje"

# Notas aparte

Cuando creas un repo "git init" aveces debes agregar el servidor remoto
* git remote add origin https://github.com/damuse-avf....

Copiamos la ruta desde el boton verde

