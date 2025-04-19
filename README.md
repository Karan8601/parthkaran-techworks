<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>ParthKaran Techworks</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;800&display=swap" rel="stylesheet">
  <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
      font-family: 'Inter', sans-serif;
    }
    body {
      line-height: 1.6;
      color: #333;
      background: #f7f9fc;
    }
    header, footer {
      background: #1e293b;
      color: white;
      padding: 2rem;
      text-align: center;
    }
    nav a {
      color: white;
      margin: 0 1rem;
      text-decoration: none;
      font-weight: 600;
    }
    .container {
      padding: 2rem;
      max-width: 1100px;
      margin: auto;
    }
    .hero {
      text-align: center;
      padding: 4rem 2rem;
      background: #e2e8f0;
      border-radius: 12px;
    }
    .hero h1 {
      font-size: 2.5rem;
      margin-bottom: 1rem;
    }
    .hero p {
      font-size: 1.2rem;
      margin-bottom: 2rem;
    }
    .hero button {
      margin: 0.5rem;
      padding: 0.75rem 1.5rem;
      border: none;
      background: #3b82f6;
      color: white;
      font-size: 1rem;
      border-radius: 8px;
      cursor: pointer;
    }
    section {
      margin-bottom: 3rem;
    }
    h2 {
      color: #1e293b;
      margin-bottom: 1rem;
    }
    ul {
      list-style-type: none;
      padding-left: 1rem;
    }
    ul li::before {
      content: "✅ ";
    }
    .contact-form input, .contact-form textarea {
      width: 100%;
      padding: 0.75rem;
      margin-bottom: 1rem;
      border: 1px solid #ccc;
      border-radius: 6px;
    }
    .contact-form button {
      background: #1e40af;
      color: white;
      border: none;
      padding: 0.75rem 1.5rem;
      border-radius: 6px;
      cursor: pointer;
    }
    .testimonials p {
      font-style: italic;
      margin-bottom: 1rem;
    }
    .footer-links a {
      color: #cbd5e1;
      margin: 0 0.5rem;
      text-decoration: none;
    }
  </style>
</head>
<body>
  <header>
    <h1>ParthKaran Techworks</h1>
    <p>Code with Purpose. Build with Legacy.</p>
    <nav>
      <a href="#about">About</a>
      <a href="#services">Services</a>
      <a href="#portfolio">Portfolio</a>
      <a href="#testimonials">Testimonials</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>
  <main class="container">
    <section class="hero">
      <h1>Welcome to ParthKaran Techworks</h1>
      <p>We build websites and apps that power ideas and bring digital dreams to life — with clean code and care.</p>
      <button>Explore Our Services</button>
      <button>Get a Free Quote</button>
    </section>
    <section id="about">
      <h2>About Us</h2>
      <p>I'm Karan Yadav, a passionate full-stack developer from Lucknow with expertise in building modern websites and applications. I founded ParthKaran Techworks to bring high-quality development to individuals and businesses — and named it after my son Parth to make every line of code more meaningful.</p>
      <h3>Our Vision:</h3>
      <p>To create impactful digital experiences with a personal touch.</p>
      <h3>Core Values:</h3>
      <ul>
        <li>Trust</li>
        <li>Innovation</li>
        <li>Quality</li>
        <li>Family First</li>
      </ul>
    </section>
    <section id="services">
      <h2>Services</h2>
      <ul>
        <li>Full-Stack Web Development – React, Node.js, Laravel, MongoDB, MySQL</li>
        <li>Mobile App Development – Flutter, React Native</li>
        <li>E-Commerce Website Setup – Shopify, WooCommerce, custom stores</li>
        <li>UI/UX Design – Responsive, user-friendly interfaces</li>
        <li>Website Maintenance & Support – Affordable plans</li>
      </ul>
    </section>
    <section id="portfolio">
      <h2>Portfolio</h2>
      <p>Coming Soon — Launching real project showcases soon! Stay tuned.</p>
    </section>
    <section id="testimonials" class="testimonials">
      <h2>Testimonials</h2>
      <p>“Karan and the team at ParthKaran Techworks gave my startup the perfect tech backbone. Super easy to work with!” – Neha M.</p>
      <p>“Reliable and professional. Highly recommended for quality web work.” – Arjun S.</p>
    </section>
    <section id="contact">
      <h2>Contact Us</h2>
      <p>Let’s build something amazing together.</p>
      <p>📧 mainhucoder@gmail.com<br>📱 +91 8601865676<br>🏠 Keshav Nagar, Faizullaganj, Lucknow, Uttar Pradesh, India<br>🌍 Available Nationwide & Globally</p>
      <div class="contact-form">
        <input type="text" placeholder="Your Name">
        <input type="email" placeholder="Your Email">
        <input type="text" placeholder="Project Type">
        <textarea rows="5" placeholder="Your Message"></textarea>
        <button>Send Message</button>
      </div>
    </section>
  </main>
  <footer>
    <p>© 2025 ParthKaran Techworks. All rights reserved.</p>
    <div class="footer-links">
      <a href="#">Privacy Policy</a> |
      <a href="#">Terms & Conditions</a>
    </div>
  </footer>
</body>
</html>
