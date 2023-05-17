<script lang="ts">
	import { Typography, Box, Button, type SSX } from '@defense-unicorns/unicorn-ui';
	const ssx: SSX = {
		$self: {
			width: '100vw',
			height: '100vh',
			display: 'flex',
			flexDirection: 'column',
			justifyContent: 'center',
			alignItems: 'center'
		}
	};

	let pathname = window.location.pathname;
</script>

<Box {ssx}>
	<Typography variant="h3">🚨 Page Not Found</Typography>
	<Button element="a" href="/" variant="raised" color="primary">Home</Button>
</Box>
