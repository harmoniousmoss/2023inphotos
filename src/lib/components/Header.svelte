<script lang="ts">
	import AOS from 'aos';
	import 'aos/dist/aos.css';

	// Initialize AOS after the component has been mounted
	import { onMount } from 'svelte';

	onMount(() => {
		AOS.init();
	});
</script>

<div class="bg-white">
	<div class="relative isolate">
		<svg
			class="absolute inset-0 -z-10 h-full w-full stroke-gray-200 [mask-image:radial-gradient(100%_100%_at_top_right,white,transparent)]"
			aria-hidden="true"
		>
			<defs>
				<pattern
					id="83fd4e5a-9d52-42fc-97b6-718e5d7ee527"
					width="200"
					height="200"
					x="50%"
					y="-1"
					patternUnits="userSpaceOnUse"
				>
					<path d="M100 200V.5M.5 .5H200" fill="none" />
				</pattern>
			</defs>
			<svg x="50%" y="-1" class="overflow-visible fill-gray-50">
				<path
					d="M-100.5 0h201v201h-201Z M699.5 0h201v201h-201Z M499.5 400h201v201h-201Z M-300.5 600h201v201h-201Z"
					stroke-width="0"
				/>
			</svg>
			<rect
				width="100%"
				height="100%"
				stroke-width="0"
				fill="url(#83fd4e5a-9d52-42fc-97b6-718e5d7ee527)"
			/>
		</svg>
		<div class="mx-auto max-w-7xl lg:flex lg:items-center lg:gap-x-10">
			<div class="max-w-2xl mx-auto lg:mx-0 lg:flex-auto">
				<h1
					class="max-w-lg px-6 pt-8 font-bold tracking-tight text-transparent text-gray-900 text-7xl lg:text-9xl bg-gradient-to-r from-cyan-500 to-pink-500 bg-clip-text"
				>
					2023 in Photos
				</h1>
				<div class="flex items-center px-6 mt-6 gap-x-6">
					<a
						href="/"
						class="rounded-full bg-cyan-500 px-4 py-2.5 text-sm font-semibold text-white shadow-sm hover:bg-gray-900 lg:text-base"
						>Download video</a
					>
				</div>
			</div>
			<div class="py-6 lg:flex-shrink-0 lg:flex-grow lg:py-16">
				<video
					class="mx-auto w-[22.875rem] max-w-full drop-shadow-xl"
					width="316"
					height="684"
					autoplay
					loop
					controls
					style="border-radius: 36px;"
				>
					<source src="/Snap.mp4" type="video/mp4" />
					Your browser does not support the video tag.
				</video>
			</div>
		</div>
	</div>
</div>
