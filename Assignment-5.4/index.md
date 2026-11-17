/* ==========================================
   Assignment 5.4 — CSS Variables & Design Tokens
   ========================================== */

:root {
  /* 1 & 2. Color Design Tokens */
  --color-primary: #2563eb;       /* Royal Blue */
  --color-secondary: #0ea5e9;     /* Sky Blue */
  --color-bg: #f8fafc;            /* Light Slate Background */
  --color-surface: #ffffff;       /* Card / Container Surface */
  --color-text: #1e293b;          /* Dark Text */
  --color-text-muted: #64748b;    /* Subtitle / Muted Text */

  /* 3. Spacing Design Tokens */
  --spacing-sm: 8px;
  --spacing-md: 16px;
  --spacing-lg: 24px;
  --spacing-xl: 32px;

  /* 4. Font Size Design Tokens */
  --font-size-sm: 0.875rem;
  --font-size-base: 1rem;
  --font-size-lg: 1.25rem;
  --font-size-xl: 1.75rem;
}

/* Base Styles Using Variables */
body {
  font-family: system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  background-color: var(--color-bg);
  color: var(--color-text);
  padding: var(--spacing-lg);
  max-width: 800px;
  margin: 0 auto;
  line-height: 1.6;
}

/* 5. Headings Using Variables */
h1, h2, h3 {
  color: var(--color-primary);
  margin-bottom: var(--spacing-md);
  font-weight: 700;
}

h1 {
  font-size: var(--font-size-xl);
}

h2 {
  font-size: var(--font-size-lg);
}

p {
  font-size: var(--font-size-base);
  color: var(--color-text);
  margin-bottom: var(--spacing-md);
}

/* 5. Cards Using Variables */
.card {
  background-color: var(--color-surface);
  padding: var(--spacing-lg);
  border-radius: 8px;
  margin-bottom: var(--spacing-lg);
  box-shadow: 0 1px 3px rgba(0, 0, 0, 0.05);
  border: 1px solid #e2e8f0;
}

/* 5. Buttons Using Variables */
.btn {
  background-color: var(--color-primary);
  color: #ffffff;
  padding: var(--spacing-sm) var(--spacing-md);
  border: none;
  border-radius: 6px;
  font-size: var(--font-size-base);
  font-weight: 500;
  cursor: pointer;
  transition: background-color 0.2s ease-in-out;
}

.btn:hover {
  background-color: var(--color-secondary);
}