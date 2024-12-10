<script>
  import Header from "./Componentes/Header.svelte";
  import Colaboraciones from "./Componentes/Colaboraciones.svelte";
  import Footer from "./Componentes/Footer.svelte";
</script>

<Header />


<div class="main-image">
  <img src="/Imagenes/Foto1.png" alt="Imagen principal" />
</div>

<Colaboraciones />
<Footer />

<style>
  .main-image {
    text-align: center;
    margin: 20px 0;
  }

  .main-image img {
    width: 100%; 
    max-width: 100vw; 
    height: auto;
    border-radius: 15px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
  }
</style>
