# Lectura 07

## DOM

### 1. Explica por qué necesitamos los modelos de dominio

Necesitamos modelos de dominio porque son herramientas poderosas para comprender y representar las complejas interacciones y relaciones dentro de un sistema o negocio. Aquí hay algunas razones clave:

1. Claridad conceptual: Los modelos de dominio ayudan a clarificar conceptos y términos dentro de un dominio específico. Al definir entidades, atributos y relaciones, proporcionan un lenguaje común que todos los miembros del equipo pueden entender y utilizar para comunicarse de manera efectiva.
2. Alineación del equipo: Al crear un modelo de dominio, los miembros del equipo pueden colaborar para comprender completamente el dominio en el que están trabajando. Esto promueve la alineación y ayuda a garantizar que todos estén en la misma página en cuanto a los requisitos y las funcionalidades del sistema.
3. Identificación de requisitos: Al analizar el dominio y modelarlo, se pueden identificar de manera más clara y precisa los requisitos del sistema. Esto ayuda a evitar malentendidos y garantiza que el software desarrollado satisfaga las necesidades del cliente.
4. Detección temprana de problemas: Al modelar el dominio, es posible identificar posibles problemas o ambigüedades en los requisitos antes de que se desarrollen completamente. Esto permite realizar ajustes y correcciones en etapas tempranas del proceso de desarrollo, lo que ahorra tiempo y recursos.
5. Facilita el diseño y la implementación: Los modelos de dominio proporcionan una base sólida para el diseño y la implementación del sistema. Al comprender la estructura y las interacciones dentro del dominio, los desarrolladores pueden tomar decisiones más informadas sobre la arquitectura y la implementación del software.

### 2. ¿Por qué no se debe utilizar tablas para los layout de página?

#### Razones para no usar tablas HTML para layouts de página

1. Accesibilidad reducida: Las tablas no están diseñadas para estructurar el diseño de la página, lo que puede dificultar la accesibilidad para usuarios con discapacidad visual. Los lectores de pantalla interpretan las etiquetas HTML, y usar tablas para diseño puede resultar en una salida confusa para estos usuarios.
2. Estructuras incorrectas: El uso de tablas para diseño puede conducir a una estructura de marcado más compleja y menos semántica en comparación con las técnicas de diseño modernas como CSS. Esto puede dificultar la escritura, el mantenimiento y la depuración del código.
Falta de respuesta adaptativa automática: Las tablas no tienen una respuesta adaptativa automática como los contenedores de diseño adecuados (por ejemplo, <div> con CSS). Mientras que los contenedores de diseño se dimensionan automáticamente según su elemento padre, las tablas se dimensionan según su contenido, lo que requiere medidas adicionales para que el diseño sea efectivo en todos los dispositivos.