# Assignment 2.4 — HTML Validation & Debugging

## Task Summary
Diagnosed, validated, and repaired an intentionally broken HTML document containing missing `<!DOCTYPE html>`, missing required attributes, improperly nested tags, unclosed elements, and inconsistent indentation using Chrome DevTools and the W3C Markup Validation Service.

---

## 1. Before: Buggy HTML Code (`buggy-index.html`)

```html
<html>
<head>
  <title>My Profile Page
</head>
<body>
  <div id="header>
    <h1>Welcome to My Webpage</h2>
    <p>This is a <strong><em>bold and italic</strong</em> introduction paragraph.
  </div>

  <div class="content">
    <h2>Favorite Resource</h2>
    <img src="profile.jpg">
    <p>Visit my favorite coding site: <a target="_blank">Example Website</a></p>
    <ul>
      <li>HTML Basics
      <li>CSS Styling
    </ul>
  </div>
</body>