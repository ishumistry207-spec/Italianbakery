<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Italian Bakery — Fresh • Local • Homemade</title>
  <meta name="description" content="Italian Bakery (Surat) — Fresh daily cakes, pastries, cookies and brownies. Order on WhatsApp or visit our shop.">
  <meta name="theme-color" content="#f7efe6">
  <link rel="icon" href="favicon.png">
  <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;600;700&display=swap" rel="stylesheet">
  <style>
    :root{
      --bg:#fffaf3; --card:#ffffff; --accent:#c96b4c; --muted:#6b5b4a; --dark:#2b1f1a;
      --maxw:1100px;
    }
    *{box-sizing:border-box}
    body{font-family:Montserrat,system-ui,-apple-system,Segoe UI,Roboto,"Helvetica Neue",Arial; margin:0; background:var(--bg); color:var(--dark);}
    .container{max-width:var(--maxw); margin:0 auto; padding:24px}
    header{display:flex;align-items:center;justify-content:space-between;padding:18px 0}
    .logo{display:flex;gap:12px;align-items:center}
    .logo img{width:64px;height:64px;object-fit:cover;border-radius:12px;box-shadow:0 4px 12px rgba(0,0,0,0.08)}
    .brand{font-weight:700;font-size:20px}
    nav a{margin-left:14px;text-decoration:none;color:var(--muted);font-weight:600}

    .hero{display:grid;grid-template-columns:1fr 420px;gap:28px;align-items:center;margin-top:12px}
    .hero-left h1{font-size:36px;margin:0 0 12px;line-height:1.05}
    .hero-left p{margin:0 0 18px;color:var(--muted)}
    .cta{display:flex;gap:12px}
    .btn{background:var(--accent);color:#fff;padding:12px 18px;border-radius:10px;text-decoration:none;font-weight:700}
    .ghost{background:transparent;border:2px solid var(--accent);color:var(--accent);padding:10px 16px;border-radius:10px;text-decoration:none;font-weight:700}

    .card{background:var(--card);border-radius:14px;padding:14px;box-shadow:0 6px 18px rgba(0,0,0,0.04)}
    .hero-right img{width:100%;border-radius:12px;object-fit:cover}

    section{margin-top:28px}
    h2{margin:0 0 12px}

    .products-grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(200px,1fr));gap:16px}
    .product{background:linear-gradient(180deg,#fff,#fff);padding:12px;border-radius:12px;border:1px solid rgba(0,0,0,0.03);display:flex;gap:12px;align-items:center}
    .product img{width:84px;height:64px;object-fit:cover;border-radius:8px}
    .p-info{flex:1}
    .p-name{font-weight:700}
    .p-price{color:var(--muted);font-weight:600}

    .highlight{display:flex;gap:12px;align-items:center}
    .badge{background:var(--accent);color:#fff;padding:6px 10px;border-radius:20px;font-weight:700}

    .gallery{display:grid;grid-template-columns:repeat(auto-fit,minmax(150px,1fr));gap:10px}
    .gallery img{width:100%;height:110px;object-fit:cover;border-radius:8px}

    .contact{display:grid;grid-template-columns:1fr 340px;gap:18px;align-items:start}
    .map{height:260px;border-radius:12px;overflow:hidden}
    iframe{width:100%;height:100%;border:0}

    footer{margin-top:30px;padding:18px 0;color:var(--muted);display:flex;justify-content:space-between;align-items:center}

    /* responsive */
    @media (max-width:900px){.hero{grid-template-columns:1fr}.contact{grid-template-columns:1fr}.hero-right{order:-1}}
  </style>
</head>
<body>
  <div class="container">
    <header>
      <div class="logo">
        <img src="placeholder-logo.png" alt="Italian Bakery logo">
        <div>
          <div class="brand">Italian Bakery</div>
          <div style="font-size:12px;color:var(--muted)">Since 2019 • Surat</div>
        </div>
      </div>
      <nav>
        <a href="#about">About</a>
        <a href="#products">Products</a>
        <a href="#gallery">Gallery</a>
        <a href="#order">Order</a>
        <a href="#contact">Contact</a>
      </nav>
    </header>

    <section class="hero">
      <div class="hero-left">
        <h1>Freshly baked every day — warm, local, and made with love</h1>
        <p>Italian Bakery is a neighborhood bakery in Surat serving popular pastries, cakes, brownies and cookies. Try our signature Black Forest and White Forest pastries today.</p>
        <div class="cta">
          <a class="btn" href="https://wa.me/919999999999?text=Hi%20Italian%20Bakery%2C%20I%20would%20like%20to%20place%20an%20order" target="_blank">Order on WhatsApp</a>
          <a class="ghost" href="#menu">See Menu</a>
        </div>
        <div style="margin-top:14px;color:var(--muted);font-size:14px">Open: 7:00 AM – 9:30 PM &nbsp; | &nbsp; Call: <a href="tel:+919999999999" style="color:var(--accent);text-decoration:none">+91 99999 99999</a></div>
      </div>
      <div class="hero-right card">
        <img src="placeholder-hero.jpg" alt="Fresh pastries and cakes">
      </div>
    </section>

    <section id="about">
      <h2>About Italian Bakery</h2>
      <div class="card">
        <p>Italian Bakery is a neighborhood bakery established in 2019 by Mr. Dipak. We specialise in fresh pastries, celebration cakes and everyday bakery items made from high-quality ingredients. Our goal is to be the community's favorite place for daily treats and special occasions.</p>
        <div style="display:flex;gap:12px;margin-top:12px;align-items:center">
          <div class="badge">Local Favorite</div>
          <div style="color:var(--muted)">Signature: Black Forest, White Forest</div>
        </div>
      </div>
    </section>

    <section id="products">
      <h2>Products & Prices</h2>
      <div class="products-grid">
        <div class="product">
          <img src="p-sweet-layer.jpg" alt="Sweet Layer Cake">
          <div class="p-info">
            <div class="p-name">Sweet Layer Cake (500g)</div>
            <div class="p-price">₹90</div>
          </div>
        </div>
        <div class="product">
          <img src="p-eggless.jpg" alt="Eggless Cake">
          <div class="p-info">
            <div class="p-name">Eggless Cake</div>
            <div class="p-price">₹90</div>
          </div>
        </div>
        <div class="product">
          <img src="p-mawa.jpg" alt="Mawa Cake">
          <div class="p-info">
            <div class="p-name">Mawa Cake</div>
            <div class="p-price">₹100</div>
          </div>
        </div>
        <div class="product">
          <img src="p-white-forest.jpg" alt="White Forest Pastry">
          <div class="p-info">
            <div class="p-name">White Forest Pastry</div>
            <div class="p-price">₹140</div>
          </div>
        </div>
        <div class="product">
          <img src="p-black-forest.jpg" alt="Black Forest Pastry">
          <div class="p-info">
            <div class="p-name">Black Forest Pastry</div>
            <div class="p-price">₹140</div>
          </div>
        </div>
        <div class="product">
          <img src="p-brownie.jpg" alt="Brownie">
          <div class="p-info">
            <div class="p-name">Brownie</div>
            <div class="p-price">₹200</div>
          </div>
        </div>
        <div class="product">
          <img src="p-cookies.jpg" alt="Cookies">
          <div class="p-info">
            <div class="p-name">Cookies</div>
            <div class="p-price">₹200</div>
          </div>
        </div>
      </div>
    </section>

    <section id="gallery">
      <h2>Gallery</h2>
      <div class="gallery">
        <img src="g-1.jpg" alt="Product 1">
        <img src="g-2.jpg" alt="Product 2">
        <img src="g-3.jpg" alt="Product 3">
        <img src="g-4.jpg" alt="Shop interior">
        <img src="g-5.jpg" alt="Shop outside">
        <img src="g-6.jpg" alt="Baking">
      </div>
    </section>

    <section id="order">
      <h2>Order & Offers</h2>
      <div class="card">
        <p>To place an order, please message us on WhatsApp. We accept advance orders for celebration cakes and bulk snack packs. For urgent orders, call us directly.</p>
        <ul>
          <li>WhatsApp Orders: <a href="https://wa.me/919999999999?text=Hi%20Italian%20Bakery%2C%20I%20want%20to%20order" target="_blank">Message on WhatsApp</a></li>
          <li>Phone: <a href="tel:+919999999999">+91 99999 99999</a></li>
          <li>Offers: Combo Pack (Pastry + Cookie) — Ask in store for today's offer.</li>
        </ul>
      </div>
    </section>

    <section id="contact">
      <h2>Contact & Visit Us</h2>
      <div class="contact">
        <div>
          <div class="card">
            <p><strong>Address:</strong> Insert full address here, Surat, Gujarat</p>
            <p><strong>Opening Hours:</strong> 7:00 AM – 9:30 PM</p>
            <p><strong>Phone:</strong> <a href="tel:+919999999999">+91 99999 99999</a></p>
            <p><strong>Follow us:</strong> <a href="https://instagram.com/your_instagram" target="_blank">Instagram</a> • <a href="#">Facebook</a></p>
            <p><strong>Website:</strong> <a href="#">www.italianbakery.example</a></p>
          </div>
          <div style="margin-top:12px;color:var(--muted)">
            <p><strong>Our commitment:</strong> Freshness, quality, and community focus.</p>
          </div>
        </div>
        <div class="map card">
          <!-- Replace the src in iframe with your Google Maps embed link -->
          <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d..." allowfullscreen="" loading="lazy"></iframe>
        </div>
      </div>
    </section>

    <footer>
      <div>© Italian Bakery • Since 2019 • Surat</div>
      <div style="font-size:13px;color:var(--muted)">Designed with ❤️ — Contact: <a href="mailto:info@italianbakery.example">info@italianbakery.example</a></div>
    </footer>
  </div>
</body>
</html>
