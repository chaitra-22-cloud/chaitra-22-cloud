<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Chaitra Naik | Resume</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap" rel="stylesheet">
  <style>
    *{
      margin:0;
      padding:0;
      box-sizing:border-box;
      font-family:'Poppins',sans-serif;
    }

    body{
      background:linear-gradient(135deg,#fdfbfb,#ebedee);
      color:#333;
      padding:40px;
    }

    .resume{
      max-width:1100px;
      margin:auto;
      background:#fff;
      border-radius:25px;
      overflow:hidden;
      box-shadow:0 10px 35px rgba(0,0,0,0.15);
      display:grid;
      grid-template-columns:320px 1fr;
    }

    .left{
      background:linear-gradient(180deg,#ff9a9e,#fad0c4);
      color:#fff;
      padding:40px 30px;
    }

    .profile{
      text-align:center;
      margin-bottom:35px;
    }

    .profile img{
      width:140px;
      height:140px;
      border-radius:50%;
      border:5px solid white;
      object-fit:cover;
      margin-bottom:15px;
    }

    .profile h1{
      font-size:30px;
      font-weight:700;
    }

    .profile p{
      font-size:15px;
      margin-top:8px;
    }

    .section{
      margin-bottom:35px;
    }

    .section h2{
      font-size:20px;
      margin-bottom:15px;
      border-bottom:2px solid rgba(255,255,255,0.4);
      padding-bottom:8px;
    }

    .section p,
    .section li{
      font-size:14px;
      line-height:1.8;
      list-style:none;
    }

    .skills span{
      display:inline-block;
      background:rgba(255,255,255,0.25);
      padding:8px 14px;
      border-radius:30px;
      margin:6px 4px;
      font-size:13px;
      backdrop-filter:blur(5px);
    }

    .right{
      padding:45px;
    }

    .title{
      margin-bottom:30px;
    }

    .title h2{
      font-size:34px;
      color:#ff758c;
      margin-bottom:10px;
    }

    .title p{
      font-size:15px;
      line-height:1.8;
      color:#555;
    }

    .card{
      background:#fff;
      border-left:5px solid #ff758c;
      padding:22px;
      margin-bottom:25px;
      border-radius:18px;
      box-shadow:0 5px 18px rgba(0,0,0,0.08);
      transition:0.3s;
    }

    .card:hover{
      transform:translateY(-5px);
    }

    .card h3{
      color:#ff758c;
      margin-bottom:10px;
      font-size:22px;
    }

    .card p{
      font-size:15px;
      line-height:1.9;
      color:#555;
    }

    .project-list li{
      margin-bottom:10px;
      margin-left:20px;
      color:#444;
    }

    .achievement{
      background:linear-gradient(135deg,#ffecd2,#fcb69f);
      padding:20px;
      border-radius:18px;
      margin-top:20px;
      box-shadow:0 5px 15px rgba(0,0,0,0.08);
    }

    .achievement h3{
      color:#ff5e78;
      margin-bottom:10px;
    }

    .footer{
      text-align:center;
      margin-top:25px;
      color:#888;
      font-size:14px;
    }

    @media(max-width:900px){
      .resume{
        grid-template-columns:1fr;
      }

      .right{
        padding:30px;
      }
    }
  </style>
</head>
<body>

  <div class="resume">

    <div class="left">

      <div class="profile">
        <img src="https://i.pinimg.com/736x/f2/22/0d/f2220df5f6496df19d1bff2b2fbbf6b6.jpg" alt="profile">
        <h1>Chaitra Naik</h1>
        <p>MCA Student • Web Developer</p>
      </div>

      <div class="section">
        <h2>Contact</h2>
        <p>Karnataka, India</p>
        <p>naikchaitra28@gmail.com</p>
        <p> +91 XXXXX XXXXX</p>
        <p> github.com/chaitra</p>
      </div>

      <div class="section">
        <h2>Skills</h2>
        <div class="skills">
          <span>HTML5</span>
          <span>CSS3</span>
          <span>JavaScript</span>
          <span>MySQL</span>
          <span>Python</span>
        </div>
      </div>

      <div class="section">
        <h2>Languages</h2>
        <ul>
          <li>English</li>
          <li>Hindi</li>
          <li>Kannada</li>
           <li>Konkani</li>
        </ul>
      </div>

      <div class="section">
        <h2>Hobbies</h2>
        <ul>
          <li>Web Designing</li>
          <li> Listening Music</li>
          <li>Creative Editing</li>
        </ul>
      </div>

    </div>

    <div class="right">

      <div class="title">
        <h2>Career Objective</h2>
        <p>
          Passionate MCA student with strong interest in modern web development and cloud computing. 
          Dedicated to building responsive and user-friendly applications with innovative ideas and attractive interfaces.
        </p>
      </div>

      <div class="card">
        <h3>Education</h3>
        <p>
          <strong>Master of Computer Applications (MCA)</strong><br>
          Pursuing MCA with specialization in cloud computing and web technologies.
        </p>
      </div>

      <div class="card">
        <h3> Major Project</h3>
        <p><strong>Event Management System</strong></p>

        <ul class="project-list">
          <li>Developed a complete event booking platform for weddings and birthday events.</li>
          <li>Implemented catering cart system with dynamic price updates.</li>
          <li>Created attractive decoration gallery with booking functionality.</li>
          <li>Used LocalStorage for storing cart items dynamically.</li>
          <li>Designed responsive pages using HTML, CSS and JavaScript.</li>
          <li>Integrated user profile management and booking confirmation system.</li>
        </ul>
      </div>

      <div class="card">
        <h3>Technical Highlights</h3>
        <p>
          ✔ Responsive Website Design<br>
          ✔ Dynamic Cart Functionality<br>
          ✔ User Interface Designing<br>
          ✔ Frontend Development<br>
          ✔ Database Connectivity Basics
        </p>
      </div>

      <div class="achievement">
        <h3> Achievement Goal</h3>
        <p>
          My goal is to become a skilled Cloud Computing professional and develop secure, scalable, and efficient cloud-based solutions for modern applications.</p>
      </div>

      <div class="footer">
        Designed with ❤ by Chaitra Naik
      </div>

    </div>

  </div>

</body>
</html>

