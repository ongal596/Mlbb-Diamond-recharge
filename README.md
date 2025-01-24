<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>MLBB Diamond Recharge</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <header>
    <div class="container">
      <h1>MLBB Diamond Recharge</h1>
      <nav>
        <a href="#home">Home</a>
        <a href="#how-it-works">How It Works</a>
        <a href="#recharge">Recharge</a>
        <a href="#contact">Contact Us</a>
      </nav>
    </div>
  </header>

  <section id="home">
    <div class="container">
      <h2>Fast & Secure Diamond Recharge</h2>
      <p>Recharge Mobile Legends Diamonds instantly and securely. Choose your desired package and enjoy exclusive offers!</p>
    </div>
  </section>

  <section id="recharge">
    <div class="container">
      <h2>Recharge Now</h2>
      <form action="#" method="POST">
        <label for="player-id">Player ID:</label>
        <input type="text" id="player-id" name="player-id" required>
        
        <label for="server-id">Server ID:</label>
        <input type="text" id="server-id" name="server-id" required>
        
        <label for="diamond-package">Diamond Package:</label>
        <select id="diamond-package" name="diamond-package" required>
          <option value="50">50 Diamonds - $0.99</option>
          <option value="100">100 Diamonds - $1.99</option>
          <option value="250">250 Diamonds - $4.99</option>
          <option value="500">500 Diamonds - $9.99</option>
        </select>
        
        <label for="payment-method">Payment Method:</label>
        <select id="payment-method" name="payment-method" required>
          <option value="paypal">PayPal</option>
          <option value="credit-card">Credit/Debit Card</option>
          <option value="mobile-wallet">Mobile Wallet</option>
        </select>
        
        <button type="submit">Recharge Now</button>
      </form>
    </div>
  </section>

  <section id="how-it-works">
    <div class="container">
      <h2>How It Works</h2>
      <ol>
        <li>Enter your Player ID and Server ID.</li>
        <li>Select your desired diamond package.</li>
        <li>Choose a payment method and complete the payment.</li>
        <li>Diamonds will be added to your account instantly!</li>
      </ol>
    </div>
  </section>

  <section id="contact">
    <div class="container">
      <h2>Contact Us</h2>
      <p>If you have any questions or issues, feel free to reach out:</p>
      <ul>
        <li>Email: support@mlbbrecharge.com</li>
        <li>Live Chat: Available 24/7</li>
        <li>Follow us on social media for updates and offers!</li>
      </ul>
    </div>
  </section>

  <footer>
    <div class="container">
      <p>&copy; 2025 MLBB Diamond Recharge. All Rights Reserved.</p>
    </div>
  </footer>
</body>
</html>
