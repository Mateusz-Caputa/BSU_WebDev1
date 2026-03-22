# Exercise 2: CSS Styling

## CSS Techniques
 
- **Custom properties** — `:root` variables for colours (`--color-gray`, `--color-white`, `--color-green`, `--color-purple`) and font sizes (`--font-size-h1` through `--font-size-p`).
- **Reset** — default `margin` and `padding` removed with `*` selector.
- **Box model** — `margin`, `padding`, and `border-radius` used throughout for spacing and rounded corners.
- **Typography** — font family, size, weight, colour, and alignment set per element.
- **Auto centering** — `article` centred horizontally using `margin: 0 auto` with a percentage width.
 
## Pseudo-classes & Animation
 
- **`:hover`** — used on `h1` to trigger animation, and on `aside` to change background colour to purple.
- **`@keyframes heartbeat`** — scales the title from `1.0` to `1.2` on hover, runs as an infinite alternating animation.
 
## Responsive Design
 
- Three breakpoints with article width and font sizes adjusting at each:
  - `950px` — fonts reduce, article width set to `70%`.
  - `600px` — fonts reduce further, article width set to `80%`.
  - `360px` — article goes full width, border radius removed, body padding removed.
- **Variable overwriting** — `:root` CSS variables redefined inside each media query so all elements update automatically.
 
## Accessibility
 
- **`prefers-reduced-motion`** — heartbeat animation disabled for users who have reduced motion enabled in their OS settings.
- Semantic elements: `<main>`, `<article>`, `<header>`, `<section>`, `<aside>`.
- `lang="en"` set on `<html>`.

### `styles.min.css` - Minified version provided for performance improvements.