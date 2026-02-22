# hazad-professional
Create new repository 
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Abdul Hazad | Automotive & Logistics Professional </title>
<meta name="description" content="Abdul Hazad is a Dubai-based professional specializing in automotive logistics, vehicle transportation, and office support services. Reliable and disciplined.">

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">
<link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css" rel="stylesheet">

<style>
:root {
  --primary: #2563EB;
  --black: #0B0B0B;
  --white: #FFFFFF;
  --glass: rgba(255,255,255,0.08);
}

* { margin:0; padding:0; box-sizing:border-box; }

body {
  font-family:'Poppins', sans-serif;
  background: var(--black);
  color: var(--white);
  line-height:1.6;
  scroll-behavior:smooth;
}

header {
  min-height:100vh;
  display:flex;
  flex-direction:column;
  justify-content:center;
  align-items:center;
  text-align:center;
  padding:20px;
  background: linear-gradient(145deg,#0B0B0B,#111827);
}

header img {
  width:170px;
  height:170px;
  border-radius:50%;
  object-fit:cover;
  border:3px solid var(--primary);
  box-shadow:0 0 40px rgba(37,99,235,0.5);
  margin-bottom:25px;
  animation: fadeIn 1.5s ease forwards;
}

header h1 {
  font-size:36px;
  font-weight:700;
  margin-bottom:15px;
}

header h1 span {
  color:var(--primary);
}

header p {
  max-width:600px;
  opacity:0.85;
  margin-bottom:30px;
}

.btn {
  padding:12px 30px;
  border-radius:30px;
  text-decoration:none;
  font-weight:500;
  margin:10px;
  transition:0.3s ease;
  display:inline-block;
}

.btn-primary {
  background:var(--primary);
  color:#fff;
  box-shadow:0 0 15px rgba(37,99,235,0.6);
}

.btn-primary:hover {
  transform:translateY(-3px);
  box-shadow:0 0 25px rgba(37,99,235,0.9);
}

.btn-outline {
  border:2px solid var(--white);
  color:var(--white);
}

.btn-outline:hover {
  background:var(--white);
  color:var(--black);
}

.social {
  margin-top:25px;
}

.social a {
  color:var(--white);
  font-size:18px;
  margin:0 12px;
  transition:0.3s;
}

.social a:hover {
  color:var(--primary);
  transform:scale(1.2);
}

section {
  padding:100px 20px;
  max-width:1100px;
  margin:auto;
}

section h2 {
  text-align:center;
  font-size:28px;
  margin-bottom:40px;
  color:var(--primary);
}

.glass-card {
  background:var(--glass);
  backdrop-filter:blur(10px);
  padding:30px;
  border-radius:15px;
  margin-bottom:25px;
  transition:0.4s ease;
}

.glass-card:hover {
  transform:translateY(-8px);
  box-shadow:0 0 25px rgba(37,99,235,0.3);
}

.skills {
  display:grid;
  grid-template-columns:repeat(auto-fit,minmax(200px,1fr));
  gap:20px;
}

.skill-box {
  background:var(--glass);
  backdrop-filter:blur(10px);
  padding:25px;
  border-radius:12px;
  text-align:center;
  transition:0.3s;
}

.skill-box:hover {
  background:var(--primary);
}

footer {
  text-align:center;
  padding:30px;
  background:#050505;
  font-size:14px;
  opacity:0.7;
}

@keyframes fadeIn {
  from { opacity:0; transform:translateY(20px); }
  to { opacity:1; transform:translateY(0); }
}

@media(max-width:768px){
  header h1 { font-size:24px; }
}
</style>
</head>

<body>

<header>
  <img src="profile.jpg" alt="Abdul Hazad">
  <h1>Reliable <span>Automotive & Office Support</span> Professional in Dubai</h1>
  <p>Delivering Precision, Responsibility, and Consistency in Every Task.</p>

  <a href="#" class="btn btn-primary">Download Resume</a>
  <a href="#contact" class="btn btn-outline">Contact Me</a>

  <div class="social">
    <a href="https://instagram.com/hazadd___" target="_blank"><i class="fab fa-instagram"></i></a>
    <a href="#"><i class="fab fa-x-twitter"></i></a>
    <a href="#"><i class="fab fa-facebook-f"></i></a>
    <a href="https://abdulhazad.ae"><i class="fas fa-globe"></i></a>
  </div>
</header>

<section>
  <h2>About Me</h2>
  <div class="glass-card">
    I am a Dubai-based professional driver and automotive logistics support specialist with experience in vehicle transportation, showroom coordination, and office administration. I maintain high standards of discipline, efficiency, and reliability in every responsibility I undertake.
  </div>
</section>

<section>
  <h2>Work Experience</h2>

  <div class="glass-card">
    <strong>Messenger & Driver – ICONIC MOTORS, Dubai</strong><br>
    Vehicle transportation, document handling, showroom coordination, and maintaining vehicle movement logs.
  </div>

  <div class="glass-card">
    <strong> – Ghassan Aboud Cars, Dubai</strong><br>
    Safe vehicle transport, staff pickup, maintenance checks, and showroom support.
  </div>

  <div class="glass-card">
    <strong>Office Support – Ghassan Aboud Cars, Dubai</strong><br>
    Administrative assistance, document management, and office organization.
  </div>

</section>

<section>
  <h2>Core Skills</h2>
  <div class="skills">
    <div class="skill-box">Automotive Logistics</div>
    <div class="skill-box">Vehicle Handling</div>
    <div class="skill-box">Office Administration</div>
    <div class="skill-box">Team Collaboration</div>
    <div class="skill-box">Communication</div>
    <div class="skill-box">Time Management</div>
  </div>
</section>

<section id="contact">
  <h2>Contact</h2>
  <div class="glass-card">
    Email: abdulhazadofficial@gmail.com<br>
    Location: IND,Manglore -Dubai, UAE
  </div>
</section>

<footer>
  © 2026 Abdul Hazad | IND , UAE
</footer>

</body>
</html>
