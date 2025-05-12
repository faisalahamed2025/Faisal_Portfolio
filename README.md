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
          <div class="belt-level">Black Belt Certified</div
