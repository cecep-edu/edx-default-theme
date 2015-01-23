Overview
========
Este directorio almacena un tema por defecto para una instancia abierta edx.

Hemos organizado el árbol para imitar la estructura de directorios de la base de código edx para que sea más fácil saber donde están los archivos terminarán al despliegue. Vamos a utilizar un archivo de configuración especial para configurar la plantilla y staticfiles caminos correctamente para apuntar a estos archivos.

![Alt text](/default_theme_screenshot.jpg?raw=true "Open edX Default Theme Screenshot")

Theme Authoring
===============
To customize your theme:
- Fork this repository.
- Clone it into the theme directory next to your edx-platform directory and rename the theme directory to your new theme's name.
- Upload your own image assets.
- Edit the .scss file in static/sass/ and rename the file with your theme's name.
- Edit the lms.envs.json file in edx-platform and set 'USE_CUSTOM_THEME' to true, and 'THEME_NAME' to your theme's name.


License
=======

The code in this repo is licensed under the Apache 2.0 License.
See [LICENSE.txt](LICENSE.txt) for more info.
