<main class="mt-1">
   {#each chart as item}
    
    <div class="flex  justify-between overflow-hidden pb-1 mt-1 max-w-lg md:mx-auto mr-4">
       
       
        <dir>
            <p class=" md:text-5xl text-2xl font-bold text-gray-700 inline-block"> <samp class=" text-purple-600">{item.head}</samp> <br> {item.head2}</p>
            <p> {item.dis} <br> {item.dis2}</p>
        </dir>
       
       
       
        <div class="flex justify-end items-end">
           
           
            <div class="relative w-36 h-36 rounded-full flex justify-center items-center text-center p-5 shadow-md bg-purple-200">
                <span class="absolute text-8xl left-0 top-0 text-purple-800">"
                </span>
                Make it simple, but significant.
             </div>
        
        </div>

    </div>
    {/each}

</main>

<script>
    const chart = [{
        head:'Project',
        head2: 'Consultant',
        dis:'Development Support',
        dis2:'Product Developmen',
    },
    {
        head:'Marketing',
        head2: 'Consultant',
        dis:'Product Support',
        dis2:'Product Developmen',
    },
    {
        head:'Product',
        head2: 'Deve',
        dis:'Product Development Support',
        dis2:'Product Development',
    },
    ];

</script>