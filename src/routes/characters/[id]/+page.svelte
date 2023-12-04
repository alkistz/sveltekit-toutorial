<script lang="ts">
	import Character from '$lib/components/Character.svelte';
	export let data;

	$: character = data?.character;
</script>

<svelte:head>
	<title>About</title>
</svelte:head>

<Character {...character} />

<style>
</style>
