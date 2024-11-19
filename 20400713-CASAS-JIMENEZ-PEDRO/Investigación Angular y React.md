# Investigación Agular y React
Pedro Casas Jiménez - 20400713
Interfaces Web - 5B

## Angular

### Definición

Es un framework para crear aplicaciones de una sola página (SPA) en el lado del cliente usando HTML y TypeScript, desarrollado por Google en 2010. Implementa la funcionalidad como un conjunto de bibliotecas TypeScript que se importa en las aplicaciones.
Posee una arquitectura basada en componentes, lo que significa que las aplicaciones se construyen utilizando componentes reutilizables que pueden integrarse fácilmente en una aplicación más amplia.

### Características
- Está basado en componentes
- Se centra en la escalabilidad y la mantenibilidad
- Gran compatibilidad con la vinculación bidireccional de datos (JavaScript y HTML) y la inyección de dependencias
- Un amplio conjunto de directivas y servicios integrados

### Ventajas
- El uso de TypeScript ofrece un mantenimiento más sencillo
- Código reutilizable, que desemboca en ahorro de recursos y evita costes añadidos.
- Es de código abierto
- Desarrollo multiplataforma
- Desarrollo rápido
- Permite utilizar una arquitectura modelo-vista-controlador (MVC)

### Desventajas
- Curva de aprendizaje alta
- Peso de las aplicaciones superior a aplicaciones HTML-JavaScript-CSS

### Instalación

Haciendo uso de un manejador de paquetes, se puede instalar angular-cli haciendo uso del siguiente comando:
```
npm install @angular/cli
```

Existen diversos comandos que pueden ayudar en la creación de proyectos. Uno de ellos permite ver la versión que se tiene instalada de angular-cli:
```
ng --version
```

Para obtener un listado de comandos se puede usar:
```
ng help
```

Para crear un proyecto:
```
ng new --nombre_proyecto--
```

### Algunas empresas que lo utilizan
- Google
- Nike
- Paypal
- Microsoft
- American Express

## React

### Definición

Es una librería de JavaScript para el desarrollo de aplicaciones móviles y web. Creada por Facebook (desde 2013), React contiene una colección de fragmentos de código JavaScript reutilizables utilizados para crear interfaces de usuario (UI) llamadas componentes, estos combinan la estructura HTML y JavaScript con la sintaxis JSX (JavaScript XML).

### Características

- Archivos JavaScript XML (JSX)
- Virtual DOM, aplica cambios en un entorno virtual para optimizar los procesos
- Basado en componentes
- No es un framework como tal, es una librería
- Permite el desarrollo multiplataforma
- Es declarativo, es decir, se pueden programar tareas sin especificar cómo hacerlas
- Los datos fluyen de componentes padre a componentes hijo

### Ventajas

- Código reutilizable, lo que reduce el tiempo y costo de desarrollo
- Código abierto
- Migración entre versiones sencilla porque se ofrecen herramientas para ello
- Aportes por parte de una comunidad activa y multitud de herrramientas complementarias

### Desventajas

- No existe un patrón de desarrollo fijo por lo que se deben tomar muchas desiciones de administración
- Curva de aprendizaje alta
- Se necesita conocimiento tanto de JavaScript como de HTML para dominarlo
- Requiere de otras herramientas para tareas como el manejo de estados o enrutamiento

### Instalación

Al igual que Angular, se requiere de un  manejador de paquetes. Donde se  utiliza el siguiente comando para instalar react
```
npm install -g create-react-app
```

Para crear un proyecto se usa
```
create-react-app --nombre_proyecto--
```

Para iniciar el proyecto se requiere moverse a la carpeta del proyecto y usar el comando start:
```
cd --nombre_proyecto--
npm start
```

Como se mencionó, React es una librería y requiere de otras herramientas para algunas funcionalidades, algunas de estas son:
- Vite (front end)
- Next (front end)
- Remix (enrutamiento)
- Gatsby (complementos para la capa de datos)
- Expo (desarrollo nativo)

```
npm create vite@latest
npx create-next-app@latest
npx create-remix
npx create-gatsby
npx create-expo-app
```

### Algunas empresas que lo utilizan
- Facebook
- Netflix
- Uber
- Reddit
- Airbnb