<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Krishna Teja | Portfolio</title>

  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700;800&display=swap" rel="stylesheet">

  <style>
    :root{
      --bg:#f9fafb;
      --card:#ffffff;
      --text:#0f172a;
      --muted:#6b7280;
      --accent:#0f766e;
    }

    *{box-sizing:border-box}

    body{
      margin:0;
      font-family:Inter,system-ui,Arial;
      background:var(--bg);
      color:var(--text);
    }

    .container{
      max-width:900px;
      margin:40px auto;
      padding:24px;
    }

    .card{
      background:var(--card);
      border-radius:16px;
      padding:28px;
      box-shadow:0 10px 30px rgba(0,0,0,0.06);
      margin-bottom:24px;
    }

    header{
      display:flex;
      justify-content:space-between;
      align-items:center;
      flex-wrap:wrap;
      gap:16px;
    }

    h1{
      margin:0;
      font-size:28px;
      font-weight:800;
    }

    .subtitle{
      color:var(--muted);
      margin-top:6px;
      font-weight:500;
    }

    .links a{
      margin-right:14px;
      text-decoration:none;
      color:var(--accent);
      font-weight:600;
    }

    h2{
      margin-top:0;
      font-size:20px;
      border-left:4px solid var(--accent);
      padding-left:10px;
    }

    p{line-height:1.6;color:var(--muted)}

    ul{padding-left:18px;color:var(--muted)}

    .grid{
      display:grid;
      grid-template-columns:1fr 1fr;
      gap:20px;
    }

    .tag{
      display:inline-block;
      background:#ecfeff;
      color:#155e75;
      padding:6px 12px;
      border-radius:999px;
      font-size:13px;
      font-weight:600;
      margin:4px 6px 0 0;
    }

    footer{
      text-align:center;
      color:var(--muted);
      font-size:13px;
      margin-top:20px;
    }

    @media(max-width:700px){
      .grid{grid-template-columns:1fr}
    }
  </style>
</head>

<body>
  <main class="container">

    <!-- HEADER -->
    <div class="card">
      <header>
        <div>
          <h1>Alaparthi Hema Venkata Krishna Teja</h1>
          <div class="subtitle">
            M.Tech (ECE) — Micro Electronic System Design
          </div>
        </div>

        <div class="links">
          <a href="mailto:ha5966@srmist.edu.in">Email</a>
          <a href="https://www.linkedin.com/in/krishna-teja-alaparthi-45485b324" target="_blank">LinkedIn</a>
        </div>
      </header>
    </div>

    <!-- ABOUT -->
    <div class="card">
      <h2>About Me</h2>
      <p>
        I am a 2nd-year M.Tech student in Electronics and Communication Engineering
        with a specialization in Micro Electronic System Design. I am passionate
        about VLSI, embedded systems, and building practical hardware solutions.
        I enjoy applying theoretical concepts to real-world projects and
        continuously upgrading my technical skill set.
      </p>
    </div>

    <!-- SKILLS -->
    <div class="card">
      <h2>Skills</h2>
      <span class="tag">Microelectronics</span>
      <span class="tag">VLSI</span>
      <span class="tag">Embedded Systems</span>
      <span class="tag">Circuit Design</span>
      <span class="tag">Python (Basics)</span>
      <span class="tag">C Language (Basics)</span>
    </div>

    <!-- PROJECTS -->
    <div class="card">
      <h2>Projects</h2>
      <ul>
        <li>
          <strong>Fire Detecting Machine:</strong>
          Sensor-based fire detection system designed for early warning and safety.
        </li>
        <li>
          <strong>Mobile Jammer:</strong>
          Controlled-range RF signal jammer providing hands-on exposure to
          wireless communication and interference concepts.
        </li>
      </ul>
    </div>

    <!-- EXPERIENCE -->
    <div class="card">
      <h2>Experience & Activities</h2>
      <ul>
        <li>VLSI Internship (June 2025 – July 2025)</li>
        <li>Participated in Hackathon & Ideathon events</li>
        <li>Active involvement in hardware-based prototyping</li>
      </ul>
    </div>

    <footer>
      © 2025 • Krishna Teja • GitHub Pages Portfolio
    </footer>

  </main>
</body>
</html>
