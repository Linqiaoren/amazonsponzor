<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>🔥 Top Amazon Deals</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>🔥 Top Amazon Deals</h1>
    <p>Exclusive picks you don't want to miss</p>
  </header>

  <main class="products">
    <div class="product-card">
      <img src="https://m.media-amazon.com/images/I/81NI0UFfayL._AC_SL1500_.jpg" alt="Wireless Earbuds">
      <h2>Wireless Bluetooth Earbuds</h2>
      <p>High-quality sound, noise cancellation, and 24h battery life. Great for work and workouts.</p>
      <a href="https://www.amazon.com/dp/B09F9Z9J2V" target="_blank" class="buy-button">View on Amazon</a>
    </div>

    <div class="product-card">
      <img src="https://m.media-amazon.com/images/I/71kxa1-0mfL._AC_SL1500_.jpg" alt="Kindle Paperwhite">
      <h2>Kindle Paperwhite</h2>
      <p>Read your favorite books anywhere with glare-free screen and waterproof design.</p>
      <a href="https://www.amazon.com/dp/B08N36XNTT" target="_blank" class="buy-button">View on Amazon</a>
    </div>

    <div class="product-card">
      <img src="https://m.media-amazon.com/images/I/71e0Pu-hTPL._AC_SL1500_.jpg" alt="Smart Plug">
      <h2>Amazon Smart Plug</h2>
      <p>Control any device with Alexa. Easy setup, voice controlled, works with routines.</p>
      <a href="https://www.amazon.com/dp/B089DR29T6" target="_blank" class="buy-button">View on Amazon</a>
    </div>
  </main>

  <footer>
    <p>© 2025 Amazon Deals Promo | Not affiliated with Amazon.com</p>
  </footer>
</body>
</html>

body {
  margin: 0;
  font-family: 'Arial', sans-serif;
  background-color: #f7f7f7;
  color: #333;
  text-align: center;
}

header {
  background-color: #232f3e;
  color: white;
  padding: 40px 20px;
}

.products {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 30px;
  padding: 30px 20px;
}

.product-card {
  background-color: white;
  width: 300px;
  border-radius: 10px;
  box-shadow: 0 4px 10px rgba(0,0,0,0.1);
  padding: 20px;
  text-align: left;
}

.product-card img {
  width: 100%;
  border-radius: 8px;
  margin-bottom: 15px;
}

.buy-button {
  display: inline-block;
  margin-top: 10px;
  padding: 12px 20px;
  background-color: #ff9900;
  color: white;
  text-decoration: none;
  font-weight: bold;
  border-radius: 5px;
}

.buy-button:hover {
  background-color: #e68a00;
}

footer {
  background-color: #eee;
  padding: 20px;
  font-size: 14px;
  color: #666;
}
