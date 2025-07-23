<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Botan's Gym</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background-color: #0d0d0d;
      color: #f0f0f0;
      line-height: 1.6;
    }

    header {
      background: linear-gradient(to right, #111, #222);
      padding: 40px 20px;
      text-align: center;
    }

    header h1 {
      font-size: 3em;
      color: #0f0;
    }

    header p {
      font-size: 1.2em;
      color: #ccc;
      margin-top: 10px;
    }

    nav {
      background-color: #111;
      display: flex;
      justify-content: center;
      padding: 15px;
      border-top: 1px solid #222;
      border-bottom: 1px solid #222;
    }

    nav a {
      color: #aaa;
      text-decoration: none;
      margin: 0 20px;
      font-weight: bold;
      transition: 0.3s;
    }

    nav a:hover {
      color: #0f0;
    }

    .container {
      max-width: 1000px;
      margin: 40px auto;
      padding: 0 20px;
    }

    section {
      margin-bottom: 50px;
    }

    h2 {
      color: #0f0;
      margin-bottom: 15px;
      border-bottom: 1px solid #333;
      padding-bottom: 5px;
    }

    ul {
      padding-left: 20px;
    }

    ul li {
      margin-bottom: 8px;
    }

    a {
      color: #09f;
    }

    form {
      background-color: #1a1a1a;
      padding: 25px;
      border-radius: 8px;
      border: 1px solid #333;
      max-width: 600px;
    }

    form label {
      display: block;
      margin-top: 15px;
      margin-bottom: 5px;
      font-weight: bold;
    }

    form input[type="text"],
    form input[type="email"] {
      width: 100%;
      padding: 10px;
      background-color: #2a2a2a;
      border: 1px solid #444;
      border-radius: 4px;
      color: #fff;
    }

    form input[type="submit"] {
      background-color: #0f0;
      color: #000;
      font-weight: bold;
      border: none;
      padding: 12px 20px;
      border-radius: 5px;
      margin-top: 20px;
      cursor: pointer;
      transition: 0.3s;
    }

    form input[type="submit"]:hover {
      background-color: #1f1;
    }

    footer {
      background-color: #111;
      text-align: center;
      padding: 30px 10px;
      color: #777;
      font-size: 0.9em;
    }

    @media (max-width: 600px) {
      nav {
        flex-direction: column;
      }

      nav a {
        margin: 10px 0;
      }
    }
  </style>
</head>
<body>

  <header>
    <h1>💪 Botan's Gym</h1>
    <p>Your Journey Starts Here — Stronger Every Day</p>
  </header>

  <nav>
    <a href="#">Home</a>
    <a href="#">Programs</a>
    <a href="#">Location</a>
    <a href="#">Contact</a>
    <a href="#">Join</a>
  </nav>

  <div class="container">

    <section>
      <h2>🏠 Home</h2>
      <p>At <strong>Botan's Gym</strong>, we believe in strength, discipline, and transformation. Whether you're just starting or you're a seasoned athlete, we're here to help you crush your goals and level up your fitness.</p>
    </section>

    <section>
      <h2>📅 Our Programs</h2>
      <ul>
        <li>Weightlifting</li>
        <li>Boxing</li>
        <li>Cardio Training</li>
        <li>Bodybuilding</li>
        <li>Personal Training</li>
      </ul>
    </section>

    <section>
      <h2>📍 Location</h2>
      <p>Erbil,Bnaslawa,Kurdistan Region of Iraq</p>
    </section>

    <section>
      <h2>📞 Contact Us</h2>
      <p>Email: <a href="mailto:botansgym@example.com">botansgym@example.com</a></p>
      <p>Phone: +964-750-657-47-22</p>
    </section>

    <section>
      <h2>📝 Join Now</h2>
      <form>
        <label for="name">Full Name</label>
        <input type="text" id="name" name="name" required>

        <label for="email">Email Address</label>
        <input type="email" id="email" name="email" required>

        <label for="goal">Your Fitness Goal</label>
        <input type="text" id="goal" name="goal">

        <input type="submit" value="Join Botan's Gym">
      </form>
    </section>

  </div>

  <footer>
    <p>Botan's Gym. Powered by 💪 Passion & 💻 Code.</p>
  </footer>

</body>
</html>

