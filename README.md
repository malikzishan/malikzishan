<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Md Zishan | Portfolio</title>
  <style>
    * {
      box-sizing: border-box;
    }
    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      margin: 0;
      background: #f9f9f9;
      color: #333;
      line-height: 1.6;
    }
    a {
      color: #2980b9;
      text-decoration: none;
    }
    a:hover {
      text-decoration: underline;
    }

    /* HEADER & HERO */
    header {
      background: linear-gradient(to right, #1e3c72, #2a5298);
      color: white;
      text-align: center;
      padding-bottom: 20px;
    }
    .hero {
      padding: 60px 20px 40px;
    }
    .hero h1 {
      margin: 0;
      font-size: 3rem;
    }
    .hero p {
      font-size: 1.2rem;
      margin-top: 10px;
      color: #cce7ff;
    }
    .hero .button {
      display: inline-block;
      margin-top: 20px;
      padding: 12px 30px;
      background: #f1c40f;
      color: #000;
      font-weight: bold;
      border-radius: 25px;
      text-decoration: none;
      transition: 0.3s;
    }
    .hero .button:hover {
      background: #d4ac0d;
    }

    .main-nav {
      background-color: #154360;
      padding: 10px 0;
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
      gap: 20px;
    }
    .main-nav a {
      color: white;
      font-weight: bold;
      padding: 8px 12px;
      border-radius: 5px;
      transition: background 0.3s;
    }
    .main-nav a:hover {
      background: rgba(255,255,255,0.2);
    }

    main {
      max-width: 900px;
      margin: 30px auto;
      padding: 0 20px;
    }
    section {
      margin-bottom: 50px;
    }
    h2 {
      border-bottom: 3px solid #2980b9;
      padding-bottom: 8px;
      margin-bottom: 20px;
      color: #205081;
    }

    /* About Section */
    #about img {
      width: 150px;
      border-radius: 50%;
      box-shadow: 0 4px 8px rgba(0,0,0,0.2);
    }

    /* Skill Tags */
    #skills ul {
      display: flex;
      flex-wrap: wrap;
      gap: 10px;
      padding-left: 0;
      list-style: none;
    }
    #skills ul li {
      background: #2980b9;
      color: white;
      padding: 8px 14px;
      border-radius: 20px;
      font-weight: 600;
      box-shadow: 1px 1px 4px rgba(0,0,0,0.1);
    }

    /* Lists */
    .experience-list {
      list-style: none;
      padding-left: 0;
    }
    .experience-list li {
      margin-bottom: 12px;
      background: #e3f2fd;
      padding: 10px 15px;
      border-radius: 6px;
      box-shadow: 1px 1px 4px rgba(41,128,185,0.15);
    }

    /* Testimonials */
    blockquote {
      border-left: 4px solid #2980b9;
      padding-left: 15px;
      margin-bottom: 20px;
      font-style: italic;
      background: #f0f8ff;
      border-radius: 4px;
      box-shadow: 2px 2px 5px rgba(41,128,185,0.1);
    }
    blockquote footer {
      margin-top: 8px;
      font-style: normal;
      color: #205081;
      font-weight: 600;
    }

    /* Contact */
    #contact a.button {
      display: inline-block;
      background: #2980b9;
      color: white;
      padding: 12px 25px;
      border-radius: 30px;
      font-weight: bold;
      margin-top: 15px;
      transition: background-color 0.3s ease;
    }
    #contact a.button:hover {
      background: #1c5f94;
    }

    /* Responsive */
    @media (max-width: 600px) {
      .main-nav {
        flex-direction: column;
        align-items: center;
      }
      #about div {
        flex-direction: column;
        text-align: center;
      }
      #about img {
        margin-bottom: 15px;
      }
    }
  </style>
</head>
<body>

