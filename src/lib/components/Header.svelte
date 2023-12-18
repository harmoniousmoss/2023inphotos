<script lang="ts">
	import AOS from 'aos';
	import 'aos/dist/aos.css';

	// Initialize AOS after the component has been mounted
	import { onMount } from 'svelte';

	onMount(() => {
		AOS.init();
	});
</script>

<div class="min-h-screen px-10 overflow-x-hidden bg-gray-50">
	<section class="relative py-10">
		<div class="relative mx-auto max-w-7xl">
			<div class="mx-auto text-center">
				<p
					class="inline-flex px-4 py-2 text-sm text-gray-900 border border-gray-200 rounded-full lg:text-base"
					data-aos="fade-down"
				>
					Prospera Newsletter - 18 December 2023
				</p>
				<h1
					class="mt-5 font-bold text-transparent text-gray-900 bg-gradient-to-b from-[#005E7F] to-[#1F3235] bg-clip-text text-5xl lg:text-8xl"
					data-aos="fade-down"
					data-aos-delay="300"
				>
					Visualised: AIFED 2023 takeaways
				</h1>
				<p
					class="mx-auto mt-6 text-base leading-7 text-gray-900 lg:text-xl"
					data-aos="fade-down"
					data-aos-delay="500"
				>
					The theme for the 2023 Annual International Forum on Economic Development and Public
					Policy was “The Fragmented World: Recalibrating Development Strategies”. A range of
					experts offered interpretations of this proposition, exploring trade, climate, technology
					and more.
				</p>

				<div class="relative inline-flex mt-10 group" data-aos="fade-down" data-aos-delay="700">
					<div
						class="absolute transitiona-all duration-1000 opacity-70 -inset-px bg-gradient-to-r from-[/44BCFF] via-[/FF44EC] to-[/FF675E] rounded-xl blur-lg group-hover:opacity-100 group-hover:-inset-1 group-hover:duration-200 animate-tilt"
					/>

					<a
						href="#explore"
						title=""
						class="relative inline-flex items-center justify-center px-8 py-2 text-base font-bold text-white transition-all duration-200 bg-gray-900 rounded-full hover:bg-[#005E7F]"
						role="button"
					>
						Start exploring
					</a>
				</div>
			</div>
		</div>

		<div class="mt-10" data-aos="fade-up" data-aos-delay="900">
			<img src="/People.png" alt="People" />
		</div>
	</section>
</div>
