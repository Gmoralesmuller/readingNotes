# **Lectura 04: Enlaces en HTML, Funciones en JS, e Introducción al CSS: Layout**

## *Crea Hipervínculos*

### 1. Para crear un enlace básico, ¿en qué elemento colocamos el texto u otro contenido?

    Para crear un enlace básico se emplea el elemento ancla `<a>` es en el cual se coloca el texto.

### 2. ¿Qué información contiene el atributo href?

    El atributo `<href>`  contendra la dirección web hacia donde nos queremos que se dirija el enlace.

### 3. ¿Cuáles son algunas de las formas en las que podemos asegurarnos de que los enlaces a nuestras páginas sean accesibles a todos los lectores?

Serian las siguientes formas:

    - Evita simplemente rellenar una página con enlaces. En lugar de eso, asegúrate de que los enlaces 
    sean comprensibles para todo tipo de lectores, independientemente del contexto o las herramientas que utilicen.
    - Los usuarios de lectores de pantalla suelen saltar de enlace a enlace en la página y los leen sin contexto. 
    Por lo tanto, es importante que el texto del enlace sea descriptivo y claro.
    - Los motores de búsqueda utilizan el texto de los enlaces para indexar los archivos buscados. 
    Incluir palabras clave relevantes en el texto del enlace ayuda a describir de manera efectiva el sitio al que apunta.
    - Los usuarios visuales suelen escanear rápidamente la página y leer solo lo que les interesa. 
    Los textos descriptivos en los enlaces son útiles para este tipo de usuarios.

 Otras recomendariones:

    - Evita repetir la URL como parte del texto del enlace,
     ya que las URLs pueden sonar mal cuando se leen letra por letra.
    - No escribas “link” o “enlace” en el texto del enlace, ya que es redundante. 
    Los lectores automáticos indican que hay un enlace al encontrarlo, y los usuarios también saben que están interactuando con un enlace.

#### **Enlaces de Fuentes**

