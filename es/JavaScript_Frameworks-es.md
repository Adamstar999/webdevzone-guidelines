# Frameworks de JavaScript

## Introducción

Los _frameworks_ llevan existiendo ya décadas y son básicamente conjuntos de código cuya premisa es facilitar el desarrollo de funciones o proyectos específicos.

Un ejemplo sencillo sería utilizar una librería para permitir que los elementos en la pantalla se puedan arrastrar con el ratón mientras se mantiene pulsado, y que el elemento permanezca en el lugar donde el usuario suelta el clic. Esta función se conoce como "_drag and drop_". Si bien esta función se puede programar con **JavaScript** puro, usar una librería puede ahorrarte tiempo al no tener que crearla desde cero.

También existen librerías o _frameworks_ más extensos y generales que permiten la creación de proyectos mucho más complejos. Los _frameworks_ y librerías actuales te brindan la capacidad de optimizar el desarrollo de una aplicación web desde el principio hasta el final y están orientados a la construcción de **SPA** (_Single Page Application_), que son páginas web de una sola página y no requieren visitar otros archivos **HTML** ni recargar la página, ya que todo el contenido se encuentra en una sola página y es completamente reactivo.

Antes de la era de los _frameworks_ y librerías modernas de **JavaScript** para la construcción de **SPA**, como **React**, **Vue**, entre otros, existió otra generación de herramientas, siendo la más popular en ese momento **jQuery**. Esta librería permitía la interacción de **JavaScript** con elementos **HTML**, controlar estilos y garantizar la compatibilidad con varios navegadores, minimizando errores. En su época, **jQuery** se erigía como una herramienta de gran utilidad.

Hoy en día, en proyectos actuales, no hay razón para emplear **jQuery**, ya que las funcionalidades que proporcionaba están ahora cubiertas por **JavaScript** de manera nativa. Sin embargo, sigue habiendo una abundancia de proyectos que aún utilizan **jQuery**, principalmente por ser costoso y laborioso actualizar a otro _framework_ o librería, especialmente en proyectos de gran envergadura. Para desarrolladores que trabajan por afición o como freelancers, el aprendizaje de **jQuery** no es necesario ni beneficioso en la actualidad. No obstante, en muchas empresas, el conocimiento de **jQuery** es un requisito para ciertas posiciones, lo que podría ampliar tus oportunidades laborales. Dominar **jQuery** es relativamente simple si ya comprendes el **DOM** de **JavaScript**.

Cubriremos **jQuery** aquí, pero recuerda que es completamente opcional y que no es comparable a las demás librerías, sino más bien una librería externa que te podría ayudar a tener más oportunidades de encontrar trabajo.

Es importante tener en cuenta que el uso excesivo de _frameworks_ y librerías puede llevar a un rendimiento más lento en tu aplicación debido a la carga adicional que el navegador debe procesar. Además, si tienes varias librerías en tu proyecto, pueden surgir problemas de compatibilidad difíciles de resolver. En esta sección nos enfocaremos principalmente en un _framework_ llamado **React**, aunque también mencionaremos aspectos y guías de otros _frameworks_.

## Tutorial

