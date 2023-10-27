<!-- YOU CAN DELETE EVERYTHING IN THIS PAGE -->
<script lang="ts">
	import 'vidstack/player';
	import 'vidstack/player/ui';
	import 'vidstack/icons';
	import { onMount } from 'svelte';
	import type { MediaPlayer } from 'vidstack';
</script>

<div class="container h-full mx-auto flex justify-center items-center">
	<div class="space-y-10 text-center flex flex-col items-center">
		<h2 class="h2">Welcome to the Garden</h2>
		<!-- <media-player
			class="w-full h-full"
			title="Sprite Fight"
			src="https://stream.mux.com/VZtzUzGRv02OhRnZCxcNg49OilvolTqdnFLEqBsTwaxU/low.mp4"
		>
			<media-provider />
		</media-player> -->
		<div class="logo-cloud grid-cols-1 lg:!grid-cols-3 gap-1">
			<a class="logo-item p-5" href="/">
				<span>Discord</span>
			</a>
			<a class="logo-item p-5" href="/">
				<span>RCCF.club</span>
			</a>
			<a class="logo-item p-5" href="/">
				<span>Instagram</span>
			</a>
		</div>
	</div>
</div>
