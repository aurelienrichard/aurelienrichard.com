<script lang="ts">
	import { Canvas } from '@threlte/core'
	import Scene from '$lib/components/Scene.svelte'
</script>

<div class="fixed top-0 left-0 -z-10 h-screen w-screen">
	<Canvas>
		<Scene />
	</Canvas>
</div>
