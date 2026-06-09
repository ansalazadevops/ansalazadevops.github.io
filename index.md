<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Antonio Salazar Gomez — DevOps Engineer</title>
<style>
  :root{
    --ink:#1c2530;
    --muted:#5a6675;
    --accent:#1f3a5f;
    --accent-soft:#33567f;
    --rule:#d9dee5;
    --bg:#ffffff;
    --tag-bg:#eef2f7;
  }
  *{box-sizing:border-box;}
  html{-webkit-text-size-adjust:100%;}
  body{
    margin:0;
    background:#eceff3;
    color:var(--ink);
    font-family:"Segoe UI",-apple-system,BlinkMacSystemFont,"Helvetica Neue",Arial,sans-serif;
    font-size:14px;
    line-height:1.55;
  }
  .page{
    max-width:850px;
    margin:32px auto;
    background:var(--bg);
    padding:56px 60px;
    box-shadow:0 6px 28px rgba(20,30,45,.12);
    border-radius:4px;
  }

  /* ---------- Header ---------- */
  .contact{
    font-size:11.5px;
    color:var(--muted);
    text-align:center;
    letter-spacing:.2px;
    line-height:1.8;
    margin-bottom:18px;
  }
  .contact a{color:var(--accent-soft);text-decoration:none;}
  .contact a:hover{text-decoration:underline;}
  .contact .sep{color:var(--rule);margin:0 6px;}

  .name{
    text-align:center;
    font-size:34px;
    font-weight:700;
    color:var(--accent);
    letter-spacing:.5px;
    margin:6px 0 2px;
  }
  .role{
    text-align:center;
    font-size:17px;
    font-weight:600;
    color:var(--accent-soft);
    margin:0 0 14px;
  }
  .rule-top,.rule-bottom{border:0;border-top:2px solid var(--accent);margin:10px 0;}

  .skills-line{
    text-align:center;
    font-weight:600;
    font-size:12.5px;
    color:var(--ink);
    margin:4px 0;
  }
  .skills-line.second{margin-bottom:18px;}

  .summary p{margin:0 0 12px;color:#2b3645;}
  .summary strong{color:var(--ink);}

  /* ---------- Section titles ---------- */
  .section-title{
    display:flex;
    align-items:center;
    justify-content:center;
    gap:18px;
    color:var(--accent);
    font-size:21px;
    font-weight:700;
    margin:30px 0 16px;
  }
  .section-title::before,
  .section-title::after{
    content:"";
    height:2px;
    background:var(--accent);
    flex:1;
    max-width:120px;
    opacity:.55;
  }

  /* ---------- Experience ---------- */
  .job{margin-bottom:22px;}
  .job-head{
    display:flex;
    justify-content:space-between;
    align-items:baseline;
    border-bottom:1.5px solid var(--accent);
    padding-bottom:3px;
    gap:12px;
  }
  .company{font-weight:700;color:var(--accent);font-size:15px;}
  .location{font-weight:600;font-style:italic;color:var(--ink);font-size:13px;}
  .dates{font-weight:700;color:var(--ink);font-size:13px;white-space:nowrap;}
  .position{font-weight:700;margin:6px 0 4px;font-size:13.5px;}
  .role-goal{font-weight:700;margin:4px 0 8px;color:#2b3645;}
  .lead{font-weight:600;margin:4px 0 8px;color:#2b3645;}

  ul{margin:6px 0;padding-left:20px;}
  li{margin-bottom:6px;color:#2b3645;}
  li strong{color:var(--ink);}

  .achievement-line{
    margin-top:8px;
    color:#2b3645;
  }
  .achievement-line strong{color:var(--ink);}

  /* ---------- Achievements / Education ---------- */
  .plain-list{padding-left:20px;}
  .plain-list li{font-weight:600;color:#2b3645;}

  .edu-list li{font-weight:600;}
  .edu-list .meta{font-weight:400;color:var(--muted);}

  .tools-list li strong{color:var(--accent);}
  .tools-list .meta{color:#2b3645;}

  /* ---------- Print ---------- */
  @media print{
    body{background:#fff;font-size:11px;}
    .page{box-shadow:none;margin:0;max-width:100%;padding:28px 34px;border-radius:0;}
    .name{font-size:28px;}
    .section-title{font-size:18px;}
    .job{break-inside:avoid;}
    a{color:var(--accent-soft);}
  }
  @media (max-width:640px){
    .page{padding:30px 22px;margin:0;border-radius:0;}
    .name{font-size:26px;}
    .job-head{flex-wrap:wrap;}
  }
</style>
</head>
<body>
<main class="page">

  <!-- Contact -->
  <div class="contact">
    <a href="mailto:jobs.antonio.salazar@gmail.com">jobs.antonio.salazar@gmail.com</a>
    <span class="sep">|</span>
    <a href="tel:+523338154216">+52 333 815 4216</a>
    <span class="sep">|</span>
    <a href="https://www.linkedin.com/in/antonio-salazar-gomez/" target="_blank" rel="noopener">linkedin.com/in/antonio-salazar-gomez</a>
    <span class="sep">|</span>
    Guadalajara, Mexico
    <span class="sep">|</span>
    On-site · Hybrid · Remote
  </div>

  <hr class="rule-top">
  <h1 class="name">Antonio Salazar Gomez</h1>
  <p class="role">DevOps Engineer</p>
  <hr class="rule-bottom">

  <p class="skills-line">Customer satisfaction focus | Problem-solving | Teamwork and collaboration | Effective communication</p>
  <p class="skills-line second">CI/CD | Configuration Management | Infrastructure as code | Container Orchestration | Active monitoring | Agile methodology</p>

  <!-- Summary -->
  <section class="summary">
    <p>I am passionate about both computer and piano keyboards, blending IT expertise with a love for music. I prioritize problem-solving, continuous improvement, teamwork, and delivering high-quality service to support organizational goals.</p>
    <p>My passion for computers inspired me to pursue a degree in Computer Science Engineering. <strong>With over 25 years in IT,</strong> I have held diverse roles—from Web Developer to Oracle DBA, and now DevOps Engineer, a role I truly enjoy. I focus on streamlining processes, reducing time and costs, and enhancing service quality. In my most recent project <strong>At Oracle, I achieved a 40% cost reduction, reduced manual task time by 20%, and maintained 99% operational availability.</strong></p>
    <p>As a collaborative partner, I value active listening and building long-term trust with colleagues, cross-functional teams, clients, and vendors.</p>
  </section>

  <!-- Work Experience -->
  <h2 class="section-title">Work Experience</h2>

  <article class="job">
    <div class="job-head">
      <span><span class="company">ORACLE</span> <span class="location">Guadalajara, Mexico</span></span>
      <span class="dates">2021–2026</span>
    </div>
    <p class="position">Principal DevOps Engineer</p>
    <p class="role-goal">Role goal: automate, streamline, and stabilize the software delivery lifecycle to make builds faster, releases safer, and maintenance easier.</p>
    <ul>
      <li><strong>CI/CD Pipelines:</strong> Maintained high-performing Jenkins pipelines, consistently met KPIs, ensured code and artifact integration, and proactively supported customers and QA teams in troubleshooting failed jobs.</li>
      <li><strong>Infrastructure Management (IaC):</strong> Helped deploy and manage Big Data clusters on OCI, cutting costs by 40% through efficient provisioning, decommissioning unused resources, and automation with Terraform and Jenkins-driven workflows.</li>
      <li><strong>Automation:</strong> Delivered automation solutions, including a BASH script that reduced YARN log retrieval time by 15%, and pioneered a containerized Hadoop Edge node plus CI/CD pipelines for Oozie jobs, reducing deployment and execution time by 20%.</li>
      <li><strong>Monitoring &amp; Logging:</strong> Implemented a real-time alerting system with Ambari, Prometheus, and Slack, improving cluster availability by 10% and helping prevent failures.</li>
      <li><strong>Security &amp; Compliance (DevSecOps):</strong> Kept operations aligned with security policies and worked with security teams to resolve Kerberos and LDAP issues, supporting secure and compliant operations.</li>
      <li><strong>Cross-Team Collaboration:</strong> Acted as a liaison across infrastructure, engineering, security, and business teams, resolving complex issues and communicating key updates to stakeholders.</li>
      <li><strong>Deployment &amp; Release Management:</strong> Supported code reviews and coordinated deployments of Big Data applications and infrastructure components to keep releases smooth and systems consistent.</li>
      <li><strong>System Reliability &amp; Performance:</strong> Maintained 99% cluster uptime through proactive monitoring, SLA-driven incident management, and planned maintenance, while keeping technical documentation current.</li>
    </ul>
    <p class="achievement-line"><strong>Achievements:</strong> Met CI/CD KPIs, reduced infrastructure costs by 40%, reduced deployment/execution time by 20%, improved availability with alerting, and ensured secure, reliable operations across teams.</p>
  </article>

  <article class="job">
    <div class="job-head">
      <span><span class="company">TOSHIBA Global Commerce Solutions</span> <span class="location">Guadalajara, Mexico</span></span>
      <span class="dates">2021–2022</span>
    </div>
    <p class="position">DevOps Engineer</p>
    <p class="lead">Accelerate software release life cycle and support applications running on Azure infrastructure</p>
    <ul>
      <li>Created virtual working environments for development teams using oVirt.</li>
      <li>Automated software builds with Jenkins pipelines, utilizing Groovy, Python, Ansible, GitLab, BASH, MS Batch scripting, Maven, and Docker.</li>
      <li>Monitored critical builds and promptly resolved failed processes.</li>
      <li>Maintained comprehensive documentation of processes, configurations, troubleshooting steps, architecture, and performance reports.</li>
      <li>Monitored applications running on Azure Web Services and reported monthly costs.</li>
    </ul>
    <p class="achievement-line"><strong>Achievements:</strong> Maintained optimal operations with 100% build completion, continuous application uptime, and all deployments delivered on schedule.</p>
  </article>

  <article class="job">
    <div class="job-head">
      <span><span class="company">Caltech Center for Technology and Management Education</span> <span class="location">California, US</span></span>
      <span class="dates">2021–2022</span>
    </div>
    <p class="position">Post Graduate Program in DevOps</p>
    <p class="lead">Capstone Project – AWS, Kubernetes, CI/CD: Designed and deployed a highly available e-commerce application infrastructure on AWS using Kubernetes and DevOps automation practices.</p>
    <ul>
      <li>Provisioned and configured a highly available AWS environment using EC2, Elastic Load Balancer (ELB), and Elastic IPs.</li>
      <li>Automated infrastructure provisioning and configuration through Jenkins CI/CD pipelines and Ansible playbooks.</li>
      <li>Installed and configured Docker and Kubernetes across the cluster.</li>
      <li>Implemented Kubernetes network policies to secure database access by allowing traffic only from authorized application pods.</li>
      <li>Managed Kubernetes RBAC by creating users and assigning permissions for pod lifecycle operations.</li>
      <li>Deployed and configured containerized applications within Kubernetes pods.</li>
      <li>Created ETCD database snapshots to support backup and disaster recovery processes.</li>
      <li>Configured Kubernetes auto-scaling policies based on CPU and memory utilization thresholds.</li>
      <li>Monitored cluster health, resource utilization, and performance using AWS CloudWatch.</li>
    </ul>
    <p class="achievement-line"><strong>Achievement:</strong> Successfully delivered a production-style, highly available Kubernetes environment, meeting all project requirements and documenting deployment, security, backup, and operational procedures.</p>
  </article>

  <article class="job">
    <div class="job-head">
      <span><span class="company">ORACLE</span> <span class="location">Guadalajara, Mexico</span></span>
      <span class="dates">2011–2021</span>
    </div>
    <p class="position">DBA / IT Consultant / DevOps Engineer</p>
    <ul>
      <li><strong>DevOps Engineer (2020–2021):</strong> Implemented automation and CI/CD solutions to enhance the application lifecycle.</li>
      <li><strong>IT Consultant (2018–2020):</strong> Supported operations of applications running on Oracle Cloud Infrastructure (OCI) and served as Application Subject Matter Expert (SME).</li>
      <li><strong>Database Administrator (2011–2018):</strong> Managed infrastructure operations for Oracle databases.</li>
    </ul>
    <p class="achievement-line"><strong>Achievements:</strong> As a DBA, implemented best practices to ensure 99% database availability, including redundancy, high availability, backups, recovery, and security. As an IT Consultant, developed a framework with automated processes enabling non-DBA engineers to monitor and resolve common critical database issues.</p>
  </article>

  <!-- Achievements -->
  <h2 class="section-title">Achievements</h2>
  <ul class="plain-list">
    <li>In Fiscal Year 2025, received the Excellence Award for developing a Proof of Concept for multiregional Big Data Clusters running on OCI, in collaboration with cross-functional teams.</li>
    <li>Achieved 99% system availability in every project by implementing IT best practices.</li>
    <li>Successfully completed all deployments on schedule throughout my career.</li>
  </ul>

  <!-- Education -->
  <h2 class="section-title">Education</h2>
  <ul class="edu-list">
    <li>Post Graduate Program in DevOps <span class="meta">| SimpliLearn/Caltech University | 2021 | certificate code 3042029</span></li>
    <li>Master of Science in Database Administration <span class="meta">| Universidad de Guadalajara | 2007</span></li>
    <li>Bachelor of Science in Computer Science <span class="meta">| Universidad del Valle de Atemajac | 1996 | cedula 4761084</span></li>
    <li>Bachelor of Music Specialized in Piano <span class="meta">| Universidad de Guadalajara | 1995 | degree ID IM/EXA/001/13</span></li>
    <li>Languages <span class="meta">| Spanish (native tongue) | English (fluent)</span></li>
  </ul>

  <!-- Tools -->
  <h2 class="section-title">Tools</h2>
  <ul class="tools-list">
    <li><strong>DevOps Tools</strong> <span class="meta">| Ansible | Docker | Git/GitHub | GitLab | Jenkins | Kubernetes | Terraform | Visual Studio Code</span></li>
    <li><strong>Programming and Scripting Languages</strong> <span class="meta">| BASH | HTML | JSON | Markdown | Python | PL/SQL | SQL | XML</span></li>
    <li><strong>Oracle DB Components and Tools</strong> <span class="meta">| ASM | RAC | Data Guard | RMAN | ADRCI | DG Broker | SQL Developer | SQLcl | SQL*Plus</span></li>
    <li><strong>Cloud Infrastructure Platforms</strong> <span class="meta">| OCI | AWS | Azure</span></li>
    <li><strong>Monitoring tools</strong> <span class="meta">| Grafana | Oracle Enterprise Manager | CloudWatch</span></li>
  </ul>

</main>
</body>
</html>
