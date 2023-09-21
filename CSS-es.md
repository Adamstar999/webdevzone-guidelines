# CSS

**CSS**, cuyas siglas en inglés significan _Hojas de Estilo en Cascada_ (**Cascading Style Sheets**), es un lenguaje que gobierna el diseño y la presentación de las páginas web, determinando su apariencia cuando los usuarios las visitan. Trabaja en conjunto con **HTML**, que maneja el contenido fundamental de los sitios.

El término _en cascada_ se emplea debido a que puedes tener múltiples hojas de estilo, y una puede heredar propiedades de otras.

Mediante **CSS**, puedes establecer reglas para indicar a tu sitio web cómo mostrar la información y separar las instrucciones para los elementos de estilo (como tipografías, colores y tamaños) de aquellas que configuran el contenido.

## Guía

A continuación, te presentaré algunos recursos que te serán de gran ayuda para aprender **CSS**:

### Cursos de CSS

En esta serie de videos principal acerca de **CSS**, tendrás todo lo necesario para programar código **CSS** de manera eficiente y rápida. Además, se proporcionan consejos y trucos sumamente valiosos. Aunque existen numerosos cursos en **YouTube**, personalmente considero que los videos producidos por Jonmircha son especialmente completos. Sin embargo, si prefieres explorar otros creadores de contenido educativo, te sugiero investigar más sobre cursos disponibles en **YouTube** o incluso considerar cursos de pago según tu preferencia. Estos recursos audiovisuales te brindarán lo necesario para dominar **CSS**:

