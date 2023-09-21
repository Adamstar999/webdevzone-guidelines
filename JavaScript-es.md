# JavaScript

**JavaScript** es un lenguaje de programación o secuencias de comandos que posibilita la creación de funciones complejas en páginas web. Cuando una página web va más allá de simplemente mostrar información estática y comienza a ofrecer actualizaciones oportunas de contenido, mapas interactivos, animación de gráficos _2D_/_3D_, reproducción de videos con capacidad de desplazamiento, entre otros, es muy probable que **JavaScript** esté desempeñando un papel fundamental. Este lenguaje representa la tercera capa en el conjunto de tecnologías web estándar, complementando a las dos anteriores (**HTML** y **CSS**) que ya hemos explorado en secciones anteriores.

**JavaScript** es oficialmente considerado un lenguaje de programación, ya que **HTML** se utiliza para definir la estructura de un sitio web y **CSS** para posicionar y dar estilo a esta estructura. Ninguno de estos dos lenguajes está destinado a la programación en el sentido tradicional. Los lenguajes de programación, en cambio, permiten el uso de variables, funciones, bucles y estructuras condicionales, tal como lo hace **JavaScript**.

Este lenguaje posee una amplia gama de aplicaciones y herramientas. Se encuentra entre los lenguajes más populares y queridos en la comunidad de desarrollo, aunque también atrae cierta crítica por ciertos aspectos distintivos. Estas diferencias se vuelven más notables a medida que adquieres experiencia con otros lenguajes de programación. Te recomiendo que, después de dominar **JavaScript**, consideres aprender otro lenguaje como **Python**, **C#**, **Java**, entre otros. Esto ampliará tu comprensión del mundo de la programación y te permitirá apreciar las similitudes y diferencias entre los diversos lenguajes.

En mi experiencia personal, ampliar mi conocimiento a otros lenguajes, como **Python** y **C#**, después de haber trabajado con **JavaScript**, proporcionó una nueva perspectiva y enriqueció mi comprensión de la programación. Sin embargo, es importante destacar que intentar dominar demasiados lenguajes puede llevar a la confusión y a la falta de dominio en ninguno de ellos, lo que puede limitar tu progreso. Por lo tanto, es recomendable enfocarse en uno o dos lenguajes que domines profundamente y tener un conocimiento básico de otros. Esto te permitirá concentrarte en los lenguajes que realmente importan para tus objetivos y proyectos.

Además, es relevante mencionar que **JavaScript** no se limita al _Front-end_. También se utiliza en el _Back-end_ a través de **Node.js**, que permite ejecutar código **JavaScript** en el servidor. **Node.js** compila el código **JavaScript** para que sea legible por la máquina. Aunque principalmente se asocia con el _Back-end_, algunas de sus características, como el gestor de paquetes **npm**, también se aplican en el _Front-end_. Exploraremos más sobre **Node.js** en la secciónes dedicadas al _Back-end_.

Tendrás la oportunidad de profundizar en el aprendizaje de este lenguaje y su aplicación a través de los recursos que te proporcionaré a continuación. Estos recursos te ayudarán a comprender cómo utilizar **JavaScript** en su totalidad.

## Guía

A continuación, te presentaré algunos recursos que te serán de gran ayuda para aprender **JavaScript**:

### Cursos de JavaScript

Cuando se trata de dominar y aprender **JavaScript**, es importante tener en cuenta que requerirá más esfuerzo y tiempo. Existen diversas formas y recursos para adentrarse en el mundo de **JavaScript**, pero quiero destacar esta lista de reproducción en _YouTube_ que considero uno de los más completos y detallados que he encontrado. Dado que el contenido es extenso, te recomiendo planificar cómo vas a organizar y aprovechar todo el código e información proporcionados en esta guía:

-   **[Curso JavaScript](https://www.youtube.com/playlist?list=PLvq-jIkSeTUZ6QgYYO3MwG9EMqC-KoLXA)**

### Recursos

Aquí tienes una selección de videos relacionados con **JavaScript**, enfocados en buenas prácticas y consejos para programar de manera efectiva:

-   **[¡Aprende los nuevos métodos de Array para JavaScript!](https://www.youtube.com/watch?v=TJKAGh9jzx4)**

Adicionalmente, te proporciono enlaces a páginas web que te serán útiles para facilitar tu proceso de programación:

-   Página de consejos y buenas prácticas de **JavaScript**: **https://code.tutsplus.com/es/24-javascript-best-practices-for-beginners--net-5399t**

### Consejos, Trucos y Buenas Prácticas

Además, te brindo una amplia recopilación de consejos, trucos y buenas prácticas relacionados con **JavaScript**. Te aconsejo tomar nota de esta valiosa compilación, ya que será de gran ayuda en tus labores de programación:

-   Opta por utilizar **===** en lugar de **==**, ya que **==** solo verifica el valor, sin considerar el tipo de dato, mientras que **===** evalúa tanto el valor como el tipo de dato. Aquí tienes un ejemplo:

    ```javascript
    let a = 3;
    let b = "3";

    console.log(a == 3); // Devolverá verdadero
    console.log(a === 3); // Devolverá verdadero

    console.log(a == b); // 3 == "3" Devolverá verdadero
    console.log(a === b); // 3 === "3" Devolverá falso
    ```

-   Evita el uso de **eval**, ya que no solo reducirá significativamente el rendimiento de tu script, sino que también representará un riesgo de seguridad al otorgar demasiados privilegios al texto proporcionado.

-   Siempre prefiere la palabra clave **let** en lugar de **var** al declarar variables. Para una explicación breve y concisa, puedes consultar este corto video en _YouTube_: **[¿Uso let o var? | #JavaScript](https://www.youtube.com/shorts/cFD9bB3UEtY)**.

-   Aunque pueda parecer innecesario inicialmente, te aseguro que comentar tu código de manera efectiva es esencial. Imagina regresar a tu proyecto meses después y descubrir que no recuerdas el propósito de cada fragmento de código. Además, considera la posibilidad de que un colega deba revisar tu trabajo; sin comentarios, podrían perderse en la complejidad. Por estas razones, los comentarios son valiosos e incluso cruciales. Por lo tanto, no olvides agregar comentarios siempre a las secciones clave de tu código.

-   Aunque técnicamente es posible omitir los puntos y comas en tu código, es recomendable evitar esta práctica. Esto podría causar problemas y dificultades en el futuro. Por lo tanto, sigue utilizando puntos y comas al final de cada línea para garantizar la claridad y la interpretación correcta del código.

-   El uso de _librerías_ o _frameworks_ puede facilitar el desarrollo de tu aplicación, pero evita depender en exceso de ellos. Esto podría afectar el rendimiento y reducir tu habilidad para programar. Úsalos sin problemas, siempre y cuando puedas programar lo que ofrece la _librería_ o el _framework_ por ti mismo y si su impacto es más positivo que negativo en tu caso.

Y así concluimos nuestra exploración de **JavaScript**. Ahora has adquirido las tres bases fundamentales de la programación web. Lo que exploraremos a continuación son tecnologías, librerías y herramientas que te capacitarán para mejorar significativamente el desarrollo y aumentar tus posibilidades de encontrar trabajo, siempre y cuando tengas el conocimiento y la experiencia en estas opciones.
