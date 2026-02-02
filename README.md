# Ex01 Portfolio
## Date:

## AIM
To create a Portfolio using HTML and CSS.

## ALGORITHM
### STEP 1
Create an HTML file (index.html)

### STEP 2
Create a CSS file (style.css)

### STEP 3
Include a navigation bar with links to different sections.

### STEP 4
Add structured sections for introduction, about, projects, and contact details.

### STEP 5
Define global styles for fonts, colors, and layout.

### STEP 6
Style the header, navigation bar, and sections.

### STEP 7
Use Flexbox or CSS Grid for layout design.

### STEP 8
Add hover effects and transitions for interactivity.

### STEP 9
Add Images and Media.

### STEP 10
Use optimized images for a professional look.

### STEP 11
Open the HTML file in a browser to check layout and functionality.

### STEP 12
Fix styling issues and refine content placement.

### STEP 13
Deploy the Portfolio.

### STEP 14
Upload to GitHub Pages for free hosting.

## PROGRAM

## HTML
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Subash E</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body data-theme="dark">
  <!-- Navigation -->
  <nav>
    <div class="nav-container">
      <div class="logo">SE</div>

      <!-- Hamburger Menu Button -->
      <button class="hamburger" onclick="toggleMenu()">☰</button>

      <ul class="nav-links">
        <li><a href="#home" class="nav-link ">Home</a></li>
        <li><a href="#about" class="nav-link">About</a></li>
        <li><a href="#projects" class="nav-link">Projects</a></li>
        <li><a href="#resume" class="nav-link">Resume</a></li>
        <li><a href="#contact" class="nav-link">Contact</a></li>
        <li><button class="theme-toggle" onclick="toggleTheme()">🌙</button></li>
      </ul>
    </div>
  </nav>

  <!-- Hero Section -->
  <section id="home" class="hero visible">
    <div class="hero-content">
      <div class="profile-pic">
        <img src="assests/subash.jpg" alt="PIC">
      </div>
      <h1>Subash E</h1>
      <div class="typing-text" id="typing-text">Tech Enthusiast</div>
      <a href="#projects" class="cta-button">View My Work</a>
    </div>
  </section>

  <!-- About Section -->
  <section id="about" class="visible">
    <h2 class="section-title">About Me</h2>
    <div class="about-content">
      <div>
        <p class="about-text">I'm Subash E, a third-year student pursuing Computer Science and Engineering at Saveetha Engineering College. I have a strong passion for solving real-world problems using data, intelligent systems, and user-centered design. My interests lie in Data Science, web development, and UI/UX design, and I enjoy blending these skills to build practical, impactful solutions.</p>
        <p class="about-text">So far, I’ve worked on projects like a Resume Analyzer and Job Matcher using ML and NLP. I also designed and built my own portfolio website from scratch to reflect my learning journey and skill set.</p>
        <p class="about-text">I'm always eager to learn new technologies and improve my craft. Whether it’s designing intuitive user experiences or training models that understand data, I enjoy every part of the development process. I look forward to collaborating on innovative projects and growing as a developer and problem solver.</p>
      </div>
      <div class="skills">
        <div class="skill">HTML</div>
        <div class="skill">CSS</div>
        <div class="skill">JavaScript</div>
        <div class="skill">Canva</div>
        <div class="skill">Python</div>
        <div class="skill">Java</div>
        <div class="skill">C</div>
        <div class="skill">SQL</div>
        <div class="skill">Power BI</div>
        <div class="skill">Front end</div>
      </div>
    </div>
  </section>

  <!-- Projects Section -->
  <section id="projects" class="visible">
    <h2 class="section-title">Featured Projects</h2>

      <div class="project-card">
        <div class="project-image">🖥️</div>
        <div class="project-content">
          <h3 class="project-title">Personal Portfolio Website</h3>
          <p class="project-description">
            A responsive website designed using Figma and built with HTML and CSS to showcase personal projects, skills, and contact details with clean UI and visual hierarchy.
          </p>
          <div class="project-links">
            <a href="#" class="project-link">Live Demo</a>
            <a href="#" class="project-link">GitHub</a>
          </div>
        </div>
      </div>

      <div class="project-card">
        <div class="project-image">🧠</div>
        <div class="project-content">
          <h3 class="project-title">Resume Analyzer & Job Matcher</h3>
          <p class="project-description">
            An ML-powered web app to parse resumes, extract information, and recommend job roles using NLP and job category classification. Features resume upload and ML-based backend processing.
          </p>
          <div class="project-links">
            <a href="#" class="project-link">Live Demo</a>
            <a href="#" class="project-link">GitHub</a>
          </div>
        </div>
      </div>
    </div>

  </section>

  <!-- Resume Section -->
  <section id="resume" class="visible">
    <h2 class="section-title">Resume</h2>
    <div class="resume-content">
      <p class="resume-description">Download my complete resume to learn more about my experience, education, and technical skills.</p>
      <div class="resume-buttons">
        <a href="assests/RESUME OF SUBASH.pdf" class="download-btn" target="_blank">👁️ View Resume</a>
        <a href="assests/RESUME OF SUBASH.pdf" class="download-btn" download>📄 Download Resume</a>
      </div>
    </div>
  </section>

  <!-- Contact Section -->
  <section id="contact" class="visible">
    <h2 class="section-title">Get In Touch</h2>
    <div class="contact-content">

      <div class="contact-item">
        <div class="contact-icon">📧</div>
        <h3 class="contact-title">Email</h3>
        <a href="mailto:subashrakshitha18@gmail.com" class="contact-link">subashrakshitha18@gmail.com</a>
      </div>

      <div class="contact-item">
        <div class="contact-icon">💼</div>
        <h3 class="contact-title">LinkedIn</h3>
        <a href="https://www.linkedin.com/in/subash-elumalai/" target="_blank" class="contact-link">linkedin.com/in/subash-elumalai/</a>
      </div>

      <div class="contact-item">
        <div class="contact-icon">🐱</div>
        <h3 class="contact-title">GitHub</h3>
        <a href="https://github.com/SUBASHVIRAT18" target="_blank" class="contact-link">github.com/SUBASHVIRAT18</a>
      </div>

      <div class="contact-item">
        <div class="contact-icon">✖️</div>
        <h3 class="contact-title">X</h3>
        <a href="https://x.com/Subashwhyrat18" target="_blank" class="contact-link">x.com/Subashwhyrat18</a>
      </div>

    </div>
  </section>


  <!-- Footer -->
  <footer>
    <p>© 2025 Subash E. All rights reserved. Built with passion and lots of coffee ☕</p>
  </footer>

  <script src="script.js"></script>
