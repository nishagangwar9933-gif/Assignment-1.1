<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Auto-Responsive Image Gallery | Assignment 8.2</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>

  <!-- Page Header -->
  <header class="page-header">
    <h1>CSS Grid Auto-Responsive Photo Gallery</h1>
    <p>Using <code>repeat(auto-fit, minmax(...))</code> for seamless responsive columns without media queries.</p>
  </header>

  <hr />

  <!-- Main Gallery Container (8 Images) -->
  <main>
    <section aria-labelledby="gallery-heading">
      <h2 id="gallery-heading" class="sr-only">Developer Workspace &amp; Nature Gallery</h2>

      <div class="gallery-grid">
        <!-- Image 1 -->
        <article class="gallery-item">
          <img src="https://images.unsplash.com/photo-1498050108023-c5249f4df085?auto=format&fit=crop&w=600&q=80" alt="Laptop showing code on desk" />
          <div class="gallery-caption">Clean Code Setup</div>
        </article>

        <!-- Image 2 -->
        <article class="gallery-item">
          <img src="https://images.unsplash.com/photo-1555066931-4365d14bab8c?auto=format&fit=crop&w=600&q=80" alt="Code editor on dual monitors" />
          <div class="gallery-caption">Development Workflow</div>
        </article>

        <!-- Image 3 -->
        <article class="gallery-item">
          <img src="https://images.unsplash.com/photo-1517694712202-14dd9538aa97?auto=format&fit=crop&w=600&q=80" alt="Person typing on mechanical keyboard" />
          <div class="gallery-caption">Typing &amp; Debugging</div>
        </article>

        <!-- Image 4 -->
        <article class="gallery-item">
          <img src="https://images.unsplash.com/photo-1531403009284-440f080d1e12?auto=format&fit=crop&w=600&q=80" alt="Team collaborating around a laptop" />
          <div class="gallery-caption">Team Collaboration</div>
        </article>

        <!-- Image 5 -->
        <article class="gallery-item">
          <img src="https://images.unsplash.com/photo-1507238691740-187a5b1d37b8?auto=format&fit=crop&w=600&q=80" alt="Planning UI wireframes on whiteboard" />
          <div class="gallery-caption">UI/UX Wireframing</div>
        </article>

        <!-- Image 6 -->
        <article class="gallery-item">
          <img src="https://images.unsplash.com/photo-1526374965328-7f61d4dc18c5?auto=format&fit=crop&w=600&q=80" alt="Abstract binary code screen" />
          <div class="gallery-caption">Data &amp; Logic</div>
        </article>

        <!-- Image 7 -->
        <article class="gallery-item">
          <img src="