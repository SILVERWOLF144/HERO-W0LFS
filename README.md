<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>HERO WOLFS - Esports Team</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background-color: #0b0b0b;
      color: #f0f0f0;
    }
    header {
      background-color: #1a1a1a;
      padding: 20px;
      text-align: center;
    }
    header img {
      max-width: 200px;
    }
    h1 {
      font-size: 2.5rem;
      margin: 10px 0;
      color: #ff4500;
    }
    section {
      padding: 40px 20px;
      max-width: 900px;
      margin: auto;
    }
    .roster, .schedule {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 20px;
    }
    .card {
      background-color: #1e1e1e;
      border-radius: 10px;
      padding: 20px;
      text-align: center;
      box-shadow: 0 0 15px rgba(255, 69, 0, 0.3);
    }
    footer {
      text-align: center;
      padding: 20px;
      background-color: #111;
      font-size: 0.9rem;
    }
    a {
      color: #ff4500;
      text-decoration: none;
    }
    a:hover {
      text-decoration: underline;
    }
  </style>
</head>
<body>
  <header>
    <img src="logo.png" alt="Hero Wolfs Logo">
    <h1>HERO WOLFS</h1>
    <p>The fire never dies.</p>
  </header>

  <section>
    <h2>About Us</h2>
    <p>We are HERO WOLFS — a competitive esports team forged in fire and built on teamwork, skill, and strategy. We dominate in the digital arena and bring the heat to every match we play.</p>
  </section>

  <section>
    <h2>Team Roster</h2>
    <div class="roster">
      <div class="card">AlphaWolf<br><small>Leader</small></div>
      <div class="card">FlameShot<br><small>Sniper</small></div>
      <div class="card">ShadowFang<br><small>Support</small></div>
      <div class="card">Blaze<br><small>Fragger</small></div>
    </div>
  </section>

  <section>
    <h2>Upcoming Matches</h2>
    <div class="schedule">
      <div class="card">Apr 10 - VS Cyber Titans</div>
      <div class="card">Apr 15 - VS Ghost Reapers</div>
      <div class="card">Apr 22 - VS Pixel Phantoms</div>
    </div>
  </section>

  <section>
    <h2>Follow Us</h2>
    <p>
      <a href="#">Instagram</a> | <a href="#">Twitter</a> | <a href="#">Twitch</a>
    </p>
  </section>

  <footer>
    &copy; 2025 HERO WOLFS. All rights reserved.
  </footer>
</body>
</html>
