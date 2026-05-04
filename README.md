<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Portfolio</title>

<style>
body {
  margin: 0;
  font-family: 'Poppins', sans-serif;
  background: #0f172a;
  color: white;
  scroll-behavior: smooth;
}

header {
  text-align: center;
  padding: 50px;
  background: #020617;
}

nav {
  text-align: center;
  background: #1e293b;
  padding: 10px;
}

nav a {
  color: white;
  margin: 15px;
  text-decoration: none;
  font-weight: bold;
}

section {
  padding: 60px 20px;
  text-align: center;
}

h2 {
  color: #38bdf8;
}

.card {
  background: #1e293b;
  padding: 20px;
  margin: 15px auto;
  max-width: 300px;
  border-radius: 10px;
  transition: 0.3s;
}

.card:hover {
  transform: scale(1.05);
}

input, textarea {
  width: 80%;
  padding: 10px;
  margin: 10px;
  border: none;
  border-radius: 5px;
}

button {
  padding: 10px 20px;
  background: #38bdf8;
  border: none;
  cursor: pointer;
}

footer {
  background: #020617;
  text-align: center;
  padding: 20px;
}
</style>

</head>
<body>

<header>
  <h1>Abhishek Kachhwah</h1>
  <p>Frontend Developer 🚀</p>
</header>

<nav>
  <a href="#about">About</a>
  <a href="#skills">Skills</a>
  <a href="#projects">Projects</a>
  <a href="#contact">Contact</a>
</nav>

<section id="about">
  <h2>About Me</h2>
  <p>BCA student passionate about web development and modern UI design.</p>
</section>

<section id="skills">
  <h2>Skills</h2>
  <div class="card">HTML</div>
  <div class="card">CSS</div>
  <div class="card">JavaScript</div>
  <div class="card">React</div>
</section>

<section id="projects">
  <h2>Projects</h2>
  <div class="card">
    <h3>Portfolio Website</h3>
    <p>Modern portfolio using HTML, CSS, JS</p>
  </div>
</section>

<section id="contact">
  <h2>Contact Me</h2>
  <input type="text" placeholder="Your Name"><br>
  <input type="email" placeholder="Your Email"><br>
  <textarea placeholder="Message"></textarea><br>
  <button onclick="sendMessage()">Send</button>
</section>

<footer>
  <p>© 2026 Abhishek</p>
</footer>

<script>
function sendMessage() {
  alert("Message Sent Successfully!");
}
</script>

</body>
</html>