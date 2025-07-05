<!DOCTYPE html>
<html lang="pt">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Descoberta surpreendente no mundo dos jogos online</title>
  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
      background: #fff;
      color: #222;
      margin: 0;
      padding: 0;
    }
    .container {
      max-width: 680px;
      margin: auto;
      padding: 20px;
    }
    h1, h2 {
      color: #111;
      line-height: 1.3;
    }
    .highlight {
      background-color: #f0f8ff;
      padding: 12px;
      border-left: 4px solid #00aaff;
      margin: 20px 0;
      font-style: italic;
    }
    ul {
      padding-left: 20px;
    }
    .video-container {
      position: relative;
      padding-bottom: 56.25%;
      height: 0;
      overflow: hidden;
      margin: 20px 0;
    }
    .video-container iframe {
      position: absolute;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
    }
    .timer {
      font-size: 18px;
      font-weight: bold;
      color: #d9534f;
      text-align: center;
      margin: 20px 0;
    }
    a.button {
      display: block;
      width: 100%;
      max-width: 300px;
      margin: 30px auto;
      background-color: #00aaff;
      color: #fff;
      text-align: center;
      padding: 14px;
      text-decoration: none;
      border-radius: 6px;
      font-size: 18px;
      font-weight: bold;
    }
    a.button:hover {
      background-color: #0077cc;
    }
    @media (max-width: 480px) {
      h1 {
        font-size: 22px;
      }
      .container {
        padding: 15px;
      }
    }
  </style>
</head>
<body>
  <div class="container">
    <h1>Engenheiro português revela como multiplicou seu saldo 6x em jogos online</h1>

    <p><strong>Lisboa, Portugal</strong> — Miguel S., um engenheiro de 32 anos do Porto, afirma ter descoberto uma estratégia matemática que o ajuda a ganhar de forma consistente em jogos online.</p>

    <div class="highlight">
      “Não sou hacker nem vigarista. Apenas uso lógica e as ferramentas legais da plataforma,” diz Miguel.
    </div>

    <p>Ele começou com apostas pequenas na plataforma <strong>888.pt</strong> e viu seu saldo multiplicar-se em apenas duas semanas.</p>

    <div class="video-container">
      <iframe src="https://www.youtube.com/embed/dQw4w9WgXcQ" title="Vídeo de demonstração" frameborder="0" allowfullscreen></iframe>
    </div>

    <h2>📈 Qual é o segredo?</h2>
    <ul>
      <li>Escolher jogos com alto RTP</li>
      <li>Aproveitar bônus e rodadas grátis com inteligência</li>
      <li>Jogar em horários estratégicos</li>
    </ul>

    <p>Miguel não vende cursos nem cobra por conselhos. Ele apenas recomenda experimentar por conta própria — com responsabilidade e disciplina.</p>

    <div class="timer">
      ⚠️ Oferta especial disponível por tempo limitado: <span id="countdown">05:00</span>
    </div>

    <a class="button" href="https://www.888.pt" target="_blank">Experimentar agora no 888.pt</a>
  </div>

  <script>
    // Таймер обратного отсчёта
    let time = 300;
    const countdownEl = document.getElementById('countdown');
    const timer = setInterval(() => {
      const minutes = Math.floor(time / 60);
      const seconds = time % 60;
      countdownEl.textContent = `${minutes.toString().padStart(2, '0')}:${seconds.toString().padStart(2, '0')}`;
      time--;
      if (time < 0) clearInterval(timer);
    }, 1000);
  </script>
</body>
</html>
