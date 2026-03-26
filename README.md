# 🖇️TIMSZYSHAK🖇️
<!DOCTYPE html>
<html>
<head>
  <title>Timszy | Developer</title>

  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background: radial-gradient(circle at top, #0f172a, #020617);
      color: white;
      text-align: center;
    }

    header {
      padding: 25px;
      font-size: 30px;
      font-weight: bold;
      color: #38bdf8;
      text-shadow: 0 0 15px #38bdf8;
    }

    img {
      width: 130px;
      height: 130px;
      border-radius: 50%;
      border: 3px solid #38bdf8;
      box-shadow: 0 0 20px #38bdf8;
      margin-top: 20px;
    }

    #typing {
      font-size: 28px;
      margin-top: 20px;
      color: #e2e8f0;
    }

    p {
      color: #94a3b8;
      font-size: 16px;
    }

    .container {
      padding: 30px;
    }

    .btn {
      display: block;
      margin: 12px auto;
      padding: 14px;
      width: 80%;
      max-width: 300px;
      border-radius: 10px;
      text-decoration: none;
      color: white;
      font-size: 16px;
      transition: 0.3s;
    }

    .whatsapp {
      background: #25D366;
    }

    .telegram {
      background: #0ea5e9;
    }

    .btn:hover {
      transform: scale(1.05);
      box-shadow: 0 0 15px white;
    }

    .card {
      margin: 20px auto;
      padding: 20px;
      width: 85%;
      max-width: 400px;
      background: rgba(255, 255, 255, 0.05);
      border-radius: 15px;
      backdrop-filter: blur(10px);
      box-shadow: 0 0 20px rgba(0,0,0,0.5);
    }

    footer {
      margin-top: 30px;
      padding: 20px;
      color: #64748b;
      font-size: 14px;
    }
  </style>
</head>

<body>

  <header>
    TIMSZY ⚡
  </header>

  <img src="https://github.com/timszy001.png" alt="profile">

  <div class="container">
    <h1 id="typing"></h1>
    <p>I build clean, powerful and modern websites 🚀</p>
  </div>

  <div class="card">
    <h2>Connect With Me</h2>

    <a href="https://wa.me/2348080171998" class="btn whatsapp">
      💬 WhatsApp Me
    </a>

    <a href="https://t.me/OMEGAPROWIN2" class="btn telegram">
      📢 Telegram Channel
    </a>
  </div>

  <div class="card">
    <h2>About Me</h2>
    <p>
      I'm Timszy, a developer building next-level digital experiences.
      I focus on clean design, speed, and creativity.
    </p>
  </div>

  <footer>
    © 2026 Timszy • All Rights Reserved
  </footer>

  <script>
    const text = "Hi, I'm Timszy 👋";
    let i = 0;

    function type() {
      if (i < text.length) {
        document.getElementById("typing").innerHTML += text.charAt(i);
        i++;
        setTimeout(type, 70);
      }
    }

    type();
  </script>

</body>
</html>
