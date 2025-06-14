<script>
	let { children, image = undefined, image_alt = undefined, image_width = "100", image_height = "100" } = $props();
</script>

{#if image}
<div class="rounded-xl border-2 border-solid border-blue-900/50 bg-blue-900/20">
	<div class="flex flex-row gap-5 p-3 text-wrap">
		<img
			src={image}
			alt={image_alt}
			class="h-1/1 rounded-xl"
			width={image_width}
			height={image_height}
		/>
		<div>
			{@render children()}
		</div>
	</div>
</div>
{:else}
<div class="rounded-xl border-2 border-solid border-blue-900/50 bg-blue-900/20">
	<div class="p-3 text-wrap">
		<div>
			{@render children()}
		</div>
	</div>
</div>
{/if}