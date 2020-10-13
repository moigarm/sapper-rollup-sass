<script>
	import Button from './Button.svelte'
	let message = "Bye"
	import Bulma from '../bulma/Bulma.svelte'
</script>

	<Bulma/>
 <style lang="sass">
	
	img 
		max-width: 400px
	
	
</style>

<svelte:head>
	<title>Sapper project template</title>
</svelte:head>

<h1 class="title is-1  has-text-centered is-uppercase has-text-weight-bold">Great success!</h1>

<figure class="has-text-centered my-3">
	<img alt='Success Kid' src='successkid.jpg'>
	<figcaption>Have fun with Sapper!</figcaption>
</figure>

<p class="has-text-centered mb-3"><strong>Try editing this file (src/routes/index.svelte) to test live reloading.</strong></p>
<p class="has-text-centered mb-3 has-text-weight-bold">Try editing this file (src/routes/index.svelte) to test live reloading.</p>

<div class="buttons is-centered">
	<button class="button is-primary">Hello</button>
	<Button {message} modifier={"warning"}/>
</div>
