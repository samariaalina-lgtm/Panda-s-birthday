<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Happy Birthday Alina ðŸ’–</title>

<style>
body {
  margin: 0;
  height: 100vh;
  background: linear-gradient(135deg, #ffb6c1, #ffd1dc, #cdb4db);
  font-family: 'Segoe UI', sans-serif;
  overflow: hidden;
  display: flex;
  justify-content: center;
  align-items: center;
  color: #fff;
}

.card {
  background: rgba(255, 255, 255, 0.2);
  backdrop-filter: blur(12px);
  padding: 35px;
  border-radius: 25px;
  width: 90%;
  max-width: 370px;
  text-align: center;
  box-shadow: 0 25px 45px rgba(0,0,0,0.25);
  animation: fadeIn 2s ease;
}

@keyframes fadeIn {
  from {opacity: 0; transform: translateY(30px);}
  to {opacity: 1; transform: translateY(0);}
}

h1 {
  font-size: 30px;
  margin-bottom: 5px;
  text-shadow: 0 0 12px rgba(255,255,255,0.8);
}

.name {
  font-size: 26px;
  font-weight: bold;
  margin-bottom: 10px;
  text-shadow: 0 0 18px #ffd1dc;
}

.message {
  font-size: 15px;
  line-height: 1.7;
}

button {
  margin-top: 20px;
  padding: 12px 28px;
  border: none;
  border-radius: 30px;
  background: linear-gradient(45deg, #ff4d6d, #ff758f);
  color: white;
  font-size: 16px;
  cursor: pointer;
  box-shadow: 0 6px 18px rgba(0,0,0,0.3);
}

button:hover {
  transform: scale(1.05);
}

/* Letter */
.letter {
  margin-top: 18px;
  font-size: 14.5px;
  line-height: 1.8;
  display: none;
  animation: glow 1.5s infinite alternate;
}

@keyframes glow {
  from {text-shadow: 0 0 6px #fff;}
  to {text-shadow: 0 0 18px #ffd1dc;}
}

.signature {
  margin-top: 10px;
  font-style: italic;
  opacity: 0.9;
}

/* Falling hearts */
.fall {
  position: absolute;
  font-size: 22px;
  animation: fall 6s linear infinite;
}

@keyframes fall {
  0% {transform: translateY(-10vh); opacity: 1;}
  100% {transform: translateY(110vh); opacity: 0;}
}
</style>
</head>

<body>

<!-- Optional soft music -->
<audio autoplay loop>
  <source src="https://cdn.pixabay.com/download/audio/2022/03/15/audio_4b8a5dcd42.mp3?filename=soft-piano-ambient-110624.mp3">
</audio>

<div class="card">
  <h1>ðŸŽ‚ Happy Birthday ðŸŽ‚</h1>
  <div class="name">Alina ðŸŒ·</div>

  <div class="message">
    Today the world feels brighter  
    because *you* were born ðŸ’•<br><br>
    This little page is just a reminder  
    of how special you truly are âœ¨
  </div>

  <button onclick="startLetter()">ðŸ’Œ Open My Heart</button>

  <div class="letter" id="letter"></div>

  <div class="signature">
    â€” From someone who truly cares ðŸ’–
  </div>
</div>

<script>
const text = `
Alina,
you are not just a friend â€”
you are comfort on hard days,
laughter on quiet ones,
and light when things feel heavy ðŸŒ¸

Your kindness, your smile,
and your heart make this world softer ðŸ’•

Never forget:
you matter more than you know,
you are loved more than you feel,
and you are enough â€” always ðŸ¥°
`;

let i = 0;
function startLetter() {
  document.getElementById("letter").style.display = "block";
  const interval = setInterval(() => {
    document.getElementById("letter").innerHTML += text.charAt(i);
    i++;
    if (i >= text.length) clearInterval(interval);
  }, 40);
}

/* Falling hearts & sparkles */
setInterval(() => {
  const el = document.createElement("div");
  el.classList.add("fall");
  el.innerHTML = Math.random() > 0.5 ? "ðŸ’–" : "âœ¨";
  el.style.left = Math.random() * 100 + "vw";
  el.style.animationDuration = (Math.random() * 3 + 4) + "s";
  document.body.appendChild(el);
  setTimeout(() => el.remove(), 6000);
}, 250);
</script>

</body>
</html>
