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
    
    /* Certification Plaque Styles */
    .certification-plaque {
      width: 100%;
      max-width: 400px;
      border: 8px solid #d4af37;
      border-radius: 4px;
      box-shadow: 0 10px 20px rgba(0,0,0,0.2);
      margin: 15px auto;
      display: block;
    }
    
    .plaque-container {
      text-align: center;
      margin: 20px 0;
    }
    
    /* Rest of your CSS remains the same */
    /* ... (include all previous CSS styles) ... */
  </style>
</head>
<body>
  <div class="container">
    <!-- Header Section -->
    <header>
      <img class="profile-pic" src="https://i.postimg.cc/30xskJK9/18bcd881.jpg" alt="Faisal Ahamed">
      <h1>Faisal Ahamed</h1>
      <p>Senior Principal Test Development Engineer</p>
    </header>

    <!-- Certifications Section with Plaque Images -->
    <section>
      <h2>Certifications</h2>
      
      <div class="plaque-container">
        <h3>Six Sigma Green Belt</h3>
        <img class="certification-plaque" src="https://example.com/your-greenbelt-plaque.jpg" alt="Six Sigma Green Belt Certification Plaque">
        <div class="certification-date">Awarded: 11 April 2005</div>
      </div>
      
      <div class="plaque-container">
        <h3>Six Sigma Black Belt</h3>
        <img class="certification-plaque" src="https://example.com/your-blackbelt-plaque.jpg" alt="Six Sigma Black Belt Certification Plaque">
        <div class="certification-date">Awarded: 14 December 2010</div>
      </div>
      
      <!-- Text Details -->
      <div class="certifications">
        <div class="certification-card green-belt">
          <div class="certification-title">Six Sigma Green Belt</div>
          <div class="certification-body">
            Certified by Freescale Semiconductor for demonstrating fundamentals in statistical analysis, 
            problem solving, and Six Sigma methodologies.
          </div>
          <div class="signatures">
            <div class="signature"><strong>Michel Mayer</strong></div>
            <div>Chairman and CEO, Freescale Semiconductor</div>
          </div>
        </div>
        
        <div class="certification-card black-belt">
          <div class="certification-title">Six Sigma Black Belt</div>
          <div class="certification-body">
            Certified by Freescale Semiconductor for advanced application of Six Sigma methodologies 
            and leadership in process improvement projects.
          </div>
          <div class="signatures">
            <div class="signature"><strong>Rich Beyer</strong></div>
            <div>Chairman and CEO, Freescale Semiconductor</div>
          </div>
        </div>
      </div>
    </section>

    <!-- Work Experience Section -->
    <section>
      <h2>Work Experience</h2>
      <div class="timeline">
        <!-- Your work experience entries here -->
        <!-- ... (include all your work experience HTML) ... -->
      </div>
    </section>

    <!-- Other sections (Projects, Contact) -->
    <!-- ... (include your other sections) ... -->
  </div>
</body>
</html>
