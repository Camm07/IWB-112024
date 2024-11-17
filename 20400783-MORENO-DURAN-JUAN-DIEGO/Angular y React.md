# ANGULAR Y REACT

## Angular

### ***¿Qué es?***
Es un framework de ingeniería de software de código abierto que se utiliza para crear aplicaciones web de una sola página. Los desarrolladores también lo utilizan para crear menús animados para páginas web HTML.
El framework es una creación de los ingenieros de Google, Misko Hevery y Adam Abrons. Google lanzó oficialmente la primera versión, AngularJS, en 2012, y la ha mantenido desde entonces.
Antes del lanzamiento de AngularJS, había otras formas de crear páginas dinámicas. Sin embargo, no eran tan convenientes como este framework.

AngularJS usa la arquitectura Modelo-Vista-Controlador (MVC), que se usa en el desarrollo de aplicaciones web.

Este tipo de arquitectura consta de:

- Modelo: la estructura de datos que administra la información y recibe información del controlador
- Vista: la representación de la información
- Controlador: responde a la entrada e interactúa con el modelo

En el contexto de AngularJS, el modelo es el framework, mientras que la vista es HTML y el control es JavaScript.

### ***Características***

1. Uso de DOM regular
Un Document Object Model (DOM) es un documento XML o HTML que tiene una estructura de árbol en la que cada nodo representa una parte del documento. Angular hace uso de DOM regular, lo que permite una mejor organización conforme avanza el desarrollo web.

2. Enlace de datos o data binding
El enlace de datos es un proceso con el que los usuarios pueden manipular elementos de una página web a través de un navegador. Entre sus principales ventajas es que no requiere secuencias de comandos ni programaciones complejas, además de que emplea HTML dinámico. También permite una mejora en la visualización de una página web, sobre todo cuando contiene una gran cantidad de datos.

3. Compatibilidad móvil y de escritorio
Como ya lo mencionamos anteriormente, Angular funciona tanto para el desarrollo de aplicaciones móviles como de escritorio. Esto también significa que puede ejecutarse en la mayoría de navegadores web.

4. Velocidad y rendimiento
Angular cuenta con código de generación que permite convertir tus plantillas en códigos altamente optimizados. Esto te ofrece todos los beneficios del código escrito a mano con la productividad de un marco.

De igual manera, allana el camino para los sitios que optimizan para SEO y sus aplicaciones angulares se cargan rápidamente. Esto ofrece una división de código automática para que solo cargues el código que necesitas para representar la vista que requieres.

5. Productividad
Angular permite la creación rápida de vistas de interfaz de usuarios con una sintaxis de plantilla muy sencilla y eficaz. Además, con sus herramientas de líneas de comandos puedes comenzar a construir en menor tiempo y agregar componentes, pruebas e implementaciones al instante.

6. Enlace bidireccional de datos
Angular enlaza JavaScript y HTML, y una de sus principales ventajas es que el código de ambos está sincronizado, lo que ahorra mucho tiempo para los desarrolladores web.

### ***Ventajas***

1. Fácil de usar: Angular es fácil de usar y comprender. Tiene una sintaxis simple y es fácil de aprender.

2. Modular: Angular es un marco modular, lo que significa que se puede dividir en componentes más pequeños que se pueden reutilizar y combinar para crear aplicaciones más grandes.

3. Cuenta con una estructura y control de los proyectos: a esto se suma una gran comunidad para solucionar cualquier problema.

4. Arquitectura MVC Angular utiliza la arquitectura Model-View-Controller (MVC), que facilita el desarrollo y mantenimiento de aplicaciones grandes.

### ***Desvantajas***

1. Complejidad: Angular es un marco complejo y puede ser difícil de aprender para los desarrolladores que son nuevos en los marcos de JavaScript.

2. Rendimiento: las aplicaciones angulares pueden ser lentas, especialmente en comparación con otros marcos como React o Vue.

3. Documentación deficiente: la documentación de Angular no es tan completa

4. Curva de aprendizaje pronunciada: Angular tiene una curva de aprendizaje pronunciada y requiere que los desarrolladores tengan una buena comprensión de TypeScript, HTML y CSS.

## React

### ***¿Qué es?***
React es una librería para crear interfaces de usuarios con código abierto, es decir, que está a disposición de cualquier programador para que use sus recursos e incluso haga colaboraciones. Esta biblioteca fue lanzada en el año 2013, por los desarrolladores de Facebook, con base en el lenguaje JavaScript.

Actualmente es una de las herramientas más utilizadas para crear páginas web porque su uso es bastante amigable y fácil de aprender. Sobre todo si ya se tienen conocimientos del lenguaje JavaScript, ya que la sintaxis que usa es muy similar. Cabe mencionar que necesita otros software para complementar las funciones de un sitio web, porque no es esencialmente un framework.

### ***Características***

