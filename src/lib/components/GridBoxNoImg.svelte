<script>
	let {
		title = undefined,
		subtitle = undefined,
		text = undefined,
		col_span = ''
	} = $props();
</script>

<div class="rounded-xl border-2 border-solid border-blue-900/50 bg-blue-900/20 {col_span}">
	<div class="p-3">
		<p class="text-2xl"><b>{@html title}</b></p>
		{#if subtitle}
			<p class="text-gray-500">{@html subtitle}</p>
		{/if}
		<p>{@html text}</p>
	</div>
</div>
