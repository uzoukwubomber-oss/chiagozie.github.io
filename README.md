<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Uzoukwu Chiagozie Emmanuel - Medical Student & Tech Enthusiast</title>
  <style>
    * {margin: 0; padding: 0; box-sizing: border-box;}
    body {
      font-family: 'Segoe UI', Arial, sans-serif;
      background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
      color: #333;
      line-height: 1.7;
    }
    .container {max-width: 900px; margin: 40px auto; padding: 20px;}
    .card {
      background: white;
      border-radius: 20px;
      padding: 40px;
      margin-bottom: 30px;
      box-shadow: 0 10px 30px rgba(0,0,0,0.2);
    }
    .header {text-align: center; margin-bottom: 30px;}
    .profile-img {
      width: 180px;
      height: 180px;
      border-radius: 50%;
      object-fit: cover;
      border: 5px solid #667eea;
      margin-bottom: 20px;
      box-shadow: 0 5px 15px rgba(0,0,0,0.2);
    }
    h1 {color: #667eea; font-size: 2.5em; margin-bottom: 5px;}
    .tagline {color: #666; font-size: 1.2em; margin-bottom: 20px;}
    .info-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 15px;
      margin: 25px 0;
    }
    .info-item {
      background: #f8f9fa;
      padding: 15px;
      border-radius: 10px;
      border-left: 4px solid #667eea;
      text-align: left;
    }
    .info-item b {color: #667eea; display: block; margin-bottom: 5px;}
    h2 {
      color: #764ba2;
      border-bottom: 3px solid #667eea;
      padding-bottom: 10px;
      margin: 30px 0 20px;
    }
    .skills {
      display: flex;
      flex-wrap: wrap;
      gap: 10px;
      margin-top: 15px;
    }
    .skill {
      background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
      color: white;
      padding: 8px 18px;
      border-radius: 20px;
      font-size: 0.9em;
    }
    .links {
      display: flex;
      flex-wrap: wrap;
      gap: 15px;
      margin-top: 20px;
      justify-content: center;
    }
    .links a {
      padding: 12px 25px;
      background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
      color: white;
      text-decoration: none;
      border-radius: 10px;
      transition: transform 0.3s;
    }
    .links a:hover {transform: translateY(-3px);}
    @media (max-width: 600px) {
      .card {padding: 25px;}
      h1 {font-size: 1.8em;}
      .profile-img {width: 140px; height: 140px;}
    }
  </style>
</head>
<body>
  <div class="container">
    
    <!-- Profile Card -->
    <div class="card header">
      <img src="profile.jpg" alt="Uzoukwu Chiagozie Emmanuel" class="profile-img">
      <h1>Uzoukwu Chiagozie Emmanuel</h1>
      <p class="tagline">Medical Student | Tech Enthusiast | Future Health Innovator</p>
      
      <div class="info-grid">
        <div class="info-item">
          <b>Age</b>
          19 years old<br>
          <small>Born: 8 April 2007</small>
        </div>
        <div class="info-item">
          <b>Hometown</b>
          Nkwesi, Oguta LGA<br>
          <small>Imo State, Nigeria</small>
        </div>
        <div class="info-item">
          <b>Nationality</b>
          Nigerian 🇳🇬
        </div>
        <div class="info-item">
          <b>Field</b>
          Medicine & Surgery<br>
          <small>Tech + Healthcare</small>
        </div>
      </div>

      <div class="links">
        <a href="YOUR_TIKTOK_LINK" target="_blank">TikTok</a>
        <a href="YOUR_INSTAGRAM_LINK" target="_blank">Instagram</a>
        <a href="mailto:YOUR_EMAIL">Email Me</a>
        <a href="https://github.com/uzoukwubomber-oss" target="_blank">GitHub</a>
      </div>
    </div>

    <!-- About Card -->
    <div class="card">
      <h2>About Me</h2>
      <p>
        I’m Uzoukwu Chiagozie Emmanuel, a 19-year-old medical student from Nkwesi town in Oguta LGA, Imo State, Nigeria. 
        Growing up in Nkwesi taught me resilience, community values, and the importance of solving real problems.
      </p>
      <p style="margin-top: 15px;">
        I’m passionate about the intersection of medicine and technology. While studying Medicine & Surgery, 
        I’m also teaching myself web development, Python, and health-tech innovation. My goal is to build digital 
        solutions that make healthcare faster, cheaper, and more accessible for rural communities like mine.
      </p>
      <p style="margin-top: 15px;">
        I believe the future of medicine in Nigeria is digital. I’m learning, building, and connecting with 
        people who share that vision.
      </p>
    </div>

    <!-- Skills Card -->
    <div class="card">
      <h2>Skills & Strengths</h2>
      <div class="skills">
        <span class="skill">Medical Sciences</span>
        <span class="skill">Anatomy & Physiology</span>
        <span class="skill">HTML & CSS</span>
        <span class="skill">Python Basics</span>
        <span class="skill">GitHub & Web Hosting</span>
        <span class="skill">Health Tech</span>
        <span class="skill">Research</span>
        <span class="skill">Problem Solving</span>
        <span class="skill">Content Creation</span>
        <span class="skill">Public Speaking</span>
      </div>
    </div>

    <!-- Vision Card -->
    <div class="card">
      <h2>Vision</h2>
      <p>
        To create and support health-tech solutions that bridge the gap between rural communities in Imo State 
        and quality healthcare. I want to be part of the generation that uses technology to save lives and 
        improve health outcomes across Nigeria.
      </p>
    </div>

  </div>
</body>
</html>
