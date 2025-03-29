<script lang="ts">
import RealEstateProduct from './lib/RealEstateProduct.svelte';
</script>

<main>
  <RealEstateProduct />
</main>

<style>
:global(body) {
  margin: 0;
  font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen-Sans, Ubuntu, Cantarell, 'Helvetica Neue', sans-serif;
  background-color: #f8fafc;
}

main {
  min-height: 100vh;
  padding: 2rem 0;
}
</style>