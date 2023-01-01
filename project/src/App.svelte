<script>
  import svelteLogo from "./assets/svelte.svg";
  import Counter from "./lib/Counter.svelte";
</script>

<main>
  <h1>Vite + Svelte</h1>
  <div class="container">
    <h1>Hello Scss is working</h1>
    <p>Successfully</p>
  </div>
</main>

<style lang="scss">
  .container {
    color: #30c2f3;
    display: flex;
    justify-content: center;
    flex-direction: column;
    align-items: center;
    padding: 0;
    p {
      font-size: 2rem;
      font-weight: bold;
      color: rgb(79, 254, 63);
      border: 1px solid rgb(35, 246, 35);
      padding: 20px 15px;
      border-radius: 4px;
      margin: 10px;
      width: fit-content;
      &:hover {
        background-color: #7c7c7c49;
      }
    }
  }
</style>
