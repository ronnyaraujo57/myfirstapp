<template>
	<section id="contacto" class="contact">
		<div class="container">
			<form action="/suscripcion/" class="form-email">
				<h3>¿Creamos algo juntos?</h3>
				<input type="text" placeholder="Dejame tu email"/>
				<button>Enviar</button>
			</form>
			<div class="social">
					<a href="https://twitter.com/leonidasesteban" class="social-link twitter"></a>
					<a href="https://facebook.com/leonidasesteban" class="social-link facebook"></a>
					<a href="https://github.com/leonidasesteban" class="social-link github"></a>
					<a href="https://instagram.com/leonidasesteban" class="social-link instagram"></a>
			</div>
		</div>
	</section>
</template>

<script type="text/javascript">
	
</script>

<style type="text/css">
.contact {
	background-color: #056fff;
	color: white;
	height: 150px;
	display: flex;
	align-items: center;
	justify-content: space-between;
}

.social {
}

.social-link {
	display: inline-block;
	width: 50px;
	height: 50px;
	background-size: 50px 50px;
	margin: 0 10px;
}

.social-link.twitter {
	background-image: url('../assets/twitter.svg');
}

.social-link.facebook {
	background-image: url('../assets/facebook.svg');
}

.social-link.github {
	background-image: url('../assets/github.svg');
}

.social-link.instagram {
	background-image: url('../assets/instagram.svg');
}

.form-email input {
	border-color: gray;
	border-style: solid;
	border-radius: 5px;
	padding: 10px 20px 10px 25px;
	background-image: url('../assets/envelope.svg'); 
	background-size: 15px 15px;
	background-repeat:  no-repeat;
	background-position-y: center;
	background-position-x: 5px; 
}

.form-email button {
	display: block;
	background: transparent;
	color: white;
	padding: 10px 0;
	border-radius: 5px;
	width: 100px;
	margin-top: 10px;
}

.form-email h3 {
	font-family: 'Source Sans Pro', sans-serif;
}
</style>