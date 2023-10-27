<script lang="ts">
	import AOS from 'aos';
	import 'aos/dist/aos.css';

	// Initialize AOS after the component has been mounted
	import { onMount } from 'svelte';

	onMount(() => {
		AOS.init();
	});

	export let contentRef: HTMLElement | null;
</script>

<div>
	<header class="py-4 bg-gray-900 sm:py-5">
		<div class="px-4 mx-auto sm:px-6 lg:px-8 max-w-7xl">
			<div class="flex items-center justify-between">
				<div class="shrink-0">
					<a href="/" title="" class="">
						<img
							class="w-auto h-14"
							src="https://newsletter.prospera.or.id/poverty-update/assets/img/logo_prospera.png"
							alt="Logo Prospera"
						/>
					</a>
				</div>

				<div class="hidden sm:flex sm:items-center sm:justify-end sm:space-x-4 sm:ml-auto">
					<a
						href="https://newsletter.prospera.or.id"
						title="Newsletter homepage"
						class="inline-flex items-center justify-center px-6 py-2 text-base font-medium text-white transition-all duration-200 border border-white rounded-full hover:bg-white hover:text-gray-900 focus:outline-none focus:ring-2 focus:ring-offset-2 focus:ring-white focus:ring-offset-gray-900"
						role="button"
					>
						Home
					</a>
				</div>
			</div>
		</div>
	</header>

	<section class="py-20 overflow-hidden bg-gray-900">
		<div class="px-4 mx-auto sm:px-6 lg:px-8 max-w-7xl">
			<div class="mx-auto text-center">
				<h1
					class="text-5xl font-semibold text-transparent xl:text-7xl sm:tracking-tight bg-clip-text bg-gradient-to-r from-cyan-500 to-amber-400"
					data-aos="fade-up"
				>
					Visualised: The proposed state budget for 2024
				</h1>

				<p
					class="mt-6 text-lg leading-7 text-white lg:leading-8 lg:text-xl"
					data-aos="fade-up"
					data-aos-delay="300"
				>
					This month we look at some interesting facets of Indonesia’s proposed state budget for
					2024 – a tight budget that promotes stability amid global and domestic uncertainty and
					targets inclusion and sustainability as Indonesia moves towards economic transformation.
				</p>

				<div class="mt-8" data-aos="fade-up" data-aos-delay="500">
					<a
						href="/"
						title=""
						class="inline-flex items-center justify-center px-8 py-2 text-base font-medium text-white transition-all duration-200 border border-transparent rounded-full shadow-sm bg-cyan-500 hover:bg-amber-400 focus:outline-none focus:ring-2 focus:ring-offset-2 focus:ring-cyan-500"
						role="button"
						on:click|preventDefault={() => {
							if (contentRef) {
								contentRef.scrollIntoView({ behavior: 'smooth' });
							}
						}}
					>
						Get started
					</a>
				</div>
			</div>

			<div class="relative mt-12 sm:mt-16 lg:mt-20" data-aos="fade-up" data-aos-delay="800">
				<img class="rounded-xl" src="/discussion.png" alt="Indonesia illustration" />
			</div>
		</div>
	</section>
</div>
