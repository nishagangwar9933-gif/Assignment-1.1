<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Profile &amp; Product Card Mini-Project | Assignment 6.5</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>

  <!-- Page Header -->
  <header class="page-header">
    <h1>CSS Mini-Project: Cards Showcase</h1>
    <p>Demonstrating box model properties, distinct backgrounds, borders, rounded corners, and absolute positioning.</p>
  </header>

  <hr style="border: none; border-top: 1px solid #cbd5e1; margin: 24px 0;" />

  <!-- Main Content: Cards Container -->
  <main class="cards-showcase">

    <!-- 1. Profile Card -->
    <article class="card profile-card">
      <!-- Positioned Badge -->
      <span class="card-badge badge-pro">Verified Pro</span>

      <div class="profile-header">
        <img
          src="images/profile.jpg"
          alt="Portrait of Your Full Name"
          class="profile-img"
        />
        <h2 class="profile-name">Your Full Name</h2>
        <p class="profile-role">Front-End Web Developer</p>
      </div>

      <p class="card-desc">
        Passionate about building clean, accessible, semantic web applications using modern HTML5, CSS3, and JavaScript.
      </p>

      <div class="skills-container">
        <span class="skill-pill">HTML5</span>
        <span class="skill-pill">CSS3</span>
        <span class="skill-pill">Git</span>
        <span class="skill-pill">UI Design</span>
      </div>

      <button class="card-btn btn-primary">Contact Me</button>
    </article>

    <!-- 2. Product Card -->
    <article class="card product-card">
      <!-- Positioned Badge -->
      <span class="card-badge badge-sale">20% OFF</span>

      <div class="product-img-container">
        <img
          src="images/product-stand.jpg"
          alt="Ergonomic aluminum laptop stand for developers"
          class="product-img"
        />
      </div>

      <div class="product-info">
        <h2 class="product-name">Ergonomic Aluminum Laptop Stand</h2>
        <div class="price-box">
          <span class="current-price">$49.00</span>
          <span class="original-price">$62.00</span>
        </div>
        <p class="card-desc">
          Sturdy, lightweight adjustable aluminum stand designed to improve posture and airflow during long coding sessions.
        </p>
      </div>

      <button class="card-btn btn-success">Add to Cart</button>
    </article>

  </main>

  <hr style="border: none; border-top: 1px solid #cbd5e1; margin: 24px 0;" />

  <!-- Footer -->
  <footer>
    <p>&copy; 2026 Card Component Mini-Project &mdash; Assignment 6.5</p>
  </footer>

</body>
</html>