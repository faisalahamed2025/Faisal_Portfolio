<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Faisal Ahamed - Senior Principal Test Development Engineer</title>
  <style>
    :root {
      --primary: #2c3e50;
      --secondary: #3498db;
      --accent: #e74c3c;
      --light: #ecf0f1;
      --dark: #2c3e50;
      --gray: #95a5a6;
    }
    
    body {
      font-family: 'Segoe UI', system-ui, sans-serif;
      background-color: #f5f7fa;
      color: var(--dark);
      line-height: 1.6;
      margin: 0;
      padding: 0;
    }
    
    .container {
      max-width: 900px;
      margin: 0 auto;
      padding: 20px;
    }
    
    header {
      display: flex;
      align-items: center;
      gap: 30px;
      margin-bottom: 40px;
      padding-bottom: 20px;
      border-bottom: 2px solid var(--secondary);
    }
    
    .profile-pic {
      width: 150px;
      height: 150px;
      border-radius: 50%;
      object-fit: cover;
      border: 5px solid var(--secondary);
      box-shadow: 0 4px 10px rgba(0,0,0,0.1);
    }
    
    .header-text h1 {
      color: var(--primary);
      margin: 0;
      font-size: 2.2rem;
    }
    
    .header-text p {
      color: var(--accent);
      font-size: 1.2rem;
      font-weight: 500;
      margin: 5px 0 0;
    }
    
    section {
      margin-bottom: 30px;
    }
    
    h2 {
      color: var(--primary);
      border-bottom: 2px solid var(--secondary);
      padding-bottom: 5px;
      display: inline-block;
      margin-bottom: 15px;
    }
    
    ul {
      padding-left: 20px;
    }
    
    li {
      margin-bottom: 8px;
      position: relative;
      list-style-type: none;
    }
    
    li:before {
      content: "•";
      color: var(--accent);
      font-weight: bold;
      display: inline-block;
      width: 1em;
      margin-left: -1em;
    }
    
    .contact-info {
      background-color: var(--light);
      padding: 20px;
      border-radius: 8px;
      margin-top: 30px;
    }
    
    .contact-info p {
      margin: 5px 0;
    }
    
    .email {
      color: var(--accent);
      font-weight: 500;
    }
    
    @media (max-width: 768px) {
      header {
        flex-direction: column;
        text-align: center;
      }
      
      .header-text h1 {
        font-size: 1.8rem;
      }
    }
  </style>
</head>
<body>
  <div class="container">
    <header>
      <img class="profile-pic" src="https://i.postimg.cc/30xskJK9/18bcd881.jpg" alt="Faisal Ahamed">
      <div class="header-text">
        <h1>Faisal Ahamed</h1>
        <p>Senior Principal Test Development Engineer</p>
      </div>
    </header>

    <section>
      <h2>Summary</h2>
      <p>24+ years of experience in semiconductor test engineering with specialization in RF applications, NPI (New Product Introduction), and yield improvement.</p>
    </section>

    <section>
      <h2>Projects</h2>
      <ul>
        <li><strong>Project Aloha</strong> - AI optimization for RF product-line</li>
        <li><strong>Project Data</strong> - Load board development with AI tuning</li>
        <li>RF Load Board Design for 5G and Wi-Fi 6 Products</li>
        <li>Automated Test Program Development for High-Volume RF Production</li>
      </ul>
    </section>

    <div class="contact-info">
      <h2>Contact</h2>
      <p><strong>Email:</strong> <span class="email">faisalking3rd@gmail.com</span></p>
      <p><strong>Phone:</strong> +6011 370 68683</p>
      <p><strong>LinkedIn:</strong> <a href="https://www.linkedin.com/in/faisal-ahamed-876aa417" target="_blank">linkedin.com/in/faisal-ahamed</a></p>
    </div>
  </div>
</body>
</html>
