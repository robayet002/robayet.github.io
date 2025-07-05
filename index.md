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

    /* Projects */
    .projects { display: grid; grid-template-columns: repeat(auto-fit, minmax(280px, 1fr)); gap: 1.5rem; }
    .project a { font-weight: 700; }

    /* Skills Grid */
    .skills { display: grid; grid-template-columns: repeat(2, 1fr); gap: 1rem; }
    .skills li { background: #fff; padding: 0.5rem 1rem; border-radius: 4px; }

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
        <div class="card">
          <h3><a href="https://github.com/robayet002/Predictive-Analytics-for-Hotel-Booking-Patterns" target="_blank">Predictive Analytics for Hotel Booking Patterns</a></h3>
          <p>Data cleaning, visualization, and exploratory analysis using Python.</p>
        </div>
        <div class="card">
          <h3><a href="#">Crime & Arrests Analysis (Los Angeles)</a></h3>
          <p>Data pipeline, preprocessing, and visualization of urban crime patterns in LA.</p>
        </div>
        <div class="card">
          <h3><a href="https://github.com/robayet002/Enhancing-Sales-Strategies-with-Power-BI-A-Visual-Analytics-Approach" target="_blank">Sales Strategies with Power BI</a></h3>
          <p>Interactive dashboard creation using Power BI for enhanced sales insights.</p>
        </div>
        <div class="card">
          <h3><a href="https://github.com/robayet002/Improving-Breast-Cancer-Diagnosis-Accuracy-Using-SVM-and-GridSearch" target="_blank">Breast Cancer Diagnosis with SVM</a></h3>
          <p>Machine learning model tuning with SVM and GridSearch in Python.</p>
        </div>
        <div class="card">
          <h3><a href="https://github.com/robayet002/Credit-Risk-Prediction-using-supervised-machine-learning.git" target="_blank">Credit Risk Prediction</a></h3>
          <p>Logistic Regression & Random Forest classifier implementation in Python.</p>
        </div>
        <div class="card">
          <h3><a href="#">Sales Insights Analysis</a></h3>
          <p>Comprehensive EDA and visualization of sales data using Python.</p>
        </div>
        <div class="card">
          <h3><a href="#">Excel Annual Sales Dashboard</a></h3>
          <p>Interactive Excel dashboard for annual sales reporting.</p>
        </div>
      </div>
    </section>

    <section id="publications">
      <h2>Publications</h2>
      <ul class="card">
        <li><strong>Secured Blockchain Framework for National Identity & Passport</strong> &middot; BAIUST Academic Journal, 2021</li>
        <li><strong>Hard-to-Defeat Car AI Using Flood-Fill Algorithm</strong> &middot; IJCCI Springer, 2020</li>
        <li><strong>Private Blockchain in Smart Card Management</strong> &middot; BAIUST Academic Journal, 2020</li>
      </ul>
    </section>

    <section id="skills">
      <h2>Skills & Certificates</h2>
      <div class="card">
        <h4>Languages & Tools</h4>
        <ul class="skills">
          <li>Python</li>
          <li>R</li>
          <li>C++</li>
          <li>Power BI</li>
          <li>MS SQL</li>
          <li>LaTeX</li>
          <li>Git & GitHub</li>
          <li>Linux & Windows</li>
        </ul>
        <h4>Certificates</h4>
        <ul>
          <li>Data Analyst with R</li>
          <li>Data Science Certificate Program</li>
          <li>Business Analysis via Power BI</li>
          <li>Python for Data Science and AI</li>
          <li>Excel Power Tools for Data Analysis</li>
        </ul>
      </div>
    </section>

    <section id="contact">
      <h2>Contact</h2>
      <div class="card">
        <p>Email: <a href="mailto:robayetcuet11@gmail.com">robayetcuet11@gmail.com</a></p>
        <p>Phone: <a href="tel:+4917674126760">+49 176 7412 6760</a></p>
        <p>GitHub: <a href="https://github.com/robayet002" target="_blank">github.com/robayet002</a></p>
        <p>LinkedIn: <a href="https://linkedin.com/in/robayet" target="_blank">linkedin.com/in/robayet</a></p>
      </div>
    </section>

    <footer>
      &copy; 2025 Mohammad Robaitul Islam Bhuiyan
    </footer>

  </div>
</body>
</html>
