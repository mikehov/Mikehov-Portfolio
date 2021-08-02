<script>
	function menuOpen() {
		document.querySelector('.home-background').classList.toggle('home-text-move');
		console.log("HALALDAS")
	}
</script>

<svelte:head>
	<meta name="description" content="Mike Hovenier's Website Portfolio" />
	<meta name="keywords" content="Mike Hovenier, Portfolio" />
	<meta name="author" content="Mike Hovenier" />
	<title>Mike Hovenier | Portfolio</title>
</svelte:head>

<section id="home-background">
	<h1 data-aos="fade-up" data-aos-duration="1000" data-aos-once="true">Mike Hovenier</h1>
	<div class="line" />
	<h2 data-aos="fade-up" data-aos-duration="1000" data-aos-delay="200" data-aos-once="true">
		Student <br />
		<span>Visual and UX Designer</span>
	</h2>
</section>

<section id="about">
	<h2 class="titleline" data-aos="fade-up" data-aos-duration="1000" data-aos-delay="0" data-aos-once="true">About me</h2>
	<!-- <div class="line"></div> -->
	<p data-aos="fade-up" data-aos-duration="1000" data-aos-delay="200" data-aos-once="true">
		Well, hello there. I'm Mike Hovenier (22). I'm a Dutch student that currently studies
		"Communcation and Multimedia Design" at the Hogeschool van Amsterdam. I consider myself as a
		Visual and/or UX Designer.
	</p>

	<div data-aos="fade-up" data-aos-duration="1000" data-aos-delay="400" data-aos-once="true">
		<img src="/mike.png" alt="Mike Hovenier" />
		<div class="flags">
			<img src="./nl.png" alt="Dutch flag" />
			<img src="./uk.png" alt="United Kingdom flag" />
			<img src="./esp.png" alt="Spain flag" />
		</div>
	</div>

	<p data-aos="fade-up" data-aos-duration="1000" data-aos-delay="600" data-aos-once="true">
		My goal is learning new skills that I can add to my current library. Even if I may don't like
		it, I think it's a good thing to have a little understanding off everything. To improve myself
		as a well sharped designer. For me design is about finding the right solution to the problem,
		besides it needs to look pretty, it is way more important that it feels/works pretty.
	</p>
</section>

<section id="project">
	<div>
		<h2 class="titleline" data-aos="fade-up" data-aos-duration="1000" data-aos-delay="0" data-aos-once="true">Projects I'm proud off</h2>
		<p class="padding-text" data-aos="fade-up" data-aos-duration="1000" data-aos-delay="200" data-aos-once="true">
			These are a few projects I'm proud of, I learned from every single one them. Projects that
			pushed me to my limits where I made the best out of them.
		</p>
	</div>
	<div class="project-blocks">
		<a href="/project-correspondent"><img src="/icon-correspondent.png" alt="Project Correspondent"></a>
		<a href="/project-awareness-campaign"><img src="/icon-awareness.png" alt="Project Awareness Campaign"></a>
		<a href="/project-generative-chessboard"><img src="/icon-chess.png" alt="Project Generative Chessboard"></a>
		<a href="/project-mysterious"><img src="/icon-mysterious.png" alt="Project Mysterious"></a>
		<a href="/project-samenoud"><img src="/icon-samenoud.png" alt="Project Samen oud"></a>
	</div>
</section>

