<script>
	let {
		title = undefined,
		subtitle = undefined,
		text = undefined,
		image = undefined,
		image_alt = 'No alt provided.',
		image_height = '100',
		image_width = '100',
		img_container_classes = ''
	} = $props();
</script>

<div class="border-1 border-solid border-yellow-50">
	<div class="flex flex-row flex-wrap md:flex-wrap lg:flex-nowrap text-wrap gap-5">
		<div class={img_container_classes}>
			<img src={image} alt={image_alt} width={image_width} height={image_height} class="" />
		</div>
		<div>
			<p class="text-2xl"><b>{@html title}</b></p>
			{#if subtitle}
			<p class="text-gray-500">{@html subtitle}</p>
			{/if}
			<p>{@html text}</p>
		</div>
	</div>
</div>
