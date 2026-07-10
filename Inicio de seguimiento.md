[[Introduccion]]

A la carpeta de Comando Git GitHub la inicio con 

``` GIT
git init
```
el resultado es:

``` GIT
git status
On branch main

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        .obsidian/
        Inicio de seguimiento.md
        Introduccion.md

nothing added to commit but untracked files present (use "git add" to track)

Luis Soto@NC000069 MINGW64 ~/OneDrive/Obsidian/Comando Git GItHub (main)
$
```

Veo que hay dos archivos, para seguir aunque todavía no se hizo el add

La acción de los comandos:

```GIT
git add.
git status
```
  Me dá este resultado:

``` GIT
git status
On branch main

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   .obsidian/app.json
        new file:   .obsidian/appearance.json
        new file:   .obsidian/core-plugins.json
        new file:   .obsidian/graph.json
        new file:   .obsidian/workspace.json
        new file:   Inicio de seguimiento.md
        new file:   Introduccion.md


Luis Soto@NC000069 MINGW64 ~/OneDrive/Obsidian/Comando Git GItHub (main)
```
Verifico el mail que tengo activo de Git

``` GIT
git config --global user.email
300199434+LuchoElectroluz@users.noreply.github.com
```

Para hacer el commit hago

``` GIT
git commit 
```
 Para que me abra por defecto el edito de VS