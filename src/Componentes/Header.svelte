<script>
    export let menuItems = ["Marcas", "Hombre", "Mujer"];
  </script>
  
  <header>
    <h1>Foot Zapas</h1>
    <div class="search-container">
      <input type="text" placeholder="Buscar..." />
    </div>
    <nav>
      <ul>
        {#each menuItems as item}
          <li><a href="#">{item}</a></li>
        {/each}
      </ul>
    </nav>
  </header>
  
  <style>
    header {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 20px 40px; 
      background-color: black;
      color: white;
      font-family: Arial, sans-serif;
    }
  
    h1 {
      font-size: 28px;
      margin: 0;
      font-weight: bold;
      letter-spacing: 2px;
      flex: 1; 
    }
  
    .search-container {
      margin-left: auto; 
    }
  
    .search-container input {
      padding: 8px;
      font-size: 16px;
      width: 180px; 
      border: 2px solid #ddd;
      border-radius: 4px;
    }
  
    nav ul {
      display: flex;
      list-style-type: none;
      margin: 0;
      padding: 0;
    }
  
    nav ul li {
      margin: 0 15px;
    }
  
    nav ul li a {
      text-decoration: none;
      color: white;
      font-size: 16px;
      font-weight: bold;
      text-transform: uppercase;
      transition: color 0.3s ease;
    }
  
    nav ul li a:hover {
      color: #FFD700;
    }
  </style>
  