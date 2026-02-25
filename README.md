
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Dung Nguyen | Portfolio</title>

  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap" rel="stylesheet">

  <style>
    *{
      margin:0;
      padding:0;
      box-sizing:border-box;
      font-family: 'Poppins', sans-serif;
    }

    body{
      background:#f9f9f9;
      color:#222;
      line-height:1.7;
    }

    header{
      min-height:100vh;
      display:flex;
      align-items:center;
      justify-content:center;
      background:linear-gradient(120deg,#0f2027,#203a43,#2c5364);
      color:white;
      text-align:center;
      padding:40px 20px;
    }

    header h1{
      font-size:48px;
      letter-spacing:2px;
      margin-bottom:10px;
    }

    header h2{
      font-weight:400;
      font-size:20px;
      opacity:0.9;
      margin-bottom:20px;
    }

    header p{
      max-width:700px;
      margin:auto;
      font-size:18px;
      opacity:0.95;
    }

    section{
      padding:80px 10%;
      background:white;
    }

    section:nth-child(even){
      background:#f4f7fb;
    }

    h2{
      text-align:center;
      font-size:34px;
      margin-bottom:40px;
      position:relative;
    }

    h2::after{
      content:"";
      width:60px;
      height:4px;
      background:#2c5364;
      display:block;
      margin:12px auto 0;
      border-radius:10px;
    }

    p{
      font-size:17px;
    }

    .grid{
      display:grid;
      grid-template-columns:repeat(auto-fit,minmax(240px,1fr));
      gap:30px;
    }

    .grid div, .project{
      background:white;
      padding:30px;
      border-radius:15px;
      box-shadow:0 10px 30px rgba(0,0,0,0.08);
      transition:.3s;
    }

    .grid div:hover, .project:hover{
      transform:translateY(-6px);
      box-shadow:0 15px 40px rgba(0,0,0,0.15);
    }

    ul{
      padding-left:18px;
    }

    li{
      margin-bottom:8px;
    }

    .project h3{
      margin-bottom:10px;
    }

    .section.dark{
      background:#0f2027;
      color:white;
      text-align:center;
    }

    .section.dark p{
      font-size:18px;
      margin-bottom:10px;
    }

    footer{
      background:black;
      color:white;
      text-align:center;
      padding:20px;
      font-size:14px;
    }

    @media(max-width:768px){
      header h1{font-size:36px;}
      section{padding:60px 6%;}
    }
  </style>
</head>
<body>

<header>
  <div>
    <h1>Nguyễn Thị Dung</h1>
    <h2>Communication • Finance • Business • Content Creator</h2>

    <p>
      FTU student majoring in <b>International Finance & Japanese Business</b>,
      passionate about <b>communication, finance, and business strategy</b>.
      I aim to combine <b>data-driven thinking, creative storytelling, and
      commercial insight</b> to create meaningful impact in modern organizations.
    </p>
  </div>
</header>

<section id="about">
  <h2>About Me</h2>
  <p>
    I am currently a student at <b>Foreign Trade University (FTU), Vietnam</b>,
    majoring in <b>International Finance and Japanese Business</b>. With a strong
    passion for <b>communication, finance, and business development</b>, I
    continuously seek opportunities to expand my professional capabilities
    in a competitive and globalized environment.
  </p>

  <br>

  <p>
    Alongside my academic journey, I am also a <b>content creator</b>, managing
    the educational platform <b>"Hành tinh văn học"</b> with over
    <b>15,000+ followers</b>. Through this platform, I develop creative content,
    storytelling strategies, and community engagement campaigns.
  </p>

  <br>

  <p>
    My long-term goal is to pursue a career in <b>corporate finance,
    international business, or strategic communication</b>, especially in
    multinational corporations where innovation, data, and creativity meet.
  </p>
</section>

<section id="skills">
  <h2>Skills</h2>

  <div class="grid">
    <div>
      <h3>Finance & Business</h3>
      <ul>
        <li>Financial Analysis</li>
        <li>Financial Modeling</li>
        <li>Market Research</li>
        <li>Business Strategy</li>
      </ul>
    </div>

    <div>
      <h3>Communication & Content</h3>
      <ul>
        <li>Content Strategy</li>
        <li>Storytelling</li>
        <li>Social Media Growth</li>
        <li>Community Engagement</li>
      </ul>
    </div>

    <div>
      <h3>Languages</h3>
      <ul>
        <li>English – Advanced</li>
        <li>Chinese – HSK Certified</li>
        <li>Japanese – JLPT Certified</li>
      </ul>
    </div>
  </div>
</section>

<section id="projects">
  <h2>Projects & Experience</h2>

  <div class="project">
    <h3>Hành tinh văn học – Content Platform</h3>
    <p>
      Built and managed a literature & education content platform with
      <b>15,000+ followers</b>. Responsible for content strategy, creative
      direction, social media growth, and community engagement.
    </p>
  </div>

  <br>

  <div class="project">
    <h3>Market Research – Vietnamese Youth Consumers</h3>
    <p>
      Conducted market research on Gen Z consumer behavior, analyzing brand
      trust, sustainability perception, and purchasing intention in the
      Vietnamese F&B industry.
    </p>
  </div>

  <br>

  <div class="project">
    <h3>Internship – Mitsubishi Corporation (Japan)</h3>
    <p>
      Participated in business operations support, market analysis, and
      corporate communication activities in a Japanese multinational working
      environment.
    </p>
  </div>

  <br>

  <div class="project">
    <h3>Business Case Competition Projects</h3>
    <p>
      Worked on multiple business case studies involving financial evaluation,
      marketing strategy development, and data-driven decision making.
    </p>
  </div>
</section>

<section id="education">
  <h2>Education</h2>
  <p style="text-align:center">
    <b>Foreign Trade University (FTU)</b><br>
    Major: International Finance & Japanese Business<br>
    Focus: Corporate Finance, International Trade, Marketing Strategy, Business Analysis
  </p>
</section>

<section id="certifications">
  <h2>Certifications</h2>
  <ul style="max-width:600px;margin:auto">
    <li>IELTS / TOEIC – Advanced English Proficiency</li>
    <li>Chinese Language Certificate (HSK)</li>
    <li>Japanese Language Certificate (JLPT)</li>
    <li>Financial Modeling Foundations</li>
    <li>Data Analytics & Power BI</li>
  </ul>
</section>

<section id="contact" class="section dark">
  <h2>Contact</h2>
  <p>Email: dungnguyen@gmail.com</p>
  <p>Facebook • Instagram • LinkedIn • YouTube</p>
</section>

<footer>
  <p>© 2026 Nguyễn Thị Dung | Personal Portfolio</p>
</footer>

</body>
</html>
