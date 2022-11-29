<header class=" sticky top-0 bg-neutral-50 sm:flex sm:justify-between md:justify-around items-center ">


  <div class="flex items-center justify-between px-2 py-1">
    <div class="flex items-center gap-1">
      <svg xmlns="http://www.w3.org/2000/svg" fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" class="w-8 h-8 text-white p-2 bg-purple-500 rounded-full" viewBox="0 0 24 24">
        <path d="M12 2L2 7l10 5 10-5-10-5zM2 17l10 5 10-5M2 12l10 5 10-5"></path>
      </svg>
      <h1 class=" font-semibold">DiaperExperts</h1>
    </div>
    <!--logo and name-->
   <div class="sm:hidden">
    <button 
   on:click={() => (hidden = !hidden)}
   class=" block text-gray-50">
    <svg class="" height="17" width="17" fill="none" xmlns="http://www.w3.org/2000/svg"><path d="M17 13H1M17 9H1M17 5H1M17 1H1" stroke="#14181F" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/></svg>
   </button>
  </div>
    <!--buttom-->
  </div>

<!---menu-->
<div class:hidden class="sm:flex sm:gap-1">
  <a on:click={() => (hidden = !hidden)} class="block ml-2 mt-1 px-1 hover:bg-purple-100 rounded-md font-normal border-b-2 border-purple-100   " href="/">Home</a>
  <a on:click={() => (hidden = !hidden)} class="block ml-2 mt-1 px-1 hover:bg-purple-100 rounded-md font-normal border-b-2 border-purple-100   " href="/about">Services</a>
  <a on:click={() => (hidden = !hidden)} class="block ml-2 mt-1 px-1 hover:bg-purple-100 rounded-md font-normal border-b-2 border-purple-100   " href="/">Work With Us</a>
  <a on:click={() => (hidden = !hidden)} class="block ml-2 mt-1 px-1 hover:bg-purple-100 rounded-md font-normal border-b-2 border-purple-100   " href="/">About Us</a>
  <a on:click={() => (hidden = !hidden)} class="block ml-2 mt-1 px-1 mb-1 hover:bg-purple-800 rounded-md font-semibold border-b-2 border-purple-100 bg-purple-400 text-neutral-50 text-center" href="/">Get in Touch</a>

</div>


</header>


<script>
  let hidden = true;
</script>