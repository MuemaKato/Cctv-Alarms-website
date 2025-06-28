# Cctv-Alarms-website<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>SecureVision | CCTV & Alarms</title>
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@700&display=swap" rel="stylesheet">
  <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }
    body {
      font-family: 'Roboto', sans-serif;
      background-color: #f4f4f4;
      color: #333;
      line-height: 1.6;
    }
    header, nav, .contact, .footer {
      text-align: center;
      padding: 1rem;
    }
    header {
      background-color: #003366;
      color: white;
    }
    nav {
      background-color: #005599;
    }
    nav a {
      color: white;
      text-decoration: none;
      margin: 0.5rem;
      display: inline-block;
      font-weight: bold;
    }
    .hero {
      background: url('https://source.unsplash.com/800x400/?cctv') no-repeat center center/cover;
      height: 240px;
      display: flex;
      align-items: center;
      justify-content: center;
      color: white;
      font-size: 1.5rem;
      padding: 1rem;
      text-shadow: 2px 2px 5px #000;
    }
    .section {
      padding: 1rem;
    }
    .section h2 {
      font-size: 1.5rem;
      color: #003366;
      margin-bottom: 1rem;
    }
    .services {
      display: flex;
      flex-direction: column;
      gap: 1rem;
    }
    @media(min-width: 600px) {
      .services {
        flex-direction: row;
        flex-wrap: wrap;
        justify-content: space-between;
      }
      .card {
        flex: 1 1 calc(33% - 1rem);
        max-width: 30%;
      }
    }
    .card {
      background: white;
      border-radius: 10px;
      box-shadow: 0 2px 6px rgba(0,0,0,0.1);
      padding: 1rem;
      text-align: center;
    }
    .card img {
      width: 100%;
      border-radius: 8px;
    }
    ul {
      margin-left: 1rem;
      padding-left: 1rem;
    }
    input, textarea {
      width: 100%;
      max-width: 400px;
      margin: 0.5rem auto;
      padding: 0.8rem;
      border-radius: 5px;
      border: 1px solid #ccc;
      display: block;
    }
    button {
      background-color: #ff5500;
      color: white;
      padding: 0.8rem 1.2rem;
      border: none;
      border-radius: 5px;
      font-weight: bold;
      cursor: pointer;
      margin-top: 1rem;
    }
    .footer {
      background: #001f33;
      color: white;
    }
    .whatsapp {
      position: fixed;
      bottom: 20px;
      right: 20px;
      z-index: 1000;
    }
    .whatsapp img {
      width: 55px;
      height: 55px;
      border-radius: 50%;
      box-shadow: 0 4px 10px rgba(0,0,0,0.3);
    }
  </style>
</head>
<body>

  <header>
    <h1>SecureVision</h1>
    <p>Your Safety, Our Priority</p>
  </header>

  <nav>
    <a href="#services">Services</a>
    <a href="#maintenance">Maintenance</a>
    <a href="#pricing">Pricing</a>
    <a href="#contact">Contact</a>
  </nav>

  <div class="hero">
    <div>Professional CCTV & Alarm Solutions</div>
  </div>

  <section class="section" id="services">
    <h2>Our Services</h2>
    <div class="services">
      <div class="card">
        <img src="https://source.unsplash.com/400x250/?cctv" alt="CCTV Installation">
        <h3>CCTV Installation</h3>
        <p>Reliable surveillance systems tailored for homes and businesses.</p>
      </div>
      <div class="card">
        <img src="https://source.unsplash.com/400x250/?alarm" alt="Alarm Systems">
        <h3>Alarm Systems</h3>
        <p>Advanced motion detection and alert systems integrated with your devices.</p>
      </div>
      <div class="card">
        <img src="https://source.unsplash.com/400x250/?security-monitoring" alt="Monitoring">
        <h3>24/7 Monitoring</h3>
        <p>Real-time monitoring with instant alerts and secure backups.</p>
      </div>
    </div>
  </section>

  <section class="section" id="maintenance">
    <h2>Maintenance & Support</h2>
    <ul>
      <li>On-site & remote diagnostics</li>
      <li>Firmware and system updates</li>
      <li>Monthly service checks</li>
      <li>Camera repositioning & upgrades</li>
    </ul>
  </section>

  <section class="section" id="pricing">
    <h2>Pricing Packages</h2>
    <div class="services">
      <div class="card">
        <h3>Starter</h3>
        <p>2 Indoor Cameras + Alarm</p>
        <strong>KES 25,000</strong>
      </div>
      <div class="card">
        <h3>Standard</h3>
        <p>4 Cameras + Alarm + App Access</p>
        <strong>KES 45,000</strong>
      </div>
      <div class="card">
        <h3>Premium</h3>
        <p>8 Cameras + Alarm + Monitoring</p>
        <strong>KES 85,000</strong>
      </div>
    </div>
  </section>

  <section class="contact" id="contact">
    <h2>Contact Us</h2>
    <p>Get in touch for a custom quote</p>
    <form action="mailto:info@securevision.co.ke" method="POST" enctype="text/plain">
      <input type="text" name="name" placeholder="Your Name" required>
      <input type="email" name="email" placeholder="Your Email" required>
      <textarea name="message" rows="4" placeholder="What do you need?"></textarea>
      <button type="submit">Send Request</button>
    </form>
  </section>

  <footer class="footer">
    <p>&copy; 2025 SecureVision. All rights reserved.</p>
  </footer>

  <!-- WhatsApp Chat Button -->
  <a class="whatsapp" href="https://wa.me/254712345678" target="_blank">
    <img src="https://upload.wikimedia.org/wikipedia/commons/6/6b/WhatsApp.svg" alt="WhatsApp Chat">
  </a>

</body>
</html>
