# Mang-oli-Digital
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Mang'oli Digital</title>
  <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;700&family=Roboto&display=swap" rel="stylesheet">
  <style>
    body {
      font-family: 'Roboto', sans-serif;
      margin: 0;
      padding: 0;
      color: #000;
      background: #fff;
      transition: background 0.3s, color 0.3s;
    }
    header {
      background-color: #2196F3;
      color: white;
      padding: 2rem;
      text-align: center;
      font-family: 'Montserrat', sans-serif;
    }
    nav {
      display: flex;
      justify-content: center;
      gap: 2rem;
      background-color: #000;
      padding: 1rem;
    }
    nav a {
      color: white;
      text-decoration: none;
      font-weight: bold;
      transition: color 0.3s;
    }
    nav a:hover {
      color: #2196F3;
    }
    section {
      padding: 3rem 2rem;
      max-width: 900px;
      margin: auto;
      animation: fadeIn 1s ease-in;
    }
    @keyframes fadeIn {
      from {opacity: 0; transform: translateY(20px);}
      to {opacity: 1; transform: translateY(0);}
    }
    h2 {
      font-family: 'Montserrat', sans-serif;
      color: #2196F3;
    }
    footer {
      background-color: #000;
      color: white;
      text-align: center;
      padding: 2rem 1rem;
    }
    .contact-form input, .contact-form textarea {
      width: 100%;
      padding: 0.75rem;
      margin: 0.5rem 0;
      border: 1px solid #ccc;
      border-radius: 5px;
    }
    .contact-form button {
      background-color: #2196F3;
      color: white;
      border: none;
      padding: 0.75rem 1.5rem;
      border-radius: 5px;
      cursor: pointer;
    }
    .portfolio-item {
      background: #f5f5f5;
      margin: 1rem 0;
      padding: 1rem;
      border-left: 4px solid #2196F3;
      border-radius: 5px;
    }
  </style>
</head>
<body>
  <header>
    <h1>Mang'oli Digital</h1>
    <p>Crafting Visual Impact. Empowering Digital Brands.</p>
  </header>

  <nav>
    <a href="#about">About</a>
    <a href="#services">Services</a>
    <a href="#portfolio">Portfolio</a>
    <a href="#contact">Contact</a>
  </nav>

  <section id="about">
    <h2>About Us</h2>
    <p>Mang'oli Digital is a creative powerhouse based in Kenya, focused on crafting distinctive brand experiences across digital platforms. We specialize in transforming ideas into visual stories, connecting businesses with their audiences through intelligent design, innovative development, and authentic storytelling.</p>
    <p>We work with startups, SMEs, and established brands, helping them elevate their digital presence and achieve measurable growth.</p>
    <ul>
      <li>Creativity fuels connection</li>
      <li>Design is strategy</li>
      <li>Every brand deserves a bold digital voice</li>
    </ul>
  </section>

  <section id="services">
    <h2>Our Services</h2>
    <h3>Brand Identity & Design</h3>
    <p>We create bold, modern visual identities — from logos to full brand systems.</p>
    <ul>
      <li>Logo Design</li>
      <li>Brand Guidelines</li>
      <li>Typography & Color Systems</li>
      <li>Stationery Design</li>
    </ul>

    <h3>Web Design & Development</h3>
    <p>Fast, mobile-friendly websites built to engage and convert.</p>
    <ul>
      <li>UI/UX Design</li>
      <li>HTML, CSS, WordPress</li>
      <li>Landing Pages</li>
    </ul>

    <h3>Digital Strategy & Marketing</h3>
    <p>Grow your digital presence with targeted content and campaigns.</p>
    <ul>
      <li>Social Media Design</li>
      <li>SEO Basics</li>
      <li>Content Strategy</li>
      <li>Digital Campaigns</li>
    </ul>
  </section>

  <section id="portfolio">
    <h2>Portfolio</h2>
    <div class="portfolio-item">
      <h4>Brand Redesign for XYZ Corp</h4>
      <p>We revamped their identity with a modern, scalable logo and cohesive digital presence.</p>
    </div>
    <div class="portfolio-item">
      <h4>NGO Website Launch</h4>
      <p>Custom WordPress site for a non-profit, featuring donation and blog functionality.</p>
    </div>
    <div class="portfolio-item">
      <h4>Social Media Campaign – EcoShop</h4>
      <p>Developed brand-aligned creatives and content calendars to boost online engagement by 45%.</p>
    </div>
  </section>

  <section id="contact">
    <h2>Contact Us</h2>
    <form class="contact-form" name="contact" method="POST" data-netlify="true">
      <input type="hidden" name="form-name" value="contact" />
      <input type="text" name="name" placeholder="Your Name" required />
      <input type="email" name="email" placeholder="Your Email" required />
      <textarea name="message" rows="5" placeholder="Your Message" required></textarea>
      <button type="submit">Send Message</button>
    </form>
  </section>

  <footer>
    <p>Follow us:</p>
    <p>
      <a href="#" style="color: #2196F3;">Instagram</a> |
      <a href="#" style="color: #2196F3;">Facebook</a> |
      <a href="#" style="color: #2196F3;">LinkedIn</a>
    </p>
    <p>&copy; 2025 Mang'oli Digital. All rights reserved.</p>
  </footer>
</body>
</html>
