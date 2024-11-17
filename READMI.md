# Pactica de como crear un README.md
## git init ##
El comando **git init** se utiliza para inicializar un nuevo repositorio de Git en un directorio. Esto convierte una carpeta ordinaria en un repositorio de Git, lo que significa que puedes comenzar a rastrear y gestionar los cambios en los archivos de ese directorio con Git.
## git add . ##
El comando **git add .** agrega todos los cambios en el directorio actual (y sus subdirectorios) al _área de preparación de Git_, también conocida como el _staging area_. Esto incluye:
1. Archivos nuevos.
2. Archivos modificados.
3. Archivos eliminados.

## git commit -m "descripcion del commit" ##
El comando **git commit -m "descripcion del commit"** se utiliza para crear un _commit en Git_, es decir, un punto de control que guarda los cambios agregados al área de preparación _(staging area)_ en el historial del repositorio.
La opción **-m** permite agregar un mensaje breve que describe los cambios realizados en ese commit.
## git push ##
El comando **git push** se utiliza para enviar los commits realizados en un repositorio local hacia un repositorio remoto. Es una de las operaciones más comunes en Git y permite compartir los cambios con otros colaboradores o almacenar el código en plataformas como GitHub, GitLab o Bitbucket.
## git pull ##
El comando **git pull** se utiliza para actualizar el repositorio local con los cambios más recientes del repositorio remoto. Es una combinación de dos comandos:

1. git fetch: Descarga los datos y commits más recientes del repositorio remoto.
2. git merge: Fusiona los cambios descargados con la rama activa en el repositorio local.

En resumen, **git pull** sincroniza tu copia local con el repositorio remoto, asegurando que trabajes con la versión más reciente del proyecto.
## git remote -v ##
El comando git **remote -v** muestra una lista de los repositorios remotos asociados a tu repositorio local, junto con las URL correspondientes. Esta información es útil cuando necesitas verificar o modificar las conexiones remotas.
![Git](https://www.google.com/imgres?q=que%20es%20git&imgurl=https%3A%2F%2Fupload.wikimedia.org%2Fwikipedia%2Fcommons%2Fe%2Fe0%2FGit-logo.svg&imgrefurl=https%3A%2F%2Fes.wikipedia.org%2Fwiki%2FGit&docid=dbukdI_kbnsxUM&tbnid=jiWk1wp2CVAo1M&vet=12ahUKEwiU4d_gj-SJAxXZL0QIHcjQFzwQM3oECBAQAA..i&w=800&h=336&hcb=2&ved=2ahUKEwiU4d_gj-SJAxXZL0QIHcjQFzwQM3oECBAQAA)

