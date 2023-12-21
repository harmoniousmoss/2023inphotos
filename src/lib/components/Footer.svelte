<script lang="ts">
	import AOS from 'aos';
	import 'aos/dist/aos.css';

	// Initialize AOS after the component has been mounted
	import { onMount } from 'svelte';

	onMount(() => {
		AOS.init();
	});
</script>

<section class="py-5 bg-gray-50">
	<div class="mx-auto max-w-7xl">
		<p class="text-sm text-center text-gray-700">
			© Copyright 2021, All Rights Reserved by Postcraft
		</p>
	</div>
</section>
