O.S-Hyderabadi-Cuisine/
├─ index.html          ← Your main webpage (full HTML we built)
├─ style.css           ← Optional, for separating CSS
├─ images/             ← Folder for all dish images
│    ├─ mutton-talawa.jpg
│    ├─ mutton-hari-mirchi.jpg
│    ├─ chicken-lagan.jpg
│    └─ ...all other dishes
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>O.S Hyderabadi Cuisine</title>
  <link href="style.css" rel="stylesheet">
</head>
<body>

<header>
  <h1>O.S Hyderabadi Cuisine</h1>
  <p>Authentic Hyderabadi & Mughlai Flavours</p>
</header>

<section id="about">
  <h2>About Us</h2>
  <p>
    O.S Hyderabadi Cuisine brings you the true taste of Hyderabadi and Mughlai food.
    Inspired by royal kitchens, our dishes are slow-cooked with authentic spices
    to deliver rich flavour and unforgettable taste.
  </p>
</section>

<section id="menu">
  <h2>Our Menu</h2>
  <div class="menu-grid">

    <div class="menu-card">
      <img src="images/mutton-talawa.jpg" alt="Mutton Talawa">
      <h3>Mutton Talawa</h3>
      <p>Delicately spiced and slow-cooked to perfection.</p>
    </div>

    <div class="menu-card">
      <img src="images/mutton-hari-mirchi.jpg" alt="Mutton Hari Mirchi">
      <h3>Mutton Hari Mirchi</h3>
      <p>Spicy green chili marinated mutton with royal taste.</p>
    </div>

    <div class="menu-card">
      <img src="images/chicken-lagan.jpg" alt="Chicken Lagan">
      <h3>Chicken Lagan</h3>
      <p>Rich, creamy chicken curry infused with traditional spices.</p>
    </div>

    <div class="menu-card">
      <img src="images/chicken-rogan.jpg" alt="Chicken Rogan">
      <h3>Chicken Rogan</h3>
      <p>Classic rogan josh style chicken cooked to perfection.</p>
    </div>

    <!-- Add all other menu items similarly -->

  </div>

  <div style="text-align:center;">
    <a class="whatsapp-btn" href="https://wa.me/966123456789" target="_blank">Order on WhatsApp</a>
  </div>
</section>

<footer>
  <p>© O.S Hyderabadi Cuisine | South Khobar</p>
</footer>

</body>
</html>
body { font-family: 'Roboto', Arial, sans-serif; margin:0; background:#f5f5f5; color:#333; }
header { background:url('images/hero.jpg') no-repeat center center/cover; color:white; text-align:center; padding:80px 20px; position:relative; }
header::after { content:""; position:absolute; left:0; top:0; width:100%; height:100%; background:rgba(0,0,0,0.5); }
header h1, header p { position:relative; z-index:1; margin:0; }
header h1{ font-size:3em; } header p{ font-size:1.5em; margin-top:10px; }
section { padding:50px 20px; max-width:1000px; margin:0 auto; }
section h2{ color:#8b0000; margin-bottom:20px; text-align:center; }
p{ line-height:1.6; text-align:center; }
.menu-grid{ display:grid; grid-template-columns:repeat(auto-fit, minmax(220px,1fr)); gap:20px; margin-top:30px; }
.menu-card{ background:white; border-radius:10px; overflow:hidden; box-shadow:0 4px 8px rgba(0,0,0,0.1); transition: transform 0.3s, box-shadow 0.3s; text-align:center; }
.menu-card:hover{ transform:translateY(-5px); box-shadow:0 8px 16px rgba(0,0,0,0.2); }
.menu-card img{ width:100%; height:150px; object-fit:cover; }
.menu-card h3{ margin:15px 0 10px 0; color:#8b0000; }
.menu-card p{ padding:0 15px 15px 15px; font-size:16px; }
.whatsapp-btn{ display:inline-block; margin-top:30px; padding:15px 30px; background:#25D366; color:white; font-weight:bold; border-radius:8px; font-size:18px; transition: background 0.3s; text-decoration:none;}
.whatsapp-btn:hover{ background:#1ebe5d; }
footer{ background:#333; color:white; text-align:center; padding:20px; margin-top:40px; }
@media(max-width:600px){ header h1{ font-size:2em; } header p{ font-size:1.2em; } }
