<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Mi Perfil - [Tu Nombre]</title>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css" />
  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
      background: #f4f4f4;
      margin: 0;
      padding: 0;
      color: #333;
    }

    header {
      background: #1e1e2f;
      color: white;
      padding: 40px 20px;
      text-align: center;
    }

    header img {
      border-radius: 50%;
      width: 120px;
      height: 120px;
      border: 4px solid #fff;
    }

    header h1 {
      margin: 10px 0 5px;
      font-size: 32px;
    }

    header p {
      margin: 0;
      font-size: 18px;
    }

    section {
      padding: 40px 20px;
      max-width: 900px;
      margin: auto;
    }

    .icon-list {
      display: flex;
      flex-wrap: wrap;
      gap: 20px;
      justify-content: center;
    }

    .icon-item {
      background: white;
      border-radius: 10px;
      box-shadow: 0 4px 8px rgba(0,0,0,0.1);
      padding: 20px;
      text-align: center;
      width: 100px;
    }

    .icon-item i {
      font-size: 32px;
      margin-bottom: 10px;
      color: #1e1e2f;
    }

    .social-links a {
      margin: 0 10px;
      font-size: 24px;
      color: #1e1e2f;
      text-decoration: none;
      transition: color 0.3s;
    }

    .social-links a:hover {
      color: #0077ff;
    }

    footer {
      background: #1e1e2f;
      color: white;
      text-align: center;
      padding: 20px;
    }
  </style>
</head>
<body>

  <header>
    <img src="https://via.placeholder.com/120" alt="Tu Foto" />
    <h1>Tu Nombre</h1>
    <p>Estudiante de Desarrollo de Software | SENA Colombia</p>
  </header>

  <section>
    <h2>Sobre Mí</h2>
    <p>
      Soy estudiante del SENA en Análisis y Desarrollo de Software. Me apasiona crear soluciones tecnológicas que ayuden a las personas.
      Tengo conocimientos en desarrollo de apps móviles con Flutter, backend con PHP, y bases de datos. Busco una oportunidad para realizar mi etapa productiva y seguir creciendo en el mundo del software.
    </p>
  </section>

  <section>
    <h2>Tecnologías que uso</h2>
    <div class="icon-list">
      <div class="icon-item"><i class="fab fa-html5"></i><br />HTML</div>
      <div class="icon-item"><i class="fab fa-css3-alt"></i><br />CSS</div>
      <div class="icon-item"><i class="fab fa-php"></i><br />PHP</div>
      <div class="icon-item"><i class="fas fa-database"></i><br />SQL</div>
      <div class="icon-item"><i class="fas fa-mobile-alt"></i><br />Flutter</div>
      <div class="icon-item"><i class="fas fa-code"></i><br />Dart</div>
    </div>
  </section>

  <section>
    <h2>Redes Sociales</h2>
    <div class="social-links">
      <a href="https://github.com/tuusuario" target="_blank"><i class="fab fa-github"></i></a>
      <a href="https://linkedin.com/in/tuusuario" target="_blank"><i class="fab fa-linkedin"></i></a>
      <a href="mailto:tuemail@gmail.com"><i class="fas fa-envelope"></i></a>
    </div>
  </section>

  <footer>
    © 2025 Tu Nombre | Hecho con 💻 desde Colombia
  </footer>

</body>
</html>
