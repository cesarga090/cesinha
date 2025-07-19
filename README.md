<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <title>Nosso Amor</title>
  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
      background: #fff0f5;
      color: #333;
      margin: 0;
      padding: 0;
      text-align: center;
    }

    header {
      background: #ff99aa;
      color: white;
      padding: 40px 20px;
    }

    h1 {
      font-size: 2.5em;
      margin-bottom: 10px;
    }

    .timeline {
      margin: 40px auto;
      max-width: 600px;
      padding: 0 20px;
    }

    .event {
      background: #fff;
      border-left: 5px solid #ff5e78;
      margin: 20px 0;
      padding: 20px;
      text-align: left;
      box-shadow: 0 2px 8px rgba(0,0,0,0.1);
      border-radius: 8px;
    }

    .gallery {
      margin: 40px 0;
      background-color: #fff;
      padding: 20px;
    }

    .gallery h2 {
      margin-bottom: 20px;
    }

    .photo-grid {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 15px;
      padding: 10px;
    }

    .photo-grid img {
      width: 100%;
      max-width: 250px;
      border-radius: 10px;
      box-shadow: 0 0 10px rgba(0,0,0,0.15);
      transition: transform 0.3s;
    }

    .photo-grid img:hover {
      transform: scale(1.05);
    }

    section h2 {
      margin-top: 40px;
      font-size: 1.8em;
    }

    iframe {
      margin-top: 20px;
      border-radius: 10px;
    }

    footer {
      margin-top: 60px;
      font-size: 0.9em;
      color: #888;
      padding: 20px;
    }
  </style>
</head>
<body>

  <header>
    <h1>Surpresa para Meu Amor ❤️</h1>
    <p>Uma homenagem feita com todo meu carinho, para você!</p>
  </header>

  <section class="timeline">
    <h2>Nosso Capítulo Especial</h2>
    <div class="event">
      <strong>Começo dessa fase especial:</strong> 21 de setembro de 2023 ✨
    </div>
    <div class="event">
      <strong>Hoje:</strong> Já se passaram <span id="diasNovaFase"></span> dias juntos nessa nova etapa!
    </div>
  </section>

  <section class="gallery">
    <h2>Nossas Memórias</h2>
    <div class="photo-grid">
      <img src="foto1.jpg" alt="Foto 1 do casal">
      <img src="foto2.jpg" alt="Foto 2 do casal">
      <img src="foto3.jpg" alt="Foto 3 do casal">
      <img src="foto4.jpg" alt="Foto 4 do casal">
      <img src="foto5.jpg" alt="Foto 5 do casal">
    </div>
  </section>

  <section>
    <h2>Nossa Música</h2>
    <iframe width="300" height="170"
      src="https://www.youtube.com/embed/QtKQfNIl69o?autoplay=1&loop=1&playlist=QtKQfNIl69o"
      frameborder="0"
      allow="autoplay; encrypted-media"
      allowfullscreen>
    </iframe>
    <p><em>Aliança – Tribalistas</em></p>
  </section>

  <footer>
    <p>Feito com amor ❤️ por [cesinha]</p>
  </footer>

  <script>
    // Nova fase desde 21/09/2023
    const dataInicio = new Date("2023-09-21");
    const hoje = new Date();
    const diffTime = Math.abs(hoje - dataInicio);
    const diffDays = Math.ceil(diffTime / (1000 * 60 * 60 * 24));
    document.getElementById("diasNovaFase").textContent = diffDays;
  </script>

</body>
</html>