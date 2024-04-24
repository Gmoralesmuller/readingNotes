# Read06 

##Javascript 

### ¿Cómo le describirías un objeto a un amigo sin conocimiento técnico con el que creciste?

Imagina que un objeto es como una caja mágica que puede contener muchas cosas diferentes. Cada cosa dentro de la caja tiene un nombre y un valor. Por ejemplo, puedes tener una caja llamada "perro" que contiene información sobre un perro, como su nombre, edad y color. Es una forma organizada de guardar información relacionada.

### ¿Cuáles son algunas de las ventajas de crear objetos literales?

    - Sencillez: Son fáciles de crear y entender.
    - Flexibilidad: Puedes agregar o eliminar propiedades fácilmente.
    - Organización: Ayudan a organizar y estructurar tu código, especialmente cuando trabajas con datos complejos.
    - Reutilización de código: Puedes crear múltiples objetos con la misma estructura base.

### ¿En qué se diferencian los objetos de los arrays?

    - Objetos: Almacenan datos en pares clave-valor, donde cada valor está asociado con una clave única. Las claves pueden ser cadenas o símbolos.
    - Arrays: Almacenan datos en una secuencia ordenada, donde cada elemento tiene un índice numérico que indica su posición en la secuencia.

### Da un ejemplo acerca de los momentos en los que necesitarías utilizar bracket notation para acceder a la propiedad de un objeto en vez de dot notation.

    - *Bracket notation:* Se utiliza cuando el nombre de la propiedad que queremos acceder está almacenado en una variable o cuando la clave contiene caracteres especiales o espacios.
    - *Dot notation:* Se utiliza cuando conocemos el nombre de la propiedad de antemano y este es un identificador válido (no contiene caracteres especiales ni espacios).
Por ejemplo, si tienes un objeto persona y quieres acceder a su propiedad edad, puedes usar dot notation (persona.edad). Pero si el nombre de la propiedad está almacenado en una variable, debes usar bracket notation (persona[nombrePropiedad]).

### Evalúa el siguiente código. ¿A qué se refiere el término this y cuál es la ventaja de utilizarlo?

```
const dog = {
  name: 'Spot',
  age: 2,
  color: 'white with black spots',
  humanAge: function (){
    console.log(`${this.name} is ${this.age*7} in human years`);
  }
}
```

En el contexto del código que proporcionaste, "this" se refiere al objeto actual en el que se está ejecutando el método humanAge(). La ventaja de utilizar "this" es que te permite acceder a las propiedades del objeto dentro de su propia definición de función. Esto hace que el código sea más flexible y reutilizable, ya que el método puede funcionar con cualquier objeto que tenga las mismas propiedades, sin importar cuál sea su nombre. En este caso, el método humanAge() puede funcionar con cualquier objeto que tenga propiedades name y age.

## DOM

1. **¿Qué es el DOM?**:
   - El DOM, o Document Object Model (Modelo de Objetos del Documento), es una interfaz de programación para documentos HTML y XML. Define la estructura lógica de documentos y la forma en que se accede y manipula un documento. Básicamente, representa la página web como un árbol de objetos, donde cada nodo representa un elemento del documento, como etiquetas HTML, atributos y texto.

2. **Relación entre el DOM y JavaScript**:
   - JavaScript interactúa con el DOM para hacer que las páginas web sean dinámicas e interactivas. A través de JavaScript, puedes acceder a los elementos del DOM, modificar su contenido, estilo y atributos, agregar o eliminar elementos, y responder a eventos del usuario. El DOM proporciona una forma estructurada y jerárquica de representar la página web, y JavaScript actúa como el lenguaje de programación que permite manipular esta estructura de manera dinámica y en tiempo real.


#### Este contenido se desarrollo con el apoyo de chatgpt.