<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>CSS Selectors Practice | Assignment 5.2</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>

  <!-- Header with ID Selector -->
  <header id="main-header">
    <h1>CSS Selectors Masterclass</h1>
    <p class="lead-text">Exploring element, class, ID, universal, grouping, and specificity rules.</p>
  </header>

  <main>
    <!-- Card 1 (Class Selector) -->
    <section class="card">
      <h2>Card One: Class Selector</h2>
      <p class="highlight-text">This paragraph uses a class selector to override standard element styles.</p>
    </section>

    <!-- Card 2 (Class Selector) -->
    <section class="card">
      <h2>Card Two: Class Selector</h2>
      <p class="highlight-text">This paragraph also shares the exact same class selector style.</p>
    </section>

    <!-- Special Section with ID Selector -->
    <section id="special-section">
      <h2>Special Section (ID Selector)</h2>
      <p>This section is styled uniquely using a high-specificity ID selector.</p>
    </section>
  </main>

  <footer>
    <p>&copy; 2026 CSS Selectors Practice &mdash; Assignment 5.2</p>
  </footer>

</body>
</html>