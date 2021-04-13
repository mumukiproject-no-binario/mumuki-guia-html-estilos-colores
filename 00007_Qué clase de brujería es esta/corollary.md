Así como vimos que existen los selectores de elemento y clase, también existe el _selector de id_. Este tipo de regla CSS tiene la característica de que el selector será el nombre con el que identificamos a un elemento mediante el atributo `id` y deberá llevar como prefijo el símbolo `#`. Si quisiéramos cambiar el color de fondo de un elemento que tenga como `id` el nombre `indice`, haríamos:

```css
#indice {
background-color: red;
}
```

Peeero **no aconsejamos** su uso ya que no es una regla que pueda reutilizarse entre varios elementos porque, como ya vimos, el `id` es único para cada uno. Es preferible crear una `class` para un solo elemento. :wink:
