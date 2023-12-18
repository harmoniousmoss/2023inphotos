<script lang="ts">
	import AOS from 'aos';
	import 'aos/dist/aos.css';

	// Initialize AOS after the component has been mounted
	import { onMount } from 'svelte';

	onMount(() => {
		AOS.init();
	});
</script>

<section class="px-24 bg-gray-50 py-28">
	<div class="mx-auto">
		<div class="mx-auto">
			<h2 class="text-2xl font-semibold text-gray-900" data-aos="fade-down" data-aos-delay="1900">
				Opportunities will arise from the need to respond to climate change as countries
				increasingly look to transition to renewable energy. Access to key resources (e.g. nickel,
				of which Indonesia and Australia dominate global reserves) will be significant.
			</h2>
		</div>

		<div
			class="grid max-w-md grid-cols-1 gap-12 mx-auto mt-8 text-center sm:mt-16 md:mx-0 md:max-w-none lg:mt-16 md:text-left md:grid-cols-2 xl:gap-x-20"
		>
			<div data-aos="fade-left" data-aos-delay="300">
				<iframe
					title="More needs to be done to minimise climate change impacts"
					aria-label="Interactive line chart"
					id="datawrapper-chart-Toap7"
					src="https://datawrapper.dwcdn.net/Toap7/4/"
					scrolling="no"
					frameborder="0"
					style="width: 0; min-width: 100% !important; border: none;"
					height="400"
					data-external="1"
				/><script type="text/javascript">
					!(function () {
						'use strict';
						window.addEventListener('message', function (a) {
							if (void 0 !== a.data['datawrapper-height']) {
								var e = document.querySelectorAll('iframe');
								for (var t in a.data['datawrapper-height'])
									for (var r = 0; r < e.length; r++)
										if (e[r].contentWindow === a.source) {
											var i = a.data['datawrapper-height'][t] + 'px';
											e[r].style.height = i;
										}
							}
						});
					})();
				</script>
			</div>

			<div data-aos="fade-left" data-aos-delay="2100">
				<iframe
					title="Rare minerals will be key for energy transition supply chains"
					aria-label="Map"
					id="datawrapper-chart-jQXuQ"
					src="https://datawrapper.dwcdn.net/jQXuQ/2/"
					scrolling="no"
					frameborder="0"
					style="width: 0; min-width: 100% !important; border: none;"
					height="367"
					data-external="1"
				/><script type="text/javascript">
					!(function () {
						'use strict';
						window.addEventListener('message', function (a) {
							if (void 0 !== a.data['datawrapper-height']) {
								var e = document.querySelectorAll('iframe');
								for (var t in a.data['datawrapper-height'])
									for (var r = 0; r < e.length; r++)
										if (e[r].contentWindow === a.source) {
											var i = a.data['datawrapper-height'][t] + 'px';
											e[r].style.height = i;
										}
							}
						});
					})();
				</script>
			</div>
		</div>
	</div>
</section>
