<script>
	import Cars from '$lib/components/card.svelte';
	import global from '$lib/images/handphone.svg';
	// import Blacks from '$lib/components/black.svelte';
</script>

<section class="hero container">
	<div class="hero-background" />
	<div class="hero-text">
		<p>Say hello to your next awessome vehicle</p>
		<p>Futuring used, wholesale and salvage cars, trucks & SUVs for sale</p>
	</div>
</section>

<section class="content">
	<div class="mt-14 justify-evenly gap-5  md:flex lg:flex">
		<div class="svg-content">
			<img src={global} alt="" width="35rem" />
			<div class="content-text">
				<p>Hyundai</p>
			</div>
		</div>
		<div class="svg-content">
			<img src={global} alt="" width="35rem" />
			<div class="content-text">
				<p>Lamborghini</p>
			</div>
		</div>
		<div class="svg-content">
			<img src={global} alt="" width="35rem" />
			<div class="content-text">
				<p>Mercedes</p>
			</div>
		</div>
	</div>
</section>

<section class="container mb-44">
	<p class="text-3xl">Active auctions</p>
	<div class="flex-col gap-5 md:flex lg:flex-row">
		<div>
			<div class="card">
				<div>
					<Cars />
				</div>
				<div class=" card-utama">
					<p>2023 Avanza Forest</p>
					<p>11.475 Miles . #72374732</p>
					<div class="mt-2 flex">
						<img src={global} alt="" width="25rem" />
						<p>Avanza Chaplin</p>
					</div>
					<div class="content-card">
						<div>
							<p>$20,0000</p>
							<p>price</p>
						</div>
						<div>
							<p>$13.0000</p>
							<p>10 bids</p>
						</div>
						<div>
							<a href="/"><button class="button-btn">Place Bid</button></a>
						</div>
					</div>
				</div>
			</div>
		</div>
		<div>
			<div class="card">
				<div>
					<Cars />
				</div>
				<div class=" card-utama">
					<p>2023 Avanza Forest</p>
					<p>11.475 Miles . #72374732</p>
					<div class="mt-2 flex">
						<img src={global} alt="" width="25rem" />
						<p>Avanza Chaplin</p>
					</div>
					<div class="content-card">
						<div>
							<p>$20,0000</p>
							<p>price</p>
						</div>
						<div>
							<p>$13.0000</p>
							<p>10 bids</p>
						</div>
						<div>
							<a href="/"><button class="button-btn">Place Bid</button></a>
						</div>
					</div>
				</div>
			</div>
		</div>
		<div>
			<div class="card">
				<div>
					<Cars />
				</div>
				<div class=" card-utama">
					<p>2023 Avanza Forest</p>
					<p>11.475 Miles . #72374732</p>
					<div class="mt-2 flex">
						<img src={global} alt="" width="25rem" />
						<p>Avanza Chaplin</p>
					</div>
					<div class="content-card">
						<div>
							<p>$20,0000</p>
							<p>price</p>
						</div>
						<div>
							<p>$13.0000</p>
							<p>10 bids</p>
						</div>
						<div>
							<a href="/"><button class="button-btn">Place Bid</button></a>
						</div>
					</div>
				</div>
			</div>
		</div>
	</div>
</section>

<section class="container mb-80">
	<div class="flex-col justify-between md:flex lg:flex-row ">
		<div class="flex-col">
			<p class="mb-2 text-3xl">Online Auto Auctions</p>
			<p>vehicles avalable for sale</p>
			<div class="flex text-5xl ">
				<div class="card-number">
					<p>0</p>
				</div>
				<div class="card-number">
					<p>5</p>
				</div>
				<div class=" card-number">
					<p>8</p>
				</div>
				<div class=" card-number">
					<p>7</p>
				</div>
				<div class="card-number">
					<p>9</p>
				</div>
			</div>
			<p class="mt-5 max-w-md">
				Lorem ipsum dolor sit amet consectetur adipisicing elit. Eum id praesentium animi
				dignissimos esse voluptatum magni beatae, deserunt dolore tempore reprehenderit repellendus,
				quae fugit? Alias tenetur praesentium ratione corrupti deserunt?
			</p>
			<button class="button-btn mt-5">Explore All Auctions</button>
		</div>
		<div>
			<img
				class="mt-5 h-96"
				src="https://cdn.dribbble.com/users/949297/screenshots/15464174/media/0ec76510fcb5d75676d40afb724cf54c.png?compress=1&resize=400x300&vertical=top"
				alt=""
			/>
		</div>
	</div>
