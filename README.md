<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Wozz Store - Instant Diamond Top-Up</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background: 
        linear-gradient(rgba(0, 0, 0, 0.7), rgba(0, 0, 0, 0.7)),
        url('1000067618.jpg') no-repeat center center/cover,
        url('https://i.ibb.co/yf6fzTb/forest-bg.jpg') no-repeat center center/cover;
      color: white;
      padding: 20px;
      min-height: 100vh;
    }
    .container {
      background: rgba(0, 0, 0, 0.8);
      padding: 25px;
      border-radius: 16px;
      max-width: 800px;
      margin: auto;
      box-shadow: 0 8px 32px rgba(0, 0, 0, 0.3);
      border: 1px solid rgba(255, 255, 255, 0.1);
      backdrop-filter: blur(10px);
    }
    h1 {
      text-align: center;
      color: #00ffcc;
      margin-bottom: 5px;
      font-size: 2.5em;
      text-shadow: 0 0 10px rgba(0, 255, 204, 0.5);
    }
    h2 {
      text-align: center;
      color: #ffffff;
      margin-top: 0;
      font-size: 1.4em;
    }
    .tagline {
      text-align: center;
      color: #00ffcc;
      font-weight: bold;
      margin-bottom: 20px;
    }
    ul {
      list-style: none;
      padding-left: 0;
    }
    li {
      margin-bottom: 8px;
      padding: 5px 0;
    }
    .section {
      margin-top: 30px;
      padding: 20px;
      background: rgba(255, 255, 255, 0.05);
      border-radius: 12px;
      border: 1px solid rgba(255, 255, 255, 0.1);
    }
    .section-title {
      color: #00ffcc;
      border-bottom: 2px solid #00ffcc;
      padding-bottom: 8px;
      margin-top: 0;
    }
    input, select, button {
      width: 100%;
      padding: 12px;
      margin: 10px 0;
      border-radius: 8px;
      border: none;
      font-size: 16px;
      box-sizing: border-box;
    }
    input, select {
      background: rgba(255, 255, 255, 0.9);
      color: #333;
      border: 2px solid transparent;
    }
    input:focus, select:focus {
      outline: none;
      border-color: #00ffcc;
      background: white;
    }
    button {
      background: linear-gradient(135deg, #00ffcc, #00ddb3);
      color: #000;
      font-weight: bold;
      cursor: pointer;
      transition: all 0.3s ease;
      font-size: 18px;
      padding: 15px;
    }
    button:hover {
      background: linear-gradient(135deg, #00ddb3, #00ffcc);
      transform: translateY(-2px);
      box-shadow: 0 5px 15px rgba(0, 255, 204, 0.4);
    }
    .contact-info {
      text-align: center;
      background: rgba(0, 255, 204, 0.1);
      padding: 15px;
      border-radius: 10px;
      margin: 20px 0;
      border: 1px solid rgba(0, 255, 204, 0.3);
    }
    .contact-number {
      font-size: 1.2em;
      font-weight: bold;
      color: #00ffcc;
      margin: 10px 0;
    }
    .features {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 15px;
      margin: 20px 0;
    }
    .feature-item {
      background: rgba(255, 255, 255, 0.05);
      padding: 15px;
      border-radius: 8px;
      text-align: center;
      border: 1px solid rgba(255, 255, 255, 0.1);
    }
    .highlight {
      color: #00ffcc;
      font-weight: bold;
    }
    .discount-badge {
      background: #ff4444;
      color: white;
      padding: 2px 8px;
      border-radius: 12px;
      font-size: 0.8em;
      margin-left: 5px;
    }
    .special-badge {
      background: #ffaa00;
      color: black;
      padding: 2px 8px;
      border-radius: 12px;
      font-size: 0.8em;
      margin-left: 5px;
      font-weight: bold;
    }
    .background-info {
      position: fixed;
      bottom: 10px;
      right: 10px;
      background: rgba(0, 0, 0, 0.7);
      padding: 10px;
      border-radius: 8px;
      font-size: 0.8em;
      color: #ccc;
      z-index: 1000;
    }
    .first-time-offers {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 15px;
      margin: 20px 0;
    }
    .offer-card {
      background: rgba(0, 255, 204, 0.1);
      padding: 15px;
      border-radius: 10px;
      border: 1px solid rgba(0, 255, 204, 0.3);
      text-align: center;
    }
    .offer-diamonds {
      font-size: 1.2em;
      font-weight: bold;
      color: #00ffcc;
      margin-bottom: 8px;
    }
    .offer-price {
      font-size: 1.1em;
      color: #ffffff;
    }
    .original-price {
      text-decoration: line-through;
      color: #ff4444;
      margin-right: 8px;
    }
    .current-price {
      color: #00ffcc;
      font-weight: bold;
    }
    .offer-note {
      font-size: 0.8em;
      color: #ffaa00;
      margin-top: 5px;
    }
    .bonus-note {
      text-align: center;
      background: rgba(255, 170, 0, 0.2);
      padding: 10px;
      border-radius: 8px;
      margin: 15px 0;
      border: 1px solid rgba(255, 170, 0, 0.4);
      color: #ffaa00;
      font-weight: bold;
    }
  </style>
</head>
<body>
  <div class="background-info">
    Background: 1000067618.jpg
  </div>
  
  <div class="container">
    <h1>Wozz Store</h1>
    <h2>INSTANT DIAMOND TOP-UP</h2>
    <p class="tagline">Via ID & Server ✅ Fast & Secure Delivery</p>

    <div class="contact-info">
      <h3 class="section-title">Contact Us</h3>
      <div class="contact-number">📞 +91 93398 74875</div>
      <p>Available 24/7 for your queries</p>
    </div>

    <div class="bonus-note">
      🎉 BONUS DIAMONDS ON EVERY PURCHASE! EXTRA VALUE GUARANTEED! 🎉
    </div>

    <div class="features">
      <div class="feature-item">
        <div class="highlight">⚡ Instant Delivery</div>
        <small>Within 5 minutes</small>
      </div>
      <div class="feature-item">
        <div class="highlight">🛡️ 100% Secure</div>
        <small>Safe transactions</small>
      </div>
      <div class="feature-item">
        <div class="highlight">💰 Best Prices</div>
        <small>Lowest rates guaranteed</small>
      </div>
    </div>

    <!-- First Time Recharge Offers Section -->
    <div class="section">
      <h3 class="section-title">🎁 First Time Recharge Offers</h3>
      <p style="text-align: center; color: #ffaa00; margin-bottom: 20px;">
        Special bonuses for first-time customers! 🚀
      </p>
      
      <div class="first-time-offers">
        <div class="offer-card">
          <div class="offer-diamonds">100 💎 + Bonus</div>
          <div class="offer-price">
            <span class="current-price">₹80</span>
          </div>
          <div class="offer-note">Best Value Offer!</div>
        </div>
        
        <div class="offer-card">
          <div class="offer-diamonds">300 💎 + Bonus</div>
          <div class="offer-price">
            <span class="current-price">₹220</span>
          </div>
          <div class="offer-note">Popular Choice!</div>
        </div>
        
        <div class="offer-card">
          <div class="offer-diamonds">500 💎 + Bonus</div>
          <div class="offer-price">
            <span class="current-price">₹350</span>
          </div>
          <div class="offer-note">Great Deal!</div>
        </div>
        
        <div class="offer-card">
          <div class="offer-diamonds">1000 💎 + Bonus</div>
          <div class="offer-price">
            <span class="current-price">₹710</span>
          </div>
          <div class="offer-note">Maximum Savings!</div>
        </div>
      </div>
    </div>

    <div class="section">
      <h3 class="section-title">Place Your Order</h3>
      <form id="orderForm">
        <label for="mlbbId">MLBB ID:</label>
        <input type="text" id="mlbbId" required placeholder="Enter your MLBB ID">

        <label for="server">Server:</label>
        <input type="text" id="server" required placeholder="Enter your server">

        <label for="diamonds">Select Diamond Pack:</label>
        <select id="diamonds" required>
          <option value="5💎 = ₹15">5💎 = ₹15</option>
          <option value="11💎 = ₹25">11💎 = ₹25</option>
          <option value="22💎 = ₹45">22💎 = ₹45</option>
          <option value="55💎 = ₹80">55💎 = ₹80</option>
          <option value="86💎 = ₹115">86💎 = ₹115</option>
          <option value="110💎 = ₹150">110💎 = ₹150</option>
          <option value="165💎 = ₹225">165💎 = ₹225</option>
          <option value="172💎 = ₹240">172💎 = ₹240</option>
          <option value="Weekly Pass = ₹139">Weekly Pass = ₹139 <span class="discount-badge">POPULAR</span></option>
          <option value="2x Weekly Pass = ₹278">2x Weekly Pass = ₹278 <span class="discount-badge">SAVE ₹10</span></option>
          <option value="First Time 100💎 = ₹80">First Time 100💎 = ₹80 <span class="special-badge">BEST OFFER</span></option>
          <option value="First Time 300💎 = ₹220">First Time 300💎 = ₹220 <span class="special-badge">BEST OFFER</span></option>
          <option value="First Time 500💎 = ₹350">First Time 500💎 = ₹350 <span class="special-badge">BEST OFFER</span></option>
          <option value="First Time 1000💎 = ₹710">First Time 1000💎 = ₹710 <span class="special-badge">BEST OFFER</span></option>
        </select>

        <label for="payment">Payment Method:</label>
        <select id="payment" required>
          <option value="Fampay">Fampay</option>
          <option value="PhonePe">PhonePe</option>
          <option value="GPay">GPay</option>
          <option value="Other UPI">Other UPI</option>
        </select>

        <button type="submit">🚀 Place Order Now</button>
      </form>
    </div>

    <div class="section">
      <h3 class="section-title">Payment Methods</h3>
      <p>✅ UPI, Fampay, PhonePe, GPay or any UPI app</p>
      <p>💳 All major payment methods accepted</p>
    </div>

    <div class="section">
      <h3 class="section-title">Why Choose Wozz Store?</h3>
      <ul>
        <li>✅ Instant diamond delivery within 5 minutes</li>
        <li>✅ 24/7 customer support</li>
        <li>✅ Best prices in the market</li>
        <li>✅ Secure and reliable service</li>
        <li>✅ Thousands of satisfied customers</li>
        <li>✅ Weekly Pass available at amazing price</li>
        <li>✅ Special first-time recharge bonuses</li>
        <li>✅ Bonus diamonds on every purchase</li>
      </ul>
    </div>
  </div>

  <script>
    document.getElementById('orderForm').addEventListener('submit', function(e) {
      e.preventDefault();
      const id = document.getElementById('mlbbId').value;
      const server = document.getElementById('server').value;
      const diamonds = document.getElementById('diamonds').value;
      const payment = document.getElementById('payment').value;
      
      const message = `Hello! I'd like to place an order with Wozz Store.\n\nMLBB ID: ${id}\nServer: ${server}\nDiamond Pack: ${diamonds}\nPayment Method: ${payment}\n\nPlease process my order.`;
      const whatsappURL = `https://wa.me/919339874875?text=${encodeURIComponent(message)}`;
      window.open(whatsappURL, '_blank');
    });

    // Add some interactive effects
    document.addEventListener('DOMContentLoaded', function() {
      const inputs = document.querySelectorAll('input, select');
      inputs.forEach(input => {
        input.addEventListener('focus', function() {
          this.style.transform = 'scale(1.02)';
        });
        input.addEventListener('blur', function() {
          this.style.transform = 'scale(1)';
        });
      });
    });
  </script>
</body>
</html>
