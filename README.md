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