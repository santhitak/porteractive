<script lang="ts">
  import { Link } from "svelte-routing";
</script>

<div>
  <nav class="p-5 flex justify-center">
    <Link to="/" class="mx-10">Home</Link>
    <Link to="about" class="mx-10">About</Link>
    <Link to="blog" class="mx-10">Blog</Link>
  </nav>
  <slot />
</div>
