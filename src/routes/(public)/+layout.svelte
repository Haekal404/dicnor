<script lang="ts">
	import { base } from '$app/paths';

	let showMenu = false;

	const toggle = () => {
		showMenu = !showMenu;
	};

	const listMenu = [
		{ text: 'Project', url: `${base}/project` },
		{ text: 'Service', url: `${base}/service` },
		{ text: 'Contact', url: `${base}/contact` },
		{ text: 'About', url: `${base}/about` }
	];
</script>

<svelte:head>
	<title>Dicnor - Homepage</title>
</svelte:head>

<nav class="flex items-center justify-between py-3 px-2 md:px-10">
	<a href={base ? base : '/'} class="flex items-center gap-1">
		<img class="h-8 w-8" src="/logo.svg" alt="Logo" />
		<span>Dicn&Oslash;r</span>
	</a>
	<ul>
		<li class="relative">
			<button aria-label="Menu" on:click={toggle} class="lg:hidden">
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
				class="absolute right-0 top-10 z-10 rounded-md bg-gray-200 p-5 leading-loose {showMenu
					? 'block'
					: 'hidden'}"
			>
				{#each listMenu as menu}
					<li>
						<a href={menu.url} on:click={toggle}>{menu.text}</a>
					</li>
				{/each}
			</ul>
			<ul class="hidden items-center gap-12 lg:flex">
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

<footer class="bg-slate-900 py-5 text-center text-white">
	<p>@Copyraight haekal apparel</p>
</footer>
