<script lang="ts">
  import svelteLogo from "../assets/svelte.svg";
  import Counter from "../lib/Counter.svelte";
</script>

<main>
  <div class="flex justify-center my-10">
    <a href="https://vitejs.dev" target="_blank">
      <img src="/vite.svg" class="mx-5" alt="Vite Logo" />
    </a>
    <a href="https://svelte.dev" target="_blank">
      <img src={svelteLogo} class="mx-5" alt="Svelte Logo" />
    </a>
  </div>
  <h1>Vite + Svelte</h1>

  <div class="card">
    <Counter />
  </div>

  <p>
    Check out
    <a href="https://github.com/sveltejs/kit#readme" target="_blank">
      SvelteKit
    </a>
    , the official Svelte app framework powered by Vite!
  </p>

  <p class="my-10">Click on the Vite and Svelte logos to learn more</p>
</main>
