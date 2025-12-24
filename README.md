# Christmaswishsaksham
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Merry Christmas Panchakshari 🎀</title>

<style>
body {
    margin: 0;
    font-family: 'Poppins', sans-serif;
    background: linear-gradient(to bottom, #0f2027, #203a43, #2c5364);
    color: white;
    text-align: center;
    overflow: hidden;
}

.container {
    position: relative;
    top: 50%;
    transform: translateY(-50%);
    padding: 20px;
}

h1 {
    font-size: 3rem;
    margin-bottom: 10px;
}

h2 {
    font-size: 2rem;
    color: #ffdede;
}

.message {
    font-size: 1.2rem;
    max-width: 600px;
    margin: 20px auto;
    line-height: 1.6;
}

.heart {
    font-size: 2rem;
    animation: pulse 1.5s infinite;
}

@keyframes pulse {
    0% { transform: scale(1); }
    50% { transform: scale(1.3); }
    100% { transform: scale(1); }
}

/* Snow effect */
.snow {
    position: absolute;
    top: -10px;
    color: white;
    font-size: 1em;
    animation: fall linear infinite;
}

@keyframes fall {
    to {
        transform: translateY(110vh);
    }
}
</style>
</head>

<body>

<div class="container">
    <h1>🎄 Merry Christmas 🎄</h1>
    <h2>Panchakshari 🎀</h2>

    <p class="message">
        This Christmas, I just want you to know how truly special you are to me.  
        Your presence makes everything brighter and warmer ✨  
        May your heart be filled with love, peace, and endless smiles this season ❄️
    </p>

    <div class="heart">❤️</div>

    <p>With lots of love,<br><b>Someone who truly cares 💫</b></p>
</div>

<script>
// Snowflakes
for (let i = 0; i < 50; i++) {
    let snow = document.createElement("div");
    snow.className = "snow";
    snow.innerHTML = "❄";
    snow.style.left = Math.random() * 100 + "vw";
    snow.style.animationDuration = (Math.random() * 3 + 2) + "s";
    snow.style.fontSize = (Math.random() * 10 + 10) + "px";
    document.body.appendChild(snow);
}
</script>

</body>
</html>
