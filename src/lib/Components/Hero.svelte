<div class="h-screen">
  
  <div class="h-1/2 bg-my-nvy1">
    {#if ready}
    <div transition:fly="{{delay: 250, x:-200, duration: 4000 }}">
      <p class="pt-16 text-center text-4xl font-extrabold text-white md:text-6xl">Grow your business,<br />Succeed with Us.</p>
    <div class="mt-2 flex justify-center gap-4">
      <p class="text-center text-2xl font-thin text-white">Product Design</p>
      <p class="text-center text-2xl font-thin text-white">Machine Design</p>
    </div>
    <p class="text-center text-2xl font-thin text-white">And much more.</p>
    </div>
    {/if}
  </div>
  
</div>
<script>
  import { onMount } from 'svelte';
	import { fly } from 'svelte/transition';
  let ready = false;
  onMount(() => ready = true);
</script>