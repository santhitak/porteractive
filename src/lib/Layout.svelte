<script lang="ts">
  import { Link } from "svelte-routing";
</script>

<div style="position: fixed; width: 100vw;">
  <nav class="p-3 flex justify-between bg-white">
    <Link to="/" class="mx-5 lg:text-lg">INDEX</Link>
    <Link to="project" class="mx-5 lg:text-lg">PROJECTS</Link>
    <Link to="about" class="mx-5 lg:text-lg">ABOUT</Link>
  </nav>
  <hr />
</div>
<slot />
