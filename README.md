<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Developer Profile</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600&display=swap" rel="stylesheet">
  <style>
    body {
      margin: 0;
      font-family: 'Inter', sans-serif;
      background: #f3f6f8;
      color: #1d2226;
    }

    .container {
      max-width: 900px;
      margin: 40px auto;
      background: white;
      border-radius: 12px;
      box-shadow: 0 4px 20px rgba(0,0,0,0.1);
      overflow: hidden;
    }

    .header {
      background: linear-gradient(135deg, #0a66c2, #004182);
      height: 150px;
    }

    .profile {
      padding: 20px;
      display: flex;
      align-items: center;
      gap: 20px;
      margin-top: -60px;
    }

    .avatar {
      width: 120px;
      height: 120px;
      border-radius: 50%;
      border: 5px solid white;
      background: url('https://via.placeholder.com/120') center/cover;
    }

    .info h1 {
      margin: 0;
      font-size: 26px;
    }

    .info p {
      margin: 5px 0;
      color: #666;
    }

    .section {
      padding: 20px;
      border-top: 1px solid #eee;
    }

    .section h2 {
      margin-bottom: 10px;
      font-size: 20px;
    }

    .skills {
      display: flex;
      flex-wrap: wrap;
      gap: 10px;
    }

    .skill {
      background: #e7f3ff;
      color: #0a66c2;
      padding: 8px 12px;
      border-radius: 20px;
      font-size: 14px;
    }

    .footer {
      text-align: center;
      padding: 15px;
      font-size: 14px;
      color: #888;
    }
  </style>
</head>
<body>

  <div class="container">
    <div class="header"></div>

    <div class="profile">
      <div class="avatar"></div>
      <div class="info">
        <h1>Gov</h1>
        <p>Full Stack Developer</p>
        <p>Master's Degree in Java ☕</p>
      </div>
    </div>

    <div class="section">
      <h2>About</h2>
      <p>
        Passionate Full Stack Developer with strong expertise in Java development.
        Experienced in building scalable applications and working across multiple
        technologies including SQL, Python, and Rust.
      </p>
    </div>

    <div class="section">
      <h2>Skills</h2>
      <div class="skills">
        <div class="skill">Java</div>
        <div class="skill">SQL</div>
        <div class="skill">Python</div>
        <div class="skill">Rust</div>
        <div class="skill">Full Stack Development</div>
      </div>
    </div>

    <div class="section">
      <h2>Experience</h2>
      <p>
        • Developed backend systems using Java and SQL databases.<br>
        • Built full-stack applications with modern frameworks.<br>
        • Optimized performance and scalability in production systems.
      </p>
    </div>

    <div class="footer">
      © 2026 Your Name • GitHub Portfolio
    </div>
  </div>

</body>
</html>
