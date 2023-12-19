<script lang="ts">
	import AOS from 'aos';
	import 'aos/dist/aos.css';

	// Initialize AOS after the component has been mounted
	import { onMount } from 'svelte';

	onMount(() => {
		AOS.init();
	});
</script>

<div class="bg-gray-50">
	<section class="relative py-20 2xl:py-28">
		<div class="absolute bottom-0 right-0 overflow-hidden">
			<img
				class="w-full h-auto origin-bottom-right transform scale-150 lg:w-auto lg:mx-auto lg:object-cover lg:scale-75"
				src="https://cdn.rareblocks.xyz/collection/clarity/images/hero/1/background-pattern.png"
				alt=""
			/>
		</div>

		<div class="px-10 lg:px-24">
			<div class="grid grid-cols-1 gap-y-4 lg:items-center lg:grid-cols-2 xl:grid-cols-2">
				<div class="text-center xl:col-span-1 lg:text-left md:px-16 lg:px-0 xl:pr-20">
					<p
						class="inline-flex px-4 py-2 text-xs text-gray-900 border border-gray-200 rounded-full 2xl:text-base"
						data-aos="fade-right"
					>
						Prospera Newsletter - 18 December 2023
					</p>
					<h1
						class="font-bold text-transparent text-gray-900 bg-gradient-to-b from-[#005E7F] to-[#1F3235] bg-clip-text my-4 text-7xl 2xl:text-8xl"
						data-aos="fade-right"
					>
						Visualised: AIFED 2023 takeaways
					</h1>
					<p
						class="max-w-sm text-base leading-7 text-gray-900 2xl:max-w-lg 2xl:text-lg"
						data-aos="fade-right"
					>
						The theme for the 2023 Annual International Forum on Economic Development and Public
						Policy was “The Fragmented World: Recalibrating Development Strategies”. A range of
						experts offered interpretations of this proposition, exploring trade, climate,
						technology and more.
					</p>
					<div class="relative inline-flex mt-5 group" data-aos="fade-right">
						<div
							class="absolute transitiona-all duration-1000 opacity-70 -inset-px bg-gradient-to-r from-[/44BCFF] via-[/FF44EC] to-[/FF675E] rounded-xl blur-lg group-hover:opacity-100 group-hover:-inset-1 group-hover:duration-200 animate-tilt"
						/>

						<a
							href="#explore"
							title=""
							class="relative inline-flex items-center justify-center px-8 py-2 text-base font-bold text-white transition-all duration-200 bg-gray-900 rounded-full hover:bg-[#005E7F] 2xl:text-lg"
							role="button"
						>
							Start exploring
						</a>
					</div>
				</div>

				<div class="xl:col-span-1" data-aos="fade-left" data-aos-delay="300">
					<img class="w-full mx-auto rounded-2xl" src="/People.png" alt="" />
				</div>
			</div>
		</div>
	</section>
</div>
