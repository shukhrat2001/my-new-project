<script>
	export let name;
</script>

<main>
	<h1>Greetings {name}!</h1>
	<p>Visit the <a href="https://sneg.herokuapp.com ">SNEG SOFTWARE </a> to learn how to build Fast Website apps.</p>
</main>
<style>
	main {
		text-align: center;
		padding: 1em;
		max-width: 240px;
		margin: 0 auto;
	}

	h1 {
		color: #ff3e00;
		text-transform: uppercase;
		font-size: 4em;
		font-weight: 100;
	}

	@media (min-width: 640px) {
		main {
			max-width: none;
		}
	}
</style>
