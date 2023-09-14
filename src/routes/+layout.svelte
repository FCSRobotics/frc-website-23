<link rel="stylesheet" href="/global.css" />

<div id="container">
	<nav>
		<a id="with-logo" href="/"
			><img id="logo" src="/logo.png" alt="Earthquakers 9094" /></a
		><a href="/first">What is FIRST?</a><a href="/about">About our team</a><a
			href="/seasons">Past seasons</a
		><a href="/sponsors">Sponsors</a><a href="/contact">Contact us</a>
	</nav>

	<main>
		<slot />
	</main>
</div>

<style>
	nav {
		background: linear-gradient(0.25turn, var(--primary), var(--accent));
		height: 15vh;
		position: sticky;
		top: 0px;
		left: 0px;
		right: 0px;
		z-index: 999;
		color: white;
		text-decoration: none;
		display: grid;
		place-items: center;
		grid-template-columns: 1fr repeat(5, 1fr);
	}

	#container {
		height: 100%;
		display: flex;
		flex-direction: column;
	}
	main {
		height: 100%;
	}
	#logo {
		width: 100%;
	}
	nav > a {
		color: white;
		font-size: 1.3vw;
		width: 100%;
		height: 100%;
		display: flex;
		align-items: center;
		justify-content: center;
		text-decoration: none;
		scale: 1;
		transition: scale 0.5s;
	}

	a:hover:not(:nth-child(1)) {
		/* font-size: 2rem; */
		scale: 1.5;
	}

	@media (max-width: 600px) {
		nav > a {
			display: none;
		}
		nav > a#with-logo {
			display: flex;
		}

		nav {
			grid-template-columns: 1fr 1fr;
		}
	}
</style>
