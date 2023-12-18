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
	<div class="flex mx-auto">
		<div class="w-1/2">
			<h2
				class="max-w-3xl text-2xl font-semibold text-gray-900"
				data-aos="fade-right"
				data-aos-delay="900"
			>
				Fragmentation has seen the decline of economic relationships between some countries, while
				creating opportunities for others who a ready to step in to fill the gaps.
			</h2>
		</div>

		<div class="w-1/2">
			<div data-aos="fade-right" data-aos-delay="1100">
				<iframe
					title="Vietnam filled the China-sized gap in US EV battery imports"
					aria-label="Stacked Columns"
					id="datawrapper-chart-2vgUD"
					src="https://datawrapper.dwcdn.net/2vgUD/1/"
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
