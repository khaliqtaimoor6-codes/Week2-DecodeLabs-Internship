# Folio — Creative Studio (Landing Page)

A clean, editorial-style **single-page portfolio/agency website** built with **semantic HTML + modern CSS** (no frameworks, no JavaScript). It’s designed as a creative studio landing page with sections for Work, About, Services, Journal, and Contact.

## Live Sections

- **Sticky header navigation** with anchor links: Work, About, Services, Journal, Contact
- **Hero** with animated headline, studio “eyebrow”, CTA buttons, and a scrolling ticker
- **Stats strip** (projects, countries, years, awards)
- **Selected Work** grid with a featured card layout
- **About** split layout with image blocks + capability pills
- **Services** list with hover interactions
- **Journal** teaser cards
- **Contact** CTA with `mailto:` button + social links
- **Footer**

## Frontend Functionality (No JS)

This project focuses on UI/UX behaviors implemented purely with HTML/CSS:

- **Responsive navigation**
  - Desktop nav appears at `min-width: 1024px`
  - Mobile uses the **HTML Popover API** (`popover`, `popovertarget`) for a slide-in full-screen menu (zero JS)
- **Smooth scrolling** via CSS (`scroll-behavior: smooth`)
- **CSS animations / motion**
  - Hero headline slide-in + fade-up entrance
  - Decorative “ink-blot” background drift
  - Continuous ticker scrolling animation
- **Hover interactions**
  - Work cards lift with shadow on hover
  - Services arrow shifts and changes color on hover
  - Journal cards highlight on hover
- **Accessibility**
  - `:focus-visible` outline styling
  - Touch-friendly targets (`min-height: 44px` on key controls)
  - `prefers-reduced-motion` support (animations/transitions are minimized)

## Tech Stack

- **HTML5** (semantic sections, ARIA labels)
- **CSS3**
  - CSS variables (design tokens)
  - Grid + Flexbox layouts
  - Fluid typography using `clamp()`
  - Media queries for responsive breakpoints
- **Fonts**: Google Fonts (Playfair Display, DM Mono, Lora)

## Project Structure

- `index.html` — page markup and sections
- `style.css` — full styling, animations, responsive breakpoints

## How to Run

Option 1: Open directly
- Double-click `index.html` to open it in your browser.

Option 2: Use VS Code Live Server (recommended)
- Install the **Live Server** extension
- Right-click `index.html` → **Open with Live Server**

## Notes / Compatibility

- The mobile menu relies on the **Popover API**, which works in modern Chromium-based browsers (Chrome/Edge). If you need Safari/older browser support, the menu would need a JS/CSS fallback.

---

Built for Week 2 — Decode Labs Internship.
