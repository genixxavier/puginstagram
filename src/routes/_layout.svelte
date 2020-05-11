<script>
	import Header from '../components/Header.svelte'
	export let segment
</script>

<Header {segment}></Header>

<main>
	<slot />
</main>