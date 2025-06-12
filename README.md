# mycode
my first respositorty
<br>
Author-Kinza Batool
<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Kinza Batool Portfolio</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600&display=swap" rel="stylesheet" />
  <script src="https://kit.fontawesome.com/a076d05399.js" crossorigin="anonymous"></script>
  <style>
    body {
      margin: 0;
      font-family: 'Poppins', sans-serif;
      background-color: #0d1117;
      color: white;
    }

    nav {
      background-color: #0d1117;
      display: flex;
      justify-content: center;
      gap: 25px;
      padding: 15px 0;
    }

    nav a {
      color: white;
      text-decoration: none;
      text-transform: uppercase;
      font-weight: bold;
      font-size: 14px;
      transition: color 0.3s ease;
    }

    nav a:hover {
      color: #58a6ff;
    }

    #home {
      display: flex;
      flex-wrap: wrap;
      justify-content: space-between;
      align-items: center;
      padding: 60px 40px;
    }

    #home img {
      max-width: 300px;
      border-radius: 20px;
    }

    .hero-text {
      max-width: 600px;
    }

    .hero-text h1 {
      font-size: 40px;
      margin-bottom: 20px;
    }

    .hero-text p {
      font-size: 18px;
      color: #ccc;
    }

    .hero-buttons a {
      padding: 12px 25px;
      margin: 15px 10px 0 0;
      border-radius: 5px;
      text-decoration: none;
      font-weight: 500;
    }

    .btn-primary {
      background-color: #58a6ff;
      color: white;
    }

    .btn-outline {
      border: 2px solid #58a6ff;
      color: #58a6ff;
      background: transparent;
    }

    section {
      padding: 60px 40px;
    }

    .skills,
    .projects,
    .contact,
    .comments,
    .about {
      background-color: #161b22;
      border-radius: 10px;
      padding: 30px;
      margin-bottom: 40px;
    }

    h2 {
      color: #58a6ff;
      margin-bottom: 20px;
    }

    footer {
      text-align: center;
      padding: 20px;
      background-color: #0d1117;
      color: #ccc;
    }

    ul {
      padding-left: 20px;
    }
  </style>
</head>

<body>

  <!-- Navigation -->
  <nav>
    <a href="#home">Home</a>
    <a href="#about">About</a>
    <a href="#skills">Skills</a>
    <a href="#projects">Projects</a>
    <a href="#contact">Contact</a>
    <a href="#comments">Comments</a>
  </nav>

  <!-- Home Section -->
  <section id="home">
    <div class="hero-text">
      <h1>I'm <span style="color:#58a6ff;">Kinza Batool</span><br />a Web Developer</h1>
      <p>Web Developer Intern at <strong>CoreTechInnovations</strong></p>
      <div class="hero-buttons">
        <a href="#contact" class="btn-primary">Hire Me</a>
        <a href="#projects" class="btn-outline">My Work</a>
      </div>
      <div style="margin-top: 20px;">
        <a href="https://github.com/yourusername" target="_blank">
          <i class="fab fa-github" style="color:white; font-size: 24px; margin-right: 15px;"></i>
        </a>
      </div>
    </div>
    <div>
      <img src="companylogo.jpg" alt="Kinza Batool Image" />
    </div>
  </section>

  <!-- About Me Section -->
  <section id="about" class="about">
    <h2>About Me</h2>
    <p>
      I am a passionate and creative web developer who enjoys crafting beautiful, responsive, and user-friendly websites.
      My journey into web development started with a curiosity to understand how websites work, and it has grown into a
      deep love for turning ideas into functional digital experiences. I enjoy writing clean code and continuously learning
      new technologies to improve my craft.
    </p>
  </section>

  <!-- Skills Section -->
  <section id="skills" class="skills">
    <h2>Skills</h2>
    <ul>
      <li>HTML</li>
      <li>CSS</li>
      <li>JavaScript</li>
      <li>Responsive Design</li>
    </ul>
  </section>

  <!-- Projects Section -->
  <section id="projects" class="projects">
    <h2>Projects</h2>
    <p>
      <strong>• Portfolio Website:</strong> Created using HTML and CSS.<br />
      <strong>• Contact Form:</strong> Clean and functional contact form.<br />
      <strong>• Upcoming:</strong> JavaScript mini apps under development.
    </p>
  </section>

  <!-- Contact Section -->
  <section id="contact" class="contact">
    <h2>Contact Me</h2>
    <p>Email: batoolk084@example.com<br />Phone: +92-3121306469</p>
  </section>

  <!-- Comments Section -->
  <section id="comments" class="comments">
    <h2>Comments</h2>
    <p>Thanks for checking my portfolio! I’d love to hear your feedback. 😊</p>
  </section>

  <!-- Footer -->
  <footer>
    &copy; 2025 CoreTechInnovations. All rights reserved.
  </footer>

</body>
</html>
