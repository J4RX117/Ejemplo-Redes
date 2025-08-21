# Ejemplo-Redes
Uso de aprendizaje de GIT
Paso 1 Crear repositorio en Github

Paso 2 Copiar la direccion HTTPS del repositorio y ejecutar el comando

Paso 3 ingresar correo de github en git para poder realizar modificaciones

$ git config --global user.email correo

git clone direccionhttpsdelrepo
git clone https://github.com/J4RX117/Ejemplo-Redes.git

cd = change directory

Buena practica usar ramas o branch en los repositorios eya que se trabaja de manera conjunta y se garantiza la organización de los proyectos

git branch nombredelarama
git branch nombre

git checkout nombredelarama
git branch nombre

# El comando de abajo agrega todos los archivos a commitear (guardar de manera local)
git add

# Se realiza el commit
git commit -m "Descripciondelcommit"

# Subir cambios en la rama con el comando git push

git push origin nombredelarama
git push origin nombre

# Unificar (fusionar) un branch en GitHub

# Cambiar al branch invitado
git checkout invitado

# Fusionar el branch principal (main) en el branch invitado
git merge main

# Si hay conflictos, resolverlos y hacer commit
git add .
git commit -m "Unificación de cambios desde main a invitado"

# Subir los cambios al repositorio remoto
git push origin invitado

# taller progra web 1