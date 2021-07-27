<script>
	function menuOpen() {
		document.querySelector('.home-background').classList.toggle('home-text-move');
	}
</script>

<svelte:head>
	<meta name="description" content="Mike Hovenier's Website Portfolio" />
	<meta name="keywords" content="Mike Hovenier, Portfolio" />
	<meta name="author" content="Mike Hovenier" />
	<title>Mike Hovenier | Portfolio</title>
</svelte:head>

<section class="home-background">
	<h1>Mike Hovenier</h1>
	<div class="line" />
	<h2>
		Student <br />
		<span>Visual and UX Designer</span>
	</h2>
</section>

<section class="about">
	<h2 class="titleline">About me</h2>
	<!-- <div class="line"></div> -->
	<p>
		Well, hello there. I'm Mike Hovenier (22). I'm a Dutch student that currently studies
		"Communcation and Multimedia Design" at the Hogeschool van Amsterdam. I consider myself as a
		Visual and/or UX Designer.
	</p>

	<div>
		<img src="/mike.png" alt="Mike Hovenier" />
		<div class="flags">
			<img src="./nl.png" alt="Dutch flag" />
			<img src="./uk.png" alt="United Kingdom flag" />
			<img src="./esp.png" alt="Spain flag" />
		</div>
	</div>

	<p>
		My goal is learning new skills that I can add to my current library. Even if I may don't like
		it, I think it's a good thing to have a little understanding off everything. To improve myself
		as a well sharped designer. For me design is about finding the right solution to the problem,
		besides it needs to look pretty, it is way more important that it feels/works pretty.
	</p>
</section>

<section class="project">
	<h2 class="titleline">Project</h2>
	<p>
		These are a few projects I'm proud of, I learned from every single one them. Projects that
		pushed me to my limits where I made the best out of them.
	</p>
</section>

<section class="contact">
	<h2 class="titleline">Contact</h2>
	<article>
		<h3>Feel free to contact me :)</h3>
		<a href="mailto:mikehovje@gmail.com">mikehovje@gmail.com</a>
		<!-- Generator: Adobe Illustrator 25.2.3, SVG Export Plug-In . SVG Version: 6.00 Build 0)  -->
		<img src="/mail.png" alt="Picture mail" />
	</article>
</section>

<style>
	h1 {
		position: relative;
		text-align: right;

		margin-right: 2rem;
		margin-bottom: 2rem;
	}

	h2 {
		font-size: 2rem;
		position: relative;
		margin-bottom: 0.5rem;
	}

	.home-background h2 {
		color: var(--white-color);
		font-size: 1.5rem;
		text-align: right;

		margin-right: 2rem;
	}

	.home-background h2 span {
		font-size: 1rem;
		font-weight: 500;
		text-align: right;
		font-style: italic;
	}

	h1::after {
		content: '';
		position: absolute;
		bottom: -1rem;
		right: 0;

		width: 100px;
		height: 3px;
		background-color: var(--main-color);
	}

	h2.titleline::after {
		content: '';
		position: absolute;
		bottom: 0rem;
		left: 1.5rem;

		width: 100px;
		height: 3px;
		background-color: var(--main-color);
	}

	.home-background {
		width: 100vw;
		height: 100vh;
		background-image: url(./background.png);
		background-size: cover;
		background-position: left center;

		display: flex;
		flex-direction: column;
		align-items: right;
		justify-content: center;

		padding-bottom: 3rem;

		opacity: 1;
	}

	:global(.home-text-move) {
		opacity: 0;
	}

	.about {
		width: 100vw;
		/* height: 100vh; */
		background-color: var(--white-color);
	}

	.about h2 {
		color: var(--text-color);

		padding: 1.5rem 1.5rem 1rem 1.5rem;
		line-height: 1.5;
		position: relative;
	}

	.about p {
		padding: 0.5rem 1.5rem 1.5rem 1.5rem;
		line-height: 1.6;
	}

	.about img {
		position: relative;
		width: 70%;
		height: auto;
		max-width: 70vw;
		display: block;
		padding: 1rem 1rem 1rem 1rem;
		margin: auto auto;
		margin-bottom: 1.5rem;
		border-radius: 50%;
		border: 5px solid var(--main-color);
	}

	.about .flags {
		display: flex;
		position: absolute;
		top: 0;
		right: 2rem;
		justify-content: center;
		align-items: center;
		flex-direction: column;
		height: 100%;
	}

	.about .flags img {
		margin: 0;
		padding: 0;
		width: 3rem;
		height: 3rem;
		border-radius: 50%;
		padding: 0rem 0rem 0rem 0rem;
		top: 0;
		border: 3px solid var(--main-color);
	}

	.about .flags img:first-child {
		right: 1.5rem;
		width: 3rem;
		height: 3rem;
	}

	.about .flags img:nth-child(2) {
		right: 1rem;
		width: 2.5rem;
		height: 2.5rem;
	}

	.about .flags img:nth-child(3) {
		right: 1.5rem;
		width: 2rem;
		height: 2rem;
	}

	.about div {
		position: relative;
	}

	.project {
		width: 100vw;
		height: 100vh;
		background-color: var(--main-color);
	}

	.project h2 {
		color: var(--text-color);

		padding: 1.5rem 1.5rem 1rem 1.5rem;
		line-height: 1.5;
		position: relative;
	}

	.project p {
		padding: 0.5rem 1.5rem 1.5rem 1.5rem;
		line-height: 1.6;
	}

	.project h2.titleline::after {
		background-color: var(--text-color);
	}

	.contact {
		width: 100vw;
		/* height: 100vh; */
		background-color: var(--white-color);
	}

	.contact h2 {
		color: var(--text-color);

		padding: 1.5rem 1.5rem 1rem 1.5rem;
		line-height: 1.5;
	}

	.contact article {
		background-color: var(--main-color);
		padding: 1.5rem;
		margin: 1.5rem;

		text-align: center;
	}

	.contact img {
		width: 55%;
		height: auto;
		margin: 2rem 0rem 1rem 0rem;
		padding: 1.5em;
	}

	@media screen and (min-width: 48rem) {

	h1 {
		margin-right: 8rem;
		font-size: 3rem;
	}

	h2 {
		font-size: 2.4rem;
	}

	p {
		font-size: 1.2rem;
	}

	.home-background h2 {
		margin-right: 8rem;
	}

	.line {
		margin-right: 8rem;
	}

	.about {
		max-width: 50rem;
		padding-left: 2rem;
		padding-right: 2rem;
		margin-top: 5rem;
		margin-left: auto;
		margin-bottom: 5rem;
		margin-right: auto;
	}

	.about img {
		width: 20rem;
		margin: 2rem auto 2rem auto;
	}

	.about .flags {
		right: 11rem;
	}

	.project {
		width: 100%;
		padding-left: 2rem;
		padding-right: 2rem;

		margin-top: 5rem;
		margin-left: auto;
		margin-bottom: 5rem;
		margin-right: auto;
	}

	.contact {
		max-width: 50rem;
		padding-left: 2rem;
		padding-right: 2rem;
		margin-top: 5rem;
		margin-left: auto;
		margin-bottom: 5rem;
		margin-right: auto;
	}

	}
</style>
