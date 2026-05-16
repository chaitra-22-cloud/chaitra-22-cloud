<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Chaitra Naik | Portfolio Resume</title>

  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap" rel="stylesheet">

  <style>

    *{
      margin:0;
      padding:0;
      box-sizing:border-box;
      font-family:'Poppins',sans-serif;
      scroll-behavior:smooth;
    }

    body{
      background:#0f172a;
      color:white;
      overflow-x:hidden;
    }

    .container{
      width:100%;
      min-height:100vh;
      padding:40px 8%;
      background:linear-gradient(135deg,#0f172a,#1e293b,#111827);
    }

    nav{
      display:flex;
      justify-content:space-between;
      align-items:center;
      margin-bottom:60px;
    }

    .logo{
      font-size:32px;
      font-weight:700;
      color:#38bdf8;
    }

    nav ul{
      display:flex;
      gap:25px;
      list-style:none;
    }

    nav ul li a{
      text-decoration:none;
      color:white;
      transition:0.3s;
      font-size:15px;
    }

    nav ul li a:hover{
      color:#38bdf8;
    }

    .hero{
      display:grid;
      grid-template-columns:1fr 400px;
      gap:60px;
      align-items:center;
      margin-bottom:80px;
    }

    .hero-text h1{
      font-size:65px;
      line-height:1.2;
      margin-bottom:20px;
    }

    .hero-text span{
      color:#38bdf8;
    }

    .hero-text p{
      color:#cbd5e1;
      line-height:1.9;
      font-size:16px;
      margin-bottom:30px;
    }

    .btn{
      display:inline-block;
      padding:14px 32px;
      background:#38bdf8;
      color:#0f172a;
      border-radius:40px;
      text-decoration:none;
      font-weight:600;
      transition:0.3s;
      box-shadow:0 0 25px rgba(56,189,248,0.5);
    }

    .btn:hover{
      transform:translateY(-5px);
    }

    .hero-image{
      position:relative;
      display:flex;
      justify-content:center;
    }

    .hero-image img{
      width:350px;
      height:350px;
      border-radius:50%;
      object-fit:cover;
      border:8px solid rgba(56,189,248,0.4);
      box-shadow:0 0 40px rgba(56,189,248,0.5);
    }

    .section-title{
      font-size:38px;
      margin-bottom:40px;
      text-align:center;
      color:#38bdf8;
    }

    .cards{
      display:grid;
      grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
      gap:25px;
      margin-bottom:80px;
    }

    .card{
      background:rgba(255,255,255,0.05);
      padding:30px;
      border-radius:25px;
      backdrop-filter:blur(10px);
      border:1px solid rgba(255,255,255,0.08);
      transition:0.4s;
      box-shadow:0 10px 30px rgba(0,0,0,0.2);
    }

    .card:hover{
      transform:translateY(-10px);
      border-color:#38bdf8;
    }

    .card h3{
      margin-bottom:18px;
      color:#38bdf8;
      font-size:24px;
    }

    .card p,
    .card li{
      color:#cbd5e1;
      line-height:1.8;
      font-size:15px;
    }

    .skills{
      display:flex;
      flex-wrap:wrap;
      gap:12px;
      margin-top:15px;
    }

    .skills span{
      background:#38bdf8;
      color:#0f172a;
      padding:10px 18px;
      border-radius:30px;
      font-weight:600;
      font-size:14px;
    }

    .project{
      background:linear-gradient(135deg,#1e293b,#0f172a);
      padding:40px;
      border-radius:25px;
      margin-bottom:80px;
      box-shadow:0 10px 30px rgba(0,0,0,0.25);
    }

    .project h2{
      color:#38bdf8;
      margin-bottom:20px;
      font-size:35px;
    }

    .project p{
      color:#cbd5e1;
      line-height:2;
      margin-bottom:20px;
    }

    .project ul{
      margin-left:20px;
    }

    .project ul li{
      margin-bottom:12px;
      color:#e2e8f0;
      line-height:1.8;
    }

    .footer{
      text-align:center;
      padding:30px;
      color:#94a3b8;
      border-top:1px solid rgba(255,255,255,0.1);
    }

    @media(max-width:950px){

      .hero{
        grid-template-columns:1fr;
        text-align:center;
      }

      .hero-text h1{
        font-size:45px;
      }

      .hero-image img{
        width:280px;
        height:280px;
      }

      nav{
        flex-direction:column;
        gap:20px;
      }

      nav ul{
        flex-wrap:wrap;
        justify-content:center;
      }

    }

  </style>
</head>
<body>

  <div class="container">

    <nav>
      <div class="logo">Chaitra.</div>

      <ul>
        <li><a href="#about">About</a></li>
        <li><a href="#skills">Skills</a></li>
        <li><a href="#project">Project</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>


    <section class="hero" id="about">

      <div class="hero-text">

        <h1>Hello, I'm <span>Chaitra Naik</span></h1>

        <p>
          MCA student passionate about Cloud Computing, Web Development, and UI Designing.
          I love creating attractive, responsive, and user-friendly web applications with modern technologies.
          My goal is to build innovative cloud-based solutions that solve real-world problems.
        </p>

        <a href="#project" class="btn">View Project</a>

      </div>

      <div class="hero-image">

        <img src="https://i.pinimg.com/736x/f2/22/0d/f2220df5f6496df19d1bff2b2fbbf6b6.jpg" alt="Profile Image">

      </div>

    </section>


    <h2 class="section-title" id="skills">My Skills</h2>

    <div class="cards">

      <div class="card">

        <h3>Frontend</h3>

        <p>
          Creating responsive and visually attractive websites using modern frontend technologies.
        </p>

        <div class="skills">
          <span>HTML5</span>
          <span>CSS3</span>
          <span>JavaScript</span>
        </div>

      </div>

      <div class="card">

        <h3>Backend</h3>

        <p>
          Basic backend development and database connectivity for dynamic web applications.
        </p>

        <div class="skills">
          <span>PHP</span>
          <span>MySQL</span>
          <span>Python</span>
        </div>

      </div>

      <div class="card">

        <h3>Cloud & Tools</h3>

        <p>
          Learning cloud computing concepts and using modern tools for development.
        </p>

        <div class="skills">
          <span>Cloud Basics</span>
          <span>GitHub</span>
          <span>UI Design</span>
        </div>

      </div>

    </div>


    <section class="project" id="project">

      <h2>🚀 Major Project</h2>

      <p>
        <strong>Event Management System</strong>
      </p>

      <ul>
        <li>Developed a web-based event booking platform for weddings and birthday events.</li>

        <li>Implemented catering cart system with dynamic item updates.</li>

        <li>Created decoration gallery with booking functionality.</li>

        <li>Designed responsive UI using HTML, CSS, and JavaScript.</li>

        <li>Integrated LocalStorage for dynamic cart management.</li>

        <li>Added booking confirmation and user profile features.</li>
      </ul>

    </section>


    <h2 class="section-title">Education</h2>

    <div class="cards">

      <div class="card">

        <h3>🎓 MCA</h3>

        <p>
          Pursuing Master of Computer Applications with specialization in Cloud Computing and Web Technologies.
        </p>

      </div>

      <div class="card">

        <h3>🌐 Career Goal</h3>

        <p>
          To become a professional Cloud Computing engineer and develop secure, scalable, and innovative cloud-based applications.
        </p>

      </div>

      <div class="card">

        <h3>💡 Interests</h3>

        <p>
          UI Designing, Cloud Technologies, Frontend Development, Creative Web Interfaces, and Modern Applications.
        </p>

      </div>

    </div>


    <h2 class="section-title" id="contact">Contact</h2>

    <div class="cards">

      <div class="card">

        <h3>📧 Email</h3>

        <p>chaitra@email.com</p>

      </div>

      <div class="card">

        <h3>💻 GitHub</h3>

        <p>github.com/chaitra</p>

      </div>

      <div class="card">

        <h3>📍 Location</h3>

        <p>Karnataka, India</p>

      </div>

    </div>


    <div class="footer">
      Designed with ❤ by Chaitra Naik
    </div>

  </div>

</body>
</html>
