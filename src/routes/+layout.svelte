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
	<title>2023 in Photos</title>
	<meta name="robots" content="noindex" />
</svelte:head>

<slot />
