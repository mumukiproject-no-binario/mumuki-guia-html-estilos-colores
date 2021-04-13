Por suerte en HTML contamos con el atributo `<class>` para poder solucionar nuestro problema :satisfied:. Gracias a él, dos o más elementos pueden compartir las mismas reglas CSS utilizando una misma _clase_ de la siguiente manera: 

```html
<section id="drama">

<article>
<h1> Relatos salvajes </h1>
<p class="descripcion"> Seis relatos que alternan la intriga, la comedia y la violencia. </p>
<p> Elenco: Ricardo Darín, Erica Rivas, Rita Cortese </p>
</article>

<article>
<h1> Esperando la carroza </h1>
<p class="descripcion"> Una anciana de ochenta años vive con su hijo y su nuera constituyendo una pesada carga para él y su mujer. </p>
<p> Elenco: China Zorrilla, Betiana Blum, Luis Brandoni </p>
</article>

</section>
```

> Copiá el siguiente código en el editor para que sólo cambien las descripciones.
>
>```css
>.descripcion {
>  color: blue;
> }
```
