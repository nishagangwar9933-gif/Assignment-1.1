<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Box Model Inspection | Assignment 6.1</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>

  <!-- Header -->
  <header>
    <h1>CSS Box Model Inspection</h1>
    <p>Exploring content, padding, border, margin, and box-sizing properties.</p>
  </header>

  <hr style="border: none; border-top: 1px solid #cbd5e1; margin: 24px 0;" />

  <!-- Main Content: 3 Boxes -->
  <main>
    <!-- Box 1: content-box -->
    <div class="box box-1">
      <h2>Box One (content-box)</h2>
      <p>This box uses default content-box sizing where padding and borders add to the total width.</p>
    </div>

    <!-- Box 2: border-box -->
    <div class="box box-2">
      <h2>Box Two (border-box)</h2>
      <p>This box uses border-box sizing to keep total width predictable including padding and borders.</p>
    </div>

    <!-- Box 3: Custom Padding, Border & Margin -->
    <div class="box box-3">
      <h2>Box Three (Custom Spacing)</h2>
      <p>This box features generous padding, thick dashed borders, and wide outer margins.</p>
    </div>
  </main>

  <!-- Footer -->
  <footer>
    <p style="font-size: 0.875rem; color: #64748b;">&copy; 2026 CSS Box Model Lab &mdash; Assignment 6.1</p>
  </footer>

</body>
</html>