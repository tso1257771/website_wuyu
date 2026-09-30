# Home Page Overrides

> **PROJECT:** Wu-Yu Liao
> **Generated:** 2026-09-30 09:10:00
> **Page Type:** Landing / Marketing

> ⚠️ **IMPORTANT:** Rules in this file **override** the Master file (`design-system/MASTER.md`).
> Only deviations from the Master are documented here. For all other rules, refer to the Master.

---

## Page-Specific Rules

### Layout Overrides

- **Max Width:** 1200px (standard)
- **Layout:** Full-width sections, centered content
- **Sections:** Hero (Name/Role) > Project Grid (Masonry) > About/Philosophy > Contact

### Spacing Overrides

- No overrides — use Master spacing

### Typography Overrides

- No overrides — use Master typography

### Color Overrides

- **Strategy:** Neutral background (let work shine). Text: Black/White. Accent: Minimal.

### Component Overrides

- Avoid: Ignore accessibility motion settings
- Avoid: Animate everything that moves
- Avoid: Force scroll effects

---

## Page-Specific Components

- No unique components for this page

---

## Recommendations

- Effects: Scroll anim (Intersection Observer), hover (300-400ms), entrance, parallax (3-5 layers), page transitions
- Animation: Check prefers-reduced-motion media query
- Animation: Animate 1-2 key elements per view maximum
- Accessibility: Honor prefers-reduced-motion and present the final readable state without parallax or scroll-jacking
- CTA Placement: Project Card Hover + Footer Contact
