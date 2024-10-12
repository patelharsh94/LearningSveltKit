<script>
    import Hero from "../component/Hero.svelte";

</script>
<h1 class="text-3xl font-bold underline">
    <Hero />
</h1>
  
  <style lang="postcss">
    :global(html) {
      background-color: theme(colors.gray.100);
    }
  </style>