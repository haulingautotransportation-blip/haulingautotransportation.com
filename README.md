<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Welcome to My Website</title>
  <style>
    body {
      font-family: 'Segoe UI', Arial, sans-serif;
      background: #f8f9fa;
      margin: 0;
      padding: 0;
      color: #222;
    }
    header {
      background: #004aad;
      color: #fff;
      padding: 2rem 1rem 1rem 1rem;
      text-align: center;
    }
    nav {
      margin: 1rem 0;
      text-align: center;
    }
    nav a {
      color: #004aad;
      text-decoration: none;
      margin: 0 1rem;
      font-weight: bold;
    }
    nav a:hover {
      text-decoration: underline;
    }
    main {
      max-width: 700px;
      margin: 2rem auto;
      background: #fff;
      padding: 2rem;
      border-radius: 8px;
      box-shadow: 0 4px 12px rgba(0,0,0,0.05);
    }
    img {
      max-width: 100%;
      border-radius: 8px;
    }
    footer {
      margin-top: 2rem;
      text-align: center;
      color: #777;
      font-size: 0.96em;
    }
  </style>
</head>
<body>
  <header>
    <h1>Welcome to My Website!</h1>
    <p>Your catchy slogan goes here.</p>
  </header>
  <nav>
    <a href="#about">About</a>
    <a href="#services">Services</a>
    <a href="#contact">Contact</a>
  </nav>
  <main>
    <section id="about">
      <h2>About Me</h2>
      <p>
        Hello! I’m glad you’re here. This is a sample website built with GitHub Pages and a custom domain. <br>
        You can update this section to introduce yourself, your business, or your portfolio.
      </p>
      <img src="https://images.unsplash.com/photo-1506744038136-46273834b3fb?auto=format&fit=crop&w=800&q=80" alt="Sample" />
    </section>
    <section id="services">
      <h2>Services</h2>
      <ul>
        <li>Custom Web Design</li>
        <li>Branding & Logo</li>
        <li>SEO Optimization</li>
        <li>And more...</li>
      </ul>
    </section>
    <section id="contact">
      <h2>Contact</h2>
      <p>Email: <a href="mailto:your@email.com">your@email.com</a></p>
      <p>
        You can also add your phone, social media or a contact form.
      </p>
    </section>
  </main>
  <footer>
    &copy; 2025 Your Name. All rights reserved.
  </footer>
</body>
</html>
