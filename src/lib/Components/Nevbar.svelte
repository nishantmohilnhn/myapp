<header class=" sticky top-0 bg-neutral-50 sm:flex sm:justify-between md:justify-around items-center">


  <div class="flex items-center justify-between px-2 py-2">
    <div class="flex items-center gap-1">
      <svg xmlns="http://www.w3.org/2000/svg" fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" class="w-10 h-10 text-white p-2 bg-my-nvy1 rounded-full" viewBox="0 0 24 24">
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
<div class:hidden class="sm:flex sm:gap-1 items-center">
  <a on:click={bawa} class="ml-2 mt-1 block rounded-md border-b-2 border-purple-100 px-1 hover:text-my-blue sm:border-b-0" href="/">Home</a>
  <a on:click={() => (hidden = !hidden)} class="ml-2 mt-1 block rounded-md border-b-2 border-purple-100 px-1 hover:text-purple-500 sm:border-b-0" href="/services">Services</a>
  <a on:click={() => (hidden = !hidden)} class="ml-2 mt-1 block rounded-md border-b-2 border-purple-100 px-1 hover:text-purple-500 sm:border-b-0" href="/">Work With Us</a>
  <a on:click={() => (hidden = !hidden)} class="ml-2 mt-1 block rounded-md border-b-2 border-purple-100 px-1 hover:text-purple-500 sm:border-b-0" href="/about">About Us</a>
  <a on:click={() => (hidden = !hidden)} class="mr-1 ml-2 mt-1 block rounded-full border-b-2 border-purple-100 bg-my-nvy1 px-1 py-1 text-center font-semibold text-neutral-50 hover:bg-purple-800 md:px-2" href="/contact">Get in Touch</a>
</div>



</header>


<script>
  let hidden = true;
  function bawa(){
    hidden = !hidden
  }
</script>