<!-- YOU CAN DELETE EVERYTHING IN THIS PAGE -->
<script lang="ts">
	import 'vidstack/player';
	import 'vidstack/player/ui';
	import 'vidstack/icons';
</script>

<div class="container h-full mx-auto flex justify-center items-center">
	<div class="space-y-10 text-center flex flex-col items-center">
		<h2 class="h2">Welcome to the Garden</h2>
		<media-player
			class="w-full h-full"
			title="Sprite Fight"
			autoplay
			src="https://stream.mux.com/VZtzUzGRv02OhRnZCxcNg49OilvolTqdnFLEqBsTwaxU/low.mp4"
		>
			<media-provider />
		</media-player>
	</div>
</div>
