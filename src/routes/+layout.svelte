<script lang="ts">
  import "../app.css";
  import Navbar from "$lib/components/Navbar.svelte";
</script>

<div class="w-full h-full flex flex-col mt-11 overflow-hidden">
  <Navbar />

  <slot />
</div>
