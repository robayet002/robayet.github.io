<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Mohammad Robaitul Islam Bhuiyan – Portfolio</title>
  <link href="https://fonts.googleapis.com/css?family=Roboto:400,700&display=swap" rel="stylesheet">
  <style>
    /* Reset & Base */
    * { margin: 0; padding: 0; box-sizing: border-box; }
    body { font-family: 'Roboto', sans-serif; background: #f4f4f9; color: #333; line-height: 1.6; }
    a { color: #0066cc; text-decoration: none; }
    a:hover { text-decoration: underline; }

    /* Container */
    .container { max-width: 960px; margin: 2rem auto; padding: 0 1rem; }

    /* Header & Nav */
    header { text-align: center; margin-bottom: 2rem; }
    header h1 { font-size: 2.5rem; margin-bottom: 0.5rem; }
    header .subtitle { font-size: 1.2rem; color: #555; }
    nav { text-align: center; margin-top: 1rem; }
    nav a { margin: 0 0.75rem; font-weight: 700; }

    /* Sections */
    section { margin-bottom: 3rem; }
    section h2 { font-size: 1.8rem; margin-bottom: 1rem; border-bottom: 2px solid #e0e0e0; padding-bottom: 0.5rem; }

    /* Cards & Lists */
    .card { background: #fff; border-radius: 8px; box-shadow: 0 2px 5px rgba(0,0,0,0.1); padding: 1.5rem; margin-bottom: 1.5rem; }

    /* Projects Grid */
    .projects { display: grid; grid-template-columns: repeat(auto-fit, minmax(280px, 1fr)); gap: 1.5rem; }

    /* Certificates Grid */
    .cert-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(200px, 1fr)); gap: 1rem; }
    .cert-card img { width: 100%; border-radius: 4px; box-shadow: 0 1px 3px rgba(0,0,0,0.1); margin-bottom: 0.5rem; }

    /* Skills & Lists */
    .skills { display: grid; grid-template-columns: repeat(auto-fit, minmax(200px, 1fr)); gap: 0.75rem; list-style: none; }
    .skills li { background: #fff; padding: 0.5rem 1rem; border-radius: 4px; box-shadow: 0 1px 3px rgba(0,0,0,0.08); }

    /* Footer */
    footer { text-align: center; font-size: 0.9rem; color: #777; margin-top: 4rem; }
  </style>
</head>
<body>
  <div class="container">

    <header>
      <h1>Mohammad Robaitul Islam Bhuiyan</h1>
      <p class="subtitle">Data Scientist & Lecturer</p>
      <nav>
        <a href="#about">About</a>
        <a href="#experience">Experience</a>
        <a href="#projects">Projects</a>
        <a href="#publications">Publications</a>
        <a href="#certificates">Certificates</a>
        <a href="#skills">Skills</a>
        <a href="#contact">Contact</a>
      </nav>
    </header>

    <section id="about">
      <h2>About Me</h2>
      <div class="card">
        <p>M.Sc. Data Science student at FAU Erlangen-Nürnberg (since Oct 2023). B.Sc. in CSE from CUET (2017). Passionate about machine learning, data analysis, and teaching. Published multiple research articles and guided student projects.</p>
      </div>
    </section>

    <section id="experience">
      <h2>Professional Experience</h2>
      <div class="card">
        <h3>Lecturer</h3>
        <p><em>Bangladesh Army International University of Science and Technology</em> &middot; Nov 2017 – Sep 2023</p>
        <ul>
          <li>Delivered undergraduate courses in Machine Learning, Data Structures, and DBMS.</li>
          <li>Developed lectures, assignments, and exams; supervised 5+ student research projects.</li>
          <li>Published 3 high-impact papers in ML and Data Science.</li>
        </ul>
      </div>
    </section>

    <section id="projects">
      <h2>Selected Projects</h2>
      <div class="projects">
        <!-- Project cards here -->
      </div>
    </section>

    <section id="publications">
      <h2>Publications</h2>
      <!-- Publication cards here -->
    </section>

    <section id="certificates">
      <h2>Certificates</h2>
      <div class="cert-grid">
        <div class="cert-card card">
          <img src="https://drive.google.com/uc?export=view&id=1KC1EIPeWMJfN3F4UBCTVRoUI_jE1bxtJ" alt="Data Analyst with R Certificate">
          <h4>Data Analyst with R</h4>
        </div>
        <div class="cert-card card">
          <img src="https://drive.google.com/uc?export=view&id=1ooDb65c9Xnxg9hIouJeXzBiZWhOZSIu1" alt="Data Science Certificate Program Certificate">
          <h4>Data Science Certificate Program</h4>
        </div>
        <div class="cert-card card">
          <img src="https://drive.google.com/uc?export=view&id=113b3olT0elGvkNeEsLwtYSlczPjuGnq-" alt="Business Analysis via Power BI Certificate">
          <h4>Business Analysis via Power BI</h4>
        </div>
        <div class="cert-card card">
          <img src="https://drive.google.com/uc?export=view&id=1nkWpTYx8q-QAUd10aIOFJ2csNBLlL1kK" alt="Python for Data Science and AI Certificate">
          <h4>Python for Data Science and AI</h4>
        </div>
        <div class="cert-card card">
          <img src="https://drive.google.com/uc?export=view&id=1L-arX47ZbUmJYsX_RS61A5ER9jaNuNO0" alt="Excel Power Tools for Data Analysis Certificate">
          <h4>Excel Power Tools for Data Analysis</h4>
        </div>
      </div>
    </section>

    <section id="skills">
      <h2>Skills</h2>
      <div class="card">
        <ul class="skills">
          <li>Python</li>
          <li>R</li>
          <li>C++</li>
          <li>Anaconda</li>
          <li>CodeBlocks</li>
          <li>Microsoft Visual Studio</li>
          <li>LaTeX</li>
          <li>Office 365</li>
          <li>Power BI</li>
          <li>MS SQL</li>
          <li>MS Access</li>
          <li>Linux</li>
          <li>Windows</li>
        </ul>
      </div>
    </section>

    <section id="contact">
      <h2>Contact</h2>
      <div class="card">
        <p><strong>Address:</strong> 91054 Erlangen, Germany</p>
        <p><strong>Email:</strong> <a href="mailto:robayetcuet11@gmail.com">robayetcuet11@gmail.com</a></p>
        <p><strong>Phone:</strong> <a href="tel:+4917674126760">+49 176 7412 6760</a></p>
        <p><strong>GitHub:</strong> <a href="https://github.com/robayet002" target="_blank">github.com/robayet002</a></p>
        <p><strong>LinkedIn:</strong> <a href="https://linkedin.com/in/robayet" target="_blank">linkedin.com/in/robayet</a></p>
      </div>
    </section>

    <footer>
      &copy; 2025 Mohammad Robaitul Islam Bhuiyan
    </footer>

  </div>
</body>
</html>
