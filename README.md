html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <title>Nossa História de Amor</title>
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

    .gallery img {
      width: 90%;
      max-width: 300px;
      margin: 10px;
      border-radius: 10px;
      box-shadow: 0 0 10px rgba(0,0,0,0.2);
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
    <h2>Nossa Linha do Tempo</h2>
    <div class="event">
      <strong>Início do nosso relacionamento:</strong> 18 de julho de 2020 💕
    </div>
    <div class="event">
      <strong>Hoje:</strong> Já se passaram <span id="dias"></span> dias de amor!
    </div>
  </section>

  <section class="gallery">
    <h2>Nossas Memórias</h2>
    <!-- Adicione quantas fotos quiser aqui -->
    <img src="foto1.jpg" alt="Foto 1 do casal">
    <img src="foto2.jpg" alt="Foto 2 do casal">
    <img src="foto3.jpg" alt="Foto 3 do casal">
  </section>

  <section>
    <h2>Nossa Música</h2>
    <iframe width="300" height="170"
      src="https://www.youtube.com/embed/QlYbN5ZP-cM?autoplay=1&loop=1&playlist=QlYbN5ZP-cM"
      frameborder="0"
      allow="autoplay; encrypted-media"
      allowfullscreen>
    </iframe>
    <p><em>Aliança – Tribalistas</em></p>
  </section>

  <footer>
    <p>Feito com amor ❤️ por [Seu Nome]</p>
  </footer>

  <script>
    const dataInicio = new Date("2020-07-18");
    const hoje = new Date();
    const diffTime = Math.abs(hoje - dataInicio);
    const diffDays = Math.ceil(diffTime / (1000 * 60 * 60 * 24));
    document.getElementById("dias").textContent = diffDays;
  </script>

</body>
</html>