# Plain static site — keep it that way

This is a hand-written HTML/CSS site with no build step, no package.json, and no framework. Do not introduce Node tooling, bundlers, or frameworks. Edit `index.html`, `conduct.html`, and `css/main.css` directly.

Style notes:

- Two pages, one stylesheet. Course cards on `index.html` mirror the [Kai-Course-Notes](https://github.com/kaiiiichen/Kai-Course-Notes) repository — one card per course, grouped by school.
- Aesthetic: a clean course catalog. Restrained palette: pure-white light background, accent is a scholarly ink blue `hsl(215, 70%, 38%)` (brightened on dark surfaces for legibility), monospace for headings and course codes.
- Support light and dark via `light-dark()`.
- Adding a course: one `<article class="card">` in the right school section, plus the badge count in the hero.
- Sibling references for structure/conventions: https://github.com/Kai-s-Hitorigaisha/Kai-s-Hitorigaisha.github.io and https://github.com/SudoSodokuApp/SudoSodokuApp.github.io
