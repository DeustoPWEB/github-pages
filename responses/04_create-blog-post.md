## Paso 5: Crea un post en tu blog

:warning: ¡No hagas merge todavía! :warning:

Este pull request pinta muy bien. :sparkles: ¡Acabas de editar el archivo `_config.yml`! Tenemos algo más de trabajo para crear tu blog. Puedes seguir haciendo commits en tu rama `{{ branch }}` y el pull request se actualizará automáticamente.

### :keyboard: Actividad: Añade algo de contenido a tu blog

{% if preferences.gitTool == 'vscode' %}

1. Descarga y abre [Visual Studio Code](https://code.visualstudio.com/Download) (referido como VS Code) si aún no lo tienes.
1. En VS Code, abre la Paleta de Comandos (o _Command Palette_) usando <kbd>Ctrl+Mayús+P</kbd> en Windows, o <kbd>Command ⌘+Mayús+P</kbd> en macOS. También puedes seguir [la documentación oficial de VS Code](https://code.visualstudio.com/docs/editor/versioncontrol#_cloning-a-repository) sobre clonar repositorios.
1. Escribe `git clone`y presiona <kbd>Enter</kbd>
      ![una captura de pantalla de VS Code con la Paleta de Comandos abierta](https://user-images.githubusercontent.com/16547949/53639288-bcf9ec80-3bf6-11e9-9d18-d97167168248.png)
1. Pega la URL del repositorio en la nueva ventana y presiona <kbd>Enter</kbd>:
      ```shell
      {{ thePayload.repository.clone_url }}
      ```
1. Selecciona la ubicación en el que quieres guardar el repositorio y haz clic en **Choose folder**. Después, abre la ubicación que seleccionaste (haciendo clic en **Open**).  
2. El directorio del repositorio debería estar ahora abierto en tu proyecto de VS Code. Haz clic en `master` en la parte inferior de la ventana de VS Code. Esto abrirá la Paleta de Comandos con todos los comandos relacionados a ramas de Git. 
      ![una captura de pantalla de las ramas de Git en VS Code](https://user-images.githubusercontent.com/16547949/53639606-adc76e80-3bf7-11e9-98ac-bd41ae2b40db.png)
1. Selecciona tu rama `{{ branch }}`
1. Crea un directorio llamado `_posts`, y un archivo nuevo dentro de este directorio llamado `AAAA-MM-DD-titulo.md`. Reemplaza `AAAA-MM-DD` con la fecha de hoy, y cambia también el `titulo` de tu primer post si quieres. _Nota:_ Si cambias el título, asegúrate de utilizar guiones en lugar de espacios.

   - Si la fecha de tu post no sigue la convención de fechas correcta, recibirás un error y tu sitio no se construirá. Para más información, puedes acceder a "[Page build failed: Invalid post date](https://help.github.com/articles/page-build-failed-invalid-post-date/)".

3. Escribe un borrador rápido de tu primer post. Recuerda, siempre puedes editarlo después y guarda el archivo.
1. Para añadir los cambios realizados al archivo, ve a la vista de Source Control y haz clic en el botón **+** a lado del archivo. También puedes seguir este paso con la [documentación oficial de VS Code](https://code.visualstudio.com/docs/editor/versioncontrol#_commit).
      ![una captura del botón de staging en la vista Source  Control](https://user-images.githubusercontent.com/16547949/53641057-d5b8d100-3bfb-11e9-9b69-53b0661cd5cd.png)
1. Haz una confirmación de cambios escribiendo un mensaje de confirmación en el campo de texto y después presionando<kbd>Ctrl+Enter</kbd> en Windows o <kbd>Comando ⌘+Enter</kbd> en macOS.
      ![una captura del mensaje de confirmación de cambios VS Code](https://user-images.githubusercontent.com/16547949/53641276-698a9d00-3bfc-11e9-9b3d-01680fd01d7c.png)
1. Haz clic en los puntos suspensivos (...) y selecciona **Pull, Push > Push**.


{% else %}


**Nota de atajo**: Haz clic en [este enlace]({{ repoUrl }}/new/{{ branch }}/?filename=_posts/{{ date | date: "%Y-%m-%d" }}-my-first-blog-post.md) para completar automáticamente los pasos 1-4.

1. En la pestaña "Code", selecciona tu rama `{{ branch }}`.
1. Haz clic en **Create new file** (crear un archivo nuevo).
1. Nombra el archivo `_posts/AAAA-MM-DD-titulo.md`.
1. Reemplaza `AAAA-MM-DD` con la fecha de hoy, y cambia también el `titulo` de tu primer post si quieres. _Nota:_ Si cambias el título, asegúrate de utilizar guiones en lugar de espacios.

   - Si la fecha de tu post no sigue la convención de fechas correcta, recibirás un error y tu sitio no se construirá. Para más información, puedes acceder a "[Page build failed: Invalid post date](https://help.github.com/articles/page-build-failed-invalid-post-date/)".

1. Escribe un borrador rápido de tu primer post. Recuerda, siempre puedes editarlo después.
1. Haz commit de tus cambios a tu rama.

{% endif %}

<hr>
<h3 align="center">Mira mi respuesta más abajo.</h3>
