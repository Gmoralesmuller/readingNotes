# Read02

## HTML

## *¿Por qué es importante utilizar elementos semánticos en nuestro HTML?*

Es importante utilizar elementos semánticos en HTML porque proporcionan un significado claro y estructurado al contenido de la página web. Esto facilita la comprensión del contenido por parte de los motores de búsqueda, los dispositivos de asistencia y otros desarrolladores. Además, mejora la accesibilidad y la mantenibilidad del código, al hacer que sea más fácil de entender y modificar.

## *¿Cuántos niveles de encabezado existen en HTML?*

HTML ofrece seis niveles de encabezado, que van desde `<h1>` hasta `<h6>`. Cada nivel indica la importancia relativa del encabezado, donde `<h1>` es el más importante y `<h6>` el menos importante.

## *¿Cuáles son algunos de los usos para los elementos `<sup>` y `<sub>`?*

- `<sup>` se utiliza para representar texto como superíndice, como por ejemplo en exponentes o notas a pie de página.
- `<sub>` se utiliza para representar texto como subíndice, como por ejemplo en fórmulas químicas o ecuaciones matemáticas.

### Al utilizar el elemento `<abbr>`, ¿qué atributo se debe añadir para proporcionar una ampliación del término?

Al utilizar el elemento `<abbr>`, se debe añadir el atributo `title` para proporcionar una ampliación del término. Este atributo especifica el texto de información sobre herramientas, que generalmente aparece cuando el usuario pasa el cursor sobre el término abreviado. Por ejemplo:

```html


<abbr title="World Wide Web">WWW</abbr>
```

En este ejemplo, cuando el usuario pasa el cursor sobre "WWW", verá una pequeña ventana emergente que muestra "World Wide Web", que es la ampliación del término abreviado.

## CSS

### ¿De qué formas podemos añadir CSS a nuestro HTML?

Hay varias formas de añadir CSS a nuestro HTML:

- **CSS Externo:** Enlazar un archivo CSS externo utilizando la etiqueta `<link>` dentro del elemento `<head>` del HTML.
- **CSS Interno:** Utilizar la etiqueta `<style>` dentro del elemento `<head>` para escribir CSS directamente en el HTML.
- **Inline CSS:** Utilizar el atributo `style` en los elementos HTML para aplicar estilos directamente en línea.

### ¿Por qué deberíamos evitar utilizar estilos inline?

Deberíamos evitar utilizar estilos inline porque mezclar la presentación con el contenido hace que el código sea menos mantenible y más difícil de gestionar. Los estilos inline también tienen una especificidad muy alta, lo que puede causar problemas de sobrescritura y dificultar la implementación de cambios en el diseño. Es una mejor práctica separar la estructura (HTML), la presentación (CSS) y el comportamiento (JavaScript) para mantener un código más limpio y modular.

### Revisa el código a continuación y responde a las siguientes preguntas:

```css
h2 {
  color: black;
  padding: 5px;
}
```

#### ¿Qué representa el selector?

El selector `h2` representa todos los elementos de encabezado de nivel 2 (`<h2>`) en el documento HTML.

#### ¿Qué componentes son declaraciones CSS?

Las declaraciones CSS son las líneas individuales dentro de las llaves `{}`. En este caso, las declaraciones CSS son:

- `color: black;`
- `padding: 5px;`

#### ¿Qué componentes se consideran propiedades?

Las propiedades son los aspectos que se están modificando en los elementos seleccionados. En este caso, las propiedades son `color` y `padding`.

## Javascript

### ¿Qué tipo de dato es una secuencia de texto entre comillas simples?

Una secuencia de texto entre comillas simples es un tipo de dato llamado "cadena de caracteres" o simplemente "cadena". En JavaScript, las cadenas de texto se utilizan para representar texto, como palabras, frases o cualquier otra secuencia de caracteres.

### Enumera 4 tipos de operadores en JavaScript.

1. **Operadores Aritméticos:** Se utilizan para realizar operaciones matemáticas, como suma (+), resta (-), multiplicación (*), división (/), etc.
2. **Operadores de Comparación:** Se utilizan para comparar valores y devolver un resultado booleano, como igualdad (==), desigualdad (!=), mayor que (>), menor que (<), etc.
3. **Operadores Lógicos:** Se utilizan para combinar expresiones condicionales y devolver un resultado booleano, como AND (&&), OR (||), NOT (!), etc.
4. **Operadores de Asignación:** Se utilizan para asignar valores a variables, como el operador de asignación básico (=), o combinaciones de operadores aritméticos y de asignación (+=, -=, *=, /=, etc.).

### Describe un problema práctico que puedes resolver con una función.

Supongamos que estás desarrollando un sitio web para una tienda en línea y necesitas calcular el precio total de una compra en función de los productos seleccionados por el usuario y la cantidad de cada producto. Podrías crear una función en JavaScript llamada `calcularPrecioTotal` que tome como parámetros el precio unitario y la cantidad de cada producto, y devuelva el precio total de la compra. Esta función podría ser útil para calcular el precio total en tiempo real a medida que el usuario agrega o elimina productos de su carrito de compras.

## Tomando decisiones en el código

Aquí están las respuestas en formato markdown:

### Si una declaración if comprueba un **condición** y si resulta **verdadera**, entonces el código se ejecutará.

La declaración `if` en JavaScript comprueba una condición y si esa condición resulta ser verdadera, entonces el bloque de código dentro del `if` se ejecutará.

### ¿Cuál es el uso del else if?

El `else if` se utiliza en JavaScript para agregar múltiples condiciones a una declaración `if`. Se coloca después de un `if` y antes de un `else`, y permite comprobar condiciones adicionales si la primera condición resulta ser falsa.

### Enumera 3 tipos de operadores de comparación.

1. **Igualdad (==):** Compara si dos valores son iguales.
2. **Desigualdad (!=):** Compara si dos valores son diferentes.
3. **Mayor que (>):** Compara si el valor de la izquierda es mayor que el de la derecha.
4. **Menor que (<):** Compara si el valor de la izquierda es menor que el de la derecha.
5. **Mayor o igual que (>=):** Compara si el valor de la izquierda es mayor o igual que el de la derecha.
6. **Menor o igual que (<=):** Compara si el valor de la izquierda es menor o igual que el de la derecha.

### ¿Cuál es la diferencia entre los operadores lógicos && y ||?

- **&& (AND):** Retorna verdadero si ambos operandos son verdaderos.
- **|| (OR):** Retorna verdadero si al menos uno de los operandos es verdadero.

La diferencia clave entre ellos radica en cómo evalúan las condiciones:

- `&&` devuelve `true` si ambos operandos son `true`.
- `||` devuelve `true` si al menos uno de los operandos es `true`.