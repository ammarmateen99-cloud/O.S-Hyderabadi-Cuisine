<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>O.S Hyderabadi Cuisine</title>
  <!-- Google Fonts -->
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
  <style>
    /* General Styles */
    body {
      font-family: 'Roboto', Arial, sans-serif;
      background: #f5f5f5;
      margin: 0;
      color: #333;
    }
    a { text-decoration: none; }

    /* Header / Hero */
    header {
      background: #8b0000;
      color: white;
      padding: 40px 20px;
      text-align: center;
    }
    header h1 {
      margin: 0;
      font-size: 2.5em;
    }
    header p {
      font-size: 1.2em;
      margin-top: 10px;
    }

    /* Sections */
    section {
      padding: 30px 20px;
      max-width: 800px;
      margin: 0 auto;
    }
    section h2, section h3 {
      color: #8b0000;
      margin-bottom: 15px;
    }
    p {
      line-height: 1.6;
    }

    /* Menu */
    .menu-category {
      margin-bottom: 30px;
    }
    .menu-category h3 {
      font-size: 1.5em;
      margin-bottom: 10px;
    }
    .menu-category ul {
      list-style: none;
      padding: 0;
    }
    .menu-category li {
      background: white;
      padding: 12px 15px;
      margin-bottom: 8px;
      border-radius: 5px;
      border: 1px solid #ddd;
      transition: background 0.3s;
    }
    .menu-category li:hover {
      background: #ffe5e5;
    }

    /* WhatsApp Button */
    .whatsapp-btn {
      display: inline-block;
      margin-top: 20px;
      padding: 12px 25px;
      background: #25D366;
      color: white;
      font-weight: bold;
      border-radius: 5px;
      transition: background 0.3s;
    }
    .whatsapp-btn:hover {
      background: #1ebe5d;
    }

    /* Footer */
    footer {
      text-align: center;
      padding: 20px;
      background: #333;
      color: white;
      margin-top: 40px;
    }

    /* Responsive */
    @media (max-width: 600px) {
      header h1 { font-size: 2em; }
      header p { font-size: 1em; }
    }
  </style>
</head>
<body>

  <!-- Hero Section -->
  <header>
    <h1>O.S Hyderabadi Cuisine</h1>
    <p>Authentic Hyderabadi & Mughlai Flavours</p>
  </header>

  <!-- About Section -->
  <section id="about">
    <h2>About Us</h2>
    <p>
      O.S Hyderabadi Cuisine brings you the true taste of Hyderabadi and Mughlai food.
      Inspired by royal kitchens, our dishes are slow-cooked with authentic spices
      to deliver rich flavour and unforgettable taste.
    </p>
  </section>

  <!-- Menu Section -->
  <section id="menu">
    <h2>Our Menu</h2>

    <div class="menu-category">
      <h3>Mutton Specialties</h3>
      <ul>
        <li>Mutton Talawa</li>
        <li>Mutton Hari Mirchi</li>
        <li>Mutton Kali Mirchi</li>
        <li>Mutton Bhunawa</li>
        <li>Mutton Badami</li>
        <li>Mutton Punjabi</li>
        <li>Mutton Masala</li>
        <li>Mutton Zafrani</li>
        <li>Mutton Bhendi</li>
      </ul>
    </div>

    <div class="menu-category">
      <h3>Chicken Specialties</h3>
      <ul>
        <li>Chicken Lagan</li>
        <li>Chicken Rogan</li>
        <li>Chicken Schezwan</li>
        <li>Chicken Tandoori Masala</li>
      </ul>
    </div>

  </section>

  <!-- Contact Section -->
  <section id="contact">
    <h2>Contact Us</h2>
    <p>
      📍 76G6+WG7, Second Street, South Khobar, Khobar 34611<br>
      📞 Call or WhatsApp for orders
    </p>
    <a class="whatsapp-btn" href="https://wa.me/966123456789" target="_blank">Order on WhatsApp</a>
  </section>

  <!-- Footer -->
  <footer>
    <p>© O.S Hyderabadi Cuisine | South Khobar</p>
  </footer>

</body>
</html>
