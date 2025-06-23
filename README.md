<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>UNIT-GB LTD</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: #f9f9f9;
      color: #333;
    }
    header {
      background: linear-gradient(to right, #ff7e00, #0052cc);
      color: white;
      padding: 20px;
      display: flex;
      align-items: center;
      justify-content: space-between;
    }
    header img {
      height: 50px;
    }
    nav a {
      margin: 0 15px;
      color: white;
      text-decoration: none;
      font-weight: bold;
    }
    section {
      padding: 40px 20px;
      max-width: 900px;
      margin: auto;
    }
    h1, h2 {
      color: #0052cc;
    }
    form input, form textarea {
      display: block;
      width: 100%;
      margin-bottom: 10px;
      padding: 10px;
      font-size: 1rem;
    }
    form button {
      padding: 10px 20px;
      background: #0052cc;
      color: white;
      border: none;
      cursor: pointer;
    }
    footer {
      background: #222;
      color: white;
      text-align: center;
      padding: 20px;
    }
  </style>
</head>
<body>
  <header>
    <img src="logo_1.png" alt="UNIT Logo" />
    <nav>
      <a href="#home">Home</a>
      <a href="#about">About</a>
      <a href="#services">Services</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <section id="home">
    <h1>Welcome to UNIT-GB LTD</h1>
    <p>We deliver digital transformation and technology consulting services that move your business forward.</p>
  </section>

  <section id="about">
    <h2>About Us</h2>
    <p>UNIT-GB LTD is a UK-based technology and consulting firm helping businesses embrace innovation and efficiency through smart digital solutions.</p>
  </section>

  <section id="services">
    <h2>Our Services</h2>
    <ul>
      <li>Technology & Digital Transformation Consulting</li>
      <li>Web & Application Development</li>
      <li>Data Analytics & Automation</li>
      <li>IT Infrastructure Planning</li>
    </ul>
  </section>

  <section id="contact">
    <h2>Contact Us</h2>
    <form action="mailto:bogdan@unit-gb.com" method="post" enctype="text/plain">
      <input type="text" name="name" placeholder="Your Name" required />
      <input type="email" name="email" placeholder="Your Email" required />
      <textarea name="message" rows="5" placeholder="Your Message"></textarea>
      <button type="submit">Send Message</button>
    </form>
  </section>

  <footer>
    &copy; 2025 UNIT-GB LTD. All rights reserved.
  </footer>
</body>
</html># unit-gb-site
