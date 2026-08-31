<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <title>KYAMBS KICKS | Step Into Your Style</title>

  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      scroll-behavior: smooth;
    }

    body {
      font-family: Arial, sans-serif;
      background: #f7f7f7;
      color: #111;
      line-height: 1.6;
    }

    /* NAVIGATION */

    nav {
      position: sticky;
      top: 0;
      z-index: 1000;
      background: #111;
      color: white;
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 18px 7%;
    }

    .logo {
      font-size: 22px;
      font-weight: bold;
      letter-spacing: 2px;
    }

    nav a {
      color: white;
      text-decoration: none;
      margin-left: 20px;
      font-size: 14px;
    }

    nav a:hover {
      opacity: 0.7;
    }

    /* HERO */

    .hero {
      min-height: 85vh;
      display: flex;
      align-items: center;
      justify-content: center;
      text-align: center;
      padding: 60px 20px;
      background:
        linear-gradient(rgba(0,0,0,0.55), rgba(0,0,0,0.55)),
        url("https://images.unsplash.com/photo-1542291026-7eec264c27ff?auto=format&fit=crop&w=1600&q=80")
        center/cover;
      color: white;
    }

    .hero-content {
      max-width: 800px;
    }

    .hero h1 {
      font-size: clamp(45px, 9vw, 90px);
      line-height: 1;
      margin-bottom: 20px;
      letter-spacing: -3px;
    }

    .hero p {
      font-size: 18px;
      margin-bottom: 30px;
      opacity: 0.9;
    }

    .btn {
      display: inline-block;
      background: white;
      color: #111;
      padding: 14px 25px;
      border-radius: 30px;
      text-decoration: none;
      font-weight: bold;
      transition: 0.3s;
    }

    .btn:hover {
      transform: translateY(-3px);
    }

    .btn-dark {
      background: #111;
      color: white;
    }

    /* SECTIONS */

    section {
      padding: 80px 7%;
    }

    .section-title {
      text-align: center;
      margin-bottom: 45px;
    }

    .section-title h2 {
      font-size: 38px;
      margin-bottom: 10px;
    }

    .section-title p {
      color: #777;
    }

    /* PRODUCTS */

    .products {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(230px, 1fr));
      gap: 25px;
      max-width: 1100px;
      margin: auto;
    }

    .product {
      background: white;
      border-radius: 18px;
      overflow: hidden;
      box-shadow: 0 8px 25px rgba(0,0,0,0.08);
      transition: 0.3s;
    }

    .product:hover {
      transform: translateY(-7px);
    }

    .product img {
      width: 100%;
      height: 250px;
      object-fit: cover;
      display: block;
    }

    .product-info {
      padding: 20px;
    }

    .product-info h3 {
      margin-bottom: 8px;
    }

    .price {
      font-weight: bold;
      font-size: 18px;
      margin-bottom: 15px;
    }

    /* ABOUT */

    .about {
      background: white;
    }

    .about-container {
      max-width: 850px;
      margin: auto;
      text-align: center;
    }

    .about-container p {
      color: #666;
      font-size: 17px;
    }

    /* WHY US */

    .features {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
      gap: 20px;
      max-width: 1000px;
      margin: auto;
    }

    .feature {
      background: white;
      padding: 30px;
      text-align: center;
      border-radius: 15px;
    }

    .feature-icon {
      font-size: 40px;
      margin-bottom: 15px;
    }

    .feature p {
      color: #777;
      margin-top: 8px;
    }

    /* GALLERY */

    .gallery {
      display: grid;
      grid-template-columns: repeat(3, 1fr);
      gap: 15px;
      max-width: 1100px;
      margin: auto;
    }

    .gallery img {
      width: 100%;
      height: 260px;
      object-fit: cover;
      border-radius: 15px;
    }

    /* CONTACT */

    .contact {
      background: #111;
      color: white;
      text-align: center;
    }

    .contact p {
      color: #ccc;
      margin: 10px 0 25px;
    }

    /* FOOTER */

    footer {
      background: #080808;
      color: #aaa;
      text-align: center;
      padding: 30px 20px;
      font-size: 14px;
    }

    /* MOBILE */

    @media (max-width: 700px) {

      nav {
        padding: 16px 5%;
      }

      nav .links {
        display: none;
      }

      section {
        padding: 60px 5%;
      }

      .hero {
        min-height: 80vh;
      }

      .hero h1 {
        font-size: 52px;
      }

      .gallery {
        grid-template-columns: 1fr;
      }

      .gallery img {
        height: 300px;
      }
    }
  </style>
</head>

