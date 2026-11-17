<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <!-- Viewport meta tag for mobile-first scaling -->
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Responsive Landing Page | Assignment 9.5 Portfolio-Ready</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>

  <!-- Outer Site Wrapper -->
  <div class="site-wrapper">

    <!-- Responsive Navigation Bar -->
    <header class="site-header">
      <div class="nav-container">
        <div class="logo">
          <a href="#">&lt;CodeCraft /&gt;</a>
        </div>
        <nav aria-label="Primary Navigation">
          <ul class="nav-links">
            <li><a href="#features">Features</a></li>
            <li><a href="#curriculum">Curriculum</a></li>
            <li><a href="#mentors">Mentors</a></li>
            <li><a href="#pricing">Pricing</a></li>
          </ul>
        </nav>
        <div class="nav-actions">
          <a href="#" class="btn btn-secondary">Sign In</a>
          <a href="#cta" class="btn btn-primary">Get Started</a>
        </div>
      </div>
    </header>

    <!-- Main Content Area -->
    <main>
      <!-- Hero Section -->
      <section class="hero-section">
        <div class="hero-container">
          <div class="hero-text">
            <span class="badge">Cohort 2026 Open</span>
            <h1>Build Professional Web Apps with Modern CSS</h1>
            <p>
              Master semantic HTML5, CSS Flexbox, Grid layouts, and professional Git workflows 
              through real-world projects and expert mentorship.
            </p>
            <div class="hero-buttons">
              <a href="#cta" class="btn btn-primary btn-lg">Start Learning Free</a>
              <a href="#features" class="btn btn-outline btn-lg">View Curriculum</a>
            </div>
          </div>
          <div class="hero-image">
            <img src="https://images.unsplash.com/photo-1498050108023-c5249f4df085?auto=format&fit=crop&w=800&q=80" alt="Developer workspace responsive view" />
          </div>
        </div>
      </section>

      <!-- Feature Cards Section -->
      <section id="features" class="features-section">
        <div class="features-container">
          <div class="section-header">
            <h2>Why Choose CodeCraft Academy?</h2>
            <p>Designed for aspiring software engineers seeking practical industry skills.</p>
          </div>

          <div class="features-grid">
            <!-- Feature Card 1 -->
            <article class="feature-card">
              <div class="card-icon">🚀</div>
              <h3>Hands-On Projects</h3>
              <p>Build real web applications from scratch and populate your professional GitHub portfolio.</p>
            </article>

            <!-- Feature Card 2 -->
            <article class="feature-card">
              <div class="card-icon">📐</div>
              <h3>Advanced Layouts</h3>
              <p>Master CSS Flexbox and Grid to build responsive, fluid interfaces for any screen size.</p>
            </article>

            <!-- Feature Card 3 -->
            <article class="feature-card">
              <div class="card-icon">👥</div>
              <h3>Expert Mentorship</h3>
              <p>Receive code reviews, debugging support, and guidance directly from industry professionals.</p>
            </article>
          </div>
        </div>
      </section>

      <!-- Call-to-Action Banner -->
      <section id="cta" class="cta-banner">
        <div class="cta-content">
          <h2>Ready to Launch Your Web Development Career?</h2>
          <p>Join thousands of students mastering modern HTML, CSS, and responsive design.</p>
          <a href="#" class="btn btn-white btn-lg">Claim Your Free Account</a>
        </div>
      </section>
    </main>

    <!-- Footer Section -->
    <footer class="site-footer">
      <div class="footer-container">
        <p>&copy; 2026 CodeCraft Developer Academy &mdash; Assignment 9.5 Capstone</p>
        <div class="footer-links">
          <a href="#">Privacy Policy</a>
          <a href="#">Terms of Service</a>
          <a href="#">Support</a>
        </div>
      </div>
    </footer>

  </div>

</body>
</html>