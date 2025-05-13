<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Faisal Ahamed - Portfolio</title>
  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
      margin: 0;
      background: #f4f4f4;
      color: #333;
    }
    header {
      background-color: #003366;
      color: white;
      padding: 20px;
      display: flex;
      align-items: center;
      justify-content: space-between;
      flex-wrap: wrap;
    }
    .header-left {
      display: flex;
      align-items: center;
      gap: 20px;
    }
    .header-left img {
      width: 80px;
      height: 80px;
      border-radius: 50%;
      object-fit: cover;
      border: 2px solid #fff;
    }
    .header-left h1 {
      margin: 0;
      font-size: 1.8em;
    }
    .buttons {
      display: flex;
      gap: 10px;
      flex-wrap: wrap;
    }
    .buttons a {
      color: white;
      text-decoration: none;
      background-color: #4a8fe7;
      padding: 10px 15px;
      border-radius: 5px;
    }
    .container {
      max-width: 1000px;
      margin: 30px auto;
      padding: 20px;
      background: white;
      border-radius: 8px;
    }
    h2 {
      margin-top: 0;
      color: #003366;
    }
    .timeline {
      display: flex;
      flex-direction: column;
      gap: 30px;
    }
    .experience-card {
      border-left: 4px solid #4a8fe7;
      padding-left: 15px;
    }
    .company-header {
      display: flex;
      justify-content: space-between;
      align-items: baseline;
    }
    .job-title {
      font-weight: bold;
      font-size: 1.1em;
    }
    .company-name {
      color: #555;
    }
    .job-location {
      font-size: 0.9em;
      color: #777;
    }
    .job-highlights {
      margin-top: 10px;
      padding-left: 20px;
    }
    .skills-tags {
      margin-top: 10px;
    }
    .skill-tag {
      background-color: #e0f0ff;
      padding: 5px 10px;
      border-radius: 5px;
      margin-right: 5px;
      display: inline-block;
      margin-top: 5px;
    }
    .portfolio-section {
      margin-top: 40px;
    }
    .portfolio-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 20px;
    }
    .portfolio-item {
      border: 1px solid #ccc;
      border-radius: 5px;
      overflow: hidden;
      background-color: #fff;
    }
    .portfolio-item img {
      width: 100%;
      height: auto;
      display: block;
    }
    .portfolio-item p {
      margin: 0;
      padding: 10px;
      font-size: 0.9em;
      color: #333;
    }
  </style>
</head>
<body>

  <header>
    <div class="header-left">
      <img src="assets/Selfimage.png" alt="Faisal Ahamed">
      <h1>Faisal Ahamed</h1>
    </div>
    <div class="buttons">
      <a href="assets/Resume.pdf" download>📄 Resume</a>
      <a href="assets/Resume_Cert.pdf" download>📎 Certificates</a>
    </div>
  </header>

  <div class="container">
    <h2>Work Experience</h2>
    <div class="timeline">

      <div class="experience-card">
        <div class="company-header">
          <div>
            <div class="job-title">Senior Staff Test/Product Development Engineer</div>
            <div class="company-name">Independent / Career Break</div>
          </div>
          <div class="job-duration">Apr 2024 - Present</div>
        </div>
        <div class="job-location">Kuala Lumpur, Malaysia · On-site</div>
        <ul class="job-highlights">
          <li>Open to full-time or contract roles where I can apply my deep industry knowledge</li>
          <li>Seeking positions to contribute to innovation and lead test development or product engineering initiatives</li>
        </ul>
      </div>

      <div class="experience-card">
        <div class="company-header">
          <div>
            <div class="job-title">Engineering Manager / Senior Principal Test Development Engineer</div>
            <div class="company-name">NXP Semiconductors</div>
          </div>
          <div class="job-duration">Mar 2016 - Mar 2024</div>
        </div>
        <div class="job-location">Kuala Lumpur, Malaysia · On-site</div>
        <ul class="job-highlights">
          <li>Led test development for 30+ new RF/mixed-signal products</li>
          <li>Directed ATE test strategies for Advantest V93K and Teradyne</li>
          <li>Reduced test cost by 20–30% via optimization</li>
          <li>Yield improvement of 5% through cross-functional FA</li>
          <li>Managed global NPI transfers and mentoring teams</li>
        </ul>
        <div class="skills-tags">
          <span class="skill-tag">ATE Test Development</span>
          <span class="skill-tag">RF Testing</span>
          <span class="skill-tag">Six Sigma Black Belt</span>
          <span class="skill-tag">Yield Improvement</span>
        </div>
      </div>

      <div class="experience-card">
        <div class="company-header">
          <div>
            <div class="job-title">Staff Product Engineer</div>
            <div class="company-name">Freescale Semiconductor</div>
          </div>
          <div class="job-duration">Jun 2004 - Jun 2016</div>
        </div>
        <div class="job-location">Petaling Jaya, Malaysia · On-site</div>
        <ul class="job-highlights">
          <li>Achieved 20% test time reduction through optimization</li>
          <li>Completed 25+ product qualifications</li>
          <li>Designed load board with 99.5% first-pass success</li>
          <li>Improved yield by 18% and created SOPs</li>
        </ul>
        <div class="skills-tags">
          <span class="skill-tag">Product Engineering</span>
          <span class="skill-tag">Failure Analysis</span>
          <span class="skill-tag">Test Optimization</span>
        </div>
      </div>

      <div class="experience-card">
        <div class="company-header">
          <div>
            <div class="job-title">Senior Test Development Engineer</div>
            <div class="company-name">Motorola Semiconductor</div>
          </div>
          <div class="job-duration">Feb 2000 - Jun 2004</div>
        </div>
        <div class="job-location">Petaling Jaya, Malaysia · On-site</div>
        <ul class="job-highlights">
          <li>Developed production test solutions for 10+ analog/RF products</li>
          <li>Reduced ATE cost by 12% and improved yield by 22%</li>
          <li>Contributed to ISO audits and accelerated NPI launches</li>
        </ul>
        <div class="skills-tags">
          <span class="skill-tag">Analog Testing</span>
          <span class="skill-tag">ATE Hardware</span>
          <span class="skill-tag">ISO Compliance</span>
        </div>
      </div>

    </div>

    <div class="portfolio-section">
      <h2>Portfolio Projects</h2>
      <div class="portfolio-grid">
        <div class="portfolio-item">
          <img src="assets/project1.jpg" alt="Project 1">
          <p>RF Test Development for NXP Semiconductors</p>
        </div>
        <div class="portfolio-item">
          <img src="assets/project2.jpg" alt="Project 2">
          <p>Load Board Design at Freescale Semiconductor</p>
        </div>
        <div class="portfolio-item">
          <img src="assets/project3.jpg" alt="Project 3">
          <p>Analog Testing Solutions at Motorola Semiconductor</p>
        </div>
        <div class="portfolio-item">
          <img src="assets/project4.jpg" alt="Project 4">
          <p>Yield Improvement Initiatives</p>
        </div>
      </div>
    </div>

    <div class="portfolio-section">
      <h2>Certifications & Awards</h2>
      <div class="portfolio-grid">
        <div class="portfolio-item">
          <img src="assets/cert1.jpg" alt="Certification 1">
          <p>Six Sigma Black Belt Certification</p>
        </div>
        <div class="portfolio-item">
          <img src="assets/cert2.jpg" alt="Certification 2">
          <p>RF Testing Excellence Award</p>
        </div>
        <div class="portfolio-item">
          <img src="assets/cert3.jpg" alt="
::contentReference[oaicite:0]{index=0}
 
