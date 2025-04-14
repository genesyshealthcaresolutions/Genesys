<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Genesys Healthcare Solutions</title>

  <!-- Font Awesome for icons -->
  <script src="https://kit.fontawesome.com/a076d05399.js" crossorigin="anonymous"></script>

  <style>
    html {
      scroll-behavior: smooth;
    }

    body {
      margin: 0;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background-color: #121212;
      color: #f5f5f5;
    }

    header {
  background-color: #ff6600;
  color: #000;
  padding: 0.02px 20px;
  display: flex;
  justify-content: space-between;
  align-items: center;
  flex-wrap: wrap;
  position: sticky;
  top: 0;
  z-index: 1000;
}


    .logo h1 {
      font-size: 1.8rem;
      font-weight: bold;
      display: flex;
      align-items: center;
      border: 2px solid #000;
      padding: 10px 20px;
      border-radius: 6px;
    }

    .logo h1 i {
      font-size: 1.5rem;
      margin-right: 10px;
    }

    nav a {
      color: #000;
      text-decoration: none;
      margin: 0 15px;
      font-weight: bold;
      transition: color 0.3s;
    }

    nav a:hover {
      color: #fff;
    }

    .hero {
      padding: 80px 20px;
      text-align: center;
      background-color: #1e1e1e;
    }

    .hero h1 {
      font-size: 2.8rem;
      margin-bottom: 20px;
      color: #ff6600;
    }

    .hero p {
      font-size: 1.2rem;
      max-width: 600px;
      margin: 0 auto;
    }

    .section {
      padding: 40px 20px;
      max-width: 1000px;
      margin: 40px auto;
      background-color: #1a1a1a;
      border-radius: 10px;
    }

    .section h2 {
      color: #ff6600;
      margin-bottom: 15px;
    }

    ul {
      list-style-type: square;
      padding-left: 20px;
    }

    li {
      margin-bottom: 10px;
    }

    .team-container {
      display: grid;
      grid-template-columns: repeat(auto-fill, minmax(200px, 1fr));
      gap: 20px;
    }

    .team-member {
      background-color: #2a2a2a;
      border-radius: 10px;
      padding: 20px;
      text-align: center;
    }

    .team-member img {
      width: 100px;
      height: 100px;
      border-radius: 50%;
      object-fit: cover;
      margin-bottom: 10px;
    }

    .team-member h4 {
      margin: 10px 0 5px;
      color: #ff6600;
    }

    .team-member p {
      font-size: 0.9rem;
      color: #ccc;
    }

    footer {
      background-color: #000;
      text-align: center;
      padding: 20px;
      font-size: 0.9rem;
      color: #999;
    }

    .btn {
      background-color: #ff6600;
      color: #000;
      border: none;
      padding: 12px 20px;
      font-weight: bold;
      border-radius: 6px;
      cursor: pointer;
      transition: all 0.3s ease;
      margin-top: 20px;
    }

    .btn:hover {
      background-color: #ff8533;
      transform: scale(1.05);
    }

    .icons i {
      font-size: 24px;
      margin: 10px;
      color: #ff6600;
      transition: color 0.3s;
    }

    .icons i:hover {
      color: #fff;
    }
  </style>
</head>
<body>

  <header>
    <div class="logo">
      <h1><i class="fas fa-hospital-alt"></i> Genesys Healthcare Solutions</h1>
    </div>
    <nav>
      <a href="#">Home</a>
      <a href="#about">About</a>
      <a href="#services">Services</a>
      <a href="#hiring">Hiring</a>
      <a href="#team">Team</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <div class="hero">
    <h1>Innovating Healthcare for a Healthier Tomorrow</h1>
    <p>We deliver modern, tech-driven healthcare solutions that empower providers and improve patient outcomes.</p>
    <button class="btn"><i class="fas fa-stethoscope"></i> Learn More</button>
  </div>

  <div class="section" id="about">
    <h2><i class="fas fa-info-circle"></i> About Us</h2>
    <p>
      At Genesys Healthcare Solutions, we connect exceptional healthcare professionals with both permanent and temporary positions across the United States. We are not a staffing agency. Instead, we operate as a dedicated hiring partner—an extension of the healthcare facility's own recruitment team.
