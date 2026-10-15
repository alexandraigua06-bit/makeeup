<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Pink Glam 💄</title>

<style>
* {
    box-sizing: border-box;
}

body {
    margin: 0;
    font-family: Arial, sans-serif;
    background: linear-gradient(135deg, #ffe0ed, #fff0f6, #f8c9e0);
    color: #9b3868;
    text-align: center;
}

header {
    padding: 25px 10px;
    background: #f7a9cc;
    color: white;
    border-bottom: 4px solid #ef8bb9;
}

header h1 {
    margin: 0;
    font-size: 34px;
}

header p {
    margin-bottom: 0;
}

.container {
    max-width: 850px;
    margin: auto;
    padding: 20px;
}

.card {
    background: white;
    border-radius: 25px;
    padding: 20px;
    margin: 20px 0;
    box-shadow: 0 6px 20px #d879a533;
}

.face {
    width: 190px;
    height: 230px;
    background: #f6c6a9;
    border-radius: 48% 48% 45% 45%;
    margin: 25px auto;
    position: relative;
    border: 4px solid #e8a58c;
    transition: .3s;
}

.hair {
    position: absolute;
    top: -12px;
    left: -9px;
    width: 200px;
    height: 95px;
    border-radius: 90px 90px 35px 35px;
    background: #593526;
    z-index: 1;
}

.eye {
    position: absolute;
    top: 95px;
    width: 27px;
    height: 12px;
    background: white;
    border-radius: 50%;
    z-index: 2;
}

.eye::after {
    content: "";
    display: block;
    width: 10px;
    height: 10px;
    border-radius: 50%;
    background: #493027;
    margin: auto;
}

.left {
    left: 35px;
}

.right {
    right: 35px;
}

.blush {
    position: absolute;
    top: 125px;
    width: 36px;
    height: 19px;
    background: #f18b9e;
    opacity: .65;
    border-radius: 50%;
}

.blush.left {
    left: 15px;
}

.blush.right {
    right: 15px;
}

.nose {
    position: absolute;
    top: 112px;
    left: 83px;
    width: 18px;
    height: 25px;
    border-bottom: 3px solid #d28d77;
    border-radius: 50%;
}

.mouth {
    position: absolute;
    top: 153px;
    left: 65px;
    width: 55px;
    height: 24px;
    border-radius: 10px 10px 50% 50%;
    background: #c94b77;
    border: 2px solid #a93d66;
    transition: .2s;
}

.hair-color {
    position: absolute;
    top: -12px;
    left: -9px;
    width: 200px;
    height: 95px;
    border-radius: 90px 90px 35px 35px;
    z-index: 1;
}

h2 {
    color: #d45d95;
}

.options {
    display: flex;
    flex-wrap: wrap;
    gap: 10px;
    justify-content: center;
}

button {
    border: none;
    padding: 12px 17px;
    border-radius: 20px;
    background: #f5b0d0;
    color: #873358;
    font-size: 15px;
    cursor: pointer;
    font-weight: bold;
    transition: .2s;
}

button:hover {
    transform: scale(1.05);
    background: #ed8fba;
}

button:active {
    transform: scale(.97);
}

.color {
    width: 43px;
    height: 43px;
    border: 3px solid white;
    box-shadow: 0 0 0 1px #e9a3c3;
    padding: 0;
}

#message {
    font-size: 18px;
    font-weight: bold;
    min-height: 25px;
}

footer {
    padding: 20px;
    color: #ad5981;
}
</style>
</head>

<body>

<header>
    <h1>🎀 Pink Glam 💄</h1>
    <p>¡Tu mundo de maquillaje y belleza!</p>
</header>

