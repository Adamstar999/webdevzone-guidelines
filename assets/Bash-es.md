# Guía de la Terminal

## Conceptos

-   **Interfaz Gráfica de Usuario (_GUIs_)** - explorador de archivos
-   **Interfaz de Línea de Comandos (_CLIs_)** - terminal
-   **Arriba/Abajo** - navegar en el historial de comandos
-   **~** - directorio del usuario (/c/Users/User/)
-   **`** - ejecuta un editor de texto dentro de la terminal
-   **ctrl + c** - para salir de cualquier código bloqueante

## Comandos

-   **pwd (_print work directory_)** - muestra el directorio actual
-   **pushd (nombre ruta)** - accede a otra ruta sin perder la actual
-   **popd (nombre ruta)** - regresa a la ruta previa
-   **file (nombre archivo)** - muestra el formato del archivo
-   **which (comando)** - verifica si un comando está instalado
-   **history** - muestra el historial de todos los comandos ejecutados
-   **whoami** - muestra el usuario actual
-   **help (comando) (_--help_)** - muestra todos los comandos
-   **clear** - limpia la terminal
-   **ls (_list storage_)** - lista archivos de la carpeta actual
-   **touch (nombre archivo) (nombre archivo)** - crea archivos
-   **echo "texto" > (nombre archivo)** - crea archivos con contenido
-   **cat (nombre archivo)** - muestra el contenido textual
-   **cat > (nombre archivo)** - reemplaza contenido textual del archivo en la terminal
-   **cat >> (nombre archivo)** - añade contenido textual al archivo en la terminal
-   **mkdir (nombre carpeta) (nombre carpeta)** - crea directorios
-   **rmdir (nombre carpeta) (nombre carpeta)** - elimina directorios vacíos
-   **rm -r (nombre archivo) (nombre archivo)** - elimina directorio y archivos dentro de él
-   **rm (nombre archivo) (nombre archivo)** - elimina archivo
-   **mv (directorio origen) (nombre archivo)** - mueve archivo
-   **mv (nombreViejo) (nombreNuevo)** - renombra archivo
-   **cp (directorio origen) (nombre archivo)** - copia archivo
-   **find** - busca archivo (_se pueden usar Expresiones Regulares_)
-   **ps** - lista los procesos actuales
-   **kill (ID)** - detiene un proceso
-   **nano (nombre archivo)** - abre nano en la terminal
-   **vim** - abre vim en la terminal
-   **code (ruta directorio)** - abre directorio actual en Visual Studio Code
-   **alias** - muestra el alias de los comandos que has creado
-   **alias (_alias_)="(_comando_)"** - crea un alias
-   **unalias (_alias_)** - borra un alias

## Comandos cd

-   **cd (_change directory_)** - cambia a otro directorio (_Para llegar a una carpeta que tenga espacios en el nombre, pon el nombre del directorio entre comillas "" o \ antes del espacio_)
-   **cd ~** - va al directorio de User
-   **cd ..** - va al directorio padre del directorio actual
-   **cd /** - va al directorio raíz
-   **cd (_c/d_)** - va al directorio de un disco duro (_c/d/etc_)
-   **cd ../..** - regresa dos niveles
-   **cd -** - regresa al directorio anterior

## Consejos

> **"comando + -letras"** = opción de comando:
>
> -   **-a** - muestra todos los archivos
> -   **-l** - muestra las especificaciones de los archivos
> -   **-a** - muestra archivos ocultos
