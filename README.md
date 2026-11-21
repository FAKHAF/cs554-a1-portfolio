# Responsive Developer Portfolio

CS-554 Advanced Web Technologies, Assignment 1 (Version A). A fast, accessible, 3-page portfolio built with plain HTML5, CSS3 and JavaScript. No frameworks.

**Live site:** https://FAKHAF.github.io/cs554-a1-portfolio/

![Screenshot of the portfolio home page](screenshot.png)

## Pages
- `index.html`: hero, about me, skills
- `projects.html`: project cards rendered by JavaScript, with search and a technology filter
- `contact.html`: contact form with JavaScript validation

## Features
- Semantic HTML5, one `h1` per page, labelled form fields and `fieldset`/`legend` radio group
- One shared stylesheet, Flexbox navbar, CSS Grid cards (1 / 2 / 3 columns at 0 / 640 / 1024 px)
- CSS custom properties with a dark theme (OS preference and manual toggle saved in `localStorage`)
- Safe DOM rendering (`createElement`, `textContent`), combined search and filter, empty state, `aria-live` result count
- Per-field form validation with accessible error messages
- Bonus: entrance animation that respects `prefers-reduced-motion`

## Run locally
Open `index.html` in a browser.
