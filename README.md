#💻 Explorando Git y GitHub: tu bitácora de control de versiones
---
##Git 🔺
<img src="https://images.icon-icons.com/2415/PNG/512/git_plain_wordmark_logo_icon_146508.png" width="190"/>

- ¿Qué es? Un sistema de control de versiones distribuido que permite a los desarrolladores rastrear cambios, hacer un seguimiento del historial del código y volver a versiones anteriores.
- Función principal: Gestionar el historial de un proyecto de forma local en la máquina de cada desarrollador.
- Características: Permite crear ramas para trabajar en paralelo, integrar con entornos de desarrollo y realizar un seguimiento detallado de los cambios.

##GitHub 🔲

<img src="https://static.vecteezy.com/system/resources/previews/017/119/660/non_2x/github-logo-git-hub-icon-with-text-on-white-and-black-background-free-vector.jpg" width="300"/>

- ¿Qué es? Una plataforma de desarrollo de software basada en la nube que utiliza Git.
- Función principal: Alojamiento de repositorios de código y colaboración entre múltiples desarrolladores a través de una interfaz web.
- Características: Proporciona herramientas adicionales como la gestión de incidencias (issues), solicitudes de extracción (pull requests) y wikis, además de funcionar como una red social para desarrolladores.
---

## Los principales comandos de Git 💻

✅ **Comandos esenciales**
- Git init: Crea un nuevo repositorio de Git  en el directorio actual.
- Git clone <url>: Copia un repositorio existente desde una URL.
- Git add <archivo>: Prepara los cambios de un archivo para el próximo commit.
- git commit guarda una instantánea de los cambios preparados en el repositorio local
- Git commit -m "mensaje": Guarda la instantánea de los cambios preparados en el historial del proyecto.
- Git add. Añade todos los archivos modificados y nuevos en el directorio actual  y sus subdirectorios al area de ensayo.
- Git status: Muestra el estado actual del directorio de trabajo y el área de preparación (staged), como los archivos modificados, añadidos o que no están siendo rastreados.

✅ **Comandos de ramas**
- Git branch: Lista las ramas existentes, crea una nueva o elimina una.
- Git checkout <nombre_rama>: Cambia a otra rama.
- Git checkout -b <nueva_rama>: Crea una nueva rama y cambia a ella.
- Git merge <rama_a_fusionar>: Combina los cambios de una rama en la rama actual.

✅ **Comandos remotos**
- Git pull origin <nombre_rama>: Descarga los cambios de un repositorio remoto y los fusiona con la rama local actual.
- Git push origin <nombre_rama>: Sube los cambios de la rama local a un repositorio remoto.
- Git push sirve para subir los cambios de tus ramas locales a un repositorio remoto, como GitHub, Bitbucket o GitLab.
- Git remote add origin <url>: Conecta el repositorio local con uno remoto.
- Git remote -v: Muestra los repositorios remotos asociados.

✅ **Comandos para revision**
- Git log: Muestra el historial de commits.
- Git diff: Muestra las diferencias entre el directorio de trabajo y el área de preparación, o entre commits.
- Git stash: Guarda los cambios en el directorio de trabajo sin hacer un commit, para poder trabajar en otra cosa y luego recuperarlos.
- Git reset: Restablece el estado de los archivos (por ejemplo, mueve la punta de la rama).
- Git revert <hash_commit>: Crea un nuevo commit que deshace los cambios de un commit anterior.

---
---
<img width="494" height="277" alt="image" src="https://github.com/user-attachments/assets/667d44e7-5b9c-4f8d-b5f9-e0c5242b31cf" />

