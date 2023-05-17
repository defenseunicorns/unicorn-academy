<script lang="ts">
	import { Theme } from '@defense-unicorns/unicorn-ui';
</script>

<Theme>
	<main><slot /></main>
</Theme>

<style>
	main {
		height: 100vh;
		width: 100vw;
		overflow-y: scroll;
		overflow-x: hidden;
	}
	/* Roboto normal (400) */
	@import '@fontsource/roboto';
	@import '@fontsource/roboto/500';
	@import '@fontsource/roboto/300';
</style>
