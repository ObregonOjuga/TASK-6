---
layout: ../../layouts/BlogPostLayout.astro
title: Patriomonio Cultural de Escuela Ideo
draft: false
date: 2022/03/10
short: Investigación del patrimonio de escuela Ideo
---




Algunos recursos que te pueden resultar interesantes son:
- [Da estilo a tus títulos](http://cssdemos.tupence.co.uk/text-shadow.htm)
- [Ejemplos de animaciones](http://css3.bradshawenterprises.com/animations/)
- [Sliding de imágenes](http://css3.bradshawenterprises.com/sliding/)

Astro te permite trabajar de una forma avanzada con las hojas de estilo,
para conocer más detalles puedes consultar la [documentación del proyecto](https://docs.astro.build/en/guides/styling/)

## Algunos trucos:

### Dar espacio alrededor de un texto

Para genererar un texto con espacio alrededor.

<div class="example" style="padding: 1em">
Ejemplo
</div>

```css
p {
    padding: 1em;
}
```

<style>
.example {
    border: 1px dashed gray;
}
</style>

### Espacio después de un párrafo

Cada párrafo tiene

<div class="example">
    <p>Párrafo 1</p>
    <p>Párrafo 2</p>
</div>

```css
p {
    margin-bottom: 1em;
}
```

### Centrar un texto

Cada párrafo tiene

<div class="example" style="text-align: center">
    Texto centrado
</div>

```css
p {
    text-align: center;
}
```