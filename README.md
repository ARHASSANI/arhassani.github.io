<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Alireza Hassani | Researcher & Software Engineer</title>

<meta name="description"
      content="Alireza Hassani - Researcher in Quantitative Finance, Algorithmic Trading, Financial Analytics, and Artificial Intelligence.">

<link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700;800&display=swap" rel="stylesheet">

<style>

:root{
    --primary:#2563eb;
    --secondary:#0f172a;
    --light:#f8fafc;
    --white:#ffffff;
    --gray:#64748b;
    --border:#e2e8f0;
}

*{
    margin:0;
    padding:0;
    box-sizing:border-box;
}

html{
    scroll-behavior:smooth;
}

body{
    font-family:'Inter',sans-serif;
    background:var(--light);
    color:#1e293b;
    line-height:1.8;
}

.container{
    width:90%;
    max-width:1200px;
    margin:auto;
}

nav{
    position:fixed;
    top:0;
    width:100%;
    background:rgba(255,255,255,.95);
    backdrop-filter:blur(12px);
    z-index:1000;
    border-bottom:1px solid var(--border);
}

.nav-container{
    display:flex;
    justify-content:space-between;
    align-items:center;
    padding:18px 0;
}

.logo{
    font-size:1.3rem;
    font-weight:800;
    color:var(--secondary);
}

.nav-links a{
    margin-left:25px;
    text-decoration:none;
    color:var(--secondary);
    font-weight:500;
}

.nav-links a:hover{
    color:var(--primary);
}

.hero{
    padding-top:150px;
    padding-bottom:100px;
}

.hero-content{
    display:grid;
    grid-template-columns:300px 1fr;
    gap:60px;
    align-items:center;
}

.profile-image{
    width:280px;
    height:280px;
    border-radius:50%;
    object-fit:cover;
    border:6px solid white;
    box-shadow:0 20px 50px rgba(0,0,0,.15);
}

.hero h1{
    font-size:3rem;
    margin-bottom:10px;
    color:var(--secondary);
}

.hero h2{
    color:var(--primary);
    font-size:1.4rem;
    margin-bottom:20px;
}

.hero p{
    color:var(--gray);
    font-size:1.05rem;
}

.buttons{
    margin-top:30px;
}

.btn{
    display:inline-block;
    padding:14px 28px;
    border-radius:10px;
    text-decoration:none;
    font-weight:600;
    margin-right:15px;
}

.btn-primary{
    background:var(--primary);
    color:white;
}

.btn-outline{
    border:2px solid var(--primary);
    color:var(--primary);
}

section{
    padding:90px 0;
}

.section-title{
    font-size:2.2rem;
    margin-bottom:40px;
    text-align:center;
    color:var(--secondary);
}

.card{
    background:white;
    border-radius:18px;
    padding:35px;
    box-shadow:0 10px 30px rgba(0,0,0,.05);
    margin-bottom:25px;
}

.grid{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(300px,1fr));
    gap:25px;
}

.card h3{
    margin-bottom:15px;
    color:var(--secondary);
}

.skills{
    display:flex;
    flex-wrap:wrap;
    gap:12px;
}

.skill{
    background:#dbeafe;
    color:#1e40af;
    padding:8px 15px;
    border-radius:999px;
    font-size:.9rem;
    font-weight:600;
}

.timeline{
    border-left:3px solid var(--primary);
    padding-left:25px;
}

.timeline-item{
    margin-bottom:35px;
}

.timeline-item h4{
    color:var(--primary);
}

.contact-links a{
    display:block;
    margin-bottom:12px;
    color:var(--primary);
    text-decoration:none;
}

footer{
    background:var(--secondary);
    color:white;
    text-align:center;
    padding:40px;
    margin-top:50px;
}

.stats{
    display:grid;
    grid-template-columns:repeat(4,1fr);
    gap:20px;
    text-align:center;
    margin-top:50px;
}

.stat{
    background:white;
    border-radius:15px;
    padding:25px;
}

.stat h3{
    color:var(--primary);
    font-size:2rem;
}

@media(max-width:900px){

.hero-content{
    grid-template-columns:1fr;
    text-align:center;
}

.profile-image{
    margin:auto;
}

.stats{
    grid-template-columns:repeat(2,1fr);
}

.nav-links{
    display:none;
}

.hero h1{
    font-size:2.2rem;
}

}

</style>
</head>

<body>

<nav>
<div class="container nav-container">
<div class="logo">Alireza Hassani</div>

<div class="nav-links">
<a href="#about">About</a>
<a href="#research">Research</a>
<a href="#projects">Projects</a>
<a href="#skills">Skills</a>
<a href="#education">Education</a>
<a href="#contact">Contact</a>
</div>
</div>
</nav>

<section class="hero">
<div class="container hero-content">

<img src="profile.jpg" alt="Alireza Hassani" class="profile-image">

<div>

<h1>Alireza Hassani</h1>

<h2>
Researcher in Quantitative Finance,
Algorithmic Trading & Artificial Intelligence
</h2>

<p>
Software Engineer with more than 15 years of programming experience and
a strong research focus on Financial Market Analytics,
Algorithmic Trading, Machine Learning,
Quantitative Finance and Advanced Ichimoku Cloud Methodologies.

