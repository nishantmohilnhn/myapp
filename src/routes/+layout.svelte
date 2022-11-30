<script>
	import Nevbar from "$lib/Components/Nevbar.svelte";
  import Fotter from "$lib/Components/Fotter.svelte";
 
  import "../app.css";
	import Whatapp from "$lib/Components/Whatapp.svelte";
  </script>
  <Nevbar/>
  <slot />
  <Fotter/>
  <Whatapp/>