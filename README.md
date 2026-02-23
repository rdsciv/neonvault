# NeonVault

A cyberpunk-themed landing page built as a portfolio piece to demonstrate advanced front-end techniques in a single self-contained HTML file — no build tools, no frameworks, just raw browser APIs and CDN libraries.

**[View Live Demo](https://rdsciv.github.io/neonvault/)**

## What's Inside

- **Three.js particle sphere** — 4,000 points distributed via golden angle, custom vertex/fragment shaders, mouse-tracking parallax, breathing animation, and scroll-driven camera zoom
- **GSAP + ScrollTrigger** — scroll-pinned horizontal section, staggered entrance animations, animated stat counters, SVG stroke draw-ons, word-by-word text reveal
- **Lenis smooth scrolling** — integrated with GSAP's ticker for buttery scroll physics
- **Micro-interactions** — 3D card tilt with spotlight gradient, magnetic buttons, logo glitch effect, shimmer border animation, custom cursor
- **CSS effects** — CRT scanlines, noise grain overlay, infinite marquee, floating particles

## Tech Stack

| Library | Version | Purpose |
|---------|---------|---------|
| Three.js | r160 | WebGL particle sphere with custom shaders |
| GSAP | 3.12 | Scroll-driven animations and timelines |
| ScrollTrigger | 3.12 | Scroll-based triggers and horizontal pinning |
| Lenis | 1.1 | Smooth scroll with physics |

Everything loads from CDNs. Open `index.html` in a browser — no server required.

## Sections

1. **Loading screen** with progress bar
2. **Glassmorphic nav** — auto-hides on scroll, active section indicator
3. **Hero** — Three.js particle sphere, clip-reveal headline, CRT scanlines
4. **Stats** — animated counters (2.1M / <50ms / 99.99%)
5. **How It Works** — horizontally pinned scroll with SVG draw-on animations
6. **Features** — 3D tilt cards with mouse-following spotlight
7. **Trust** — infinite logo marquee, scroll-scrubbed testimonial reveal
8. **CTA** — shimmer border, floating particles, magnetic button
9. **Footer** — line draws from center on scroll

## Responsive

- Desktop: full Three.js effects, custom cursor, horizontal scroll, 3D tilt
- Mobile (< 768px): reduced particle count, vertical layout, touch-optimized
