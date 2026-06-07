<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Contact Us - Wild Water Rafting</title>
  <link rel="stylesheet" href="styles.css"> <!-- Add your CSS file if needed -->
</head>
<body>
  <header>
    <h1>Wild Water Rafting</h1>
    <nav>
      <ul>
        <li><a href="index.html">Home</a></li>
        <li><a href="about.html">About</a></li>
        <li><a href="contact.html">Contact Us</a></li>
      </ul>
    </nav>
  </header>

  <main>
    <h2>Contact Us</h2>
    <p>We’d love to hear from you! Please fill out the form below to get in touch:</p>

    <form action="#" method="post">
      <label for="name">Full Name:</label><br>
      <input type="text" id="name" name="name" required minlength="2"><br><br>

      <label for="email">Email Address:</label><br>
      <input type="email" id="email" name="email" required><br><br>

      <label for="message">Message:</label><br>
      <textarea id="message" name="message" required rows="5"></textarea><br><br>

      <button type="submit">Submit</button>
    </form>

  </main>

  <footer>
    <p>&copy; 2026 Wild Water Rafting. All rights reserved.</p>
  </footer>
</body>
</html>