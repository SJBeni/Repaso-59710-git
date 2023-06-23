# Clase 02

## GIT REMOTE

### Agregar remoto

    git remote add origin <URL>
    git remote add origin https://github.com/SJBeni/Repaso-59710-git.git

### Verificar los remotos

    git remote
    git remote -v

### Para subir el repo local al remoto

    git push -u origin master

## GITIGNORE
Me permite descartar archivos y carpetas que no quiero subir.

## GITKEEP
Me permite mantener y versionar carpetas vacias.

## GIT COMMIT

### Para hacer un commit

    git commit -m "Mensaje"

### Para hacer un git add y un git commit en simultaneo
Los archivos que quiero hacer commit deben estar en seguimiento. Si los archivos no estan en seguimiento (o sea no Untracked) no me los va a agregar en el git add

    git commit -am "Mensaje"

### Para enmendar un commit

Agrego los archivos que me olvide

    git add clase-02/cualquiera.md
Y luego hago el amend

    git commit --amend

## Status de archivos

* Untracked: Archivos que no se agregaron al index (staging area) o sea archivos que estan en el Working Directory (WD)

* Unmodified: Son archivos que ya estan en el repositorio. O sea ya tienen una foto

* Modified: Son archivos que ya estan en el repositorio pero con respecto al Working Directory tienen modificaciones detectadas por git. O sea compara la foto del repositorio con el WD.

* Staged: Archivos que estan confirmados para ser un proximo commit.

## GIT LOG

### Me muestra una cantidad especifica de commit

    git log --help

> Me muestra los ultimos 2 commits

    git log -2

> Me muestra los commit por 

    git log --since = "2022-05-01"
    git log --after = "2022-06-01"
    git log --before = "2022-05-01"
    git log --after = "2022-05-01" --before="2022-05-10"

## GIT RAMAS (Branchs)
    
> Crear una rama

    git branch <nombre-rama>
    git branch dev

> Moverme entre ramas

    git switch <nombre-rama>
    git switch dev

> Para ver las ramas

    git branch