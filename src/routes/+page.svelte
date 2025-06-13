<script>
	// import Box1 from '$lib/components/Box1.svelte';
	import GridBox from '$lib/components/GridBox.svelte';
	import GridBoxNoImg from '$lib/components/GridBoxNoImg.svelte';
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
		<GridBoxNoImg
			title="Technology"
			subtitle="What I use"
			text="<b>== Hardware ==</b>
			<dl>
				<dt>- Lenovo IdeaPad C340-15IWL</dt>
				<dd>- Upgraded to 12GB RAM, Intel i5-8265U (8) @ 3.9GHz, NVIDIA GeForce MX230</dd>
				<dt>- LG ULTRAGEAR</dt>
				<dd>- HD Resolution</dd>
				<dt>- Samsung Galaxy A14 5G</dt>
				<dd>- Certified Android enjoyer</dd>
			</dl>
			<b>== Software ==</b>
			<dl>
				<dt>- Linux Mint 22.1</dt>
				<dd>- Cinnamon</dd>
				<dt>- Visual Studio Code</dt>
				<dt>- IntelliJ IDEA</dt>
			</dl>"
		/>
</div>