<body>

  <!-- NAVIGATION -->

  <nav>
    <div class="logo">KYAMBS KICKS</div>

    <div class="links">
      <a href="#home">Home</a>
      <a href="#shop">Shop</a>
      <a href="#about">About</a>
      <a href="#contact">Contact</a>
    </div>
  </nav>


  <!-- HERO -->

  <section class="hero" id="home">

    <div class="hero-content">

      <h1>STEP INTO YOUR STYLE.</h1>

      <p>
        Fresh sneakers. Clean style. Everyday confidence.
      </p>

      <a href="#shop" class="btn">
        SHOP COLLECTION
      </a>

    </div>

  </section>


  <!-- PRODUCTS -->

  <section id="shop">

    <div class="section-title">

      <h2>Featured Kicks</h2>

      <p>
        Discover some of our latest styles.
      </p>

    </div>


    <div class="products">

      <div class="product">

        <img
          src="https://images.unsplash.com/photo-1542291026-7eec264c27ff?auto=format&fit=crop&w=800&q=80"
          alt="Red sneaker"
        >

        <div class="product-info">

          <h3>Classic Runner</h3>

          <div class="price">
            UGX 150,000
          </div>

          <a
            class="btn btn-dark"
            href="https://wa.me/256700000000?text=Hello%20KYAMBS%20KICKS%2C%20I%20am%20interested%20in%20the%20Classic%20Runner."
          >
            Order
          </a>

        </div>

      </div>


      <div class="product">

        <img
          src="https://images.unsplash.com/photo-1549298916-b41d501d3772?auto=format&fit=crop&w=800&q=80"
          alt="White sneaker"
        >

        <div class="product-info">

          <h3>Street Flex</h3>

          <div class="price">
            UGX 180,000
          </div>

          <a
            class="btn btn-dark"
            href="https://wa.me/256700000000?text=Hello%20KYAMBS%20KICKS%2C%20I%20am%20interested%20in%20the%20Street%20Flex."
          >
            Order
          </a>

        </div>

      </div>


      <div class="product">

        <img
          src="https://images.unsplash.com/photo-1600185365483-26d7a4cc7519?auto=format&fit=crop&w=800&q=80"
          alt="Black sneaker"
        >

        <div class="product-info">

          <h3>Urban Pro</h3>

          <div class="price">
            UGX 200,000
          </div>

          <a
            class="btn btn-dark"
            href="https://wa.me/256700000000?text=Hello%20KYAMBS%20KICKS%2C%20I%20am%20interested%20in%20the%20Urban%20Pro."
          >
            Order
          </a>

        </div>

      </div>

    </div>

  </section>


  <!-- ABOUT -->

  <section class="about" id="about">

    <div class="about-container">

      <div class="section-title">

        <h2>About KYAMBS KICKS</h2>

      </div>

      <p>
        KYAMBS KICKS is a modern sneaker store created for people
        who want fresh, stylish and quality footwear.
        We bring together clean designs and everyday comfort
        for sneaker lovers in Uganda.
      </p>

    </div>

  </section>


  <!-- WHY US -->

  <section>

    <div class="section-title">

      <h2>Why Choose Us?</h2>

    </div>


    <div class="features">

      <div class="feature">

        <div class="feature-icon">👟</div>

        <h3>Fresh Styles</h3>

        <p>
          Discover modern sneaker styles for everyday wear.
        </p>

      </div>


      <div class="feature">

        <div class="feature-icon">⭐</div>

        <h3>Quality First</h3>

        <p>
          We focus on quality and great-looking footwear.
        </p>

      </div>


      <div class="feature">

        <div class="feature-icon">📱</div>

        <h3>Easy Ordering</h3>

        <p>
          Contact us easily and place your order online.
        </p>

      </div>


      <div class="feature">

        <div class="feature-icon">🇺🇬</div>

        <h3>Made For Uganda</h3>

        <p>
          A sneaker experience designed for local customers.
        </p>

      </div>

    </div>

  </section>


  <!-- GALLERY -->

  <section>

    <div class="section-title">

      <h2>Sneaker Gallery</h2>

      <p>Explore the KYAMBS KICKS style.</p>

    </div>


    <div class="gallery">

      <img
        src="https://images.unsplash.com/photo-1552346154-21d32810aba3?auto=format&fit=crop&w=900&q=80"
        alt="Sneakers"
      >

      <img
        src="https://images.unsplash.com/photo-1460353581641-37baddab0fa2?auto=format&fit=crop&w=900&q=80"
        alt="Sneakers"
      >

      <img
        src="https://images.unsplash.com/photo-1495555961986-6d4c1ecb7be3?auto=format&fit=crop&w=900&q=80"
        alt="Sneakers"
      >

    </div>

  </section>


  <!-- CONTACT -->

  <section class="contact" id="contact">

    <div class="section-title">

      <h2>Ready For Your Next Pair?</h2>

      <p>
        Contact KYAMBS KICKS and find your next favorite sneakers.
      </p>

      <a
        class="btn"
        href="https://wa.me/256700000000"
      >
        WhatsApp Us
      </a>

    </div>

  </section>


  <!-- FOOTER -->

  <footer>

    <p>
      © 2026 KYAMBS KICKS. All rights reserved.
    </p>

    <p>
      Uganda
    </p>

  </footer>

</body>
</html>
