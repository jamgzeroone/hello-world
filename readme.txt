"Hello!"
Esto es solo la prueba para comenzar hacer commit(commpromisos) para para empezar tenemos que crear el comando <git init> este comando crea una folder(carpeta) .git donde se almacena la history(historia) de los commit el siguiente comando es agregar archivos adicionar los archivos al commit para llevar su evolucion con <git add> mas el nombre de los archivos. otro comando util es de poder ver el estatus del commit que es <git status> y finalmente el comando <git commit -m "coemntarios"> con este comando se agregan el commit para comprometer los cambios al repositorio con el "-m" es el agragar comentarios o mensajes el el commit para describir las actualizaciones echas en el commit

otros comandos son el comando <git diff> este comando nos dice las diferencias entre los archivos


Check status of changes to a repository
Chequear el estado de los cambios en el repositorio 
<git status>

View changes to files 
Ver los cambios en los archivos
<git diff>

Add a file's changes to be committed 
Adicionar un archivo al commit
<git add <FILENAME>>

To add all files changes
Adicionar todos los cambios de los archivos al commit
<git add .>

To commit (aka save) the changes you've added with a short message describing the changes 
Para salvar los cambios y agregar un mensaje corto describiendo los cambios 
<git commit -m "your commit message">

Agregamos mas tips

Add remote connections
adicionamos la conexion remota a github
git remote add <REMOTENAME> <URL>

Set a URL to a remote
poner la direccion de  servidor remot 
git remote set-url <REMOTENAME> <URL>

Pull in changes
traer los cambios desde el servidor remoto
git pull <REMOTENAME> <BRANCHNAME>

View remote addresses
ver la direccion remota.
git remote -v

Push changes
Enpujar los cambios al servidor remoto
git push <REMOTENAME> <BRANCH>

algunos tips mas sobre agregar un repositorio clonar un repositorio poner otra direccion al fork del repositorio los fork son como proyectos que ponemos en nuestras cuentas traidos desde otros repositorios de otros usuarios para hacer cambios utilizarlos o mejorarlos para el original.  

para clonar un repositorio el comando es 
git clone <urlDeGitHubDelRepositorio>


En los fork podemos poner la direccion del repositorio original de donde lo hemos traido con el comando 
git remote add <nombreQueleDemos> <UrlDelRepositorioOriginal>

Tips

Add a remote
adicionar direccion remota
git remote add <REMOTENAME> <URL> 

Change a remote URL 
Cambiar la direccion remota 
git remote set-url <REMOTENAME> <URL>


View remote connections
Ver las conexiones remotas que tienen nuestro proyecto
git remote -v





Nuevos comentarios para crear ramas 

You can create and switch to a branch in one line 
Crear y pasarce a la nueva rama con una sola linea de comandos
git checkout -b <BRANCHNAME> 


Create a new branch 
crear una nueva rama
git branch <BRANCHNAME>

Move onto a branch
Moverce a una rama 
git checkout <BRANCHNAME>

List the branches 
Listar las ramas del repositorio
git branch


Rename a branch you're currently on 
renombrar la rama en que uno se encuentre
git branch -m <NEWBRANCHNAME> 

Verify what branch you're working on 
Verificar en que rama se esta trabajando
git status