</body>
</html>


```
## CSS
```
/* === RESET & BASE === */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

:root {
    --primary-color: #63f19c;
    --primary-hover: #086641;
    --bg-color: #0f172a;
    --surface-color: #1d2c44;
    --text-primary: #f8fafc;
    --text-secondary: #cbd5e1;
    --border-color: #334155;
}

[data-theme="light"] {
    --bg-color: #ffffff;
    --surface-color: #f8fafc;
    --text-primary: #0f172a;
    --text-secondary: #475569;
    --border-color: #e2e8f0;
}

body {
    font-family: 'Inter', -apple-system, BlinkMacSystemFont, sans-serif;
    background-color: var(--bg-color);
    color: var(--text-primary);
    line-height: 1.6;
    transition: all 0.3s ease;
}

html {
    scroll-behavior: smooth;
}

/* === NAVIGATION === */
nav {
    position: fixed;
    top: 0;
    width: 100%;
    background: rgba(28, 37, 56, 0.9);
    backdrop-filter: blur(10px);
    z-index: 1000;
    padding: 1rem 0;
    transition: all 0.3s ease;
}

[data-theme="light"] nav {
    background: rgba(255, 255, 255, 0.9);
}

.nav-container {
    max-width: 1200px;
    margin: 0 auto;
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 0 2rem;
}

.logo {
    font-size: 1.5rem;
    font-weight: 700;
    color: var(--primary-color);
}

.nav-links {
    display: flex;
    list-style: none;
    gap: 2rem;
    align-items: center;
}

.nav-links a {
    color: var(--text-primary);
    text-decoration: none;
    transition: color 0.3s ease;
    position: relative;
}

