<script>
  import Title from "../lib/title.svelte";
  import "../styles/global.css";
</script>

<header>
  <Title title="Anime Reviews" />
</header>

<main>
  <slot />
</main>
<footer>
  <p>&copy; footer stuff</p>
</footer>
