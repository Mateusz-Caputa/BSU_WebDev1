# Exercise 3: Page Layout

## Layout Techniques Used

1. `body`: Flexbox, column direction, centres content horizontally.
2. `ul`: CSS Grid, auto column flow, horizontal navigation bar.
3. `#about > img`: Float right, text wraps around the image.
4. `#gallery`: Flexbox, row direction with wrapping, images fill available space.

# Exercise 3: Extras

## Responsive Design
 
- Four breakpoints: 1000px, 750px, 550px, 380px.
- Font sizes scale down at each breakpoint using CSS custom properties (`--title-size`, `--text-size`).
- Gallery image height reduces at each breakpoint.
- Gallery switches to single column below 380px.
 
## JavaScript — Lightbox
 
- Click any image to open a fullscreen preview.
- Close by clicking the background or the close button.
- Fade-in and fade-out CSS animations.
- Element is hidden after the close animation finishes using the `animationend` event.
 
## Accessibility
 
- Semantic elements: `<header>`, `<nav>`, `<main>`, `<section>`.
- `aria-label` on navigation and both sections.
- `alt` text on all images.
- `loading="lazy"` on gallery images.
- Fallback text inside `<video>` for unsupported browsers.
 