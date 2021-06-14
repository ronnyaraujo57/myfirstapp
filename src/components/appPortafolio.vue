<template>
	<section id="portafolio" class="portfolio">
		<div class="container">
			<h2>Portafolio</h2>
			<article class="project">
				<div class="project-details">
					<h3 class="project-title">Plazi Video</h3>
					<h6 class="project-course">React Native / React</h6>
					<p class="project-date"><small><strong>Fecha: </strong> 01/07/2018</small></p>
					<p class="project-url"><small><strong>Puedes verlo en:</strong> www.plazi.com/native</small></p>
					<p class="project-description">Platzi Video fue el resultado de 3 meses de trabajo para crear la mejor app para enseñar el funcionamiento de React y React Native. Desde crear un vista-detalle, hasta patrones avanzados de nevegación, este proyecto ha sido el ejemplo de futuros creadores de aplicaciones multiplataforma</p>
				</div>
				<figure class="project-imageContainer">
					<img class="project-image" width="500" src="../assets/platzi-video-react-native.png" alt="proyecto del curso de React
				Native"/>
				</figure>
			</article>
			<article class="project">
				<div class="project-details">
					<h3 class="project-title">Plazi Video</h3>
					<h6 class="project-course">React Native / React</h6>
					<p class="project-date"><small><strong>Fecha: </strong> 01/07/2018</small></p>
					<p class="project-url"><small><strong>Puedes verlo en:</strong> www.plazi.com/native</small></p>
					<p class="project-description">Platzi Video fue el resultado de 3 meses de trabajo para crear la mejor app para enseñar el funcionamiento de React y React Native. Desde crear un vista-detalle, hasta patrones avanzados de nevegación, este proyecto ha sido el ejemplo de futuros creadores de aplicaciones multiplataforma</p>
				</div>
				<figure class="project-imageContainer">
					<img class="project-image" width="500" src="../assets/platzi-video-react-native.png" alt="proyecto del curso de React
				Native"/>
				</figure>
			</article>
		</div>
	</section>
</template>

<script type="">
	
</script>

<style type="text/css">
.portfolio {
	background: #fafafa;
	padding: 20px;
}

.project {
	/*border-top: 10px solid red;
	border-right: 10px solid green;
	border-left: 10px solid orange;
	border-bottom: : 10px solid pink;*/
	/*border-top-color: red;
	border-width: 15px;
	border-style: solid;*/
	border: 1px solid gray;
	border-radius: 10px;
	/*margin: 10px;*/
	margin-bottom: 15px;
	padding: 20px;
	background: white;
	display: flex;
	align-items: center;
	justify-content: space-between;

}

.project-course,
.project-date,
.project-url {
	margin: 10px 0;
}

.project-description {
	font-size: 20px;
}

.project strong {
	font-family: 'Fjalla One', sans-serif;
}

.project-title {
	font-size: 30px;
	margin-top: 0;
	margin-bottom: 10px;
}
.project-details {
	width: 500px;
}

.project-imageContainer {
	width: 500px;
}
</style>