# Tatooine-HDH
## Introducción a GIT

#### Palabras Clave
* Local: Los archivos locales que están alojados en el equipo en uso.
* Remote: Servidor remoto de git.
* Init: Crea un nuevo repositorio de git.
* Clone: Copia el repositorio git a un directorio local.
* Add: Mueve los archivos hacia el estado staged.
* Commit: Mueve los archivos de staged a committed y abre una ventana para insertar un comentario.
* Push: Mueve los archivos del directorio local hacia el servidor git y abre un pull request.
* Pull: Solicita los archivos del servidor git y los mueve hacia al directorio local.
* Merge: Une los archivos, de distintas ramas o la misma, en uno solo a sus respectivos archivos.

#### Fases de GIT
1. Untracked: No existe registro o seguimiento de los archivos.
2. Tracked: Ya existe un seguimiento de los archivos.
3. Modified: El archivo está siendo o ya fue modificado.
4. Staged: El archivo ya fue añadido para hacer un commit.
5. Committed: El archivo ya fue respaldado.

##### ¿Qué cosas **NO** se deben hacer en un repositorio de GIT?
* Hacer push hacia master.
* No usar *checkout* para ir a cada rama.
* No comentar los push.
* No borrar las ramas después de trabajar en ellas.

##### ¿A qué año debía volver Marty McFly para restablecer la línea del tiempo?
Al año 1955.

##### Extras:
* Diff: Compara la rama actual con la indicada [git diff *branch*].
