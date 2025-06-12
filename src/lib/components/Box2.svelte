<script>
	let {
		title = undefined,
		subtitle = undefined,
		text = undefined,
		image = undefined,
		image_alt = 'No alt provided.',
		image_height = '100',
		image_width = '100'
	} = $props();
</script>

<div class="border-2 border-solid border-blue-900/50 rounded-xl bg-blue-900/20">
	<div class="flex flex-row flex-wrap md:flex-wrap lg:flex-nowrap text-wrap gap-5 p-1">
			<img src={image} alt={image_alt} width={image_width} height={image_height} class="" />
		<div>
			<p class="text-2xl"><b>{@html title}</b></p>
			{#if subtitle}
			<p class="text-gray-500">{@html subtitle}</p>
			{/if}
			<p>{@html text}</p>
		</div>
	</div>
</div>
