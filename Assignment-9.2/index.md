<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Responsive Typography &amp; Images | Assignment 9.2</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>

  <!-- Main Content Container with Max-Width Constraint -->
  <main class="article-container">

    <!-- Article Header -->
    <header class="article-header">
      <span class="category-tag">Web Design Principles</span>
      <h1>Responsive Typography &amp; Fluid Images in Modern Web Development</h1>
      <p class="article-meta">Published on November 16, 2026 &bull; By Student Developer</p>
    </header>

    <!-- Featured Image -->
    <div class="image-wrapper">
      <img 
        src="https://images.unsplash.com/photo-1498050108023-c5249f4df085?auto=format&fit=crop&w=1200&q=80" 
        alt="Developer workspace displaying clean responsive code" 
      />
      <figcaption>Figure 1: Designing layouts that adapt smoothly to every device viewport.</figcaption>
    </div>

    <!-- Article Body Content -->
    <article class="article-body">
      <h2>The Importance of Fluid Sizing</h2>
      <p>
        Building resilient web applications requires moving away from rigid pixel dimensions. By leveraging relative units like <code>rem</code>, fluid font sizing with <code>clamp()</code>, and flexible image containers, developers ensure that content remains readable and visually appealing across all devices.
      </p>

      <h2>Controlling Line Length and Readability</h2>
      <p>
        Text blocks that stretch too wide become difficult for the human eye to track. Constraining containers with a comfortable maximum width (such as <code>max-width: 70ch</code>) optimizes line length for maximum readability on both mobile screens and wide desktop monitors.
      </p>

      <!-- Secondary Content Image -->
      <div class="image-wrapper">
        <img 
          src="https://images.unsplash.com/photo-1517694712202-14dd9538aa97?auto=format&fit=crop&w=1200&q=80" 
          alt="Hands typing on a mechanical keyboard" 
        />
        <figcaption>Figure 2: Writing clean CSS rules for responsive media scaling.</figcaption>
      </div>

      <h2>Preventing Overflow and Image Distortion</h2>
      <p>
        Images must never break out of their parent containers or distort when viewports shrink. Applying <code>max-width: 100%</code> and <code>height: auto</code> guarantees that images scale down proportionally while preserving their original aspect ratios.
      </p>
    </article>

  </main>

  <!-- Footer -->
  <footer class="site-footer">
    <p>&copy; 2026 Responsive Typography Lab &mdash; Assignment 9.2</p>
  </footer>

</body>
</html>