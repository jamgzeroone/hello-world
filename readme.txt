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

Gregamos mas tips

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