<main class="container">

    <div class="card">
        <h2>✨ Crea tu look ✨</h2>
        <p>¡Conviértete en una maquilladora profesional!</p>

        <div class="face" id="face">
            <div class="hair" id="hair"></div>
            <div class="eye left"></div>
            <div class="eye right"></div>
            <div class="blush left" id="blush1"></div>
            <div class="blush right" id="blush2"></div>
            <div class="nose"></div>
            <div class="mouth" id="mouth"></div>
        </div>

        <p id="message">¡Tu modelo está lista para un cambio de look! 💕</p>
    </div>

    <div class="card">
        <h2>💋 Elige tu labial</h2>
        <div class="options">
            <button onclick="lipstick('#c2185b')">Rojo pasión</button>
            <button onclick="lipstick('#f48fb1')">Rosa Barbie</button>
            <button onclick="lipstick('#9c4268')">Malva</button>
            <button onclick="lipstick('#a0522d')">Nude</button>
            <button onclick="lipstick('#8e1747')">Vino</button>
        </div>
    </div>

    <div class="card">
        <h2>🎨 Sombras de ojos</h2>
        <div class="options">
            <button class="color" style="background:#e8a4e8"
            onclick="shadow('#e8a4e8')" aria-label="Sombra lila"></button>

            <button class="color" style="background:#b388ff"
            onclick="shadow('#b388ff')" aria-label="Sombra morada"></button>

            <button class="color" style="background:#ffb6c1"
            onclick="shadow('#ffb6c1')" aria-label="Sombra rosa"></button>

            <button class="color" style="background:#d4af37"
            onclick="shadow('#d4af37')" aria-label="Sombra dorada"></button>

            <button class="color" style="background:#8d6e63"
            onclick="shadow('#8d6e63')" aria-label="Sombra café"></button>
        </div>
    </div>

    <div class="card">
        <h2>🌸 Rubor</h2>
        <div class="options">
            <button onclick="blush('#ff7997')">Rosa</button>
            <button onclick="blush('#f08080')">Coral</button>
            <button onclick="blush('#d88b9a')">Malva</button>
            <button onclick="blush('#efa9c8')">Baby pink</button>
        </div>
    </div>

    <div class="card">
        <h2>💇‍♀️ Color de cabello</h2>
        <div class="options">
            <button onclick="hair('#593526')">Castaño</button>
            <button onclick="hair('#171313')">Negro</button>
            <button onclick="hair('#b87939')">Caramelo</button>
            <button onclick="hair('#e3b36b')">Rubio</button>
            <button onclick="hair('#d76f9c')">Rosado</button>
        </div>
    </div>

    <div class="card">
        <h2>💖 ¡Termina tu maquillaje!</h2>
        <div class="options">
            <button onclick="finish()">✨ Mostrar mi look</button>
            <button onclick="resetLook()">🔄 Reiniciar</button>
        </div>
    </div>

</main>

<footer>
    Hecho con 💗 para las amantes del maquillaje.
    <br>Pink Glam © 2026
</footer>

<script>
let currentShadow = "#ffffff";

function lipstick(color) {
    document.getElementById("mouth").style.background = color;
    document.getElementById("message").textContent =
        "¡Ese labial está precioso! 💋";
}

function shadow(color) {
    currentShadow = color;

    document.querySelectorAll(".eye").forEach(eye => {
        eye.style.background = color;
        eye.style.height = "17px";
    });

    document.getElementById("message").textContent =
        "¡Sombras aplicadas! ✨";
}

function blush(color) {
    document.getElementById("blush1").style.background = color;
    document.getElementById("blush2").style.background = color;

    document.getElementById("message").textContent =
        "¡Un rubor precioso para completar el look! 🌸";
}

function hair(color) {
    document.getElementById("hair").style.background = color;

    document.getElementById("message").textContent =
        "¡Nuevo color de cabello! 💇‍♀️";
}

function finish() {
    document.getElementById("message").textContent =
        "💖 ¡LOOK TERMINADO! Eres una maquilladora increíble. 💖";

    document.querySelector(".face").style.boxShadow =
        "0 0 25px #f08abb";
}

function resetLook() {
    document.getElementById("mouth").style.background = "#c94b77";
    document.getElementById("blush1").style.background = "#f18b9e";
    document.getElementById("blush2").style.background = "#f18b9e";
    document.getElementById("hair").style.background = "#593526";

    document.querySelectorAll(".eye").forEach(eye => {
        eye.style.background = "white";
        eye.style.height = "12px";
    });

    document.querySelector(".face").style.boxShadow = "none";

    document.getElementById("message").textContent =
        "¡Empecemos de nuevo! 💕";
}
</script>

</body>
</html>
