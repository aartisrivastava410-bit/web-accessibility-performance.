# Web Accessibility and Performance: Week 4 Task

A static web page (Green Trails Club) optimized for performance and accessibility, built for the Yuva Intern Frontend Web Developer internship.

## Files

- `index.html`: semantic, accessible page structure
- `styles.css`: lightweight, optimized stylesheet

## Performance improvements

- One small external stylesheet with no unused rules and flat, low-specificity selectors
- CSS custom properties and CSS Grid, so fewer media queries are needed
- Explicit `width` and `height` on images to prevent layout shift
- `loading="lazy"` on images
- Lightweight inline SVG images, so there are no extra requests
- System font stack, so no web fonts are downloaded
- No JavaScript, so nothing blocks rendering

## Accessibility improvements

- Semantic landmarks: `header`, `nav`, `main`, `section`, `footer`
- Logical heading hierarchy (one `h1`, then `h2` and `h3`)
- Skip-to-content link for keyboard users
- ARIA attributes: `aria-label`, `aria-labelledby`, `aria-current`, `aria-describedby`
- Descriptive `alt` text on all images
- Labeled form fields with proper input types and `autocomplete`
- Visible focus outlines and full keyboard navigation
- Color contrast of at least 4.5:1 (WCAG 2.1 AA)
- `prefers-reduced-motion` support and relative units (`rem`)

## Tools used

- Lighthouse (performance and accessibility audit)
- WAVE and axe DevTools (accessibility checks)
- WebPageTest (load timing)
- Manual keyboard and screen reader testing

## How to run

Download or clone the repo and open `index.html` in any browser.

## Author

Aarti Srivastava
