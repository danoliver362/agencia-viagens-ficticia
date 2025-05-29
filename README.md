
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <title>Sua Viagem</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background: linear-gradient(to bottom right, #a6e3e9, #71c9ce);
    }

    header {
      background-color: #8BC34A;
      padding: 15px 30px;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }

    nav a {
      color: white;
      text-decoration: none;
      margin: 0 15px;
      font-weight: bold;
    }

    .logo {
      font-size: 28px;
      font-weight: bold;
      color: white;
    }

    .logo span {
      color: #0B7189;
    }

    .login-buttons {
      display: flex;
      gap: 15px;
    }

    .login-buttons a {
      color: white;
      background-color: #4CAF50;
      padding: 8px 16px;
      border-radius: 20px;
      text-decoration: none;
    }

    .container {
      display: flex;
      align-items: center;
      justify-content: center;
      padding: 40px;
      flex-wrap: wrap;
    }

    .texto {
      flex: 1;
      min-width: 300px;
      background-color: #8BC34A;
      padding: 30px;
      border-radius: 12px;
      color: white;
      font-size: 22px;
      box-shadow: 0 4px 10px rgba(0, 0, 0, 0.2);
      margin: 15px;
    }

    .mapa {
      flex: 1;
      min-width: 300px;
      text-align: center;
      margin: 15px;
    }

    .mapa img {
      max-width: 100%;
      border-radius: 10px;
    }
  </style>
</head>
<body>

  <header>
    <div class="logo">SUAM <span>VIAGEM</span></div>
    <nav>
      <a href="#">INÍCIO</a>
      <a href="#">SOBRE NÓS</a>
    </nav>
    <div class="login-buttons">
      <a href="#">CADASTRE-SE</a>
      <a href="#">LOGIN</a>
    </div>
  </header>

  <section class="container">
    <div class="mapa">
      <img src="pngwing.com.png" usemap="mapaBrasil" alt="Mapa do Brasil">
      <map name="mapaBrasil">
          <area shape="poly" 
           coords="386,464,477,429,521,360,472,307,412,314,368,366,351,381,342,391,327,414"
          alt="Sudeste" title="Sudeste" href="submenu.html" target="_blank">
      </map>
    </div>
    <div class="texto">
      "Descubra o Brasil, um destino de cada vez. Sua próxima aventura começa aqui."
    </div>
  </section>

</body>
</html>
