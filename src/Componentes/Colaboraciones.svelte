<script>
    export let productos = [
      { id: 1, imagen: "/Imagenes/Foto2.png", nombre: "Zapatilla 1" },
      { id: 2, imagen: "/Imagenes/Foto2.png", nombre: "Zapatilla 2" },
      { id: 3, imagen: "/Imagenes/Foto2.png", nombre: "Zapatilla 3" },
      { id: 4, imagen: "/Imagenes/Foto2.png", nombre: "Zapatilla 4" },
      { id: 5, imagen: "/Imagenes/Foto2.png", nombre: "Zapatilla 5" },
      { id: 6, imagen: "/Imagenes/Foto2.png", nombre: "Zapatilla 6" }
    ];
  </script>
  
  <section>
    <h2>Colaboraciones</h2>
    <div class="productos">
      {#each productos as producto, index}
        <div class="producto producto-{index + 1}">
          <img src={producto.imagen} alt={producto.nombre} />
          <p>{producto.nombre}</p>
        </div>
      {/each}
    </div>
  </section>
  
  <style>
    section {
      padding: 20px;
      text-align: center;
      font-family: Arial, sans-serif;
    }
  
    h2 {
      font-size: 28px;
      margin: 20px 0;
      font-weight: bold;
    }
  
    .productos {
      display: grid;
      grid-template-columns: repeat(3, 1fr);
      grid-template-rows: repeat(2, auto);
      gap: 5px;
      justify-items: center;
      align-items: center;
    }
  
    .producto {
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
    }
  
    .producto img {
      width: 230px;
      height: 230px;
      object-fit: cover;
      border-radius: 10px;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
      transition: transform 0.3s ease;
    }
  
    .producto img:hover {
      transform: scale(1.1);
    }
  
    .producto p {
      margin-top: 5px;
      font-size: 16px;
      color: black;
      font-weight: bold;
    }
  
    
    .producto-1 {
      justify-self: start;
      margin-left: 20px; 
    }
  
    .producto-2 {
      justify-self: center;
    }
  
    .producto-3 {
      justify-self: end;
      margin-right: 20px; 
    }
  
    .producto-4 {
      justify-self: start;
      margin-left: 20px; 
    }
  
    .producto-5 {
      justify-self: center;
    }
  
    .producto-6 {
      justify-self: end;
      margin-right: 20px; 
    }
  </style>
  