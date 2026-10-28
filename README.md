 <!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>NJ Technology Solutions | Innovation for Everyone</title>

<meta name="description" content="NJ Technology Solutions provides software development, IT support, cloud solutions, networking and technology consulting.">

<style>
:root {
  --navy: #061426;
  --blue: #087cf5;
  --cyan: #12c8ff;
  --white: #ffffff;
  --light: #f1f6fc;
  --text: #172a44;
}

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  scroll-behavior: smooth;
}

body {
  font-family: Arial, Helvetica, sans-serif;
  color: var(--text);
  line-height: 1.6;
}

a {
  text-decoration: none;
}

.container {
  width: min(1150px, 90%);
  margin: auto;
}

/* NAVIGATION */

header {
  background: var(--navy);
  color: white;
  position: sticky;
  top: 0;
  z-index: 100;
  border-bottom: 1px solid #20354c;
}

nav {
  min-height: 78px;
  display: flex;
  align-items: center;
  justify-content: space-between;
  gap: 20px;
}

.logo {
  font-size: 24px;
  font-weight: 800;
  color: white;
}

.logo span {
  color: var(--cyan);
}

.nav-links {
  display: flex;
  gap: 22px;
  align-items: center;
}

.nav-links a {
  color: white;
  font-size: 14px;
}

.nav-links a:hover {
  color: var(--cyan);
}

.btn {
  display: inline-block;
  padding: 13px 23px;
  background: var(--blue);
  color: white;
  border-radius: 8px;
  font-weight: bold;
  transition: 0.2s;
}

.btn:hover {
  background: #0065d1;
  transform: translateY(-2px);
}

.menu-button {
  display: none;
  background: none;
  color: white;
  border: 1px solid #456078;
  border-radius: 6px;
  padding: 8px 12px;
  font-size: 20px;
}

/* HERO */

