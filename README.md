<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Kyle's Personal Website</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background: #f4f4f4;
      color: #333;
    }
    header {
      background: #333;
      color: #fff;
      padding: 20px 0;
      text-align: center;
    }
    nav a {
      margin: 0 15px;
      color: #fff;
      text-decoration: none;
    }
    section {
      padding: 40px;
      max-width: 800px;
      margin: auto;
    }
    footer {
      background: #333;
      color: #fff;
      text-align: center;
      padding: 20px 0;
    }
    .profile-pic {
      width: 150px;
      border-radius: 50%;
      display: block;
      margin: 20px auto;
    }
    .portfolio-grid {
      display: flex;
      flex-wrap: wrap;
      gap: 20px;
    }
    .portfolio-item {
      flex: 1 1 calc(33% - 20px);
      background: #fff;
      padding: 10px;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
    }
    .portfolio-item img {
      width: 100%;
      height: auto;
    }
    @media (max-width: 600px) {
      .portfolio-item {
        flex: 1 1 100%;
      }
    }
  </style>
</head>
<body>

  <header>
    <h1>Kyle</h1>
    <nav>
      <a href="#about">About</a>
      <a href="#portfolio">Portfolio</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <section id="about">
    <h2>About Me</h2>
    <img src="your-profile-photo.jpg" alt="Kyle's Profile Photo" class="profile-pic">
    <p>Hi! I'm Kyle. I'm passionate about [your interests here]. Welcome to my personal corner of the internet!</p>
  </section>

  <section id="portfolio">
    <h2>Portfolio</h2>
    <div class="portfolio-grid">
      <div class="portfolio-item">
        <img src="project1-thumbnail.jpg" alt="Project 1">
        <p>Project 1 - <a href="#">View</a></p>
      </div>
      <div class="portfolio-item">
        <img src="project2-thumbnail.jpg" alt="Project 2">
        <p>Project 2 - <a href="#">View</a></p>
      </div>
      <div class="portfolio-item">
        <img src="project3-thumbnail.jpg" alt="Project 3">
        <p>Project 3 - <a href="#">View</a></p>
      </div>
    </div>
  </section>

  <section id="contact">
    <h2>Contact</h2>
    <p>You can reach me at: <a href="mailto:your.email@example.com">your.email@example.com</a></p>
  </section>

  <footer>
    <p>&copy; 2025 Kyle. All rights reserved.</p>
  </footer>

</body>
</html>