</section>

<section class="container mb-20">
	<div class="flex-col justify-between md:flex lg:flex-row  ">
		<div>
			<p class="mb-3 text-3xl">Find car by</p>
		</div>
		<div class="flex gap-3">
			<a href="/"> <button class="button-btn">Body Type</button> </a>
			<a href="/"> <button class="button-btn">Makes</button> </a>
			<a href="/"> <button class="button-btn">Models</button> </a>
			<a href="/"> <button class="button-btn">Trending</button> </a>
		</div>
	</div>
	<div class="mt-14">
		<p>popular makes</p>
		<div class="flex-col justify-between md:flex lg:flex-row ">
			<div class="leading-5">
				<div>
					<div class="card-makes">
						<img src={global} alt="" width="35rem" />
						<div class="content-makes">
							<p>Subaru</p>
							<p>from $40k</p>
						</div>
					</div>
				</div>
				<div>
					<div class="card-makes">
						<img src={global} alt="" width="35rem" />
						<div class="content-makes">
							<p>Hyundai</p>
							<p>from $240k</p>
						</div>
					</div>
				</div>
				<div>
					<div class="card-makes">
						<img src={global} alt="" width="35rem" />
						<div class="content-makes">
							<p>Mercedes</p>
							<p>from $140k</p>
						</div>
					</div>
				</div>
				<div>
					<div class="card-makes">
						<img src={global} alt="" width="35rem" />
						<div class="content-makes ">
							<p>Mercedes</p>
							<p>from $140k</p>
						</div>
					</div>
				</div>
			</div>
			<div class=" rounded-lg bg-white p-6 shadow-xl">
				<p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Tempore, officiis.</p>
			</div>
		</div>
	</div>
</section>

<style type="postcss">
	.hero {
		height: 70vh;
		--tw-bg-opacity: 0.4;
		@apply relative flex flex-col items-center justify-center;
	}

	.hero-background {
		background-image: url(https://images.unsplash.com/photo-1511919884226-fd3cad34687c?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxzZWFyY2h8MTR8fGNhcnxlbnwwfHwwfHw%3D&auto=format&fit=crop&w=400&q=60);
		background-size: cover;
		background-attachment: fixed;
		background-repeat: no-repeat;
		background-position-y: -40rem;
		@apply absolute top-0 left-0 z-0 h-full w-full bg-black bg-opacity-70 bg-local bg-center p-5 brightness-50;
	}

	.hero-text {
		@apply z-10 flex flex-col items-center justify-items-center;
	}

	.hero-text p:is(:first-child) {
		@apply rounded-lg bg-white bg-opacity-25 py-2 px-4 text-3xl text-black;
	}

	.hero-text p {
		@apply text-center text-white;
	}

	.content {
		@apply container mb-40 font-sans;
	}

	.svg-content {
		@apply mt-2 flex;
	}

	.content-text {
		@apply flex-col pl-2 text-2xl text-black;
	}

	.card-utama {
		@apply mt-2 bg-white p-5 shadow-md;
	}

	.card {
		@apply rounded-lg bg-white p-6 shadow-xl;
	}

	.content-card {
		@apply mt-2 flex justify-between;
	}

	.button-btn {
		@apply rounded-sm bg-purple-700 px-4 py-2 text-white;
	}

	.card-number {
		@apply rounded-lg bg-white p-6 shadow-xl;
	}

	.card-makes {
		@apply mb-2 flex rounded-lg bg-white  p-6 shadow-xl;
	}

	.content-makes {
		@apply flex-col pl-5;
	}
</style>