1. Lenguaje JSX
La sintaxis que usa React es el JavaScript XML (JSX), el cual es una combinación del lenguaje HTML y el JavaScript, por lo que también se considera una extensión. Así que la relación que hay entre estos es bastante estrecha. Algunos programadores han afirmado que solamente se diferencian por detalles y que puede coincidir en más de un 90 % el código del JSX con el de JavaScript. Así que las personas que ya dominen este lenguaje se adaptarán muy fácil a React.

2. Componentes
Regularmente dentro de la programación web se manejan tres carpetas: la de la estructura de la página web (HTML), la de la presentación de la interfaz (CSS) y la del comportamiento de la misma (JS). Por su lado, React decidió juntar todas estas en un mismo lugar, de manera dinámica, para dar lugar a los componentes. Estos son partes de la interfaz del usuario que es independiente y que se puede reutilizar en otro lugar del sitio web. Esta es una de las características más sobresalientes. Asimismo, existen dos tipos de componentes:

    -Componentes funcionales. Son los más usados: representan una función de JavaScript, retornan a un elemento JSX de React, comienzan con mayúscula y pueden recibir valores.

    -Componentes de clase. Se refiere a los componentes que están escritos en JavaScript moderno de una manera más elaborada: retornan a un elemento JSX a través de un método render y también es posible que se les asigne valores.

3. Ciclos de vida
Dentro de React los componentes pasan por una serie de etapas durante su creación. Regularmente se divide en tres fases esenciales: montaje, utilización y desmontaje. A través de ellas suceden los siguientes métodos que se ejecutan para programar una interfaz de usuario.

    -Constructor. Es donde se crea el estado de un componente, enlaza eventos y setea variables globales.
    -ComponentWillMount. Se ejecuta antes que el componente sea montado, permite modificarlo y limpia la demanda de dependencias. No hace llamados a API ni suscripción a eventos.
    -Render. Aquí se toman las propiedades, el estado y el contexto. Es cuando ya se empieza a mostrar la imagen de la interfaz y refleja los cambios realizados en ella.
    -ComponentDidMount. Este método se ejecuta cuando el componente ya se ha renderizado; es ideal para llamar a API e iniciar la carga remota de datos, enlazar eventos y modificar el estado.
    -Actualización. Se puede repetir varias veces para realizar cambios en las propiedades de los estados, renderizar los componentes y preparar actualización del diseño de interfaz de usuario (UI).
    -Desmontar. Se aplica con el método ComponentWillUnmount para dejar de escuchar eventos, quitarse de un WebSocket y cancelar peticiones HTTP. Es una especie de limpieza.
    -ComponentDidCatch. También conocido como control de errores, se activa cuando detecta equivocaciones al montar un componente.

4. Virtual DOM
El virtual DOM es una característica de React que permite que el rendimiento de la página web no se vea afectada por las actualizaciones y que estas, a su vez, se mantengan bien reflejadas en el modelo en objetos para la representación de documentos (DOM).

Normalmente, para que los cambios realizados en los estados de una página web se vean en la interfaz gráfica es necesario un proceso complejo, largo y costoso. Así que el virtual DOM se encarga de actuar como una memoria intermediaria entre las actualizaciones al estado de la página y el DOM real para renderizar los menos cambios posibles.

### ***Ventajas***

1. Fácil de aprender. React es mucho más fácil de aprender debido a su simplicidad en términos de sintaxis. Los ingenieros sólo tienen que confiar en sus conocimientos de redacción de HTML. No es necesario aprender TypeScript con Angular.
2. Alto nivel de flexibilidad y máxima «capacidad de respuesta».
3. DOM virtual (Document Object Model) que convierte los documentos en formato HTML, XHTML o XML en una estructura de árbol más manejable para los navegadores mientras analiza los diferentes elementos de la aplicación.
4. Combinado con ES6/7, React JS puede trabajar fácilmente con una gran carga.
5. Vinculación de datos descendente, lo que significa que con este tipo de flujo de datos, los elementos «hijos» no pueden afectar a los datos «padres».
6. Biblioteca JavaScript 100% de código abierto con frecuentes actualizaciones y mejoras de desarrolladores de todo el mundo.
7. Marco muy ligero, ya que los datos del lado del usuario pueden presentarse simultáneamente en el servidor.
8. La migración entre versiones suele ser muy sencilla, ya que Facebook proporciona «codemods» (cambios de código) para automatizar gran parte del proceso.

### ***Desventajas***

1. Falta de documentación oficial. La alta velocidad de desarrollo de React JS deja poco espacio para una documentación adecuada, que es un poco caótica ya que diferentes desarrolladores contribuyen sin un enfoque común.
2. No hay un patrón de desarrollo, por lo que tenemos que tomar demasiadas decisiones.
3. Se necesita mucho tiempo para dominarlo, así como un profundo conocimiento de cómo integrar las interfaces de usuario en los frameworks MVC.