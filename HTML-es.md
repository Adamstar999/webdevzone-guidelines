# HTML

**HTML**, siglas en inglés de _**HyperText Markup Language**_ (‘lenguaje de marcado de hipertexto’), hace referencia al lenguaje de marcado para la elaboración de páginas web. Es un estándar que sirve de referencia del software que conecta con la elaboración de páginas web en sus diferentes versiones, define una estructura básica y un código (denominado código **HTML**) para la definición de contenido de una página web, como texto, imágenes, videos, juegos, entre otros.

## Guía

A continuación, te presentaré algunos recursos que te serán de gran ayuda para aprender **HTML**:

### Cursos de HTML

En este video, a pesar de su duración, descubrirás cómo utilizar **HTML**. Obtendrás consejos, conocerás buenas prácticas y accederás a valiosos recursos. Aunque extenso, es una fuente completa e imprescindible para dar inicio a tu aventura en el mundo del desarrollo web:

-   **[Curso HTML & CSS (1/5): Fundamentos HTML - jonmircha](https://www.youtube.com/watch?v=-oK6zL01fNM)**

### Recursos

Aquí te proporciono una serie de recursos que te facilitarán el proceso de desarrollo con **HTML**:

-   Descubre una página que te brinda iconos e imágenes en formato **SVG** de forma gratuita: **https://www.svgrepo.com/**
-   Explora una página que presenta una tabla de etiquetas **HTML**, inspirada en la tabla periódica de elementos químicos: **https://madebymike.github.io/html5-periodic-table/**
-   Accede a un **CDN** gratuito y de código abierto (un conjunto de servidores distribuidos en diferentes regiones geográficas que optimizan la entrega de contenido web): **https://cdnjs.com/**
-   Sumérgete en esta página que ofrece consejos sobre las mejores prácticas de **HTML** y **CSS**: **https://codeguide.co/**

### Consejos, Trucos y Buenas Prácticas

Además, te brindo una amplia recopilación de consejos, trucos y buenas prácticas relacionados con **HTML**. Te aconsejo tomar nota de esta valiosa compilación, ya que será de gran ayuda en tus labores de programación:

-   No confíes solo en el atributo **required**; implementa validaciones del lado del servidor para una mayor seguridad.

-   Si utilizas caracteres especiales básicos **(<, >, &, ")** directamente en el código **HTML**, funcionará correctamente. Sin embargo, al operar con código **JavaScript** o **PHP**, o si no se están mostrando correctamente en la web, necesitarás utilizar terminaciones específicas para insertar estos símbolos. Aquí están las terminaciones correspondientes:
    | Terminaciones | Símbolos |
    | ------------- | -------- |
    | `&lt;` | < |
    | `&gt;` | > |
    | `&amp;` | & |
    | `&quot;` | " |

-   Restringe el empleo de la etiqueta **iframe** a un máximo de 2 por página para evitar posibles impactos adversos en el rendimiento.

-   Para agilizar las etiquetas **iframe** procedentes de YouTube, puedes aprovechar el sitio web **https://tube.rvere.com/**. Este sitio carga las dependencias requeridas para reproducir el video únicamente cuando presionas el botón de reproducción, en lugar de cargarlas al abrir la página. Obtendrás un código que deberás sustituir en lugar de tu **iframe** actual.

-   Recuerda que en un documento **HTML** solo debe existir un elemento **h1**.

-   Incluye una URL canónica en tu página web para mejorar su posicionamiento y permitir que **Google** indexe tu página de manera precisa.

-   El favicon solo es funcional en navegadores y no en dispositivos móviles. Si deseas que funcione en móviles, utiliza `<link rel="apple-touch-icon" href="img/favicon.png">`.

-   En general, es preferible emplear imágenes en formato **SVG** o **WEBP** en tu sitio web en lugar de **PNG** o **JPG**. Las razones son amplias, por lo que te dejo un artículo que profundiza en este tema: **https://ed.team/blog/que-imagenes-debes-usar-en-tu-web-jpg-png-svg-o-webp**.

-   Evita abusar de la etiqueta **div** y en su lugar, prefiere utilizar etiquetas semánticas como **main**, **section**, **article**, entre otras. Esto contribuirá a mantener un código más limpio y estructurado.

-   Siempre añade el atributo de idioma **lang** a la etiqueta **html**. Esto ayuda a las herramientas de síntesis de voz a determinar las pronunciaciones adecuadas y a las herramientas de traducción a aplicar las reglas correctas.

-   La etiqueta **title** debe tener entre 55 y 65 caracteres, mientras que la etiqueta **description** no debe exceder los 165 caracteres para un óptimo posicionamiento de la página.

-   Para una legibilidad óptima del código, los atributos **HTML** deben seguir este orden específico:

    1. class
    2. id, name
    3. data-
    4. src, for, type, href, value
    5. title, alt
    6. role, aria-
    7. tabindex
    8. style

---

-   Verifica la accesibilidad de tu sitio web utilizando **[Page Speed Insights](https://pagespeed.web.dev)** para garantizar una experiencia de usuario óptima.

-   Si alguna vez tienes dudas acerca de la compatibilidad de una funcionalidad de **HTML** o **CSS** en distintos navegadores, puedes verificarlo en el sitio **https://caniuse.com/**.

-   Utiliza `tabindex="0"` para crear elementos interactivos que se puedan navegar con la tecla Tab, sin alterar el orden de tabulación actual.

-   Evita incluir una barra oblicua final en elementos que se cierran automáticamente. Según la especificación **HTML5**, esta barra es opcional.

-   Un atributo booleano es aquel que no requiere un valor declarado. Mientras **XHTML** exigía declarar un valor, **HTML5** no lo necesita.

Y eso es todo en relación a **HTML**. Aún quedan otros dos fundamentos esenciales para la web: **CSS** y **JavaScript**. Aprenderás cómo dominarlos en sus secciones respectivas.
