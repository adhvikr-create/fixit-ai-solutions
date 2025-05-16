<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>FixIt AI Solutions</title>
  <style>
    @import url('https://fonts.googleapis.com/css2?family=Orbitron:wght@500&family=Roboto:wght@400;700&display=swap');

    body {
      margin: 0;
      font-family: 'Roboto', sans-serif;
      background: #0f111b;
      color: #eee;
      display: flex;
      flex-direction: column;
      min-height: 100vh;
      justify-content: center;
      align-items: center;
      padding: 20px;
      text-align: center;
    }

    header {
      font-family: 'Orbitron', sans-serif;
      font-size: 3rem;
      color: #00ffea;
      margin-bottom: 0.2em;
      text-shadow: 0 0 10px #00ffea;
    }

    .tagline {
      font-size: 1.2rem;
      color: #00ffd1;
      margin-bottom: 2em;
      text-shadow: 0 0 6px #00ffd1;
    }

    .services {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 1.5em;
      max-width: 900px;
      width: 100%;
      margin-bottom: 3em;
    }

    .service-item {
      background: linear-gradient(135deg, #00ffd1 0%, #006666 100%);
      border-radius: 12px;
      padding: 20px;
      box-shadow: 0 0 15px #00ffd1;
      color: #021f1f;
      font-weight: 700;
      font-size: 1.1rem;
    }

    .contact {
      font-size: 1.2rem;
      background: #111827;
      padding: 20px 30px;
      border-radius: 12px;
      box-shadow: 0 0 12px #00ffd1;
      max-width: 500px;
      margin-bottom: 2em;
    }

    .contact strong {
      color: #00ffea;
    }

    .btn-contact {
      background: #00ffea;
      color: #021f1f;
      font-weight: 700;
      padding: 15px 30px;
      border-radius: 30px;
      text-decoration: none;
      font-size: 1.2rem;
      box-shadow: 0 0 15px #00ffea;
      transition: background 0.3s ease;
      display: inline-block;
      margin-top: 1em;
    }

    .btn-contact:hover {
      background: #00d1b2;
    }

    footer {
      margin-top: auto;
      font-size: 0.9rem;
      color: #004d4d;
      padding: 10px 0;
    }

    @media (max-width: 480px) {
      header {
        font-size: 2.2rem;
      }
      .services {
        grid-template-columns: 1fr;
      }
    }
  </style>
</head>
<body>

  <header>FixIt AI Solutions</header>
  <div class="tagline">Smarter Business. Simple AI.</div>

  <section class="services" aria-label="Services offered">
    <div class="service-item">💬 WhatsApp Auto Replies Setup</div>
    <div class="service-item">📩 Google Forms for Customer Feedback</div>
    <div class="service-item">🧠 AI-Generated Instagram Captions & Posts</div>
    <div class="service-item">📄 FAQ Page Creation</div>
    <div class="service-item">🧾 Basic Invoice Templates</div>
  </section>

  <section class="contact" aria-label="Contact information">
    <p>Want to boost your business with AI-powered tools? <strong>DM RJ FixIt on Instagram now!</strong></p>
    <a href="https://instagram.com/" target="_blank" rel="noopener" class="btn-contact">DM me on Instagram</a>
  </section>

  <footer>© 2025 FixIt AI Solutions</footer>

</body>
</html>
