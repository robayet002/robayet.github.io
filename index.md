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
        <!-- (projects as before) -->
      </div>
    </section>

    <section id="publications">
      <h2>Publications</h2>
      <div class="card">
        <h3>A Secured Blockchain Based Integrated Framework for National Identity and Passport</h3>
        <p><em>BAIUST Academic Journal &middot; 2021</em></p>
        <p><strong>Abstract:</strong> This system will help simplify the process of validating and issuing National Identity (NID) cards and passports along with preventing unauthorized issuance. ([journal.baiust.ac.bd](https://journal.baiust.ac.bd/wp-content/uploads/2022/08/2.pdf?utm_source=chatgpt.com))</p>
        <p><a href="https://journal.baiust.ac.bd/wp-content/uploads/2022/08/2.pdf" target="_blank">Read paper</a></p>
      </div>
      <div class="card">
        <h3>Facilitating Hard-to-Defeat Car AI Using Flood-Fill Algorithm</h3>
        <p><em>IJCCI Springer &middot; 2020</em></p>
        <p><strong>Abstract:</strong> The most vital element in making a non-playable car AI in racing games is finding the shortest path between two locations (the start and the finish lines) by making an efficient algorithm for the car to follow it. Usually, both the lines are predetermined for each race in most of the popular games. However, there has not been any game where the player gets the option to select those. ([scispace.com](https://scispace.com/papers/facilitating-hard-to-defeat-car-ai-using-flood-fill-5aeujufd4x?utm_source=chatgpt.com))</p>
        <p><a href="https://link.springer.com/chapter/10.1007/978-981-15-3607-6_43" target="_blank">Read chapter</a></p>
      </div>
      <div class="card">
        <h3>Implementation of Private Blockchain in Smart Card Management System</h3>
        <p><em>BAIUST Academic Journal &middot; 2020</em></p>
        <p><strong>Abstract:</strong> Nowadays Blockchain technology is adopted for various services by a good number of global companies. Blockchain technology ensures integrity of ledgers, privacy of transaction and authenticity of transactions without a centralized control actor. In this paper, we are focused on using this technology in citizen identification system of Bangladesh. A Certification Authority ensures that the information which is not genuine and tempered is not added in our proposed decentralized network. ([journal.baiust.ac.bd](https://journal.baiust.ac.bd/implementation-of-private-blockchain-in-smart-card-management-system/?utm_source=chatgpt.com))</p>
        <p><a href="https://journal.baiust.ac.bd/implementation-of-private-blockchain-in-smart-card-management-system/" target="_blank">Read paper</a></p>
      </div>
    </section>

    <section id="skills">
      <h2>Skills & Certificates</h2>
      <div class="card">
        <h4>Technical Skills</h4>
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
