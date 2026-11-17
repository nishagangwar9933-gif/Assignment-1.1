# Assignment 3.4 — Semantic HTML & Accessibility

## Task Summary
Converted a `<div>`-based webpage (from Assignment 2.3) into meaningful, accessible **Semantic HTML5** using landmark elements (`<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<aside>`, `<footer>`), strict heading hierarchy (`<h1>` &rarr; `<h2>` &rarr; `<h3>`), descriptive image `alt` attributes, and self-explanatory link labels.

## Key Semantic & Accessibility Improvements
| Old `<div>`-Based Structure | New Semantic HTML5 Element | Accessibility Benefit |
| :--- | :--- | :--- |
| `<div id="header-section">` | `<header>` | Identifies introductory site branding and top-level heading |
| `<div class="nav-links">` | `<nav aria-label="...">` | Lets screen readers jump straight to primary navigation links |
| `<div id="page-container">` | `<main>` | Marks the primary unique content of the page (skipping repeated headers) |
| `<div class="section-container">` | `<section>` | Groups thematically related content with clear `<h2>` section headings |
| `<div class="content-card">` | `<article>` | Marks self-contained, reusable entries (projects and education items) |
| `<div class="sidebar-notes">` | `<aside>` | Separates tangential tips and external resources from the main flow |
| `<div id="footer">` | `<footer>` | Identifies contact details and copyright metadata |
| Vague `"Click here"` links | Descriptive link text | Screen reader users scanning links out of context understand each destination |

## Requirements Checklist
- [x] Structured page using `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<aside>`, and `<footer>`
- [x] Placed primary navigation links inside `<nav>`
- [x] Wrapped core page sections inside `<main>`
- [x] Maintained strict heading hierarchy (`<h1>` &rarr; `<h2>` &rarr; `<h3>` with zero skipped levels)
- [x] Added meaningful `alt` text on the profile `<img>`
- [x] Verified all link labels and section landmarks are clear and understandable

## Before & After Screenshots
### Before (Div-Based Layout & DevTools Elements Tree)
*(Insert your screenshot of the Assignment 2.3 `<div>`-based page and its DevTools Elements panel here)*

### After (Semantic HTML5 Layout & DevTools Elements Tree)
*(Insert your screenshot of the updated semantic `index.html` page and its DevTools Elements panel showing `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<aside>`, and `<footer>` here)*