# Investigación Angular y React - JUAN LUIS GÓMEZ GONZÁLEZ

## Angular

- ### **¿Qué es?**

Angular es un framework de desarrollo para aplicaciones web de código abierto creado y mantenido por Google.
Este es utilizado principalmente para desarrollar aplicaciones web de estilo Single Page Application (SPA) y Progressive Web App (PWA).
Sirve tanto para versiones móviles como de escritorio. Angular tiene un nivel de complejidad de medio a elevado y ofrece soluciones robustas,
escalables y optimizadas para lograr un estilo de codificación homogéneo y de gran modularidad. Su desarrollo se realiza por medio de
TypeScript o JavaScript. En este último se ofrecen diversas herramientas adicionales al lenguaje como tipado estático o decoradores.


- ### **Características**

1. **Uso de DOM regular**
Angular utiliza el DOM estándar, lo que permite una interacción directa con la estructura del documento HTML o XML. Esto puede ser 
útil para desarrollar aplicaciones donde la manipulación precisa del DOM es necesaria, aunque a menudo puede ser más lento comparado 
con el Virtual DOM utilizado en React.


2. **Enlace de datos (data binding)**
Angular permite un enlace de datos bidireccional, sincronizando automáticamente el modelo de datos y la vista. Esto elimina la 
necesidad de escribir código adicional para actualizar manualmente ambos elementos, facilitando la manipulación de contenido 
dinámico en tiempo real, como tablas o formularios extensos.


3. **Compatibilidad móvil y de escritorio**
Soporta el desarrollo de aplicaciones tanto móviles como de escritorio. Esto significa que las aplicaciones pueden 
ejecutarse de manera consistente en diferentes plataformas, incluidos navegadores modernos.


4. **Velocidad y rendimiento**
Optimiza el rendimiento al generar código a partir de plantillas, resultando en aplicaciones más rápidas y eficientes. 
Esta funcionalidad combina la productividad de un framework con el rendimiento de un código escrito manualmente.


5. **Alta Productividad**
Facilita el desarrollo rápido gracias a su sintaxis de plantillas clara y herramientas integradas como Angular 
CLI (Command Line Interface). Con Angular CLI, los desarrolladores pueden iniciar proyectos, agregar componentes, realizar 
pruebas y desplegar aplicaciones de manera eficiente.


6. **Enlace bidireccional de datos**
Este enfoque asegura que los cambios en el modelo se reflejen automáticamente en la vista, y viceversa, manteniendo ambos 
sincronizados sin necesidad de lógica adicional. Esto reduce significativamente el tiempo de desarrollo, especialmente en 
aplicaciones complejas.


7. **Directivas**
Angular extiende las capacidades del HTML mediante directivas personalizadas. Estas permiten acciones como la
vinculación dinámica de datos y la reutilización de componentes, mejorando la modularidad y el control sobre la interfaz.


8. **Pruebas**
Angular incluye soporte para pruebas unitarias y de integración mediante el framework Jasmine. Esto permite a los 
desarrolladores escribir y ejecutar pruebas fácilmente, asegurando la calidad del código desde las etapas iniciales del desarrollo.



- ### **Ventajas**

1. **Arquitectura robusta**
Angular sigue el patrón MVVM (Model-View-ViewModel), lo que asegura una estructura clara y modular para las aplicaciones, facilitando 
la colaboración entre equipos, el mantenimiento del código y la escalabilidad del proyecto


2. **Productividad mejorada**
Mmejora la productividad al proporcionar herramientas como Angular CLI para crear proyectos rápidamente, módulos para dividir la aplicación 
en partes manejables, y un enlace de datos bidireccional que reduce el código necesario para sincronizar vista y modelo.

3. **Reutilización de código**
La reutilización de código en Angular es altamente eficiente gracias a sus componentes encapsulados, los cuales facilitan la implementación 
consistente de lógica y diseño en distintas partes de la aplicación, ahorrando tiempo y esfuerzo.