.nav-links a:hover,
.nav-links a.active {
    color: var(--primary-color);
}

.nav-links a.active::after {
    content: '';
    position: absolute;
    bottom: -5px;
    left: 0;
    width: 100%;
    height: 2px;
    background: var(--primary-color);
}

.theme-toggle {
    background: var(--surface-color);
    border: 1px solid var(--border-color);
    color: var(--text-primary);
    padding: 0.5rem;
    border-radius: 0.5rem;
    cursor: pointer;
    transition: all 0.3s ease;
}

.theme-toggle:hover {
    background: var(--primary-color);
}

/* === HERO SECTION === */
.hero {
    width: 100%;
    max-width: 100%;
    padding: 0;
    margin: 0;
    min-height: 100vh;
    display: flex;
    align-items: center;
    justify-content: center;
    text-align: center;
    padding: 2rem;
    background: linear-gradient(135deg, var(--bg-color) 0%, var(--surface-color) 100%);
}

.hero-content {
    max-width: 800px;
    opacity: 0;
    animation: fadeInUp 1s ease 0.5s forwards;
}

.profile-pic img{
    width: 200px;
    height: 200px;
    border-radius: 50%;
    margin: 0 auto 2rem;
    background: linear-gradient(45deg, var(--primary-color), #8b5cf6);
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 4rem;
    opacity: 0;
    animation: fadeInScale 1s ease 0.2s forwards;
}

.hero h1 {
    font-size: 3.5rem;
    font-weight: 700;
    margin-bottom: 1rem;
    background: linear-gradient(45deg, var(--primary-color), #8b5cf6);
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    background-clip: text;
}

.typing-text {
    font-size: 1.5rem;
    color: var(--text-secondary);
    margin-bottom: 2rem;
    min-height: 2rem;
}

.typing-text::after {
    content: '|';
    animation: blink 1s infinite;
}

.cta-button {
    display: inline-block;
    background: var(--primary-color);
    color: white;
    padding: 1rem 2rem;
    border-radius: 0.5rem;
    text-decoration: none;
    font-weight: 600;
    transition: all 0.3s ease;
    transform: translateY(20px);
    opacity: 0;
    animation: fadeInUp 1s ease 1s forwards;
}

.cta-button:hover {
    background: var(--primary-hover);
    transform: translateY(-2px);
    box-shadow: 0 10px 25px rgba(99, 102, 241, 0.3);
}

/* === SECTION STYLES === */
section {
    padding: 5rem 2rem;
    max-width: 1200px;
    margin: 0 auto;
    opacity: 0;
    transform: translateY(50px);
    transition: all 0.8s ease;
}

section.visible {
    opacity: 1;
    transform: translateY(0);
}

.section-title {
    font-size: 2.5rem;
    font-weight: 700;
    text-align: center;
    margin-bottom: 3rem;
    color: var(--text-primary);
}

/* === ABOUT SECTION === */
.about-content {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 4rem;
    align-items: center;
}

.about-text {
    font-size: 1.1rem;
    color: var(--text-secondary);
    margin-bottom: 2rem;
}

.skills {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(120px, 1fr));
    gap: 1rem;
}

.skill {
    background: var(--surface-color);
    padding: 1rem;
    border-radius: 0.5rem;
    text-align: center;
    border: 1px solid var(--border-color);
    transition: all 0.3s ease;
}

.skill:hover {
    transform: translateY(-5px);
    border-color: var(--primary-color);
}

/* === PROJECTS SECTION === */
.projects-grid {
    display: grid;
    grid-template-columns: 1fr; /* default mobile - 1 column */
    gap: 2rem;
}

@media (min-width: 768px) {
    .projects-grid {
        grid-template-columns: repeat(2, 1fr); /* 2 columns for tablets */
    }
}

@media (min-width: 1024px) {
    .projects-grid {
        grid-template-columns: repeat(2, 1fr); /* 3 columns for desktops */
    }
}


.project-card {
    background: var(--surface-color);
    border-radius: 1rem;
    overflow: hidden;
    border: 1px solid var(--border-color);
    transition: all 0.3s ease;
}

.project-card:hover {
    transform: translateY(-10px);
    box-shadow: 0 20px 40px rgba(0, 0, 0, 0.1);
}

.project-image {
    height: 200px;
    background: linear-gradient(45deg, var(--primary-color), #8b5cf6);
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 3rem;
    color: white;
}

.project-content {
    padding: 1.5rem;
}

.project-title {
    font-size: 1.3rem;
    font-weight: 600;
    margin-bottom: 0.5rem;
}

.project-description {
    color: var(--text-secondary);
    margin-bottom: 1rem;
}

.project-links {
    display: flex;
    gap: 1rem;
}

.project-link {
    color: var(--primary-color);
    text-decoration: none;
    font-weight: 500;
    transition: color 0.3s ease;
}

.project-link:hover {
    color: var(--primary-hover);
}

/* === RESUME SECTION === */
.resume-content {
    text-align: center;
}

.resume-buttons {
    display: flex;
    justify-content: center;
    flex-wrap: wrap;         /* Wrap on small screens */
    gap: 1rem;               /* Space between buttons */
    margin-top: 1rem;
}

.resume-description {
    font-size: 1.1rem;
    color: var(--text-secondary);
    margin-bottom: 2rem;
    max-width: 600px;
    margin-left: auto;
    margin-right: auto;
}

.download-btn {
    display: inline-flex;
    align-items: center;
    gap: 0.5rem;
    background: var(--primary-color);
    color: white;
    padding: 1rem 2rem;
    border-radius: 0.5rem;
    text-decoration: none;
    font-weight: 600;
    transition: all 0.3s ease;
}

.download-btn:hover {
    background: var(--primary-hover);
    transform: translateY(-2px);
}

/* === CONTACT SECTION === */
.contact-content {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 2rem;
    text-align: center;
}

.contact-item {
    background: var(--surface-color);
    padding: 2rem;
    border-radius: 1rem;
    border: 1px solid var(--border-color);
    transition: all 0.3s ease;
}

.contact-item:hover {
    transform: translateY(-5px);
    border-color: var(--primary-color);
}

.contact-icon {
    font-size: 2rem;
    margin-bottom: 1rem;
    color: var(--primary-color);
}

.contact-title {
    font-size: 1.2rem;
    font-weight: 600;
    margin-bottom: 0.5rem;
}

.contact-link {
    color: var(--text-secondary);
    text-decoration: none;
    transition: color 0.3s ease;
}

.contact-link:hover {
    color: var(--primary-color);
}

/* === FOOTER === */
footer {
    background: var(--surface-color);
    padding: 2rem;
    text-align: center;
    border-top: 1px solid var(--border-color);
    color: var(--text-secondary);
}

/* === ANIMATIONS === */
@keyframes fadeInUp {
    to {
        opacity: 1;
        transform: translateY(0);
    }
}

@keyframes fadeInScale {
    to {
        opacity: 1;
        transform: scale(1);
    }
}

@keyframes blink {
    0%, 50% { opacity: 1; }
    51%, 100% { opacity: 0; }
}
.hamburger {
  display: none;
  font-size: 1.5rem;
  background: none;
  border: none;
  color: var(--text-primary);
  cursor: pointer;
}

@media (max-width: 768px) {
  .nav-links {
    display: none;
    flex-direction: column;
    gap: 1rem;
    background-color: var(--surface-color);
    position: absolute;
    top: 70px;
    right: 20px;
    padding: 1rem;
    border-radius: 0.5rem;
    z-index: 999;
  }

  .nav-links.show {
    display: flex;
  }

  .hamburger {
    display: block;
  }
}
```


## OUTPUT
<img width="1897" height="944" alt="image" src="https://github.com/user-attachments/assets/d3a409c9-0299-4e70-8e37-e1c0c7d679a1" />
<img width="1782" height="860" alt="image" src="https://github.com/user-attachments/assets/343d9603-8745-4d2f-881f-79c8c3d314c7" />
<img width="1732" height="897" alt="image" src="https://github.com/user-attachments/assets/70365b86-b1a3-455f-8948-d15235c3d347" />
<img width="1914" height="1035" alt="image" src="https://github.com/user-attachments/assets/aa2467cb-bc24-4d38-b0e7-a7c8255dbe5b" />






## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.
