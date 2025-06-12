<script>
	// import Box1 from '$lib/components/Box1.svelte';
	import Box2 from '$lib/components/Box2.svelte';
</script>

<h1 style="text-align: center">h</h1>
<!--
<Box1 text="Hello aaahaaa" title="a" subtitle="abcdefg" footer="mmm" image="/assets/GitHub_logo_white_normalized.png" image_alt="h" />
<Box1 text="Hello aaahaaa" title="a" subtitle="abcdefg" footer="mmm" image="/assets/GitHub_logo_white_normalized.png" image_alt="h" />
-->
<div class="grid grid-cols-1 gap-10 p-10 md:grid-cols-1 lg:grid-cols-2">
	<Box2
		title="hi"
		subtitle="asdf"
		text="Lorem ipsum dolor sit amet, consectetur adipiscing elit. Maecenas placerat lacinia nibh, nec molestie quam."
		image="/assets/GitHub_logo_white_normalized.png"
		image_alt="abc"
	/>
	<Box2
		title="hi"
		text="normal text"
		image="/assets/GitHub_logo_white_normalized.png"
		image_alt="abc"
	/>
</div>
