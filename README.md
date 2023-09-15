-Como subir un proyecto local a github.
desde la web de github
Creamos un nuevo repositorio en https://github.com. Le damos nombre, descripción, seleccionamos si va a ser un proyecto publico o privado si es el caso, y dejamos el check de crear README sin marcar. Le damos a crear repositorio y con esto ya tenemos el repositorio donde alojaremos nuestro proyecto.

-Desde la terminal del equipo donde esta el proyecto que queremos subir a github
-Nos vamos a la carpeta del proyecto y ejecutamos estos comandos.

![Imagen de WhatsApp 2023-09-05 a las 13 05 46](https://github.com/DavidProgramer404/como-subir-tu-repositorio-github/assets/100321757/093c4717-6855-4af4-91b6-680402a261e5)


-git init

-git add .

-git commit -m "first commit"

-git remote add origin https://github.com/NOMBRE_USUARIO/NOMBRE_PROYECTO.git

-git push -u origin master
