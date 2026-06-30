#<!DOCTYPE html>
<html lang="hi">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Amit Kumar - Web Developer</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }
    body {
      font-family: Arial, sans-serif;
      background: #0f172a;
      color: white;
      line-height: 1.6;
    }
    .container {
      max-width: 600px;
      margin: 0 auto;
      padding: 20px;
    }
    /* Header */
    .header {
      text-align: center;
      padding: 40px 0;
    }
    .profile-pic {
      width: 120px;
      height: 120px;
      border-radius: 50%;
      border: 3px solid #38bdf8;
      margin-bottom: 15px;
    }
    h1 {
      color: #38bdf8;
      margin-bottom: 5px;
    }
    .tagline {
      color: #94a3b8;
      margin-bottom: 20px;
    }
    .btn {
      background: #38bdf8;
      color: #0f172a;
      padding: 12px 25px;
      border: none;
      border-radius: 8px;
      font-weight: bold;
      text-decoration: none;
      display: inline-block;
    }
    /* Sections */
    .section {
      background: #1e293b;
      margin: 20px 0;
      padding: 25px;
      border-radius: 12px;
    }
    h2 {
      color: #38bdf8;
      margin-bottom: 15px;
      border-bottom: 2px solid #38bdf8;
      padding-bottom: 5px;
    }
    .skill {
      background: #334155;
      padding: 8px 15px;
      border-radius: 20px;
      display: inline-block;
      margin: 5px;
      font-size: 14px;
    }
    .project {
      background: #334155;
      padding: 15px;
      border-radius: 8px;
      margin: 10px 0;
    }
    .project h3 {
      color: #7dd3fc;
    }
    /* Contact */
    .contact-item {
      margin: 10px 0;
    }
    .contact-item a {
      color: #7dd3fc;
      text-decoration: none;
    }
    /* Footer */
    .footer {
      text-align: center;
      padding: 30px 0;
      color: #64748b;
      font-size: 14px;
    }
  </style>
</head>
<body>
  <div class="container">
    
    <!-- Header -->
    <div class="header">
      <img src="https://via.placeholder.com/120" alt="Amit Kumar" class="profile-pic">
      <h1>Amit Kumar</h1>
      <p class="tagline">12th Pass | Aspiring Web Developer | Darbhanga, Bihar</p>
      <a href="#contact" class="btn">Contact Karo</a>
    </div>

    <!-- About Me -->
    <div class="section">
      <h2>Mere Baare Me</h2>
      <p>Namaste! Main Amit hoon, 19 saal ka. Mujhe computer aur science me bahut interest hai. Abhi HTML, CSS seekh raha hoon aur Web Developer banna chahta hoon. Mobile se coding start ki hai aur roz naya seekh raha hoon.</p>
    </div>

    <!-- Skills -->
    <div class="section">
      <h2>Skills</h2>
      <span class="skill">HTML</span>
      <span class="skill">CSS</span>
      <span class="skill">JavaScript - Learning</span>
      <span class="skill">Mobile Coding</span>
      <span class="skill">Problem Solving</span>
    </div>

    <!-- Projects -->
    <div class="section">
      <h2>Projects</h2>
      <div class="project">
        <h3>Personal Portfolio</h3>
        <p>Ye website jo aap dekh rahe ho. HTML CSS se mobile par banayi.</p>
      </div>
      <div class="project">
        <h3>Coming Soon</h3>
        <p>Calculator App - JavaScript se banaunga</p>
      </div>
    </div>

    <!-- Contact -->
    <div class="section" id="contact">
      <h2>Contact</h2>
      <div class="contact-item">📧 Email: <a href="mailto:amitkumarchoudhary@0102@gmsil.com">amitkumarchoudhary0102@gmail.com</a></div>
      <div class="contact-item">📱 WhatsApp: <a href="https://wa.me/916207464309">+916207464309</a></div>
      <div class="contact-item">📍 Location: Darbhanga, Bihar</div>
    </div>

    <!-- Footer -->
    <div class="footer">
      <p>© 2026 Amit Kumar. Mobile se banaya gaya 💙</p>
    </div>

  </div>
</body>
</html> my-website-