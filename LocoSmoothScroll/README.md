<p align="center"><img src="logo.png" height="200"></p>

<h1 align="center">LocoSmoothScroll</h1>

### Test de la fonction ***Smooth*** de la library [***Locomotive-Scroll***](https://github.com/locomotivemtl/locomotive-scroll.git) de [@locomotivemtl](https://github.com/locomotivemtl)

```html
<body data-scroll-container>
	<section data-scroll-section>
		<h1>Lorem, ipsum dolor sit amet.</h1>
	</section>

	<section data-scroll-section>
		<p>Lorem, ipsum dolor sit amet consectetur adipisicing, elit. Consequatur...</p>	
	</section>

	<section data-scroll-section>
		<img src="image.jpg" alt="image">
	</section>

	<section data-scroll-section>
		<p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Maiores ...</p>
	</section>

	<section data-scroll-section>
		<h1>END !</h1>
	</section>
</body>
```

```html
<script src="locomotive-scroll.min.js"></script>
<script>
    const scroll = new LocomotiveScroll({
	    el: document.querySelector('[data-scroll-container]'),
	    smooth: true,
	    lerp: 0.1
	});
</script>
```