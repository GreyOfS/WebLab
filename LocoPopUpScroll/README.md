<p align="center"><img src="logo.png" height="200"></p>

<h1 align="center">LocoPopUpScroll</h1>

### Test de la possibilité de faire apparaitre des éléments avec la library [***Locomotive-Scroll***](https://github.com/locomotivemtl/locomotive-scroll.git) de [@locomotivemtl](https://github.com/locomotivemtl)

```html
<body data-scroll-container>
	<div class="body" data-scroll data-scroll-speed="0">
		<section>
			<h1 data-scroll data-scroll-speed="5">Lorem, ipsum dolor sit amet.</h1>
		</section>

		<section>
			<p data-scroll data-scroll-speed="5">Lorem, ipsum dolor sit amet consectetur adipisicing, elit. Consequatur ...</p>	
		</section>

		<section>
			<img src="image.jpg" alt="image" data-scroll data-scroll-speed="5">
		</section>

		<section>
			<p data-scroll data-scroll-speed="5">Lorem ipsum dolor sit amet consectetur adipisicing elit. Maiores ...</p>
		</section>

		<section>
					<h1 data-scroll data-scroll-speed="5">END !</h1>
		</section>
	</div>
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