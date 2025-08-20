<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Anant Dwivedi | Web Developer</title>
  <style>
    * { margin: 0; padding: 0; box-sizing: border-box; font-family: Arial, sans-serif; }
    body { background: #f9f9f9; color: #333; }
    header { background: #1a1a1a; color: #fff; padding: 20px 10%; text-align: center; }
    header h1 { font-size: 2.5rem; margin-bottom: 10px; }
    header p { font-size: 1.2rem; }

    nav { background: #333; padding: 10px; text-align: center; }
    nav a { color: #fff; margin: 0 15px; text-decoration: none; font-weight: bold; }
    nav a:hover { color: #ff9800; }

    section { padding: 50px 10%; }
    h2 { margin-bottom: 20px; font-size: 2rem; color: #1a1a1a; border-bottom: 3px solid #ff9800; display: inline-block; }

    .about, .skills, .projects, .contact { margin-bottom: 50px; }

    .skills-list { display: flex; flex-wrap: wrap; gap: 10px; }
    .skills-list span { background: #ff9800; color: #fff; padding: 8px 15px; border-radius: 5px; }

    .project-card { background: #fff; border: 1px solid #ddd; border-radius: 10px; padding: 20px; margin: 20px 0; box-shadow: 0 4px 6px rgba(0,0,0,0.1); }
    .project-card h3 { margin-bottom: 10px; }
    .project-card a { color: #ff9800; text-decoration: none; font-weight: bold; }

    .contact form { display: flex; flex-direction: column; gap: 15px; }
    .contact input, .contact textarea { padding: 10px; border: 1px solid #ccc; border-radius: 5px; width: 100%; }
    .contact button { background: #ff9800; color: white; border: none; padding: 12px; border-radius: 5px; cursor: pointer; font-size: 1rem; }
    .contact button:hover { background: #e68900; }

    footer { background: #1a1a1a; color: #fff; text-align: center; padding: 15px; }
  </style>
</head>
<body>

  <!-- Header -->
  <header>
    <h1>Hello, I'm Anant Dwivedi</h1>
    <p>A Student & Web Developer</p>
  </header>

  <!-- Navbar -->
  <nav>
    <a href="#about">About</a>
    <a href="#skills">Skills</a>
    <a href="#projects">Projects</a>
    <a href="#contact">Contact</a>
  </nav>

  <!-- About Section -->
  <section id="about" class="about">
    <h2>About Me</h2>
    <p>
      I am a passionate student learning web development. I enjoy creating modern, responsive, and user-friendly websites. 
      My goal is to use my skills to help businesses and individuals establish a strong online presence.
    </p>
  </section>

  <!-- Skills Section -->
  <section id="skills" class="skills">
    <h2>My Skills</h2>
    <div class="skills-list">
      <span>HTML</span>
      <span>CSS</span>
      <span>JavaScript</span>
      <span>React.js</span>
      <span>Node.js</span>
      <span>Git & GitHub</span>
    </div>
  </section>

  <!-- Projects Section -->
  <section id="projects" class="projects">
    <h2>Projects</h2>

    <div class="project-card">
      <h3>Portfolio Website</h3>
      <p>A simple portfolio website showcasing my skills and projects.</p>
      <a href="#">View Project</a>
    </div>

    <div class="project-card">
      <h3>Restaurant Website</h3>
      <p>A modern responsive website for a local restaurant.</p>
      <a href="#">View Project</a>
    </div>

    <div class="project-card">
      <h3>E-commerce Landing Page</h3>
      <p>A sample landing page for an online store.</p>
      <a href="#">View Project</a>
    </div>
  </section>

  <!-- Contact Section -->
  <section id="contact" class="contact">
    <h2>Contact Me</h2>
    <form>
      <input type="text" placeholder="Your Name" required>
      <input type="email" placeholder="Your Email" required>
      <textarea rows="5" placeholder="Your Message"></textarea>
      <button type="submit">Send Message</button>
    </form>
  </section>

  <!-- Footer -->
  <footer>
    <p>© 2025 Anant Dwivedi | All Rights Reserved</p>
  </footer>

</body>
</html> 