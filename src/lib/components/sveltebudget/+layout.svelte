<script lang="ts">
	import '../app.css';
	import { onMount } from 'svelte';

	let showBackToTop = false;

	onMount(() => {
		window.addEventListener('scroll', handleScroll);
		return () => {
			// Cleanup
			window.removeEventListener('scroll', handleScroll);
		};
	});

	function handleScroll() {
		updateProgressBar();

		if (window.scrollY > 300) {
			showBackToTop = true;
		} else {
			showBackToTop = false;
		}
	}

	function updateProgressBar() {
		const progressBar = document.getElementById('progressBar');

		if (progressBar) {
			// Check if the element is not null
			const windowHeight =
				'innerHeight' in window ? window.innerHeight : document.documentElement.offsetHeight;
			const body = document.body;
			const html = document.documentElement;
			const docHeight = Math.max(
				body.scrollHeight,
				body.offsetHeight,
				html.clientHeight,
				html.scrollHeight,
				html.offsetHeight
			);
			const windowBottom = windowHeight + window.pageYOffset;

			const progress = (windowBottom / docHeight) * 100;
			progressBar.style.width = progress + '%';
		}
	}

	function scrollToTop() {
		window.scrollTo({
			top: 0,
			behavior: 'smooth'
		});
	}
</script>

<svelte:head>
	<title>Visualised: The proposed state budget for 2024</title>
	<meta name="robots" content="noindex" />
</svelte:head>

<!-- Progress Bar -->
<div class="fixed top-0 left-0 z-50 w-full h-1 bg-gray-300">
	<div id="progressBar" class="h-1 transition-all duration-200 bg-cyan-500" />
</div>

<!-- Back to Top Button -->
<button
	class="fixed bottom-5 right-5 z-50 w-12 h-12 flex items-center justify-center rounded-full bg-cyan-500 text-white focus:outline-none transition-opacity duration-300 hover:bg-amber-400 {showBackToTop
		? 'opacity-100'
		: 'opacity-0'}"
	on:click={scrollToTop}
>
	↑
</button>
<slot />
