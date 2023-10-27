<script lang="ts">
	import { onMount } from 'svelte';

	onMount(() => {
		window.addEventListener('scroll', () => {
			const btn = document.getElementById('backToTopBtn');
			if (btn) {
				// Check if the button is not null or undefined
				if (document.body.scrollTop > 20 || document.documentElement.scrollTop > 20) {
					btn.style.display = 'block';
				} else {
					btn.style.display = 'none';
				}
			}
		});
	});

	function topFunction() {
		document.body.scrollIntoView({ behavior: 'smooth' });
	}
</script>

<button
	id="backToTopBtn"
	on:click={topFunction}
	class="fixed hidden w-10 h-10 text-white transition-colors duration-200 ease-in rounded-full bg-blackg bottom-4 right-4 focus:outline-none hover:bg-gray-700"
>
	&#8679;
</button>
