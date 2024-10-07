<header>
	<div id="headings">
		<img id="logo" src="/Logo_Final_Nowords.png" alt="Earthquakers 9094" />
	</div>
</header>
<div id="matts-white-box">
	<p>
		Welcome to the homepage of The Earthquakers #9094. We are a FIRST® 
		Robotics Competition Team based out of Friends’ Central School in
		Wynnewood, Pennsylvania. Founded in 2022, we are committed to the school's mission
		of “Going Further” by creating future leaders in STEM through robotics education, 
		outreach, and innovation. 
	<div id="logos">
		<a target="_blank" href="https://www.friendscentral.org/"
			><img src="/fcs.png" alt="FCS" /></a
		><a target="_blank" href="https://www.firstinspires.org/"
			><img src="/FIRST.png" alt="FIRST" /></a
		><a target="_blank" href="https://corporate.comcast.com/"
			><img src="/comcast.png" alt="comcast" /></a
		>
	</div>
</div>

<style>
	#matts-white-box {
		background-color: white;
		display: flex;
		align-items: center;
		justify-content: center;
		flex-direction: column;
		font-size: 5vw;
	}
	#logos {
		display: flex;
		align-items: center;
		justify-content: center;
		flex-direction: row;
		width: 70%;
		gap: 5vw;
	}
	#logos > a {
		width: 50%;
	}

	#logos > a:nth-child(1) {
		filter: invert(180);
	}
	a > img {
		width: 100%;
	}

	p {
		width: 70%;
		font-size: 1.75vw;
	}

	/* this formats logo */
	#logo {
		width: 80%;
		height: auto;
	}

	header {
		background-image: url(/AYU_8063.webp);
		background-size: cover;
		background-repeat: no-repeat;
		background-position: center 45%;
		padding-top: 2px;
		padding-bottom: 5px;
		height: 90vh;
		display: flex;
		flex-direction: column;
		align-items: center;
		justify-content: center;
		text-align: center;
		color: white;
	}

	h2 {
		font-size: max(2vw, 1rem);
	}

		/* this formats the grey box */
	#headings {
		display: flex;
		align-items: center;
		justify-content: center;
		flex-direction: column;
		width: 38%;
		height: 300px;
		padding-top: 1px;
		padding-bottom: 10px;
		border-radius: 100px;
		backdrop-filter: blur(0px) brightness(50%);
	}

	@media (max-width: 900px) {
		#fcs-link {
			width: 10vw;
		}
	}

	@media (max-width: 600px) {
		#logo {
			content: url("/logo-vertical.png");
			height: 50vh;
			width: auto;
		}

		#fcs-link {
			display: none;
		}
	}
</style>
