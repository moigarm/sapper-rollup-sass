<script>
	import Nav from '../components/Nav.svelte';

	export let segment;
</script>

<style global lang="sass">

// @import './styles/main.sass'


	main 
		position: relative
		max-width: 56em
		background-color: white
		padding: 2em
		margin: 0 auto
		box-sizing: border-box
	
	h1
		font-size: 90px
</style>



<Nav {segment}/>

<main>
	<slot></slot>
</main>
