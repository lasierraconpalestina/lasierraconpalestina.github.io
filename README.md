# Instrucciones para editar la página web

## Cómo crear una carpeta nueva desde la web de GitHub

Para añadir imágenes a una acción, hay que subir las imágenes a una carpeta en `/archivos/acciones/` con el mismo nombre que el `id` de  la acción en `_data/acciones.yml`. Aquí va una explicación de cómo crear una carpeta nueva en `/archivos/acciones/` y subir imágenes desde la interfaz web de GitHub.

1. Desde la página principal del repositorio de la web, hacemos click en la carpeta `archivos`, que nos mostrará el contenido de la carpeta.
2. Hacemos click en la carpeta `acciones`, que nos mostrará el contenido con las carpetas de cada acción.
3. Una vez dentro de la carpeta `/archivos/acciones/`, hacemos click en "Add file", arriba a la derecha, que mostrará el desplegable con las opciones "Create new file" y "Upload new files".
4. Hacemos click en "Create new file". Lo que vamos a hacer es crear una carpeta como si fuera un archivo nuevo.
5. En el campo "Name your file", arriba en el centro, escribimos el nombre de la carpeta, por ejemplo `nueva-carpeta`.
6. A continuación, introducimos una barra "/". Automáticamente, GitHub nos permitirá crear un nuevo archivo dentro de una nueva carpeta llamada `nueva-carpeta`.
7. A continuación, escribimos `.gitkeep`. Este es un nombre especial para hacer que GitHub cree una carpeta vacía. Es importante escribir este nombre tal cual ".gitkeep" con el punto inicial incluído.
8. Hacemos click en el botón verde "Commit changes..." arriba a la derecha. GitHub nos mostrará una pequeña ventana donde podemos escribir el mensaje del _commit_.
9. Escribimos la descripción del _commit_, por ejemplo "Crear carpeta nueva-carpeta en archivos/acciones/".
10. Hacemos click en el botón verde "Commit changes" en la parte inferior derecha de la pequeña ventana. GitHub nos mostrará el contenido de la nueva carpeta, con el archivo `.gitkeep`.
11. Para subir las imágenes, hacemos click en "Add file", arriba a la derecha, que mostrará el desplegable con las opciones "Create new file" y "Upload new files".
12. Hacemos click en "Upload files".
13. Hacemos click en "choose your files" o arrastramos los archivos a la zona central.
14. Se abrirá un navegador de nuestro sistema, donde podemos seleccionar las imágenes que queremos subir.
15. Una vez seleccionadas, veremos la lista de imágenes en el centro.
16. Escribimos el mensaje de _commit_, por ejemplo "Subir imágenes..."
17. Hacemos click en el botón verde "Commit changes", en la parte inferior izquierda. GitHub mostrará una ventana con el mensaje "Processing your files..."
18. Una vez completado el proceso, veremos el contenido de la nueva carpeta con las imágenes que hemos subido.

El GIF inferior muestra un ejemplo del proceso.

![Cómo crear una carpeta nueva desde la interfaz web de GitHub](/archivos/instrucciones/crear_nueva_carpeta_github.gif)
