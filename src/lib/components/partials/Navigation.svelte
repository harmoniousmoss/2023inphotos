<script>
	let menuOpen = false;
</script>

<header class="bg-white">
	<div class="px-6 py-5 lg:px-24">
		<div class="flex items-center justify-between h-14">
			<div class="flex-shrink-0">
				<a href="https://prospera.or.id" title="" class="flex">
					<img
						class="w-auto h-12"
						src="https://prospera.or.id/wp-content/uploads/2023/06/Logo-Prospera.png"
						alt="Logo Prospera"
					/>
				</a>
			</div>

			<button
				on:click={() => (menuOpen = !menuOpen)}
				type="button"
				class="inline-flex p-1 text-black transition-all duration-200 border border-black lg:hidden focus:bg-gray-100 hover:bg-gray-100"
			>
				<!-- Show menu icon when menu is closed -->
				{#if !menuOpen}
					<svg
						class="block w-6 h-6"
						xmlns="http://www.w3.org/2000/svg"
						fill="none"
						viewBox="0 0 24 24"
						stroke="currentColor"
					>
						<path
							stroke-linecap="round"
							stroke-linejoin="round"
							stroke-width="2"
							d="M4 6h16M4 12h16M4 18h16"
						/>
					</svg>
				{/if}

				<!-- Show close icon when menu is open -->
				{#if menuOpen}
					<svg
						class="block w-6 h-6"
						xmlns="http://www.w3.org/2000/svg"
						fill="none"
						viewBox="0 0 24 24"
						stroke="currentColor"
					>
						<path
							stroke-linecap="round"
							stroke-linejoin="round"
							stroke-width="2"
							d="M6 18L18 6M6 6l12 12"
						/>
					</svg>
				{/if}
			</button>

			<div class="hidden ml-auto lg:flex lg:items-center lg:justify-center lg:space-x-10">
				<a
					href="https://prospera.or.id"
					title=""
					class="inline-flex items-center justify-center px-8 py-1 text-base font-semibold text-white bg-gray-900 rounded-full hover:text-white hover:bg-[#005E7F]"
					role="button"
				>
					Home
				</a>
			</div>
		</div>

		<!-- Mobile menu -->
		{#if menuOpen}
			<div class="w-full">
				<div class="">
					<a
						href="https://prospera.or.id"
						title=""
						class="block py-3 text-base font-semibold text-center text-gray-900 transition-all duration-200"
					>
						Home
					</a>
				</div>
			</div>
		{/if}
	</div>
</header>
