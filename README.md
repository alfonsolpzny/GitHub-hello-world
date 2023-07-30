# hello-world
Hello World repository for Git tutorial
This is an example repository for the Git tutoial on https://www.w3schools.com

This repository is built step by step in the tutorial.

# comados
#### Iniciar usuario y correo
`git config --global user.name "alfonso"`
`git config --global user.email "luislopezanaya@outlook.com"`

#### Ir a un directio e iniciar el repo
`mkdir "directorio"` -> opcional
`cd "directorio"`
``git init`

#### listar los archivos
`ls`

#### Añadir los archivos o añadirlos todos
`git add "nombre de archivo"`

###### Diferentes formas de añadirlos todos los archivos
`git add --all`
`git add -A`

#### checar los status - verifica los archivos ya segudos y que faltan asi como modificaciones
`git status`

###### forma corta ver el status
`git status --short`

###### advertencias en el status corto
?? - Untracked files
A - Files added to stage
M - Modified files
D - Deleted files

#### Añadir un commit
`git commit -m "Mensaje de commit"`

#### Agregar commit para cuando no se creo un archivo y solo se modifico o para mitir el comado add
`git commit -a -m "info"`

#### ver los commits
`git log`

#### ver opciones del comando
`git comad -help`

#### ver todos los comandos
`git help --all`

#### Crear una nueva rama (branch)
`git branch name-branch`

#### ver las ramas existentes
`gir branch`

#### Cambiarse a una rama
`git checkout name-branch`

#### crear una rama y cambiarse directamente a esa rama
`git checkou -d branch-name`

#### Mesclar una rama
`git merge branch-name`
Nota: Antes de mezclar, en la rama que se edito se tiene que ejecutar el comado `add --all` y luego hacer `commit`. Despues se tiene que cambiar a la rama donde quieres que afecte la mezcla ahora ejecutar `merge` con el nombre de la rama que se edito.

Ya en la rama master o la que se quiera afectar ejecutar el comando `add file.extencion` o `add --all` y hacer otro commit

#### Eliminar una rama 
`git checkout -b branch-name`

# Iniciar un repositorio en github
Crear un repositorio nuevo en github y ejecutar el siguiente comado con la url del repositorio que se crea
`git remote add origin url`

#### Despues subir los archivos
para la primera vez `git push --set-upstream origin master`
`git push origin master`

#### se edito en otra maquina o en el navegador un nuevo cambio para hecer con pull
Con el comado `git log origin/master` ven los commit en todas las maquinas hechos.
Para ver la diferencia entre lo que se edito y lo que esta en la maquina local usar el comando `git giff origin/master`

#### actualizar archivos cuando se editan en otra parte
`git pull origin`




