# Clasificación de imágenes (autobuses y automoviles)


Este código representa el sitio web, una vez que se crea y entrena el modelo de inteligencia artificial con Python y Tensorflow, el cual es exportado a los archivos "json" y "bin".
Puede utilizarse en el celular, solo carga la cámara al vehiculo que quieres clasificar (puede ser una imagen de la computadora, una foto, o uno de verdad), lo hace todo en el explorador utilizando Tensorflow.js.

## Cómo utilizarlo

### Descargar el repositorio
Descarga el repositorio donde gustes en tu computadora

### Inicia un servidor en la carpeta
Este proyecto utiliza un modelo de Tensorflow.js, el cual para cargarse requiere que el acceso sea por medio de http/https.
Para eso puedes usar cualquier servidor, pero aquí hay una forma de hacerlo:
- Descarga Python en tu computadora
- Abre una línea de comandos o terminal
- Navega hasta la carpeta donde descargaste el repositorio
- Ejecuta el comando `python -m http.server 8000`
- Abre un explorador y ve a http://localhost:8000
