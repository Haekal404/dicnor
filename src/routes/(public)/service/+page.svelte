
<section class="hero container mb-10 mt-10">
	<div class="hero-background" />
	<div class="hero-text">
		<p>Find your next awessome vehicle</p>
		<div class="flex justify-between rounded-lg bg-white  p-2 shadow-xl">
			<h1 class="text-black">Lorem ipsum dolor sit amet.</h1>
			<input class="w-16 rounded-sm bg-purple-700 text-center" type="text" placeholder="searh" />
			
		</div>
	</div>
</section>

<section class="container">
	<h1>Trending near you</h1>
</section>

<style type="postcss">
	.hero {
		height: 70vh;
		width: 90%;
		@apply relative flex flex-col items-start justify-center;
	}

	.hero-background {
		@apply absolute top-0 left-0 z-0 h-full w-full rounded-lg bg-blue-800 bg-center  p-5;
	}

	.hero-text {
		@apply z-10 flex-col items-start justify-items-center;
	}

	.hero-text p:is(:first-child) {
		@apply mb-5 text-3xl text-white;
	}
</style>
