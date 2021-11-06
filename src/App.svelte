<script>
  import Pikachu from "./Pikachu.svelte";
</script>

<svelte:head>
  <link
    href="https://fonts.googleapis.com/css2?family=Fira+Code:wght@400;700&display=swap"
    rel="stylesheet"
  />
</svelte:head>

<body>
  <div class="pikachu-wrapper">
    <div class="text">
      <h2>Send me your Crazy Ideas for this Domain on Discord:</h2>
      <h1>$ su Amresh#6575</h1>
    </div>
    <div class="pikachu">
      <Pikachu />
    </div>
  </div>
</body>

<style>
  * {
    margin: 0;
    padding: 0;
  }
  body {
    background: #fffce0;
  }
  .pikachu-wrapper {
    position: absolute;
    margin: auto;
    top: 40%;
    left: 50%;
    transform: translate(-50%, -50%);
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
  }
  .text {
    text-align: center;
  }
  h1 {
    font-family: "Fira Code", monospace;
  }
  h2 {
    font-family: "Fira Code", monospace;
  }
</style>
