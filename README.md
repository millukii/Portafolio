# Portafolio

Vitrina donde expongo mis proyectos web de aprendizaje y aplico distintos conceptos de html, css y js.

En el sitio principal tendré una descripción de mí y mi trayecto por el camino del fullstack utilizando bootstrap.

También se podrá ver algunos proyectos de practica a los que podrás acceder a través de la barra de navegación.

En cada proyecto puede que se usen distintas tecnologías.

En este Readme/Wiki tendré documentados mis apuntes y referencias.

## Instalación

- Clonar repositorio git clone
- Abrir index.html en el navegador

## Conceptos Básicos Repaso

### Qué significa desarrollo fullstack?

- El termino fullstack hace alusión a una pila de conocimientos que requerimos para lanzar una aplicación completa, tanto la parte gráfica como funcional y el almacenamiento de datos. Maneja de alguna forma todo el ciclo de vida de una aplicación (Planificación ,Análisis , Diseño, Codificación, Implementación,Fase de pruebas, Despliegue).

- Para dividir estas responsabilidades en roles/desarrolladores a menudo hablamos de frontend y backend.

- Un desarrollador frontend va entregar las pantallas donde el usuario interactúa con una interfaz como un formulario dentro de una web, o también podría ser una aplicación de escritorio.

- Por otro lado un desarrollador backend va a disponibilizar los servicios que procesen la información y cumplan con el flujo de datos que necesitamos para el funcionamiento que requerimos. Estos servicios alimentan de información al frontend.

- Podemos inferir entonces que un fullstack es como una navaja suiza, pero además tiene que saber cómo conectar los servicios a bases de datos, y como conectar el backend con el frontend. Eso como la base de la responsabilidad de este termino.

- Un Desarrollador puede entregar distintos tipos de aplicaciones como sitios web, aplicaciones moviles, APIs, aplicaciones de consola, drivers, sistemas operativos, aplicaciones de escritorio, apps para smartwach, plugins, drivers, etc.

- Vamos a profundizar principalmente en el desarrollador fullstack que se orienta al desarrollo web.

- Vamos a asumir el conocimiento básico de internet y de computación.

### Qué es un sitio web?

- Sabemos que un sitio web en el trasfondo es un directorio o una carpeta en un host (pc) con todos los archivos y documentos necesarios para mostrar una experiencia al usuario. (Ver tipos de sitios web)
- Este portal está asociado a un dominio que representa el nombre o dirección por el cuál encontrarán nuestro sitio en la World Wide Web (internet)
- Internet es una red mundial interconectada de portales
- https://es.wikipedia.org/wiki/Sitio_web

### W3C

- El World Wide Web Consortium (W3C) desarrolla estándares web internacionales: HTML, CSS y muchos más. Los estándares de W3C se llaman Recomendaciones del W3C.

- El soporte para la accesibilidad de todos los estándares de W3C es revisado por el Grupo de Trabajo de Arquitecturas de Plataforma Accesible - APA (en Inglés).

- Los estándares W3C y las Notas de los Grupos de Trabajo que se mencionan abajo son particularmente relevantes para la accesibilidad.

- Muchos de los inventos humanos son investigados, normados, promovidos y deprecados por grandes organizaciones que establecen estandares, normas, especificaciones, certificaciones, buenas practicas, comunidades, y escuelas etc.
- La escuela w3s está llena de ejemplos básicos para cada cosa que necesitemos acerca de desarrollo web a nivel inicial.
- https://www.w3schools.com/
- https://www.w3.org/WAI/standards-guidelines/es

### Cómo accedo a un sitio web?

- A través de escribir una url que es la direccion para identificar el sitio en un navegador.
- Buscando en google.com un termino relacionado y explorar los resultados.

### Qué tecnologías o conocimientos básicos necesito para desarrollar un sitio web?

