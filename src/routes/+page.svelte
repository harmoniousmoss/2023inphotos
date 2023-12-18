<script lang="ts">
	import Header from '$lib/components/Header.svelte';
	import BackToTop from '$lib/components/partials/BackToTop.svelte';
	import Navigation from '$lib/components/partials/Navigation.svelte';

	let contentRef: HTMLElement | null = null;
</script>

<Navigation />
<Header />
<BackToTop />