1. **[Curso HTML & CSS ( 2 / 5 ): Fundamentos CSS - jonmircha](https://www.youtube.com/watch?v=K3xmRF8ab1o)**
2. **[Curso HTML & CSS ( 3 / 5 ): Unidades y Estilos CSS - jonmircha](https://www.youtube.com/watch?v=p_lT7AgpEMU)**
3. **[Curso HTML & CSS ( 4 / 5 ): Efectos Visuales y Movimiento en CSS - jonmircha](https://www.youtube.com/watch?v=mVhoGXkDbMw)**
4. **[Curso HTML & CSS ( 5 / 5 ): Responsive Design y Arquitectura CSS - jonmircha](https://www.youtube.com/watch?v=udGrXWeJp1Y)**
5. **[Curso Flexbox CSS](https://www.youtube.com/playlist?list=PLvq-jIkSeTUbQc3dGsssp8lxAi5npMrys)**
6. **[Curso Grid CSS](https://www.youtube.com/playlist?list=PLvq-jIkSeTUY628cyd9LVbXSXi2xG9mUl)**

Además, te proporciono una serie de videos que, si bien no son obligatorios, te ayudarán a agilizar el aprendizaje y a obtener una comprensión más profunda de ciertos aspectos de **CSS**:

-   **[¡El programa que TODO DESARROLLADOR debería tener INSTALADO! 🔨 9 utilidades en 1 para el día a día](https://www.youtube.com/watch?v=kVQguYQ5IsA)**
-   **[CSS Grid vs Flexbox - Cuando usar uno u otro.](https://www.youtube.com/watch?v=6qko7Nbe8YA)**
-   **[APRENDE a usar la METODOLOGÍA BEM](https://www.youtube.com/watch?v=6LUz0MnNCiA)**
-   **[APRENDE a usar AFTER y BEFORE en CSS](https://www.youtube.com/watch?v=VsYqbdBOP50)**
-   **[SocraTips - Cómo funcionan las CONTAINER QUERIES de CSS - SocraTech](https://www.youtube.com/watch?v=Mg6HS84QJ9A)**
-   **[¿Qué unidades de medida usar en CSS? 🤔](https://www.youtube.com/watch?v=EbsyJrtJgpw)**

### Recursos

Aquí te proporciono una serie de recursos que te facilitarán el proceso de desarrollo con **CSS**:

-   Descubre una página que te ofrece iconos **CSS** predefinidos: **https://css.gg/app**.
-   Explora un sitio web que brinda diversas herramientas para simplificar problemas y desafíos de **CSS**: **https://bennettfeely.com**.
-   Aquí puedes visualizar fuentes de diversos estilos y tamaños para después exportarlas a tu código **CSS**: **https://typescale.com**.
-   Utiliza este convertidor de píxeles a ems, que también te permite establecer una fuente base: **http://pxtoem.com**.
-   Explora estas dos páginas para descubrir una amplia gama de colores, paletas y crear gradientes. Una se centra en colores estándar: **https://hue.tools/info**, y la otra en gradientes: **https://cssgradient.io**.
-   Accede a la página oficial de Google Fonts para seleccionar entre una amplia variedad de fuentes para tu sitio web. Sin embargo, recuerda no abusar de demasiadas fuentes, ya que esto puede afectar negativamente el rendimiento: **https://fonts.google.com**.
-   Explora ejemplos prácticos de media queries y diseño responsivo en esta página: **https://mediaqueri.es**.
-   Sumérgete en el contenido de este desarrollador Front-End que ofrece consejos valiosos y herramientas útiles, como un generador de sombras en **CSS** y más: **https://www.joshwcomeau.com**.
-   Sumérgete en esta página que ofrece consejos sobre las mejores prácticas de **HTML** y **CSS**: **https://codeguide.co/**.

### Consejos, Trucos y Buenas Prácticas

Además, te brindo una amplia recopilación de consejos, trucos y buenas prácticas relacionados con **CSS**. Te aconsejo tomar nota de esta valiosa compilación, ya que será de gran ayuda en tus labores de programación:

-   Al imprimir el contenido de páginas web, puedes aprovechar una media query que te permite personalizar los estilos y el contenido **HTML** para que se apliquen al imprimir. Si deseas aprender cómo utilizarla, te recomiendo este video tutorial: **https://www.youtube.com/watch?v=CAgLAeykOyU**.

-   Comúnmente, se utilizan los siguientes puntos de interrupción según la resolución del dispositivo:

    | Tamaños | Ámbito                                                                                                       |
    | ------- | ------------------------------------------------------------------------------------------------------------ |
    | 320px   | Dispositivos con pantallas pequeñas, como teléfonos en modo vertical.                                        |
    | 480px   | Dispositivos con pantallas pequeñas, como teléfonos, en modo horizontal.                                     |
    | 600px   | Tabletas pequeñas, como Amazon Kindle (600×800) y Barnes & Noble Nook (600×1024), en modo vertical.          |
    | 768px   | Tabletas de diez pulgadas como iPad (768×1024), en modo vertical.                                            |
    | 1024px  | Tabletas como iPad (1024×768), en modo horizontal, y algunas pantallas de portátiles, netbooks y escritorio. |
    | 1200px  | Pantallas panorámicas, principalmente portátiles y de escritorio.                                            |

-   En las media queries, es más recomendable usar las propiedades min-width y max-height con valores en ems en lugar de pixeles. Aunque los pixeles se consideran unidades absolutas, en realidad son relativas a la resolución de pantalla del dispositivo. Si el dispositivo tiene una densidad mayor, la proporción de los pixeles cambia. Por ello, es importante que los puntos de quiebre (breakpoints) de las media queries se expresen en ems, que son unidades relativas y proporcionales. Aquí tienes la conversión de px a em, basada en la fuente base de 16px (320px / 16px = 20em):

    | PX     | EM     |
    | ------ | ------ |
    | 320px  | 20em   |
    | 480px  | 30em   |
    | 600px  | 37.5em |
    | 768px  | 48em   |
    | 1024px | 64em   |
    | 1200px | 75em   |

-   Restablecer el valor de `box-sizing` a `border-box` en **CSS** asegura que el tamaño total de un elemento incluya tanto el relleno como el borde, simplificando el diseño, evitando desbordamientos inesperados y ofreciendo un mayor control sobre las dimensiones. Además, facilita la integración con frameworks y librerías de **CSS**.

-   En el desarrollo web, es preferible aplicar estilos a clases en lugar de identificadores. Esto permite reutilizar estilos en varios elementos, simplifica el mantenimiento al centralizar los cambios, evita conflictos de especificidad, mantiene una clara separación entre estructura y diseño, se alinea con los estándares de la comunidad y ofrece una mayor flexibilidad para la colaboración y escalabilidad en proyectos grandes.

-   Este es el orden recomendado de las pseudo-clases de un enlace:

    1. **:link**
    2. **:hover**
    3. **:active**
    4. **:visited**

-   Limita el uso de un sistema de color en el proyecto actual para mantener una estructura de colores más ordenada.

-   Emplea propiedades lógicas como `inline` y `block`. Dado que no todos los idiomas siguen la dirección izquierda a derecha del inglés, es crucial contar con un modo de escritura adaptable. Las propiedades lógicas permiten brindar apoyo a idiomas que pueden escribirse en sentido horizontal o vertical (como chino, japonés y coreano). Además, suelen ser más breves y sencillas de redactar.

-   Ten en cuenta que si un elemento hijo tiene la propiedad `width` en porcentajes, el padre ocupará automáticamente el 100% del espacio disponible. Es importante gestionar esta interacción.

-   Limita el uso de declaraciones abreviadas a casos donde sea necesario establecer explícitamente todos los valores disponibles (como **background**, **font**, etc.). El abuso de propiedades abreviadas puede llevar a un código desordenado con anulaciones innecesarias y efectos secundarios no deseados.

-   Evita **@import**, ya que puede ralentizar la carga, añadir solicitudes adicionales y generar problemas inesperados. Es más recomendable importar hojas de estilo con la etiqueta **link** en el **HTML** o mediante el uso de preprocesadores.

-   Para mejorar la legibilidad, sigue un orden estructurado al declarar propiedades **CSS**. Puedes encontrar el orden sugerido en esta página: **https://markdotto.com/2011/11/29/css-property-order/**

-   Con el soporte de _**CSS** Color Levels 4_ en los navegadores principales, **rgba()** y **hsla()** ahora son equivalentes a **rgb()** y **hsl()**, lo que permite modificar los valores alfa en **rgb()** y **hsl()**. Aquí tienes un ejemplo: `color: rgb(255 255 255 / .65);`

-   Para lograr que toda la multimedia de tu página web sea flexible y se adapte al tamaño de su contenedor, puedes emplear la siguiente regla **CSS** (aunque hay otras formas según tus necesidades):

    ```css
    img,
    audio,
    video,
    iframe,
    canvas,
    svg,
    picture {
        max-width: 100%;
        height: auto;
    }
    ```

-   Si alguna vez tienes dudas acerca de la compatibilidad de una funcionalidad de **HTML** o **CSS** en distintos navegadores, puedes verificarlo en el sitio **https://caniuse.com/**.

-   Evita utilizar la unidad de medida **vw** para establecer un ancho de `100vw` en elementos, ya que esto podría causar desbordamientos horizontales, problemas en dispositivos pequeños y resultados inesperados en el diseño. Es preferible optar por unidades relativas como porcentajes, em's o rem's.

-   **Desktop First** y **Mobile First** son las dos estrategias principales del diseño responsivo para adaptar el contenido al tamaño de la pantalla. **Mobile First** se centra en dispositivos con pantallas más pequeñas, mientras que **Desktop First** se enfoca en las de mayor tamaño. En el diseño responsivo, es recomendable utilizar **Mobile First**, ya que prioriza la experiencia en dispositivos móviles, mejorando la velocidad de carga y la usabilidad en pantallas pequeñas. Luego, puedes expandir progresivamente el diseño para dispositivos más grandes, lo que resulta en una adaptabilidad eficiente y efectiva.

Y eso es todo en cuanto a **CSS**. Aún queda una última parte por aprender, que se llama **JavaScript**. Aprenderás cómo dominarlo en su sección respectiva.
