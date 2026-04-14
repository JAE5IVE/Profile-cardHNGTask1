\# Profile Card — Stage 1B (Frontend)



A responsive, accessible profile card built with semantic HTML, modern CSS, and vanilla JavaScript.



\## Live Demo



> Deploy to Netlify / Vercel / GitHub Pages and paste the URL here.



\---



\## Features



\- ✅ All required `data-testid` attributes present

\- ✅ Semantic HTML (`<article>`, `<header>`, `<figure>`, `<nav>`, `<section>`, `<time>`, `<footer>`)

\- ✅ Live epoch time in milliseconds (updates every 1 second via `Date.now()`)

\- ✅ Accessible avatar with `alt` text

\- ✅ Social links open in new tab with `rel="noopener noreferrer"`

\- ✅ Keyboard-navigable — all links have visible focus styles

\- ✅ `aria-live="polite"` on epoch time element for screen reader announcements

\- ✅ WCAG AA color contrast compliant

\- ✅ Responsive at mobile (< 640px), tablet, and desktop breakpoints

\- ✅ No frameworks — plain HTML, CSS, JS only



\---



\## `data-testid` Reference



| Element              | `data-testid`                     |

|----------------------|-----------------------------------|

| Card root            | `test-profile-card`               |

| Name                 | `test-user-name`                  |

| Biography            | `test-user-bio`                   |

| Epoch time           | `test-user-time`                  |

| Avatar image         | `test-user-avatar`                |

| Social links list    | `test-user-social-links`          |

| GitHub link          | `test-user-social-github`         |

| Twitter/X link       | `test-user-social-twitter`        |

| LinkedIn link        | `test-user-social-linkedin`       |

| AltSchool link       | `test-user-social-altschool`      |

| Hobbies section      | `test-user-hobbies`               |

| Dislikes section     | `test-user-dislikes`              |



\---



\## Run Locally



No build step required. Just open the file:



```bash

\# Option 1: Open directly in browser

open index.html



\# Option 2: Serve with VS Code Live Server extension



\# Option 3: Python simple server

python3 -m http.server 3000

\# Then visit http://localhost:3000

```



\---



\## Deploy to GitHub Pages



1\. Push this repo to GitHub

2\. Go to \*\*Settings → Pages\*\*

3\. Set source to `main` branch, `/ (root)`

4\. Your card will be live at `https://<username>.github.io/<repo-name>/`



\## Deploy to Netlify (drag \& drop)



1\. Go to \[app.netlify.com](https://app.netlify.com)

2\. Drag the project folder onto the dashboard

3\. Done — instant live URL



\---



\## File Structure



```

/

└── index.html    # Everything lives here (HTML + CSS + JS)

└── README.md

```

