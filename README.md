# https-waelalanzuu.github.io
Wael
<!DOCTYPE html>
<html lang="ar">
<head>
<meta charset="UTF-8">
<title>Wael Al-Edah</title>
<style>
body{
  margin:0;
  font-family:Arial, sans-serif;
  background:linear-gradient(135deg,#7f00ff,#00c6ff,#00ffcc);
  color:white;
}
nav{
  background:rgba(0,0,0,0.3);
  padding:15px;
  text-align:center;
}
nav a{
  color:white;
  margin:0 15px;
  text-decoration:none;
  font-weight:bold;
}
header{
  text-align:center;
  padding:80px 20px;
}
.cards{
  display:grid;
  grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
  gap:20px;
  padding:40px;
}
.card{
  background:rgba(0,0,0,0.25);
  padding:25px;
  border-radius:15px;
  box-shadow:0 10px 25px rgba(0,0,0,0.3);
}
footer{
  text-align:center;
  padding:20px;
  background:rgba(0,0,0,0.4);
}
button{
  background:#00ffcc;
  border:none;
  padding:12px 20px;
  border-radius:25px;
  cursor:pointer;
  font-weight:bold;
}
button a{
  text-decoration:none;
  color:#000;
}
</style>
</head>
<body>

<nav>
  <a href="index.html">الرئيسية | Home</a>
  <a href="blog.html">المدونة | Blog</a>
  <a href="projects.html">المشاريع | Projects</a>
  <a href="contact.html">تواصل | Contact</a>
</nav>

<header>
  <h1>وائل بن عبدالاله الأيداء</h1>
  <p>Computer Engineering Student • Writer • Entrepreneur</p>
  <p>طالب هندسة حاسب | كاتب | رائد أعمال</p>
  <button><a href="projects.html">استعرض مشاريعي | View Projects</a></button>
</header>

<section class="cards">
  <div class="card">
    <h3>🧠 عني | About</h3>
    <p>طالب هندسة حاسب، كاتب صحفي، مهتم بالأمن السيبراني والذكاء الاصطناعي وريادة الأعمال.</p>
  </div>
  <div class="card">
    <h3>📝 المدوّنة | Blog</h3>
    <p>مقالات تقنية وفكرية تهدف لرفع الوعي الرقمي وتمكين الشباب.</p>
  </div>
  <div class="card">
    <h3>💼 الأعمال | Projects</h3>
    <p>مشاريع في الأغذية، المياه، العقار، والتحول الرقمي.</p>
  </div>
</section>

<footer>
  © Wael Al-Edah
</footer>

</body>
</html>