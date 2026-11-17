/* ==========================================
   Assignment 5.1 — Global Styles & Typography
   ========================================== */

/* 1. Base Styles & Body Setup */
body {
  font-family: system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
  background-color: #f8fafc; /* Soft light slate background */
  color: #1e293b; /* Dark slate text for high readability */
  line-height: 1.6;
  max-width: 900px;
  margin: 0 auto;
  padding: 24px;
}

/* 2. Headings Styling */
h1, h2, h3, h4, h5, h6 {
  color: #0f172a; /* Deep navy for headings */
  margin-top: 24px;
  margin-bottom: 12px;
  font-weight: 700;
}

h1 {
  font-size: 2.25rem;
  border-bottom: 3px solid #2563eb;
  padding-bottom: 8px;
}

h2 {
  font-size: 1.75rem;
  color: #1d4ed8;
}

h3 {
  font-size: 1.25rem;
}

/* 3. Paragraphs & Text Content */
p {
  margin-bottom: 16px;
  font-size: 1rem;
}

/* 4. Links Styling */
a {
  color: #2563eb; /* Vibrant royal blue */
  text-decoration: none;
  font-weight: 500;
  transition: color 0.2s ease-in-out;
}

a:hover {
  color: #1d4ed8;
  text-decoration: underline;
}

/* 5. Readable & Attractive Navigation Bar */
nav {
  background-color: #ffffff;
  border: 1px solid #e2e8f0;
  border-radius: 8px;
  padding: 12px 16px;
  margin-top: 16px;
  box-shadow: 0 1px 3px rgba(0, 0, 0, 0.05);
}

nav ul {
  list-style: none;
  padding: 0;
  margin: 0;
  display: flex;
  flex-wrap: wrap;
  gap: 16px;
  align-items: center;
}

nav li {
  margin: 0;
}

nav a {
  color: #475569;
  background-color: #f1f5f9;
  padding: 6px 12px;
  border-radius: 6px;
  font-size: 0.9rem;
}

nav a:hover {
  background-color: #2563eb;
  color: #ffffff;
  text-decoration: none;
}

/* 6. Containers, Cards & Tables */
header, main, section, footer {
  background-color: #ffffff;
  border-radius: 8px;
  padding: 24px;
  margin-bottom: 24px;
  box-shadow: 0 1px 3px rgba(0, 0, 0, 0.05);
  border: 1px solid #e2e8f0;
}

table {
  width: 100%;
  border-collapse: collapse;
  margin-top: 16px;
  margin-bottom: 16px;
}

th, td {
  border: 1px solid #cbd5e1;
  padding: 10px 12px;
  text-align: left;
}

th {
  background-color: #f1f5f9;
  color: #0f172a;
}