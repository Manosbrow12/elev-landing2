<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Elev Marketing Digital</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;700&display=swap" rel="stylesheet">
  <style>
    body {
      font-family: 'Inter', sans-serif;
      margin: 0;
      background: #f2f4f7; /* fundo suave */
      color: #333333;
      line-height: 1.6;
    }
    header {
      background: #0b1f3f;
      color: #ffffff;
      padding: 3rem 1rem;
      text-align: center;
    }
    header h1 {
      margin: 0;
      font-size: 2.5rem;
      color: #ff8c00;
    }
    header p {
      font-size: 1.2rem;
      margin-top: 0.5rem;
      color: #ffffff;
    }
    .container {
      max-width: 900px;
      margin: 0 auto;
      padding: 0 1rem;
    }
    .hero {
      background: #ffffff;
      padding: 4rem 2rem;
      margin-top: -2rem;
      border-radius: 16px;
      box-shadow: 0 8px 24px rgba(0,0,0,0.08);
      text-align: center;
      position: relative;
      z-index: 1;
    }
    .hero h2 {
      font-size: 2.25rem;
      color: #0b1f3f;
      margin-bottom: 1rem;
    }
    .hero p {
      font-size: 1.15rem;
      color: #555555;
      margin-bottom: 2rem;
    }
    .hero form {
      display: flex;
      flex-direction: column;
      gap: 1rem;
      align-items: center;
    }
    .hero input[type="text"], .hero input[type="email"] {
      width: 100%;
      max-width: 400px;
      padding: 1rem;
      font-size: 1rem;
      border: 1px solid #ccd1d9;
      border-radius: 8px;
      background: #f9fafb;
    }
    .hero button {
      padding: 1rem 2rem;
      font-size: 1.1rem;
      background: #ff8c00;
      color: #ffffff;
      border: none;
      border-radius: 8px;
      cursor: pointer;
      transition: background 0.3s;
      font-weight: 600;
    }
    .hero button:hover {
      background: #e07b00;
    }
    .testimonials {
      margin: 4rem 0;
      text-align: center;
    }
    .testimonials h2 {
      font-size: 2rem;
      color: #0b1f3f;
      margin-bottom: 2rem;
    }
    .testimonial {
      background: #ffffff;
      margin: 1rem auto;
      padding: 2rem;
      max-width: 700px;
      border-radius: 12px;
      box-shadow: 0 4px 16px rgba(0,0,0,0.05);
      font-style: italic;
      color: #444444;
      position: relative;
    }
    .testimonial::before {
      content: '“';
      font-size: 4rem;
      position: absolute;
      top: -10px;
      left: 20px;
      color: #ff8c00;
    }
    .testimonial strong {
      display: block;
      margin-top: 1rem;
      font-style: normal;
      font-weight: 600;
      color: #0b1f3f;
    }
    .whatsapp {
      text-align: center;
      margin: 3rem 0;
    }
    .whatsapp a {
      background: #25d366;
      color: #ffffff;
      padding: 1rem 2rem;
      border-radius: 50px;
      text-decoration: none;
      font-weight: 600;
      transition: background 0.3s;
      display: inline-block;
    }
    .whatsapp a:hover {
      background: #1ebe5d;
    }
    footer {
      text-align: center;
      padding: 2rem 1rem;
      font-size: 0.9rem;
      color: #777777;
      border-top: 1px solid #e2e8f0;
      background: #ffffff;
    }
    @media(min-width: 768px) {
      .hero { margin-top: -3rem; }
    }
  </style>
</head>
<body>
  <header>
    <div class="container">
      <h1>Elev Marketing Digital</h1>
      <p>Tráfego Pago, Inteligência Comercial e Crescimento Exponencial</p>
    </div>
  </header>

  <section class="hero container">
    <h2>Uma Onda de Clientes Qualificados Chegando Até Você</h2>
    <p>Descubra os segredos por trás de campanhas matadoras que geram resultados reais e impulsionam seu faturamento.</p>
    <form action="https://formsubmit.co/seu-email@dominio.com" method="POST">
      <input type="hidden" name="_captcha" value="false">
      <input type="hidden" name="_subject" value="Novo lead - Consultoria Elev">
      <input type="text" name="name" placeholder="Seu nome" required>
      <input type="email" name="email" placeholder="Seu e-mail" required>
      <button type="submit">Quero Acesso Agora</button>
    </form>
  </section>

  <section class="testimonials container">
    <h2>O que dizem nossos clientes</h2>
    <div class="testimonial">
      Depois da consultoria com a Elev, meu faturamento dobrou em 3 meses!
      <strong>— Ana Paula, Loja de Roupas</strong>
    </div>
    <div class="testimonial">
      As estratégias de tráfego transformaram meu negócio!
      <strong>— Carlos Mendes, Agência de Turismo</strong>
    </div>
  </section>

  <section class="whatsapp container">
    <a href="https://wa.me/5547988664048?text=Ol%C3%A1%2C%20me%20interessei%20pelo%20seu%20servi%C3%A7o%20e%20quero%20saber%20mais" target="_blank">Fale com nossa equipe agora!</a>
  </section>

  <footer>
    <div class="container">
      &copy; 2025 Elev Marketing Digital. Todos os direitos reservados.
    </div>
  </footer>
</body>
</html>
