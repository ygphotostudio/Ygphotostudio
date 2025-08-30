## Hi there 👋

<!--
**ygphotostudio/Ygphotostudio** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>My Portfolio</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>

  <!-- Navigation -->
  <header>
    <nav>
      <h1>My Portfolio</h1>
      <ul>
        <li><a href="#home">Home</a></li>
        <li><a href="#services">Services</a></li>
        <li><a href="#gallery">Gallery</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
  </header>

  <!-- Home Section -->
  <section id="home" class="section home">
    <div class="container">
      <h2>Welcome to My Portfolio</h2>
      <p>I create stunning visuals, websites, and digital art.</p>
      <img src="images/hero.jpg" alt="Hero Image" class="hero-image"/>
    </div>
  </section>

  <!-- Services Section -->
  <section id="services" class="section">
    <div class="container">
      <h2>Services</h2>
      <ul class="services-list">
        <li>Web Design</li>
        <li>Photography</li>
        <li>Graphic Design</li>
        <li>UI/UX Consulting</li>
      </ul>
    </div>
  </section>

  <!-- Gallery Section -->
  <section id="gallery" class="section">
    <div class="container">
      <h2>Gallery</h2>
      <div class="gallery-grid">
        <img src="images/album1/image1.jpg" alt="Gallery 1"/>
        <img src="images/album1/image2.jpg" alt="Gallery 2"/>
        <img src="images/album2/image1.jpg" alt="Gallery 3"/>
        <img src="images/album2/image2.jpg" alt="Gallery 4"/>
      </div>
    </div>
  </section>

  <!-- Contact Section -->
  <section id="contact" class="section">
    <div class="container">
      <h2>Contact Me</h2>
      <form class="contact-form" action="#" method="POST">
        <input type="text" name="name" placeholder="Your Name" required/>
        <input type="email" name="email" placeholder="Your Email" required/>
        <textarea name="message" placeholder="Your Message" required></textarea>
        <button type="submit">Send</button>
      </form>
      <div class="social-links">
        <a href="#">Instagram</a>
        <a href="#">LinkedIn</a>
        <a href="#">GitHub</a>
      </div>
    </div>
  </section>

  <footer>
    <p>&copy; 2025 My Portfolio. All rights reserved.</p>
  </footer>

</body>
</html>/