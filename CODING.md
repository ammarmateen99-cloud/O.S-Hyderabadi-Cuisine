<meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>O.S Hyderabadi Cuisine</title>
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
  <style>
    body {
      font-family: 'Roboto', Arial, sans-serif;
      margin: 0;
      background: #f5f5f5;
      color: #333;
    }

    /* Hero Section */
    header {
      background: url('https://images.unsplash.com/photo-1600891964599-f61ba0e24092?auto=format&fit=crop&w=1350&q=80') no-repeat center center/cover;
      color: white;
      text-align: center;
      padding: 80px 20px;
      position: relative;
    }
    header::after {
      content: "";
      position: absolute;
      left:0; top:0;
      width:100%; height:100%;
      background: rgba(0,0,0,0.5);
    }
    header h1, header p {
      position: relative;
      z-index: 1;
      margin: 0;
    }
    header h1 { font-size: 3em; }
    header p { font-size: 1.5em; margin-top: 10px; }

    /* Sections */
    section { padding: 50px 20px; max-width: 1000px; margin: 0 auto; }
    section h2 { color: #8b0000; margin-bottom: 20px; text-align: center; }
    p { line-height: 1.6; text-align: center; }

    /* Menu Grid */
    .menu-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
      gap: 20px;
      margin-top: 30px;
    }

    .menu-card {
      background: white;
      border-radius: 10px;
      overflow: hidden;
      box-shadow: 0 4px 8px rgba(0,0,0,0.1);
      transition: transform 0.3s, box-shadow 0.3s;
      text-align: center;
    }
    .menu-card:hover {
      transform: translateY(-5px);
      box-shadow: 0 8px 16px rgba(0,0,0,0.2);
    }
    .menu-card img {
      width: 100%;
      height: 150px;
      object-fit: cover;
    }
    .menu-card h3 {
      margin: 15px 0 10px 0;
      color: #8b0000;
    }
    .menu-card p {
      padding: 0 15px 15px 15px;
      font-size: 16px;
    }

    /* WhatsApp Button */
    .whatsapp-btn {
      display: inline-block;
      margin-top: 30px;
      padding: 15px 30px;
      background: #25D366;
      color: white;
      font-weight: bold;
      border-radius: 8px;
      font-size: 18px;
      transition: background 0.3s;
    }
    .whatsapp-btn:hover { background: #1ebe5d; }

    /* Footer */
    footer {
      background: #333;
      color: white;
      text-align: center;
      padding: 20px;
      margin-top: 40px;
    }

    @media (max-width:600px){
      header h1 { font-size: 2em; }
      header p { font-size: 1.2em; }
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
    <div class="menu-grid">

      <!-- Mutton Specialties -->
      <div class="menu-card">
        <img src="https://images.unsplash.com/photo-1600891964599-f61ba0e24092?auto=format&fit=crop&w=500&q=80" alt="Mutton Talawa">
        <h3>Mutton Talawa</h3>
        <p>Delicately spiced and slow-cooked to perfection.</p>
      </div>
      <div class="menu-card">
        <img src="https://images.unsplash.com/photo-1617196031911-1ecb3e86c998?auto=format&fit=crop&w=500&q=80" alt="Mutton Hari Mirchi">
        <h3>Mutton Hari Mirchi</h3>
        <p>Spicy green chili marinated mutton with royal taste.</p>
      </div>
      <div class="menu-card">
        <img src="https://images.unsplash.com/photo-1598511725241-c9c1c2e36421?auto=format&fit=crop&w=500&q=80" alt="Mutton Kali Mirchi">
        <h3>Mutton Kali Mirchi</h3>
        <p>Peppery black chili mutton, rich and flavorful.</p>
      </div>
      <div class="menu-card">
        <img src="https://images.unsplash.com/photo-1604945007611-459b0376a930?auto=format&fit=crop&w=500&q=80" alt="Mutton Bhunawa">
        <h3>Mutton Bhunawa</h3>
        <p>Slow-cooked mutton with traditional bhunawa spices.</p>
      </div>
      <div class="menu-card">
        <img src="https://images.unsplash.com/photo-1617196031911-1ecb3e86c998?auto=format&fit=crop&w=500&q=80" alt="Mutton Badami">
        <h3>Mutton Badami</h3>
        <p>Rich almond-flavored mutton for royal taste.</p>
      </div>
      <div class="menu-card">
        <img src="https://images.unsplash.com/photo-1604945007611-459b0376a930?auto=format&fit=crop&w=500&q=80" alt="Mutton Punjabi">
        <h3>Mutton Punjabi</h3>
        <p>Classic Punjabi-style mutton, aromatic and spicy.</p>
      </div>
      <div class="menu-card">
        <img src="https://images.unsplash.com/photo-1598511725241-c9c1c2e36421?auto=format&fit=crop&w=500&q=80" alt="Mutton Masala">
        <h3>Mutton Masala</h3>
        <p>Mutton cooked with a rich, spicy masala gravy.</p>
      </div>
      <div class="menu-card">
        <img src="https://images.unsplash.com/photo-1600891964599-f61ba0e24092?auto=format&fit=crop&w=500&q=80" alt="Mutton Zafrani">
        <h3>Mutton Zafrani</h3>
        <p>Mutton delicately flavored with saffron and spices.</p>
      </div>
      <div class="menu-card">
        <img src="https://images.unsplash.com/photo-1617196031911-1ecb3e86c998?auto=format&fit=crop&w=500&q=80" alt="Mutton Bhendi">
        <h3>Mutton Bhendi</h3>
        <p>Mutton cooked with okra and traditional spices.</p>
      </div>

      <!-- Chicken Specialties -->
      <div class="menu-card">
        <img src="https://images.unsplash.com/photo-1589308078055-f0e5030b0d7c?auto=format&fit=crop&w=500&q=80" alt="Chicken Lagan">
        <h3>Chicken Lagan</h3>
        <p>Rich, creamy chicken curry infused with traditional spices.</p>
      </div>
      <div class="menu-card">
        <img src="https://images.unsplash.com/photo-1600718377425-9b55a5a27b87?auto=format&fit=crop&w=500&q=80" alt="Chicken Rogan">
        <h3>Chicken Rogan</h3>
        <p>Classic rogan josh style chicken cooked to perfection.</p>
      </div>
      <div class="menu-card">
        <img src="https://images.unsplash.com/photo-1604945007611-459b0376a930?auto=format&fit=crop&w=500&q=80" alt="Chicken Schezwan">
        <h3>Chicken Schezwan</h3>
        <p>Spicy Schezwan-style chicken with bold flavors.</p>
      </div>
      <div class="menu-card">
        <img src="https://images.unsplash.com/photo-1598511725241-c9c1c2e36421?auto=format&fit=crop&w=500&q=80" alt="Chicken Tandoori Masala">
        <h3>Chicken Tandoori Masala</h3>
        <p>Grilled chicken marinated in traditional tandoori spices.</p>
      </div>

    </div>

    <div style="text-align:center;">
      <a class="whatsapp-btn" href="https://wa.me/966123456789" target="_blank">Order on WhatsApp</a>
    </div>
  </section>

  <!-- Footer -->
  <footer>
    <p>© O.S Hyderabadi Cuisine | South Khobar</p>
  </footer>

</body>
</html>
