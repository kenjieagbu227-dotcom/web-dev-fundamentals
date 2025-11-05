MINI PROJECT: PERSONAL PORTFOLIO WEBSITE

🎯 Objective

Build a responsive personal portfolio webpage using HTML, CSS, and JavaScript.
It will showcase your name, skills, projects, and contact info — like a real developer’s website.


---

🧩 Project Structure

portfolio/
│
├── index.html
├── style.css
└── script.js


---

🧱 1. HTML — index.html

This sets up the structure of your portfolio.

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>My Portfolio</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <!-- Header -->
  <header>
    <h1>Hi, I'm <span class="highlight">Rock Xebec</span></h1>
    <p>Front-End Developer | Cybersecurity Enthusiast</p>
    <button id="theme-toggle">🌙 Toggle Dark Mode</button>
  </header>

  <!-- About Section -->
  <section id="about">
    <h2>About Me</h2>
    <p>I’m passionate about creating clean, user-friendly websites and learning modern web technologies.</p>
  </section>

  <!-- Projects Section -->
  <section id="projects">
    <h2>Projects</h2>
    <div class="project-list">
      <div class="project-card">
        <h3>Portfolio Website</h3>
        <p>My first responsive portfolio built with HTML, CSS, and JS.</p>
      </div>
      <div class="project-card">
        <h3>Cybersecurity Notes</h3>
        <p>My GitHub repository for cybersecurity concepts and tutorials.</p>
      </div>
    </div>
  </section>

  <!-- Contact Section -->
  <section id="contact">
    <h2>Contact</h2>
    <p>Email: <a href="mailto:rockxebec@example.com">rockxebec@example.com</a></p>
  </section>

  <footer>
    <p>© 2025 Rock Xebec | Made with ❤️ and JavaScript</p>
  </footer>

  <script src="script.js"></script>
</body>
</html>


---

🎨 2. CSS — style.css

Add styling and responsive design.

/* Basic setup */
body {
  font-family: 'Poppins', sans-serif;
  margin: 0;
  padding: 0;
  background-color: #f4f4f9;
  color: #333;
  transition: background 0.3s, color 0.3s;
}

header {
  text-align: center;
  padding: 50px 20px;
  background-color: #2e86de;
  color: white;
}

.highlight {
  color: #ffe66d;
}

section {
  padding: 40px 20px;
  max-width: 800px;
  margin: auto;
}

.project-list {
  display: flex;
  flex-wrap: wrap;
  gap: 20px;
}

.project-card {
  background: white;
  padding: 20px;
  flex: 1 1 45%;
  box-shadow: 0 2px 6px rgba(0,0,0,0.1);
  border-radius: 10px;
}

/* Responsive Design */
@media (max-width: 600px) {
  .project-list {
    flex-direction: column;
  }
}

.dark-mode {
  background-color: #121212;
  color: #eee;
}


---

⚙️ 3. JavaScript — script.js

Add a Dark Mode Toggle feature.

const toggle = document.getElementById("theme-toggle");
toggle.addEventListener("click", () => {
  document.body.classList.toggle("dark-mode");
});




Combining HTML, CSS, and JS into one project

Responsive layout using media queries

Adding interactivity (Dark Mode)
