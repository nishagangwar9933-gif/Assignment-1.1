<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>CSS Grid Photo Gallery Showcase | Assignment 8.5</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>

  <!-- Outer Page Layout Grid Container -->
  <div class="page-container">

    <!-- Header Section -->
    <header class="header-section">
      <div class="logo">&lt;VisualGrid /&gt;</div>
      <nav aria-label="Gallery Navigation">
        <ul class="nav-links">
          <li><a href="#" class="active">Explore</a></li>
          <li><a href="#">Architecture</a></li>
          <li><a href="#">Workspace</a></li>
          <li><a href="#">About</a></li>
        </ul>
      </nav>
    </header>

    <!-- Main Content Area -->
    <main class="main-section">
      <div class="gallery-hero">
        <h1>Curated Developer &amp; Architecture Gallery</h1>
        <p>Exploring modern CSS Grid layouts, auto-responsive columns, and overflow prevention.</p>
      </div>

      <!-- Auto-Responsive Photo Grid -->
      <div class="photo-grid">
        <!-- Photo Card 1 -->
        <article class="photo-card">
          <img src="https://images.unsplash.com/photo-1498050108023-c5249f4df085?auto=format&fit=crop&w=600&q=80" alt="Clean code setup on laptop" />
          <div class="photo-info">
            <h3>Clean Code Setup</h3>
            <span class="category">Workspace</span>
          </div>
        </article>

        <!-- Photo Card 2 -->
        <article class="photo-card">
          <img src="https://images.unsplash.com/photo-1555066931-4365d14bab8c?auto=format&fit=crop&w=600&q=80" alt="Code editor on dual monitors" />
          <div class="photo-info">
            <h3>Development Workflow</h3>
            <span class="category">Coding</span>
          </div>
        </article>

        <!-- Photo Card 3 -->
        <article class="photo-card">
          <img src="https://images.unsplash.com/photo-1517694712202-14dd9538aa97?auto=format&fit=crop&w=600&q=80" alt="Mechanical keyboard close-up" />
          <div class="photo-info">
            <h3>Tactile Precision</h3>
            <span class="category">Hardware</span>
          </div>
        </article>

        <!-- Photo Card 4 -->
        <article class="photo-card">
          <img src="https://images.unsplash.com/photo-1531403009284-440f080d1e12?auto=format&fit=crop&w=600&q=80" alt="Team collaboration meeting" />
          <div class="photo-info">
            <h3>Team Synergy</h3>
            <span class="category">Collaboration</span>
          </div>
        </article>

        <!-- Photo Card 5 -->
        <article class="photo-card">
          <img src="https://images.unsplash.com/photo-1507238691740-187a5b1d37b8?auto=format&fit=crop&w=600&q=80" alt="UI wireframing on whiteboard" />
          <div class="photo-info">
            <h3>Architectural Planning</h3>
            <span class="category">Design</span>
          </div>
        </article>

        <!-- Photo Card 6 -->
        <article class="photo-card">
          <img src="https://images.unsplash.com/photo-1526374965328-7f61d4dc18c5?auto=format&fit=crop&w=600&q=80" alt="Binary code matrix screen" />
          <div class="photo-info">
            <h3>Data &amp; Logic</h3>
            <span class="category">Engineering</span>
          </div>
        </article>

        <!-- Photo Card 7 -->
        <article class="photo-card">
          <img src="https://images.unsplash.com/photo-1551288049-bebda4e38f71?auto=format&fit=crop&w=600&q=80" alt="Analytics graphs on monitor" />
          <div class="photo-info">
            <h3>Performance Metrics</h3>
            <span class="category">Analytics</span>
          </div>
        </article>

        <!-- Photo Card 8 -->
        <article class="photo-card">
          <img src="https://images.unsplash.com/photo-1461749280684-dccba630e2f6?auto=format&fit=crop&w=600&q=80" alt="Programming syntax on dark theme" />
          <div class="photo-info">
            <h3>Syntax &amp; Structure</h3>
            <span class="category">Code</span>
          </div>
        </article>
      </div>
    </main>

    <!-- Footer Section -->
    <footer class="footer-section">
      <p>&copy; 2026 VisualGrid Gallery &mdash; Assignment 8.5 CSS Grid Capstone</p>
    </footer>

  </div>

</body>
</html>