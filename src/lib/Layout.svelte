<script lang="ts">
  import { Link } from "svelte-routing";
</script>

<div style="position: fixed; width: 100vw;">
  <nav
    class="p-3 flex justify-between backdrop-blur-sm"
    style="background-color: rgba(255, 255, 255, 0.6)"
  >
    <Link to="/" class="mx-5 lg:text-lg">INDEX</Link>
    <Link to="project" class="mx-5 lg:text-lg">PROJECTS</Link>
    <Link to="about" class="mx-5 lg:text-lg">ABOUT</Link>
  </nav>
  <hr class="bg-current" />
</div>
<slot />
