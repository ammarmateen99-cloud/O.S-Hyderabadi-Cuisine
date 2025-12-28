<html lang="en">
<head>
  
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <meta name="description" content="O.S Hyderabadi Cuisine — Authentic Hyderabadi & Mughlai flavours. Slow-cooked dishes using traditional spices for a royal taste." />
  <!-- Open Graph / Social -->
  <meta property="og:title" content="O.S Hyderabadi Cuisine" />
  <meta property="og:description" content="Authentic Hyderabadi & Mughlai flavours. Order delicious slow-cooked mutton & chicken specialties." />
  <meta property="og:image" content="https://images.unsplash.com/photo-1600891964599-f61ba0e24092?auto=format&fit=crop&w=1350&q=80" />
  <meta property="og:type" content="website" />
  <meta name="theme-color" content="#8b0000" />
  <link rel="icon" href="/favicon.ico" />
  <style>
    :root {
      --accent: #8b0000;
      --muted-bg: #f5f5f5;
      --card-bg: #fff;
      --text: #222;
      --radius: 10px;
    }
    html,body{ height:100%; }
    body { font-family: system-ui, -apple-system, "Segoe UI", Roboto, "Helvetica Neue", Arial; margin:0; background:var(--muted-bg); color:var(--text); -webkit-font-smoothing:antialiased; -moz-osx-font-smoothing:grayscale; }

    /* Hero Section */
    header {
      position:relative;
      color:white;
      text-align:center;
      padding:80px 20px;
      background-color:#111;
      background-image: url('https://images.unsplash.com/photo-1600891964599-f61ba0e24092?auto=format&fit=crop&w=1350&q=80');
      background-repeat:no-repeat;
      background-size:cover;
      background-position:center;
    }
    header .overlay{ position:absolute; inset:0; background:linear-gradient(rgba(0,0,0,0.45), rgba(0,0,0,0.45)); }
    header .hero-inner{ position:relative; z-index:1; max-width:900px; margin:0 auto; }
    header h1{ margin:0; font-size:2.4rem; letter-spacing:0.02em; }
    header p{ margin-top:10px; font-size:1.1rem; opacity:0.95; }

    /* Sections */
    main{ padding-bottom:40px; }
    section { padding:48px 20px; max-width:1100px; margin:0 auto; }
    section h2{ color:var(--accent); margin-bottom:18px; text-align:center; font-size:1.5rem; }
    p{ line-height:1.6; text-align:center; margin:0 auto; max-width:70ch; }

    /* Menu Grid */
    .menu-grid{ display:grid; grid-template-columns:repeat(auto-fit, minmax(220px,1fr)); gap:20px; margin-top:26px; }
    .menu-card{ background:var(--card-bg); border-radius:var(--radius); overflow:hidden; box-shadow:0 6px 18px rgba(15,15,15,0.08); transition: transform 0.22s ease, box-shadow 0.22s ease; text-align:center; display:flex; flex-direction:column; }
    .menu-card:focus-within, .menu-card:hover{ transform:translateY(-6px); box-shadow:0 14px 30px rgba(15,15,15,0.12); }
    .menu-card img{ width:100%; height:150px; object-fit:cover; display:block; }
    .menu-card .card-body{ padding:14px 12px 20px; flex:1; display:flex; flex-direction:column; justify-content:space-between; }
    .menu-card h3{ margin:8px 0 10px; color:var(--accent); font-size:1.05rem; }
    .menu-card p{ margin:0; font-size:0.96rem; color:#444; }

    /* WhatsApp Button */
    .actions{ text-align:center; margin-top:26px; }
    .whatsapp-btn{ display:inline-block; margin-top:16px; padding:12px 22px; background:#25D366; color:white; font-weight:700; border-radius:8px; font-size:1rem; transition: background .18s ease; text-decoration:none; }
    .whatsapp-btn:hover{ background:#1ebe5d; }
    .whatsapp-btn:focus{ outline:3px solid rgba(37,211,102,0.18); outline-offset:3px; }

    /* Footer */
    footer{ background:#222; color:white; text-align:center; padding:18px; margin-top:36px; font-size:0.95rem; }

    @media (max-width:600px){
      header{ padding:48px 16px; }
      header h1{ font-size:1.6rem; }
      header p{ font-size:0.98rem; }
    }
  </style>
</head>
<body>
  <header role="banner" aria-label="O.S Hyderabadi Cuisine hero">
    <div class="overlay" aria-hidden="true"></div>
    <div class="hero-inner">
    
      <p>Authentic Hyderabadi & Mughlai Flavours — South Khobar</p>
    </div>
  </header>

  <main>
    <section id="about" aria-labelledby="about-heading">
      <h2 id="about-heading">About Us</h2>
      <p>
        O.S Hyderabadi Cuisine brings you the true taste of Hyderabadi and Mughlai food.
        Inspired by royal kitchens, our dishes are slow-cooked with authentic spices
        to deliver rich flavour and unforgettable taste.
      </p>
    </section>

    <section id="menu" aria-labelledby="menu-heading">
      <h2 id="menu-heading">Our Menu</h2>
      <div class="menu-grid" role="list">
        <!-- Example menu card (duplicate/modify for more items) -->
        <article class="menu-card" role="listitem" aria-label="Mutton Talawa">
          <img src="https://images.unsplash.com/photo-1625497032872-8e3b2fcd7e6d?auto=format&fit=crop&w=800&q=80" alt="Mutton Talawa" loading="lazy" />
          <div class="card-body">
            <h3>Mutton Talawa</h3>
            <p>Delicately spiced and slow-cooked to perfection.</p>
          </div>
        </article>

        <article class="menu-card" role="listitem" aria-label="Mutton Hari Mirchi">
          <img src="https://images.unsplash.com/photo-1617196031911-1ecb3e86c998?auto=format&fit=crop&w=800&q=80" alt="Mutton Hari Mirchi" loading="lazy" />
          <div class="card-body">
            <h3>Mutton Hari Mirchi</h3>
            <p>Spicy green chili marinated mutton with royal taste.</p>
          </div>
        </article>

        <article class="menu-card" role="listitem" aria-label="Chicken Lagan">
          <img src="https://images.unsplash.com/photo-1589308078055-f0e5030b0d7c?auto=format&fit=crop&w=800&q=80" alt="Chicken Lagan" loading="lazy" />
          <div class="card-body">
            <h3>Chicken Lagan</h3>
            <p>Rich, creamy chicken curry infused with traditional spices.</p>
          </div>
        </article>

        <!-- Add other cards similarly -->
      </div>

      <div class="actions" aria-hidden="false">
        <!-- WhatsApp: ensure international number is correct (example uses +966). Use wa.me with no symbols/spaces -->
        <a class="whatsapp-btn" href="https://wa.me/966123456789" target="_blank" rel="noopener noreferrer" aria-label="Order on WhatsApp">Order on WhatsApp</a>
      </div>
    </section>
  </main>

  <footer role="contentinfo">
    <p>© O.S Hyderabadi Cuisine | South Khobar</p>
  </footer>
</body>
</html>
