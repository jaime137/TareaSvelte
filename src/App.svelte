<script>
  import Header from "./Componentes/Header.svelte";
  import Colaboraciones from "./Componentes/Colaboraciones.svelte";
  import Footer from "./Componentes/Footer.svelte";
</script>

<Header />

<!-- Imagen Principal -->
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
    width: 100%; /* Hace que la imagen ocupe el 100% del ancho disponible */
    max-width: 100vw; /* Asegura que la imagen ocupe el 100% del ancho de la pantalla */
    height: auto;
    border-radius: 15px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
  }
</style>
