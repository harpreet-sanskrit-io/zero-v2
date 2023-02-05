<script lang="ts">
import TopNav from "$lib/common/TopNav.svelte"
  import "../app.css"
</script>

<div class="isolate bg-gray-100 max-h-screen">
  <TopNav/>
  <main>
    <slot />
  </main>

</div>