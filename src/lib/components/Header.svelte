<script lang="ts">
	import AOS from 'aos';
	import 'aos/dist/aos.css';

	// Initialize AOS after the component has been mounted
	import { onMount } from 'svelte';

	onMount(() => {
		AOS.init();
	});
</script>

<div class="overflow-x-hidden bg-gray-50">
	<section class="relative py-10">
		<div class="relative px-4 mx-auto sm:px-6 lg:px-8 max-w-7xl">
			<div class="max-w-3xl mx-auto text-center">
				<p
					class="inline-flex px-4 py-2 text-sm text-gray-900 border border-gray-200 rounded-full font-pj"
				>
					Prospera Newsletter - 18 December 2023
				</p>
				<h1
					class="mt-5 font-bold text-transparent text-gray-900 text-8xl bg-gradient-to-b from-[#005E7F] to-[#1F3235] bg-clip-text"
				>
					Visualised: AIFED 2023 takeaways
				</h1>
				<p class="mx-auto mt-6 text-lg leading-7 text-gray-00 font-inter">
					The theme for the 2023 Annual International Forum on Economic Development and Public
					Policy was “The Fragmented World: Recalibrating Development Strategies”. A range of
					experts offered interpretations of this proposition, exploring trade, climate, technology
					and more.
				</p>

				<div class="relative inline-flex mt-10 group">
					<div
						class="absolute transitiona-all duration-1000 opacity-70 -inset-px bg-gradient-to-r from-[/44BCFF] via-[/FF44EC] to-[/FF675E] rounded-xl blur-lg group-hover:opacity-100 group-hover:-inset-1 group-hover:duration-200 animate-tilt"
					/>

					<a
						href="/"
						title=""
						class="relative inline-flex items-center justify-center px-8 py-2 text-base font-bold text-white transition-all duration-200 bg-gray-900 rounded-full hover:bg-[#005E7F]"
						role="button"
					>
						Start exploring
					</a>
				</div>
			</div>
		</div>

		<div class="mt-16 md:mt-20">
			<img
				class="object-cover object-top w-full h-auto mx-auto scale-150 2xl:max-w-screen-2xl xl:scale-100"
				src="/People.png"
				alt="People"
			/>
		</div>
	</section>
</div>
