<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Buscadores</title>

  <style>
    body{
      font-family: Arial, sans-serif;
      background: linear-gradient(to right, #4facfe, #00f2fe);
      text-align: center;
      margin: 0;
      padding: 0;
    }

    h1{
      color: white;
      margin-top: 40px;
      font-size: 50px;
    }

    p{
      color: white;
      font-size: 20px;
    }

    .contenedor{
      margin-top: 50px;
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
      gap: 20px;
    }

    .boton{
      background: white;
      color: #333;
      text-decoration: none;
      padding: 20px 40px;
      border-radius: 15px;
      font-size: 22px;
      transition: 0.3s;
      box-shadow: 0px 4px 10px rgba(0,0,0,0.2);
    }

    .boton:hover{
      background: #333;
      color: white;
      transform: scale(1.1);
    }
  </style>
</head>

<body>

  <h1>🔎 BUSCADORES</h1>
  <p>Selecciona un buscador para entrar</p>

  <div class="contenedor">

    <a class="boton" href="https://www.google.com" target="_blank">
      Google
    </a>

    <a class="boton" href="https://www.bing.com" target="_blank">
      Bing
    </a>

    <a class="boton" href="https://search.yahoo.com" target="_blank">
      Yahoo
    </a>

    <a class="boton" href="https://duckduckgo.com" target="_blank">
      DuckDuckGo
    </a>

    <a class="boton" href="https://www.apple.com/safari/" target="_blank">
      Safari
    </a>

  </div>

</body>
</html># estudio-