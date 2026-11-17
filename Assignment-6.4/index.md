<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Positioning Practice | Assignment 6.4</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>

  <!-- 2. Sticky Navigation Bar -->
  <nav class="sticky-nav">
    <div class="nav-container">
      <h2>CSS Positioning Lab</h2>
      <ul>
        <li><a href="#section-1">Home</a></li>
        <li><a href="#section-2">Absolute Badge</a></li>
        <li><a href="#section-3">Fixed Button</a></li>
      </ul>
    </div>
  </nav>

  <!-- 1. Multiple Scrollable Sections -->
  <main>
    <section id="section-1" class="scroll-section">
      <h1>Welcome to Positioning Practice</h1>
      <p>Scroll down this page to observe the sticky navigation bar staying locked to the top of the viewport.</p>
    </section>

    <!-- 4 & 5. Position: absolute badge inside a relative parent card -->
    <section id="section-2" class="scroll-section">
      <h2>Absolute Positioning &amp; Z-Index</h2>
      <p>The card below uses a relative container so the badge can be positioned absolutely in its top-right corner.</p>

      <div class="card-container">
        <!-- Position: absolute badge -->
        <span class="badge">Featured</span>
        <h3>Card With Absolute Badge</h3>
        <p>This card demonstrates how <code>position: absolute</code> relies on a parent element with <code>position: relative</code>.</p>
      </div>
    </section>

    <section id="section-3" class="scroll-section">
      <h2>Fixed Floating Action Button</h2>
      <p>Look at the bottom-right corner of your screen to find the floating contact button anchored via <code>position: fixed</code>.</p>
      <div style="height: 300px;"></div>
    </section>
  </main>

  <!-- 3. Floating Action Button (position: fixed) -->
  <button class="floating-btn" aria-label="Contact Support">
    💬 Help
  </button>

  <!-- Footer -->
  <footer>
    <p>&copy; 2026 CSS Positioning Lab &mdash; Assignment 6.4</p>
  </footer>

</body>
</html>