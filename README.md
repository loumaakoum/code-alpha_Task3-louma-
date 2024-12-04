# code-alpha_Task3-louma-
//index.html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My Portfolio</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <nav>
      <ul>
        <li><a href="#home">Home</a></li>
        <li><a href="#about">About</a></li>
        <li><a href="#skills">Skills</a></li>
        <li><a href="#projects">Projects</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
  </header>

  <section id="home" class="home">
    <h1>Welcome to My Portfolio</h1>
    <p>I am Louma akoum a Front-End Developer</p>
  </section>

  <section id="about" class="about">
    <h2>About Me</h2>
    <p>Hi, I'm louma akoum I specialize in building responsive and user-friendly websites. With a passion for design and development, I love turning ideas into beautiful web experiences.</p>
  </section>

  <section id="skills" class="skills">
    <h2>Skills</h2>
    <ul>
      <li>HTML</li>
      <li>CSS</li>
      <li>JavaScript</li>
      <li>React</li>
      <li>Git</li>
      <li>Responsive Design</li>
    </ul>
  </section>

  <section id="projects" class="projects">
    <h2>Projects</h2>
    <div class="project">
      <h3>Project 1</h3>
      <p>Description of your project.</p>
      <a href="#" target="_blank">View Project</a>
    </div>
    <div class="project">
      <h3>Project 2</h3>
      <p>Description of your project.</p>
      <a href="#" target="_blank">View Project</a>
    </div>
  </section>

  <section id="contact" class="contact">
    <h2>Contact Me</h2>
    <p>If you would like to get in touch, feel free to reach out!</p>
    <form>
      <input type="text" placeholder="Your Name" required>
      <input type="email" placeholder="Your Email" required>
      <textarea placeholder="Your Message" required></textarea>
      <button type="submit">Send</button>
    </form>
  </section>

  <footer>
    <p>&copy; 2024 louma akoum. All rights reserved.</p>
  </footer>

  <script src="script.js"></script>
</body>
</html>

//style.css
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    line-height: 1.6;
    color: #333;
  }
  
  header {
    background: #333;
    color: #fff;
    padding: 1rem 0;
    text-align: center;
  }
  
  header nav ul {
    list-style: none;
    padding: 0;
  }
  
  header nav ul li {
    display: inline;
    margin: 0 15px;
  }
  
  header nav ul li a {
    color: #fff;
    text-decoration: none;
  }
  
  section {
    padding: 2rem;
    text-align: center;
  }
  
  .home {
    background: #f4f4f4;
    padding: 5rem 2rem;
  }
  
  .about, .skills, .projects, .contact {
    background: #fff;
  }
  
  .skills ul {
    list-style: none;
    padding: 0;
  }
  
  .skills ul li {
    display: inline-block;
    margin: 0 10px;
    background: #eee;
    padding: 10px 15px;
    border-radius: 5px;
  }
  
  .projects .project {
    background: #f9f9f9;
    margin: 1rem 0;
    padding: 1rem;
    border: 1px solid #ddd;
  }
  
  .project a {
    color: #3498db;
    text-decoration: none;
  }
  
  footer {
    background: #333;
    color: #fff;
    text-align: center;
    padding: 1rem 0;
    margin-top: 2rem;
  }
  
  form input, form textarea {
    width: 100%;
    padding: 10px;
    margin: 10px 0;
    border: 1px solid #ddd;
    border-radius: 5px;
  }
  
  form button {
    background: #3498db;
    color: #fff;
    padding: 10px 15px;
    border: none;
    border-radius: 5px;
    cursor: pointer;
  }
  
  form button:hover {
    background: #2980b9;
  }

  //script.js
  document.querySelector('form').addEventListener('submit', function(e) {
    e.preventDefault();
    alert('Thank you for your message!');
  });
  
