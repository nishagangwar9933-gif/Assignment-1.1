<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Projects &amp; Blog | Your Full Name</title>
</head>
<body>

  <!-- Header & Working Navigation Bar -->
  <header id="top-header">
    <h1>&lt;YourName /&gt; &mdash; Projects &amp; Dev Blog</h1>
    <p><em>Detailed write-ups on my web development projects and weekly study notes.</em></p>

    <nav aria-label="Primary Navigation">
      <ul>
        <li><a href="index.html">Home</a></li>
        <li><a href="index.html#about-me">About Me</a></li>
        <li><a href="index.html#skills-interests">Skills &amp; Interests</a></li>
        <li><a href="projects.html">Projects &amp; Blog Posts</a></li>
        <li><a href="index.html#useful-links">Useful Links</a></li>
        <li><a href="#contact-footer">Contact</a></li>
      </ul>
    </nav>
  </header>

  <hr />

  <!-- Main Content -->
  <main>

    <!-- Projects Section -->
    <section aria-labelledby="all-projects-heading">
      <h2 id="all-projects-heading">Completed Web Projects</h2>

      <article id="project-semantic-site">
        <h3>1. Semantic Personal Introduction Website</h3>
        <p><small>Published: <time datetime="2026-11-10">November 10, 2026</time> | Category: HTML5</small></p>
        <img
          src="images/project-html.jpg"
          alt="Screenshot of semantic personal introduction website rendered in Chrome"
          width="400"
          height="240"
        />
        <p>
          <strong>Overview:</strong> Built a structured personal introduction webpage using pure HTML5 semantic tags. 
          The page organizes biography, education, technical skills, and contact links without relying on CSS.
        </p>
        <p><strong>Key Features Implemented:</strong></p>
        <ul>
          <li>Landmark structure with <code>&lt;header&gt;</code>, <code>&lt;main&gt;</code>, <code>&lt;section&gt;</code>, and <code>&lt;footer&gt;</code></li>
          <li>Accessible internal jump links and external links secured with <code>rel="noopener noreferrer"</code></li>
          <li>Validated through the W3C HTML Validator with zero markup errors</li>
        </ul>
      </article>

      <hr />

      <article id="project-college-directory">
        <h3>2. College Course &amp; Syllabus Information Portal</h3>
        <p><small>Published: <time datetime="2026-11-14">November 14, 2026</time> | Category: Information Architecture</small></p>
        <p>
          <strong>Overview:</strong> Created an academic information page presenting core computer science subjects, 
          step-by-step admission procedures, nested syllabus units, and a faculty directory using <code>&lt;ul&gt;</code>, 
          <code>&lt;ol&gt;</code>, and <code>&lt;dl&gt;</code> lists.
        </p>
      </article>
    </section>

    <hr />

    <!-- Blog Posts Section -->
    <section aria-labelledby="blog-posts-heading">
      <h2 id="blog-posts-heading">Developer Blog Posts</h2>

      <article id="blog-semantic-html">
        <h3>Why Semantic HTML5 Matters for Accessibility &amp; SEO</h3>
        <p><small>Posted on <time datetime="2026-11-16">November 16, 2026</time> &bull; 3 min read</small></p>
        <img
          src="images/project-git.jpg"
          alt="Terminal and code editor showing clean HTML markup and Git commit history"
          width="400"
          height="240"
        />
        <p>
          When beginners first learn HTML, it is tempting to wrap every block in a <code>&lt;div&gt;</code>. However, 
          replacing generic containers with elements like <code>&lt;nav&gt;</code>, <code>&lt;main&gt;</code>, 
          <code>&lt;article&gt;</code>, and <code>&lt;aside&gt;</code> gives browsers, search engines, and screen readers 
          clear context about how a page is organized.
        </p>
        <p>
          Combined with descriptive <code>alt</code> attributes on images and meaningful link text, semantic HTML 
          makes the web usable for everyone before a single line of CSS is written.
        </p>
      </article>
    </section>

    <p><a href="index.html">&larr; Back to Home Page</a></p>

  </main>

  <hr />

  <!-- Footer with Contact Details -->
  <footer id="contact-footer">
    <h2>Contact Details</h2>
    <ul>
      <li><strong>Email:</strong> <a href="mailto:your.email@example.com">your.email@example.com</a></li>
      <li><strong>GitHub:</strong> <a href="https://github.com/yourusername" target="_blank" rel="noopener noreferrer">github.com/yourusername</a></li>
    </ul>
    <p><small>&copy; 2026 Your Full Name &mdash; Assignment 3.5 Mini-Project</small></p>
  </footer>

</body>
</html>