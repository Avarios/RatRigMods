<script lang="ts">
	import { NavBar } from '$lib';
	import { AppleTouchIcon, Favicon16, Favicon32, Manifest, SafariPinnedTab } from '$lib/icons';
</script>

<svelte:head>
	<link rel="apple-touch-icon" sizes="180x180" href="{AppleTouchIcon}" />
	<link rel="icon" type="image/png" sizes="32x32" href={Favicon32} />
	<link rel="icon" type="image/png" sizes="16x16" href={Favicon16} />
	<link rel="manifest" href={Manifest} />
	<link rel="mask-icon" href={SafariPinnedTab} color="#5bbad5" />
	<title>RatRig Mod Database</title>
</svelte:head>

<div class="container mx-auto px-4">
	<NavBar></NavBar>
	<slot />
</div>