La lista de _frameworks_ y librerías es extensa y sigue creciendo cada año. Mencionaremos tres principales _frameworks_: **React**, **Vue** y **Angular**. Nos enfocaremos principalmente en **React**, y también mencionaremos a **jQuery**. Aunque existen otros _frameworks_, son menos utilizados y ofrecen menos oportunidades laborales. Sin embargo, si prefieres utilizar alguno de estos, eres libre de hacerlo, todos tienen sus ventajas y desventajas. Antes de hablar sobre los _frameworks_, te recomiendo ver un video que compara las diferencias entre ellos, lo cual te ayudará a entender cuál se adapta mejor a tus necesidades: **[Angular vs. React vs. Vue | ¿Cuál es mejor? ¿Cuál paga más?](https://www.youtube.com/watch?v=IWbl8SXsb7Q)**

### jQuery

**jQuery** es una librería antigua que ya no ofrece novedades, pero aún se utiliza bastante. Aquí tienes algunas guías por si quieres aprenderlo:

-   **[jQuery Tutorial Español - 💪 Curso de jQuery 2018 desde cero 💪](https://www.youtube.com/watch?v=DVN8NWppCN0)**
-   **[Documentación oficial de jQuery](https://api.jquery.com)**

### Angular

**Angular** es un _framework_ basado en componentes para crear aplicaciones web escalables, desarrollado por Google. Ofrece una colección de bibliotecas bien integradas que cubren una amplia variedad de características, como enrutamiento, administración de formularios, comunicación cliente-servidor y más. También proporciona un conjunto de herramientas para desarrolladores que facilitan el desarrollo, compilación, prueba y actualización del código fuente de la aplicación. **Angular** está basado en **TypeScript**, por lo que es importante saber usar este lenguaje para trabajar con **Angular**. Aquí tienes los recursos para aprenderlo:

-   **[Curso Angular en Español - Tutorial de Angular desde cero ▶️🤯](https://www.youtube.com/watch?v=i-oYrcNtc2s)**
-   **[Documentación oficial de Angular](https://angular.io/docs)**

### Vue

**Vue** es un _framework_ progresivo para construir interfaces de usuario. A diferencia de otros _frameworks_ monolíticos, **Vue** está diseñado desde cero para ser utilizado de manera incremental. La librería central se enfoca únicamente en la capa de visualización y es fácil de usar e integrar con otras librerías o proyectos existentes. **Vue** fue creado por Evan You, un ex empleado de Google, en el año 2014. Aquí tienes los recursos para aprenderlo:

-   **[💥 CURSO VUE y VUEX COMPLETO desde cero y práctico | Clon Trello](https://www.youtube.com/watch?v=Wd9dOIlTWCc)**
-   **[Documentación oficial de Vue](https://es.vuejs.org/v2/guide/)**

### React

**React** es una de las librerías más populares de **JavaScript** para el desarrollo de aplicaciones móviles y web. Creada por Facebook, **React** contiene una colección de fragmentos de código **JavaScript** reutilizables utilizados para crear interfaces de usuario llamadas componentes.

Es importante señalar que **React** no es un _framework_ de **JavaScript**. Esto se debe a que solo es responsable de renderizar los componentes de la capa de vista de una aplicación. **React** es una alternativa a _frameworks_ como **Angular** y **Vue**, que permiten crear funciones complejas. Aquí tienes los recursos para aprenderlo:

-   **[Curso React.js](https://www.youtube.com/playlist?list=PLvq-jIkSeTUZ5XcUw8fJPTBKEHEKPMTKk)**
-   **[Documentación oficial de React](https://react.dev/learn)**

También te proporciono algunos videos complementarios sobre **React**, que será el enfoque principal de aquí en adelante.

-   **[¿Qué es y cómo funciona useEffect? Hooks de React](https://www.youtube.com/watch?v=TBxpAhpQqYk)**
-   **[Principios SOLID en React.js (Buenas prácticas) con ejemplos prácticos](https://www.youtube.com/watch?v=jKdt-BnTTR0)**
-   **[Aprende a pasar una Prueba Técnica de React. Entiende useMemo, useCallback y useRef [Curso de React]](https://www.youtube.com/watch?v=GOEiMwDJ3lc)**
-   **[Pruebas y Accesibilidad - React Testing Library](https://www.youtube.com/watch?v=ZE4galFU5HU)**
-   **[¡Resuelvo Prueba Técnica de React para Juniors y Trainee!](https://www.youtube.com/watch?v=XYpadB4VadY)**
-   **[Cómo Consumir APIs en REACT como un PROFESIONAL](https://www.youtube.com/watch?v=6u1RHUoXIPI)**

No descarto la posibilidad de agregar contenido sobre otras librerías o _frameworks_ en el futuro, pero por ahora nos centraremos principalmente en **React**. Sin embargo, si prefieres utilizar otra opción, eres totalmente libre de explorar contenido en línea por tu cuenta y emplearlas, ya que todas son igualmente válidas.

## Recursos

-   Esto es una imagen de cómo deberían estar organizadas las carpetas de tus proyectos en **React**:
    **![Estructura de Proyectos con React](../assets/React%20SRC.jpg)**

## Consejos, Trucos y Buenas Prácticas

-   Puedes utilizar el componente `HashRouter` siempre y cuando haya casos de _URLs_ en tu página que presenten errores al acceder a ellas desde otro lugar. Esto suele suceder con hosting compartidos. Sin embargo, lo normal es usar siempre `BrowserRouter`.

## Ejercicios y Proyectos

### Angular

-   **[Angular | Ejemplos Practicos](https://www.youtube.com/playlist?list=PLo5lAe9kQrworYq5xJWBTtzPgyOUShZnY)**

### Vue

-   **[Proyectos Vue js](https://www.youtube.com/playlist?list=PLP07Cb8pDHCPIQlie1aD_D0HujvWRkrUW)**

### React

-   El canal de YouTube de **[JavaScript Mastery](https://www.youtube.com/@javascriptmastery)** te brinda videos para practicar proyectos cotidianos con las últimas tecnologías.

-   **[FreeCodeCamp](https://www.freecodecamp.org/learn/front-end-development-libraries/)** ofrece un curso con ejercicios prácticos y un certificado ampliamente reconocido.

-   **[🌔 Proyectos ReactJS](https://www.youtube.com/playlist?list=PL9c-AU5X8n1T4y1Y3VG-maQYyASZEg-4C)**

## Conclusión

Después de haber aprendido algún _framework_ o librería y haber practicado lo suficiente con él, serías capaz de no solo crear una página web con una estructura compleja y ordenada, sino que también tendrías el conocimiento necesario para empezar a buscar empleo. Aun así, habrá una sección para ayudarte en cuanto a este tema y qué hacer si no tienes contenido que incluir en tu currículum. Aún nos falta hablar de algunos aspectos más orientados al diseño, como los _frameworks_ de **CSS**. Sin embargo, en comparación con los _frameworks_ y librerías de **JavaScript**, son mucho más sencillos.
