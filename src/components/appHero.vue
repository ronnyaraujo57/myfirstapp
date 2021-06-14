<template>
	<section class="hero">
		<div class="container">
			<h1>
				Hola! Soy <strong>Leonidas Esteban</strong><br> Desarrollador<strong>Javascript</strong> con <br>pasión por la <strong>enseñanza</strong>
			</h1>
			<img class="hero-img" src="../assets/hero.jpg" width="500" height="300" alt="imagen principal del sitio">
		</div>
	</section>
</template>

<script>
	
</script>

<style type="text/css">
.hero { 
	height: 300px;
	/*background-image: url('../images/hero.jpg');*/
	background-color: #1b2127;
	/*background-size: 500px 300px;*/
	/*background-repeat:  no-repeat;*/
	/*background-position-x: right;*/
	display: flex;
	align-items: center;
	justify-content: space-between;
}
.hero-img {
	object-fit: cover;
}
/*.container {
	width: 1000px;
	margin: 0 auto;
	display: block;
	justify-content: space-between;
	align-items: center;
	height: 50px;
	flex-wrap: wrap;
}*/
.container {
	width: 1000px;
	margin: 0 auto;
	display: inherit;
	justify-content: inherit;
	align-items: inherit;
	height: inherit;
	flex-wrap: inherit;
}
</style>