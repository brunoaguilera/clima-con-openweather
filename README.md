<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Clima Actual</title>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css">
  <style>
    body {
      font-family: 'Roboto', sans-serif;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      margin: 0;
      background: linear-gradient(to right, #f0f4f8, #ffffff); /* Fondo claro elegante */
      color: #333;
    }
    .container {
      background: white;
      padding: 20px;
      border-radius: 10px;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
      max-width: 400px;
      width: 100%;
      text-align: center;
      transition: transform 0.3s ease-in-out;
    }
    .container:hover {
      transform: translateY(-10px);
    }
    h2 {
      margin-bottom: 20px;
      font-weight: 500;
    }
    .icon {
      width: 50px;
      height: 50px;
    }
  </style>
</head>
<body>
  <div class="container">
    <h2><i class="fas fa-sun"></i> Clima Actual</h2>
    <p>Este proyecto muestra el clima actual de una ubicación ingresada por el usuario.</p>
    <ul>
      <li><i class="fas fa-map-marker-alt"></i> Ubicación: Ingresa un lugar para obtener su clima actual.</li>
      <li><i class="fas fa-thermometer-half"></i> Temperatura: Se muestra en grados Celsius.</li>
      <li><i class="fas fa-cloud"></i> Descripción del clima: Se muestra una breve descripción del clima actual.</li>
      <li><i class="fas fa-tint"></i> Humedad: Se muestra el porcentaje de humedad actual.</li>
      <li><i class="fas fa-wind"></i> Viento: Se muestra la velocidad del viento en metros por segundo.</li>
    </ul>
    <p>¡Espero que disfrutes de este proyecto!</p>
  </div>
</body>
</html>