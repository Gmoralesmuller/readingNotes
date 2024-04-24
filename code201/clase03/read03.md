# Read03 

## HTML

1. **¿Cuándo se puede utilizar una lista no ordenada en tu documento HTML?**

Una lista no ordenada se puede utilizar cuando el orden de los elementos no es relevante, como en una lista de elementos sin una secuencia específica. Por ejemplo, para listar elementos de una receta, características de un producto, o elementos de una lista de compras.

2. **¿Cómo cambias el estilo bullet de la lista de elementos no ordenados?**

Puedes cambiar el estilo del bullet de una lista no ordenada utilizando CSS. Por ejemplo, puedes cambiar el tipo de marcador, el tamaño, el color, o incluso utilizar imágenes como marcadores en lugar de los bullets predeterminados.

3. **¿Cuándo debes usar una lista ordenada o lista no ordenada en tu documento HTML?**

Debes usar una lista ordenada cuando el orden de los elementos es importante, como en una lista de pasos de un proceso, clasificaciones o rankings. Por otro lado, una lista no ordenada se utiliza cuando el orden de los elementos no importa, como en una lista de ítems sin secuencia específica.

4. **Describe dos formas en las que puedes cambiar los números en los elementos de la lista proporcionados por una lista ordenada:**

   - Utilizando CSS para cambiar el estilo de los números. Por ejemplo, puedes cambiar el tamaño, el color, la fuente o la posición de los números.
   - Utilizando el atributo `type` en el elemento `<ol>` para especificar el tipo de numeración. Por ejemplo, puedes usar "a" para letras minúsculas, "A" para letras mayúsculas, "i" para números romanos minúsculos, "I" para números romanos mayúsculos, etc.

## CSS

### La historia del Box Model: Margin y Padding

En el mundo de la maquetación web, Margin y Padding son dos personajes fundamentales en la historia del Box Model. Imagina que están inmersos en un cuento épico donde cada uno tiene un rol crucial.

**Margin:** Margin es como el guardián del perímetro del elemento. Él define el espacio que rodea al elemento, actuando como una frontera protectora que separa al elemento de otros elementos circundantes. Es el espacio en blanco entre el elemento y su entorno, estableciendo una especie de zona segura para el elemento.

**Padding:** Por otro lado, Padding es como el abrazo reconfortante desde adentro del elemento. Él define el espacio dentro del borde del elemento, proporcionando un área acogedora donde el contenido del elemento puede respirar y tener su propio espacio. Padding actúa como una capa interna de protección, manteniendo el contenido del elemento alejado de su borde exterior.

### Las partes del Box Model:

En la historia del Box Model, cada elemento HTML tiene cuatro partes distintas que conforman su estructura:

1. **Content (Contenido):** Este es el corazón del elemento, donde reside su contenido real, como texto, imágenes u otros elementos HTML. Es el área visible dentro del elemento.

2. **Padding (Relleno):** Alrededor del contenido, está el relleno, definido por el Padding. Este espacio interno separa el contenido del borde del elemento, proporcionando espacio adicional y aire alrededor del contenido.

3. **Border (Borde):** El borde es la línea que rodea el contenido y su padding. Es como el límite físico del elemento, que define su forma y tamaño visibles.

4. **Margin (Margen):** Finalmente, en el exterior del borde, está el margen, definido por el Margin. Este espacio exterior separa al elemento de otros elementos circundantes, creando un espacio entre el elemento y su entorno.

## Javascript

### ¿Qué tipos de datos puedes almacenar en un Array?

*Tipos de datos que puedes almacenar en un Array:*

En un Array de JavaScript puedes almacenar una variedad de tipos de datos, incluyendo:

    - Números
    - Cadenas de texto
    - Booleanos
    - Objetos
    - Funciones
    - Arrays (también conocidos como arreglos)

### ¿El array people es un array de JavaScript válido? De ser así, ¿cómo puedo acceder a los valores almacenados? Y si no, ¿por qué?

El array people es un array de JavaScript válido. Es un array multidimensional que contiene otros arrays como elementos.

Para acceder a los valores almacenados en el array people, puedes utilizar la notación de corchetes [ ]. Cada elemento dentro del array people es a su vez un array. Puedes acceder a los valores de la siguiente manera:

    - Para acceder al primer array dentro de people: people[0].
    - Para acceder al segundo array dentro de people: people[1].
    - Para acceder al tercer array dentro de people: people[2].

Cada uno de estos sub-arrays contiene diferentes valores, y puedes acceder a cada elemento dentro de ellos utilizando la misma notación de corchetes [ ]. Por ejemplo, para acceder al primer elemento del primer array dentro de people, usarías people[0][0], que devolvería 'pete'.

