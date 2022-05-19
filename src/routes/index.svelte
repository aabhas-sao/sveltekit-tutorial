<script>
  let title = "Ninja Gaming Guides";

  const updateTitle = () => {
    title = "Demon Slayer Guides";
  };
</script>

<h1>{title}</h1>
<p>
  Visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to read the documentation
</p>
<button on:click={updateTitle}>change title</button>
<input type="text" name="title" bind:value={title} />
