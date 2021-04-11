<p align="center"><img src="icon.png" height="200"></p>

<h1 align="center">LogIn</h1>

### LogIn page basé sur le movement du [***Neumorphism***](#neumorphism)

```html
<body>
	<div class="frame">
		<h1 class="titre">LogIn</h1>
		<form action="" method="POST">
			<input type="text" name="username" id="username" placeholder="Username">
			<input type="password" name="password" id="password" placeholder="Password">
			<input type="button" name="login" id="login" value="LogIn">
		</form>
	</div>
</body>
```

```css
* {
	margin: 0px;
	padding: 0px;
	color: white;
	text-decoration: none;
	font-family: sans-serif;
}

body {
	background-color: #202020;
	height: auto;
	width: auto;
}

.frame {
	border-style: solid;
	border-radius: 50px;
	height: auto;
	width: auto;
	margin:2% 10% 0px 10%;
	padding: 5%;
}

.titre {
	text-align: center;
	border-style: none none solid none;
	margin: 0% 10% 10% 10%;
	padding: 5%;
}

.frame form {
	height: auto;
	display: flex;
	flex-direction: column;
}

.frame form input {
	background-color: #202020;
	height: 50px;
	border-radius: 25px;
	padding: 5px;
	margin: 2%;
	border: none;
	box-shadow: -5px -5px 10px #505050, 5px 5px 10px #101010;
}

#login:hover{	
	box-shadow: inset -5px -5px 10px #505050, inset 5px 5px 10px #101010;
}
```

## NEUMORPHISM
<p align="center"><img src="neumorphism.png"></p>