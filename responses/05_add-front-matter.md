## Paso 6: Añade metadatos del post

Ahora que has creado tu archivo con el post para un blog en Jekyll, podemos añadir algo de sintaxis. La sintaxis que usan los archivos de Jekyll se llama texto preliminar YAML. Va en la parte superior de tu archivo y tiene este aspecto:

```yaml
---
title: "Bienvenida a mi blog"
date: 2019-01-20
---
```

Este ejemplo añade un título y una fecha a tu post. Hay otras cosas útiles que puedes añadir aquí en el futuro como plantillas, categorías o cualquier otra lógica que te resulte útil. Para más información sobre la configuración del texto preliminar, puedes consultar [Jekyll front matter documentation](https://jekyllrb.com/docs/frontmatter/).

### :keyboard: Actividad: Añade texto preliminar a tu post

{% if preferences.gitTool == 'vscode' %}

1. En VS Code, añade lo siguiente en la parte superior de tu post (recuerda, está en `_posts/AAAA-MM-DD-titulo.md`:

       ---
       title: "TU TÍTULO"
       date: AAAA-MM-DD
       ---

4. Reemplaza TU TÍTULO con el título para tu post.
5. Reemplaza AAAA-MM-DD con la fecha de hoy.
6. Para añadir los cambios realizados al archivo, ve a la vista de Source Control y haz clic en el botón **+** a lado del archivo. También puedes seguir este paso con la [documentación oficial de VS Code](https://code.visualstudio.com/docs/editor/versioncontrol#_commit).
      ![una captura del botón de staging en la vista Source  Control](https://user-images.githubusercontent.com/16547949/53641057-d5b8d100-3bfb-11e9-9b69-53b0661cd5cd.png)
1. Haz una confirmación de cambios escribiendo un mensaje de confirmación en el campo de texto y después presionando<kbd>Ctrl+Enter</kbd> en Windows o <kbd>Comando ⌘+Enter</kbd> en macOS.
      ![una captura del mensaje de confirmación de cambios VS Code](https://user-images.githubusercontent.com/16547949/53641276-698a9d00-3bfc-11e9-9b3d-01680fd01d7c.png)
1. Haz clic en los puntos suspensivos (...) y selecciona **Pull, Push > Push**.

{% else %}

1. Haz clic en la pestaña "Files Changed" de este pull request.
1. Hay dos archivos en la pestaña "Files Changed", el archivo `_config.yml` y el archivo `_posts/YYYY-MM-DD-title.md`. Asegúrate de editar el archivo que hay en la carpeta `_posts`. 
2. Haz clic en el icono de la parte derecha para editar.
3. Escribe lo siguiente en la parte superior de tu post:

       ---
       title: "TU TÍTULO"
       date: AAAA-MM-DD
       ---

4. Reemplaza TU TÍTULO con el título para tu post.
5. Reemplaza AAAA-MM-DD con la fecha de hoy.
6. Haz commit de tus cambios en tu rama.

{% endif %}

<hr>
<h3 align="center">Mira mi respuesta más abajo.</h3>