<section id="contact">
	<h2 class="titleline" data-aos="fade-up" data-aos-duration="1000" data-aos-delay="0" data-aos-once="true">Contact</h2>
	<article data-aos="fade-up" data-aos-duration="1000" data-aos-delay="200" data-aos-once="true">
		<h3 data-aos="fade-up" data-aos-duration="1000" data-aos-delay="400" data-aos-once="true">Feel free to contact me :)</h3>
		<a href="mailto:mikehovje@gmail.com" data-aos="fade-up" data-aos-duration="1000" data-aos-delay="600" data-aos-once="true">mikehovje@gmail.com</a>
		<!-- Generator: Adobe Illustrator 25.2.3, SVG Export Plug-In . SVG Version: 6.00 Build 0)  -->
		<!-- <img src="/mail.png" alt="Picture mail" /> -->
		<span data-aos="zoom-in" data-aos-duration="1000" data-aos-delay="700" data-aos-once="true">
			<svg version="1.1" id="Layer_1" x="0" y="0" viewBox="0 0 371.1 294.71" xml:space="preserve"><style>.st0{fill:#fff}.st1{fill:#131718}.st3{fill:none;stroke:#131718;stroke-width:5;stroke-miterlimit:10}</style><g id="BIRD"><path class="st0" d="M337.2 288.3c-9.8 0-33.76-3.03-48.37-30.57-.62.59-1.28 1.36-1.73 1.99-1.42 2.28-11.86 16.95-45.09 18.02-1.98.06-3.9.1-5.73.1-30.19 0-44.62-8.45-70.15-32.26l-.4-.37-.3-.46c-17.78-27.16-46.26-47.64-66.24-47.64-1.52 0-3 .12-4.4.35l-.29.05-.3.01c-.14 0-.27.01-.41.01-8.04 0-10.06-7.41-10.81-10.2l-.07-.28-.04-.28c-.08-.58-1.88-14.29 6.13-23.49 4.54-5.22 11.12-7.87 19.55-7.87 4.66 0 9.96.83 15.76 2.48 15.44 4.52 24.08 9.82 27.86 12.57 1.95 1.42 4.02 2.47 6.17 3.12 5.61 1.7 14.46 3.72 24.75 3.72 17.65 0 32.43-5.91 43.95-17.57 32-32.39 49.84-57.42 75.09-146.69.65-2.31 2.09-4.17 4.05-5.25 1.12-.62 2.29-.93 3.47-.93 7.45 0 9.45 10.96 9.82 20.15l.01.31-.03.31c-.12 1.25-1.7 16.4-6.71 35.51 2.27-7.05 4.52-14.94 6.71-23.79.42-1.71 1.25-3.26 2.4-4.48 2.52-2.67 4.99-3.23 6.62-3.23 1.54 0 3.8.48 5.86 2.76 3.23 3.57 4.75 10.54 3.97 18.19-.36 3.56-1.14 8.78-2.81 15.34.05-.18.1-.35.14-.53.96-3.55 4.2-6.03 7.88-6.03 2.46 0 4.73 1.12 6.23 3.07 4.59 5.99 4.21 18.82 4.09 21.33l-.01.24-.04.24c-.12.8-1.62 9.83-6.85 22.25.7-.28 1.46-.43 2.24-.43 2.37 0 4.46 1.33 5.48 3.46 6.25 13.19-1.3 33.31-6.29 38.63-.53.56-1.19 1.36-1.96 2.28-2.19 2.61-5.17 6.19-9.82 10.45l.51-.01c1.63 0 3.8.97 4.54 3.7 1.24 4.63.29 19.87-13.77 27.99-4.17 2.41-8.44 4.44-12.45 6.12a5.23 5.23 0 014.1 4.99c.08 3-.7 13.12-13.82 17.73-3.75 1.32-7.77 2.25-11.62 2.91 2.24.44 4.66 1.32 7.05 3.05.77.56 1.57 1.2 2.41 1.88 6.39 5.14 18.28 14.71 55.41 15.73 3.77.1 6.73 3.13 6.73 6.9v7.04c0 2.12-.95 4.03-2.46 5.3l.83-.12-1.38 6.35c-2.42 10.95-14.52 15.85-25.46 15.85z"/><path class="st1" d="M309.65 11.36c4.69 0 5.32 15.83 5.32 15.83s-6.1 61.33-34.73 94.47c-1.95 2.45-.98 5.86 1.65 5.86 1.69 0 4.05-1.39 6.78-5.33 6.92-10 22.32-29.81 35.15-81.76.23-.91.66-1.78 1.3-2.47 1.19-1.26 2.32-1.82 3.35-1.82 3.77 0 6.21 7.52 5.35 16-1.16 11.43-7.27 44.67-40.5 84.68-1.58 3.57-.42 6.06 2.12 6.06 2.14 0 5.26-1.77 8.54-6.16 7-9.36 25.98-31.17 35.99-68.14.46-1.7 2-2.7 3.54-2.7.98 0 1.96.41 2.65 1.31 3.82 4.98 3.16 18.37 3.16 18.37s-6.46 41.28-44.3 70.47c-1.56 1.21-2.4 3.25-1.79 5.13.44 1.36 1.35 2.26 2.82 2.26 1.82 0 4.5-1.38 8.2-5 8.49-8.31 25.16-26.72 33.5-44.95.27-.6.84-.9 1.41-.9.56 0 1.13.3 1.41.89 5.32 11.23-1.49 29.34-5.51 33.62-4.24 4.52-12.14 17.2-40.63 32.32-1.88 1-3.1 3.03-2.78 5.13.27 1.78 1.29 3.04 3.44 3.04 1.97 0 4.9-1.06 9.07-3.78 11.63-7.56 22.28-15.41 22.87-16.37.02-.03.04-.04.05-.04.64 0 2.34 15.3-11.49 23.3-11.77 6.81-24.6 10.5-28.7 11.58-.97.26-1.84.77-2.52 1.51-1.99 2.13-5.16 6.43 1.67 6.43.7 0 1.5-.04 2.42-.14 9.04-.95 13.46-3.43 15.29-4.82.15-.11.32-.16.48-.16.39 0 .75.29.77.73.08 3.07-.94 9.9-10.82 13.36-10 3.51-22.12 4.14-27.17 4.25a5.106 5.106 0 00-4.43 2.73c-1.03 1.96-1.14 4.31 3.89 4.65.87.06 1.72.08 2.55.08 3.72 0 7.08-.47 10.22-.47 3.29 0 6.32.51 9.22 2.61 6.19 4.47 16.96 17.27 60.33 18.45 1.3.04 2.35 1.09 2.35 2.4v7.04c0 1.24-.93 2.28-2.16 2.41-1.93.2-5.03.43-8.86.43-10.13 0-25.37-1.64-37.55-9.98-.8-.55-1.73-.88-2.7-.92-.34-.02-.73-.03-1.13-.03-3.37 0-7.97.8-1.76 6.06 7.67 6.5 26.32 13.15 43.22 13.15 2.74 0 5.44-.17 8.03-.55-1.94 8.91-12.89 12.3-21.02 12.3-8.14 0-31.68-2.13-45.44-30.23-.63-.87-1.37-1.22-2.14-1.22-2.9 0-6.29 4.9-6.29 4.9s-8.33 14.92-41.47 15.99c-1.92.06-3.79.09-5.58.09-29.18 0-42.71-8.32-67.08-31.05-17.16-26.22-46.77-49.68-70.01-49.68-1.75 0-3.46.13-5.13.41h-.26c-4.34 0-5.57-3.56-6.47-6.88 0 0-3.65-26.24 21.22-26.24 4.04 0 8.84.69 14.53 2.31 14.6 4.27 22.72 9.17 26.44 11.88 2.29 1.67 4.8 2.97 7.51 3.79 5.47 1.66 14.97 3.92 26.06 3.92 14.81 0 32.45-4.03 47.15-18.9 31.92-32.3 50.54-57.84 76.22-148.63.29-1.04.93-2.01 1.88-2.53.46-.23.89-.35 1.3-.35m0-9c-1.94 0-3.84.5-5.64 1.48-3.02 1.66-5.23 4.49-6.21 7.97-24.96 88.26-42.51 112.92-73.96 144.75-10.64 10.77-24.35 16.23-40.75 16.23-10.26 0-19.09-2.21-23.45-3.53-1.66-.5-3.28-1.33-4.82-2.45-4.91-3.58-13.96-8.78-29.21-13.24l-.04-.01-.04-.01c-6.2-1.76-11.91-2.65-16.99-2.65-12.19 0-19.2 5.12-22.94 9.41-9.18 10.55-7.42 25.41-7.19 27.06l.08.57.15.55c.69 2.53 1.57 5.21 3.39 7.67 2.78 3.77 6.96 5.85 11.77 5.85.18 0 .36 0 .55-.01l.59-.02.58-.1c1.16-.19 2.4-.29 3.67-.29 18.29 0 45.73 20.03 62.48 45.6l.6.91.8.74c25.31 23.6 41.07 33.47 73.22 33.47 1.87 0 3.85-.03 5.87-.1 27.77-.89 40.8-10.85 46.08-16.65 15.85 24.38 39.07 27.21 48.97 27.21 12.74 0 26.91-6 29.82-19.39l1.4-6.45a11.37 11.37 0 001.71-6.03v-7.04c0-6.22-4.88-11.23-11.11-11.4-35.27-.96-46.52-9.75-52.54-14.59.22-.07.44-.15.65-.23 16-5.61 16.93-18.32 16.83-22.08a9.842 9.842 0 00-.73-3.49c2.27-1.1 4.56-2.3 6.83-3.61 16.02-9.26 17.6-26.58 15.86-33.06-.39-1.45-1.03-2.67-1.83-3.65 2.48-2.58 4.31-4.76 5.71-6.44.73-.87 1.35-1.62 1.79-2.09 6.5-6.93 14.12-28.76 7.08-43.63a10.563 10.563 0 00-5.37-5.17c3.64-9.93 4.78-16.78 4.89-17.49l.07-.47.02-.48c.19-3.91.4-17.23-5.01-24.29a12.267 12.267 0 00-9.8-4.84c-.41 0-.82.02-1.22.06.21-1.45.37-2.75.48-3.89.92-9.01-.99-17.11-5.11-21.67-2.47-2.74-5.74-4.24-9.2-4.24-1.26 0-2.83.2-4.53.88l.06-.57-.03-.63c-.02-.47-.21-4.74-1.05-9.22C320.54 5 314.39 2.36 309.65 2.36z"/></g><g id="VLEUGEL_1_"><path class="st0" d="M181.93 178.74c-19.94 0-35.84-11.81-46.06-20.7-20.63-17.93-14.86-40.44-12.61-46.91a5.345 5.345 0 015.04-3.58c1.02 0 1.99.29 2.81.8-4.66-10.4-7.52-19.49-7.95-24.12-1.46-7.02.03-14.77 3.74-19.38 2.15-2.68 4.98-4.15 7.97-4.15.39 0 .79.03 1.18.08 1.14.15 2.19.57 3.07 1.21-.59-6.85-.28-12.54-.08-16.08.03-.6.06-1.15.08-1.63.28-6.27 5.37-11.78 10.9-11.78 1.8 0 5.49.63 8.06 5.3-.83-10.44.27-16.85.61-18.5.79-3.84 3.28-12.78 9.4-12.78 3.3 0 5.79 2.46 7.41 7.32l.06.19.05.2c18.15 76.87 50.07 117.15 59.42 127.67 2.97 3.34 2.72 8.53-.54 11.58-18.22 17-35.41 25.26-52.56 25.26z"/><path class="st1" d="M168.09 11.03c1.04 0 2.12 1.18 3.14 4.25 18.46 78.19 51.19 119.22 60.43 129.62a3.795 3.795 0 01-.25 5.3c-18.88 17.61-35.23 24.04-49.49 24.04-17.12 0-31.23-9.27-43.11-19.59-18.32-15.93-13.56-35.6-11.31-42.03.13-.37.46-.56.79-.56.31 0 .62.17.77.51 3.66 8.52 19.83 33.78 27.19 39.04 2.53 2.69 4.7 3.74 6.28 3.74 2.6 0 3.58-2.85 1.86-5.92-20.06-17.29-36.04-55.23-36.77-65.84-1.9-8.63 1.74-18.38 7.24-18.38.2 0 .4.01.61.04 1.05.13 1.85 1 1.89 2.06.7 21.46 31.15 67.03 39.68 74.7 1.97 1.42 3.39 1.97 4.4 1.97 3.55 0 2.14-6.77 2.14-6.77-9.01-8.43-22.96-30.67-32.55-49.12-9.59-18.46-7.7-37.06-7.41-43.6.17-3.72 3.28-7.48 6.4-7.48 2.37 0 4.74 2.18 5.81 8.2 2.18 29.65 36.62 82.69 40.26 86.91 1.11 1.29 2.29 1.86 3.31 1.86 2.31 0 3.79-2.91 1.77-6.95-44.91-60.89-39.24-101.15-38.08-106.82.79-3.85 2.8-9.18 5-9.18m0-9c-6.74 0-11.65 5.82-13.81 16.38-.32 1.54-.88 4.94-1.01 10.04a12.9 12.9 0 00-3.24-.44c-7.96 0-15 7.36-15.39 16.08-.02.46-.05.99-.08 1.58-.14 2.56-.34 6.18-.24 10.55-4.16.17-8.01 2.22-10.9 5.82-4.53 5.64-6.34 14.55-4.69 22.87.45 4.43 2.42 11.22 5.55 19.02a9.867 9.867 0 00-5.25 5.73c-2.49 7.15-8.86 32 13.9 51.79 10.77 9.36 27.56 21.8 49.01 21.8 18.34 0 36.54-8.65 55.63-26.46 5.04-4.7 5.42-12.72.84-17.87-9.17-10.32-40.49-49.87-58.4-125.71l-.09-.39-.13-.38c-2.89-8.61-7.95-10.41-11.7-10.41z"/></g><g id="MAIL"><path d="M89.51 278.08c-.85 0-1.69-.21-2.44-.61L7.43 235.13a5.218 5.218 0 01-2.16-7.04l29.89-56.22a5.191 5.191 0 014.6-2.76c.85 0 1.69.21 2.44.61l79.63 42.33c1.23.65 2.13 1.75 2.54 3.08a5.18 5.18 0 01-.38 3.97L94.1 275.32a5.172 5.172 0 01-4.59 2.76z" fill="#f9f6c1"/><path class="st1" d="M39.77 172.1c.35 0 .7.08 1.04.26l79.63 42.34a2.2 2.2 0 01.91 2.99l-29.89 56.22a2.2 2.2 0 01-1.95 1.17c-.35 0-.7-.08-1.04-.26L8.84 232.48a2.2 2.2 0 01-.91-2.99l29.89-56.22c.39-.74 1.16-1.17 1.95-1.17m0-6c-3.04 0-5.82 1.67-7.25 4.36L2.63 226.68a8.152 8.152 0 00-.6 6.25 8.14 8.14 0 004 4.85l79.63 42.34c1.18.63 2.51.96 3.85.96 3.04 0 5.82-1.67 7.25-4.36l29.89-56.22c2.13-4 .6-8.98-3.4-11.1l-79.63-42.34a8.196 8.196 0 00-3.85-.96z"/><path class="st3" d="M38.85 171.32l16.52 54.35c1.41 4.62 6.29 7.28 10.98 5.97l55.57-15.55M90.43 275.86l-12.32-47.62M6.89 231.45l45.01-16.8"/></g><g id="SNAVEL_1_"><path d="M68.33 200.51c-.52-1.32-.44-2.68.23-3.93 2.38-4.45 12.04-6.62 13.14-6.85l1.53-.33.26 1.54c.11.63.11.67 1.55 2.93.33.53.74 1.16 1.22 1.94l1.79 2.86-3.32-.58c-.47-.08-1.02-.12-1.61-.12-4.54 0-10.91 2.37-12.68 3.32l-1.48.79-.63-1.57z" fill="#eeaf8c"/><path class="st1" d="M82 191.2c.2 1.19.39 1.29 2.98 5.42-.58-.1-1.21-.15-1.87-.15-4.86 0-11.47 2.47-13.39 3.49C67.47 194.29 82 191.2 82 191.2m2.44-3.59l-3.06.65c-1.9.4-11.5 2.67-14.15 7.61-.89 1.66-.99 3.45-.3 5.19l1.24 3.12 2.96-1.58c1.62-.86 7.76-3.14 11.97-3.14.51 0 .97.03 1.35.1l6.64 1.16-3.58-5.71c-.49-.78-.89-1.42-1.23-1.95-1.27-2-1.27-2.02-1.33-2.37l-.51-3.08z"/></g><circle id="OOG" class="st1" cx="107.38" cy="175.63" r="4.31"/></svg>
		</span>
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

	#home-background h2 {
		color: var(--white-color);
		font-size: 1.5rem;
		text-align: right;

		margin-right: 2rem;
	}

	#home-background h2 span {
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

	#home-background {
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

	#about {
		width: 100vw;
		/* height: 100vh; */
		background-color: var(--white-color);
	}

	#about h2 {
		color: var(--text-color);

		padding: 1.5rem 1.5rem 1rem 1.5rem;
		line-height: 1.5;
		position: relative;
	}

	#about p {
		padding: 0.5rem 1.5rem 1.5rem 1.5rem;
		line-height: 1.6;
	}

	#about img {
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

	#about .flags {
		display: flex;
		position: absolute;
		top: 0;
		right: 2rem;
		justify-content: center;
		align-items: center;
		flex-direction: column;
		height: 100%;
	}

	#about .flags img {
		margin: 0;
		padding: 0;
		width: 3rem;
		height: 3rem;
		border-radius: 50%;
		padding: 0rem 0rem 0rem 0rem;
		top: 0;
		border: 3px solid var(--main-color);
	}

	#about .flags img:first-child {
		right: 1.5rem;
		width: 3rem;
		height: 3rem;
	}

	#about .flags img:nth-child(2) {
		right: 1rem;
		width: 2.5rem;
		height: 2.5rem;
	}

	#about .flags img:nth-child(3) {
		right: 1.5rem;
		width: 2rem;
		height: 2rem;
	}

	#about div {
		position: relative;
	}

	#project {
		width: 100vw;
		min-height: 100vh;
		background-color: var(--main-color);
	}

	#project h2 {
		color: var(--text-color);

		padding: 1.5rem 1.5rem 1rem 1.5rem;
		line-height: 1.5;
		position: relative;
	}

	#project p {
		padding: 0.5rem 1.5rem 1.5rem 1.5rem;
		line-height: 1.6;
	}

	#project h2.titleline::after {
		background-color: var(--text-color);
	}

	#project .project-blocks {
		display: flex;
		flex-wrap: wrap;
		flex-direction: row;
		justify-content: center;
	}

	#project .project-blocks a {
		display: block;
	}

	#project .project-blocks img {
		width: 10rem;
		height: auto;
		margin: 2rem;
		border-radius: 50%;
		transition: 0.3s all ease;
		filter: grayscale(0%);
	}

	#project .project-blocks img:hover {
		transform: translateY(-1rem);
		filter: grayscale(0%);
	}

	#project .padding-text {
		padding: 1.5rem;
		margin-top: 2rem;
		background-color: var(--white-color);
		border-radius: 4px;
	}

	#contact {
		width: 100vw;
		/* height: 100vh; */
		background-color: var(--white-color);
	}

	#contact h2 {
		color: var(--text-color);

		padding: 1.5rem 1.5rem 1rem 1.5rem;
		line-height: 1.5;
	}

	#contact a {
		text-align: center;
		display: block;
		transition: 0.3s;
	}

	#contact a:hover {
		color: var(--main-color);
	}

	#contact article {
		/* background-color: var(--main-color); */
		padding: 1.5rem;
		margin: 1.5rem;
		border: 0.5rem solid var(--gray-color);
		border-radius: 1rem;

		text-align: center;
	}

	#contact img {
		width: 70%;
		height: auto;
		margin: 2rem 0rem 1rem 0rem;
		padding: 1.5em;
		transition: 0.3s;
	}

	#contact img:hover {
		transform: translate(1.2deg);
	}

	#contact h3 {
		position: relative;
		padding: 0.5rem 0.5rem 2rem 0.5rem;
		font-size: 1.5rem;
	}

	#contact h3::after {
		content: '';
		position: absolute;
		bottom: 0rem;
		left: 50%;
		transform: translateX(-50%);

		width: 100px;
		height: 3px;
		background-color: var(--main-color);
	}

	#contact a {
		padding: 1.5rem;
		font-size: 1.2rem;
	}

	#contact span {
		transition: 0.8s all ease;
	}

	#contact span svg:hover {
		transform: translateY(-1rem) rotate(10deg);
	}

	#contact span svg {
		width: 20rem;
		margin: 3rem 0rem;
		transition: 0.3s;
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

	#home-background h2 {
		margin-right: 8rem;
	}

	.line {
		margin-right: 8rem;
	}

	#about {
		max-width: 50rem;
		padding-left: 2rem;
		padding-right: 2rem;
		margin-top: 5rem;
		margin-left: auto;
		margin-bottom: 5rem;
		margin-right: auto;
	}

	#about img {
		width: 20rem;
		margin: 2rem auto 2rem auto;
	}

	#about .flags {
		right: 11rem;
	}

	#project {
		width: 100%;
		padding-left: 2rem;
		padding-right: 2rem;
		padding-top: 1rem;

		margin-top: 5rem;
		margin-left: auto;
		margin-bottom: 5rem;
		margin-right: auto;
	}

	#project div {
		max-width: 50rem;
		padding-left: 2rem;
		padding-right: 2rem;
		margin-top: 5rem;
		margin-left: auto;
		margin-bottom: 5rem;
		margin-right: auto;
	}

	#project .project-blocks img {
		filter: grayscale(100%);
	}

	#project .project-blocks img:hover {
		filter: grayscale(0%);
	}

	#contact {
		max-width: 50rem;
		padding-left: 2rem;
		padding-right: 2rem;
		margin-top: 5rem;
		margin-left: auto;
		margin-bottom: 8rem;
		margin-right: auto;
	}

	}
</style>
