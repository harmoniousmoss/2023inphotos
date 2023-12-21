<script lang="ts">
	import AOS from 'aos';
	import 'aos/dist/aos.css';

	// Initialize AOS after the component has been mounted
	import { onMount } from 'svelte';

	onMount(() => {
		AOS.init();
	});
</script>

<section class="py-6 bg-gray-50">
	<div class="mx-auto max-w-7xl">
		<p class="text-sm text-center text-gray-700">
			© Copyright 2023 Prospera. Made with 💗 with <a
				href="https://prosperadev.net/"
				class="ml-1 text-cyan-500 hover:text-amber-400"
				target="_blank"
				rel="noopener noreferrer"
			>
				Open Source</a
			>
		</p>
	</div>
</section>
