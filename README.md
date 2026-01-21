<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Mouli Banerjee | GitHub Portfolio</title>

  <style>
    :root{
      --bg:#0b1220;
      --card:#0f1a2e;
      --muted:#9fb2d1;
      --text:#eaf1ff;
      --accent:#6ee7ff;
      --accent2:#a78bfa;
      --good:#22c55e;
      --border: rgba(255,255,255,0.08);
      --shadow: 0 18px 60px rgba(0,0,0,0.45);
    }

    *{margin:0; padding:0; box-sizing:border-box; font-family: system-ui, -apple-system, Segoe UI, Roboto, Arial;}
    body{
      background: radial-gradient(1200px 500px at 20% 0%, rgba(110,231,255,0.18), transparent 60%),
                  radial-gradient(900px 500px at 90% 20%, rgba(167,139,250,0.18), transparent 60%),
                  var(--bg);
      color: var(--text);
      padding: 32px 16px;
    }

    a{color:inherit; text-decoration:none;}
    .wrap{max-width:1100px; margin:0 auto; display:grid; gap:18px;}

    .top{
      background: linear-gradient(135deg, rgba(110,231,255,0.12), rgba(167,139,250,0.12));
      border: 1px solid var(--border);
      border-radius: 18px;
      box-shadow: var(--shadow);
      padding: 26px;
      position: relative;
      overflow:hidden;
    }
    .glow{
      position:absolute;
      inset:-120px;
      background: radial-gradient(circle at 30% 30%, rgba(110,231,255,0.18), transparent 50%),
                  radial-gradient(circle at 80% 40%, rgba(167,139,250,0.18), transparent 52%);
      filter: blur(30px);
      pointer-events:none;
    }

    .header{
      display:flex; flex-wrap:wrap;
      align-items:center; justify-content:space-between;
      gap:16px;
      position:relative;
      z-index:2;
    }

    .name{
      display:flex; flex-direction:column; gap:6px;
    }
    .name h1{
      font-size: 30px;
      letter-spacing: 0.2px;
    }
    .tagline{
      color: var(--muted);
      font-size: 14.5px;
      max-width: 680px;
      line-height:1.5;
    }

    .btns{
      display:flex; flex-wrap:wrap;
      gap:10px;
    }
    .btn{
      padding: 10px 14px;
      border-radius: 12px;
      border: 1px solid var(--border);
      background: rgba(255,255,255,0.06);
      transition: 0.2s ease;
      font-weight: 600;
      font-size: 14px;
    }
    .btn:hover{
      transform: translateY(-2px);
      border-color: rgba(110,231,255,0.35);
      background: rgba(110,231,255,0.08);
    }

    .grid{
      display:grid;
      grid-template-columns: 1.2fr 0.8fr;
      gap: 18px;
    }

    @media(max-width: 900px){
      .grid{grid-template-columns:1fr;}
    }

    .card{
      background: rgba(15,26,46,0.82);
      border: 1px solid var(--border);
      border-radius: 18px;
      box-shadow: var(--shadow);
      padding: 18px;
    }

    .title{
      display:flex;
      align-items:center;
      justify-content:space-between;
      gap:10px;
      margin-bottom: 12px;
    }

    .title h2{
      font-size: 18px;
      letter-spacing:0.2px;
    }

    .pill{
      font-size: 12px;
      padding: 6px 10px;
      border-radius: 999px;
      border: 1px solid var(--border);
      background: rgba(255,255,255,0.05);
      color: var(--muted);
    }

    .list{
      display:grid;
      gap: 10px;
    }

    .item{
      padding: 12px;
      border-radius: 14px;
      border: 1px solid var(--border);
      background: rgba(255,255,255,0.04);
    }

    .item strong{font-size: 14.5px;}
    .item p{
      color: var(--muted);
      margin-top:6px;
      line-height:1.5;
      font-size: 13.5px;
    }

    .mini{
      display:grid;
      gap: 10px;
    }

    .mini .row{
      display:flex;
      justify-content:space-between;
      gap:12px;
      padding: 12px;
      border-radius: 14px;
      border: 1px solid var(--border);
      background: rgba(255,255,255,0.04);
      font-size: 14px;
    }

    .mini .row span{
      color: var(--muted);
    }

    .skills{
      display:flex;
      flex-wrap:wrap;
      gap:8px;
      margin-top:10px;
    }
    .chip{
      font-size: 12.5px;
      padding: 7px 10px;
      border-radius: 999px;
      border: 1px solid var(--border);
      background: rgba(255,255,255,0.05);
      color: var(--text);
    }

    .footer{
      text-align:center;
      color: var(--muted);
      font-size: 13px;
      margin-top: 8px;
    }

    .highlight{
      color: var(--good);
      font-weight: 700;
    }
  </style>
</head>

