<script lang="ts">
	import AOS from 'aos';
	import 'aos/dist/aos.css';

	// Initialize AOS after the component has been mounted
	import { onMount } from 'svelte';

	onMount(() => {
		AOS.init();
	});
</script>

<section id="explore" class="px-10 py-10 bg-white lg:py-28 lg:px-24">
	<div class="mx-auto">
		<div class="mx-auto">
			<h2 class="text-2xl font-semibold text-gray-900" data-aos="fade-down">
				While the indications are that the era of “hyperglobalisation” is over, globalisation seems
				set to continue though perhaps in a different form. Fragmentation triggered by geopolitical
				shifts will be a feature of the new era.
			</h2>
		</div>

		<div
			class="grid max-w-md grid-cols-1 gap-12 mx-auto mt-8 text-center sm:mt-16 md:mx-0 md:max-w-none lg:mt-16 md:text-left md:grid-cols-2 xl:gap-x-20"
		>
			<div data-aos="fade-right" data-aos-delay="300">
				<iframe
					title="Global trade has steadied post-GFC after decades of growth"
					aria-label="Interactive line chart"
					id="datawrapper-chart-GF72u"
					src="https://datawrapper.dwcdn.net/GF72u/2/"
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

			<div data-aos="fade-right" data-aos-delay="700">
				<iframe
					title="Chinese investment in the US collapsed after 2016"
					aria-label="Stacked Columns"
					id="datawrapper-chart-DmHQs"
					src="https://datawrapper.dwcdn.net/DmHQs/1/"
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
