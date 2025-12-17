Presentacion de Proyecto FInal para Ingenieria de Software, del Profesor Marcos Luciano Sosa. A cargo del Alumno ALvez Pedro.

Se implemento un Index.html y un Dockerfile  ( donde definimos el container de nginx a utilziar y su puerto)

En el proyecto se deja la carpeta Imagenes, con los comandos Docker para generar el container e inicializarlo. El git se hizo via update desde Visual Studio Code. 

El proyecto esta en modo publico para el acceso del Profesor.

Como ultimo comentario se deja el comando de docker para poder montar la imagen y ejecutarla:

docker build -t final-ingsoft .
docker run -d -p 8080:80 --name final-ingsoft-container final-ingsoft


