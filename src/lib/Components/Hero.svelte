<script>
let imghero="https://images.unsplash.com/photo-1573662012516-5cb4399006e7?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1548&q=80"
import viewport from './useViewportAction';
import {fly} from 'svelte/transition'

let vise=false;


</script>




<section  
    use:viewport
    on:enterViewport={()=> vise = true}
class="text-gray-600 body-font bg-purple-100">

{#if vise}
  <div 
  in:fly="{{ x: -200, duration: 3000 }}"
  class="container mx-auto flex px-1 py-10 md:px-5 md:py-24 md:flex-row flex-col items-center">
  <div class="lg:max-w-lg lg:w-full md:w-1/2 w-5/6 mb-10 md:mb-0">
    <img class="object-cover object-center rounded" alt="hero" src="https://picsum.photos/id/950/945">
  </div>
    <div class="flex justify-center">
      <button class="inline-flex text-white bg-purple-500 border-0 py-2 px-6 focus:outline-none hover:bg-purple-600 rounded text-lg">Get in touch</button>
      <button class="ml-4 inline-flex text-gray-700 bg-gray-100 border-0 py-2 px-6 focus:outline-none hover:bg-gray-200 rounded text-lg">Learn more</button>
    </div>
  </div>
</div>
    {/if}
</section>

