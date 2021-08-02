<svelte:head>
	<meta name="description" content="Mike Hovenier's Website Portfolio" />
	<meta name="keywords" content="Mike Hovenier, Portfolio" />
	<meta name="author" content="Mike Hovenier" />
	<title>Project | Awareness Campaign</title>
</svelte:head>

<section class="work">
	<h1 data-aos="fade-up" data-aos-duration="1000" data-aos-once="true">Project Awareness Campaign</h1>
	<span class="home-icon">
		<a href="/#project">
			<svg viewBox="0 0 576 512"><path d="M280.37 148.26L96 300.11V464a16 16 0 0016 16l112.06-.29a16 16 0 0015.92-16V368a16 16 0 0116-16h64a16 16 0 0116 16v95.64a16 16 0 0016 16.05L464 480a16 16 0 0016-16V300L295.67 148.26a12.19 12.19 0 00-15.3 0zM571.6 251.47L488 182.56V44.05a12 12 0 00-12-12h-56a12 12 0 00-12 12v72.61L318.47 43a48 48 0 00-61 0L4.34 251.47a12 12 0 00-1.6 16.9l25.5 31A12 12 0 0045.15 301l235.22-193.74a12.19 12.19 0 0115.3 0L530.9 301a12 12 0 0016.9-1.6l25.5-31a12 12 0 00-1.7-16.93z"/></svg>
		</a>
	</span>

	<article class="the-project">
		<div class="work-text">
			<h2 data-aos="fade-up" data-aos-duration="1000" data-aos-delay="200" data-aos-once="true">What is it?</h2>
			<p data-aos="fade-up" data-aos-duration="1000" data-aos-delay="400" data-aos-once="true">The goal of this project is to think of a <span>"Awareness campaign"</span> and make a poster out of it. 
				It's not just a simple poster, the position, size, meaning of every object in the poster is thought out. Just take a little moment to look at the poster and think about it for a little while. 
				What do you see? What is it about? The more information you indentify, the easier it is to understand the poster. 
				<br><br>
				If you still haven't found it, its awareness campaign about people with depression, it's not a secret in this picture and it shouldn't been. So if someone is depressed that
				you know of, support them and help them in the best way possible to get them back on track. If you want more information about this picture and the full meaning behind, feel free to ask.
			</p>
			<a href="img-beeldtaal.png" class="button" target="_blank" data-aos="fade-up" data-aos-delay="600" data-aos-duration="1000" data-aos-once="true">Awarness Campaign Poster</a>
		</div>
		<div class="work-images" data-aos="fade-up" data-aos-duration="1000" data-aos-delay="400" data-aos-once="true" >
			<img src="/img-beeldtaal.png" alt="Awareness campaign no text">
			<img src="/img-beeldtaal-notext.png" class="dissapear" alt="Awareness campaign">
		</div>
	</article>

</section>

<style>

	.work-images {
		position: relative;
	}

	.work-images img {
		position: absolute;
		width: 100%;
		height: auto;
		top: 0;
		left: 0;
		transition: 0.3s;
		animation-delay: 0s;
		opacity: 1;
	}

	.work-images img.dissapear:hover {
		opacity: 0;
	}

</style>