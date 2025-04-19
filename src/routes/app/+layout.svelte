<script lang="ts">
	import AppFooterBar from '$lib/component/global/AppFooterBar.svelte';
	import AppNavBar from '$lib/component/global/AppNavBar.svelte';

	let { children } = $props();
</script>

<AppNavBar />
{@render children()}
<AppFooterBar />
