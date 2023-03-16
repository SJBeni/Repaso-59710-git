# Clase 01

## COMANDOS DE COSOLA BASICOS

* ls : Listar directorios
* cd : Cambiar de directorio

    cd <directorio>
    cd clase-01

* cd .. : Salir de un directorio
* touch : Crear archivos vacios
    
    touch <nombre-archivo.extension>
    touch archivo1.txt archivo2.txt

* mkdir : Crear directorios

    mkdir <nombre-directorio>
    mkdir dir1 dir2 dir3

* rm : Borrar archivos

    rm <archivo-a-borrar>
    rm index.html

* rmdir : Borrar directorio (que se encuentre vacio)

    rmdir <directorio-a-borrar>
    rmdir dir1

* clear : Limpio la consola

### GIT

> Saber si tengo git instalado

    git --version

> Configuracion importante de git
  GLOBAL: Para todos los repositorios que se creen en el equipo

    git config --global user.name "Nombre Completo"
    git config --global user.email "usuario@correo.com"

> Inicializar repositorio git (Crear un repositorio)

    git init

> Configuracion de repositorio con un usuario y mail diferente
  LOCAL: Configura usuario y mail para el repositorio actual

    git config --local user.name "nombre"
    git config --local user.email "correo"
