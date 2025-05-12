<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Faisal Ahamed - Senior Principal Test Development Engineer</title>
  <style>
    :root {
      --primary: #003366;
      --secondary: #4a8fe7;
      --accent: #e74c3c;
      --light: rgba(255,255,255,0.9);
      --dark: #2c3e50;
      --sixsigma-green: #009b77;
      --sixsigma-black: #333333;
    }
    
    body {
      font-family: 'Segoe UI', system-ui, sans-serif;
      background: 
        linear-gradient(rgba(245, 245, 245, 0.9), rgba(245, 245, 245, 0.9)),
        url('https://images.unsplash.com/photo-1629904853893-c2c8981a1dc5?ixlib=rb-4.0.3&auto=format&fit=crop&w=1350&q=80') center/cover no-repeat fixed;
      color: var(--dark);
      line-height: 1.6;
      margin: 0;
    }
    
    .container {
      max-width: 1000px;
      margin: 0 auto;
      padding: 20px;
    }
    
    header {
      background: 
        linear-gradient(rgba(0, 51, 102, 0.85), rgba(0, 51, 102, 0.9)),
        url('https://images.unsplash.com/photo-1635070041078-e363dbe005cb?ixlib=rb-4.0.3&auto=format&fit=crop&w=1350&q=80');
      color: white;
      padding: 2rem;
      text-align: center;
      border-radius: 8px;
      margin-bottom: 2rem;
      background-size: cover;
      background-position: center;
      box-shadow: 0 4px 15px rgba(0,0,0,0.1);
    }
    
    .profile-pic {
      width: 150px;
      height: 150px;
      border-radius: 50%;
      border: 4px solid white;
      object-fit: cover;
      margin: 0 auto;
      display: block;
      box-shadow: 0 4px 8px rgba(0,0,0,0.2);
    }
    
    section {
      background-color: var(--light);
      padding: 1.5rem;
      border-radius: 8px;
      margin-bottom: 2rem;
      backdrop-filter: blur(2px);
      border: 1px solid rgba(0,0,0,0.1);
    }
    
    .projects-section {
      background:
        linear-gradient(rgba(248, 249, 250, 0.85), rgba(248, 249, 250, 0.9)),
        url('https://images.unsplash.com/photo-1550751827-4bd374c3f58b?ixlib=rb-4.0.3&auto=format&fit=crop&w=1350&q=80');
      background-size: cover;
      background-position: center;
    }
    
    h1, h2 {
      color: var(--primary);
    }
    
    h2 {
      border-bottom: 2px solid var(--secondary);
      padding-bottom: 5px;
      display: inline-block;
    }
    
    ul {
      padding-left: 20px;
    }
    
    li {
      margin-bottom: 10px;
      position: relative;
      list-style-type: none;
      padding-left: 1.5em;
    }
    
    li:before {
      content: "▹";
      color: var(--accent);
      position: absolute;
      left: 0;
    }
    
    .contact-info {
      background: 
        linear-gradient(rgba(236, 240, 241, 0.9), rgba(236, 240, 241, 0.95)),
        url('https://images.unsplash.com/photo-1626785774573-4b799315345d?ixlib=rb-4.0.3&auto=format&fit=crop&w=1350&q=80');
      background-size: cover;
      background-position: center;
    }
    
    /* Certifications Section */
    .certifications {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
      gap: 20px;
      margin-top: 20px;
    }
    
    .certification-card {
      background: white;
      border-radius: 8px;
      padding: 20px;
      box-shadow: 0 4px 8px rgba(0,0,0,0.1);
      border-top: 4px solid var(--primary);
    }
    
    .green-belt {
      border-top-color: var(--sixsigma-green);
    }
    
    .black-belt {
      border-top-color: var(--sixsigma-black);
    }
    
    .certification-title {
      font-size: 1.4rem;
      font-weight: bold;
      margin-bottom: 5px;
    }
    
    .belt-level {
      font-size: 1.1rem;
      color: #666;
      margin-bottom: 15px;
    }
    
    .certification-body {
      margin-bottom: 15px;
      line-height: 1.5;
    }
    
    .certification-date {
      font-style: italic;
      color: #666;
    }
    
    .signatures {
      margin-top: 20px;
      font-size: 0.9rem;
    }
    
    .signature {
      margin-bottom: 5px;
    }
    
    /* Experience Section */
    .timeline {
      position: relative;
      max-width: 1000px;
      margin: 0 auto;
    }
    
    .timeline::after {
      content: '';
      position: absolute;
      width: 2px;
      background-color: var(--secondary);
      top: 0;
      bottom: 0;
      left: 50px;
      margin-left: -1px;
    }
    
    .experience-card {
      position: relative;
      background-color: white;
      border-radius: 8px;
      padding: 20px;
      margin-bottom: 30px;
      box-shadow: 0 4px 8px rgba(0,0,0,0.1);
      margin-left: 80px;
    }
    
    .experience-card::before {
      content: '';
      position: absolute;
      width: 20px;
      height: 20px;
      background-color: white;
      border: 4px solid var(--secondary);
      border-radius: 50%;
      left: -62px;
      top: 30px;
      z-index: 1;
    }
    
    .company-header {
      display: flex;
      justify-content: space-between;
      margin-bottom: 10px;
    }
    
    .company-name {
      font-weight: bold;
      color: var(--primary);
      font-size: 1.2rem;
    }
    
    .job-title {
      font-weight: 600;
      margin-bottom: 5px;
    }
    
    .job-duration {
      color: #666;
      font-size: 0.9rem;
    }
    
    .job-location {
      font-style: italic;
      color: #666;
      margin-bottom: 15px;
    }
    
    .job-description {
      margin-bottom: 15px;
      line-height: 1.6;
    }
    
    .job-highlights {
      padding-left: 20px;
    }
    
    .job-highlights li {
      margin-bottom: 8px;
    }
    
    .skills-tags {
      display: flex;
      flex-wrap: wrap;
      gap: 8px;
      margin-top: 15px;
    }
    
    .skill-tag {
      background-color: #e0e9f5;
      color: var(--primary);
      padding: 4px 10px;
      border-radius: 20px;
      font-size: 0.8rem;
    }
    
    footer {
      text-align: center;
      padding: 1rem;
      color: #666;
      font-size: 0.9rem;
    }
    
    @media (max-width: 768px) {
      .container {
        padding: 10px;
      }
      
      .experience-card {
        margin-left: 60px;
      }
      
      .timeline::after {
        left: 30px;
      }
      
      .experience-card::before {
        left: -42px;
      }
    }
  </style>
