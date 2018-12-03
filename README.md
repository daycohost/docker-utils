# jteran3/docker

Docker utils

### docker-container-backup.sh

* ./docker-container-backup.sh "<empty>" <-- Respaldo de todos los contenedores
* ./docker-container-backup.sh "<container-name>" <-- Respaldo de un contenedor

### docker-container-restore.sh

* Restaura contenedor desde el archivo .tar de la imagen respaldada (snapshot) del contenedor

### docker-image-backup.sh

* ./docker-image-backup.sh <empty> <-- Respaldo de todas las imagenes
* ./docker-image-backup.sh <stack-name> <-- Respaldo de las imagenes de una stack

### docker-stack-backup.sh

* ./docker-stack-backup.sh <stack-name> <-- Respaldo de todos los contenedores de la stack

### docker-stack-restore.sh

* Restaura el directorio de la stack y los archivos .tar de las imagenes respaldadas (snapshot) de los contenedores
