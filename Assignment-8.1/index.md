
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Dashboard Grid Layout | Assignment 8.1</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>

  <!-- Outer Dashboard Grid Container -->
  <div class="dashboard-grid">

    <!-- 1. Dashboard Header -->
    <header class="dashboard-header">
      <h2>Admin Dashboard</h2>
      <span class="user-profile">Hello, Student</span>
    </header>

    <!-- 2. Sidebar Navigation -->
    <aside class="dashboard-sidebar">
      <nav aria-label="Dashboard Sidebar">
        <ul>
          <li><a href="#" class="active">Overview</a></li>
          <li><a href="#">Analytics</a></li>
          <li><a href="#">Reports</a></li>
          <li><a href="#">Settings</a></li>
        </ul>
      </nav>
    </aside>

    <!-- 2 & 3. Main Content Area with 4 Statistic Cards -->
    <main class="dashboard-main">
      <h1>Dashboard Overview</h1>
      <p>Welcome back! Here is your system performance and statistic summary for today.</p>

      <!-- Statistic Cards Grid -->
      <div class="stats-grid">
        <div class="stat-card">
          <h3>Total Users</h3>
          <p class="stat-value">1,245</p>
        </div>
        <div class="stat-card">
          <h3>Active Sessions</h3>
          <p class="stat-value">328</p>
        </div>
        <div class="stat-card">
          <h3>Bounce Rate</h3>
          <p class="stat-value">24.2%</p>
        </div>
        <div class="stat-card">
          <h3>Conversion Rate</h3>
          <p class="stat-value">4.8%</p>
        </div>
      </div>
    </main>

  </div>

</body>
</html>