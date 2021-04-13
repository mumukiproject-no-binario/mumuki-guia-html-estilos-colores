Olvidémonos por un momento de nuestra receta e imaginemos la estructura de una página web para ver películas argentinas :tv: en la que vamos a tener: 

* un `<section>` por cada género de películas que haya;
* un `<article>` por cada película;
* un `<h1>` con el nombre de cada una;
* un párrafo `<p>` para la descripción y otro para el elencos.

Nuestro HTML quedaría de esta forma: 

```html
<section id="drama">

<article>
<h1> Relatos salvajes </h1>
<p> Seis relatos que alternan la intriga, la comedia y la violencia. </p>
<p> Elenco: Ricardo Darín, Erica Rivas, Rita Cortese </p>
</article>

<article>
<h1> Esperando la carroza </h1>
<p> Una anciana de ochenta años vive con su hijo y su nuera constituyendo una pesada carga para él y su mujer. </p>
<p> Elenco: China Zorrilla, Betiana Blum, Luis Brandoni </p>
</article>

</section>
```

¿Y si quisiéramos poner de otro color la descripción de las películas? :thinking: Deberíamos, desde nuestro archivo CSS, cambiar el color de esos `<p>`:

> Si creamos la regla:
>
> ```css
> p {
>	color: blue;
> }
```
