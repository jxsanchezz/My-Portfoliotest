<!DOCTYPE html>
<html>
<head>
  <title>My Portfolio</title>
  <link rel="stylesheet" type="text/css" href="styles.css">
  <script src="script.js"></script>
</head>
<body>
  <header>
    <h1>Welcome to My Portfolio</h1>
  </header>
  
  <nav>
    <ul>
      <li><a href="#about">About</a></li>
      <li><a href="#projects">Projects</a></li>
      <li><a href="#contact">Contact</a></li>
    </ul>
  </nav>
  
  <main>
    <section id="about">
      <h2>About Me</h2>
      <p>Write a brief introduction about yourself here.</p>
    </section>
    
    <section id="projects">
      <h2>My Projects</h2>
      <ul>
        <li>
          <h3>Project 1</h3>
          <p>Description of project 1.</p>
        </li>
        <li>
          <h3>Project 2</h3>
          <p>Description of project 2.</p>
        </li>
      </ul>
    </section>
    
    <section id="contact">
      <h2>Contact Me</h2>
      <form>
        <label for="name">Name:</label>
        <input type="text" id="name" name="name">
        
        <label for="email">Email:</label>
        <input type="email" id="email" name="email">
        
        <label for="message">Message:</label>
        <textarea id="message" name="message"></textarea>
        
        <input type="submit" value="Send">
      </form>
    </section>
  </main>
  
  <footer>
    <p>&copy; 2023 My Portfolio. All rights reserved.</p>
  </footer>
</body>
</html>
