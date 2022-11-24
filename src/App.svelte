<script lang="ts">
  import Counter from './lib/Counter.svelte'
</script>

<main>
  <div>
    <img src="https://simpleicons.org/icons/vercel.svg" class="logo" alt="Vercel Logo" />
  </div>
  <h1>The Coalition Journal</h1>
  <p>
	Under Construction
  </p>

  <div class="card">
    <Counter />
  </div>
</main>

<style>
  .logo {
    height: 6em;
    padding: 1.5em;
    will-change: filter;
  }
  .logo {
    filter: drop-shadow(0 0 2em #b4b4b4d9);
  }

  .logo:hover {
    filter: drop-shadow(0 0 2em #ffffffff);
  }
</style>