- Puedes tener informacion simplemente con un archivo.txt, aunque así se vería bastante feo, no tendriamos estilos y ninguna funcionalidad(validaciones, programación).
- Podemos tener un archivo.html y si usamos el estandar HTML5 podríamos decir que estamos especificando un sitio web.
- https://html.spec.whatwg.org/
- Si agregamos una hoja de estilos en cascada archivo.css siguiendo el estándar CSS3 podriamos decir que estamos maquetando.
- https://www.w3.org/Style/CSS/specs.en.html
- Si agregamos codigo js dentro del archivo.html o si agregamos un archivo.js con un script dentro estamos agregando código o funcionalidades. A este punto le llamo desarrollar.
- Si agregamos un sistema de versionado estamos hablando del inicio de nuestro camino fullstack.
- Si todas estas tareas las identificamos, medimos, y documentamos de una forma iterativa y cercana al cliente/usuario y seguimos los principios del manifesto ágil http://agilemanifesto.org/iso/es/manifesto.html, felicitaciones vamos muy bien encaminados.

### Cuáles son los pasos que debo dar para desarrollar un sitio web y desplegarlo(implementarlo)? (Idealmente)

- Establecer objetivos. Ej: Quiero crear un sitio web donde mostrar mis servicios y recibir consultas.

- Definir alcance. Especificar el cómo o la implicancia.
- Diseñar la solución en un bosquejo.
- Identificar, dividir y priorizar las tareas de forma pequeña, descriptiva y medible.
- Utilizar alguna herramienta o sistema para ir registrando este avance
- Iniciar el proyecto en un repositorio.
- Crear estructura de carpetas
- Crear readme
- Crear archivo index.html, assets/css/estilos.css, assets/js/index.js
- Enlazar archivos al index
- Agregar bootstrap
- Comprar dominio u obtener un subdominio gratuito. Lo mismo con el hosting.
- Desplegar la aplicación.
- Probar.
- Automatizar el despliegue con alguna herramienta de integración continua.
- Configurar los dns y enlazar el dominio
- Configurar https
- Hacer que google nos indexe
- Enriquecer el contenido
- Optimizar

## Proyectos

### Maqueta 1

- Estructura HTML5 con comentarios de las etiquetas y acerca de los documentos html, section, articles, etc.
- Se describen los propositos de algunas etiquetas que van en el nodo head
- Se agrega un formulario básico de contacto con inputs, labels, textarea y un button
- Se incluyen listas ordenadas y no ordenadas

### Maqueta 2

- Se agregan contenedores
- Navegador aplicando position fixed top
- Se agrega un mapa emebebido en un iframe

### Landing de ventas

- Diseño mockup
- Repositorio git
- Estructura carpetas estandar
- Utilizando bootstrap o similar
- Navagacion <header>
- Jumbotron introduccion y call to action para dejar el correo
- Blog
- Adicionales
- Footer

### Cine

- Este proyecto utilizara flexbox css

### Floreria

### Hamburguesería

### Recomendaciones

- Investigar sobre la crisis del software
- Revisar stackoverflow

## Git, Github, Git console, Github desktop

- Git nos sirve para crear un repositorio con un sistema de versionado ampliamente usado

## DOM

- Document Object Model: El navegador carga el archivo html en un DOM, que es el documento cargado en la memoria del ordenador.

1. Se carga el html
2. Se parsea el html
3. Se crea el arbol del DOM
4. Se Carga css
5. Parsea el css
6. Se aplica el css al DOM
7. Se visualiza

## HTML

- Agregar una estrutura básica de HTML5 es bastante simple podemos ver el ejemplo en maqueta 1 o maqueta 2.
- <!Doctype html></html>:
- <head></head>:
- <body></body>:
- <link>:
- <meta>:
- <main>:
- <section></section>:
- <article></article>:
- <nav></nav>:
- <footer></footer>:
- <aside></aside>:
- <img>:
- <ul><li></li></ul>:
- <style></style>:
- <script></script>:

## CSS

- En las hojas de estilo en cascada primero identificamos al nodo html al cual le queremos aplicar diseño con los selectores, y especificamos las propiedades que queremos modificar y sus valores.
- Cada tipo de nodo o componente puede tener distintas propiedades.
- Las propiedades pueden tener un valor por defecto.
- Si el navegador no entiende los selectores o las propiedades se las saltan.
- https://developer.mozilla.org/es/docs/Learn/CSS/First_steps/How_CSS_works
- https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/Debugging_CSS
- https://developer.mozilla.org/en-US/docs/Web/CSS/Specificity

