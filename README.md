<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Team Scarlet Roses - Reclutamiento</title>
  <style>
    @import url('https://fonts.googleapis.com/css2?family=Bebas+Neue&family=Poppins:wght@400;600;700&display=swap');

    * { margin: 0; padding: 0; box-sizing: border-box; }

    body {
      background: linear-gradient(135deg, #0A0A1A 0%, #1A001A 50%, #000A1A 100%);
      font-family: 'Poppins', sans-serif;
      color: #fff;
      min-height: 100vh;
      padding: 20px;
    }

    .container {
      max-width: 650px;
      margin: 0 auto;
      text-align: center;
    }

    .logo {
      font-family: 'Bebas Neue', sans-serif;
      font-size: 12vw;
      background: linear-gradient(90deg, #FF0040, #0040FF);
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
      letter-spacing: 3px;
      margin-bottom: 10px;
      text-shadow: 0 0 30px rgba(255,0,64,0.5);
    }

    .subtitle {
      color: #FF0040;
      font-size: 5vw;
      margin-bottom: 25px;
    }

    .card {
      background: rgba(255,255,255,0.05);
      border: 2px solid;
      border-image: linear-gradient(90deg, #FF0040, #0040FF) 1;
      border-radius: 20px;
      padding: 25px;
      margin: 20px 0;
      backdrop-filter: blur(10px);
    }

    .card h2 {
      font-family: 'Bebas Neue';
      font-size: 7vw;
      margin-bottom: 15px;
      background: linear-gradient(90deg, #FF0040, #0040FF);
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
    }

    .list {
      text-align: left;
      font-size: 4vw;
      line-height: 1.8;
    }

    .list li {
      margin: 8px 0;
      list-style: none;
      padding-left: 25px;
      position: relative;
    }

    .list li::before {
      content: '🌹';
      position: absolute;
      left: 0;
    }

    .warning {
      color: #FF0040;
      font-weight: 600;
    }

    .btn {
      display: inline-block;
      background: linear-gradient(90deg, #FF0040, #0040FF);
      color: white;
      padding: 15px 40px;
      border-radius: 50px;
      text-decoration: none;
      font-weight: 700;
      font-size: 4.5vw;
      margin-top: 20px;
      transition: 0.3s;
    }

    .btn:hover {
      transform: scale(1.05);
      box-shadow: 0 0 30px rgba(255,0,64,0.6);
    }

    @media (min-width: 600px) {
      .logo { font-size: 60px; }
      .subtitle, .list, .btn { font-size: 18px; }
      .card h2 { font-size: 32px; }
    }
  </style>
</head>
<body>
  <div class="container">
    <h1 class="logo">SCARLET ROSES</h1>
    <p class="subtitle">🌹 RECLUTAMIENTO ABIERTO 🌹</p>

    <div class="card">
      <h2>REQUISITOS</h2>
      <ul class="list">
        <li>NO excluir a nadie</li>
        <li>Full activo/a</li>
        <li>Tener +14 años</li>
        <li>Ser región Sur</li>
        <li>Respetar gustos</li>
        <li>Ser nivel 40 en adelante</li>
        <li>Disponibilidad horaria para salas y act.</li>
      </ul>
    </div>

    <div class="card">
      <h2>ACLARACIONES</h2>
      <ul class="list">
        <li class="warning">3 advertencias = KICK</li>
        <li>No aparecer a horario sin justificación = advertencia</li>
        <li>Estar en grupo de WhatsApp OBLIGATORIO</li>
        <li>Participar mínimo 3 veces por semana en actividades</li>
        <li>No faltar el respeto a los demás integrantes</li>
      </ul>
    </div>

    <a class="btn" href="https://wa.me/tu_numero">UNIRME AL EQUIPO 🔥</a>
    
    <p style="margin-top:20px; color:#888;">COLORES OFICIALES: ROJO 🔴 Y AZUL 🔵</p>
  </div>
</body>
</html>