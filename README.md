# Week 4 — Frontend Performance Optimization

## Project
**Idea Star** is a responsive landing page built with semantic HTML, CSS, and vanilla JavaScript. It demonstrates performance-focused implementation without frameworks or external image/font dependencies.

## Run locally
1. Extract the ZIP file.
2. Open `index.html` in a modern browser, or use VS Code with the Live Server extension.
3. For Lighthouse testing, serve the folder over localhost (recommended) and open Chrome DevTools → Lighthouse.
4. Run Lighthouse for **Mobile** and **Desktop**, keeping the mode and conditions consistent between runs.

## Project structure
- `index.html` — page content and semantic structure
- `css/styles.css` — responsive styles and reduced-motion support
- `js/app.js` — small deferred interaction script
- `performance-report.md` — analysis, optimization choices, and measurement worksheet

## Notes
The report does not invent Lighthouse scores. Record actual baseline and optimized scores on your machine using the same browser, device mode, and network conditions. The initial baseline is described as a review checklist rather than a measured historical score because no pre-optimization deployment or Lighthouse output was supplied.
