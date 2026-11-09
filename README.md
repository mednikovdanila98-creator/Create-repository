
<!DOCTYPE html>
<html lang="ru">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>NovaTech — Игры. Технологии. Будущее.</title>
<style>
*{box-sizing:border-box}
body{
 margin:0;background:#080512;color:white;
 font-family:Arial,sans-serif;
}
header{
 padding:22px 8%;display:flex;
 justify-content:space-between;align-items:center;
 border-bottom:1px solid #6725a5;
}
.logo{font-size:30px;font-weight:900;color:#bd70ff}
nav a{color:white;text-decoration:none;margin:0 12px}
.hero{
 text-align:center;padding:100px 20px;
 background:radial-gradient(ellipse,#38116d,#080512 70%);
}
.hero h1{font-size:clamp(45px,8vw,85px);margin:0}
.hero h1 span{color:#bd70ff}
.hero p{font-size:20px;color:#c9b8dc}
button{
 background:linear-gradient(90deg,#852bff,#c34cff);
 border:0;color:white;padding:15px 28px;
 border-radius:30px;font-size:16px;
 cursor:pointer;font-weight:bold;
}
section{padding:55px 8%;text-align:center}
h2{font-size:34px;color:#c78aff}
.cards{
 display:grid;grid-template-columns:repeat(auto-fit,minmax(220px,1fr));
 gap:20px;margin-top:30px;
}
.card{
 background:#171025;border:1px solid #7435a5;
 padding:28px;border-radius:18px;
 transition:.25s;
}
.card:hover{transform:translateY(-7px);box-shadow:0 0 25px #862dce}
.card .emoji{font-size:48px}
.card h3{color:#d3a1ff}
footer{
 text-align:center;padding:35px;
 color:#a99ab9;border-top:1px solid #54217a;
}
</style>
</head>
<body>
<header>
 <div class="logo">♛ NovaTech</div>
 <nav>
  <a href="#about">О нас</a>
  <a href="#products">Продукты</a>
  <a href="#future">Будущее</a>
 </nav>
</header>

<div class="hero">
 <h1>Добро пожаловать в <span>NovaTech</span></h1>
 <p>Игры. Технологии. Будущее.</p>
 <button onclick="document.querySelector('#products').scrollIntoView({behavior:'smooth'})">
  Исследовать мир
 </button>
</div>

<section id="about">
 <h2>Наша миссия</h2>
 <p>Мы создаём технологии, которые меняют игровой мир.</p>
</section>

<section id="products">
 <h2>Наша вселенная</h2>
 <div class="cards">
  <div class="card">
   <div class="emoji">🎮</div>
   <h3>NovaGames</h3>
   <p>Игры нового поколения.</p>
  </div>
  <div class="card">
   <div class="emoji">🖥️</div>
   <h3>NovaHardware</h3>
   <p>Мощные игровые устройства.</p>
  </div>
  <div class="card">
   <div class="emoji">🤖</div>
   <h3>NovaAI</h3>
   <p>Искусственный интеллект.</p>
  </div>
  <div class="card">
   <div class="emoji">🌌</div>
   <h3>NovaWorld</h3>
   <p>Целая цифровая вселенная.</p>
  </div>
 </div>
</section>

<section id="future">
 <h2>Будущее начинается здесь</h2>
 <p>Наша цель — создать крупнейшую игровую экосистему.</p>
 <button onclick="alert('Добро пожаловать в NovaTech!')">
  Присоединиться
 </button>
</section>

<footer>
 © 2026 NovaTech. Играй. Создавай. Побеждай. 💜
</footer>
</body>
</html>

