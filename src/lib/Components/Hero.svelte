<script>
	import { onMount } from 'svelte';
	import { fly } from 'svelte/transition';
	let ready = false;
	onMount(() => (ready = true));
</script>

<div class="">
	<div class="">
		{#if ready}
			<div in:fly={{ delay: 250, x: -200, duration: 4000 }}>
				<p class="pt-16 text-center text-4xl font-extrabold text-my-nvy1 md:text-6xl">
					Grow your business,<br />Succeed with Us.
				</p>
				<div class="mt-2 flex justify-center gap-4">
					<p class="text-center text-2xl font-thin text-my-nvy1">Product Design</p>
					<p class="text-center text-2xl font-thin text-my-nvy1">Machine Design</p>
				</div>
				<p class="text-center text-2xl font-thin text-my-nvy1 pb-16">And much more.</p>
			</div>
		{/if}
	</div>
</div>
