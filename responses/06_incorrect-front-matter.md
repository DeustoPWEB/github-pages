## Comprobando tu texto preliminar

Parece que podría haber algunos errores en tu texto preliminar. Echa un ojo a tu texto preliminar para asegurarte de que cumple estas condiciones:

- [{% if dashes %}x{% else %} {% endif %}] Has utilizado guiones en la primera y la última línea de tu texto preliminar
- [{% if title %}x{% else %} {% endif %}] Has añadido el título del post entre comillas
- [{% if date %}x{% else %} {% endif %}] Has añadido la fecha utilizando el formato correcto

El texto preliminar YAML debería estar en la parte superior de tu archivo y tener este aspecto:

```yaml
---
title: "El título de tu post"
date: AAAA-MM-DD
---
```

### :keyboard: Actividad: Edita tu post

{% if preferences.gitTool == 'vscode' %}

1. En VS Code, realiza los ajustes necesarios en el archivo `_posts/AAAA-MM-DD-titulo.md` basándote en los errores mencionados arriba.
6. Para añadir los cambios realizados al archivo, ve a la vista de Source Control y haz clic en el botón **+** a lado del archivo.
1. Haz una confirmación de cambios escribiendo un mensaje de confirmación en el campo de texto y después presionando<kbd>Ctrl+Enter</kbd> en Windows o <kbd>Comando ⌘+Enter</kbd> en macOS.
1. Haz clic en los puntos suspensivos (...) y selecciona **Pull, Push > Push**.

{% else %}

1. Haz clic en la pestaña "Files Changed" de este pull request.
1. Haz scroll hasta pasar el archivo de configuración, y localiza el archivo que has creado.
1. Haz clic en el icono del lápiz en la parte derecha de la pantalla.
1. Realiza los ajustes necesarios basándote en los errores mencionados arriba.
1. Haz scroll hasta la parte de abajo, y haz commit de tus cambios.

{% endif %}

Si necesitas ayuda resolviendo el problema que estás encontrando, crea un post en el tablero de [GitHub Community]({{ communityBoard }}). Puede que también quieras buscar tu problema para ver si otras personas lo han resuelto en el pasado.

<hr><h3 align="center">Mira mi respuesta más abajo.</h3>
