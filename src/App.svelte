<script>
  import Header from "./lib/Header.svelte";
</script>

<main>
  <div class="app">
    <Header />
    <div class="buttons">
      <a href="#login" class="btn">Iniciar Sesión</a>
      <a href="#register" class="btn">Registrarse</a>
    </div>
  </div>
</main>

<style>
  .app {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    width: 375px;
    height: 667px;
    margin: auto;
    background: linear-gradient(to bottom, black, green);
    box-shadow: 0px, 0px, 15px rgba(0, 0, 0, 0.5);
  }
  .buttons {
    display: flex;
    flex-direction: column;
    gap: 20px;
    width: 80%;
  }
  .btn {
    text-decoration: none;
    background-color: black;
    color: white;
    border: 2px solid white;
    padding: 15px;
    font-size: 16px;
    text-align: center;
    border-radius: 25px;
    width: 100%;
    box-sizing: border-box;
  }
  .btn:hover {
    background-color: green;
    color: black;
  }
</style>
