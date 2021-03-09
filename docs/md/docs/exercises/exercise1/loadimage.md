# P5 inline code

Adapted from [here](https://p5js.org/es/examples/image-load-and-display-image.html).

> :P5 sketch=/docs/sketches/image-canvas.js, width=720, height=560

```md
> :P5 sketch=/docs/sketches/image-canvas.js, width=720, height=560
>
> let img; 
> function setup() {
>  createCanvas(720, 560);
>  img = loadImage('/docs/exercises/cat.png'); // Cargar la imagen
> }
>
> function draw() {
>  image(img, 0, 0, 720, 560);
> }
```

> :ToCPrevNext