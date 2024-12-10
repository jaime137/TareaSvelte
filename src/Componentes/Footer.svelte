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
      background-color: #000000; /* Fondo negro */
      color: #ffffff; /* Letras blancas */
      padding: 80px 20px; /* Aumentar más el padding para hacer el footer más grande */
      display: flex;
      justify-content: space-between;
      align-items: center;
      font-size: 22px; /* Aumentar el tamaño del texto */
    }
  
    .footer-content {
      display: flex;
      align-items: center;
      justify-content: space-between;
      width: 100%;
    }
  
    .footer-imagen img {
      width: 200px; /* Hacer la imagen mucho más grande */
      height: auto;
      border-radius: 10px;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
    }
  
    .footer-texto {
      text-align: center; /* Centrar el texto de los enlaces */
      flex: 1; /* Tomar todo el espacio disponible */
    }
  
    .footer-texto p {
      margin: 15px 0;
      font-size: 24px; /* Aumentar el tamaño de la fuente */
      color: white; /* Letras blancas */
    }
  
    .encuentranos {
      font-weight: bold; /* Poner en negrita el texto "Encuéntranos en:" */
      font-size: 28px; /* Aumentar el tamaño del texto */
      margin-bottom: 20px; /* Más espacio entre "Encuéntranos en:" y los enlaces */
    }
  
    .social-links a {
      display: inline-block;
      margin: 0 30px; /* Aumentar el margen entre los enlaces */
      color: #ffffff; /* Letras blancas para los enlaces */
      text-decoration: none;
      font-weight: bold;
      font-size: 22px; /* Aumentar el tamaño del texto de los enlaces */
    }
  
    .social-links a:hover {
      text-decoration: underline;
    }
  
    .footer-ayuda {
      text-align: right; /* Alinear el texto de ayuda y sobre nosotros a la derecha */
    }
  
    .footer-ayuda p {
      margin: 15px 0;
      font-size: 24px; /* Aumentar el tamaño de la fuente */
      color: white; /* Letras blancas */
    }
  </style>
  