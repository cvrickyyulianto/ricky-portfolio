portfolio-engineering/
 ├─ index.html
 ├─ style.css
 └─ script.js
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Ricky Yulianto | Engineering Supervisor</title>

  <link rel="stylesheet" href="style.css"/>

  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700;900&display=swap" rel="stylesheet">
</head>

<body>

  <div class="bg-glow"></div>

  <section class="hero">

    <div class="badge">
      Engineering Supervisor • Bali Indonesia
    </div>

    <h1>
      Ricky <br>
      <span>Yulianto</span>
    </h1>

    <p>
      Engineering Supervisor with 10+ years of experience in HVAC,
      electrical systems, hospitality engineering, and building maintenance operations.
    </p>

    <div class="buttons">
      <a href="https://wa.me/6282142814408" target="_blank" class="btn primary">
        WhatsApp
      </a>

      <a href="mailto:rickyyulianto88@gmail.com" class="btn">
        Email
      </a>

      <a href="https://www.linkedin.com/in/ricky-yulianto-2082ab1ba" target="_blank" class="btn">
        LinkedIn
      </a>

      <a href="#" class="btn white">
        Download CV
      </a>
    </div>

  </section>

  <section class="stats">

    <div class="card">
      <h2>10+</h2>
      <p>Years Experience</p>
    </div>

    <div class="card">
      <h2>HVAC</h2>
      <p>Building Systems</p>
    </div>

    <div class="card full">
      <h3>Core Expertise</h3>

      <div class="tags">
        <span>HVAC</span>
        <span>Electrical Systems</span>
        <span>Generator & UPS</span>
        <span>Preventive Maintenance</span>
      </div>
    </div>

  </section>

  <section class="about">

    <small>ABOUT ME</small>

    <h2>
      Reliable Engineering Leadership
      for Hospitality & Building Operations
    </h2>

    <p>
      Experienced in supervising engineering operations, preventive maintenance,
      corrective maintenance, and technical troubleshooting for hospitality and commercial properties.
    </p>

  </section>

  <section class="experience">

    <small>EXPERIENCE</small>

    <h2>Professional Journey</h2>

    <div class="job">
      <h3>Supervisor Engineering</h3>
      <span>PT. Bersama Bali Cemerlang</span>

      <ul>
        <li>Supervise daily engineering operations</li>
        <li>Coordinate preventive maintenance</li>
        <li>Handle technical troubleshooting</li>
      </ul>
    </div>

    <div class="job">
      <h3>Project Engineer</h3>
      <span>CV. Sinar Inti Abadi</span>

      <ul>
        <li>Managed electrical installation projects</li>
        <li>Handled supervision and QC</li>
        <li>Prepared technical documentation</li>
      </ul>
    </div>

  </section>

  <section class="skills">

    <small>TECHNICAL SKILLS</small>

    <h2>Core Competencies</h2>

    <div class="skill-grid">

      <div class="skill">
        <p>HVAC</p>
        <div class="line"></div>
      </div>

      <div class="skill">
        <p>Electrical Systems</p>
        <div class="line"></div>
      </div>

      <div class="skill">
        <p>Plumbing</p>
        <div class="line"></div>
      </div>

      <div class="skill">
        <p>Generator & UPS</p>
        <div class="line"></div>
      </div>

    </div>

  </section>

  <section class="contact">

    <small>CONTACT</small>

    <h2>
      Let’s Build Reliable
      <span>Engineering Operations</span>
    </h2>

    <p>
      Available for Engineering Supervisor,
      Building Maintenance,
      Hospitality Engineering,
      and Technical Management opportunities.
    </p>

    <a href="https://wa.me/6282142814408" class="contact-btn">
      Contact Me
    </a>

  </section>

</body>
</html>
*{
  margin:0;
  padding:0;
  box-sizing:border-box;
}

body{
  background:#020617;
  color:white;
  font-family:'Inter',sans-serif;
  overflow-x:hidden;
}

.bg-glow{
  position:fixed;
  width:600px;
  height:600px;
  background:#06b6d4;
  filter:blur(180px);
  opacity:.15;
  top:-200px;
  left:-200px;
  z-index:-1;
}

section{
  padding:80px 24px;
  max-width:1200px;
  margin:auto;
}

.hero{
  min-height:100vh;
  display:flex;
  flex-direction:column;
  justify-content:center;
}

.badge{
  border:1px solid #164e63;
  color:#67e8f9;
  width:max-content;
  padding:12px 22px;
  border-radius:999px;
  margin-bottom:30px;
}

.hero h1{
  font-size:72px;
  line-height:1;
  font-weight:900;
  margin-bottom:30px;
}

.hero h1 span{
  color:#22d3ee;
}

.hero p{
  color:#cbd5e1;
  max-width:700px;
  font-size:22px;
  line-height:1.7;
  margin-bottom:40px;
}

.buttons{
  display:flex;
  flex-wrap:wrap;
  gap:16px;
}

.btn{
  padding:16px 28px;
  border:1px solid #334155;
  border-radius:18px;
  color:white;
  text-decoration:none;
  font-weight:700;
}

.primary{
  background:#22d3ee;
  color:black;
  border:none;
}

.white{
  background:white;
  color:black;
}

.stats{
  display:grid;
  grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
  gap:20px;
}

.card{
  background:#0f172a;
  border:1px solid #1e293b;
  padding:30px;
  border-radius:24px;
}

.card h2{
  color:#22d3ee;
  font-size:42px;
  margin-bottom:10px;
}

.full{
  grid-column:span 2;
}

.tags{
  display:flex;
  flex-wrap:wrap;
  gap:12px;
  margin-top:20px;
}

.tags span{
  background:#082f49;
  color:#67e8f9;
  padding:10px 16px;
  border-radius:12px;
}

.about h2,
.experience h2,
.skills h2,
.contact h2{
  font-size:52px;
  margin:18px 0 30px;
}

small{
  color:#22d3ee;
  letter-spacing:3px;
}

.about p,
.contact p{
  color:#cbd5e1;
  line-height:1.8;
  font-size:20px;
}

.job{
  background:#0f172a;
  border:1px solid #1e293b;
  border-radius:24px;
  padding:30px;
  margin-top:24px;
}

.job h3{
  font-size:30px;
  margin-bottom:10px;
}

.job span{
  color:#67e8f9;
}

.job ul{
  margin-top:20px;
  padding-left:20px;
  color:#cbd5e1;
}

.skill-grid{
  display:grid;
  grid-template-columns:repeat(auto-fit,minmax(240px,1fr));
  gap:20px;
}

.skill{
  background:#0f172a;
  border:1px solid #1e293b;
  padding:24px;
  border-radius:20px;
}

.line{
  width:100%;
  height:6px;
  background:#22d3ee;
  border-radius:999px;
  margin-top:14px;
}

.contact{
  text-align:center;
}

.contact span{
  color:#22d3ee;
}

.contact-btn{
  display:inline-block;
  margin-top:40px;
  background:#22d3ee;
  color:black;
  padding:18px 40px;
  border-radius:20px;
  font-weight:700;
  text-decoration:none;
}

@media(max-width:768px){

  .hero h1{
    font-size:56px;
  }

  .about h2,
  .experience h2,
  .skills h2,
  .contact h2{
    font-size:38px;
  }

  .hero p{
    font-size:18px;
  }

  .full{
    grid-column:span 1;
  }

}

console.log("Ricky Yulianto Portfolio Loaded");