Currently seeking fully funded PhD opportunities in
Computational Finance, Financial Engineering,
Artificial Intelligence and Data Science.
</p>

<div class="buttons">

<a href="CV.pdf" class="btn btn-primary">
Download CV
</a>

<a href="#contact" class="btn btn-outline">
Contact Me
</a>

</div>

</div>

</div>

<div class="container stats">

<div class="stat">
<h3>15+</h3>
<p>Years Programming</p>
</div>

<div class="stat">
<h3>96</h3>
<p>TOEFL Score</p>
</div>

<div class="stat">
<h3>10+</h3>
<p>Research Projects</p>
</div>

<div class="stat">
<h3>2026</h3>
<p>PhD Applications</p>
</div>

</div>
</section>

<section id="about">
<div class="container">

<h2 class="section-title">About Me</h2>

<div class="card">

<p>
I am a software engineer and researcher specializing in quantitative finance,
financial time-series analysis, algorithmic trading, and artificial intelligence.

My research focuses on developing intelligent analytical frameworks capable of identifying
high-probability trading opportunities through advanced technical analysis,
machine learning, and predictive modeling.

My Master's research introduced a novel approach based on Residual Ichimoku Cloud Analysis
for identifying future support and resistance structures in financial markets.
</p>

</div>

</div>
</section>

<section id="research">

<div class="container">

<h2 class="section-title">Research Interests</h2>

<div class="grid">

<div class="card">
<h3>Quantitative Finance</h3>
<p>
Financial modeling, risk management,
market forecasting and systematic trading strategies.
</p>
</div>

<div class="card">
<h3>Algorithmic Trading</h3>
<p>
Development of automated trading systems
based on statistical and technical methodologies.
</p>
</div>

<div class="card">
<h3>Machine Learning</h3>
<p>
Application of AI and ML techniques
for prediction and financial decision support.
</p>
</div>

<div class="card">
<h3>Financial Analytics</h3>
<p>
Large-scale analysis of market data
and intelligent trading signal generation.
</p>
</div>

</div>

</div>

</section>

<section id="projects">

<div class="container">

<h2 class="section-title">Research Projects</h2>

<div class="grid">

<div class="card">

<h3>Residual Ichimoku Cloud Research</h3>

<p>
Development of a novel analytical framework
for detecting residual cloud structures,
future support and resistance levels,
and cloud interaction zones.
</p>

</div>

<div class="card">

<h3>Algorithmic Trading Platform</h3>

<p>
Python-based trading research platform
including signal generation,
backtesting and performance evaluation.
</p>

</div>

<div class="card">

<h3>Machine Learning for Market Prediction</h3>

<p>
Exploration of AI techniques for
forecasting financial market movements
and improving trading performance.
</p>

</div>

<div class="card">

<h3>Industrial Monitoring Platform</h3>

<p>
Design and implementation of industrial
analytics systems featuring dashboards,
predictive monitoring and automation.
</p>

</div>

</div>

</div>

</section>

<section id="skills">

<div class="container">

<h2 class="section-title">Technical Skills</h2>

<div class="card">

<div class="skills">

<span class="skill">Python</span>
<span class="skill">C#</span>
<span class="skill">JavaScript</span>
<span class="skill">TypeScript</span>
<span class="skill">FastAPI</span>
<span class="skill">Node.js</span>
<span class="skill">Docker</span>
<span class="skill">Linux</span>
<span class="skill">Git</span>
<span class="skill">Pandas</span>
<span class="skill">NumPy</span>
<span class="skill">SQL</span>
<span class="skill">REST APIs</span>
<span class="skill">Machine Learning</span>
<span class="skill">Data Analytics</span>
<span class="skill">Financial Modeling</span>

</div>

</div>

</div>

</section>

<section id="education">

<div class="container">

<h2 class="section-title">Academic Profile</h2>

<div class="card timeline">

<div class="timeline-item">
<h4>Master's Research</h4>
<p>
Trading Strategy in Financial Markets Based on Residual Ichimoku Cloud Analysis
</p>
</div>

<div class="timeline-item">
<h4>Bachelor's Degree</h4>
<p>
ICT / Electrical Engineering
</p>
</div>

<div class="timeline-item">
<h4>Language Qualifications</h4>
<p>
TOEFL Home Edition: 96<br>
German: A2
</p>
</div>

<div class="timeline-item">
<h4>Future Research Directions</h4>
<p>
Computational Finance,
Explainable AI,
Financial Engineering,
Deep Learning,
Market Forecasting,
Risk Analytics.
</p>
</div>

</div>

</div>

</section>

<section id="contact">

<div class="container">

<h2 class="section-title">Contact</h2>

<div class="card">

<div class="contact-links">

<a href="mailto:YOUR_EMAIL">
alirezahassani64@yahoo.com
</a>

<a href="https://github.com/ARHASSANI">
GitHub
</a>

<a href="https://linkedin.com/in/alirezahassani64">
LinkedIn
</a>

</div>

</div>

</div>

</section>

<footer>

<p>
© 2026 Alireza Hassani
</p>

<p>
Researcher in Quantitative Finance, AI and Algorithmic Trading
</p>

</footer>

</body>
</html>
