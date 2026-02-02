# Ex01 Portfolio
## Date: 31-01-2026

## AIM
To create a Portfolio using HTML and CSS.

## ALGORITHM
### STEP 1
Create an HTML file (index.html)

### STEP 2
Create a CSS file (style.css)

### STEP 3
Include a navigation bar with links to different sections.

### STEP 4
Add structured sections for introduction, about, projects, and contact details.

### STEP 5
Define global styles for fonts, colors, and layout.

### STEP 6
Style the header, navigation bar, and sections.

### STEP 7
Use Flexbox or CSS Grid for layout design.

### STEP 8
Add hover effects and transitions for interactivity.

### STEP 9
Add Images and Media.

### STEP 10
Use optimized images for a professional look.

### STEP 11
Open the HTML file in a browser to check layout and functionality.

### STEP 12
Fix styling issues and refine content placement.

### STEP 13
Deploy the Portfolio.

### STEP 14
Upload to GitHub Pages for free hosting.

## PROGRAM
MY.HTML
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Game Developer Portfolio</title>

  <!-- Google Font -->
  <link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@400;600;700&display=swap" rel="stylesheet">

  <!-- CSS Link -->
  <link rel="stylesheet" href="style.css">
</head>
<body>

  <!-- HERO -->
  <header>
    <div class="hero">
      <h1>Hi, I'm <span>SANJAY A</span></h1>
      <p>Web Developer | Web Designer | Fullstack Developer</p>
      <a href="#games" class="btn">View My Projects</a>
    </div>
  </header>

  <!-- ABOUT -->
  <section class="about">
    <h2>About Me</h2>
    <p>
      I'M A STUDENT IN SAVEETHA ENGINEERING COLLEGE & I'm STUDING THE DEGREE OF
      B.E CSE
    </p>
  </section>

  <!-- SKILLS -->
  <section>
    <h2>PROGRAMMING Skills</h2>
    <div class="grid">
      <div class="card">
        <h3>PYTHON</h3>
        <p>DEBUGING & SOLVING THE PROBLEMS</p>
      </div>
      <div class="card">
        <h3>C# / C++</h3>
        <p>CRITICAL PROGRAMMING</p>
      </div>
      <div class="card">
        <h3>Level Design</h3>
        <p>Balanced & immersive maps</p>
      </div>
      <div class="card">
        <h3>UI / HUD</h3>
        <p>Clean website interfaces</p>
      </div>
    </div>
  </section>

  <!-- GAMES -->
  <section id="games">
    <h2>My webs</h2>
    <div class="grid">
      <div class="card">
        <h3>My Portfolio</h3>
        <p>It Is My Best Website I Ever Design</p>
      </div>
      <div class="card">
        <h3>Car Selection</h3>
        <p>World's Best Car Selection Website.</p>
      </div>
      <div class="card">
        <h3>Fullstack</h3>
        <p>We're the Best Fullstack Developer.</p>
      </div>
    </div>
  </section>

  <!-- FOOTER -->
  <footer>
    <p>SANJAY| WEB Portfolio</p>
  </footer>

</body>
</html>
```
STYLE.CSS
```* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: 'italicbold', sans-serif;
}

body {
  background: radial-gradient(circle at top, #0f172a, #020617);
  color: #ff0000;
  line-height: 1.6;
}

/* HERO */
header {
  min-height: 100vh;
  display: flex;
  align-items: center;
  justify-content: center;
  text-align: center;
  padding: 20px;
}

header h1 {
  font-size: 3.2rem;
  text-shadow: 0 0 20px #100501;
}

header span {
  color: #e600ff;
}

header p {
  margin: 20px auto;
  max-width: 600px;
  color: #0047c3;
}

.btn {
  display: inline-block;
  padding: 14px 40px;
  border-radius: 40px;
  background: linear-gradient(135deg, #f5f5f5, #8d0a52);
  color: #020617;
  text-decoration: none;
  font-weight: 700;
  box-shadow: 0 0 25px rgba(56,189,248,0.6);
  transition: transform 0.3s ease;
}

.btn:hover {
  transform: scale(1.08);
}

/* SECTIONS */
section {
  padding: 80px 10%;
}

h2 {
  text-align: center;
  font-size: 2.6rem;
  margin-bottom: 50px;
  color: #38bdf8;
  text-shadow: 0 0 15px rgba(56,189,248,0.6);
}

.about p {
  max-width: 800px;
  margin: auto;
  text-align: center;
  color: #cbd5f5;
}

/* GRID */
.grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
  gap: 30px;
}

.card {
  background: rgba(2,6,23,0.9);
  padding: 30px;
  border-radius: 22px;
  box-shadow: 0 0 40px rgba(0,0,0,0.6);
  transition: transform 0.35s ease, box-shadow 0.35s ease;
}

.card:hover {
  transform: translateY(-12px);
  box-shadow: 0 0 50px rgba(56,189,248,0.6);
}

.card h3 {
  margin-bottom: 15px;
  color: #a5f3fc;
}

/* FOOTER */
footer {
  text-align: center;
  padding: 30px;
  background: #0027d6;
  color: #9ca3af;
}
```
## OUTPUT
<img width="1857" height="1025" alt="image" src="https://github.com/user-attachments/assets/0277f108-49e4-4286-8494-69d27d8771a6" />
<img width="1868" height="1034" alt="Screenshot 2026-02-02 110505" src="https://github.com/user-attachments/assets/8a17d888-719c-4970-bed0-72a0bcfced27" />





## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.
