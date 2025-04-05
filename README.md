<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Sarkar E-Sports Registration</title>
  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
      background-color: #111;
      color: #fff;
      margin: 0;
      padding: 0;
      display: flex;
      flex-direction: column;
      align-items: center;
    }
    header {
      text-align: center;
      padding: 2rem;
    }
    header h1 {
      font-size: 2.5rem;
      color: #00ffcc;
    }
    .intro {
      max-width: 600px;
      text-align: center;
      margin-bottom: 2rem;
      font-size: 1.1rem;
    }
    form {
      background: #222;
      padding: 2rem;
      border-radius: 10px;
      max-width: 400px;
      width: 100%;
      display: flex;
      flex-direction: column;
    }
    form input {
      padding: 0.8rem;
      margin: 0.5rem 0;
      border: none;
      border-radius: 5px;
      font-size: 1rem;
    }
    form button {
      background: #00ffcc;
      color: #000;
      padding: 1rem;
      border: none;
      border-radius: 5px;
      font-size: 1rem;
      cursor: pointer;
      margin-top: 1rem;
    }
    .whatsapp {
      margin-top: 2rem;
    }
    .whatsapp a {
      background: #25D366;
      color: white;
      padding: 1rem 2rem;
      text-decoration: none;
      border-radius: 10px;
      font-size: 1.2rem;
    }
  </style>
</head>
<body>
  <header>
    <h1>Welcome to Sarkar E-Sports</h1>
  </header>

  <div class="intro">
    <p>Get ready to compete in thrilling online tournaments and show off your skills. Register now and join our WhatsApp channel for the latest updates, match schedules, and team interactions!</p>
  </div>

  <form>
    <input type="text" name="name" placeholder="Name" required>
    <input type="tel" name="phone" placeholder="Phone Number" required>
    <input type="email" name="email" placeholder="Gmail" required>
    <input type="text" name="team" placeholder="Team Name" required>
    <button type="submit">Register Now</button>
  </form>

  <div class="whatsapp">
    <a href="https://chat.whatsapp.com/H04HdpDpLez2gblNSTV7F6" target="_blank">Join WhatsApp Channel</a>
  </div>
</body>
</html>