<body>
  <div class="wrap">

    <!-- TOP HERO -->
    <section class="top">
      <div class="glow"></div>

      <div class="header">
        <div class="name">
          <h1>Mouli Banerjee</h1>
          <div class="tagline">
            B.Tech CSE (LPU) | Data Analyst + ML Enthusiast | Power BI • Python • SQL • ML Dashboards <br/>
            Focused on building real-world ML solutions and analytics tools with strong problem-solving skills.
          </div>
        </div>

        <div class="btns">
          <a class="btn" href="https://www.linkedin.com/in/moulibanerjee" target="_blank">LinkedIn</a>
          <a class="btn" href="https://github.com/MOULI3636" target="_blank">GitHub</a>
          <a class="btn" href="mailto:banerjeemouli26@gmail.com">Email</a>
        </div>
      </div>
    </section>

    <!-- MAIN GRID -->
    <section class="grid">

      <!-- LEFT -->
      <div class="card">
        <div class="title">
          <h2>Internship Experience</h2>
          <span class="pill">Industry Exposure</span>
        </div>

        <div class="list">

          <div class="item">
            <strong>Data Science Intern — CipherByte Technologies (Jul 2025 – Aug 2025)</strong>
            <p>
              Built classification models (KNN, SVM, Logistic Regression) achieving <span class="highlight">92% F1-score</span>.
              Performed EDA to improve prediction precision by <span class="highlight">12%</span>.
              Developed a Tkinter desktop app for fast spam detection, reducing processing time by <span class="highlight">40%</span>.
            </p>
          </div>

          <div class="item">
            <strong>Machine Learning Intern — Academy Innova World (Jun 2025 – Jul 2025)</strong>
            <p>
              Built and deployed <span class="highlight">5+ ML models</span> with up to <span class="highlight">93% accuracy</span>.
              Automated preprocessing with StandardScaler + Feature Engineering, boosting accuracy by <span class="highlight">18%</span>
              and reducing manual effort by <span class="highlight">70%</span>.
              Created explainable dashboards using PCA + SHAP for 20K+ records.
            </p>
          </div>

        </div>
      </div>

      <!-- RIGHT -->
      <div class="card">
        <div class="title">
          <h2>Quick Info</h2>
          <span class="pill">Contact</span>
        </div>

        <div class="mini">
          <div class="row">
            <b>Email</b><span>banerjeemouli26@gmail.com</span>
          </div>
          <div class="row">
            <b>Mobile</b><span>+91 7602927810</span>
          </div>
          <div class="row">
            <b>Location</b><span>India</span>
          </div>
          <div class="row">
            <b>LeetCode + GFG</b><span>200+ DSA Problems</span>
          </div>
        </div>

        <div style="margin-top:14px;">
          <div class="title" style="margin-bottom:6px;">
            <h2>Skills</h2>
            <span class="pill">Tech Stack</span>
          </div>

          <div class="skills">
            <span class="chip">Python</span>
            <span class="chip">C / C++</span>
            <span class="chip">Java</span>
            <span class="chip">HTML</span>
            <span class="chip">CSS</span>
            <span class="chip">JavaScript</span>
            <span class="chip">Power BI</span>
            <span class="chip">MS Excel</span>
            <span class="chip">MySQL</span>
            <span class="chip">MongoDB</span>
            <span class="chip">TensorFlow</span>
            <span class="chip">PyTorch</span>
            <span class="chip">Scikit-Learn</span>
            <span class="chip">Pandas</span>
            <span class="chip">NumPy</span>
            <span class="chip">Docker</span>
            <span class="chip">AWS</span>
            <span class="chip">Git & GitHub</span>
          </div>
        </div>
      </div>

    </section>

    <!-- CERTIFICATES + ACHIEVEMENTS + EDUCATION -->
    <section class="grid">

      <div class="card">
        <div class="title">
          <h2>Certificates</h2>
          <span class="pill">Verified Learning</span>
        </div>

        <div class="list">
          <div class="item">
            <strong>Privacy & Security in Online Social Media — NPTEL</strong>
            <p>October 2025</p>
          </div>
          <div class="item">
            <strong>Generative AI Professional — Oracle</strong>
            <p>October 2025</p>
          </div>
          <div class="item">
            <strong>GenAI Powered Data Analytics Program — Tata iQ</strong>
            <p>July 2025</p>
          </div>
          <div class="item">
            <strong>Software Engineering Job Simulation — Accenture Nordics</strong>
            <p>July 2025</p>
          </div>
          <div class="item">
            <strong>Data Analytics Simulation — Deloitte Australia</strong>
            <p>June 2025</p>
          </div>
        </div>
      </div>

      <div class="card">
        <div class="title">
          <h2>Achievements & Hackathons</h2>
          <span class="pill">Highlights</span>
        </div>

        <div class="list">
          <div class="item">
            <strong>Hackathons</strong>
            <p>
              ✅ Top 5 among 100+ teams in <b>GNA Hackathon 3.0</b><br/>
              ✅ Finalist in <b>Web-A-Thon</b> with an AI-driven educational platform (250+ users)
            </p>
          </div>

          <div class="item">
            <strong>DSA Growth</strong>
            <p>
              Solved <b>200+ DSA problems</b> on LeetCode and GeeksforGeeks, improving efficiency by 40%.
            </p>
          </div>
        </div>
      </div>

    </section>

    <section class="card">
      <div class="title">
        <h2>Education</h2>
        <span class="pill">Academic Journey</span>
      </div>

      <div class="list">
        <div class="item">
          <strong>Lovely Professional University (Punjab, India)</strong>
          <p>B.Tech — Computer Science & Engineering | CGPA: <b>8.35</b> (Aug 2023 – Jul 2027)</p>
        </div>
        <div class="item">
          <strong>Khatra High School (West Bengal, India)</strong>
          <p>Intermediate | <b>83%</b> (Feb 2021 – Mar 2023)</p>
        </div>
        <div class="item">
          <strong>Khatra Sishu Niketan (West Bengal, India)</strong>
          <p>Matriculation | <b>96%</b> (Feb 2019 – Mar 2021)</p>
        </div>
      </div>
    </section>

    <div class="footer">
      © <span id="year"></span> Mouli Banerjee • Built for GitHub Portfolio
    </div>

  </div>

  <script>
    document.getElementById("year").innerText = new Date().getFullYear();
  </script>
</body>
</html>
