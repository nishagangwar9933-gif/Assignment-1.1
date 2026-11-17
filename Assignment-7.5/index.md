<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Flexbox Mini-Project: Landing Page | Assignment 7.5</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>

  <!-- 1. Navigation Bar -->
  <header class="site-header">
    <div class="nav-container">
      <div class="logo">
        <a href="#">&lt;CodeCraft /&gt;</a>
      </div>
      <nav aria-label="Primary Navigation">
        <ul class="nav-links">
          <li><a href="#features">Features</a></li>
          <li><a href="#curriculum">Curriculum</a></li>
          <li><a href="#cta">Join Us</a></li>
        </ul>
      </nav>
      <div class="nav-action">
        <a href="#cta" class="btn btn-secondary">Get Started</a>
      </div>
    </div>
  </header>

  <main>
    <!-- 2. Hero Section -->
    <section class="hero-section">
      <div class="hero-container">
        <div class="hero-text">
          <span class="badge">Module 7 Capstone</span>
          <h1>Build Professional Websites with Flexbox</h1>
          <p>
            Master one-dimensional layouts, alignment, wrapping, and responsive design 
            through hands-on projects and modern CSS architecture.
          </p>
          <div class="hero-btns">
            <a href="#cta" class="btn btn-primary">Enroll Free Today</a>
            <a href="#features" class="btn btn-outline">Explore Features</a>
          </div>
        </div>
        <div class="hero-visual">
          <div class="code-preview-card">
            <div class="preview-header">
              <span class="dot red"></span>
              <span class="dot yellow"></span>
              <span class="dot green"></span>
              <span class="filename">flexbox-layout.css</span>
            </div>
            <pre><code>display: flex;
flex-wrap: wrap;
justify-content: space-between;
align-items: center;
gap: 24px;</code></pre>
          </div>
        </div>
      </div>
    </section>

    <!-- 3. Feature Cards Section (3 Cards in Responsive Row) -->
    <section id="features" class="features-section">
      <div class="section-header">
        <h2>Why Learn With CodeCraft?</h2>
        <p>Everything you need to go from beginner to confident web developer.</p>
      </div>

      <div class="features-grid">
        <!-- Feature Card 1 -->
        <article class="feature-card">
          <div class="card-icon">🚀</div>
          <h3>Hands-On Projects</h3>
          <p>Apply HTML and CSS concepts immediately by building real-world landing pages and components.</p>
        </article>

        <!-- Feature Card 2 -->
        <article class="feature-card">
          <div class="card-icon">📐</div>
          <h3>Modern Layouts</h3>
          <p>Master Flexbox and Grid to build responsive, fluid interfaces that look great on any device.</p>
        </article>

        <!-- Feature Card 3 -->
        <article class="feature-card">
          <div class="card-icon">👥</div>
          <h3>Peer Community</h3>
          <p>Collaborate with fellow students, share code reviews, and build your developer portfolio together.</p>
        </article>
      </div>
    </section>

    <!-- 4. Call-to-Action (CTA) Section -->
    <section id="cta" class="cta-section">
      <div class="cta-container">
        <h2>Ready to Start Your Web Development Journey?</h2>
        <p>Join thousands of students learning modern HTML, CSS, and Git workflows.</p>
        <a href="#" class="btn btn-white">Claim Your Free Membership</a>
      </div>
    </section>
  </main>

  <!-- 5. Footer -->
  <footer class="site-footer">
    <div class="footer-container">
      <p>&copy; 2026 CodeCraft Developer Academy &mdash; Assignment 7.5 Flexbox Mini-Project</p>
      <p class="footer-links">
        <a href="#">Privacy Policy</a> | <a href="#">Terms of Service</a> | <a href="#">Contact</a>
      </p>
    </div>
  </footer>

</body>
</html>