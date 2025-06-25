<script>
	let { children } = $props();
</script>

<p class="big-title">
	<b>
		{@render children()}
	</b>
</p>

<style>
    .big-title {
        font-size: 50px;
        font-weight: bold;
    }
</style>