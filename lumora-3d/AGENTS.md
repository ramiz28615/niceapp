# LUMORA 3D — Project Agent / Skill Instructions

## Purpose
Maintain a distinctive, fast, accessible Turkish e-commerce **frontend demo** with interactive 3D experiences. Do not present local demo functionality as production services.

## Project structure
- `index.html`: single-file HTML, CSS and vanilla JavaScript.
- `PRODUCTS` / `CATS`: demo catalogue; prices and stock are illustrative.
- `localStorage` key `lumora-demo-v1`: only demo cart, favorites, profile and orders.
- WebGL Three.js model renderer dynamically loaded from CDN; gracefully degrade to visible CSS/emoji art.

## Visual standards
- Strong typographic hierarchy, premium editorial direction, semantic design tokens and consistent spacing.
- Accessible controls, focus visibility, labels, `aria-pressed`, mobile responsive layout.
- Honor `prefers-reduced-motion` and avoid heavy GPU work offscreen.

## Safety and production boundary
- Never place provider tokens, API keys, payment credentials or private user data in frontend files.
- Keep server authority over orders, inventory, totals, discounts, roles and transaction state if adding real commerce.
- A genuine Base44 integration requires official SDK/CLI, authenticated app profile, entity schemas, permissions and server functions; do not claim connection without configuring them.

## QA acceptance
1. Validate HTML structure and JavaScript syntax.
2. Verify search/filter/sort, demo checkout, coupon, cart and favorites.
3. Verify 3D model picker, color variations, rotation and WebGL fallback.
4. Verify 390px, tablet and desktop widths with no horizontal overflow.
5. Clearly label all demo-only features.
