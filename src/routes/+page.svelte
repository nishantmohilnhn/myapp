<script>
	import ComponentOne from "$lib/Components/Component_one.svelte";
	import Nevbar from "$lib/Components/Nevbar.svelte";

</script>

<div class="min-h-screen flex flex-col">
  <header class="bg-red-50"> <Nevbar/> </header> 

  <div class="flex-1 flex flex-col sm:flex-row">
    <main class="flex-1 bg-red-200 "><ComponentOne/> </main>

    <div class="order-first sm:w-32  bg-pink-200"></div>

    <div class="sm:w-32 bg-yellow-100">Right Sidebar</div>
  </div>

  <footer class="bg-gray-100">Footer</footer>
</div>

