<script>
	import '../app.css';

	// NOTE: bootstrap import
	// import 'bootstrap/dist/css/bootstrap.min.css';
	// import 'bootstrap/dist/js/bootstrap.min.js';
</script>

<svelte:head>
	<link rel="preconnect" href="https://fonts.googleapis.com" />
	<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin="anonymous" />
	<link href="https://fonts.googleapis.com/css2?family=Righteous&display=swap" rel="stylesheet" />
</svelte:head>

<main class="font-righteous">
	<slot />
</main>
