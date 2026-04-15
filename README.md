# Profile Card — Stage 1B (Frontend)

A responsive, accessible profile card built with semantic HTML, modern CSS, and vanilla JavaScript.

## Live Demo

🔗 [https://profile-cardhng1.netlify.app](https://profile-cardhng1.netlify.app)

## GitHub Repo

🔗 [https://github.com/JAE5IVE/Profile-cardHNGTask1](https://github.com/JAE5IVE/Profile-cardHNGTask1)

---

## Features

- ✅ All required `data-testid` attributes present
- ✅ Semantic HTML (`<article>`, `<header>`, `<figure>`, `<nav>`, `<section>`, `<time>`, `<footer>`)
- ✅ Live epoch time in milliseconds (updates every 1 second via `Date.now()`)
- ✅ Accessible avatar with `alt` text
- ✅ Social links open in new tab with `rel="noopener noreferrer"`
- ✅ Keyboard-navigable — all links have visible focus styles
- ✅ `aria-live="polite"` on epoch time element for screen reader announcements
- ✅ WCAG AA color contrast compliant
- ✅ Responsive at mobile (< 640px), tablet, and desktop breakpoints
- ✅ Custom favicon (`.ico` and `.png`)
- ✅ No frameworks — plain HTML, CSS, JS only

---

## `data-testid` Reference

| Element              | `data-testid`                     |
|----------------------|-----------------------------------|
| Card root            | `test-profile-card`               |
| Name                 | `test-user-name`                  |
| Biography            | `test-user-bio`                   |
| Epoch time           | `test-user-time`                  |
| Avatar image         | `test-user-avatar`                |
| Social links list    | `test-user-social-links`          |
| GitHub link          | `test-user-social-github`         |
| LinkedIn link        | `test-user-social-linkedin`       |
| Hobbies section      | `test-user-hobbies`               |
| Dislikes section     | `test-user-dislikes`              |

---

## Run Locally

No build step required. Just open the file:

```bash
# Option 1: Double-click index.html to open in your browser

# Option 2: Open from terminal (Windows)
start index.html


```

---

## File Structure

```
/
├── index.html      # All HTML, CSS, and JS in one file
├── favicon.ico     # Favicon (multi-resolution)
├── favicon.png     # Favicon (PNG fallback)
└── README.md
```

---

## Deployment

Deployed via [Netlify](https://netlify.com) — connected to the `main` branch of the GitHub repo. Every `git push` to `main` triggers an automatic redeploy.