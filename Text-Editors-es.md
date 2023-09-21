# Editores de Código

Los editores de código son herramientas esenciales para cualquier desarrollador. Permiten modificar el código fuente en varios lenguajes de programación y brindan diversas funciones para simplificar el trabajo y mejorar la eficiencia.

Es importante hacer una distinción entre editores de código e **IDE**. Los editores son generalmente programas ligeros que proporcionan lo esencial para una experiencia de desarrollo efectiva y productiva, sin complejidades.

Sin embargo, los editores actuales tienen la capacidad de expandirse considerablemente a través de complementos, lo que puede llevarlos a niveles de sofisticación similares a los de los **IDE**.

En el ámbito de la programación, existen numerosos editores de código entre los cuales puedes investigar y elegir el que más te agrade. Si te falta conocimiento o sientes indecisión en este asunto, permíteme presentarte una opción muy recomendable. En esta sección, vamos a tratar sobre **Visual Studio Code**, que destaca por su facilidad de uso y una amplia gama de funcionalidades. Otros editores igualmente buenos son **Sublime Text** y **Vim**. Sin embargo, **Sublime Text** es de pago, y aunque **Vim** puede ser complicado de aprender al principio, una vez dominado puede aumentar significativamente tu eficiencia en la manipulación de texto mediante el teclado.

## Guía

A continuación, te presentaré algunos recursos que te serán de gran ayuda para dominar la herramienta de **Visual Studio Code**:

### Cursos de Visual Studio Code

Comenzaremos con un video que te brindará una comprensión completa sobre el uso de **Visual Studio Code**, además de proporcionarte valiosos consejos y trucos. Te recomiendo omitir las secciones de _Control de versiones con **Git**_ y _Debugger, el depurador de **VSCode**_, ya que abordaremos esos temas en otras secciones. Además, no es necesario seguir todos los pasos detallados, la mayoría son opcionales. Este video está bien estructurado y es breve, lo que lo convierte en una introducción perfecta. Sin más preámbulos, aquí tienes el enlace al video:

-   **[Aprende VS Code ahora! | curso completo de VSCode desde CERO](https://www.youtube.com/watch?v=Ei1y51K8jQk)**

También te proporciono otro video que será útil una vez hayas utilizado **Visual Studio Code** por un tiempo. En este video, aprenderás a aplicar configuraciones personalizadas:

-   **[Cómo configurar VSCode para que sea ASOMBROSO! 😎🤓 | Extensiones, Tips y temas](https://www.youtube.com/watch?v=HiVnGgYudLY)**

### Recursos

Aquí tienes una serie de recursos que te simplificarán el proceso de desarrollo con **Visual Studio Code**:

-   Esta imagen muestra todos los atajos de teclado disponibles en **Visual Studio Code**:
    ![VSCode Shortcuts](https://code.visualstudio.com/assets/docs/getstarted/tips-and-tricks/KeyboardReferenceSheet.png)

### Consejos, Trucos y Buenas Prácticas

Además, te ofrezco una extensa recopilación de consejos, trucos y buenas prácticas relacionadas con **HTML**. Te recomiendo tomar nota de esta valiosa compilación, ya que será de gran ayuda en tus labores de programación:

-   Aquí tienes una amplia tabla de atajos de teclado muy útiles que te permitirán optimizar tu uso de **Visual Studio Code**:

    | Atajo                                 | Acción                                      |
    | ------------------------------------- | ------------------------------------------- |
    | Alt + Shift + A                       | Convertir la selección en un comentario     |
    | Alt + Click                           | Selección múltiple                          |
    | Alt + Shift + Up/Down                 | Duplicar las líneas                         |
    | Alt + Up/Down                         | Mover las líneas hacia arriba/abajo         |
    | Alt + Z                               | Activar o desactivar el "Word wrap"         |
    | Ctrl + ,                              | Abrir la configuración de preferencias      |
    | Ctrl + .                              | Abrir el menú de contexto                   |
    | Ctrl + /                              | Convertir la línea en un comentario         |
    | Ctrl + D                              | Seleccionar la palabra actual               |
    | Ctrl + D, Ctrl + D (Multiples veces)  | Seleccionar y editar palabras siguientes    |
    | Ctrl + F                              | Buscar                                      |
    | Ctrl + F4                             | Cerrar el archivo actual                    |
    | Ctrl + H                              | Buscar y reemplazar                         |
    | Ctrl + K (en la terminal)             | Limpiar la terminal                         |
    | Ctrl + K + P (Ctrl + Tab)             | Seleccionar el archivo abierto              |
    | Ctrl + K + W                          | Cerrar todos los archivos abiertos          |
    | Ctrl + P                              | Seleccionar un archivo                      |
    | Ctrl + Right/Left                     | Moverse entre palabras                      |
    | Ctrl + S                              | Guardar el archivo actual                   |
    | Ctrl + Shift + P                      | Ejecutar comandos de **Visual Studio Code** |
    | Ctrl + Space                          | Activar sugerencias (Intellisense)          |
    | Ctrl + Y                              | Rehacer la última acción deshecha           |
    | Ctrl + Z                              | Deshacer la última acción                   |
    | Ctrl + `                              | Abrir la Terminal                           |
    | Del                                   | Eliminar el carácter siguiente              |
    | End                                   | Ir al final de la línea                     |
    | Home                                  | Ir al principio de la línea                 |
    | Shitf + Tab (Seleccion + Shitf + Tab) | Disminuir la indentación                    |
    | Tab (Seleccion + Tab)                 | Aumentar la indentación                     |

-   Si deseas crear atajos de teclado personalizados en Visual Studio Code, sigue estos pasos:

    1. Accede a las preferencias a través del menú "Archivo", selecciona "Preferencias" y luego "Atajos de Teclado". También puedes usar el atajo rápido `Ctrl + K Ctrl + S`.

    2. Busca el comando para el cual deseas crear un atajo. Edita su atajo actual o crea uno nuevo haciendo clic en el símbolo "+" en la parte superior.

    3. Define la combinación de teclas para el atajo personalizado, utilizando **Ctrl**, **Shift**, **Alt** junto con otras teclas. Asegúrate de evitar conflictos con atajos existentes.

    4. Una vez hecho, guarda las modificaciones en el archivo de atajos de teclado. Verifica el funcionamiento del nuevo atajo en tu proyecto para asegurarte de que se comporte como esperabas.

-   El término "Snippet" se utiliza en programación para referirse a fragmentos pequeños y reutilizables de código fuente, código binario o texto. Existen Snippets predefinidos para casi todas las tecnologías, creados por la comunidad, que puedes encontrar en la sección de extensiones. Si deseas personalizar uno, sigue estos pasos: Presiona `Ctrl + Shift + P`, luego selecciona `Snippets: Configure User Snippets`, escribe el lenugaje al que deseas aplicar el Snippet. Encontrarás una breve explicación allí. Si aún tienes dudas, en el video del curso de **Visual Studio Code** en la parte 48:50 se explica con más detalle cómo establecer los Snippets.

Y eso es todo en cuanto al editor de código. Ahora cuentas con las herramientas y el conocimiento necesarios para comenzar a practicar la escritura de código y mejorar significativamente tu velocidad al programar.
