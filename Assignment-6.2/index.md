<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Card Designs &amp; Display Properties | Assignment 6.2</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>

  <!-- Header -->
  <header>
    <h1>Backgrounds, Borders &amp; Display Properties</h1>
    <p>Exploring distinct card tiers, rounded corners, max-width sizing, and CSS display behaviors.</p>
  </header>

  <hr />

  <!-- Main Content: 3 Card Designs -->
  <main>
    <section aria-labelledby="cards-heading">
      <h2 id="cards-heading">Pricing &amp; Membership Tiers</h2>
      
      <div class="cards-container">
        <!-- 1. Basic Card -->
        <article class="card card-basic">
          <h3>Basic Plan</h3>
          <p class="price">$9 / month</p>
          <p class="card-desc">Essential features for beginners starting their coding journey with HTML and CSS.</p>
          <button class="btn">Get Started</button>
        </article>

        <!-- 2. Standard Card -->
        <article class="card card-standard">
          <h3>Standard Plan</h3>
          <p class="price">$19 / month</p>
          <p class="card-desc">Advanced modules, Git version control workshops, and community access.</p>
          <button class="btn">Choose Standard</button>
        </article>

        <!-- 3. Premium Card -->
        <article class="card card-premium">
          <h3>Premium Plan</h3>
          <p class="price">$49 / month</p>
          <p class="card-desc">Full curriculum, 1-on-1 mentorship, and certificate of completion.</p>
          <button class="btn">Go Premium</button>
        </article>
      </div>
    </section>

    <hr />

    <!-- Display Property Demonstration Section -->
    <section aria-labelledby="display-heading">
      <h2 id="display-heading">CSS Display Properties Demonstration</h2>
      <p>Comparing how elements behave under different display rules:</p>

      <!-- Display: block -->
      <div class="demo-box demo-block">
        <strong>display: block</strong> — Takes up the full available width and starts on a new line.
      </div>

      <!-- Display: inline -->
      <p>
        Here is a paragraph containing 
        <span class="demo-inline">display: inline</span> 
        elements which flow naturally within text lines without breaking to new lines.
      </p>

      <!-- Display: inline-block -->
      <div>
        <div class="demo-box demo-inline-block">Inline-Block 1</div>
        <div class="demo-box demo-inline-block">Inline-Block 2</div>
        <div class="demo-box demo-inline-block">Inline-Block 3</div>
      </div>
      <p><small><em>Above: Inline-block elements sit side by side while still respecting width and height rules.</em></small></p>
    </section>
  </main>

  <hr />

  <!-- Footer -->
  <footer>
    <p>&copy; 2026 Display &amp; Card Layouts Lab &mdash; Assignment 6.2</p>
  </footer>

</body>
</html>