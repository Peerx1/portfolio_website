<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>John Eseneh Portfolio</title>
  <style>
    /* Set background image */
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      color: #333;
      background-image: url('port.jpeg'); /* Replace 'your-image.jpg' with your image path */
      background-size: 60%; /* Cover the entire screen */
      background-position: center; /* Center the image */
      background-attachment: fixed; /* Make the background fixed when scrolling */
    }

    /* Header Styling */
    header {
      background-color: rgba(76, 175, 80, 0.7); /* Semi-transparent green background */
      color: white;
      padding: 1rem;
      text-align: center;
    }

    /* Navigation Bar Styling */
    nav {
      background-color: #333;
      padding: 10px;
    }

    nav a {
      color: white;
      margin: 0 15px;
      text-decoration: none;
      font-weight: bold;
    }

    nav a:hover {
      color: #ff66b2;
    }

    /* Section Styling */
    section {
      padding: 40px 20px;
      max-width: 800px;
      margin: 0 auto;
      background-color: rgba(255, 255, 255, 0.8); /* White background with slight transparency */
      border-radius: 10px;
    }

    h2 {
      text-align: center;
      margin-bottom: 20px;
    }

    /* Footer Styling */
    footer {
      background-color: #4CAF50;
      color: white;
      text-align: center;
      padding: 1rem;
      margin-top: 40px;
    }

    /* Contact Form Styling */
    form {
      display: flex;
      flex-direction: column;
      gap: 10px;
    }

    input, textarea {
      padding: 10px;
      border: 1px solid #ccc;
      border-radius: 5px;
      font-size: 1rem;
    }

    button[type="submit"] {
      background-color: #4CAF50;
      color: white;
      padding: 10px;
      border: none;
      border-radius: 5px;
      font-weight: bold;
      cursor: pointer;
    }

    button[type="submit"]:hover {
      background-color: #388E3C;
    }
  </style>
</head>
<body>

  <!-- Navigation -->
  <nav>
    <a href="#home">Home</a>
    <a href="#about">About</a>
    <a href="#projects">Projects</a>
    <a href="#contact">Contact</a>
  </nav>

  <!-- Header -->
  <header>
    <h1>John Eseneh Portfolio</h1>
  </header>

  <!-- About Section -->
  <section id="about">
    <h2>About Me</h2>
    <p>
      Hi! I'm John Eseneh, a passionate web developer and software engineer.
      I specialize in creating user-friendly websites and applications. 
      My goal is to create clean, efficient, and accessible solutions to meet client needs.
    </p>
  </section>

  <!-- Projects Section -->
  <section id="projects">
    <h2>My Projects</h2>
    <p>
      I have worked on a variety of web-based projects. Here are a few of the notable ones:
      <ul>
        <li><a href="https://johns-webscraper.com" target="_blank"><strong>Web Scraper</strong></a>: A Python-based scraper that extracts data from websites.</li>
        <li><a href="https://johns-website.com" target="_blank"><strong>Responsive Website</strong></a>: Created several responsive, mobile-first websites using HTML, CSS, and JavaScript.</li>
      </ul>
    </p>
  </section>

  <!-- Contact Section -->
  <section id="contact">
    <h2>Contact Me</h2>
    <form action="https://formspree.io/f/xoveravp" method="POST">
      <input type="text" name="name" placeholder="Your Name" required />
      <input type="email" name="email" placeholder="Your Email" required />
      <textarea name="message" rows="5" placeholder="Your Message"></textarea>
      <button type="submit">Send Message</button>
    </form>
  </section>

  <!-- Footer -->
  <footer>
    &copy; 2025 John Eseneh. All rights reserved.
  </footer>

</body>
</html>
