# Codealpha_project_portfolio
html

Copy code

<!DOCTYPE html>

<html lang="en">

<head>

  <meta charset="UTF-8">

  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <title>My Portfolio</title>

  <style>

    /* Basic Reset */

    * {

      margin: 0;

      padding: 0;

      box-sizing: border-box;

      font-family: Arial, sans-serif;

    }

    body {

      background-color: #f3f4f6;

      color: #333;

    }



    /* Navigation */

    nav {

      width: 100%;

      background-color: #333;

      padding: 15px;

    }

    nav ul {

      display: flex;

      justify-content: center;

      list-style-type: none;

    }

    nav ul li {

      margin: 0 15px;

    }

    nav ul li a {

      color: #fff;

      text-decoration: none;

      font-weight: bold;

    }

    nav ul li a:hover {

      color: #ff6347;

    }



    /* Header */

    header {

      text-align: center;

      padding: 50px 20px;

      background-color: #444;

      color: #fff;

    }

    header h1 {

      font-size: 36px;

      margin-bottom: 10px;

    }

    header p {

      font-size: 18px;

      max-width: 600px;

      margin: auto;

    }



    /* Section Styling */

    section {

      padding: 40px 20px;

      max-width: 800px;

      margin: auto;

    }

    h2 {

      font-size: 28px;

      color: #444;

      margin-bottom: 20px;

      text-align: center;

    }

    .skills, .experience, .projects {

      margin-top: 20px;

      text-align: center;

    }

    .skill-item, .experience-item, .project-item {

      background-color: #fff;

      padding: 20px;

      margin: 10px;

      border-radius: 8px;

      box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);

    }

    .skills-list, .experience-list, .projects-list {

      display: flex;

      flex-wrap: wrap;

      justify-content: center;

    }

    .skill-item, .experience-item, .project-item {

      width: 100%;

    }

    .project-item {

      text-align: left;

    }



    /* Contact Section */

    .contact-form {

      display: flex;

      flex-direction: column;

      gap: 10px;

      max-width: 400px;

      margin: auto;

    }

    .contact-form input, .contact-form textarea {

      padding: 10px;

      border: 1px solid #ccc;

      border-radius: 4px;

      width: 100%;

    }

    .contact-form button {

      padding: 10px;

      border: none;

      border-radius: 4px;

      background-color: #333;

      color: white;

      cursor: pointer;

      font-size: 16px;

    }

    .contact-form button:hover {

      background-color: #555;

    }



    /* Footer */

    footer {

      text-align: center;

      padding: 20px;

      background-color: #333;

      color: #fff;

    }

  </style>

</head>

<body>



<!-- Navigation -->

<nav>

  <ul>

    <li><a href="#about">About</a></li>

    <li><a href="#skills">Skills</a></li>

    <li><a href="#experience">Experience</a></li>

    <li><a href="#projects">Projects</a></li>

    <li><a href="#contact">Contact</a></li>

  </ul>

</nav>



<!-- Header Section -->

<header>

  <h1>My Portfolio</h1>

  <p>Hi! I'm [Your Name], a passionate [Your Profession] with experience in [Your Field/Skills]. Welcome to my personal portfolio website.</p>

</header>



<!-- About Section -->

<section id="about">

  <h2>About Me</h2>

  <p>

    I am a [Your Profession] based in [Your Location]. I specialize in [your specialization] and have a passion for developing innovative solutions. My goal is to leverage my skills to contribute to impactful projects and grow as a professional in the field.

  </p>

</section>



<!-- Skills Section -->

<section id="skills">

  <h2>Skills</h2>

  <div class="skills-list">

    <div class="skill-item">HTML</div>

    <div class="skill-item">CSS</div>

    <div class="skill-item">JavaScript</div>

    <div class="skill-item">Python</div>

    <div class="skill-item">React</div>

  </div>

</section>



<!-- Experience Section -->

<section id="experience">

  <h2>Experience</h2>

  <div class="experience-list">

    <div class="experience-item">

      <h3>Job Title - Company Name</h3>

      <p>Duration: January 2020 - Present</p>

      <p>Description of the role, responsibilities, and achievements.</p>

    </div>

    <div class="experience-item">

      <h3>Job Title - Company Name</h3>

      <p>Duration: May 2018 - December 2019</p>

      <p>Description of the role, responsibilities, and achievements.</p>

    </div>

  </div>

</section>



<!-- Projects Section -->

<section id="projects">

  <h2>Projects</h2>

  <div class="projects-list">

    <div class="project-item">

      <h3>Project Title</h3>

      <p>Description of the project and the skills/technologies used.</p>

      <a href="#" target="_blank">View Project</a>

    </div>

    <div class="project-item">

      <h3>Project Title</h3>

      <p>Description of the project and the skills/technologies used.</p>

      <a href="#" target="_blank">View Project</a>

    </div>

  </div>

</section>



<!-- Contact Section -->

<section id="contact">

  <h2>Contact Me</h2>

  <form class="contact-form">

    <input type="text" name="name" placeholder="Your Name" required>

    <input type="email" name="email" placeholder="Your Email" required>

    <textarea name="message" rows="5" placeholder="Your Message" required></textarea>

    <button type="submit">Send Message</button>

  </form>

</section>



<!-- Footer -->

<footer>

  <p>© 2023 [Your Name]. All rights reserved.</p>

</footer>



</body>

</html>

