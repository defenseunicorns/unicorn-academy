<script lang="ts">
	import { Typography, Box, type SSX } from '@defense-unicorns/unicorn-ui';

	const ssx: SSX = {
		$self: {
			width: '100vw',
			height: '100vh',
			display: 'flex',
			flexDirection: 'column',
			justifyContent: 'center',
			alignItems: 'center',
			'& > h1': {
				marginBlock: 'unset'
			}
		}
	};
</script>

<Box {ssx}>
	<Typography variant="h1">🦄 Unicorn Academy</Typography>
	<Typography variant="h2">🚧 Coming Soon...</Typography>
</Box>
