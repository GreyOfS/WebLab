<p align="center"><img src="logo.png"></p>

<h1 align="center">LocoSmoothScroll</h1>

### Test de la fonction ***Smooth*** de la library [***Locomotive-Scroll***](https://github.com/locomotivemtl/locomotive-scroll.git) de [@locomotivemtl](https://github.com/locomotivemtl)

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