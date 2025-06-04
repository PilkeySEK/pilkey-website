<script>
	let { src, alt, text } = $props();
</script>

<button class="img-button-1 img-button-orange">
	<img {src} {alt} class="h-5 w-5" />
	<p>{text}</p>
</button>

<!-- svelte-ignore css_unused_selector (https://github.com/sveltejs/svelte/issues/14847) -->
<style>
	@import 'tailwindcss';
	.img-button-1.img-button-orange {
		@apply flex items-center gap-1 rounded-sm border-1 border-solid border-orange-500/25 bg-orange-500/10 pt-0.5 pr-1 pb-0.5 pl-1;
		@apply hover:bg-orange-500/20;
		@apply active:bg-orange-500/30;
	}
	.img-button-1.img-button-blue {
		@apply flex items-center gap-1 rounded-sm border-1 border-solid border-blue-500/25 bg-blue-500/10 pt-0.5 pr-1 pb-0.5 pl-1;
		@apply hover:bg-blue-500/20;
		@apply active:bg-blue-500/30;
	}
</style>
