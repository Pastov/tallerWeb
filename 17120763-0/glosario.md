##### 17.120.763-0

- a.- Control de versiones:

  Es un sistema que permite registrar los cambios realizados en un archivo dentro de un repositorio,  
  el cual permite recuperar versiones anteriores del mismo en caso de errores al pushear en una rama.

  Fuente: https://git-scm.com/book/es/v1/Empezando-Acerca-del-control-de-versiones

- b.- Control de versions distribuido:

  Tiene la misma finalidad que el control de versiones pero con la diferencia que, en vez de ser solo de cliente a servidor, permite la interaccion peer to peer, por lo que muchos clientes pueden manipular un repositorio a la vez.

  Fuente: https://es.wikipedia.org/wiki/Control_de_versiones_distribuido

- c.- Repositorio local y remoto:

  El repositorio remoto es una version del proyecto que se encuentran alojados en la red. Se pueden tener varias copias de este con diferentes niveles de seguridad(solo lectura, lectura y escritura, etc...), este version ademas puede ser modificada por varios participantes en el repositorio siempre con el nivel de seguridad adecuado y revision de los cambios hechos.

  Por otro lado, el repositorio remoto es la version que el usuario maneja en su computador y la cual modificada de acuerdo al trabajo que necesite realizar. Para que este repositorio local pase a ser parte de un repositorio remoto se deben añadir los cambios, "commitear" lo que se ha cambiado y finalmente pushear a la rama en la cual se este trabajando. Si se desean bajar cambios nuevos realizados en un repositorio remoto a una local, se debe hacer "pull"

  Fuente: https://git-scm.com/book/es/v1/Fundamentos-de-Git-Trabajando-con-repositorios-remotos

- d.- Copia de trabajo:

  Es la copia local de los archivos locales en un repositorio, bajo un momento o revision especificos

  Fuente: https://es.wikipedia.org/wiki/Control_de_versiones

- e.- Area de preparacion:

  Es un archivo dentro del directorio de git, el cual contiene la informacion sobre lo que ira en la proxima confirmacion. Tambien suele llamarse indice.

  Fuente: https://git-scm.com/book/es/v1/Empezando-Fundamentos-de-Git

- f.- Preparar cambios:

  Es un paso antes de "commitear" en git. Mientras todo el "changeSet" este en el area de preparacion, se podran realizar cambios
  que se estimen convenientes.

  Fuente: https://softwareengineering.stackexchange.com/questions/119782/what-does-stage-mean-in-git

- g.- Confirmar Cambios:

  Es el commit realizado sobre los cambios hechos en el repositorio local. Se hace este para los archivos agregados mediante "git add", que son los que recibieron alguna modificacion y reflejan lo descrito en el commit.

  Fuente: https://www.git-tower.com/learn/git/commands/git-commit

 - h.-commit:

  Este comando sirve para cambiar a la cabecera. Agregando "-m" se pueden agregar comentarios que pueden reflejar los cambios hechos en el repositorio local.

  Fuente: https://www.hostinger.es/tutoriales/comandos-de-git

 - i.- clone:

  Este comando se usa para "targetear" un repositorio existente y clonarlo. La ventaja de este comando es que crea un repositorio con una conexion remota llamada "origin", la cual permite tener una facil interaccion con el repostorio original.

  Fuente: https://www.atlassian.com/git/tutorials/setting-up-a-repository/git-clone

- j.- pull:

  Incorpora los cambios hechos en un repositorio remoto en la rama actual.

  Fuente: https://git-scm.com/docs/git-pull

- k.- push:

  Este comando sirve para subir el contenido del repositorio local hacia el repositorio remoto, actualizandolo.

  Fuente: https://www.atlassian.com/git/tutorials/syncing/git-push

- l.- fetch:

  Este comando permite descargar commits, archivos y referencias desde un repositorio remoto hacia uno local.

  Fuente: https://www.atlassian.com/git/tutorials/syncing/git-fetch

- m.- merge:

  Permite tomar las lineas independientes de trabajo en diferentes "brach" en git e integrarlas en una sola rama.

  Fuente: https://www.atlassian.com/git/tutorials/using-branches/git-merge

- n.- status:

  Este comando muestra el estado del directorio de trabajo y el area de preparacion. Permite ver los cambios que han sido preparados

  Fuente: https://www.atlassian.com/git/tutorials/inspecting-a-repository

- o.- log:

  Muestra todos los commits hechos en el repositorio local.

  Fuente: https://git-scm.com/docs/git-log

- p.- checkout:

  Permite cambiar entre las diferentes versiones de una entidad. Estas entidades en las cuales opera pueden ser: archivos, commits y ramas.

  Fuente: https://www.atlassian.com/git/tutorials/using-branches/git-checkout

- q.- branch:

  Las ramas son las diferentes instacias que puede llegar a poseer un repositorio remoto, las cuales contienen versiones de este repositorio con cambios variados, de diferentes usuarios.

  Fuente: https://www.atlassian.com/git/tutorials/using-branches

- r.- tag:

  Hace referencia a un punto en especifico dentro de la historia en git. Se puede definir como una especie de rama la cual nunca sufre cambios y no tiene historia de commits.

  Fuente: https://www.atlassian.com/git/tutorials/inspecting-a-repository/git-tag
