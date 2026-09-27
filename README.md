<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <title>Rist Technological Production Online School</title>

  <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    body {
      font-family: Arial, sans-serif;
      line-height: 1.6;
      background: #f5f7fa;
      color: #222;
    }

    header {
      background: #12355b;
      color: white;
      padding: 25px 15px;
      text-align: center;
    }

    header h1 {
      font-size: 28px;
      margin-bottom: 8px;
    }

    header p {
      font-size: 16px;
    }

    nav {
      background: #0b2239;
      padding: 12px;
      text-align: center;
    }

    nav a {
      color: white;
      text-decoration: none;
      margin: 0 10px;
      font-weight: bold;
    }

    nav a:hover {
      color: #ffd166;
    }

    .hero {
      background: white;
      text-align: center;
      padding: 55px 20px;
    }

    .hero h2 {
      font-size: 32px;
      color: #12355b;
      margin-bottom: 15px;
    }

    .hero p {
      max-width: 750px;
      margin: auto;
      font-size: 17px;
    }

    .button {
      display: inline-block;
      margin-top: 25px;
      padding: 13px 25px;
      background: #12355b;
      color: white;
      text-decoration: none;
      border-radius: 6px;
      font-weight: bold;
    }

    .button:hover {
      background: #0b2239;
    }

    section {
      padding: 40px 20px;
      max-width: 1100px;
      margin: auto;
    }

    section h2 {
      text-align: center;
      color: #12355b;
      margin-bottom: 25px;
    }

    .courses {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(230px, 1fr));
      gap: 18px;
    }

    .course {
      background: white;
      padding: 22px;
      border-radius: 8px;
      box-shadow: 0 2px 8px rgba(0,0,0,0.08);
    }

    .course h3 {
      color: #12355b;
      margin-bottom: 8px;
    }

    .about {
      background: white;
      border-radius: 8px;
      padding: 30px;
    }

    .languages {
      text-align: center;
      margin-top: 25px;
      font-weight: bold;
    }

    footer {
      background: #0b2239;
      color: white;
      text-align: center;
      padding: 25px 15px;
      margin-top: 30px;
    }

    @media (max-width: 600px) {
      header h1 {
        font-size: 22px;
      }

      .hero h2 {
        font-size: 26px;
      }

      nav a {
        display: inline-block;
        margin: 5px;
      }
    }
  </style>
</head>

<body>

  <header>
    <h1>Rist Technological Production Online School</h1>
    <p>Technology • Engineering • Innovation • Practical Skills</p>
  </header>

  <nav>
    <a href="#home">Home</a>
    <a href="#courses">Courses</a>
    <a href="#about">About</a>
    <a href="#register">Register</a>
  </nav>

  <div class="hero" id="home">
    <h2>Learn Technology. Build the Future.</h2>

    <p>
      Welcome to Rist Technological Production Online School.
      Our online learning platform provides practical and innovative
      technology education for students, professionals and technology
      enthusiasts.
    </p>

    <a
      class="button"
      href="https://forms.gle/g4UGA7FhJ9jjYZtw8"
      target="_blank">
      Register Now
    </a>
  </div>

  <section id="courses">
    <h2>Our Courses</h2>

    <div class="courses">

      <div class="course">
        <h3>☀️ Solar Energy Technology</h3>
        <p>Solar power systems, installation, design and maintenance.</p>
      </div>

      <div class="course">
        <h3>🌬️ Wind Energy Technology</h3>
        <p>Wind energy systems, turbines and renewable-energy applications.</p>
      </div>

      <div class="course">
        <h3>🌱 Biofuel & Biomass</h3>
        <p>Biomass conversion, biofuel production and sustainable energy.</p>
      </div>

      <div class="course">
        <h3>🚜 Agricultural Mechanization</h3>
        <p>Modern agricultural machinery, equipment and mechanization.</p>
      </div>

      <div class="course">
        <h3>⚡ Power Converter Technology</h3>
        <p>Power electronics, converters, inverters and electrical systems.</p>
      </div>

      <div class="course">
        <h3>🚗 Electric Vehicle Technology</h3>
        <p>EV systems, batteries, motors, charging and maintenance.</p>
      </div>

      <div class="course">
        <h3>🌾 Agricultural Technology</h3>
        <p>Modern technology for productive and sustainable agriculture.</p>
      </div>

      <div class="course">
        <h3>🔋 Rural Energy Technology</h3>
        <p>Affordable renewable-energy solutions for rural communities.</p>
      </div>

      <div class="course">
        <h3>🔌 Electrical & Electronics</h3>
        <p>Electrical circuits, electronics and practical engineering skills.</p>
      </div>

      <div class="course">
        <h3>🤖 Robotics & Drones</h3>
        <p>Robotics, automation, drones and intelligent technology.</p>
      </div>

      <div class="course">
        <h3>🚀 Aerospace Technology</h3>
        <p>Introduction to aerospace systems and emerging technologies.</p>
      </div>

      <div class="course">
        <h3>⚛️ Quantum Physics & Quantum Circuits</h3>
        <p>Introduction to quantum physics, quantum computing and circuits.</p>
      </div>

    </div>
  </section>

  <section id="about">
    <h2>About Rist Online School</h2>

    <div class="about">
      <p>
        Rist Technological Production Online School is an educational
        platform focused on technology, engineering, renewable energy,
        agriculture, electronics, transportation and emerging technologies.
      </p>

      <div class="languages">
        English • Afaan Oromo • Amharic
      </div>
    </div>
  </section>

  <section id="register">
    <h2>Student Registration</h2>

    <div style="text-align:center;">
      <p>
        Ready to start learning? Register through our online registration form.
      </p>

      <a
        class="button"
        href="https://forms.gle/g4UGA7FhJ9jjYZtw8"
        target="_blank">
        Register for a Course
      </a>
    </div>
  </section>

  <footer>
    <p>© 2026 Rist Technological Production Online School</p>
    <p>Rist Technological Production PLC</p>
  </footer>

</body>
</html>
