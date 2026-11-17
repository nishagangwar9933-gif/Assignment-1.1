/* ==========================================
   Assignment 5.5 — CSS Fundamentals Mini-Project
   College Club Website Design System & Styles
   ========================================== */

/* 1. Design Tokens & CSS Variables (:root) */
:root {
  --color-primary: #1d4ed8;       /* Royal Blue */
  --color-secondary: #0ea5e9;     /* Sky Blue Accent */
  --color-bg: #f8fafc;            /* Light Slate Background */
  --color-surface: #ffffff;       /* Card & Container White Surface */
  --color-text: #1e293b;          /* Dark Slate Text */
  --color-text-muted: #64748b;    /* Subtitle & Footer Text */
  --color-border: #cbd5e1;        /* Subtle Border Gray */

  --spacing-sm: 8px;
  --spacing-md: 16px;
  --spacing-lg: 24px;
  --spacing-xl: 32px;

  --font-base: system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
}

/* 2. Universal Reset & Base Styles */
* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}

body {
  font-family: var(--font-base);
  background-color: var(--color-bg);
  color: var(--color-text);
  line-height: 1.6;
  max-width: 900px;
  margin: 0 auto;
  padding: var(--spacing-lg);
}

/* 3. Typography & Headings */
h1, h2, h3 {
  color: var(--color-primary);
  margin-bottom: var(--spacing-md);
  font-weight: 700;
}

h1 {
  font-size: 2rem;
  border-bottom: 3px solid var(--color-primary);
  padding-bottom: var(--spacing-sm);
}

h2 {
  font-size: 1.5rem;
  margin-top: var(--spacing-lg);
}

h3 {
  font-size: 1.2rem;
}

p {
  margin-bottom: var(--spacing-md);
}

/* 4. Links & Navigation Bar */
a {
  color: var(--color-primary);
  text-decoration: none;
  font-weight: 500;
  transition: color 0.2s ease;
}

a:hover {
  color: var(--color-secondary);
  text-decoration: underline;
}

header {
  background-color: var(--color-surface);
  border: 1px solid var(--color-border);
  border-radius: 8px;
  padding: var(--spacing-lg);
  margin-bottom: var(--spacing-lg);
  box-shadow: 0 1px 3px rgba(0, 0, 0, 0.05);
}

nav {
  margin-top: var(--spacing-md);
  background-color: #f1f5f9;
  padding: var(--spacing-sm) var(--spacing-md);
  border-radius: 6px;
}

nav ul {
  list-style: none;
  display: flex;
  flex-wrap: wrap;
  gap: var(--spacing-md);
  align-items: center;
}

nav a {
  color: #334155;
  padding: 6px 12px;
  border-radius: 4px;
  font-size: 0.95rem;
}

nav a:hover {
  background-color: var(--color-primary);
  color: #ffffff;
  text-decoration: none;
}

/* 5. Main Content Containers & Sections */
main, section, aside, article {
  background-color: var(--color-surface);
  border: 1px solid var(--color-border);
  border-radius: 8px;
  padding: var(--spacing-lg);
  margin-bottom: var(--spacing-lg);
  box-shadow: 0 1px 3px rgba(0, 0, 0, 0.05);
}

/* 6. Tables Styling */
table {
  width: 100%;
  border-collapse: collapse;
  margin-top: var(--spacing-md);
  margin-bottom: var(--spacing-md);
  background-color: var(--color-surface);
}

th, td {
  border: 1px solid var(--color-border);
  padding: 10px 14px;
  text-align: left;
  font-size: 0.95rem;
}

th {
  background-color: #f1f5f9;
  color: var(--color-primary);
  font-weight: 600;
}

tfoot td {
  background-color: #f8fafc;
  font-style: italic;
}

/* 7. Forms Styling */
fieldset {
  border: 1px solid var(--color-border);
  border-radius: 6px;
  padding: var(--spacing-md);
  margin-bottom: var(--spacing-md);
  background-color: #fafafa;
}

legend {
  font-weight: 600;
  color: var(--color-primary);
  padding: 0 8px;
}

label {
  font-weight: 500;
  display: inline-block;
  margin-bottom: 4px;
}

input[type="text"],
input[type="email"],
input[type="tel"],
input[type="date"],
input[type="url"],
select,
textarea {
  width: 100%;
  padding: 10px;
  border: 1px solid var(--color-border);
  border-radius: 6px;
  font-family: var(--font-base);
  font-size: 1rem;
  margin-bottom: var(--spacing-sm);
  background-color: #ffffff;
}

input:focus, select:focus, textarea:focus {
  outline: none;
  border-color: var(--color-primary);
  box-shadow: 0 0 0 3px rgba(29, 78, 216, 0.15);
}

input[type="radio"],
input[type="checkbox"] {
  margin-right: 6px;
}

/* Buttons */
button[type="submit"],
button[type="reset"] {
  background-color: var(--color-primary);
  color: #ffffff;
  border: none;
  border-radius: 6px;
  padding: 10px 20px;
  font-size: 1rem;
  font-weight: 600;
  cursor: pointer;
  margin-right: var(--spacing-sm);
  transition: background-color 0.2s ease;
}

button[type="submit"]:hover {
  background-color: #1e40af;
}

button[type="reset"] {
  background-color: #64748b;
}

button[type="reset"]:hover {
  background-color: #475569;
}

/* Footer Styling */
footer {
  text-align: center;
  background-color: var(--color-surface);
  border: 1px solid var(--color-border);
  border-radius: 8px;
  padding: var(--spacing-md);
  color: var(--color-text-muted);
  font-size: 0.9rem;
}