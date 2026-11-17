<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Modern Landing Page | Assignment 7.4</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>

  <!-- 1. Header with Logo, Navigation Links, and CTA Button -->
  <header class="site-header">
    <div class="nav-container">
      <div class="logo">
        <a href="#">&lt;CodeCraft /&gt;</a>
      </div>

      <nav aria-label="Primary Navigation">
        <ul class="nav-links">
          <li><a href="#">Features</a></li>
          <li><a href="#">Curriculum</a></li>
          <li><a href="#">Mentors</a></li>
          <li><a href="#">Pricing</a></li>
        </ul>
      </nav>

      <div class="header-cta">
        <a href="#" class="btn btn-secondary">Sign In</a>
      </div>
    </div>
  </header>

  <!-- Main Landing Page Content -->
  <main>
    <!-- 2, 3, 4 & 5. Hero Section (Side-by-side Flexbox Layout) -->
    <section class="hero-section">
      <div class="hero-container">
        
        <!-- Hero Text Column -->
        <div class="hero-text">
          <span class="hero-badge">Cohort 2026 Open</span>
          <h1>Master Modern Web Development with Confidence</h1>
          <p>
            Learn semantic HTML5, advanced CSS Flexbox &amp; Grid, and professional Git workflows 
            through hands-on projects and expert-led mentorship.
          </p>
          <div class="hero-buttons">
            <a href="#" class="btn btn-primary">Start Learning Free</a>
            <a href="#" class="btn btn-outline">Explore Syllabus</a>
          </div>
        </div>

        <!-- Hero Illustration / Image Column -->
        <div class="hero-image">
          <div class="illustration-box">
            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 500 400" width="100%" height="auto">
              <rect width="500" height="400" rx="16" fill="#eff6ff"/>
              <rect x="40" y="40" width="420" height="320" rx="8" fill="#ffffff" stroke="#cbd5e1" stroke-width="2"/>
              <!-- Mock code editor header -->
              <circle cx="65" cy="65" r="6" fill="#ef4444"/>
              <circle cx="85" cy="65" r="6" fill="#f59e0b"/>
              <circle cx="105" cy="65" r="6" fill="#10b981"/>
              <!-- Mock code lines -->
              <rect x="65" y="95" width="180" height="12" rx="4" fill="#2563eb" opacity="0.2"/>
              <rect x="65" y="125" width="280" height="10" rx="4" fill="#64748b" opacity="0.3"/>
              <rect x="65" y="150" width="220" height="10" rx="4" fill="#64748b" opacity="0.3"/>
              <rect x="85" y="175" width="160" height="10" rx="4" fill="#0ea5e9" opacity="0.5"/>
              <rect x="85" y="200" width="240" height="10" rx="4" fill="#64748b" opacity="0.3"/>
              <rect x="65" y="225" width="120" height="10" rx="4" fill="#64748b" opacity="0.3"/>
              <rect x="65" y="260" width="370" height="50" rx="6" fill="#f8fafc" stroke="#e2e8f0"/>
              <circle cx="95" cy="285" r="12" fill="#10b981" opacity="0.8"/>
              <text x="120" y="290" font-family="sans-serif" font-size="14" font-weight="bold" fill="#0f172a">All Tests Passed Successfully!</text>
            </svg>
          </div>
        </div>

      </div>
    </section>
  </main>

  <!-- 6. Styled Footer -->
  <footer class="site-footer">
    <p>&copy; 2026 CodeCraft Developer Academy &mdash; Assignment 7.4</p>
  </footer>

</body>
</html>