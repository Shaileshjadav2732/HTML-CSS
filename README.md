# HTML-CSS
<!DOCTYPE html>
<html>
<head>
  <title>Shailesh's Website</title>
  <style>
    /* CSS Styling */
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
    }

    header {
      background-color: #232F3E;
      color: #FFF;
      padding: 10px;
      text-align: center;
    }

    nav ul {
      list-style: none;
      padding: 0;
      margin: 0;
    }

    nav ul li {
      display: inline;
    }

    nav ul li a {
      color: #FFF;
      text-decoration: none;
      padding: 10px;
    }

    main {
      padding: 20px;
    }

    footer {
      background-color: #232F3E;
      color: #FFF;
      padding: 10px;
      text-align: center;
    }
  </style>
</head>
<body>
  <header>
    <img src="logo.png" alt="Logo">
    <h1>Shailesh</h1>
    <nav>
      <ul>
        <li><a href="#about">About</a></li>
        <li><a href="#skills">Skills</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
  </header>

  <main>
    <section id="about">
      <h2>About Me</h2>
      <p>I am Shailesh, a web developer with a Bachelor's degree in Information Technology.</p>
    </section>

    <section id="skills">
      <h2>Skills</h2>
      <ul>
        <li>C</li>
        <li>Java</li>
        <li>Android Development</li>
        <li>Python</li>
      </ul>
    </section>

    <section id="contact">
      <h2>Contact Me</h2>
      <p>Email: jshailesh798@gmail.com</p>
      <p>Phone: 7990749717</p>
      <p>Instagram: <a href="https://www.instagram.com/your_username">your_username</a></p>
      <p>LinkedIn: <a href="https://www.linkedin.com/in/your_profile">your_profile</a></p>
    </section>
  </main>

  <footer>
    <p>&copy; 2023 Shailesh. All rights reserved.</p>
  </footer>
</body>
</html>
