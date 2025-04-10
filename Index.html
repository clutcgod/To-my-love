<!doctype html>
<html lang="en"> 
 <head> 
  <meta charset="UTF-8"> 
  <meta name="viewport" content="width=device-width, initial-scale=1.0"> 
  <title>My Love for You</title> 
  <link rel="stylesheet" href="styles.css"> 
 </head> 
 <body> 
  <div class="heart-container"></div> <!-- Floating Hearts --> 
  <div class="content"> 
   <div class="message-box"> 
    <p id="intro-message">I have written with my whole heart for you Aliza 💞.</p> <button id="click-me-btn" onclick="startTyping()">Click Me</button> 
    <p id="message" style="display: none;"></p> <button id="next-btn" onclick="nextPage()" disabled style="display: none;">Next</button> 
   </div> 
  </div> 
  <script src="script.js"></script> 
 </body>
</html>/* General Styles */
body {
    background-color: #ffccdc;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
    margin: 0;
    overflow: hidden;
    font-family: 'Arial', sans-serif;
}

/* Floating Hearts */
.heart-container {
    position: absolute;
    width: 100%;
    height: 100%;
    overflow: hidden;
    pointer-events: none;
}

/* Message Box */
.content {
    position: relative;
    z-index: 10;
}

.message-box {
    background: rgba(255, 182, 193, 0.9);
    padding: 20px;
    border-radius: 15px;
    text-align: center;
    max-width: 500px;
    box-shadow: 0 0 20px rgba(255, 105, 180, 0.8);
    border: 3px solid #ff69b4;
    animation: glow 1.5s infinite alternate;
}

@keyframes glow {
    0% { box-shadow: 0 0 10px rgba(255, 105, 180, 0.8); }
    100% { box-shadow: 0 0 20px rgba(255, 20, 147, 1); }
}

/* Typing Effect */
#message {
    font-size: 20px;
    font-weight: bold;
    color: #800020;
    white-space: pre-wrap;
    overflow: hidden;
    border-right: 2px solid #800020;
    animation: blink 0.8s step-end infinite alternate;
    display: none;
}

@keyframes blink {
    50% { border-color: transparent; }
}

/* Buttons */
button {
    margin-top: 20px;
    padding: 10px 20px;
    font-size: 16px;
    border: none;
    background-color: #ff1493;
    color: white;
    border-radius: 5px;
    cursor: pointer;
}

button:hover {
    background-color: #ff69b4;
}

#next-btn {
    opacity: 0.5;
    transition: opacity 0.5s;
}

#next-btn.enabled {
    opacity: 1;
    pointer-events: auto;
}const messages = [
    "Like the moon that lights the darkest skies,\nYou walked into my world, a sweet surprise.\nEvery heartbeat whispers your name,\nIn love’s warm glow, an endless flame.",
    "With every sunrise, you are my light,\nA love so pure, so soft, so bright.\nLike stars that dance in endless space,\nI lose myself in your embrace.",
    "Through every storm, through every tide,\nI’ll hold your hand and stay by your side.\nIn this journey, love's sweet tune,\nForever starts with me and you.",
    "So here I stand, my heart laid bare,\nWith love so deep, beyond compare.\nA single wish, a vow so true—\nWill you say yes? My heart is yours to hold forever too."
];

let pageIndex = 0;

function startTyping() {
    document.getElementById("intro-message").style.display = "none";
    document.getElementById("click-me-btn").style.display = "none";
    document.getElementById("message").style.display = "block";
    
    typeMessage(pageIndex);
}

function typeMessage(index) {
    const messageElement = document.getElementById("message");
    const nextButton = document.getElementById("next-btn");
    
    messageElement.innerHTML = "";
    nextButton.disabled = true;
    nextButton.classList.remove("enabled");
    nextButton.style.display = "none";

    let text = messages[index];
    let i = 0;

    function type() {
        if (i < text.length) {
            messageElement.innerHTML += text.charAt(i);
            i++;
            setTimeout(type, 50);
        } else {
            nextButton.disabled = false;
            nextButton.classList.add("enabled");
            nextButton.style.display = "block";
        }
    }

    type();
}

function nextPage() {
    pageIndex++;
    if (pageIndex < messages.length) {
        typeMessage(pageIndex);
    } else {
        alert("");
    }
}

// Start floating hearts animation
document.addEventListener("DOMContentLoaded", () => {
    createFloatingHearts();
});

function createFloatingHearts() {
    const container = document.querySelector(".heart-container");

    setInterval(() => {
        const heart = document.createElement("div");
        heart.classList.add("heart");
        heart.style.left = Math.random() * 100 + "vw";
        heart.style.animationDuration = Math.random() * 3 + 2 + "s";
        container.appendChild(heart);

        setTimeout(() => {
            heart.remove();
        }, 5000);
    }, 500);
}
