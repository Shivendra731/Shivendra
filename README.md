<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Shivendra Pal - School Project</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@600&display=swap" rel="stylesheet" />
  <style>
    /* Reset */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    html, body {
      height: 100%;
      font-family: 'Poppins', sans-serif;
      background: linear-gradient(135deg, #ff36b8, #4b47ff, #00ffd5, #ffdc00);
      background-size: 800% 800%;
      animation: gradientShift 15s ease infinite;
      display: flex;
      justify-content: center;
      align-items: center;
      color: #fff;
      overflow-x: hidden;
      text-align: center;
      padding: 20px;
    }

    @keyframes gradientShift {
      0% { background-position: 0% 50%; }
      50% { background-position: 100% 50%; }
      100% { background-position: 0% 50%; }
    }

    .container {
      position: relative;
      z-index: 1;
      background: rgba(0, 0, 0, 0.65);
      padding: 60px 40px;
      border-radius: 20px;
      max-width: 480px;
      box-shadow:
        0 15px 30px rgba(255, 255, 255, 0.3),
        inset 0 0 30px rgba(255, 255, 255, 0.1);
      user-select: none;
      backdrop-filter: blur(10px);
      border: 1px solid rgba(255, 255, 255, 0.25);
    }

    h1 {
      font-weight: 600;
      font-size: 3.5rem;
      margin-bottom: 0.3em;
      color: #ff49b0;
      letter-spacing: 3px;
      text-shadow:
        0 0 7px #ff49b0,
        0 0 15px #ff49b0,
        0 0 20px #ff49b0;
    }

    .details {
      font-size: 1.8rem;
      font-weight: 600;
      color: #53fff3;
      margin-bottom: 10px;
      text-shadow:
        0 0 8px #53fff3,
        0 0 18px #53fff3;
    }

    .school-name {
      font-size: 1.3rem;
      font-style: italic;
      color: #ffde59;
      margin-bottom: 25px;
      letter-spacing: 2px;
      text-shadow:
        0 0 6px #ffde59,
        0 0 14px #ffde59;
    }

    .footer-text {
      font-size: 1rem;
      color: #ffffffcc;
      text-shadow: 0 0 6px rgba(255, 255, 255, 0.3);
    }

    /* Responsive */
    @media (max-width: 600px) {
      .container {
        padding: 45px 30px;
        max-width: 90vw;
      }
      h1 {
        font-size: 2.8rem;
        letter-spacing: 2px;
      }
      .details {
        font-size: 1.3rem;
      }
      .school-name {
        font-size: 1.1rem;
      }
    }
  </style>
</head>
<body>
  <main class="container" role="main" aria-label="School project information">
    <h1>Shivendra Pal</h1>
    <div class="details">Class 12th A2</div>
    <div class="school-name">SKD Academy</div>
    <div class="footer-text">Welcome to my school project website!</div>
  </main>
</body>
</html>