4. **Gran comunidad y soporte**
Angular cuenta con el respaldo de Google, una amplia comunidad de desarrolladores y una documentación exhaustiva, lo que facilita el aprendizaje, 
la resolución de problemas y la adopción de buenas prácticas.


5. **Enfoque en pruebas integradas**
Incluye soporte integrado para pruebas unitarias y de integración, lo que permite a los desarrolladores garantizar la calidad del 
código desde las primeras etapas del desarrollo.



- ### **Desventajas**

1. **Curva de aprendizaje alta**
Tiene una curva de aprendizaje alta debido a su uso de TypeScript, una arquitectura compleja y su ecosistema extensivo. Esto 
puede ser abrumador para desarrolladores nuevos en frameworks opinados.

2. **Complejidad en proyectos grandes**
En aplicaciones grandes, Angular puede generar archivos pesados debido a su framework robusto y dependencias, lo que afecta el tiempo 
de carga inicial y el rendimiento en conexiones lentas o dispositivos con recursos limitados.


3. **Dependencias y actualizaciones**
La frecuencia de las actualizaciones y su dependencia de otras bibliotecas pueden complicar el proceso de actualización, 
especialmente en proyectos grandes con soluciones personalizadas.


4. **Costo de mantenimiento**
A medida que una aplicación crece, el mantenimiento requiere desarrolladores con experiencia en Angular para manejar la 
complejidad del framework y sus dependencias.

5. **Mayor tamaño de la aplicación**
Angular tiende a generar aplicaciones más grandes debido a su infraestructura robusta y código adicional. Esto puede degradar la experiencia
del usuario en dispositivos móviles o con recursos limitados.


---

## React

- ### **¿Qué es?**
React es una biblioteca de JavaScript para crear interfaces de usuario y para el desarrollo de aplicaciones móviles y web, creada por Facebook, 
que permite a los desarrolladores crear componentes reutilizables y aplicaciones escalables. Es conocida por su enfoque en la virtualización de 
elementos y la optimización del rendimiento.



- ### **Características**

1. **JSX**
JSX (JavaScript XML) es una extensión de sintaxis que permite escribir elementos HTML directamente en código JavaScript. Facilita la creación de 
componentes de React al combinar HTML y JavaScript en un único archivo, lo que mejora la legibilidad y organización del código. Aunque no es obligatorio, 
JSX simplifica la escritura y renderización de interfaces dinámicas.


2. **Virtual DOM**
Utiliza un Virtual DOM para mejorar el rendimiento. Este modelo representa una copia ligera del DOM real que se mantiene en la memoria. Cuando se realizan 
cambios en la UI, el Virtual DOM calcula las diferencias y actualiza solo las partes necesarias del DOM real, optimizando el tiempo de renderización.


3. **Componentes y Props**
Organiza las interfaces en componentes reutilizables que encapsulan lógica y presentación. Estos componentes pueden recibir datos a través de props (propiedades), 
que son inmutables y permiten pasar información entre diferentes niveles de la aplicación, asegurando consistencia y modularidad.


4. **Gestión de Estado**
La gestión del estado se realiza principalmente con el hook useState o bibliotecas externas. Este permite a los componentes manejar datos dinámicos y 
actualizar la UI cuando el estado cambia, mejorando la interactividad de las aplicaciones.


5. **Redux**
Es una biblioteca externa para gestionar estados complejos en aplicaciones React. Centraliza el estado de la aplicación en un único "store", lo que facilita el 
manejo de grandes cantidades de datos y su propagación a diferentes componentes de forma eficiente y predecible.


6. **Recoil**
Es una alternativa más sencilla que Redux para gestionar estados. Introduce el concepto de "átomos" y "selectores", que permiten a múltiples componentes 
compartir un estado y calcular datos derivados de forma sencilla. Es ideal para principiantes debido a su simplicidad conceptual.


7. **Navegación programática**
Facilita la navegación programática con bibliotecas como React Router. Esto permite redirigir a los usuarios entre páginas mediante código, en lugar de depender 
únicamente de enlaces estáticos. Es útil para acciones como redirecciones tras el inicio de sesión, sincronizando la UI con la URL para una experiencia fluida


