<script lang="ts">
	import '../app.css'
	import '@fontsource-variable/bitter'
	import '@fontsource-variable/quicksand'
	import type { Snippet } from 'svelte'

	interface Props {
		children: Snippet
	}

	let { children }: Props = $props()
</script>

<svelte:head>
	<title>Aurélien Richard</title>
</svelte:head>

{@render children()}
