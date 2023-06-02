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

`Issues` Espacio en el que podemos escribir y dar seguimiento a tareas, bugs, ideas e incluso retroalimentación

`pull request` solicitud para integrar los cambios en una rama diferente

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

`git switch <rama>` este igual es para posicionarnos a la rama

`git merge <la que tiene los cambios>` para integrar los cambios a la otra rama

`git pull origin main` ver que la rama este actualizada


---

## GitHub Pages

Para subir un proyecto web estatico, nos da un dominio web. <nombredeusuario>.github.io 

sitio web estático: se muestra tal como está almacenado y todos los usuarios ven la misma información. (portafolio, proyectos pequeños, o proyectos de documentación)

creamos nuestro repositorio y nos vamos a settings y en pages lo vamos a subir.

---

## Markdown

Lenguaje de Markup que nos permite escribir texto formateado con una sintaxis simple, que es facil de leer y escribir

shields.io

---

## Open Source Software (OSS)

Software que tiene un tipo de licencia especial que permite el uso, modificación y distribución a cualquier persona.

¿Cómo contribuir en open source?
- código
- documentación
- diseño
- reporte de errores
- generación de ideas
- creación de contenido