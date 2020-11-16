<script>
  import Navbar from "./Navbar.svelte";
  import Title from "./Title.svelte";
  let fruits = ["apple", "orange", "lemon"];
</script>

<Navbar />

{#each fruits as fruit}
  <Title title={fruit} />
{/each}
