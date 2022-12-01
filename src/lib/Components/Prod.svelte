<section class="mt-4">
    <h1 class="text-center text-2xl font-extrabold text-my-nvy1">Product Design</h1>
    <p class="mt-2 font-Roboto p-2 text-center font-semibold text-gray-700">We Have Provided the Design of the Quality Product List are According to below.</p>
  
    <div class="bg-white">
      <div class="mx-auto max-w-2xl py-16 px-4 sm:py-16 sm:px-6 lg:max-w-7xl lg:px-8">
        <h2 class="sr-only">Products</h2>
        <div class="grid grid-cols-1 gap-y-10 gap-x-6 sm:grid-cols-2 lg:grid-cols-3 xl:grid-cols-4 xl:gap-x-8">
          <!-- product --->
          {#each productsTypes as p}
            
          <a href="/" class="group">
            <div class="aspect-w-1 aspect-h-1 xl:aspect-w-7 xl:aspect-h-8 w-full overflow-hidden rounded-lg bg-gray-200">
              <img src="{p.imgsrc}" alt="Tall slender porcelain bottle with natural clay textured body and cork stopper." class=" h-72 w-full object-cover object-center group-hover:opacity-75" />
            </div>
            <h3 class="mt-4 text-sm text-gray-700">{p.subtitel}</h3>
            <p class="mt-1 text-lg font-medium text-gray-900">{p.title}</p>
          </a>
          {/each}
          <!-- More products... -->
        </div>
      </div>
    </div>
    <p class="font-Roboto p-2 text-center text-base font-thin text-my-nvy1 md:px-32">Our Product Design are enjoyable(Appropriate),worthy to skin and feel like Free. Before you choose a good Product Design , seek Experts Help . <span class="hidden md:block"> (we are here to help you, but other consultants can also do it for you). Our design base on your budget, your market area , your competitor's product design and Quality. We are analyse your market and set your product fectures .Then we are create the good Profitable Product Design .</span> Set all parameter According your Market and Current situation and as well as future trends. Best Performance Product Design We give You.</p>
    <!-- product segment--->
  </section>

  <script>
    let productsTypes =[
        {"title":"Baby Diaper","subtitel":"Open and Pull-Up","imgsrc":"https://images.unsplash.com/photo-1613465457505-42eaac07c3e3?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=774&q=80"},
        {"title":"Adult Diaper ","subtitel":"Open and Pull-Up","imgsrc":"https://images.unsplash.com/photo-1613732437147-f5878329f6b3?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=2071&q=80"},
        {"title":"Sanitary Napkin","subtitel":"Single and Double Wings","imgsrc":"https://images.unsplash.com/photo-1613733451221-c3e5e37e4b36?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=2070&q=80"},
        {"title":"Panty Liner","subtitel":" ","imgsrc":"https://images.unsplash.com/photo-1534639077088-d702bcf685e7?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1065&q=80"},
        {"title":"Under Pad","subtitel":" ","imgsrc":"https://images.unsplash.com/photo-1612882514773-2bf558552e1c?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=2070&q=80"},
        {"title":"Wet - Wipes","subtitel":" ","imgsrc":"https://images.unsplash.com/photo-1633265484557-e298493cb162?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=2070&q=80"},
        {"title":"Toilet Paper","subtitel":" ","imgsrc":"https://images.unsplash.com/photo-1584374829107-d5edbfe98d66?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=774&q=80"},
        {"title":"Pocket Tissue","subtitel":" ","imgsrc":"https://images.unsplash.com/photo-1502148589715-3f209594d750?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1625&q=80"},
    ];
  </script>