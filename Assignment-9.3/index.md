<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Responsive Landing Page (Grid &amp; Flexbox) | Assignment 9.3</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>

  <!-- Outer Page Layout -->
  <div class="page-layout">

    <!-- 1 & 5. Header & Navigation Bar (Flexbox) -->
    <header class="site-header">
      <div class="logo">
        <a href="#">&lt;CodeCraft /&gt;</a>
      </div>
      <nav aria-label="Primary Navigation">
        <ul class="nav-links">
          <li><a href="#hero">Home</a></li>
          <li><a href="#features">Features</a></li>
          <li><a href="#cta">Contact</a></li>
        </ul>
      </nav>
      <div class="nav-action">
        <a href="#cta" class="btn btn-secondary">Get Started</a>
      </div>
    </header>

    <!-- 4. Main Section Layout (CSS Grid) -->
    <main class="main-grid">

      <!-- 2 & 5. Hero Section (Flexbox Alignment) -->
      <section id="hero" class="hero-section">
        <div class="hero-text">
          <h1>Combine Flexbox &amp; Grid Responsively</h1>
          <p>
            Master advanced web layouts by pairing the one-dimensional alignment power of Flexbox 
            with the two-dimensional layout strength of CSS Grid, scaled seamlessly across all devices.
          </p>
          <div class="hero-buttons">
            <a href="#features" class="btn btn-primary">Explore Features</a>
          </div>
        </div>
        <div class="hero-image">
          <img src="https://images.unsplash.com/photo-1498050108023-c5249f4df085?auto=format&fit=crop&w=800&q=80" alt="Developer workspace setup" />
        </div>
      </section>

      <!-- 3. Features Section (3-6 Cards with Flexbox Internal Content) -->
      <section id="features" class="features-section">
        <div class="section-title">
          <h2>Powerful Layout Tools</h2>
          <p>Designed with mobile-first principles and progressive enhancement.</p>
        </div>

        <div class="cards-grid">
          <!-- Card 1 -->
          <article class="feature-card">
            <div class="card-icon">📐</div>
            <div class="card-content">
              <h3>CSS Grid Layouts</h3>
              <p>Define two-dimensional column and row structures with absolute precision.</p>
            </div>
          </article>

          <!-- Card 2 -->
          <article class="feature-card">
            <div class="card-icon">⚡</div>
            <div class="card-content">
              <h3>Flexbox Alignment</h3>
              <p>Effortlessly distribute space and align items along a single axis.</p>
            </div>
          </article>

          <!-- Card 3 -->
          <article class="feature-card">
            <div class="card-icon">📱</div>
            <div class="card-content">
              <h3>Mobile-First Design</h3>
              <p>Start with simple single-column layouts and scale up via media queries.</p>
            </div>
          </article>

          <!-- Card 4 -->
          <article class="feature-card">
            <div class="card-icon">🛡️</div>
            <div class="card-content">
              <h3>Overflow Prevention</h3>
              <p>Ensure images and text adapt cleanly without breaking viewports.</p>
            </div>
          </article>
        </div>
      </section>

    </main>

    <!-- Footer -->
    <footer id="cta" class="site-footer">
      <div class="footer-content">
        <h3>Ready to Build Responsive Web Pages?</h3>
        <p>&copy; 2026 CodeCraft Developer Academy &mdash; Assignment 9.3</p>
      </div>
    </footer>

  </div>

</body>
</html>