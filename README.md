# KASANA-PORTFOLIO5
<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>KASANA BRENDA DAPHINE— PORTFOLIO</title>
  <link rel="stylesheet" href="css/styles.css">
</head>
<body>
  <header class="site-header">
    <div class="container">
      <h1 class="logo">KASANA BRENDA DAPHINE </h1>
      <nav class="main-nav">
        <a href="#home">Home</a>
        <a href="#about">About</a>
        <a href="#projects">Projects</a>
        <a href="#contact">Contact</a>
      </nav>
    </div>
  </header>

  <main>
    <section id="home" class="hero container">
      <img class="profile" src="       " alt="cal.jpg">
      <div class="intro">
        <h2>Geetings to you all,  I'm Kasana Brenda Daphine </h2>
        <p class="lead">BSIT - Cybersecurity Specialist. I work to protect web and mobile applications from secuity threat and vulnarabilities.</p>
      </div>
    </section>

    <section id="about" class="container">
      <h2>About</h2>
      <p>I am studying BSIT — Web and Mobile Application Development. I enjoy front-end development, building small apps, and learning version control with Git and GitHub.</p>
      <ul>
        <li><strong>Degree:</strong> BSIT - Web and Mobile Application Development</li>
        <li><strong>Interests:</strong> Web dev, mobile apps,databases</li>
      </ul>
    </section>

    <section id="projects" class="container">
      <h2>Projects</h2>
      <div class="projects-grid">
        <article class="project">
          <h3>Project One</h3>
          <p>Small web app built for coursework. Features: CRUD, responsive UI.</p>
          <p><a href="#">View code on GitHub</a></p>
        </article>

        <article class="project">
          <h3>Project Two</h3>
          <p>Another project demonstrating JavaScript and APIs.</p>
          <p><a href="#">View code on GitHub</a></p>
        </article>
      </div>
    </section>

    <section id="contact" class="container">
      <h2>Contact</h2>
      <p>Email: <a href="mailto:youremail@example.com">kasanadaphine@gmail.com</a></p>
      <p>GitHub: <a href="https://github.com/yourusername" target="_blank" rel="noreferrer">Daphine Kasana</a></p>
      <p>LinkedIn: <a href="https://www.linkedin.com/in/yourprofile" target="_blank" rel="noreferrer">cal.jpg</a></p>
    </section>
  </main>

  <footer class="site-footer">
    <div class="container">
      <small>&copy; <span id="year"></span> Kasana Brenda Daphine</small>
    </div>
  </footer>

  <script src="js/script.js"></script>
</body>
</html>

/* Basic, minimal styles for the portfolio */
:root{
  --accent:#d8e51e;
  --text:#218e26;
  --muted:#1698bc;
  --max-width:1000px;
}
*{box-sizing:border-box}
body{font-family:Segoe UI, Roboto, Arial, sans-serif;color:var(--text);margin:0;line-height:1.5}
.container{max-width:var(--max-width);margin:0 auto;padding:20px}
.site-header{background:#c82148;border-bottom:1px solid #6e1453}
.site-header .container{display:flex;align-items:center;justify-content:space-between}
.logo{margin:0;font-size:1.25rem}
.main-nav a{margin-left:12px;color:var(--muted);text-decoration:none}
.hero{display:flex;gap:20px;align-items:center;padding:40px 20px}
.profile{width:120px;height:120px;border-radius:8px;border:2px solid #16a099}
.lead{color:var(--muted)}
.projects-grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(220px,1fr));gap:12px}
.project{padding:12px;border:1px solid #6993355e;border-radius:6px;background:#ad1c4346}
.site-footer{border-top:1px solid #234ca49a;padding:12px;text-align:center;color:var(--muted)}
@media(max-width:600px){
  .hero{flex-direction:column;text-align:center}
  .main-nav{display:none}
}
