<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <!-- 2. Verify the viewport meta tag for mobile-first scaling -->
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Mobile-First Responsive Layout | Assignment 9.1</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>

  <!-- Page Container -->
  <div class="page-wrapper">

    <!-- Header Section -->
    <header class="site-header">
      <div class="logo">&lt;MobileFirst /&gt;</div>
      <nav aria-label="Mobile Navigation">
        <ul class="nav-links">
          <li><a href="#" class="active">Home</a></li>
          <li><a href="#">Gallery</a></li>
          <li><a href="#">About</a></li>
        </ul>
      </nav>
    </header>

    <!-- Main Content Area -->
    <main class="main-content">
      <section class="hero">
        <h1>Responsive Design from the Ground Up</h1>
        <p>Built using mobile-first CSS principles, fluid scaling, and progressive enhancement via media query breakpoints.</p>
      </section>

      <!-- Responsive Cards Grid -->
      <section class="cards-grid">
        <article class="card">
          <img src="https://images.unsplash.com/photo-1498050108023-c5249f4df085?auto=format&fit=crop&w=600&q=80" alt="Mobile First Coding" />
          <div class="card-body">
            <h3>Mobile-First Base</h3>
            <p>Styles are written for small mobile screens first, ensuring fast load times and clean stacking.</p>
          </div>
        </article>

        <article class="card">
          <img src="https://images.unsplash.com/photo-1555066931-4365d14bab8c?auto=format&fit=crop&w=600&q=80" alt="Tablet Breakpoint" />
          <div class="card-body">
            <h3>Tablet Breakpoint</h3>
            <p>Expanding layout grid columns at 640px and above for intermediate viewports.</p>
          </div>
        </article>

        <article class="card">
          <img src="https://images.unsplash.com/photo-1517694712202-14dd9538aa97?auto=format&fit=crop&w=600&q=80" alt="Desktop Breakpoint" />
          <div class="card-body">
            <h3>Desktop Enhancement</h3>
            <p>Full multi-column grid layout activated at 1024px and above for large displays.</p>
          </div>
        </article>
      </section>
    </main>

    <!-- Footer -->
    <footer class="site-footer">
      <p>&copy; 2026 Mobile-First Responsive Design Lab &mdash; Assignment 9.1</p>
    </footer>

  </div>

</body>
</html>