<header>
  <div class="hero">
    <h1>Hi, I'm Md Zishan</h1>
    <p>Frontend Developer | HTML | CSS | JavaScript</p>
    <a href="#contact" class="button">Hire Me</a>
  </div>
  <nav class="main-nav">
    <a href="#about">About</a>
    <a href="#skills">Skills</a>
    <a href="#experience">Experience</a>
    <a href="#portfolio">Portfolio</a>
    <a href="#contact">Contact</a>
    <a href="#testimonials">Testimonials</a>
    <a href="#education">Education</a>
    <a href="#certifications">Certifications</a>
    <a href="#hobbies">Hobbies</a>
  </nav>
</header>

<main>

  <section id="about">
    <h2>About Me</h2>
    <div style="display: flex; flex-wrap: wrap; align-items: center; gap: 20px;">
      <img src="https://i.pravatar.cc/150?img=3" alt="Md Zishan" />
      <p style="flex: 1;">
        I'm Md Zishan, a passionate Frontend Developer skilled in HTML, CSS, and JavaScript. I create responsive and user-friendly web interfaces with a strong focus on clean design and accessibility. Always eager to learn and grow in tech!
      </p>
    </div>
  </section>

  <section id="skills">
    <h2>Skills</h2>
    <ul>
      <li>HTML5</li>
      <li>CSS3</li>
      <li>JavaScript (ES6+)</li>
      <li>Responsive Design</li>
      <li>Git & GitHub</li>
      <li>React Basics</li>
    </ul>
  </section>

  <section id="experience">
    <h2>Experience</h2>
    <ul class="experience-list">
      <li><strong>Frontend Developer</strong> - XYZ Company (2023 - Present)</li>
      <li><strong>Intern Web Developer</strong> - ABC Startup (2022 - 2023)</li>
    </ul>
  </section>

  <section id="portfolio">
    <h2>Portfolio</h2>
    <p>Recent projects:</p>
    <ul>
      <li><a href="https://github.com/mdzishan/project1" target="_blank">Responsive Website</a></li>
      <li><a href="https://github.com/mdzishan/project2" target="_blank">To-Do App</a></li>
      <li><a href="https://github.com/mdzishan/project3" target="_blank">Blog Template</a></li>
    </ul>
  </section>

  <section id="contact">
    <h2>Contact</h2>
    <p>Email: <a href="mailto:mdzishan@example.com">mdzishan@example.com</a></p>
    <p>LinkedIn: <a href="https://linkedin.com/in/mdzishan" target="_blank">linkedin.com/in/mdzishan</a></p>
    <a href="mailto:mdzishan@example.com" class="button">Send me an Email</a>
  </section>

  <section id="testimonials">
    <h2>Testimonials</h2>
    <blockquote>
      "Md Zishan is a talented developer with great attention to detail. He delivered our website ahead of schedule."
      <footer>- Jane Doe, Project Manager at ABC Company</footer>
    </blockquote>
    <blockquote>
      "Very professional and easy to work with. Highly recommend for front-end projects."
      <footer>- John Smith, Client</footer>
    </blockquote>
  </section>

  <section id="education">
    <h2>Education</h2>
    <ul class="experience-list">
      <li><strong>B.Sc. Computer Science</strong>, University of Mumbai (2019 - 2023)</li>
      <li><strong>HSC</strong>, XYZ High School (2017 - 2019)</li>
    </ul>
  </section>

  <section id="certifications">
    <h2>Certifications</h2>
    <ul class="experience-list">
      <li>Responsive Web Design - freeCodeCamp</li>
      <li>JavaScript Data Structures - freeCodeCamp</li>
      <li>Intro to React - Coursera</li>
    </ul>
  </section>

  <section id="hobbies">
    <h2>Hobbies & Interests</h2>
    <ul class="experience-list">
      <li>Reading tech blogs</li>
      <li>Playing cricket and badminton</li>
      <li>Traveling and exploring</li>
      <li>Photography and editing</li>
    </ul>
  </section>

</main>

<footer>
  <p>© 2025 Md Zishan. All rights reserved.</p>
</footer>

</body>
</html>