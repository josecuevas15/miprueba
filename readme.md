# Labotatorio GIT

## 1. Crear un repositorio local 
Primero creo la carpeta llamada **MIPRUEBA**, y accedo a ella.

A continuacion, abro una terminal y, tras instalar las dependencias con `npm install`, inicializo el repositorio con `git init`.

## 2. Subir el repositorio a GitHub 
Para ello creo un nuevo repositorio en mi cuenta de github. Lo he llamado [miprueba](https://github.com/josecuevas15/miprueba).

Seguidamente, en la terminal de visual, usando `git remote add origin git@github.com:josecuevas15/miprueba.git` enlazamos el repositorio local al repositorio en github.

## 3. Hacer un commit y un push
Hacemos `git add .` para aniadir los archivos al staging. Seguidamente, usando `git commit -m "Commit inicial"` creamos el commit con su mensaje.

Finalmente, hacemos `git push -u origin master` especificando asi la rama local y el repositorio remoto al que queremos hacer el push.

4. Crear una rama
