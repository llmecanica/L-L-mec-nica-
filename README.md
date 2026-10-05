<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <title>L&L Mecânica | Seu carro em boas mãos</title>

  <meta name="description" content="L&L Mecânica - manutenção, revisão e serviços automotivos. Fale conosco pelo WhatsApp.">

  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: Arial, sans-serif;
    }

    body {
      background: #0b0b0b;
      color: #fff;
      line-height: 1.6;
    }

    header {
      background: #111;
      padding: 18px 6%;
      display: flex;
      justify-content: space-between;
      align-items: center;
      border-bottom: 1px solid #222;
    }

    .logo {
      font-size: 25px;
      font-weight: bold;
      color: #fff;
    }

    .logo span {
      color: #e50914;
    }

    .hero {
      min-height: 75vh;
      display: flex;
      align-items: center;
      padding: 60px 7%;
      background:
        linear-gradient(rgba(0,0,0,.75), rgba(0,0,0,.9)),
        radial-gradient(circle at center, #333 0%, #080808 70%);
    }

    .hero-content {
      max-width: 750px;
    }

    .hero h1 {
      font-size: clamp(42px, 8vw, 75px);
      line-height: 1;
      margin-bottom: 20px;
    }

    .hero h1 span {
      color: #e50914;
    }

    .hero p {
      font-size: 20px;
      color: #ccc;
      margin-bottom: 30px;
    }

    .button {
      display: inline-block;
      background: #e50914;
      color: white;
      text-decoration: none;
      padding: 15px 25px;
      border-radius: 8px;
      font-weight: bold;
      transition: .2s;
    }

    .button:hover {
      transform: scale(1.03);
      background: #ff1824;
    }

    section {
      padding: 60px 7%;
    }

    .title {
      text-align: center;
      margin-bottom: 40px;
    }

    .title h2 {
      font-size: 36px;
      margin-bottom: 10px;
    }

    .title p {
      color: #aaa;
    }

    .services {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
      gap: 20px;
    }

    .card {
      background: #151515;
      border: 1px solid #292929;
      border-radius: 12px;
      padding: 25px;
      transition: .2s;
    }

    .card:hover {
      transform: translateY(-5px);
      border-color: #e50914;
    }

    .card h3 {
      margin-bottom: 10px;
      color: #fff;
    }

    .card p {
      color: #aaa;
    }

    .contact {
      text-align: center;
      background: #111;
    }

    .contact p {
      color: #bbb;
      margin-bottom: 25px;
    }

    footer {
      text-align: center;
      padding: 25px;
      background: #080808;
      color: #777;
      font-size: 14px;
    }

    .whatsapp {
      position: fixed;
      right: 20px;
      bottom: 20px;
      width: 58px;
      height: 58px;
      border-radius: 50%;
      background: #25D366;
      color: white;
      display: flex;
      align-items: center;
      justify-content: center;
      text-decoration: none;
      font-size: 27px;
      box-shadow: 0 5px 20px rgba(0,0,0,.5);
      z-index: 10;
    }
  </style>
</head>

<body>

<header>
  <div class="logo">L&L <span>MECÂNICA</span></div>
</header>

<section class="hero">
  <div class="hero-content">
    <h1>Seu carro em <span>boas mãos.</span></h1>

    <p>
      Manutenção, revisão e serviços automotivos
      com qualidade e confiança.
    </p>

    <a class="button"
       href="https://wa.me/5522999590010"
       target="_blank">
      Falar pelo WhatsApp
    </a>
  </div>
</section>

<section>
  <div class="title">
    <h2>Nossos Serviços</h2>
    <p>Cuidamos do seu veículo do jeito que ele merece.</p>
  </div>

  <div class="services">

    <div class="card">
      <h3>🔧 Manutenção Preventiva</h3>
      <p>
        Cuidados para evitar problemas e manter seu veículo sempre funcionando bem.
      </p>
    </div>

    <div class="card">
      <h3>🚗 Revisão Automotiva</h3>
      <p>
        Avaliação dos principais componentes do veículo.
      </p>
    </div>

    <div class="card">
      <h3>⚙️ Reparos Mecânicos</h3>
      <p>
        Soluções para problemas mecânicos do seu carro.
      </p>
    </div>

    <div class="card">
      <h3>💻 Diagnóstico Automotivo</h3>
      <p>
        Identificação de falhas para encontrar a solução correta.
      </p>
    </div>

    <div class="card">
      <h3>🛢️ Troca de Óleo</h3>
      <p>
        Troca de óleo e cuidados essenciais para o motor.
      </p>
    </div>

    <div class="card">
      <h3>🛞 Freios e Suspensão</h3>
      <p>
        Manutenção para mais segurança e estabilidade.
      </p>
    </div>

  </div>
</section>

<section class="contact">
  <div class="title">
    <h2>Precisa de um mecânico?</h2>
    <p>Entre em contato com a L&L Mecânica.</p>
  </div>

  <a class="button"
     href="https://wa.me/5522999590010"
     target="_blank">
    📲 Chamar no WhatsApp
  </a>
</section>

<footer>
  © 2026 L&L Mecânica — Todos os direitos reservados.
</footer>

<a class="whatsapp"
   href="https://wa.me/5522999590010"
   target="_blank"
   aria-label="WhatsApp">
  ☎
</a>

</body>
</html>