### Responsive Design

### Modelo de cajas

- Todos los elementos o nodos html representados por las etiquetas se renderizan en el navegador como una caja.
- Este modelo está formado por la caja contenido, el padding, los borders y los margin.
- Padding es el espacio interno de un elemento que se situa entre el contenido y el borde.
- Margin es el espacio por fuera del borde entre un elemento y los demás
- El modelo de cajas se puedem clasificar en bloques y en líneas.
- Los elementos block tienen un tamaño personalizado y generan salto de línea.
- Los elementos inline tienen un tamaño determinado por su contenido y no generan saltos de linea.
- Los elementos block son adecuados para crear columnas y secciones del sitio como el nav, el header, section, footer, div
- Los elementos inline representan el contenido de los elementos como em, strong, span
- El modelo de caja tradicional establece que los elementos pueden flotar hacia izquierda/derecha y compartir el mismo espacio en una línea.
- Para hacer flotar los elementos usamos la propiedad float y esta puede terner un valor left, right o none

### Layout

- Un modo de diseño CSS(CSS layout mode), a veces simplemente llamado "layout", es un algoritmo que determina la posición y tamaño de cajas basado en la forma en la que interactúan con sus (elementos) hermanos y padres. Hay varios de ellos:

- El block layout, diseñado para presentar documentos. El block layout contiene características de documento-centrado, como la capacidad de flotar(float) elementos o distribuirlos en múltiples columnas.
- El inline layout, diseñado para presentar texto.
- El table layout, diseñado para presentar tablas.
- El positioned layout, diseñado para posicionar elementos sin demasiada interacción con otros elementos.
- El flexible box layout, diseñado para presentar páginas complejas que pueden redimensionarse de forma fluida.
- El grid layout, diseñado para presentar elementos relativos a una cuadrícula fija (fixed grid).
- Nota: No todas las propiedades CSS aplican a todos los modos de diseño. La mayoría de ellos aplican a uno o dos de ellos y no tienen efecto si se configuran en un elemento que es parte de otro modo de diseño.
- https://developer.mozilla.org/es/docs/Web/CSS/Layout_mode

### Propiedad Display

- Esta es la propiedad que define el tipo de caja es decir, que un elemento sea block o inline

#### Display Block

- Un div por defecto tiene su propiedad display con el valor block
- El elemento usa el 100% del ancho posible

#### Display Inline

- El ancho y alto es definido por el contenido
- El width y el height no funciona
- Hay etiquetas que por defecto son display inline como por ejemplo las etiquetas label

#### Display Inline-block

- Podemos asignar ancho y alto
- Un elemento inline block se posiciona uno al lado del otro en una misma fila pero con el tamaño que queramos.

#### Display flex

- Debemos crear un contenedor y ese contenedor debe ser el padre con un display: flex
- Los elementos se hacen flexible, acomodandose unos al lado del otro

#### Display none

### Propiedad Position

-

#### Position Static

- No es necesario utilizarlo, es el position que viene por defecto.
- Indica que el componente, etiqueta o nodo.

#### Position Relative

#### Position Absolute

#### Position fixed

#### Position Static

- https://www.youtube.com/watch?v=1F_Q5NQBkyU&ab_channel=YoelvisMulen%7Bcode%7D
- https://www.youtube.com/watch?v=FLet5o2ecE8&ab_channel=EduardoFierro

### Z-index

### Centrar Elementos

### Flexbox

### Grid CSS

### Variables

- https://developer.mozilla.org/es/docs/Web/CSS/Using_CSS_custom_properties

## JS

### Otras referencias

- https://www.youtube.com/watch?v=wERUdGHvvVI&ab_channel=FalconMasters
- https://www.youtube.com/watch?v=n4hgWGK_8cQ&ab_channel=HolaMundo