.hero {
  background:
    radial-gradient(ellipse at 85% 40%, #073b75 0%, transparent 45%),
    linear-gradient(120deg, #020b17, #061c35);
  color: white;
  padding: 85px 0;
  overflow: hidden;
}

.hero-grid {
  display: grid;
  grid-template-columns: 1.15fr 0.85fr;
  gap: 35px;
  align-items: center;
}

.eyebrow {
  color: var(--cyan);
  letter-spacing: 2px;
  text-transform: uppercase;
  font-size: 12px;
  font-weight: bold;
}

.hero h1 {
  font-size: clamp(38px, 5vw, 64px);
  line-height: 1.1;
  margin: 20px 0;
}

.hero h1 span {
  color: var(--cyan);
}

.hero p {
  color: #d0dfef;
  max-width: 570px;
  margin-bottom: 28px;
}

.hero-actions {
  display: flex;
  gap: 14px;
  flex-wrap: wrap;
}

.btn-outline {
  border: 1px solid #b5c8dc;
  padding: 12px 23px;
  border-radius: 8px;
  color: white;
}

.btn-outline:hover {
  background: white;
  color: var(--navy);
}

.tech-visual {
  min-height: 320px;
  display: flex;
  align-items: center;
  justify-content: center;
}

.tech-card {
  width: 100%;
  max-width: 410px;
  padding: 30px 20px;
  text-align: center;
  border: 1px solid #1677ca;
  border-radius: 20px;
  background: linear-gradient(145deg, #102f51, #04101f);
  box-shadow: 0 0 55px #087cf530;
}

.tech-icon {
  font-size: 78px;
  margin-bottom: 10px;
}

.tech-card h2 {
  color: var(--cyan);
  font-size: 24px;
}

.tech-card p {
  margin: 12px auto 0;
}

/* SERVICES */

.services {
  padding: 75px 0;
  background: var(--white);
}

.section-title {
  text-align: center;
  margin-bottom: 40px;
}

.section-title h2 {
  font-size: 34px;
  color: var(--navy);
  margin: 8px 0;
}

.section-title p {
  color: #62738a;
}

.service-grid {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 22px;
}

.service-card {
  padding: 28px;
  border: 1px solid #e0eaf5;
  border-radius: 14px;
  background: white;
  transition: 0.2s;
}

.service-card:hover {
  transform: translateY(-5px);
  box-shadow: 0 12px 35px #0c2e5014;
}

.service-icon {
  width: 55px;
  height: 55px;
  display: grid;
  place-items: center;
  border-radius: 12px;
  background: #e8f3ff;
  font-size: 27px;
  margin-bottom: 18px;
}

.service-card h3 {
  margin-bottom: 10px;
  color: var(--navy);
}

.service-card p {
  color: #62738a;
  font-size: 14px;
}

/* ABOUT */

.about {
  padding: 75px 0;
  background: var(--light);
}

.about-grid {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 50px;
  align-items: center;
}

.about h2 {
  color: var(--navy);
  font-size: 34px;
  line-height: 1.2;
  margin: 12px 0 20px;
}

.about p {
  color: #53657b;
  margin-bottom: 22px;
}

.values {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 15px;
}

.value {
  padding: 22px;
  border-radius: 12px;
  background: white;
  border: 1px solid #e1eaf4;
}

.value strong {
  color: var(--blue);
  display: block;
  margin-bottom: 6px;
}

/* CONTACT */

.contact {
  background: var(--navy);
  color: white;
  text-align: center;
  padding: 75px 0;
}

.contact h2 {
  font-size: 34px;
  margin: 12px 0;
}

.contact p {
  color: #c4d3e5;
  margin-bottom: 25px;
}

footer {
  background: #020b15;
  color: #a9bacd;
  padding: 24px 0;
  font-size: 13px;
}

.footer-content {
  display: flex;
  justify-content: space-between;
  flex-wrap: wrap;
  gap: 12px;
}

/* MOBILE */

@media (max-width: 800px) {
  .menu-button {
    display: block;
  }

  .nav-links {
    display: none;
    position: absolute;
    top: 78px;
    left: 0;
    width: 100%;
    padding: 25px 5%;
    background: var(--navy);
    flex-direction: column;
    align-items: flex-start;
  }

  .nav-links.open {
    display: flex;
  }

  .hero {
    padding: 60px 0;
  }

  .hero-grid,
  .about-grid {
    grid-template-columns: 1fr;
  }

  .tech-visual {
    min-height: 250px;
  }

  .service-grid {
    grid-template-columns: 1fr 1fr;
  }
}

@media (max-width: 520px) {
  .service-grid,
  .values {
    grid-template-columns: 1fr;
  }

  .hero h1 {
    font-size: 39px;
  }

  .section-title h2,
  .about h2,
  .contact h2 {
    font-size: 29px;
  }

  .footer-content {
    flex-direction: column;
  }
}
</style>
</head>

<body>

<header>
  <nav class="container">
    <a href="#home" class="logo">NJ <span>TECHNOLOGY</span></a>

    <button class="menu-button"
      onclick="document.querySelector('.nav-links').classList.toggle('open')"
      aria-label="Toggle navigation">☰</button>

    <div class="nav-links">
      <a href="#home">Home</a>
      <a href="#about">About</a>
      <a href="#services">Services</a>
      <a href="#contact">Contact</a>
      <a href="#contact" class="btn">Get Started →</a>
    </div>
  </nav>
</header>

<main>

<section class="hero" id="home">
  <div class="container hero-grid">

    <div>
      <div class="eyebrow">Innovation | Solutions | Tomorrow</div>

      <h1>
        NJ Technology<br>
        <span>Building a Smarter Digital World</span>
      </h1>

      <p>
        We help businesses and individuals use technology to
        achieve more. From software development to IT support,
        we turn ideas into practical digital solutions.
      </p>

      <div class="hero-actions">
        <a class="btn" href="#services">Explore Our Services →</a>
        <a class="btn-outline" href="#contact">Contact Us</a>
      </div>
    </div>

    <div class="tech-visual">
      <div class="tech-card">
        <div class="tech-icon">💻</div>
        <h2>Technology That Works</h2>
        <p>
          Software. Networks. Cloud. Security.
          One partner for your digital journey.
        </p>
        <div style="font-size:32px;margin-top:20px">
          🌐 ☁️ 🛡️
        </div>
      </div>
    </div>

  </div>
</section>

<section class="services" id="services">
  <div class="container">

    <div class="section-title">
      <div class="eyebrow">What We Do</div>
      <h2>Our Technology Services</h2>
      <p>Solutions designed to help you work smarter and grow.</p>
    </div>

    <div class="service-grid">

      <article class="service-card">
        <div class="service-icon">💻</div>
        <h3>Software Development</h3>
        <p>Websites, mobile applications and custom software built around your needs.</p>
      </article>

      <article class="service-card">
        <div class="service-icon">☁️</div>
        <h3>Cloud Solutions</h3>
        <p>Cloud-based tools and digital services to help your business work efficiently.</p>
      </article>

      <article class="service-card">
        <div class="service-icon">🛡️</div>
        <h3>IT Support & Security</h3>
        <p>Technical troubleshooting, security reviews and support for your systems.</p>
      </article>

      <article class="service-card">
        <div class="service-icon">🌐</div>
        <h3>Network Solutions</h3>
        <p>Network setup, connectivity support and troubleshooting for devices.</p>
      </article>

      <article class="service-card">
        <div class="service-icon">📱</div>
        <h3>Digital Products</h3>
        <p>Practical digital tools and technology products for everyday needs.</p>
      </article>

      <article class="service-card">
        <div class="service-icon">💡</div>
        <h3>Technology Consulting</h3>
        <p>Guidance to help you choose, plan and use technology effectively.</p>
      </article>

    </div>
  </div>
</section>

<section class="about" id="about">
  <div class="container about-grid">

    <div>
      <div class="eyebrow">About NJ Technology</div>
      <h2>Your Partner in Digital Innovation</h2>

      <p>
        NJ Technology Solutions is focused on making technology
        more useful, accessible and practical for businesses
        and individuals.
      </p>

      <p>
        Our goal is to turn ideas into reliable digital solutions
        through creativity, thoughtful design and technology.
      </p>

      <a class="btn" href="#contact">Work With Us →</a>
    </div>

    <div class="values">
      <div class="value">
        <strong>Innovation</strong>
        Fresh ideas and modern digital solutions.
      </div>

      <div class="value">
        <strong>Reliability</strong>
        Practical solutions built around your needs.
      </div>

      <div class="value">
        <strong>Customer Focus</strong>
        Technology designed with people in mind.
      </div>

      <div class="value">
        <strong>Growth</strong>
        Helping you move forward with confidence.
      </div>
    </div>

  </div>
</section>

<section class="contact" id="contact">
  <div class="container">
    <div class="eyebrow">Let's Connect</div>
    <h2>Have an Idea? Let's Build It.</h2>
    <p>Contact NJ Technology Solutions to discuss your next project.</p>

    <!-- Replace the email address with your real business email -->
    <a class="btn" href="mailto:YOUR-EMAIL@example.com">
      Contact NJ Technology →
    </a>
  </div>
</section>

</main>

<footer>
  <div class="container footer-content">
    <div>© <span id="year"></span> NJ Technology Solutions.</div>
    <div>Building a Smarter Digital World.</div>
  </div>
</footer>

<script>
document.getElementById("year").textContent =
  new Date().getFullYear();
</script>

</body>
</html>
