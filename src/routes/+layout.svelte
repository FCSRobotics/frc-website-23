<link rel="stylesheet" href="/global.css" />
<link
	rel="stylesheet"
	href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:opsz,wght,FILL,GRAD@24,400,0,0"
/>
<div id="main-thing">
	<div id="container">
		<nav>
			<a id="with-logo" href="/"
				><img id="logo" src="/logo.png" alt="Earthquakers 9094" /></a
			><a href="/first">What is FIRST?</a><a href="/about">About our team</a><a
				href="/seasons">Past seasons</a
			><a href="/sponsors">Sponsors</a><a href="/community">Community</a><a
				href="/contact">Contact us</a
			>
			<span id="spacer" />
			<div id="dropdown">
				<button id="mobile-dropdown"
					><span class="material-symbols-outlined"> menu </span></button
				>
				<div id="dropdown-content">
					<a href="/first">What is FIRST?</a><a href="/about">About our team</a
					><a href="/seasons">Past seasons</a><a href="/sponsors">Sponsors</a><a
						href="/community">Community</a
					><a href="/contact">Contact us</a>
				</div>
			</div>
		</nav>

		<main>
			<slot />
		</main>
	</div>
	<div id="footer">
		<img id="fcs-logo" src="/fcs.png" alt="FCS" />
		<img id="comcast-logo" src="/comcast.png" alt="Comcast" />
	</div>
</div>

<style>
	#main-thing {
		width: 100%;
		height: 100%;
		display: flex;
		flex-direction: column;
	}

	nav {
		background-color: var(--accent);
		/* background: linear-gradient(0.25turn, var(--primary), var(--accent)); */
		height: max(15vh, min-content);
		position: sticky;
		top: 0px;
		left: 0px;
		right: 0px;
		z-index: 999;
		color: white;
		text-decoration: none;
		display: grid;
		place-items: center;
		grid-template-columns: 1.5fr repeat(6, 1fr);
	}

	#footer {
		width: 100%;
		height: 10%;

		display: flex;
		align-items: center;
		flex-direction: row;
		justify-content: space-around;
		padding-top: 5vh;
		padding-bottom: 5vh;
		margin-top: auto;
		background-color: var(--primary);
	}

	#fcs-logo,
	#comcast-logo {
		height: 100%;
	}

	#container {
		height: min-content;
		display: flex;
		flex-direction: column;
	}
	main {
		height: 100%;
		text-align: center;
	}
	#logo {
		width: 100%;
	}
	nav > a {
		color: white;
		font-size: 1.3vw;
		width: 100%;

		display: flex;
		align-items: center;
		justify-content: center;
		text-decoration: none;
		scale: 1;
		transition: scale 0.5s;
	}

	nav > a:hover:not(:nth-child(1)) {
		/* font-size: 2rem; */
		scale: 1.5;
	}

	#dropdown {
		display: none;
	}

	#spacer {
		display: none;
	}

	#dropdown-content {
		display: none;
		position: absolute;
		right: 0px;
		padding: 2vw;
		background-color: var(--primary);
		z-index: 9999;
		border-radius: 15px;
	}

	#dropdown-content > a {
		color: white;
	}

	@media (max-width: 1000px) {
		nav > a {
			display: none;
		}
		nav > a#with-logo {
			display: flex;
			/* content: url("/logo-vertical.png"); */
		}

		#spacer {
			display: block;
		}

		nav {
			grid-template-columns: 2fr 3fr 1fr;
			height: 20vh;
		}

		#dropdown {
			display: block;
		}

		#mobile-dropdown {
			color: white;
			background: none;
			border: none;
		}

		#dropdown:hover > #dropdown-content {
			display: flex;
			flex-direction: column;
			gap: 2vw;
		}
	}
</style>
