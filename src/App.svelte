<script lang="ts">
  import SimpleExample from "./SimpleExample.svelte";
  import HowItWorks from "./HowItWorks.svelte";
  import AutoplayExample from "./AutoplayExample.svelte";
</script>

<main>
  <div class="description">
    <h1>
      trace-svelte
    </h1>
    <h2>A line by line highlighter for Svelte</h2>
    <p>
      <span style:font-weight="bold">GOAL</span>: 
      Create a code highlighter that has no dependencies and is fully extensible with great developer experience (DX)
    </p>
    <div class="links">
      <a href="https://github.com/zeucapua/trace-svelte">Github</a>
      <a href="https://npmjs.com/package/trace-svelte">npm</a>
      <a href="https://twitter.com/zeu_dev">Twitter</a>
      <a href="https://rabbitstars.vercel.app/editor">
        <button>Try out the Live Editor</button>
      </a>
    </div>
  </div>
  <SimpleExample />
  <HowItWorks />
  <AutoplayExample />
</main>

<style>
  main {
    display: flex;
    gap: 0.5rem;
    flex-direction: column;
    justify-content: center;
    align-content: center;
    font-family: sans-serif;
  }

  .description {
    margin: 0 auto;
  }

  .links {
    display: inline-flex;
    gap: 16px;
    justify-content: center;
    align-items: center;
  }
</style>
