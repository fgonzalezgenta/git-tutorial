# Git

## ¿Qué es git?

Git es un software de control de versiones. De VERSIONES

## ¿Qué es github?

Github es un servicio web que aloja código y trabaja con git.

## git init

Este comando permite inicial el seguimiento de git en un repositorio determinadoSSS23

## git clone

Clona un repositorio remoto (que vive por ej github) de manera local

## git status

Describe el estado del repositorio actual, cambios a agregar, cambios agregados a commitear y commits a pushear si los hubiere. Además especifica información como la branch actual.

## git add2

Agrega los cambios realizados en archivos/directorios del proyecto para formar parte del potencial próximo commit

## git commit

Crea un hito o punto de control con todos los cambios agregados desde el último commit, permite añadirle un mensaje descriptivo.

### good commits messages

* Captitalizados
* En inglés
* En infinitivo
* En presente simple

ej: "Add goof commits messages tips"

## git log

Muestra el historial de commits del repositorio y branch actuales, el hash de cada uno, así como fecha y hora, autor y mensaje.

## git checkout

Permite desplazarse entre ramas git checkout nombre-de-la-rama así como crear nuevas ramas git checkout -b "nombre-de-la-rama"

## git push

Publica los commits locales en un repositorio remoto (ej github)

## git pull

Actualiza el repositorio local con los commits publicados en el repositorio remoto y que sean faltantes.

## git merge

Permite mezclar o unir la rama de trabajo actual con una especificada.

## .gitignore

Es un archivo que permite especificar todos aquellos archivos y directorios que no son necesarios seguir, agregar, commitear ni pushear.

Ej: 
*.pyc
tmp

## Tutorial interactivo

[learngitbranching](https://learngitbranching.js.org/)
