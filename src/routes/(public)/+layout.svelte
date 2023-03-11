<script lang="ts">
	let showMenu = false;

	const toggleNavbar = () => {
		showMenu = !showMenu;
	};

	const listMenu = [
		{ text: 'Project', url: '/' },
		{ text: 'service', url: 'service' },
		{ text: 'contact', url: 'contact' },
		{ text: 'About ', url: 'about' }
	];
</script>

<nav class="flex items-center justify-between py-3 px-5">
	<div class="flex items-center justify-center gap-2">
		<img class="w-8" src="/logo.svg" alt="Logo" />
		<a href="/">Dicn&Oslash;r</a>
	</div>
	<ul>
		<li class="relative">
			<button on:click={toggleNavbar}>
				<svg
					xmlns="http://www.w3.org/2000/svg"
					class="h-6 w-6"
					fill="none"
					viewBox="0 0 24 24"
					stroke="currentColor"
					><path
						stroke-linecap="round"
						stroke-linejoin="round"
						stroke-width="2"
						d="M4 6h16M4 12h16m-7 6h7"
					/></svg
				>
			</button>
			<ul
				class="absolute z-10 right-0 top-10 rounded-md bg-gray-200 p-5 leading-loose {showMenu
					? 'block'
					: 'hidden'}"
			>
				{#each listMenu as menu}
					<li>
						<a href={menu.url}>{menu.text}</a>
					</li>
				{/each}
			</ul>
		</li>
	</ul>
</nav>

<div>
	<slot />
</div>


<section>
	<div class="text-center bg-slate-900 py-5 text-white">
		<p>@Copyraight haekal apparel</p>
	</div>
</section>
