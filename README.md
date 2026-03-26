# 🖇️TIMSZYSHAK🖇️

<!DOCTYPE html>
<html>
<head>
  <title>Timszy | Developer</title>

  <!-- FIX MOBILE ZOOM -->
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <style>
    body {
      margin: 0;
      font-family: Arial;
      background: black;
      color: white;
      text-align: center;
      overflow-x: hidden;
    }

    /* STARS BACKGROUND */
    body::before {
      content: "";
      position: fixed;
      width: 100%;
      height: 100%;
      background: url("https://www.transparenttextures.com/patterns/stardust.png");
      animation: move 60s linear infinite;
      z-index: -1;
    }

    @keyframes move {
      from {background-position: 0 0;}
      to {background-position: 1000px 1000px;}
    }

    header {
      padding: 20px;
      font-size: 26px;
      color: #00f7ff;
    }

    img {
      width: 110px;
      height: 110px;
      border-radius: 50%;
      border: 2px solid #00f7ff;
      margin-top: 10px;
    }

    #typing {
      font-size: 22px;
      margin: 15px;
    }

    .container {
      padding: 15px;
    }

    .btn {
      display: block;
      margin: 10px auto;
      padding: 12px;
      width: 90%;
      max-width: 300px;
      border-radius: 8px;
      text-decoration: none;
      color: white;
    }

    .whatsapp { background: #25D366; }
    .telegram { background: #0088cc; }

    .card {
      background: rgba(255,255,255,0.05);
      margin: 15px;
      padding: 15px;
      border-radius: 10px;
    }

    footer {
      margin: 20px;
      font-size: 13px;
      color: #aaa;
    }
  </style>
</head>

<body>

  <header>TIMSZY 🚀</header>

  <img src="https://github.com/timszy001.png">

  <h1 id="typing"></h1>

  <div class="container">

    <div class="card">
      <a href="https://wa.me/2348080171998" class="btn whatsapp">WhatsApp Me</a>
      <a href="https://t.me/OMEGAPROWIN2" class="btn telegram">Telegram Channel</a>
    </div>

    <div class="card">
      <h3>My Projects</h3>
      <p>Coming soon... 🚀</p>
    </div>

    <div class="card">
      <h3>Chat Bot 🤖</h3>
      <input id="userInput" placeholder="Type something..." style="width:80%;padding:10px;border-radius:5px;">
      <button onclick="reply()">Send</button>
      <p id="botReply"></p>
    </div>

  </div>

  <footer>© 2026 Timszy</footer>

  <!-- TYPING EFFECT -->
  <script>
    let text = "Hi, I'm Timszy 👋";
    let i = 0;
    function type() {
      if(i < text.length){
        document.getElementById("typing").innerHTML += text.charAt(i);
        i++;
        setTimeout(type, 70);
      }
    }
    type();

    function reply(){
      let input = document.getElementById("userInput").value;
      document.getElementById("botReply").innerText = "You said: " + input;
    }
  </script>

  <!-- MUSIC (ASAKE) -->
  <audio autoplay loop>
    <source src="PUT-YOUR-ASAKE-SONG-LINK.mp3" type="audio/mpeg">
  </audio>

</body>
</html>
