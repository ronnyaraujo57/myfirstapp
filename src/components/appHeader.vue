<template>
	<header class="header">
		<div class="container">
			<figure class="logo">
				<img src="../assets/logo.png" height="50" alt="Logo de http://leonidasesteban.com"/>
				</figure>
			<nav class="menu">
				<ol>
					<li>
						<a class="link" href="#portafolio">Portafolio</a>
					</li>
					<li>
						<a class="link" href="#eventos">Experiencia</a>
					</li>
					<li>
						<a class="link" href="#contacto">Tabajemos Juntos</a>
					</li>
				</ol>
			</nav>
		</div>
	</header>
</template>

<script type="text/javascript">
	
</script>

<style type="text/css">
	figure {
		margin: 0;
	}
	ol,
	ul{
		margin: 0;
		padding: 0;
		list-style: none;
	}
	.header { 
		background-color: #1d252c;
		color: white;
		display: flex;
		height: 70px;
		align-items: center;
		justify-content: space-between;
	}
	.menu {
		height: inherit;
	}

	.header ol {
		display: flex;
		height: inherit;
	}

	.header ol li {
		height: inherit;
	}

	.header a {
		color: white;
		text-decoration: none;
		height: inherit;
		display: flex;
		align-items: center;
		padding: 0 10px;
	}
</style>