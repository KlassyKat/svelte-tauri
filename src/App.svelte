<script>
	let name = "Svelte";
	let name2 = "Tauri";
</script>

<main>
	<h1 id="svelte">{name}</h1>
	<h1 id="tauri">{name2}</h1>
</main>

<style>
	main {
		text-align: center;
		padding: 1em;
		max-width: 240px;
		margin: 0 auto;
	}
	h1 {
		text-transform: uppercase;
		font-size: 4em;
	}
	#svelte {
		color: #ff3e00;
		font-weight: 100;
	}
	#tauri {
		color: #57ADBF;
	}
</style>