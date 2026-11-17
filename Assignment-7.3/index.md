<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Responsive Product Listing | Assignment 7.3</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>

  <!-- Page Header -->
  <header class="page-header">
    <h1>CodeCraft Tech Store &mdash; Product Listing</h1>
    <p>Responsive product catalog utilizing CSS Flexbox, wrapping, gap spacing, and flex sizing properties.</p>
  </header>

  <hr />

  <!-- Main Product Listing Container -->
  <main>
    <section aria-labelledby="catalog-heading">
      <h2 id="catalog-heading" class="sr-only">Featured Developer Hardware &amp; Accessories</h2>

      <!-- Flexbox Container with flex-wrap -->
      <div class="product-grid">

        <!-- Product 1 -->
        <article class="product-card">
          <div class="product-img-container">
            <img src="images/stand.jpg" alt="Ergonomic Aluminum Laptop Stand" class="product-img" />
          </div>
          <div class="product-info">
            <h3>Aluminum Laptop Stand</h3>
            <p class="product-price">$49.00</p>
            <p class="product-desc">Ergonomic adjustable stand for improved airflow and posture.</p>
          </div>
          <button class="btn-buy">Add to Cart</button>
        </article>

        <!-- Product 2 -->
        <article class="product-card">
          <div class="product-img-container">
            <img src="images/keyboard.jpg" alt="Mechanical Wireless Keyboard" class="product-img" />
          </div>
          <div class="product-info">
            <h3>Mechanical Wireless Keyboard</h3>
            <p class="product-price">$89.00</p>
            <p class="product-desc">Tactile switches with customizable RGB backlighting and Bluetooth.</p>
          </div>
          <button class="btn-buy">Add to Cart</button>
        </article>

        <!-- Product 3 -->
        <article class="product-card">
          <div class="product-img-container">
            <img src="images/mouse.jpg" alt="Ergonomic Wireless Mouse" class="product-img" />
          </div>
          <div class="product-info">
            <h3>Ergonomic Wireless Mouse</h3>
            <p class="product-price">$35.00</p>
            <p class="product-desc">Designed for comfort and precision during long coding sessions.</p>
          </div>
          <button class="btn-buy">Add to Cart</button>
        </article>

        <!-- Product 4 -->
        <article class="product-card">
          <div class="product-img-container">
            <img src="images/monitor.jpg" alt="Ultra-Wide 4K Monitor" class="product-img" />
          </div>
          <div class="product-info">
            <h3>Ultra-Wide 4K Monitor</h3>
            <p class="product-price">$399.00</p>
            <p class="product-desc">Stunning color accuracy and expansive screen real estate for multitasking.</p>
          </div>
          <button class="btn-buy">Add to Cart</button>
        </article>

        <!-- Product 5 -->
        <article class="product-card">
          <div class="product-img-container">
            <img src="images/hub.jpg" alt="USB-C Multi-Port Hub" class="product-img" />
          </div>
          <div class="product-info">
            <h3>USB-C Multi-Port Hub</h3>
            <p class="product-price">$29.00</p>
            <p class="product-desc">Includes 4K HDMI, USB 3.0 ports, and 100W Power Delivery pass-through.</p>
          </div>
          <button class="btn-buy">Add to Cart</button>
        </article>

        <!-- Product 6 -->
        <article class="product-card">
          <div class="product-img-container">
            <img src="images/lamp.jpg" alt="LED Desk Light Bar" class="product-img" />
          </div>
          <div class="product-info">
            <h3>LED Desk Light Bar</h3>
            <p class="product-price">$45.00</p>
            <p class="product-desc">Anti-glare monitor light bar with adjustable color temperature.</p>
          </div>
          <button class="btn-buy">Add to Cart</button>
        </article>

      </div>
    </section>
  </main>

  <hr />

  <!-- Footer -->
  <footer>
    <p>&copy; 2026 Responsive Product Catalog Lab &mdash; Assignment 7.3</p>
  </footer>

</body>
</html>