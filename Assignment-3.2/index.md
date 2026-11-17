<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Portfolio Gallery | DevJourney</title>
</head>
<body>

  <!-- Header & Navigation -->
  <header>
    <h1>DevJourney Portfolio</h1>
    <nav aria-label="Primary Navigation">
      <a href="index.html">Home</a> |
      <a href="#gallery">Project Gallery</a> |
      <a href="about.html">About</a>
    </nav>
  </header>

  <hr />

  <!-- Main Content -->
  <main>
    <section id="intro">
      <h2>Welcome to My Portfolio</h2>
      <p>
        Explore snapshots of my web development workspace, coding progress, and recent learning milestones below.
      </p>
    </section>

    <hr />

    <!-- Images Section (Assignment 3.2) -->
    <section id="gallery">
      <h2>Project &amp; Workspace Gallery</h2>
      <p>Here are three highlights from my web development journey:</p>

      <!-- Image 1 -->
      <figure>
        <img
          src="images/workspace.jpg"
          alt="Laptop displaying HTML code inside Visual Studio Code on a clean wooden desk"
          width="400"
          height="260"
        />
        <figcaption><strong>1. Development Workspace:</strong> My daily VS Code setup for building semantic HTML pages.</figcaption>
      </figure>

      <br />

      <!-- Image 2 -->
      <figure>
        <img
          src="images/html-structure.jpg"
          alt="Close-up view of a browser window displaying a structured personal portfolio webpage"
          width="400"
          height="260"
        />
        <figcaption><strong>2. Semantic Webpage Layout:</strong> Testing clean heading hierarchy and navigation links in Chrome.</figcaption>
      </figure>

      <br />

      <!-- Image 3 -->
      <figure>
        <img
          src="images/git-workflow.jpg"
          alt="Terminal window showing Git commit history and successful push to a GitHub repository"
          width="400"
          height="260"
        />
        <figcaption><strong>3. Version Control Workflow:</strong> Tracking code updates and pushing commits to GitHub.</figcaption>
      </figure>
    </section>
  </main>

  <hr />

  <!-- Footer -->
  <footer>
    <p><small>&copy; 2026 DevJourney Portfolio &mdash; Assignment 3.2</small></p>
  </footer>

</body>
</html>