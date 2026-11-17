<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Overflow &amp; Layout Fixing | Assignment 6.3</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>

  <!-- Header -->
  <header>
    <h1>CSS Overflow &amp; Layout Fixing</h1>
    <p>Demonstrating fixed-height containers and testing overflow properties: <code>visible</code>, <code>hidden</code>, <code>scroll</code>, and <code>auto</code>.</p>
  </header>

  <hr />

  <!-- Main Content -->
  <main>

    <!-- Section 1: Overflow Property Demonstrations -->
    <section aria-labelledby="overflow-demo-heading">
      <h2 id="overflow-demo-heading">1. Overflow Property Variations</h2>
      <p>All four boxes below have a fixed height of <strong>120px</strong> and contain excess text to demonstrate how each overflow value behaves.</p>

      <div class="overflow-grid">
        <!-- overflow: visible -->
        <div class="demo-card">
          <h3>overflow: visible (Default)</h3>
          <div class="box overflow-visible">
            <p>This content is too long for the container. With overflow set to visible, the text spills out over the bottom border without being clipped or generating scrollbars.</p>
          </div>
        </div>

        <!-- overflow: hidden -->
        <div class="demo-card">
          <h3>overflow: hidden</h3>
          <div class="box overflow-hidden">
            <p>This content is too long for the container. With overflow set to hidden, any text exceeding the 120px height boundary is cleanly clipped and invisible to the user.</p>
          </div>
        </div>

        <!-- overflow: scroll -->
        <div class="demo-card">
          <h3>overflow: scroll</h3>
          <div class="box overflow-scroll">
            <p>This content is too long for the container. With overflow set to scroll, horizontal and vertical scrollbars are permanently rendered so users can scroll through the excess text.</p>
          </div>
        </div>

        <!-- overflow: auto -->
        <div class="demo-card">
          <h3>overflow: auto</h3>
          <div class="box overflow-auto">
            <p>This content is too long for the container. With overflow set to auto, scrollbars appear *only* when the content actually exceeds the container dimensions, keeping the UI clean.</p>
          </div>
        </div>
      </div>
    </section>

    <hr />

    <!-- Section 2: Layout Fixing Example -->
    <section aria-labelledby="fix-heading">
      <h2 id="fix-heading">2. Layout Fixing Example (Long Strings / Unbreakable Content)</h2>
      <p>Unbroken strings or wide media can break container layouts if not handled correctly. Using <code>overflow: auto</code> or <code>word-break: break-word</code> prevents horizontal layout breaking.</p>

      <div class="fixed-layout-container">
        <h3>Fixed Container with Long Content</h3>
        <div class="overflow-auto" style="height: 100px;">
          <p>Here is a very long unbroken technical token or URL string that could potentially cause layout overflow: <code>https://www.example.com/very/long/path/to/resource/with/no/spaces/that/might/break/the/container/layout/if/overflow/is/not/handled</code></p>
        </div>
      </div>
    </section>

  </main>

  <hr />

  <!-- Footer -->
  <footer>
    <p>&copy; 2026 Overflow &amp; Layout Lab &mdash; Assignment 6.3</p>
  </footer>

</body>
</html>