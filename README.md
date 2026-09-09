<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="Sudarshan Sugadev — SQL Performance & Data Analytics Consultant specializing in SQL Server, T-SQL, Crystal Reports and database performance.">
  <title>Sudarshan Sugadev | SQL Performance & Data Analytics Consultant</title>
  <style>
    :root{
      --bg:#f7f9fc; --surface:#ffffff; --text:#172033; --muted:#5d687b;
      --line:#e3e8f0; --accent:#2457d6; --accent2:#173b99; --dark:#0e172a;
      --radius:18px; --shadow:0 12px 35px rgba(20,35,70,.08);
    }
    *{box-sizing:border-box;scroll-behavior:smooth}
    body{margin:0;font-family:Inter,system-ui,-apple-system,Segoe UI,Roboto,Arial,sans-serif;color:var(--text);background:var(--bg);line-height:1.65}
    a{text-decoration:none;color:inherit}
    .container{width:min(1120px,92%);margin:auto}
    header{position:sticky;top:0;z-index:10;background:rgba(255,255,255,.94);backdrop-filter:blur(12px);border-bottom:1px solid var(--line)}
    nav{height:72px;display:flex;align-items:center;justify-content:space-between}
    .logo{font-weight:800;font-size:1.05rem;letter-spacing:-.02em}
    .logo span{color:var(--accent)}
    .navlinks{display:flex;gap:24px;font-size:.92rem;color:var(--muted)}
    .navlinks a:hover{color:var(--accent)}
    .menu{display:none;border:0;background:none;font-size:1.5rem}
    .hero{padding:105px 0 90px;background:linear-gradient(135deg,#f7f9fc 0%,#edf3ff 100%)}
    .eyebrow{display:inline-block;color:var(--accent);font-weight:750;font-size:.86rem;text-transform:uppercase;letter-spacing:.11em;margin-bottom:18px}
    h1{font-size:clamp(2.55rem,6vw,4.7rem);line-height:1.05;letter-spacing:-.055em;margin:0 0 24px;max-width:900px}
    .hero p{font-size:1.18rem;color:var(--muted);max-width:760px;margin:0 0 32px}
    .buttons{display:flex;gap:12px;flex-wrap:wrap}
    .btn{display:inline-block;padding:13px 20px;border-radius:11px;font-weight:700;border:1px solid transparent}
    .primary{background:var(--accent);color:#fff}.primary:hover{background:var(--accent2)}
    .secondary{background:#fff;border-color:var(--line)}.secondary:hover{border-color:#bbc7da}
    section{padding:85px 0}
    .section-head{max-width:730px;margin-bottom:38px}
    .section-head h2{font-size:2.15rem;letter-spacing:-.035em;margin:0 0 10px}
    .section-head p{color:var(--muted);margin:0}
    .grid{display:grid;grid-template-columns:repeat(3,1fr);gap:20px}
    .card{background:var(--surface);border:1px solid var(--line);border-radius:var(--radius);padding:28px;box-shadow:var(--shadow)}
    .card h3{margin:0 0 10px;font-size:1.18rem}.card p{color:var(--muted);margin:0}
    .icon{width:42px;height:42px;border-radius:12px;background:#eaf0ff;color:var(--accent);display:grid;place-items:center;font-weight:800;margin-bottom:20px}
    .skills{display:flex;flex-wrap:wrap;gap:10px}
    .tag{background:#fff;border:1px solid var(--line);padding:9px 13px;border-radius:999px;color:#465268;font-size:.9rem}
    .about{display:grid;grid-template-columns:1.15fr .85fr;gap:50px;align-items:start}
    .about h2{font-size:2.2rem;line-height:1.15;margin:0 0 18px}
    .about p{color:var(--muted)}
    .statbox{background:var(--dark);color:#fff;border-radius:var(--radius);padding:30px}
    .stat{padding:17px 0;border-bottom:1px solid rgba(255,255,255,.14)}.stat:last-child{border:0}
    .stat strong{display:block;font-size:1.55rem}.stat span{color:#b8c1d4;font-size:.9rem}
    .portfolio{grid-template-columns:repeat(3,1fr)}
    .project{overflow:hidden}.project-top{height:8px;background:var(--accent)}
    .project h3{margin-top:20px}
    .process{counter-reset:step}
    .process .card{position:relative;padding-left:78px}
    .process .card:before{counter-increment:step;content:counter(step);position:absolute;left:26px;top:28px;width:34px;height:34px;border-radius:50%;background:#eaf0ff;color:var(--accent);display:grid;place-items:center;font-weight:800}
    .contact{background:var(--dark);color:#fff}
    .contact .section-head p{color:#b8c1d4}
    .contact-grid{display:grid;grid-template-columns:1fr 1fr;gap:28px}
    .contact-card{background:#17233a;border:1px solid rgba(255,255,255,.1);padding:28px;border-radius:var(--radius)}
    .contact-card p{color:#c5cede}.contact-card a{color:#fff;font-weight:700}
    footer{background:#0a1120;color:#9da8bb;padding:25px 0;font-size:.86rem}
    footer .container{display:flex;justify-content:space-between;gap:20px}
    @media(max-width:800px){
      .navlinks{display:none}.menu{display:block}
      .grid,.portfolio,.about,.contact-grid{grid-template-columns:1fr}
      .hero{padding:75px 0 65px}section{padding:65px 0}
      footer .container{flex-direction:column}
    }
  </style>
</head>
<body>
<header>
  <div class="container">
    <nav>
      <a class="logo" href="#home">Sudarshan <span>Sugadev</span></a>
      <button class="menu" aria-label="Open menu" onclick="toggleMenu()">☰</button>
      <div class="navlinks" id="navlinks">
        <a href="#services">Services</a><a href="#about">About</a><a href="#portfolio">Portfolio</a>
        <a href="#skills">Skills</a><a href="#contact">Contact</a>
      </div>
    </nav>
  </div>
</header>

<main>
<section class="hero" id="home">
  <div class="container">
    <div class="eyebrow">SQL Performance • Reporting • Data Analytics</div>
    <h1>Make your data faster, more reliable and easier to scale.</h1>
    <p>I help businesses identify and fix SQL Server and reporting performance problems, with a strong focus on T-SQL, database optimization and Crystal Reports.</p>
    <div class="buttons">
      <a class="btn primary" href="#contact">Discuss a project</a>
      <a class="btn secondary" href="#services">Explore services</a>
    </div>
  </div>
</section>

<section id="services">
  <div class="container">
    <div class="section-head">
      <h2>Specialized services</h2>
      <p>Focused database and reporting expertise for business applications that depend on reliable, high-performing data.</p>
    </div>
    <div class="grid">
      <article class="card"><div class="icon">01</div><h3>SQL Performance</h3><p>Query optimization, execution-plan analysis, indexing, stored procedures, views, functions, troubleshooting and performance assessments.</p></article>
      <article class="card"><div class="icon">02</div><h3>Crystal Reports</h3><p>Optimize the SQL and database layer behind Crystal Reports to improve report execution time, reliability and maintainability.</p></article>
      <article class="card"><div class="icon">03</div><h3>Database Administration</h3><p>SQL Server installation, upgrades, patching, backup and recovery, security, SQL Agent jobs and production support.</p></article>
      <article class="card"><div class="icon">04</div><h3>SQL Development</h3><p>Complex T-SQL and PL/SQL development including stored procedures, functions, views and triggers.</p></article>
      <article class="card"><div class="icon">05</div><h3>Reporting & Analytics</h3><p>SQL-based reporting, reporting-query analysis, data validation and practical analytics solutions.</p></article>
      <article class="card"><div class="icon">06</div><h3>Data Engineering</h3><p>Developing modern data-engineering capability with Python, Pandas, PySpark, Spark SQL and Databricks.</p></article>
    </div>
  </div>
</section>

<section id="about" style="background:#fff">
  <div class="container about">
    <div>
      <div class="eyebrow">About</div>
      <h2>Enterprise database experience with a modern data direction.</h2>
      <p>I'm a Database Administrator and SQL Developer with 16+ years of enterprise IT experience. My background combines SQL Server administration, advanced T-SQL development, database performance tuning, backup and disaster recovery, reporting and enterprise software implementations.</p>
      <p>I have worked with mission-critical SQL Server environments and enterprise HRIS solutions, collaborating with developers, DBAs and business stakeholders to deliver scalable database and reporting solutions.</p>
      <p>My current direction is to combine this strong database foundation with modern data engineering and analytics, building a practical bridge from enterprise SQL databases to data pipelines and analytics.</p>
    </div>
    <aside class="statbox">
      <div class="stat"><strong>16+ years</strong><span>Enterprise IT experience</span></div>
      <div class="stat"><strong>SQL Server 2005–2019</strong><span>Administration & development</span></div>
      <div class="stat"><strong>Crystal Reports</strong><span>Development & optimization</span></div>
      <div class="stat"><strong>Python → PySpark</strong><span>Modern data-engineering direction</span></div>
    </aside>
  </div>
</section>

<section id="portfolio">
  <div class="container">
    <div class="section-head">
      <h2>Selected portfolio projects</h2>
      <p>These are designed as demonstration projects to show how I approach real-world performance and data problems.</p>
    </div>
    <div class="grid portfolio">
      <article class="card project"><div class="project-top"></div><h3>SQL Report Performance Optimization</h3><p>Analyze a slow business query, execution plan and indexes, then demonstrate measurable performance improvement through query and indexing changes.</p></article>
      <article class="card project"><div class="project-top"></div><h3>Crystal Reports Optimization</h3><p>Trace a slow Crystal Report through its stored procedure, joins, parameters and database objects, then optimize the underlying data retrieval.</p></article>
      <article class="card project"><div class="project-top"></div><h3>SQL → Python → PySpark Pipeline</h3><p>A transition project demonstrating extraction from SQL Server, transformation with Python/Pandas and PySpark, and preparation for analytics.</p></article>
    </div>
  </div>
</section>

<section id="skills" style="background:#fff">
  <div class="container">
    <div class="section-head"><h2>Technical skills</h2><p>Core technologies and capabilities currently represented in my professional background.</p></div>
    <div class="skills">
      <span class="tag">Microsoft SQL Server</span><span class="tag">T-SQL</span><span class="tag">Oracle PL/SQL</span>
      <span class="tag">SQL Performance Tuning</span><span class="tag">Query Optimization</span><span class="tag">Indexing</span>
      <span class="tag">Stored Procedures</span><span class="tag">Functions</span><span class="tag">Views</span>
      <span class="tag">Triggers</span><span class="tag">Backup & Restore</span><span class="tag">Disaster Recovery</span>
      <span class="tag">SQL Server Agent</span><span class="tag">Security & Permissions</span><span class="tag">Crystal Reports</span>
      <span class="tag">Reporting Optimization</span><span class="tag">SSMS</span><span class="tag">Oracle SQL Developer</span>
      <span class="tag">On-Prem & Cloud Environments</span><span class="tag">Python</span><span class="tag">Pandas</span>
      <span class="tag">PySpark</span><span class="tag">Spark SQL</span><span class="tag">Databricks</span>
    </div>
  </div>
</section>

<section class="contact" id="contact">
  <div class="container">
    <div class="section-head">
      <div class="eyebrow">Let's talk</div>
      <h2>Have a slow query or reporting problem?</h2>
      <p>Tell me what is slow, what database you are using, and what you have already tried. We can start by understanding the bottleneck.</p>
    </div>
    <div class="contact-grid">
      <div class="contact-card">
        <h3>Email</h3>
        <p>For consulting and project enquiries:</p>
        <a href="mailto:sudarshan.sugadev@gmail.com">sudarshan.sugadev@gmail.com</a>
      </div>
      <div class="contact-card">
        <h3>Professional profiles</h3>
        <p>Connect with me or view my freelance profile.</p>
        <div class="buttons">
          <a class="btn secondary" href="https://www.linkedin.com/in/sudarshan-sugadev-1080b056" target="_blank" rel="noopener">LinkedIn</a>
          <a class="btn secondary" href="#" onclick="alert('Replace this button with your Upwork profile URL before publishing.');return false;">Upwork</a>
        </div>
      </div>
    </div>
  </div>
</section>
</main>

<footer>
  <div class="container">
    <span>© <span id="year"></span> Sudarshan Sugadev. All rights reserved.</span>
    <span>SQL Performance • Reporting • Data Analytics</span>
  </div>
</footer>

<script>
  document.getElementById("year").textContent = new Date().getFullYear();
  function toggleMenu(){
    const n=document.getElementById("navlinks");
    n.style.display=n.style.display==="flex"?"none":"flex";
    n.style.position="absolute"; n.style.right="4%"; n.style.top="65px";
    n.style.background="#fff"; n.style.padding="18px"; n.style.border="1px solid #e3e8f0";
    n.style.borderRadius="12px"; n.style.flexDirection="column"; n.style.boxShadow="0 12px 30px rgba(0,0,0,.1)";
  }
</script>
</body>
</html>
