<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>AshEditz - Professional Video Editing</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600;700&display=swap" rel="stylesheet">
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Poppins', sans-serif;
    }

    body {
      background-color: #0f0f0f;
      color: #ffffff;
      line-height: 1.6;
    }

    header {
      background: linear-gradient(to right, #1f1c2c, #928dab);
      padding: 60px 20px;
      text-align: center;
    }

    header h1 {
      font-size: 3rem;
      font-weight: 700;
    }

    header p {
      font-size: 1.2rem;
      margin-top: 10px;
    }

    nav {
      background: #1c1c1c;
      display: flex;
      justify-content: center;
      gap: 30px;
      padding: 15px 0;
    }

    nav a {
      color: #00ffff;
      text-decoration: none;
      font-weight: 600;
    }

    section {
      padding: 60px 20px;
      max-width: 1200px;
      margin: auto;
    }

    h2 {
      font-size: 2.2rem;
      margin-bottom: 20px;
      color: #00ffff;
      text-align: center;
    }

    .services, .portfolio {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 30px;
    }

    .card {
      background: #1e1e1e;
      padding: 25px;
      border-radius: 12px;
      box-shadow: 0 0 20px rgba(0, 255, 255, 0.1);
      text-align: center;
    }

    .card h3 {
      margin-bottom: 10px;
      color: #00ffff;
    }

    .card p {
      font-size: 0.95rem;
      color: #ccc;
    }

    .btn {
      display: inline-block;
      margin-top: 20px;
      padding: 12px 30px;
      background: #00ffff;
      color: #000;
      font-weight: bold;
      border: none;
      border-radius: 5px;
      text-decoration: none;
      transition: 0.3s;
    }

    .btn:hover {
      background: #00dddd;
    }

    footer {
      background: #111;
      text-align: center;
      padding: 30px;
      font-size: 0.9rem;
      color: #aaa;
    }

    a {
      color: #00ffff;
    }
  </style>
</head>
<body>
  <header>
    <h1>AshEditz</h1>
    <p>Professional, Affordable & Creative Video Editing Services</p>
  </header>

  <nav>
    <a href="#services">Services</a>
    <a href="#portfolio">Portfolio</a>
    <a href="#contact">Contact</a>
  </nav>

  <section id="services">
    <h2>Our Services</h2>
    <div class="services">
      <div class="card">
        <h3>YouTube Video Editing</h3>
        <p>Custom thumbnails, engaging cuts, intros/outros, and royalty-free music included.</p>
      </div>
      <div class="card">
        <h3>Social Media Reels</h3>
        <p>Short, punchy edits for Instagram Reels, TikTok, and YouTube Shorts with effects & captions.</p>
      </div>
      <div class="card">
        <h3>Event Highlights</h3>
        <p>Birthday, school functions, and other event edits with cinematic feel and background music.</p>
      </div>
    </div>
  </section>

  <section id="portfolio">
    <h2>Portfolio</h2>
    <div class="portfolio">
      <div class="card">
        <h3>Birthday Highlights</h3>
        <p>Coming Soon – contact for sample clips!</p>
      </div>
      <div class="card">
        <h3>School Projects</h3>
        <p>Beautifully edited videos for school presentations and events.</p>
      </div>
      <div class="card">
        <h3>Vlogs & Short Films</h3>
        <p>Engaging cuts and storytelling edits for personal or school vlog projects.</p>
      </div>
    </div>
  </section>

  <section id="contact">
    <h2>Contact Me</h2>
    <p>Email: <a href="mailto:asheditz@gmail.com">asheditz@gmail.com</a></p>
    <p>WhatsApp: <a href="https://wa.me/94XXXXXXXXX">+94 XXXXXXXXX</a></p>
    <a class="btn" href="mailto:asheditz@gmail.com">Request a Free Quote</a>
  </section>

  <footer>
    &copy; 2025 AshEditz | Designed with passion by a young creator.
  </footer>
</body>
</html>
