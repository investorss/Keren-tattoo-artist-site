<!DOCTYPE html>
<html lang="it">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Keren Tattoo Artist - Prenotazioni</title>
  <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;700&family=Playfair+Display:wght@700&display=swap" rel="stylesheet" />
  <style>
    /* Reset e base */
    * {
      box-sizing: border-box;
    }
    body {
      margin: 0;
      background: linear-gradient(135deg, #0d0d0d, #1a1a1a);
      color: #fceabb;
      font-family: 'Montserrat', sans-serif;
      display: flex;
      flex-direction: column;
      min-height: 100vh;
      scroll-behavior: smooth;
    }
    header {
      background: #111;
      padding: 30px 20px;
      text-align: center;
      font-family: 'Playfair Display', serif;
      font-size: 2.8rem;
      font-weight: 700;
      letter-spacing: 0.1em;
      color: #f0a500;
      text-shadow: 0 0 10px #f0a500;
      border-bottom: 2px solid #f0a500;
    }
    main {
      flex: 1;
      max-width: 900px;
      margin: 40px auto 60px;
      padding: 0 15px;
    }
    section {
      margin-bottom: 60px;
      background: #222;
      border-radius: 15px;
      padding: 25px 30px;
      box-shadow: 0 6px 15px rgba(240, 165, 0, 0.4);
      transition: transform 0.3s ease;
    }
    section:hover {
      transform: translateY(-6px);
      box-shadow: 0 14px 25px rgba(240, 165, 0, 0.7);
    }
    h2 {
      font-family: 'Playfair Display', serif;
      font-size: 2rem;
      color: #f0a500;
      margin-bottom: 20px;
      border-bottom: 3px solid #f0a500;
      padding-bottom: 8px;
      letter-spacing: 0.05em;
    }
    p {
      font-size: 1rem;
      line-height: 1.6;
      color: #fceabb;
    }
    /* Calendly */
    .calendly-inline-widget {
      width: 100%;
      height: 650px;
      border-radius: 15px;
      overflow: hidden;
      box-shadow: 0 8px 20px rgba(240, 165, 0, 0.5);
      border: 2px solid #f0a500;
    }
    /* Instagram */
    .instagram-widget {
      width: 100%;
      height: 520px;
      border-radius: 15px;
      border: 2px solid #f0a500;
      box-shadow: 0 8px 20px rgba(240, 165, 0, 0.5);
      overflow: hidden;
    }
    /* Mappa */
    iframe {
      width: 100%;
      height: 320px;
      border: none;
      border-radius: 15px;
      filter: drop-shadow(0 4px 10px rgba(240, 165, 0, 0.6));
      transition: transform 0.3s ease;
    }
    iframe:hover {
      transform: scale(1.02);
    }
    /* Contatti */
    #contatti a {
      color: #f0a500;
      font-weight: 600;
      text-decoration: none;
      transition: color 0.3s ease;
    }
    #contatti a:hover {
      color: #fff4cc;
      text-decoration: underline;
    }
    footer {
      background: #111;
      text-align: center;
      padding: 20px 10px;
      font-size: 0.9rem;
      color: #665500;
      letter-spacing: 0.05em;
      border-top: 1px solid #333;
    }
    @media (max-width: 600px) {
      header {
        font-size: 2rem;
        padding: 20px 15px;
      }
      main {
        margin: 25px auto 40px;
      }
      section {
        padding: 20px 15px;
        margin-bottom: 40px;
      }
      .calendly-inline-widget {
        height: 550px;
      }
      .instagram-widget {
        height: 420px;
      }
      iframe {
        height: 240px;
      }
    }
  </style>
  <script src="https://assets.calendly.com/assets/external/widget.js" async></script>
</head>
<body>
  <header>
    Keren Tattoo Artist
  </header>
  <main>
    <section id="prenotazioni" aria-label="Prenotazioni appuntamenti">
      <h2>Prenota il tuo appuntamento</h2>
      <div class="calendly-inline-widget" data-url="https://calendly.com/keren_tattoo_artist"></div>
      <p style="margin-top:15px; font-style: italic;">
        Scegli tra: <br />
        – Sessione 15 minuti: Conosciamoci <br />
        – Consulenza 30 minuti <br />
        – Sessione tatuaggio 90 minuti
      </p>
    </section>
    <section id="instagram" aria-label="Galleria Instagram">
      <h2>Galleria Instagram</h2>
      <iframe src="https://snapwidget.com/embed/123456" class="instagram-widget" scrolling="no" allowtransparency="true" title="Instagram feed di Keren Tattoo Artist"></iframe>
    </section>
    <section id="sede" aria-label="Sede Luke’s Tattoo Studio">
      <h2>Luke’s Tattoo Studio</h2>
      <p>Via Filippo Corridoni, 5, 20071 Vermezzo con Zelo MI</p>
      <iframe
        src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d2785.154467720458!2d9.01031531561616!3d45.4069616791012!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x4786e986b647a8a1%3A0xc3896b2aa313d4d0!2sVia%20Filippo%20Corridoni%2C%205%2C%2020071%20Vermezzo%20con%20Zelo%20MI!5e0!3m2!1sit!2sit!4v1692606000000!5m2!1sit!2sit"
        allowfullscreen=""
        loading="lazy"
        referrerpolicy="no-referrer-when-downgrade"
        title="Mappa della sede"></iframe>
    </section>
    <section id="contatti" aria-label="Contatti e social media">
      <h2>Contatti e Social</h2>
      <p>
        Instagram: <a href="https://www.instagram.com/keren_tattoo.artist" target="_blank" rel="noopener noreferrer">keren_tattoo.artist</a>
      </p>
      <p>
        WhatsApp: <a href="https://wa.me/39TUONUMERO" target="_blank" rel="noopener noreferrer">Invia messaggio</a>
      </p>
    </section>
  </main>
  <footer>
    © 2025 Keren Tattoo Artist - Luke’s Tattoo Studio
  </footer>
</body>
</html>
