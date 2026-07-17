
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>KY Prof | Professional Video Editing</title>

<style>
:root{
--bg:#0b0b0b;
--card:#141414;
--text:#fff;
--accent:#ff7b00;
}
*{margin:0;padding:0;box-sizing:border-box;font-family:Segoe UI,sans-serif;}
body{
background:var(--bg);
color:var(--text);
scroll-behavior:smooth;
}
header{
position:sticky;
top:0;
background:rgba(0,0,0,.85);
backdrop-filter:blur(10px);
padding:15px 8%;
display:flex;
justify-content:space-between;
align-items:center;
z-index:100;
}
.logo{
font-size:1.6rem;
font-weight:700;
color:var(--accent);
}
nav a{
color:white;
text-decoration:none;
margin-left:20px;
}
.hero{
min-height:90vh;
display:flex;
flex-direction:column;
justify-content:center;
align-items:center;
text-align:center;
padding:20px;
}
.hero h1{
font-size:4rem;
animation:slide 1s ease;
}
.hero span{color:var(--accent);}
.hero p{
max-width:700px;
margin:20px 0;
font-size:1.1rem;
}
.btn{
display:inline-block;
padding:14px 28px;
background:var(--accent);
color:black;
font-weight:bold;
border-radius:10px;
text-decoration:none;
transition:.3s;
}
.btn:hover{
transform:translateY(-3px);
}
section{
padding:80px 8%;
}
h2{
margin-bottom:25px;
font-size:2rem;
color:var(--accent);
}
.grid{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
gap:20px;
}
.card{
background:var(--card);
padding:25px;
border-radius:15px;
transition:.3s;
}
.card:hover{
transform:translateY(-8px);
}
.portfolio{
height:180px;
display:flex;
align-items:center;
justify-content:center;
font-weight:bold;
font-size:1.2rem;
background:linear-gradient(135deg,#ff7b00,#ffb347);
color:black;
border-radius:15px;
}
.price{
font-size:2rem;
margin:10px 0;
}
.contact-links a{
display:block;
margin:10px 0;
color:white;
text-decoration:none;
}
footer{
text-align:center;
padding:30px;
background:#050505;
}
.toggle{
cursor:pointer;
background:var(--accent);
padding:8px 14px;
border:none;
border-radius:8px;
font-weight:bold;
}
form{
display:flex;
flex-direction:column;
gap:12px;
}
input,textarea{
padding:12px;
border:none;
border-radius:10px;
background:#222;
color:white;
}
button{
padding:12px;
border:none;
background:var(--accent);
border-radius:10px;
font-weight:bold;
cursor:pointer;
}
@keyframes slide{
from{opacity:0;transform:translateY(40px);}
to{opacity:1;transform:translateY(0);}
}
</style>
</head>

<body>

<header>
<div class="logo">KY Prof</div>
<nav>
<a href="#services">Services</a>
<a href="#portfolio">Portfolio</a>
<a href="#pricing">Pricing</a>
<a href="#contact">Contact</a>
</nav>
<button class="toggle" onclick="toggleTheme()">Theme</button>
</header>

<section class="hero">
<h1><span>KY Prof</span> Video Editing</h1>
<p>
Professional Anime Edits, Gaming Montages, YouTube Shorts,
TikTok Videos, Reels, and Long-Form Content.
Fast delivery. High-quality edits. Affordable pricing.
</p>
<a href="#contact" class="btn">Book Now</a>
</section>

<section id="services">
<h2>Services</h2>
<div class="grid">
<div class="card">
<h3>Gaming Edits</h3>
<p>Montages, highlights, funny moments, transitions, and effects.</p>
</div>

<div class="card">
<h3>Anime Edits</h3>
<p>AMVs, sync edits, transitions, and cinematic effects.</p>
</div>

<div class="card">
<h3>YouTube Shorts</h3>
<p>Captions, hooks, zooms, memes, and viral-style editing.</p>
</div>

<div class="card">
<h3>Long-Form Videos</h3>
<p>Full YouTube videos, storytelling, and retention editing.</p>
</div>
</div>
</section>

<section id="portfolio">
<h2>Portfolio</h2>

<div class="grid">
<div class="portfolio">🎮 Gaming Edits</div>
<div class="portfolio">🔥 Anime AMVs</div>
<div class="portfolio">📱 TikTok Videos</div>
<div class="portfolio">🎬 YouTube Shorts</div>
<div class="portfolio">🚀 Viral Reels</div>
<div class="portfolio">📹 Long-Form Content</div>
</div>

<p style="margin-top:20px;">
Replace these placeholders with screenshots or embedded videos of your work.
</p>
</section>

<section id="pricing">
<h2>Pricing</h2>

<div class="grid">

<div class="card">
<h3>Starter</h3>
<div class="price">$10</div>
<p>1 Short Edit</p>
<p>Captions Included</p>
</div>

<div class="card">
<h3>Pro</h3>
<div class="price">$30</div>
<p>3 Edited Videos</p>
<p>Priority Delivery</p>
</div>

<div class="card">
<h3>Elite</h3>
<div class="price">$75</div>
<p>10 Videos</p>
<p>Highest Priority</p>
</div>

</div>
</section>

<section>
<h2>Client Reviews</h2>

<div class="grid">
<div class="card">
⭐⭐⭐⭐⭐
<p>"Amazing edits and fast delivery."</p>
</div>

<div class="card">
⭐⭐⭐⭐⭐
<p>"My Shorts got way more engagement."</p>
</div>

<div class="card">
⭐⭐⭐⭐⭐
<p>"Professional quality for a great price."</p>
</div>
</div>
</section>

<section>
<h2>FAQ</h2>

<div class="grid">
<div class="card">
<h3>How long does editing take?</h3>
<p>Usually 1–3 days depending on the project.</p>
</div>

<div class="card">
<h3>What content do you edit?</h3>
<p>Gaming, anime, YouTube, TikTok, Reels, and more.</p>
</div>

<div class="card">
<h3>Can I request revisions?</h3>
<p>Yes, revisions are included.</p>
</div>
</div>
</section>

<section id="contact">
<h2>Book a Project</h2>

<form action="mailto:dakyonlittles@gmail.com" method="post">
<input type="text" placeholder="Your Name" required>
<input type="email" placeholder="Your Email" required>
<textarea rows="5" placeholder="Tell me about your project"></textarea>
<button type="submit">Send Request</button>
</form>

<div class="contact-links" style="margin-top:30px;">
<a href="mailto:dakyonlittles@gmail.com">📧 dakyonlittles@gmail.com</a>
<a href="https://instagram.com/try_ky7" target="_blank">📸 Instagram: @try_ky7</a>
<a href="https://tiktok.com/@kailime45" target="_blank">🎵 TikTok: @kailime45</a>
</div>

</section>

<footer>
<p>© 2026 KY Prof | Professional Video Editing Services</p>
</footer>

<script>
function toggleTheme(){
const root=document.documentElement;

if(root.style.getPropertyValue('--bg')==='#ffffff'){
root.style.setProperty('--bg','#0b0b0b');
root.style.setProperty('--card','#141414');
root.style.setProperty('--text','#ffffff');
}else{
root.style.setProperty('--bg','#ffffff');
root.style.setProperty('--card','#f2f2f2');
root.style.setProperty('--text','#000000');
}
}
</script>

</body>
</html>