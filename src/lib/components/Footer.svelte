<script>
	import ImgButton from "./ImgButton.svelte";

</script>

<div class="border-t-2 border-solid border-blue-900/50 bg-black">
	<div class="flex items-center gap-2 p-3">
		<!--<button class="img-button-1 img-button-orange">
			<img
				src="/assets/GitHub_logo_white_normalized.png"
				alt="GitHub logo"
				class="footer-button-img"
			/>
			<p>GitHub</p>
		</button>
		<button class="img-button-1 img-button-orange">
			<img
				src="/assets/Discord_logo_colored_normalized.png"
				alt="Discord logo"
				class="footer-button-img"
			/>
			<p>Discord</p>
		</button>
		<button class="img-button-1 img-button-orange">
			<img src="/assets/Mastodon_logo_colored.png" alt="Mastodon logo" class="footer-button-img" />
			<p>Mastodon</p>
		</button>-->
        <ImgButton src="/assets/GitHub_logo_white_normalized.png" alt="Github logo" text="GitHub"/>
        <ImgButton src="/assets/Discord_logo_colored_normalized.png" alt="Discord logo" text="Discord"/>
        <ImgButton src="/assets/Mastodon_logo_colored.png" alt="Mastodon logo" text="Mastodon"/>
	</div>
</div>