</head>
<body>
  <div class="container">
    <header>
      <img class="profile-pic" src="https://i.postimg.cc/30xskJK9/18bcd881.jpg" alt="Faisal Ahamed">
      <h1>Faisal Ahamed</h1>
      <p>Senior Principal Test Development Engineer</p>
    </header>

    <section>
      <h2>Summary</h2>
      <p>24+ years of experience in semiconductor test engineering with specialization in RF applications, NPI (New Product Introduction), and yield improvement. Expertise in integrating AI solutions for test optimization and predictive maintenance.</p>
    </section>

    <section>
      <h2>Certifications</h2>
      <div class="certifications">
        <div class="certification-card green-belt">
          <div class="certification-title">Six Sigma</div>
          <div class="belt-level">Green Belt Certified</div>
          <div class="certification-body">
            This certifies that Faisal Ahamed Raj Mohamed has successfully completed the requirements 
            for Green Belt certification by demonstrating the fundamentals in the application of 
            statistical, problem solving, and Six Sigma tools.
          </div>
          <div class="certification-date">11 April 2005</div>
          <div class="signatures">
            <div class="signature"><strong>Michel Mayer</strong></div>
            <div>Chairman and CEO, Freescale Semiconductor</div>
            <div class="signature" style="margin-top: 10px;"><strong>Janelle Harris</strong></div>
            <div>SVP, Business Operations</div>
          </div>
        </div>
        
        <div class="certification-card black-belt">
          <div class="certification-title">Six Sigma</div>
          <div class="belt-level">Black Belt Certified</div>
          <div class="certification-body">
            This certifies that Faisal Ahamed Bin Raj Mohamed has successfully completed the requirements 
            for Black Belt certification by demonstrating advanced application of statistical, 
            problem solving, and Six Sigma methodologies.
          </div>
          <div class="certification-date">14 December 2010</div>
          <div class="signatures">
            <div class="signature"><strong>Rich Beyer</strong></div>
            <div>Chairman and CEO, Freescale Semiconductor</div>
            <div class="signature" style="margin-top: 10px;"><strong>Jim Baillie</strong></div>
            <div>Vice President Quality</div>
          </div>
        </div>
      </div>
    </section>

    <section>
      <h2>Work Experience</h2>
      <div class="timeline">
        
        <!-- Current Role -->
        <div class="experience-card">
          <div class="company-header">
            <div>
              <div class="job-title">Senior Staff Test/Product Development Engineer</div>
              <div class="company-name">Independent / Career Break</div>
            </div>
            <div class="job-duration">Apr 2024 - Present</div>
          </div>
          <div class="job-location">Kuala Lumpur, Malaysia · On-site</div>
          <div class="job-description">
            After completing 8+ years of service as a Senior Principal Test Development Engineer at NXP Semiconductors, 
            I took a short career break to pursue personal goals. I am now actively seeking new opportunities in RF testing, 
            semiconductor test/product engineering, or smart manufacturing.
          </div>
          <ul class="job-highlights">
            <li>Open to full-time or contract roles where I can apply my deep industry knowledge</li>
            <li>Seeking positions to contribute to innovation and lead test development or product engineering initiatives</li>
          </ul>
        </div>
        
        <!-- NXP Role -->
        <div class="experience-card">
          <div class="company-header">
            <div>
              <div class="job-title">Engineering Manager/Senior Principal Test Development Engineer</div>
              <div class="company-name">NXP Semiconductors</div>
            </div>
            <div class="job-duration">Mar 2016 - Mar 2024 · 8 yrs</div>
          </div>
          <div class="job-location">Kuala Lumpur, Malaysia · On-site</div>
          <ul class="job-highlights">
            <li>Led test development and introduction of 30+ new RF/mixed-signal products for automotive, industrial, and IoT applications</li>
            <li>Directed ATE test strategy including load board/interface design for Advantest V93K and Teradyne platforms</li>
            <li>Achieved 20-30% test cost reductions through test flow optimization and data-driven improvements</li>
            <li>Improved yield by 5% through failure analysis and collaboration with fab/assembly teams</li>
            <li>Managed cross-functional teams to meet NPI timelines with first-pass success</li>
            <li>Championed Six Sigma projects (Green & Black Belt certified) for yield optimization</li>
            <li>Supported global manufacturing transfers to OSATs in Southeast Asia and Europe</li>
            <li>Multiple award winner for technical excellence and mentoring junior engineers</li>
          </ul>
          <div class="skills-tags">
            <span class="skill-tag">ATE Test Development</span>
            <span class="skill-tag">RF Testing</span>
            <span class="skill-tag">Six Sigma Black Belt</span>
            <span class="skill-tag">Yield Improvement</span>
            <span class="skill-tag">NPI Management</span>
          </div>
        </div>
        
        <!-- Freescale Role -->
        <div class="experience-card">
          <div class="company-header">
            <div>
              <div class="job-title">Staff Product Engineer</div>
              <div class="company-name">Freescale Semiconductor</div>
            </div>
            <div class="job-duration">Jun 2004 - Jun 2016 · 12 yrs</div>
          </div>
          <div class="job-location">Petaling Jaya, Malaysia · On-site</div>
          <ul class="job-highlights">
            <li>Delivered 20% test time reduction through optimized test plans and bench-to-production transfer</li>
            <li>Supported 25+ product qualifications, reducing time-to-market by 15%</li>
            <li>Improved yield by 18% through systematic electrical failure analysis</li>
            <li>Spearheaded load board/socket interface design achieving 99.5% first-pass success</li>
            <li>Reduced engineering debug cycle by 30% through global team collaboration</li>
            <li>Trained junior engineers and created SOP documentation</li>
          </ul>
          <div class="skills-tags">
            <span class="skill-tag">Product Engineering</span>
            <span class="skill-tag">Test Optimization</span>
            <span class="skill-tag">Failure Analysis</span>
            <span class="skill-tag">LabVIEW Certified</span>
          </div>
        </div>
        
        <!-- Motorola Role -->
        <div class="experience-card">
          <div class="company-header">
            <div>
              <div class="job-title">Senior Test Development Engineer</div>
              <div class="company-name">Motorola Semiconductor</div>
            </div>
            <div class="job-duration">Feb 2000 - Jun 2004 · 4 yrs 5 mos</div>
          </div>
          <div class="job-location">Petaling Jaya, Malaysia · On-site</div>
          <ul class="job-highlights">
            <li>Developed production test solutions for 10+ analog/RF products</li>
            <li>Reduced ATE hardware cost by 12% through component reusability</li>
            <li>Designed thermally stable load boards for high-power RF applications</li>
            <li>Improved yield by 22% within 3 months through cross-functional FA</li>
            <li>Key contributor to ISO/quality audits with documentation excellence</li>
            <li>"Engineering Excellence" award winner for accelerating NPI schedule</li>
          </ul>
          <div class="skills-tags">
            <span class="skill-tag">Analog Testing</span>
            <span class="skill-tag">ATE Hardware</span>
            <span class="skill-tag">ISO Compliance</span>
          </div>
        </div>
      </div>
    </section>

    <section class="projects-section">
      <h2>Key Projects</h2>
      <ul>
        <li><strong>Project Aloha</strong> - AI optimization for RF product-line using machine learning algorithms</li>
        <li><strong>Project Data</strong> - Load board development with AI-driven impedance tuning</li>
        <li><strong>5G Test Solution</strong> - RF load board design for millimeter-wave applications</li>
        <li><strong>Yield Enhancement</strong> - AI-based pattern recognition for failure analysis</li>
      </ul>
    </section>

    <section class="contact-info">
      <h2>Contact</h2>
      <p><strong>Email:</strong> faisalking3rd@gmail.com / Faizal_1500@yahoo.com</p>
      <p><strong>Phone:</strong> +6011 370 68683</p>
      <p><strong>LinkedIn:</strong> <a href="https://www.linkedin.com/in/faisal-ahamed-876aa417" target="_blank">linkedin.com/in/faisal-ahamed-876aa417</a></p>
    </section>

    <footer>
      © 2024 Faisal Ahamed | Senior Principal Test Development Engineer
    </footer>
  </div>
</body>
</html>
