<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Alaparthi Hema Venkata Krishna Teja — Portfolio</title>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700;800&display=swap" rel="stylesheet">
  <style>
    :root{
      --bg:#ffffff; --text:#0b0b0b; --muted:#6b7280; --accent:#0f766e; --card:#f8fafb;
      --radius:14px; --gap:28px; --maxw:980px;
    }
    *{box-sizing:border-box}
    html,body{height:100%;margin:0;font-family:Inter,system-ui,Segoe UI,Roboto,'Helvetica Neue',Arial;background:var(--bg);color:var(--text);-webkit-font-smoothing:antialiased}
    .wrap{max-width:var(--maxw);margin:48px auto;padding:40px;background:linear-gradient(180deg,rgba(0,0,0,0.02),transparent);border-radius:20px;box-shadow:0 8px 30px rgba(11,11,11,0.06)}
    .grid{display:grid;grid-template-columns:1fr 320px;gap:var(--gap)}

    header{display:flex;align-items:center;justify-content:space-between;margin-bottom:20px}
    .brand{display:flex;gap:16px;align-items:center}
    .avatar{width:72px;height:72px;border-radius:12px;background:linear-gradient(135deg,var(--accent),#064e52);display:flex;align-items:center;justify-content:center;color:#fff;font-weight:700;font-size:20px}
    h1{font-size:26px;margin:0;letter-spacing:-0.2px}
    p.lead{margin:6px 0 0;color:var(--muted);font-weight:500}

    .card{background:var(--card);padding:20px;border-radius:12px}
    .muted{color:var(--muted);font-size:14px}

    .section{margin-bottom:18px}
    .skills{display:flex;flex-wrap:wrap;gap:10px}
    .chip{background:white;padding:8px 12px;border-radius:999px;border:1px solid rgba(11,11,11,0.06);font-weight:600;font-size:13px}

    .projects{display:grid;gap:12px}
    .project{padding:14px;border-radius:10px;border:1px solid rgba(11,11,11,0.04);background:linear-gradient(180deg,rgba(255,255,255,0.6),transparent)}
    .project h4{margin:0 0 6px}
    .project p{margin:0;color:var(--muted);font-size:14px}

    aside .meta{display:flex;flex-direction:column;gap:12px}
    .meta .item{display:flex;flex-direction:column}
    .meta .label{font-size:12px;color:var(--muted);font-weight:600}
    .meta .value{font-weight:700}

    footer{display:flex;justify-content:space-between;align-items:center;margin-top:24px;color:var(--muted);font-size:13px}

    a{color:var(--accent);text-decoration:none;font-weight:600}
    a:hover{text-decoration:underline}

    @media (max-width:900px){
      .grid{grid-template-columns:1fr;}
      .wrap{margin:20px;padding:20px}
      .avatar{width:64px;height:64px}
    }
  </style>
</head>
<body>
  <main class="wrap" role="main">
    <header>
      <div class="brand">
        <div class="avatar">AH</div>
        <div>
          <h1>Alaparthi Hema Venkata Krishna Teja</h1>
          <p class="lead">M.Tech (ECE) — Micro Electronic System Design</p>
        </div>
      </div>
      <div class="muted">ID: RA2412705010005</div>
    </header>

    <div class="grid">
      <section>
        <div class="card section">
          <h3 style="margin-top:0">About Me</h3>
          <p class="muted">I am a 2nd-year M.Tech student in Electronics and Communication Engineering with a strong interest in microelectronics, VLSI, and embedded systems. I enjoy converting theoretical concepts into working hardware prototypes and continuously improving my software skills to complement hardware design.</p>
        </div>

        <div class="card section">
          <h3 style="margin-top:0">Skills</h3>
          <div style="display:grid;grid-template-columns:1fr 1fr;gap:12px">
            <div>
              <div class="muted" style="margin-bottom:8px">Programming</div>
              <div class="skills">
                <div class="chip">Python (Basics)</div>
                <div class="chip">C Language (Basics)</div>
              </div>
            </div>
            <div>
              <div class="muted" style="margin-bottom:8px">Technical</div>
              <div class="skills">
                <div class="chip">Microelectronics</div>
                <div class="chip">VLSI</div>
                <div class="chip">Embedded Systems</div>
                <div class="chip">Circuit Design</div>
              </div>
            </div>
          </div>
        </div>

        <div class="card section">
          <h3 style="margin-top:0">Projects</h3>
          <div class="projects">
            <div class="project">
              <h4>Fire Detecting Machine</h4>
              <p>Designed a sensor-based fire detection prototype capable of identifying fire conditions and triggering alerts. Focused on safety, reliability, and real-time response.</p>
            </div>
            <div class="project">
              <h4>Mobile Jammer</h4>
              <p>Developed a controlled-range mobile signal jammer. Gained hands-on exposure to RF communication, signal interference, and regulatory considerations.</p>
            </div>
          </div>
        </div>

        <div class="card section">
          <h3 style="margin-top:0">Hackathon & Activities</h3>
          <ul style="margin:8px 0 0 18px;color:var(--muted)">
            <li>Participated in a Hackathon, collaborating in a team to ideate, design, and present a working solution under time constraints</li>
            <li>Active participant in technical events and ideathons</li>
          </ul>
        </div>

        <div class="card section">
          <h3 style="margin-top:0">Achievements & Experience</h3>
          <ul style="margin:8px 0 0 18px;color:var(--muted)">
            <li>Completed VLSI Internship (01/06/2025 – 31/07/2025)</li>
            <li>Hands-on experience in hardware prototyping and testing</li>
            <li>Strong interest in research-oriented and industry-relevant projects</li>
          </ul>
        </div>
      </section>

      <aside>
        <div class="card meta">
          <div class="item">
            <div class="label">Contact</div>
            <div class="value">
              <a href="mailto:ha5966@srmist.edu.in">ha5966@srmist.edu.in</a><br>
              <a href="tel:+918985675123">+91 8985675123</a>
            </div>
          </div>

          <div class="item">
            <div class="label">LinkedIn</div>
            <div class="value">
              <a href="https://www.linkedin.com/in/krishna-teja-alaparthi-45485b324" target="_blank">linkedin.com/in/krishna-teja-alaparthi</a>
            </div>
          </div>

          <div class="item">
            <div class="label">Location</div>
            <div class="value">Chennai, Tamil Nadu, India</div>
          </div>

          <div class="item">
            <div class="label">Education</div>
            <div class="value">M.Tech in ECE — 2nd Year</div>
          </div>

          <div class="item">
            <div class="label">Specialization</div>
            <div class="value">Micro Electronic System Design</div>
          </div>
        </div>

        <div class="card" style="margin-top:14px;text-align:center">
          <div class="muted" style="font-size:13px;margin-bottom:10px">Quick actions</div>
          <div style="display:flex;gap:10px;justify-content:center">
            <button onclick="window.print()" style="padding:10px 14px;border-radius:10px;border:0;background:var(--accent);color:#fff;font-weight:700;cursor:pointer">Print</button>
            <a href="mailto:ha5966@srmist.edu.in" style="display:inline-block;padding:10px 14px;border-radius:10px;border:1px solid rgba(0,0,0,0.06);text-decoration:none;color:var(--text);font-weight:700">Email</a>
          </div>
        </div>
      </aside>
    </div>

    <footer>
      <div>© 2025 Alaparthi Hema Venkata Krishna Teja</div>
      <div class="muted">Clean • Professional • Student Portfolio</div>
    </footer>
  </main>
</body>
</html>
