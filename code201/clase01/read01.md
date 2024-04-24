# Read01

## Introducción a HTML 

### **Crea un poema corto describiendo cómo HTTP envía datos entre computadoras.**

En la vasta red de internet, HTTP surca el cielo,  
Datos como aves mensajeras, vuelan de sitio en sitio.  
Una petición aquí, una respuesta allá,  
Conexiones establecidas, comunicación sin parar.  
Servidores y clientes, unidos en danza,  
HTTP lleva y trae, con gracia y confianza.

### **Describe cómo los archivos HTML, CSS y JS son “analizados” en el navegador.**

Los archivos HTML, CSS y JS son analizados secuencialmente por el navegador cuando una página web es cargada. 

1. **HTML (HyperText Markup Language):** El navegador interpreta el HTML para crear la estructura de la página web. Cada etiqueta y atributo HTML define elementos como encabezados, párrafos, enlaces, imágenes, etc. El navegador renderiza estos elementos en la ventana del navegador según su jerarquía y contenido.

2. **CSS (Cascading Style Sheets):** Una vez que se ha generado la estructura de la página con HTML, el navegador analiza el CSS para aplicar estilos visuales a los elementos HTML. Los estilos CSS definen aspectos como colores, fuentes, márgenes, espaciado, etc., que afectan la apariencia de la página web.

3. **JS (JavaScript):** Finalmente, el navegador analiza y ejecuta el código JavaScript para agregar interactividad y dinamismo a la página web. El JavaScript puede manipular los elementos HTML y CSS, responder a eventos del usuario, realizar solicitudes al servidor, entre otras funciones.

### **¿Cómo puedes encontrar imágenes para agregar a una página web?**

Puedes encontrar imágenes para agregar a una página web de varias maneras:

- Utilizando motores de búsqueda de imágenes como Google Images.
- Visitando sitios web de stock de imágenes gratuitas como Unsplash, Pixabay, Pexels, entre otros.
- Creando tus propias imágenes utilizando cámaras fotográficas, software de diseño gráfico o herramientas de dibujo.
- Contratando a un fotógrafo o diseñador gráfico para que cree imágenes personalizadas para tu sitio web.

### **¿Cómo creas una String en comparación con un Number en JavaScript?**

En JavaScript, una String se crea rodeando el texto con comillas simples (`'`) o dobles (`"`), mientras que un Number se escribe simplemente como un valor numérico sin comillas.

Ejemplo de String:
```javascript
let nombre = "Juan";
let mensaje = 'Hola mundo';
```

Ejemplo de Number:
```javascript
let edad = 25;
let precio = 19.99;
```

### **¿Qué es una Variable y por qué son importantes en JavaScript?**

Una Variable en JavaScript es un contenedor para almacenar datos. Pueden contener diferentes tipos de datos, como números, cadenas, booleanos, objetos, etc. Las variables son importantes en JavaScript porque permiten almacenar y manipular datos de forma dinámica durante la ejecución del programa. Son esenciales para la programación porque facilitan la reutilización de valores, la organización del código y la creación de programas más dinámicos y flexibles.

# Miscelanea 

# *¿Cómo empiezo a diseñar mi sitio web?.*

## ¿Cuál es el primer paso para diseñar una página web?

El primer paso para diseñar una página web es establecer el propósito y el objetivo de la página. Esto implica comprender para quién se está diseñando la página, qué información o servicios se proporcionarán y qué acciones se espera que realicen los usuarios al visitar la página. Este paso ayuda a definir el alcance del proyecto y a guiar todas las decisiones de diseño subsiguientes.

## ¿Cuál es la pregunta más importante que se debe responder al diseñar una página web?

