# aspirantes-mir-ejercicioi-3

Administrador@AM-39 MINGW64 ~ (master)
$ pwd
/c/Users/Administrador.000

Administrador@AM-39 MINGW64 ~ (master)
$ git init
Reinitialized existing Git repository in C:/Users/Administrador.000/.git/

Administrador@AM-39 MINGW64 ~ (master)
$ git add README.md
fatal: pathspec 'README.md' did not match any files

Administrador@AM-39 MINGW64 ~ (master)
$ cd curso-de-git

Administrador@AM-39 MINGW64 ~/curso-de-git (master)
$ git add README.md

Administrador@AM-39 MINGW64 ~/curso-de-git (master)
$ Yurani Estrada Ruiz
bash: Yurani: command not found

Administrador@AM-39 MINGW64 ~/curso-de-git (master)
$ git commit -m "Agregué el archivo README.md"
[master (root-commit) c6cdb94] Agregué el archivo README.md
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 curso-de-git/README.md

Administrador@AM-39 MINGW64 ~/curso-de-git (master)
$ add . Felipe
bash: add: command not found

Administrador@AM-39 MINGW64 ~/curso-de-git (master)
$ git init
Initialized empty Git repository in C:/Users/Administrador.000/curso-de-git/.git/

Administrador@AM-39 MINGW64 ~/curso-de-git (master)
$ touch index.html

Administrador@AM-39 MINGW64 ~/curso-de-git (master)
$ nano index.html

Administrador@AM-39 MINGW64 ~/curso-de-git (master)
$ git add index.html
warning: in the working copy of 'index.html', LF will be replaced by CRLF the next time Git touches it

Administrador@AM-39 MINGW64 ~/curso-de-git (master)
$ git commit -m "commit inicial"
[master (root-commit) fcbd0f8] commit inicial
 1 file changed, 10 insertions(+)
 create mode 100644 index.html

Administrador@AM-39 MINGW64 ~/curso-de-git (master)
$ $ ^[[200~git branch~
git branch
bash: $: command not found
* master

Administrador@AM-39 MINGW64 ~/curso-de-git (master)
$ git branch develop

Administrador@AM-39 MINGW64 ~/curso-de-git (master)
$ git checkout develop
Switched to branch 'develop'

Administrador@AM-39 MINGW64 ~/curso-de-git (develop)
$ touch git.env

Administrador@AM-39 MINGW64 ~/curso-de-git (develop)
$ nano git.env

Administrador@AM-39 MINGW64 ~/curso-de-git (develop)
$ git rev-parse --show-toplevel
C:/Users/Administrador.000/curso-de-git

Administrador@AM-39 MINGW64 ~/curso-de-git (develop)
$ cd Users/Administrador.000/curso-de-git
bash: cd: Users/Administrador.000/curso-de-git: No such file or directory

Administrador@AM-39 MINGW64 ~/curso-de-git (develop)
$ cd ..

Administrador@AM-39 MINGW64 ~ (master)
$ touch .gitignore

Administrador@AM-39 MINGW64 ~ (master)
$ nano .gitignore

Administrador@AM-39 MINGW64 ~ (master)
$ nano .gitignore

Administrador@AM-39 MINGW64 ~ (master)
$ git add .gitignore
warning: in the working copy of '.gitignore', LF will be replaced by CRLF the next time Git touches it

Administrador@AM-39 MINGW64 ~ (master)
$ nano index.html

Administrador@AM-39 MINGW64 ~ (master)
$ git add index.html
warning: in the working copy of 'index.html', LF will be replaced by CRLF the next time Git touches it

Administrador@AM-39 MINGW64 ~ (master)
$ git commit -m "Cambios en la rama develop"
[master 48e33a7] Cambios en la rama develop
 2 files changed, 2 insertions(+)
 create mode 100644 .gitignore
 create mode 100644 index.html

Administrador@AM-39 MINGW64 ~ (master)
$ git checkout develop
error: pathspec 'develop' did not match any file(s) known to git

Administrador@AM-39 MINGW64 ~ (master)
$ git checkout main
error: pathspec 'main' did not match any file(s) known to git

Administrador@AM-39 MINGW64 ~ (master)
$ ^C

Administrador@AM-39 MINGW64 ~ (master)
$ cd curso-de-git

Administrador@AM-39 MINGW64 ~/curso-de-git (develop)
$ git commit -m "Cambios en la rama develop"
On branch develop
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        README.md
        git.env
        holamundo.php

nothing added to commit but untracked files present (use "git add" to track)

Administrador@AM-39 MINGW64 ~/curso-de-git (develop)
$ cd..
bash: cd..: command not found

Administrador@AM-39 MINGW64 ~/curso-de-git (develop)
$ cd ..

Administrador@AM-39 MINGW64 ~ (master)
$ ls
'3D Objects'/
 AppData/
'Configuración local'@
 Contacts/
 Cookies@
'Datos de programa'@
 Desktop/
 Documents/
 Downloads/
'Entorno de red'@
 Favorites/
 Impresoras@
 Links/
'Menú Inicio'@
'Mis documentos'@
 Music/
 NTUSER.DAT
 NTUSER.DAT{53b39e88-18c4-11ea-a811-000d3aa4692b}.TM.blf
 NTUSER.DAT{53b39e88-18c4-11ea-a811-000d3aa4692b}.TMContainer00000000000000000001.regtrans-ms
 NTUSER.DAT{53b39e88-18c4-11ea-a811-000d3aa4692b}.TMContainer00000000000000000002.regtrans-ms
 OneDrive/
 Pictures/
 Plantillas@
 Reciente@
'Saved Games'/
 Searches/
 SendTo@
 Videos/
 curso-de-git/
 index.html
 ntuser.dat.LOG1
 ntuser.dat.LOG2
 ntuser.ini

Administrador@AM-39 MINGW64 ~ (master)
$ cat index.html
Realizar cambios al archivo

Administrador@AM-39 MINGW64 ~ (master)
$ git add index.html

Administrador@AM-39 MINGW64 ~ (master)
$ cat index.html
Realizar cambios al archivo

Administrador@AM-39 MINGW64 ~ (master)
$ git add index.html

Administrador@AM-39 MINGW64 ~ (master)
$ cd curso-de-git/

Administrador@AM-39 MINGW64 ~/curso-de-git (develop)
$ git add index.html

Administrador@AM-39 MINGW64 ~/curso-de-git (develop)
$ cat index.html
<!DOCTYPE html>
<html>
<head>
  <title>Título de la página</title>
  <meta charset="UTF-8">
</head>
<body>
Cuerpo de la página.
</body>
</html>

Administrador@AM-39 MINGW64 ~/curso-de-git (develop)
$ git ls-files --other --ignored --exclude-standard

Administrador@AM-39 MINGW64 ~/curso-de-git (develop)
$ ls
README.md  git.env  holamundo.php  index.html

Administrador@AM-39 MINGW64 ~/curso-de-git (develop)
$
