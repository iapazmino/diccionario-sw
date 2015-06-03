# Diccionario de software
Este es un diccionario que tiene la traducción al idioma español de los términos referentes al desarrollo de software.

El objetivo de este diccionario es recopilar los términos que aparecen en las muchas actividades, herramientas, ténicas y medidas que están al rededor del software y la tecnología en general y evitar así anglicismos españolizados, como por ejemplo "deployar", "commitear", "testear" y así una lista interminable.

Este diccionario es además mi último esfuerzo por defender el idioma.

**Este proyecto no contiene traducciones oficiales.**

**Su uso es gratuito y sin ninguna garantía.**

## Estructura de archivos
Las traducciones van en un archivo de llamado diccionario.json dentro de una carpeta nombrada a partir del idioma de origen y el idioma y cultura de destino. Por ejemplo:

```
+ en_es-EC
|- diccionario.json
+ en_pt-BR
|- diccionario.json
```

## Formato de los archivos
El formato de los archivos es JSON para que a futuro puedan ser explotados por una aplicación o importados a un repositorio de datos fácilmente.

Una vez modificado un archivo se puede validar su estructura en http://jsonlint.com

## Colaborar
### Solicitar traducciones

1. Abre la sección [Issues](https://github.com/iapazmino/diccionario-sw/issues) y presiona el botón "New issue".
2. Registra en el título la traducción que requieres y el idioma de destino. Si crees conveniente agrega algún comentario que guíe la traducción.

### Enviar traducciones
Para agregar o modificar una traducción solamente necesitas seguir los siguientes tres pasos.

1. Haz una copia de este proyecto presionando el botón [Fork](https://github.com/iapazmino/diccionario-sw#fork-destination-box) ubicado en la parte superior derecha de esta página. **Esto es necesario hacerlo solo una vez.**
2. Abre el archivo diccionario.json de la sección que vas a editar y agrega el contenido y escribe un comentario de la adición en la caja de texto "Commit changes" y presiona el botón con el mismo nombre.
3. Finalmente abre la sección "Pull requests", presiona el botón "New pull request" y en la pantalla que aparece a continuación presiona el botón "Create pull request".
