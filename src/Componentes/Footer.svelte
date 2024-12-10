<footer>
    <div class="footer-content">
      <div class="footer-imagen">
        <img src="/Imagenes/Foto3.png" alt="Footer Imagen" />
      </div>
      <div class="footer-texto">
        <p class="encuentranos">Encuéntranos en:</p>
        <div class="social-links">
          <a href="#">Instagram</a>
          <a href="#">Facebook</a>
        </div>
      </div>
      <div class="footer-ayuda">
        <p>Ayuda</p>
        <p>Sobre nosotros</p>
      </div>
    </div>
  </footer>
  
  <style>
    footer {
      background-color: #000000;
      color: #ffffff; 
      padding: 80px 20px; 
      display: flex;
      justify-content: space-between;
      align-items: center;
      font-size: 22px; 
    }
  
    .footer-content {
      display: flex;
      align-items: center;
      justify-content: space-between;
      width: 100%;
    }
  
    .footer-imagen img {
      width: 200px; 
      height: auto;
      border-radius: 10px;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
    }
  
    .footer-texto {
      text-align: center; 
      flex: 1; 
    }
  
    .footer-texto p {
      margin: 15px 0;
      font-size: 24px; 
      color: white; 
    }
  
    .encuentranos {
      font-weight: bold;
      font-size: 28px; 
      margin-bottom: 20px; 
    }
  
    .social-links a {
      display: inline-block;
      margin: 0 30px; 
      color: #ffffff; 
      text-decoration: none;
      font-weight: bold;
      font-size: 22px; 
    }
  
    .social-links a:hover {
      text-decoration: underline;
    }
  
    .footer-ayuda {
      text-align: right; 
    }
  
    .footer-ayuda p {
      margin: 15px 0;
      font-size: 24px; 
      color: white; 
    }
  </style>
  