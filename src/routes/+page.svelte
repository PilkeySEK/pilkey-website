<script>
	// import Box1 from '$lib/components/Box1.svelte';
	import GridBox from '$lib/components/GridBox.svelte';
</script>

<div class="grid grid-cols-1 gap-10 p-10 md:grid-cols-1 lg:grid-cols-2">
		<GridBox
			title="Hello!"
			subtitle="Click to insert subtitle"
			text="I'm Pilkey :)
			<br>Also known as <profile-colored-text>@PilkeySEK</profile-colored-text> on many platforms.
			<br>I like to code things, but rarely release them 😭
			<br>You should really check out my <a href='https://github.com/PilkeySEK'>GitHub</a> :3"
			image="/assets/pilkey_pfp.png"
			image_alt="Pilkey's picture"
		/>
</div>