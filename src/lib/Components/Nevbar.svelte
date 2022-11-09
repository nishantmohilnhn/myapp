<header>
    <nav class=" flex justify-center py-2 px-4 border-b-2 border-purple-300 font-mono font-semibold text-neutral-600 flex-wrap">
        <div class="w-1/2  justify-center items-center ">
            <h1 class=" inline-block tracking-tight ">
               <span class=" text-purple-500  font-extrabold inline-block mr-0.5 text-xl"> MS </span>Hygiene Solution
            </h1>
            
        </div>

        <div class="w-1/2 flex justify-end  font-extrabold">
            <button class=" py-1 px-2 hover:bg-purple-500 hover:text-white tracking-tight">Contact</button>
            <button class=" py-1 px-2 hover:bg-purple-500 hover:text-white md:hidden " on:click="{()=>btncic=!btncic}">Menu</button>
            
        </div>
        {#if btncic}
        <div transition:fade class="flex border-t-2 border-purple-300 w-full justify-center">
            <a href="/" class="inline-block mx-2">Home</a>
            <a href="/" class="inline-block mx-2">Home</a>
            <a href="/" class="inline-block mx-2">Home</a>
            <a href="/" class="inline-block mx-2">Home</a>
        </div>
        {/if}

        
    </nav>
    

</header>

<script>
	import { fade } from "svelte/transition";


    let btncic = false;
</script>