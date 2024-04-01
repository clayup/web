<script>
	import Logo from '$lib/components/Logo.svelte';

	import img_fav1 from '$lib/images/potery/fav/IMG-20231220-WA0006.jpg';
	import img_fav2 from '$lib/images/potery/fav/IMG-20240221-WA0007.jpg';
	import img_fav3 from '$lib/images/potery/fav/IMG_20240107_204454.jpg';
	import img_fav4 from '$lib/images/potery/fav/IMG_20240221_163008.jpg';
	import img_fav5 from '$lib/images/potery/fav/IMG_20240225_172533.jpg';
	import img_fav6 from '$lib/images/potery/fav/IMG_20240221_175642.jpg';


	import img_1 from '$lib/images/potery/IMG_20240221_100125.jpg';
	import img_2 from '$lib/images/potery/IMG_20240221_163157.jpg';
	import img_3 from '$lib/images/potery/IMG_20240221_163809.jpg';
	import img_4 from '$lib/images/potery/IMG-20230705-WA0000.jpg';
	import img_5 from '$lib/images/potery/IMG-20230903-WA0021.jpg';
	import img_6 from '$lib/images/potery/IMG-20231001-WA0013.jpg';
	import img_7 from '$lib/images/potery/IMG-20231001-WA0024.jpg';
	import img_8 from '$lib/images/potery/IMG-20231001-WA0045.jpg';
	import img_9 from '$lib/images/potery/IMG-20231220-WA0005.jpg';
	import img_10 from '$lib/images/potery/IMG-20240221-WA0001.jpg';
	import img_11 from '$lib/images/potery/IMG-20240221-WA0003.jpg';
</script>


<div class="flex items-center justify-center min-h-48">
	<Logo />
</div>


<div class="wrapper">
	<p>wsh</p>
	<div class="flex flex-wrap gap-9 justify-center">
		<img src={img_fav1} alt="potery" class="md:max-h-[300px] max-w-full" />
		<img src={img_fav2} alt="potery" class="md:max-h-[300px] max-w-full" />
		<img src={img_fav3} alt="potery" class="md:max-h-[300px] max-w-full" />
		<img src={img_fav4} alt="potery" class="md:max-h-[300px] max-w-full" />
		<img src={img_fav5} alt="potery" class="md:max-h-[300px] max-w-full" />
		<img src={img_fav6} alt="potery" class="md:max-h-[300px] max-w-full" />
	</div>

	<div class="full-bleed min-h-48 bg-orange-50">

	</div>
	<div class="flex flex-wrap gap-9 justify-center">
		<img src={img_1} alt="potery" class="md:max-h-[300px] max-w-full" />
		<img src={img_2} alt="potery" class="md:max-h-[300px] max-w-full" />
		<img src={img_3} alt="potery" class="md:max-h-[300px] max-w-full" />
		<img src={img_4} alt="potery" class="md:max-h-[300px] max-w-full" />
		<img src={img_5} alt="potery" class="md:max-h-[300px] max-w-full" />
		<img src={img_6} alt="potery" class="md:max-h-[300px] max-w-full" />
		<img src={img_7} alt="potery" class="md:max-h-[300px] max-w-full" />
		<img src={img_8} alt="potery" class="md:max-h-[300px] max-w-full" />
		<img src={img_9} alt="potery" class="md:max-h-[300px] max-w-full" />
		<img src={img_10} alt="potery" class="md:max-h-[300px] max-w-full" />
		<img src={img_11} alt="potery" class="md:max-h-[300px] max-w-full" />

	</div>
</div>

<style lang="postcss">
    .wrapper {
        display: grid;
        grid-template-columns:
					1fr
					min(130ch, 100%)
					1fr;
    }

    .wrapper > * {
        grid-column: 2;
    }

    .full-bleed {
        width: 100%;
        grid-column: 1 / -1;
    }
</style>
