## React

### ¿Qué es React?

React es una biblioteca de JavaScript para la creación de interfaces de usuario (UI) desarrollada por Facebook y una comunidad de desarrolladores de software libre. Su enfoque principal es construir componentes reutilizables para aplicaciones web y móviles, que faciliten la creación de interfaces dinámicas y eficientes.

### Historia

XHP, una librería de componentes para PHP influenció a Jordan Walke, un ingeniero de Facebook, a desarrollar el primer prototipo de React, llamado FaxJS, que tenía como objetivo mejorar el rendimiento de la interfaz de usuario. FaxJS fue utilizado en el feed de Noticias de Facebook y en Instagram, inicialmente. Fue hasta 2013 que se volvió de código abierto y en 2015 se introdujo React Native, una extensión para el desarrollo móvil. 

Con el paso de los años, React ha evolucionado hasta convertirse en lo que es hoy en día. Una de las librerías de desarrollo front-end más utilizadas.

### Características

¿Qué hace tan popular a React?

**Componentes**

- React divide la interfaz de usuario en pequeñas partes de código reutilizable, a las cuales llama **componentes**

**Virtual DOM**

- React mantiene un virtual DOM propio, lo que permite actualizaciones rápidas  y eficientes al comparar y entonces renderizar sólo los cambios necesarios.

**Declarativo**

- React describe cómo debe de comportarse la interfaz en un estado dado y maneja el DOM de manera eficiente para reflejar esos estados

**Flujo unidireccional**

- Los datos fluyen en una sola dirección (de componentes padres a hijos), lo que facilita la depuración y mantenimiento de código

**Hooks**

- Disponibles desde la versión 16.8, permiten usar estado y otras características de React sin escribir clases

**Extensibilidad**

- React puede integrarse facilmente con otras bibliotecas o frameworks, como Redux, Next.js y Material-UI

**Herramientas de desarrollador**

- Existen una extensión en el navegador (React Developer Tools) que ayudan al momento del desarrollo para depurar aplicaciones React.

### Ventajas

Gracias a sus componentes reutilizables promueve el desarrollo modular

Cuenta con una gran comunidad, haciendo disponibles una vasta cantidad de recursos, bibliotecas y soporte

Tiene un buen rendimiento gracias a su Virtual DOM

### Ecosistema

Debido a su tamaño, React cuenta con un ecosistema robusto:

1. **Herramientas complementarias**
    - React Router, para el manejo de rutas en aplicaciones React
    - Redux, para la gestión del estado global en aplicaciones grandes
    - Context API, como alternativa liviana a Redux
    - Material-UI, como biblioteca de componentes
2. **Frameworks basados en React**
    - Next.js, para el renderizado del lado del servidor
    - Gatsby.js, como framework enfocado en sitios estáticos
3. **Extensiones Móviles**
    - React Native, que permite usar React para la creación de aplicaciones móviles nativas para Android y iOS
4. Herramientas de Desarrollo
    - Create React App, herramienta oficial para la configuración rápida de proyectos React
    - Vite, como alternativa moderna y más rápida que Create React App

## Angular

### ¿Qué es Angular?

Angular es un framework de desarrollo web basado en TypeScript diseñado para la creación de aplicaciones web dinámicas de una sola página. Desarrollado por Google utilizado para construir aplicaciones con un enfoque modular y orientado a componentes.

### Historia

Basado en AngularJS, creado en 2010 por Misko Hevery y Adam Abrons como proyecto interno de Google. Este utilizaba JavaScript y un enfoque declarativo basado en plantillas. 

Fue hasta 2016 que Google lanzó Angular 2, reescritura completa que adoptó TypeScript y además mejoró el rendimiento. A partir de entonces, se han lanzado versiones regulares con una periodicidad de 6 meses.

### Características

¿Qué hace especial a Angular?

**Componentes**

- Angular divide las aplicaciones en piezas reutilizables llamadas componentes, que encapsulan lógica, estilos y vistas específicas.

**Data Binding**

- Proporciona enlaces de datos bidireccionales entre el modelo y la vista, permitiendo actualizaciones automáticas en ambas direcciones.

**Directivas**

- Angular utiliza directivas para manipular el DOM

**Dependencias**

- Angular tiene un sistema incorporado para administrar dependencias, lo que facilita la creación de aplicaciones escalables y mantenibles

**TypeScript**

- Angular adopta TypeScript, un superconjunto de JavaScript con tipado estático, lo que ayuda a detectar errores en tiempo de desarrollo.

### Ventajas

**Estructura organizada**

Angular promueve un desarrollo estructurado con módulos, componentes y servicios claramente definidos

**Soporte continuo**

Al estar respaldado por Google, Angular recibe actualizaciones regulares

**Rendimiento optimizado**

Su compilación Ahead of Time y capacidades como Lazy Loading permiten aplicaciones rápidas y eficientes

### Ecosistema

**Herramientas principales**

- RxJS, **p**ara programación reactiva y manejo avanzado de eventos asíncronos.
- Angular Material, **u**na biblioteca oficial de componentes
- NgRx, **u**na biblioteca para la gestión del estado basada en Redux.

**CLI** 

- Angular CLI incluye comandos para crear, probar, construir y desplegar aplicaciones rápidamente.

**Extensiones móviles**

- Ionic, como framework para crear aplicaciones móviles híbridas con Angular

**Integración con servicios de backend**

- Angular trabaja fácilmente con REST APIs y GraphQL para la gestión de datos

### Conclusión

React y Angular son herramientas clave para desarrollar aplicaciones web modernas, pero tienen enfoques diferentes. React es ideal para proyectos dinámicos y flexibles gracias a su arquitectura basada en componentes y su gran ecosistema. Angular, en cambio, es un framework completo que ofrece una estructura organizada y es perfecto para aplicaciones grandes y complejas.