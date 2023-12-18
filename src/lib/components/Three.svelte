<script lang="ts">
	import AOS from 'aos';
	import 'aos/dist/aos.css';

	// Initialize AOS after the component has been mounted
	import { onMount } from 'svelte';

	onMount(() => {
		AOS.init();
	});
</script>

<section class="px-24 bg-white py-28">
	<div class="mx-auto">
		<div class="mx-auto">
			<h2 class="text-2xl font-semibold text-gray-900" data-aos="fade-down" data-aos-delay="1300">
				Asia has emerged as a significant player in an increasingly multi-polar world and the
				emerging economies in Southeast Asia can look to opportunities to develop new products and
				markets to emulate the growth of the nations to the north.
			</h2>
		</div>

		<div
			class="grid max-w-md grid-cols-1 gap-12 mx-auto mt-8 text-center sm:mt-16 md:mx-0 md:max-w-none lg:mt-16 md:text-left md:grid-cols-2 xl:gap-x-20"
		>
			<div data-aos="fade-right" data-aos-delay="1500">
				<iframe
					title="The decades long rise of East Asia"
					aria-label="Interactive line chart"
					id="datawrapper-chart-0h5VT"
					src="https://datawrapper.dwcdn.net/0h5VT/5/"
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

			<div data-aos="fade-right" data-aos-delay="1700">
				<iframe
					title="Harnessing emerging opportunities could propel Indonesia"
					aria-label="Interactive line chart"
					id="datawrapper-chart-RAXIQ"
					src="https://datawrapper.dwcdn.net/RAXIQ/3/"
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
		</div>
	</div>
</section>
