<template>
	<section id="eventos" class="event-list">
		<div class="container">
			<h2 class="event-list-title">Mas sobre mi experiencia</h2>
		</div>
		<div class="container">
			<article class="event">
				<figure class="event-imageContiner">
					<img class="event-image" src="../assets/platzi-conf.jpg" width="500" />
				</figure>
				<div class="event-detail">
					<h3 class="event-title">PlaziConf Mexico 2018</h3>
					<p class="event-description">El evento más grande sobre gente que quiere aprender más de internet. En esté evento te comparto como tener una vida de constante aprendizaje.</p>
					<a class="event-url" href="https://www.youtube.com/watch?v=BIS7cWGgJg0" target="_blank">Ver Platica</a>
				</div>
			</article>
			<article class="event">
				<figure class="event-imageContiner">
					<img class="event-image" src="../assets/platzi-conf.jpg" width="500" />
				</figure>
				<div class="event-detail">
					<h3 class="event-title">PlaziConf Mexico 2018</h3>
					<p class="event-description">El evento más grande sobre gente que quiere aprender más de internet. En esté evento te comparto como tener una vida de constante aprendizaje.</p>
					<a class="event-url" href="https://www.youtube.com/watch?v=BIS7cWGgJg0" target="_blank">Ver Platica</a>
				</div>
			</article>
			<article class="event">
				<figure class="event-imageContiner">
					<img class="event-image" src="../assets/platzi-conf.jpg" width="500" />
				</figure>
				<div class="event-detail">
					<h3 class="event-title">PlaziConf Mexico 2018</h3>
					<p class="event-description">El evento más grande sobre gente que quiere aprender más de internet. En esté evento te comparto como tener una vida de constante aprendizaje.</p>
					<a class="event-url" href="https://www.youtube.com/watch?v=BIS7cWGgJg0" target="_blank">Ver Platica</a>
				</div>
			</article>
			<article class="event">
				<figure class="event-imageContiner">
					<img class="event-image" src="../assets/platzi-conf.jpg" width="500" />
				</figure>
				<div class="event-detail">
					<h3 class="event-title">PlaziConf Mexico 2018</h3>
					<p class="event-description">El evento más grande sobre gente que quiere aprender más de internet. En esté evento te comparto como tener una vida de constante aprendizaje.</p>
					<a class="event-url" href="https://www.youtube.com/watch?v=BIS7cWGgJg0" target="_blank">Ver Platica</a>
				</div>
			</article>
		</div>
	</section>
</template>

<script type="text/javascript">
	
</script>

<style type="text/css">
.event-list {
	display: flex;
	flex-wrap: wrap;
}

.event-list-title{
 margin-left: 20px;
}

.event {
	margin: 10px;
	width: 480px;
	flex-shrink: 0;
	border-radius: 10px;
	overflow: hidden;
	background: #f4fbff;
}

.event img {
	width: 480px;
	height: 200px;
	object-fit: cover;
}

.event-detail {
	margin: 20px 40px;
	margin-top: -40px;
	background-color: white;
	position: relative;
	padding: 20px;
	text-align: center;

}

.event-description {
	text-align: left;
}

.event-url {
	color: #056fff;
	border: 1px solid;
	padding: 5px 20px;
	text-decoration: none;
	border-radius: 5px;
}
</style>