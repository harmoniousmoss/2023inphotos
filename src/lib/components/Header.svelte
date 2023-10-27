<script>
	let expanded = false;

	function toggleMenu() {
		expanded = !expanded;
	}
</script>

<div>
	<header class="py-4 bg-gray-900 sm:py-5">
		<div class="px-4 mx-auto sm:px-6 lg:px-8 max-w-7xl">
			<div class="flex items-center justify-between">
				<div class="shrink-0">
					<a href="/" title="" class="">
						<img
							class="w-auto h-12"
							src="https://newsletter.prospera.or.id/poverty-update/assets/img/logo_prospera.png"
							alt="Logo Prospera"
						/>
					</a>
				</div>

				<!-- <div class="hidden lg:flex lg:items-center lg:space-x-4 lg:ml-12">
					<a
						href="/"
						title=""
						class="inline-flex items-center justify-center px-4 py-2.5 text-base font-medium text-white transition-all duration-200 border border-transparent rounded-full hover:bg-gray-700 focus:outline-none focus:ring-2 focus:ring-offset-2 focus:ring-ring-700"
					>
						Products
					</a>

					<a
						href="/"
						title=""
						class="inline-flex items-center justify-center px-4 py-2.5 text-base font-medium text-white transition-all duration-200 border border-transparent rounded-full hover:bg-gray-700 focus:outline-none focus:ring-2 focus:ring-offset-2 focus:ring-ring-700"
					>
						Features
					</a>

					<a
						href="/"
						title=""
						class="inline-flex items-center justify-center px-4 py-2.5 text-base font-medium text-white transition-all duration-200 border border-transparent rounded-full hover:bg-gray-700 focus:outline-none focus:ring-2 focus:ring-offset-2 focus:ring-ring-700"
					>
						Pricing
					</a>

					<a
						href="/"
						title=""
						class="inline-flex items-center justify-center px-4 py-2.5 text-base font-medium text-white transition-all duration-200 border border-transparent rounded-full hover:bg-gray-700 focus:outline-none focus:ring-2 focus:ring-offset-2 focus:ring-ring-700"
					>
						Support
					</a>
				</div> -->

				<div class="hidden sm:flex sm:items-center sm:justify-end sm:space-x-4 sm:ml-auto">
					<a
						href="/"
						title="Newsletter homepage"
						class="inline-flex items-center justify-center px-6 py-3 text-base font-medium text-white transition-all duration-200 border border-white rounded-full hover:bg-white hover:text-gray-900 focus:outline-none focus:ring-2 focus:ring-offset-2 focus:ring-white focus:ring-offset-gray-900"
						role="button"
					>
						Home
					</a>
				</div>

				<div class="flex ml-4 lg:hidden">
					<button
						type="button"
						class="inline-flex items-center p-2.5 text-white duration-200 border border-white rounded-full hover:bg-white hover:text-gray-900 transiton-all focus:outline-none focus:ring-2 focus:ring-offset-2 focus:ring-white focus:ring-offset-gray-900"
						on:click={toggleMenu}
					>
						<span class:hidden={expanded}>
							<!-- SVG for the hamburger icon -->
						</span>
						<span class:hidden={!expanded}>
							<!-- SVG for the close icon -->
						</span>
					</button>
				</div>
			</div>
		</div>
	</header>

	<section class="overflow-hidden bg-gray-900 py-20">
		<div class="px-4 mx-auto sm:px-6 lg:px-8 max-w-7xl">
			<div class="mx-auto text-center">
				<h1 class="text-4xl font-semibold text-white sm:text-5xl xl:text-7xl sm:tracking-tight">
					Visualised: The proposed state budget for 2024
				</h1>
				<p class="mt-6 text-lg leading-7 text-white lg:leading-8 lg:text-xl">
					This month we look at some interesting facets of Indonesia’s proposed state budget for
					2024 – a tight that promotes stability amid global and domestic uncertainty and targets
					inclusion and sustainability as Indonesia moves towards economic transformation.
				</p>
				<div class="mt-8">
					<a
						href="/"
						title=""
						class="inline-flex items-center justify-center px-8 py-2 text-base font-medium text-white transition-all duration-200 bg-cyan-500 border border-transparent rounded-full shadow-sm hover:bg-amber-400 focus:outline-none focus:ring-2 focus:ring-offset-2 focus:ring-cyan-500"
						role="button"
					>
						Get started
					</a>
				</div>
			</div>

			<div class="relative mt-12 sm:mt-16 lg:mt-20">
				<img class="rounded-xl" src="/discussion.png" alt="Indonesia illustration" />
			</div>
		</div>
	</section>
</div>
