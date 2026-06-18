# Work-Portfolio
/
├── index.html
├── style.css
└── script.js
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Jason Schmidt | Community & Inclusion Portfolio</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>

<header class="hero">
  <div class="hero-content">
    <h1>Jason Schmidt</h1>
    <h2>Building inclusive pathways through sport, employment, and community leadership</h2>
    <p>
      For more than a decade, I’ve worked alongside communities to design and lead inclusive
      programs across sport, education, disability, and employment.
    </p>
  </div>
</header>

<section class="stats">
  <div class="stat">
    <span class="number">10+</span>
    <span class="label">Years contribution</span>
  </div>
  <div class="stat">
    <span class="number">1000s</span>
    <span class="label">People engaged</span>
  </div>
  <div class="stat">
    <span class="number">ACT, TAS, National</span>
    <span class="label">Reach</span>
  </div>
  <div class="stat">
    <span class="number">Founder & Leader</span>
    <span class="label">Roles</span>
  </div>
</section>

<section class="section">
  <h3>Flagship work</h3>

  <div class="card">
    <h4>Hurricanes Inclusion Cup</h4>
    <p>
      Founded and led a season‑long inclusive cricket competition in Tasmania, rebuilding
      sporting pathways for people with disability and laying the foundation for blind cricket programs.
    </p>
  </div>

  <div class="card">
    <h4>Vocational Ventures</h4>
    <p>
      Co‑developed a four‑term, multi‑industry career program supporting senior secondary students
      with disability to build confidence and make informed employment decisions.
    </p>
  </div>
</section>

<section class="section">
  <h3>Ongoing leadership</h3>

  <div class="card highlight">
    <h4>President – Blind Cricket ACT</h4>
    <p>
      Responsible for governance, sustainability, and growth of blind cricket in the ACT,
      ensuring access to structured, competitive sport and representative pathways.
    </p>
  </div>
</section>

<section class="section">
  <h3>Selected community initiatives</h3>

  <div class="grid">
    <div class="card small">
      <h5>ACT Work Experience Project</h5>
      <p>Supported placements for students with high and complex support needs.</p>
    </div>

    <div class="card small">
      <h5>Employment in the Park</h5>
      <p>Inclusive careers expo with 400 attendees and 35 organisations.</p>
    </div>

    <div class="card small">
      <h5>Tradie Training – Tools for Training and Trust</h5>
      <p>Video training series for 6,000+ public housing contractors.</p>
    </div>

    <div class="card small">
      <h5>Accessible Sport & Recreation Expo</h5>
      <p>Co‑delivered event increasing awareness of inclusive sport options.</p>
    </div>

    <div class="card small">
      <h5>Inclusive Sports Alliance & Sports Hub</h5>
      <p>Network of 60+ clubs with an online hub launching in 2025.</p>
    </div>
  </div>
</section>

<footer class="footer">
  <p>
    This site documents past and ongoing community contribution.<br>
    Built and hosted on GitHub Pages.
  </p>
</footer>

<script src="script.js"></script>
</body>
</html>

* {
  box-sizing: border-box;
}

body {
  margin: 0;
  font-family: system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", sans-serif;
  line-height: 1.6;
  color: #1f2933;
  background: #f9fafb;
}

.hero {
  background: linear-gradient(135deg, #0f172a, #1e293b);
  color: white;
  padding: 80px 20px;
}

.hero-content {
  max-width: 900px;
  margin: auto;
}

.hero h1 {
  font-size: 3rem;
  margin-bottom: 10px;
}

.hero h2 {
  font-size: 1.4rem;
  font-weight: 400;
  margin-bottom: 20px;
}

.stats {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(160px, 1fr));
  gap: 20px;
  padding: 40px 20px;
  max-width: 1000px;
  margin: auto;
}

.stat {
  background: white;
  padding: 20px;
  border-radius: 8px;
  text-align: center;
}

.stat .number {
  font-size: 1.5rem;
  font-weight: bold;
}

.section {
  max-width: 1000px;
  margin: 60px auto;
  padding: 0 20px;
}

.section h3 {
  font-size: 1.8rem;
  margin-bottom: 20px;
}

.card {
  background: white;
  padding: 20px;
  border-radius: 8px;
  margin-bottom: 20px;
}

.card.highlight {
  border-left: 5px solid #2563eb;
}

.grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(240px, 1fr));
  gap: 20px;
}

.card.small h5 {
  margin-top: 0;
}

.footer {
  background: #0f172a;
  color: white;
  text-align: centre;
  padding: 30px 20px;
  margin-top: 60px;
}

// Simple future-ready file for animations or interactions
console.log("Portfolio loaded");