La pregunta más importante que se debe responder al diseñar una página web es: **¿Quiénes son los usuarios y qué necesidades tienen?** Comprender a fondo a los usuarios y sus necesidades es fundamental para crear una experiencia web efectiva y satisfactoria. Esto incluye identificar el público objetivo, sus características demográficas, comportamientos, objetivos y desafíos. Al responder a esta pregunta, se puede diseñar una página web que responda de manera efectiva a las necesidades y expectativas de los usuarios.

# *Semántica*

## ¿Por qué se debe utilizar un elemento `<h1>` en vez de un `<span>` para mostrar un título de primer nivel?

El uso de un elemento `<h1>` en lugar de un `<span>` para mostrar un título de primer nivel proporciona significado semántico al contenido. El elemento `<h1>` indica que el texto es un título de nivel 1, lo que ayuda a los motores de búsqueda y a los lectores de pantalla a comprender la estructura y la jerarquía del contenido. Además, los navegadores y otras herramientas de accesibilidad pueden aplicar estilos y comportamientos predeterminados específicos para los títulos, lo que mejora la legibilidad y la usabilidad del sitio web.

## ¿Cuáles son los beneficios de utilizar etiquetas semánticas en nuestro HTML?

Los beneficios de utilizar etiquetas semánticas en nuestro HTML incluyen:

1. **Mejora de la accesibilidad:** Las etiquetas semánticas proporcionan significado adicional al contenido, lo que facilita la comprensión por parte de los lectores de pantalla y otros dispositivos de asistencia utilizados por personas con discapacidad visual o cognitiva.

2. **Mejora del SEO:** Los motores de búsqueda utilizan las etiquetas semánticas para comprender mejor la estructura y el tema de una página web, lo que puede mejorar su clasificación en los resultados de búsqueda.

3. **Facilita el mantenimiento del código:** El uso de etiquetas semánticas hace que el código HTML sea más legible y comprensible para los desarrolladores, lo que facilita el mantenimiento y la actualización del sitio web en el futuro.

4. **Compatibilidad con dispositivos y navegadores:** Las etiquetas semánticas están diseñadas para ser interpretadas de manera consistente por los navegadores y otros dispositivos, lo que garantiza una experiencia de usuario coherente en diferentes plataformas y dispositivos.

# *¿Qué es JavaScript?*

### Describe 2 cosas que requieran de JavaScript en el navegador:

1. **Validación de Formularios:** JavaScript se utiliza comúnmente para validar los datos ingresados por los usuarios en formularios web. Por ejemplo, se pueden verificar campos obligatorios, formatos de correo electrónico válidos, números de teléfono correctos, entre otros. Esto ayuda a mejorar la experiencia del usuario al garantizar que los datos enviados sean válidos y consistentes.

2. **Manipulación del DOM:** JavaScript se utiliza para interactuar dinámicamente con el Document Object Model (DOM) de una página web. Esto permite cambiar el contenido HTML, modificar estilos CSS, agregar o eliminar elementos, responder a eventos del usuario, entre otras acciones. Por ejemplo, al hacer clic en un botón, JavaScript puede mostrar u ocultar contenido, cambiar el texto de un elemento o realizar animaciones.

### ¿Cómo se puede añadir JavaScript a un documento en HTML?

JavaScript se puede añadir a un documento HTML de las siguientes maneras:

1. **Incorporado en la página:** Se puede agregar código JavaScript directamente en el cuerpo del documento HTML utilizando la etiqueta `<script>`. Por ejemplo

   ```html
   <script>
       // Código JavaScript aquí
   </script>
   ```

2. **Enlazado desde un archivo externo:** También se puede enlazar un archivo JavaScript externo utilizando la etiqueta `<script>` con el atributo `src`, que apunta al archivo JavaScript. Por ejemplo:

   ```html
   <script src="archivo.js"></script>
   ```

3. **Manejado por el atributo `onclick`:** Se puede agregar JavaScript directamente a un elemento HTML utilizando el atributo `onclick`. Por ejemplo:

   ```html
   <button onclick="miFuncion()">Haz clic</button>
   ```