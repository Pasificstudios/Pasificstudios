index.html
style.css
script.js
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Pacific Studio - Gaming Community</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <!-- Header Section -->
  <header>
    <h1>Pacific Studio</h1>
    <p>Your ultimate gaming community</p>
    <nav>
      <a href="#about">About</a>
      <a href="#features">Features</a>
      <a href="#community">Join Us</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <!-- Welcome Section -->
  <section id="welcome">
    <h2>Welcome to Pacific Studio</h2>
    <p>Discover a world where gamers unite, play, and thrive together.</p>
    <button onclick="learnMore()">Learn More</button>
  </section>

  <!-- About Section -->
  <section id="about">
    <h2>About Us</h2>
    <p>Pacific Studio is a community of passionate gamers from all around the world. We bring together people who love games, from casual players to hardcore enthusiasts.</p>
  </section>

  <!-- Features Section -->
  <section id="features">
    <h2>Our Features</h2>
    <ul>
      <li>🎮 Weekly game tournaments</li>
      <li>💬 24/7 live chat & support</li>
      <li>📈 Leaderboards and rankings</li>
      <li>🎁 Exclusive member rewards</li>
    </ul>
  </section>

  <!-- Community Section -->
  <section id="community">
    <h2>Join the Community</h2>
    <p>Connect with us on social media and become part of our family.</p>
    <div class="social-icons">
      <a href="https://discord.com" target="_blank">Discord</a>
      <a href="https://twitter.com" target="_blank">Twitter</a>
      <a href="https://youtube.com" target="_blank">YouTube</a>
    </div>
  </section>

  <!-- Contact Section -->
  <section id="contact">
    <h2>Contact Us</h2>
    <p>Email: contact@pacificstudio.com</p>
    <p>Phone: +123 456 7890</p>
  </section>

  <script src="script.js"></script>
</body>
</html>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: Arial, sans-serif;
  color: #333;
  background-color: #f4f4f4;
}

header {
  background-color: #2b2d42;
  color: #edf2f4;
  padding: 20px;
  text-align: center;
}

header nav a {
  color: #edf2f4;
  margin: 0 10px;
  text-decoration: none;
}

header nav a:hover {
  text-decoration: underline;
}

section {
  padding: 40px;
  max-width: 800px;
  margin: auto;
}

#welcome {
  background: url('https://example.com/background.jpg') no-repeat center center/cover;
  color: #fff;
  text-align: center;
  padding: 60px 20px;
}

#welcome button {
  background-color: #ef233c;
  color: #fff;
  border: none;
  padding: 10px 20px;
  cursor: pointer;
}

#welcome button:hover {
  background-color: #d90429;
}

#features ul {
  list-style: none;
}

#features li {
  padding: 10px 0;
  font-size: 1.2em;
}

.social-icons a {
  text-decoration: none;
  margin: 0 10px;
  color: #2b2d42;
  font-weight: bold;
}

.social-icons a:hover {
  color: #ef233c;
}

footer {
  background-color: #2b2d42;
  color: #edf2f4;
  padding: 10px;
  text-align: center;
}
function learnMore() {
  alert("Thanks for your interest in Pacific Studio! Explore the sections to learn more about us.");
}

