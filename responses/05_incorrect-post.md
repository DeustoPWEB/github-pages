## Comprobando tu post

@{{ user.username }} veo que has creado un archivo, pero ¡hay algunas cosas que tienes que resolver!

Echa un vistazo a tu archivo y asegúrate de que cumple los siguientes requerimientos:

- [{% if directory %}x{% else %} {%endif%}] Está en el directorio `_posts` 
- [{% if filenumber %}x{% else %} {%endif%}] El nombre del archivo empieza con el formato correcto para la fecha: AAAA-MM-DD
- [{% if post %}x{% else %} {%endif%}] El nombre del archivo incluye un título de post
- [{% if extension %}x{% else %} {%endif%}] El nombre del archivo incluye la extensión `.md`
- [{% if filename %}x{% else %} {%endif%}] El nombre del archivo cumple con los [requerimientos específicos para nombres de archivo](https://jekyllrb.com/docs/posts/#creating-post-files) de Jekyll.

### :keyboard: Actividad: Edita tu archivo

{% if preferences.gitTool == 'vscode' %}

1. En VS Code, realiza los ajustes necesarios en el archivo `_posts/AAAA-MM-DD-titulo.md` basándote en los errores mencionados arriba.
6. Para añadir los cambios realizados al archivo, ve a la vista de Source Control y haz clic en el botón **+** a lado del archivo.
1. Haz una confirmación de cambios escribiendo un mensaje de confirmación en el campo de texto y después presionando<kbd>Ctrl+Enter</kbd> en Windows o <kbd>Comando ⌘+Enter</kbd> en macOS.
1. Haz clic en los puntos suspensivos (...) y selecciona **Pull, Push > Push**.

{% else %}

1. Haz clic en la pestaña "Files Changed" en este pull request.
1. Haz clic en el icono del lápiz en el lado derecho de la pantalla.
1. Realiza los ajustes necesarios basándote en los errores mencionados arriba.
1. Haz scroll hasta la parte de abajo, y haz commit de tus cambios.

{% endif %}

Si necesitas ayuda resolviendo el problema que estás encontrando, crea un post en el tablero de [GitHub Community]({{ communityBoard }}). Puede que también quieras buscar tu problema para ver si otras personas lo han resuelto en el pasado.

<hr>
<h3 align="center">Mira mi respuesta más abajo.</h3>