<br><br>
Our focus is on building direct, long-term relationships with hospitals, clinics, and healthcare organizations to ensure seamless hiring and onboarding of top-tier talent. By eliminating third-party staffing layers, we streamline the process, improve retention, and ensure professionals are aligned with each facility’s mission and values.
    </p>
  </div>

  <div class="section" id="services">
    <h2><i class="fas fa-cogs"></i> Our Services</h2>
    <ul>
      <li>Direct-hire Healthcare Professionals</li>
      <li>Healthcare IT Consulting</li>
      <li>Telemedicine Development</li>
      <li>AI-Powered Patient Data Analytics</li>
    </ul>
  </div>

  <div class="section" id="hiring">
    <h2>We Are Hiring Department!</h2>
    <p>We support hiring for leading organizations including:</p>
    <ul>
      <li>Amedisys</li>
      <li>LHC Group (UnitedHealth Group)</li>
      <li>Kindred at Home (CenterWell Home Health)</li>
      <li>Interim HealthCare</li>
      <li>Select Medical</li>
      <li>Brookdale Senior Living</li>
      <li>Genesis HealthCare</li>
      <li>Mayo Clinic</li>
      <li>Cleveland Clinic</li>
      <li>Johns Hopkins Hospital</li>
      <li>Massachusetts General Hospital</li>
      <li>Cedars-Sinai Medical Center</li>
      <li>Life Care Centers of America</li>
      <li>Encompass Health</li>
      <li>Shirley Ryan AbilityLab</li>
    </ul>
  </div>

  <div class="section" id="team">
    <h2><i class="fas fa-users"></i> Our Hiring Team</h2>
    <div class="team-container">
      <div class="team-member">
        <img src="https://via.placeholder.com/100" alt="">
        <h4>Emily Johnson</h4><p>Hiring Manager<br>emily.genesys@outlook.com</p>
      </div>
      <div class="team-member">
        <img src="https://via.placeholder.com/100" alt="">
        <h4>Michael Smith</h4><p>Team Lead<br>michael.genesys@outlook.com</p>
      </div>
      <div class="team-member">
        <img src="https://via.placeholder.com/100" alt="">
        <h4>Sophia Lee</h4><p>Document Specialist<br>sophia.genesys@outlook.com</p>
      </div>
      <div class="team-member">
        <img src="https://via.placeholder.com/100" alt="">
        <h4>Daniel Kim</h4><p>Hiring Specialist<br>daniel.genesys@outlook.com</p>
      </div>
      <div class="team-member">
        <img src="https://via.placeholder.com/100" alt="">
        <h4>Ava Patel</h4><p>Support Specialist<br>ava.genesys@outlook.com</p>
      </div>
      <div class="team-member">
        <img src="https://via.placeholder.com/100" alt="">
        <h4>Liam Brown</h4><p>Support Specialist<br>liam.genesys@outlook.com</p>
      </div>
      <div class="team-member">
        <img src="https://via.placeholder.com/100" alt="">
        <h4>Noah Davis</h4><p>Document Specialist<br>noah.genesys@outlook.com</p>
      </div>
      <div class="team-member">
        <img src="https://via.placeholder.com/100" alt="">
        <h4>Penny Zen </h4><p>Hiring Specialist<br>penny.genesys@outlook.com</p>
      </div>
      <div class="team-member">
        <img src="https://via.placeholder.com/100" alt="">
        <h4>William Harris</h4><p>Team Lead<br>william.genesys@outlook.com</p>
      </div>
      <div class="team-member">
        <img src="https://via.placeholder.com/100" alt="">
        <h4>Isabella Clark</h4><p>Support Specialist<br>isabella.genesys@outlook.com</p>
      </div>
      <div class="team-member">
        <img src="https://via.placeholder.com/100" alt="">
        <h4>James Lewis</h4><p>Hiring Specialist<br>james.genesys@outlook.com</p>
      </div>
      <div class="team-member">
        <img src="https://via.placeholder.com/100" alt="">
        <h4>Mia Walker</h4><p>Support Specialist<br>mia.genesys@outlook.com</p>
      </div>
      <div class="team-member">
        <img src="https://via.placeholder.com/100" alt="">
        <h4>Benjamin Hall</h4><p>Document Specialist<br>benjamin.genesys@outlook.com</p>
      </div>
      <div class="team-member">
        <img src="https://via.placeholder.com/100" alt="">
        <h4>Charlotte Allen</h4><p>Hiring Specialist<br>charlotte.genesys@outlook.com</p>
      </div>
      <div class="team-member">
        <img src="https://via.placeholder.com/100" alt="">
        <h4>Elijah Young</h4><p>Team Lead<br>elijah.genesys@outlook.com</p>
      </div>
    </div>
  </div>

  <div class="section" id="contact">
    <h2><i class="fas fa-envelope"></i> Contact Us</h2>
    <p>Email: hr.genesys@outlook.com</p>
    <p>Phone: +1 (267) 267-3661</p>
    <p>Locations: US & India</p>
    <div class="icons">
      <a href="#"><i class="fab fa-linkedin"></i></a>
      <a href="#"><i class="fab fa-twitter-square"></i></a>
      <a href="#"><i class="fab fa-facebook-square"></i></a>
    </div>
  </div>

  <footer>
    &copy; 2024 Genesys Healthcare Solutions. All rights reserved.
  </footer>

</body>
</html>
