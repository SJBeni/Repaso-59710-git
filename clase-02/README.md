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
