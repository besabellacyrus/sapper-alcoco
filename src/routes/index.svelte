<script></script>
<style>
	.container {
		max-width: 1300px;
		margin: 0 auto;  
		padding: 1rem;
	}
	.bottle-wrapper {
		display: flex;
		justify-content: center;
		align-items: center;
	}
	.bottle {
		height: 29rem;
	}
	.bottle img {
		position: relative;
		height: 100%;
		z-index: 9;
	}
	.main-wrapper {
		display: grid;
    grid-template-rows: 0.1fr 1fr 0.3fr;

    height: 100vh;
	}
	footer {
		text-align: center;
		padding: 0 3rem; 
	}
	footer span {
		color: #48935F;
	} 
	.bg-main-wrapper {
		background-image: url(img/BG.svg);
		background-size: cover;
		background-repeat: no-repeat;
		height: 100%;
	}
	a {
		text-decoration: none;
		color: #48935F;
	}
	.bottle:after {
		content: '';
    height: 25rem;
    position: absolute;
    background: url(img/coconut-silo.svg);
    background-repeat: no-repeat;
    background-size: cover;
    width: 27rem;
    z-index: 1;
    transform: translate(-50%, -50%);
    top: 42%;
    left: 50%;
	}
	@media screen and (max-width: 425px) {
		.bottle:after { 
	    height: 17rem; 
	    width: 19rem; 
	    top: 49%; 
		}
	}
</style>

<svelte:head>
	<title>Alcoco</title>
</svelte:head>

<div class="bg-main-wrapper"> 
	<div class="container">
		<div class="main-wrapper">
			<nav>
				<div class="logo">
					<img src="img/alcoco-logo.svg" alt="">
				</div>
			</nav>
			<section class="bottle-wrapper">
				<div class="bottle">
					<img src="img/alcoco-bottle.png" alt="">
				</div>
			</section>
			<footer>
				<p>We're still building our site but you may reach us for any questions. <br> You may contact us through <span><a href="mailto:email@alcoco.com.ph">email@alcoco.com.ph</a></span> Keep safe!</p> 
			</footer>
		</div>
	</div>
</div>
 

