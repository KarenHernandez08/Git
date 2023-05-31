# Git

Curso de codigo facilito por Manuela Castrillón.

`Versión:` es un estado unico de un proyecto en un punto determinado del tiempo.

`Control de versiones:` gestiona los cambios realizados en el código fuente u otros documentos a lo largo del tiempo.

* control de versiones local
* control de versiones centralizado
* control de versiones distribuido

>Linus Torvalds creó Git en 2005 para controlar las versiones del kernel de Linux.

`Github:` es una empresa que almacena los proyectos

`Rama main` Es la rama que contiene la versión más estable

`Ramas` Bifurcaciones del flujo del trabajo

---
# Terminal de git
Para configurar nuestro Nombre vamos a colocar

```git
git config --globar user.name "<TuNombre>"
git congif --user.email "<tuEmail>"
```

`git add` para agregar cambios

`git commit`  registrar los cambios realizados en el área de preparación

`git log`Historial de commits

`git init` para inicializar nuestro repositorio

`git push -u origin main` subir los cambios al repositorio remoto

`git clone <url del repositorio>` para clonar un repositorio remoto a local

`git status` para verificar el estado del repositorio local


***
El proceso que segui para subir este repositorio

```git

git init

git clone <ssh> "aquí ya tenia el repositorio remoto"

cd <Nombre de el repositorio clonado>

git add <Nombre del archivo>

git commit -m "comentario o mensaje"

git push origin main "Subirlo a la rama original"

git commit -a -m "Agregando nuevas funcionalidades al archivo X"

```

`git branch` para ver las ramas que tenemos

`git switch -c <nombre de la rama>` para crear una rama

`git add .` para agregar todos los archivos4

`git push origin <Nombre de la rama>` se publica nuestra rama 

`git checkout <Nombre de la rama>` para posiscionarnos en la rama
