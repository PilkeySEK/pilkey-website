<script>
	let {
		title,
		subtitle = undefined,
		text,
		footer = undefined,
		image = undefined,
		image_alt = undefined,
		width = 0,
		height = 0
	} = $props();
</script>

<div
	class="{width === 0 ? '' : `w-${width}`} {height === 0
		? ''
		: `w-${height}`} border-2 border-solid border-blue-500/20"
>
	<div class="flex">
		{#if image}
			<img src={image} alt={image_alt} />
		{/if}
		<div>
			<b><p class="text-2xl">{title}</p></b>
			{#if subtitle}
				<b><p class="text-sm">{subtitle}</p></b>
			{/if}
			<p class="text-justify hyphens-auto">{text}</p>
			{#if footer}
				<p class="text-sm text-gray-500">{footer}</p>
			{/if}
		</div>
	</div>
</div>
