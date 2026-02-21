<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>The Metal Classes</title>

  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;500;700&display=swap" rel="stylesheet">

  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Poppins', sans-serif;
    }

    body {
      background: radial-gradient(circle at top, #300000, #0f0f0f);
      color: white;
      min-height: 100vh;
    }

    nav {
      display: flex;
      justify-content: space-between;
      padding: 20px 8%;
      backdrop-filter: blur(10px);
      background: rgba(255, 0, 0, 0.1);
      border-bottom: 1px solid rgba(255, 0, 0, 0.2);
    }

    nav h2 {
      color: #ff4d4d;
    }

    nav a {
      color: white;
      text-decoration: none;
      margin-left: 20px;
      transition: 0.3s;
    }

    nav a:hover {
      color: #ff4d4d;
    }

    .hero {
      display: flex;
      justify-content: center;
      align-items: center;
      height: 85vh;
      text-align: center;
      padding: 20px;
    }

    .glass {
      background: rgba(255, 0, 0, 0.08);
      border-radius: 20px;
      padding: 40px;
      backdrop-filter: blur(15px);
      border: 1px solid rgba(255, 0, 0, 0.2);
      box-shadow: 0 0 25px rgba(255, 0, 0, 0.2);
    }

    h1 {
      font-size: 2.5rem;
      color: #ff4d4d;
      margin-bottom: 15px;
    }

    p {
      opacity: 0.8;
    }
  </style>
</head>
<body>

<nav>
  <h2>The Metal Classes</h2>
  <div>
    <a href="index.html">Home</a>
    <a href="contact.html">Contact</a>
    <a href="location.html">Location</a>
  </div>
</nav>

<section class="hero">
  <div class="glass">
    <h1>THE METAL CLASSES BY MAYUR GUPTA SIR</h1>
    <p>Futuristic Learning • Concept Clarity • Academic Excellence</p>
  </div>
</section>

</body>
</html>
