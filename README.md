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
</html>
/* Reset */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

/* Base Styles */
body {
  font-family: 'Segoe UI', sans-serif;
  line-height: 1.6;
  background: #f4f4f4;
  color: #333;
}

.container {
  width: 90%;
  max-width: 1000px;
  margin: auto;
  padding: 40px 0;
}

header {
  background: #111;
  color: #fff;
  padding: 20px 0;
}

nav {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 0 10%;
}

nav h1 {
  font-size: 24px;
}

nav ul {
  list-style: none;
  display: flex;
  gap: 20px;
}

nav a {
  color: #fff;
  text-decoration: none;
  font-weight: bold;
}

.section {
  padding: 60px 0;
  background: #fff;
}

.section:nth-child(even) {
  background: #f9f9f9;
}

h2 {
  text-align: center;
  margin-bottom: 30px;
}

.hero-image {
  width: 100%;
  max-height: 400px;
  object-fit: cover;
  margin-top: 20px;
  border-radius: 8px;
}

.services-list {
  display: flex;
  justify-content: space-around;
  flex-wrap: wrap;
  gap: 15px;
  font-size: 18px;
}

.gallery-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
  gap: 20px;
}

.gallery-grid img {
  width: 100%;
  height: 200px;
  object-fit: cover;
  border-radius: 6px;
  box-shadow: 0 2px 8px rgba(0,0,0,0.2);
}

.contact-form {
  display: flex;
  flex-direction: column;
  gap: 15px;
}

.contact-form input,
.contact-form textarea {
  padding: 10px;
  border: 1px solid #ccc;
  border-radius: 4px;
  font-size: 16px;
}

.contact-form button {
  background: #111;
  color: #fff;
  padding: 10px;
  font-size: 16px;
  border: none;
  border-radius: 4px;
  cursor: pointer;
}

.contact-form button:hover {
  background: #333;
}

.social-links {
  text-align: center;
  margin-top: 20px;
}

.social-links a {
  margin: 0 10px;
  text-decoration: none;
  color: #111;
  font-weight: bold;
}

footer {
  background: #222;
  color: #aaa;
  text-align: center;
  padding: 20px 0;
  font-size: 14px;
}