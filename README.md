# Demo.github.io
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Jay Shankar Agrawal | Portfolio</title>

<style>
*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:Arial,Helvetica,sans-serif;
}

body{
background:#0b0b0b;
color:white;
overflow-x:hidden;
}

/* Background */
body::before{
content:"";
position:fixed;
width:100%;
height:100%;
background:
linear-gradient(rgba(255,255,255,.03) 1px, transparent 1px),
linear-gradient(90deg, rgba(255,255,255,.03) 1px, transparent 1px);
background-size:45px 45px;
z-index:-3;
}

.chart{
position:fixed;
width:100%;
height:100%;
opacity:.08;
z-index:-2;
}

.chart svg{
width:100%;
height:100%;
}

.bullbear{
position:fixed;
bottom:20px;
right:20px;
font-size:90px;
opacity:.08;
z-index:-1;
}

.container{
width:90%;
max-width:950px;
margin:auto;
padding:60px 0;
}

header{
text-align:center;
margin-bottom:60px;
}

header h1{
font-size:52px;
letter-spacing:2px;
}

header h3{
margin-top:12px;
font-weight:normal;
color:#9ca3af;
}

.line{
width:120px;
height:3px;
background:#00ff99;
margin:20px auto;
}

.card{
background:#131313;
padding:30px;
margin:25px 0;
border-radius:15px;
border:1px solid #222;
transition:.4s;
}

.card:hover{
transform:translateY(-6px);
border-color:#00ff99;
}

h2{
color:#00ff99;
margin-bottom:18px;
}

p{
line-height:1.8;
color:#d1d5db;
}

ul{
list-style:none;
}

li{
padding:8px 0;
color:#d1d5db;
}

.grid{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
gap:20px;
}

.footer{
text-align:center;
padding:30px;
color:#777;
font-size:14px;
}

.badge{
display:inline-block;
padding:8px 16px;
border:1px solid #00ff99;
border-radius:30px;
margin-top:15px;
color:#00ff99;
}

a{
color:#00ff99;
text-decoration:none;
}

@media(max-width:700px){
header h1{
font-size:38px;
}
}
</style>
</head>

<body>

<div class="chart">
<svg viewBox="0 0 1200 600" preserveAspectRatio="none">
<polyline fill="none"
stroke="#00ff99"
stroke-width="4"
points="0,500 120,470 220,430 320,450 450,350 560,380 700,250 850,280 960,160 1080,200 1200,80"/>
</svg>
</div>

<div class="bullbear">
🐂 🐻
</div>

<div class="container">

<header>
<h1>Jay Shankar Agrawal</h1>
<div class="line"></div>
<h3>Student • Commerce • Future Investor</h3>
<div class="badge">Minimal Portfolio</div>
</header>

<div class="card">
<h2>About Me</h2>
<p>
Hello! I'm <strong>Jay Shankar Agrawal</strong>, a Commerce student who has completed
12th grade. I enjoy learning about finance, the stock market, and business.
Apart from academics, I love playing cricket, watching movies, and working out
at the gym. I believe in continuous learning and personal growth.
</p>
</div>

<div class="grid">

<div class="card">
<h2>Education</h2>
<ul>
<li>🏫 Little Flower School</li>
<li>🎓 CNC College</li>
<li>📖 Stream: Commerce</li>
<li>✅ Qualification: 12th Pass</li>
</ul>
</div>

<div class="card">
<h2>Personal Info</h2>
<ul>
<li>👤 Role: Student</li>
<li>📍 Balangir</li>
<li>📧 jayshankar19745@gmail.com</li>
</ul>
</div>

</div>

<div class="card">
<h2>Hobbies</h2>
<ul>
<li>🏏 Playing Cricket</li>
<li>🎬 Watching Movies</li>
<li>💪 Gym & Fitness</li>
</ul>
</div>

<div class="card">
<h2>My Interests & Work</h2>
<p>
I am passionate about the stock market and investment concepts.
I enjoy understanding Bull and Bear markets, financial trends,
and wealth creation strategies. I continuously improve my skills
through learning and practical knowledge.
</p>
</div>

<div class="card">
<h2>Stock Market</h2>
<p>
🐂 <b>Bull Market:</b> A period where prices generally move upward and
investor confidence remains strong.
<br><br>
🐻 <b>Bear Market:</b> A period where prices decline over time and
market sentiment becomes cautious.
</p>
</div>

<div class="footer">
© 2026 Jay Shankar Agrawal • Designed with HTML & CSS
</div>

</div>

</body>
</html>
