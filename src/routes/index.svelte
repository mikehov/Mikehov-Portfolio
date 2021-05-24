<svelte:head>
	<meta name="description" content="Mike Hovenier's Website Portfolio" />
	<meta name="keywords" content="Mike Hovenier, Portfolio" />
	<meta name="author" content="Mike Hovenier" />
	<title>Mike Hovenier | Portfolio</title>
</svelte:head>

<section class="home-background">
<h1>Mike Hovenier</h1>
<div class="line"></div>
<h2>Student <br>
	<span>Visual and UX Designer</span>
</h2>
</section>

<style>
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
	}

	h1 {
		position: relative;
		text-align: right;

		margin-right: 2rem;
		margin-bottom: 2rem;
	}

	h2 {
		color: var(--white-color);
		font-size: 1.5rem;
		text-align: right;

		margin-right: 2rem;
	}

	h2 span {
		font-size: 1rem;
		font-weight: 500;
		text-align: right;
		font-style: italic;
	}

	h1::after {
	content: "";
	position: absolute;
	bottom: -1rem;
	right: 0;

    width: 100px;
    height: 3px;
    background-color: var(--main-color);
}
</style>