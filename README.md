<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Pentest Project - Vulnerability Testing</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;500;700&display=swap" rel="stylesheet">
  <style>
    body {
      margin: 0;
      font-family: 'Poppins', sans-serif;
      background: linear-gradient(135deg, #0f172a, #1e293b);
      color: #f8fafc;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      min-height: 100vh;
    }
    header {
      text-align: center;
      margin-bottom: 30px;
    }
    header img {
      width: 100px;
      border-radius: 50%;
      box-shadow: 0 0 15px rgba(255,255,255,0.2);
    }
    h1 {
      margin-top: 15px;
      font-size: 2.2rem;
      font-weight: 700;
      color: #38bdf8;
    }
    p {
      font-size: 1rem;
      max-width: 600px;
      text-align: center;
      color: #94a3b8;
    }
    .container {
      background: rgba(255, 255, 255, 0.05);
      padding: 30px;
      border-radius: 20px;
      box-shadow: 0 8px 25px rgba(0, 0, 0, 0.2);
      width: 90%;
      max-width: 600px;
      text-align: center;
    }
    input[type="text"], input[type="password"] {
      width: 80%;
      padding: 12px;
      border: none;
      border-radius: 8px;
      margin: 10px 0;
      background: rgba(255, 255, 255, 0.1);
      color: #fff;
      font-size: 1rem;
    }
    input:focus {
      outline: 2px solid #38bdf8;
      background: rgba(255, 255, 255, 0.15);
    }
    button {
      background: #38bdf8;
      border: none;
      padding: 12px 30px;
      border-radius: 8px;
      font-size: 1rem;
      color: #0f172a;
      cursor: pointer;
      font-weight: 600;
      margin-top: 15px;
      transition: all 0.3s ease;
    }
    button:hover {
      background: #0ea5e9;
      transform: translateY(-2px);
    }
    footer {
      margin-top: 40px;
      font-size: 0.9rem;
      color: #64748b;
    }
    .icon {
      width: 60px;
      margin: 15px 10px;
      opacity: 0.8;
    }
    .icons {
      display: flex;
      justify-content: center;
      margin-top: 20px;
    }
  </style>
</head>
<body>
  <header>
    <img src="https://cdn-icons-png.flaticon.com/512/3845/3845731.png" alt="Security Icon">
    <h1>Pentest Vulnerability Testing</h1>
    <p>Test your web application’s vulnerabilities in a safe and secure environment. Built with Flask & Burp Suite.</p>
  </header>

  <div class="container">
    <h2>Login Form</h2>
    <form action="/login" method="POST">
      <input type="text" name="username" placeholder="Username" required><br>
      <input type="password" name="password" placeholder="Password" required><br>
      <button type="submit">Login</button>
    </form>
  </div>

  <div class="icons">
    <img class="icon" src="https://cdn-icons-png.flaticon.com/512/1006/1006771.png" alt="Burp Icon">
    <img class="icon" src="https://cdn-icons-png.flaticon.com/512/919/919853.png" alt="Python Icon">
    <img class="icon" src="https://cdn-icons-png.flaticon.com/512/919/919830.png" alt="Flask Icon">
  </div>

  <footer>
    © 2025 Pentest Project | Developed for educational and ethical use only.
  </footer>
</body>
</html>
