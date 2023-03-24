<script lang="ts">
  import "@picocss/pico/css/pico.classless.min.css";
  let message = "Hello, 世界!";
</script>

<main class="container">
  <p>{message}</p>
  <input bind:value={message} />
</main>

<style global lang="scss">
</style>
