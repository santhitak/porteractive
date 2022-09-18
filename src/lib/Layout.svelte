<script lang="ts">
  import { Link } from "svelte-routing";
</script>

<div>
  <div style="position: fixed; width: 100vw;">
    <nav class="p-3 flex justify-between">
      <Link to="/" class="mx-5 text-lg">INDEX</Link>
      <Link to="project" class="mx-5 text-lg">PROJECTS</Link>
    </nav>
  </div>
  <hr />
  <slot />
</div>
