# Contributing to kai-course-notes.kaichen.dev

Thanks for helping improve the Kai Course Notes showcase site! This repo
is the website only — for the course materials themselves (notes,
homework, projects, and content policy questions), head to
[kaiiiichen/Kai-Course-Notes](https://github.com/kaiiiichen/Kai-Course-Notes).

## What we welcome

* 🐛 **Display bugs** — layout breakage, light/dark scheme issues,
  horizontal scroll on mobile, broken links
* 📝 **Copy fixes** — typos, grammar, clarity
* ♿ **Accessibility** — contrast, semantics, keyboard navigation

## What we will decline

* Frameworks, bundlers, npm, or any build step — this site is plain
  HTML + CSS on purpose (see [AGENTS.md](AGENTS.md))
* Webfonts, analytics, or any external request
* JavaScript, unless the feature is impossible without it and the page
  still works with JS off
* Course-content changes — course cards mirror the
  [Kai-Course-Notes](https://github.com/kaiiiichen/Kai-Course-Notes)
  repository; fix things there first

## Getting started

```sh
git clone https://github.com/kaiiiichen/kai-course-notes.kaichen.dev.git
cd kai-course-notes.kaichen.dev
python3 -m http.server 8080   # then open http://localhost:8080
```

Nothing to install, nothing to build.

## Before opening a PR

1. Open both pages in a browser.
2. Check light + dark scheme, 375px + 1280px widths.
3. No horizontal scroll, no console errors, no external requests.
4. All links resolve (CI runs `proof-html` on every push).

## Code style

* Tabs for indentation in HTML/CSS (match the existing files).
* Conventions and aesthetic rules: [AGENTS.md](AGENTS.md).
* Keep changes surgical — touch only what your fix requires.

## Code of Conduct

This project follows the [Contributor Covenant](CODE_OF_CONDUCT.md).
