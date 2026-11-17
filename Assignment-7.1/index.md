<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Responsive Navigation Bar | Assignment 7.1</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>

  <!-- 1. Header containing logo, nav links, and CTA button -->
  <header class="navbar-header">
    <div class="nav-container">
      
      <!-- Brand Logo -->
      <div class="logo">
        <a href="#">&lt;CodeCraft /&gt;</a>
      </div>

      <!-- Navigation Links -->
      <nav aria-label="Primary Navigation">
        <ul class="nav-links">
          <li><a href="#">Home</a></li>
          <li><a href="#">About</a></li>
          <li><a href="#">Courses</a></li>
          <li><a href="#">Blog</a></li>
          <li><a href="#">Contact</a></li>
        </ul>
      </nav>

      <!-- Action Button -->
      <div class="nav-action">
        <a href="#" class="btn-cta">Get Started</a>
      </div>

    </div>
  </header>

  <!-- Main Content Area -->
  <main style="padding: 40px 24px; max-width: 900px; margin: 0 auto;">
    <h1>Responsive Flexbox Navigation Bar</h1>
    <p>Resize your browser window (Step 6) to test how the Flexbox layout automatically distributes space and aligns items cleanly across viewports.</p>
  </main>

  <!-- Footer -->
  <footer>
    <p style="text-align: center; color: #64748b; font-size: 0.875rem; padding: 24px;">&copy; 2026 Flexbox Navigation Lab &mdash; Assignment 7.1</p>
  </footer>

</body>
</html>