### Enumera cinco opreadores abreviados de asignación en javascript y describe lo que hacen.

1. **`+=`**: Este operador abreviado suma el valor del operando derecho al operando izquierdo y asigna el resultado a la variable del operando izquierdo. Por ejemplo: `x += 5;` es lo mismo que `x = x + 5;`.

2. **`-=`**: Este operador abreviado resta el valor del operando derecho al operando izquierdo y asigna el resultado a la variable del operando izquierdo. Por ejemplo: `y -= 3;` es lo mismo que `y = y - 3;`.

3. **`*=`**: Este operador abreviado multiplica el valor del operando derecho por el operando izquierdo y asigna el resultado a la variable del operando izquierdo. Por ejemplo: `z *= 2;` es lo mismo que `z = z * 2;`.

4. **`/=`**: Este operador abreviado divide el valor del operando izquierdo por el operando derecho y asigna el resultado a la variable del operando izquierdo. Por ejemplo: `a /= 4;` es lo mismo que `a = a / 4;`.

5. **`%=`**: Este operador abreviado divide el valor del operando izquierdo por el operando derecho y asigna el resto de la división a la variable del operando izquierdo. Por ejemplo: `b %= 3;` es lo mismo que `b = b % 3;`.

### Lee el código a continuación, evalúa la últimaexpresión y explica cuál sería el resultado y por qué.

Dado el código proporcionado:

```javascript
let a = 10;
let b = 'dog';
let c = false;

// evalúa esto
(a + c) + b;
```

La última expresión ` (a + c) + b;` intenta sumar la variable `a` con la variable `c`, y luego concatenar el resultado con la variable `b`.

Aquí está el proceso de evaluación:

1. La variable `a` es un número (`10`).
2. La variable `c` es un booleano (`false`).
3. JavaScript intentará convertir el booleano `false` a un tipo de dato numérico durante la operación de suma. En JavaScript, `false` se convierte a `0` cuando se usa en una operación numérica.
4. Entonces, la expresión `(a + c)` se convierte a `(10 + 0)` que es igual a `10`.
5. Finalmente, se concatenará el resultado (`10`) con la cadena de texto `'dog'`, ya que JavaScript, al encontrarse con una cadena de texto, realiza la concatenación en lugar de la suma numérica.

Por lo tanto, el resultado de la expresión `(a + c) + b;` sería la cadena de texto `'10dog'`. Esto se debe a que el número `10` se convierte en una cadena de texto al concatenarse con la cadena `'dog'`.

### Describe un ejemplo cotidiano de por qué una declaración condicional se debería usar en un programa en JavaScript.

Claro, aquí tienes las respuestas:

### Ejemplo de por qué una declaración condicional se debería usar en un programa en JavaScript:

Imagina un sitio web de comercio electrónico donde los usuarios pueden agregar productos a su carrito de compras. Cuando un usuario agrega un producto al carrito, es posible que desee aplicar diferentes descuentos según ciertas condiciones, como el tipo de producto, el total de la compra, o si el usuario tiene una membresía premium. Aquí es donde las declaraciones condicionales serían útiles.

Por ejemplo, podrías usar una declaración condicional para verificar si el usuario tiene una membresía premium. Si es así, aplicarías un descuento especial al total de la compra. Si no tiene una membresía premium, podrías aplicar un descuento estándar o no aplicar ningún descuento.

```javascript
if (usuario.tieneMembresiaPremium) {
    // Aplicar descuento especial
    totalCompra *= 0.8; // 20% de descuento para miembros premium
} else {
    // Aplicar descuento estándar o no aplicar descuento
    totalCompra *= 0.9; // 10% de descuento estándar
}
```

### Da un ejempo de por qué un Bucle es últil en JavaScript.

Imaginemos que se tiene una lista de tareas pendientes en tu aplicación de gestión de tareas. Necesitas mostrar todas las tareas en tu página web. Aquí es donde un bucle sería útil para recorrer la lista de tareas y mostrar cada una de ellas en la interfaz de usuario.

```javascript
// Suponiendo que 'listaTareas' es un array que contiene todas las tareas
for (let i = 0; i < listaTareas.length; i++) {
    mostrarTareaEnInterfaz(listaTareas[i]);
}
```

En este ejemplo, el bucle `for` se ejecuta tantas veces como elementos haya en el array `listaTareas`, permitiendo que cada tarea se muestre en la interfaz. Esto hace que el código sea más eficiente y escalable, ya que no necesitas escribir una línea de código para cada tarea, sino que el bucle se encarga de manejar todas ellas de manera automatizada.

###### *Este contenido fue desarrollado con el apoyo de chatgpt*