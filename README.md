Overview
========
Este directorio almacena un tema por defecto para una instancia abierta edx.

Hemos organizado el árbol para imitar la estructura de directorios de la base de código edx para que sea más fácil saber donde están los archivos terminarán al despliegue. Vamos a utilizar un archivo de configuración especial para configurar la plantilla y staticfiles caminos correctamente para apuntar a estos archivos.

![Alt text](/default_theme_screenshot.jpg?raw=true "Open edX Default Theme Screenshot")


Theme Authoring
===============

Para personalizar el tema:

contener este repositorio.
Clonar en el directorio del tema junto a su directorio edx-plataforma y cambiar el nombre del directorio del tema al nombre de su nuevo tema.
Sube tus propios recursos de imagen.
Edite el archivo .scss en estático / sass / y cambiar el nombre del archivo con el nombre de su tema.
Edite el archivo lms.envs.json en edx-plataforma y establecer 'USE_CUSTOM_THEME' true, y 'THEME_NAME' al nombre de su tema.


License
=======

El código de este repo está licenciado bajo la licencia Apache 2.0. Ver LICENSE.txt para obtener más información.
