<p align="center"><img src="logo.png" height="200"></p>

<h1 align="center">LocoParallaxScroll</h1>

### Test de la possibilité de faire des ***Parallax*** avec la library [***Locomotive-Scroll***](https://github.com/locomotivemtl/locomotive-scroll.git) de [@locomotivemtl](https://github.com/locomotivemtl)

```html
<body data-scroll-container>
	<div class="body" daata-scroll data-scroll-speed="0">
		<div class="containt" data-scroll data-scroll-speed="5">
			<section>
				<div class="side">
					<h1>Lorem ipsum, dolor sit amet.</h1>
				</div>
			</section>
			<section>
				<div class="side">
					<p>Lorem ipsum dolor sit, amet consectetur adipisicing, elit. Aliquid ...</p>
				</div>
			</section>
			<section>
				<div class="side">
					<img src="image.jpg" alt="image">
				</div>
			</section>
			<section>
				<div class="side">
					<p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Consequuntur ...</p>
				</div>
			</section>
			<section>
				<div class="side">
					<h1>END !</h1>
				</div>
			</section>
		</div>
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