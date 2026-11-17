<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Dashboard with Grid and Flexbox | Assignment 8.4</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>

  <!-- Outer Dashboard Grid Layout -->
  <div class="dashboard-grid">

    <!-- 1. Dashboard Header -->
    <header class="dashboard-header">
      <h2>CodeCraft Analytics</h2>
      <div class="user-profile">
        <span>Welcome, Student</span>
        <div class="avatar">SC</div>
      </div>
    </header>

    <!-- 1 & 2. Sidebar Navigation -->
    <aside class="dashboard-sidebar">
      <nav aria-label="Dashboard Sidebar">
        <ul class="sidebar-menu">
          <li><a href="#" class="active">Dashboard</a></li>
          <li><a href="#">Analytics</a></li>
          <li><a href="#">Projects</a></li>
          <li><a href="#">Team</a></li>
          <li><a href="#">Settings</a></li>
        </ul>
      </nav>
    </aside>

    <!-- 1, 3, 4 & 5. Main Content Area -->
    <main class="dashboard-main">
      <div class="main-header">
        <h1>Dashboard Overview</h1>
        <p>Monitor your core performance metrics and recent activities.</p>
      </div>

      <!-- 3 & 4. Four Statistic Cards (Aligned using Flexbox) -->
      <section class="stats-grid">
        <!-- Card 1 -->
        <article class="stat-card">
          <div class="stat-icon bg-blue">📁</div>
          <div class="stat-content">
            <h3>Total Projects</h3>
            <p class="stat-value">24</p>
          </div>
        </article>

        <!-- Card 2 -->
        <article class="stat-card">
          <div class="stat-icon bg-green">👥</div>
          <div class="stat-content">
            <h3>Active Users</h3>
            <p class="stat-value">1,420</p>
          </div>
        </article>

        <!-- Card 3 -->
        <article class="stat-card">
          <div class="stat-icon bg-purple">📈</div>
          <div class="stat-content">
            <h3>Conversion Rate</h3>
            <p class="stat-value">12.8%</p>
          </div>
        </article>

        <!-- Card 4 -->
        <article class="stat-card">
          <div class="stat-icon bg-orange">⚡</div>
          <div class="stat-content">
            <h3>System Uptime</h3>
            <p class="stat-value">99.9%</p>
          </div>
        </article>
      </section>

      <!-- 5. Recent Activity / Table Section -->
      <section class="activity-section">
        <div class="section-title">
          <h3>Recent Student Submissions</h3>
          <a href="#" class="view-all">View All</a>
        </div>
        <div class="table-container">
          <table class="activity-table">
            <thead>
              <tr>
                <th>Assignment</th>
                <th>Module</th>
                <th>Status</th>
                <th>Submitted Date</th>
              </tr>
            </thead>
            <tbody>
              <tr>
                <td>Assignment 8.3 — Magazine Layout</td>
                <td>Module 8 (CSS Grid)</td>
                <td><span class="badge badge-success">Completed</span></td>
                <td>Nov 16, 2026</td>
              </tr>
              <tr>
                <td>Assignment 8.2 — Photo Gallery</td>
                <td>Module 8 (CSS Grid)</td>
                <td><span class="badge badge-success">Completed</span></td>
                <td>Nov 15, 2026</td>
              </tr>
              <tr>
                <td>Assignment 8.1 — Dashboard Grid</td>
                <td>Module 8 (CSS Grid)</td>
                <td><span class="badge badge-success">Completed</span></td>
                <td>Nov 14, 2026</td>
              </tr>
              <tr>
                <td>Assignment 7.5 — Flexbox Mini-Project</td>
                <td>Module 7 (Flexbox)</td>
                <td><span class="badge badge-success">Completed</span></td>
                <td>Nov 12, 2026</td>
              </tr>
            </tbody>
          </table>
        </div>
      </section>
    </main>

  </div>

</body>
</html>