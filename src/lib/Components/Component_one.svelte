<main class="mt-1 ml-0">
   {#each chart as item}
    
    <div class="flex  overflow-hidden pb-1">
        <dir class="">
            <p class=" text-5xl font-bold text-gray-700 inline-block"> <samp class=" text-purple-600">{item.head}</samp> <br> {item.head2}</p>
               <p> {item.dis} <br> {item.dis2}</p>
        </dir>
        <div class="flex  w-full justify-end items-end ml-1">
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
        dis:'Product Development Support',
        dis2:'tProduct Developmen',
    },
    {
        head:'marketing',
        head2: 'Consultant',
        dis:'Product Development Support',
        dis2:'tProduct Developmen',
    },
    {
        head:'Product',
        head2: ' development',
        dis:'Product Development Support',
        dis2:'Product Development',
    },
    ];

</script>