<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Pricing Cards &amp; Centered Login Form | Assignment 7.2</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>

  <!-- Page Header -->
  <header class="page-header">
    <h1>Pricing Tiers &amp; Authentication Portal</h1>
    <p>Demonstrating CSS Flexbox alignment, wrapping, and absolute/flex centering properties.</p>
  </header>

  <hr />

  <!-- Main Content -->
  <main>

    <!-- Section 1: Pricing Cards (Flexbox Container) -->
    <section aria-labelledby="pricing-heading">
      <h2 id="pricing-heading" class="section-title">Choose Your Plan</h2>

      <div class="pricing-container">
        <!-- 1. Basic Plan Card -->
        <article class="pricing-card">
          <h3>Basic Plan</h3>
          <p class="price">$9<span> /mo</span></p>
          <ul class="features-list">
            <li>1 Website Project</li>
            <li>Basic HTML/CSS Support</li>
            <li>Community Access</li>
          </ul>
          <button class="btn btn-basic">Choose Basic</button>
        </article>

        <!-- 2. Pro Plan Card (Featured) -->
        <article class="pricing-card pricing-pro">
          <span class="badge">Most Popular</span>
          <h3>Pro Plan</h3>
          <p class="price">$29<span> /mo</span></p>
          <ul class="features-list">
            <li>5 Website Projects</li>
            <li>Advanced Flexbox &amp; Grid</li>
            <li>Priority Code Reviews</li>
          </ul>
          <button class="btn btn-pro">Choose Pro</button>
        </article>

        <!-- 3. Premium Plan Card -->
        <article class="pricing-card">
          <h3>Premium Plan</h3>
          <p class="price">$59<span> /mo</span></p>
          <ul class="features-list">
            <li>Unlimited Projects</li>
            <li>Full Stack Mentorship</li>
            <li>1-on-1 Support Calls</li>
          </ul>
          <button class="btn btn-premium">Choose Premium</button>
        </article>
      </div>
    </section>

    <hr />

    <!-- Section 2: Centered Login Form Container -->
    <section aria-labelledby="login-heading">
      <h2 id="login-heading" class="section-title">Member Login Portal</h2>

      <div class="login-wrapper">
        <form class="login-form" action="#" method="post">
          <h3>Welcome Back</h3>
          <p class="form-desc">Sign in to access your dashboard.</p>

          <div class="form-group">
            <label for="login-email">Email Address:</label>
            <input type="email" id="login-email" name="email" placeholder="you@example.com" required />
          </div>

          <div class="form-group">
            <label for="login-password">Password:</label>
            <input type="password" id="login-password" name="password" placeholder="••••••••" required />
          </div>

          <button type="submit" class="btn btn-login">Sign In</button>
        </form>
      </div>
    </section>

  </main>

  <hr />

  <!-- Footer -->
  <footer>
    <p>&copy; 2026 Flexbox Pricing &amp; Login Lab &mdash; Assignment 7.2</p>
  </footer>

</body>
</html>