8. **Rutas**
Las rutas son una forma de organizar la navegación en aplicaciones React. Estas permiten definir diferentes rutas que se pueden acceder a través de la URL, 
cada una asociada a un componente o grupo de componentes específicos. Facilitando la creación de aplicaciones con múltiples pantallas y una estructura lógica clara.




- ### **Ventajas**

1. **Apoyo de la comunidad**
Tiene una de las comunidades más grandes y activas en el desarrollo web. Esto significa que hay una abundancia de recursos disponibles, como tutoriales, foros, 
y bibliotecas de terceros. Los desarrolladores pueden encontrar fácilmente soluciones a problemas comunes y compartir sus experiencias, lo que facilita el 
aprendizaje y la mejora continua.


2. **Bajos costos**
La reutilización de componentes en React permite a los equipos de desarrollo crear aplicaciones de manera más eficiente. Al poder reutilizar componentes 
en diferentes partes de la aplicación, se reduce el tiempo y el esfuerzo necesario para el desarrollo, lo que puede traducirse en menores costos de desarrollo 
y mantenimiento a largo plazo.


3. **Soporte con plugins externos**
Se puede integrar con una variedad de bibliotecas y plugins que añaden funcionalidades adicionales sin necesidad de reinventar la rueda. Esto incluye soluciones 
para la gestión del estado, la navegación, y la optimización del rendimiento, lo que permite a los desarrolladores personalizar y extender sus aplicaciones según 
las necesidades específicas.

4. **Arquitectura modular**
La arquitectura basada en componentes de React permite a los desarrolladores dividir la interfaz de usuario en partes más pequeñas y manejables. Cada componente 
puede ser desarrollado, probado y mantenido de manera independiente, lo que mejora la organización del código y facilita la colaboración en equipos grandes.


5. **SAceso a bibliotecas y soluciones listas**
Tiene un ecosistema rico en bibliotecas y soluciones preconstruidas. Esto incluye herramientas para la gestión del estado como Redux y Recoil, bibliotecas 
para la manipulación de formularios, y soluciones para la gestión de rutas. Esto acelera el proceso de desarrollo al permitir a los desarrolladores implementar 
características complejas sin tener que construirlas desde cero.



- ### **Desventajas**

1. **Inmadurez**
A pesar de su popularidad, React es relativamente nuevo en comparación con otros frameworks y bibliotecas. Esto puede resultar en una falta de estabilidad en 
algunas características y en la necesidad de adaptarse rápidamente a los cambios en la API o en las mejores prácticas.


2. **Difícil de aprender**
Aunque muchos desarrolladores encuentran a React intuitivo, su curva de aprendizaje puede ser empinada para aquellos que son nuevos en el desarrollo web. 
Conceptos como JSX, el manejo del estado y la gestión del ciclo de vida de los componentes pueden ser desafiantes, especialmente para quienes vienen de un fondo 
de desarrollo más tradicional.


3. **UI compleja**
A medida que las aplicaciones crecen en complejidad, la gestión de la interfaz de usuario puede volverse complicada. Los desarrolladores deben ser cuidadosos en la 
organización de los componentes y la gestión del estado para evitar confusiones y errores, lo que puede aumentar la carga cognitiva.


4. **Largo tiempo de inicialización**
Las aplicaciones pueden tener un tiempo de inicialización más largo debido a la cantidad de código necesario para cargar y renderizar los componentes. 
Esto puede ser un problema en dispositivos con recursos limitados o en conexiones lentas, afectando la experiencia del usuario.


5. **Gestión de la memoria**
En aplicaciones grandes, la gestión de la memoria puede volverse un desafío. Si no se maneja correctamente, puede haber fugas de memoria que afecten el rendimiento 
de la aplicación. Los desarrolladores deben estar atentos a cómo se gestionan los componentes y el estado para evitar problemas de rendimiento a largo plazo.