- [Aprende HTML](https://developer.mozilla.org/es/docs/Learn/HTML)

- [Crea Hipervinculos](https://developer.mozilla.org/es/docs/Learn/HTML/Introduction_to_HTML/Creating_hyperlinks)

***

## *CSS: Layout: Normal Flow CSS: Layout: Positioning*

### 1. ¿A qué se refiere con “normal flow”?


    El "flujo normal" o "normal flow" se refiere al comportamiento predeterminado de los elementos en una página web cuando no se aplica ningún estilo de CSS que altere su disposición natural. En este flujo normal, los elementos se distribuyen en función de su tipo (bloque o en línea) y se presentan de acuerdo con el modelo de caja estándar, que incluye el contenido, el relleno, el borde y los márgenes.

### 2. ¿Cuáles son algunas de las diferencias entre los elementos block-level e inline?

    - Los elementos de nivel de bloque se presentan uno debajo del otro en la dirección del flujo de bloque, 
    ocupando todo el ancho disponible de su elemento padre.
    - Los elementos en línea se colocan en la misma línea entre sí y con cualquier contenido de texto adyacente, 
    ocupando solo el espacio necesario según su contenido y ajustándose al ancho del elemento de nivel de bloque contenedor
    - La altura y el ancho de los elementos de nivel de bloque se determinan por su contenido y pueden ser configurados utilizando CSS.
    - La altura y el ancho de los elementos en línea son determinados por su contenido y
    no pueden ser configurados directamente mediante CSS, aunque pueden influir en el flujo de línea.
    - Los márgenes de los elementos de nivel de bloque afectan el espacio entre ellos y otros elementos,
     y no se colapsan con los márgenes de otros elementos.
    - Los márgenes de los elementos en línea pueden colapsar con los márgenes adyacentes, 
    lo que significa que si dos elementos en línea tienen márgenes configurados y los márgenes se tocan,
     se aplica el mayor de los dos márgenes y el menor desaparece.

### 3. El ___ positioning es la posición por defecto de todos los elementos en html.

    El "static" positioning es la posición por defecto de todos los elementos en HTML. En el modelo de caja estándar de CSS, cuando no se especifica ningún tipo de posicionamiento, los elementos se colocan en el flujo normal del documento, es decir, siguiendo el orden natural de aparición en el HTML y respetando las propiedades de margen, relleno y otros atributos de estilo.

    El posicionamiento "static" no se ve afectado por las propiedades de posicionamiento como "top", "bottom", "left" o "right", ya que este tipo de posicionamiento hace que los elementos se muestren en su posición predeterminada según el flujo normal del documento.

### 4. Nombra algunas ventajas de utilizar absolute positioning en un elemento

    - Control preciso de la ubicación: Permite colocar un elemento en una posición exacta dentro de su contenedor padre o incluso en relación con el documento en su conjunto, utilizando las propiedades "top", "bottom", "left" y "right". Esto proporciona un control detallado sobre la disposición de los elementos en la página.
    - Superposición de elementos: Con absolute positioning, es posible superponer elementos unos sobre otros, lo que puede ser útil para crear efectos visuales complejos o diseños de capas.
    - Independencia del flujo normal: Los elementos posicionados absolutamente se eliminan del flujo normal del documento, lo que significa que no afectan a la disposición de otros elementos. Esto puede ser útil para crear diseños más complejos y evitar que otros elementos se vean afectados por la posición del elemento absolutamente posicionado.
    - Anidamiento de elementos: Los elementos posicionados absolutamente pueden anidarse dentro de otros elementos y mantener su posición relativa a su contenedor más cercano con un posicionamiento relativo. Esto permite una estructura más modular y flexible en el diseño.

### 5. ¿Cuál es una diferencia clave entre fixed positioning y absolute positioning?
    Una diferencia clave entre fixed positioning y absolute positioning es cómo se relacionan con el desplazamiento de la página:

    - Absolute positioning: Los elementos posicionados absolutamente se colocan en relación con el primer 
    ancestro posicionado (es decir, un elemento cuyo posicionamiento es distinto de "static") o con el elemento de nivel de bloque contenedor, si no hay ninguno posicionado.
    Esto significa que si el contenedor padre tiene un desplazamiento (scroll) en la página, el elemento posicionado absolutamente se moverá con respecto a ese contenedor,
    no con respecto a la ventana del navegador.
    - Fixed positioning: En cambio, los elementos con fixed positioning se colocan en relación con la ventana del navegador, 
    independientemente del desplazamiento de la página. Esto significa que un elemento posicionado fijo permanecerá en la misma posición en la pantalla incluso 
    cuando se desplace la página hacia arriba o hacia abajo. Es útil para elementos que se desean fijos en la pantalla, 
    como barras de navegación o encabezados que deben permanecer visibles mientras el usuario navega por el contenido.


#### **Enlaces de Fuentes**

- [CSS Layout](https://developer.mozilla.org/es/docs/Learn/CSS/CSS_layout)

- [CSS: Layout: Normal Flow](https://developer.mozilla.org/es/docs/Learn/CSS/CSS_layout/Normal_Flow)

- [CSS: Layout: Positioning](https://developer.mozilla.org/es/docs/Learn/CSS/CSS_layout/Positioning)

***

## *Funciones*

### 1. Describe la diferencia entre una declaración de función y una invocación de función.

    - Una declaración de función es simplemente la definición de la función en sí misma,
    donde se especifica su nombre, parámetros (si los tiene) y cuerpo de la función. Esto se hace utilizando la palabra clave "function".
    - Por otro lado, la invocación de función es cuando realmente se ejecuta o se llama a la función definida.
    Esto se logra escribiendo el nombre de la función seguido de paréntesis, que pueden contener argumentos si la función los espera.

### 2. ¿Cuál es la diferencia entre un parameter y un argument?

    - Un parámetro es un valor variable que se declara en la definición de la función y 
    que actúa como un marcador de posición para los valores que se le pasarán cuando se invoque la función. 
    Especifica qué tipo de datos o valores la función espera recibir.
    - Por otro lado, un argumento es el valor real que se pasa a la función cuando se la invoca. 
    Es el dato real que se asigna a un parámetro específico durante la llamada a la función.

#### **Enlaces de Fuentes**

- [Aprende JS](https://developer.mozilla.org/es/docs/Learn/JavaScript)

- [Funciones](https://imoralescs.gitbooks.io/javascript/content/funciones.html)

***

## *Beneficios del Pair Programming*

### * Escoge 2 beneficios del pair programming y reflexiona acereca de cómo estos beneficios te pueden ayudar en tu carrera como programador.

    - *Mejores soluciones diseñadas a través de la colaboración compartida.*
    El pair programming nos permite tener soluciones mas elaboradas y originales fruto de la colaboracion de dos desarrolladores al emplear distintos puntos de vista.
    - *Feedback rápido*
    Recibir un feedback sobre el trabajo elaborado resulta muy beneficioso ya que nos ayuda a notar inconsistencias, errores, etc y asi poder mejorar la calidad y el flujo de trabajo como desarrollador. 


## *Cosas que me gustaría aprender más*

- Descubrir y probar nuevas herramientas y tecnologías que me ayuden a desarrollarme más en Front end.

- Perfeccionar y conocer más sobre estilos de Css para mis proyectos.

- Aprender sobre patrones de diseño de software que pueda incluir en mis proyectos.

### Autor

  Georgina Morales: [Gmoralesmuller](https://github.com/Gmoralesmuller)`(GitHub)`


###### *Este contenido fue en colaboracion y apoyo de Chatbot (Chat GPT)*

### Creacion

- Miercoles 17 de Abril del 2024.

Enlace de este contenido [clase04](https://Gmoralesmuller.github.io/readingNotes/code201/clase04)