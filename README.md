# Este es el primer proyecto del curso.

## Creación de repo:
git init

## Añadir el fichero
git add <nombre_fichero>    # Añadir un fichero
git add *                   # Añadir todos los ficheros del directorio (los ocultos no)
git add .                   # Añadir todos los ficheros del directorio (los ocultos también)
Empezar a controlar el fichero.
Pasa el fichero al área de STAGING.
GIT solo guarda ficheros 

# OBJETOS EN GIT
## WORKSPACE:
Carpeta en la que está el proyecto.
## REPO:
Carpeta .git
## STAGING:
Fichero dentro de la carpeta .git que anota los cambios que se mandan al repo desde el área de staging.

## Información del estado del proyecto
git status

## Commit
Paquete de cambios que se registra en el repo
<< Paquete de cambios >> unidad mínima en git

## Sacar un fichero del área de staging
git rm --cached <nombre_fichero>

## Borra fichero del workspace y en el STAGING para el próximo paquete de cambios se elimine.
git rm <nombre_fichero>