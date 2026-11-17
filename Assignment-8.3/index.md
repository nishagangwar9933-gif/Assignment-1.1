<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Magazine Layout Using Grid Areas | Assignment 8.3</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>

  <!-- Outer Magazine Grid Container -->
  <div class="magazine-container">

    <!-- 1 & 4. Header Section -->
    <header class="header-section">
      <h1>The CodeCraft Chronicle</h1>
      <p>Your daily digest of modern web development, CSS layouts, and engineering insights.</p>
    </header>

    <!-- 1 & 4. Navigation Section -->
    <nav class="nav-section" aria-label="Magazine Navigation">
      <ul>
        <li><a href="#">Top Stories</a></li>
        <li><a href="#">Tech &amp; Code</a></li>
        <li><a href="#">Design Systems</a></li>
        <li><a href="#">Opinion</a></li>
      </ul>
    </nav>

    <!-- 1, 4 & 5. Main Article Section (Given more space) -->
    <main class="main-section">
      <h2>Mastering CSS Grid Template Areas for Visual Layout Design</h2>
      <p class="author">By Lead Architecture Editor &bull; November 16, 2026</p>
      <p>
        CSS Grid Template Areas provide an exceptionally visual and intuitive way to design complex multi-section web layouts. By defining named grid areas directly in your stylesheet, developers can map out web pages like an architectural blueprint without relying on complex floating or positioning workarounds.
      </p>
      <p>
        In this article, we explore how combining fractional units (<code>fr</code>) with <code>grid-template-areas</code> allows main editorial content to take up two-thirds of the viewport while sidebars occupy the remaining column cleanly and responsively.
      </p>
    </main>

    <!-- 1 & 4. Sidebar Section -->
    <aside class="sidebar-section">
      <h3>Trending Topics</h3>
      <ul>
        <li><a href="#">CSS Subgrid Explained</a></li>
        <li><a href="#">Flexbox vs Grid in 2026</a></li>
        <li><a href="#">Semantic HTML Best Practices</a></li>
        <li><a href="#">Optimizing DevTools Performance</a></li>
      </ul>
    </aside>

    <!-- 1 & 4. Footer Section -->
    <footer class="footer-section">
      <p>&copy; 2026 The CodeCraft Chronicle &mdash; Assignment 8.3 Magazine Layout</p>
    </footer>

  </div>

</body>
</html>