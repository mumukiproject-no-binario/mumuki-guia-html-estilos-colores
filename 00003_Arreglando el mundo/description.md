Antes de cambiar el color de fondo, vamos a desglosar el código del ejercicio anterior :eyes:... 

```css
 body {
   background-color: black;
 }
```
... para conocer cada una de sus partes: 

* _bloque de declaraciones_: es todo lo que está entre llaves `{ }`.
* _declaración_: cada línea con forma `propiedad: valor;` dentro de ese bloque. 
* _selector_: es quien define qué parte del html se verá afectado por el bloque de declaraciones.
* _regla_: el conjunto de todas estas partes que te mencionamos.

En nuestro código:
	
<table class="table table-striped">
 <tbody>
 <tr>
   <td>Selector</td>
   <td><code>body</code></td>
 </tr>
 <tr>
   <td>Declaración</td>
   <td><code>background-color: black;</code></td>
 </tr>
 <tr>
   <td>Bloque de declaraciones</td>
   <td style="display: block;">
    <code style="display: block;">{</code>
    <code style="display: block;">&nbsp; background-color: black; </code>
    <code style="display: block;">}</code>
   </td>
 </tr>
  <tr>
   <td>Regla</td>
   <td style="display: block;">
    <code style="display: block;">body {</code>
    <code style="display: block;">&nbsp; background-color: black; </code>
    <code style="display: block;">}</code>
   </td>
  </tr>
 </tbody>
</table>
 
Pero… acá hay mucho ruido y ¡pocas nueces! :stuck_out_tongue_closed_eyes:

> Modificá el archivo `receta.css` para que el color de fondo del `<body>` sea `tan`.