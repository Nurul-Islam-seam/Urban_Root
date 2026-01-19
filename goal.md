# Project Goals & Requirements

## 1. Initial Setup
- [ ] Create `index.html` and `style.css` at workspace root
- [ ] Link CSS to HTML
- [ ] Place all images/logos from `assets/UI` where needed
- [ ] Note layered/stacked assets for hero circle and background waves
- [ ] Set CSS variables:
  - Brand gradients
  - Text colors
  - Background colors
  - Spacing scale
  - Font stacks

---

## 2. Global Layout & Base Styles

### Layout
- [ ] Dark gradient page background
- [ ] Max-width container, centered with padding

### Typography
- [ ] Basic scale: H1–H4, body, small
- [ ] Set font stack + line-heights

### Buttons
- [ ] Primary: gradient
- [ ] Secondary: outline

### Utilities
- [ ] Flex helpers (row/col, align, justify)
- [ ] Simple grid helper
- [ ] Gap/spacing helpers

### Breakpoints
- [ ] Small: ≤576px
- [ ] Large: ≥992px

---

## 3. Navbar (Desktop First)

### Desktop Layout
- [ ] Left: Logo
- [ ] Center: Navigation links
- [ ] Right: Gradient CTA button
- [ ] Add hover/active states

### Mobile Layout
- [ ] Hide navigation links
- [ ] Show hamburger menu icon
- [ ] Implement slide-down/overlay menu

---

## 4. Hero/Banner Section

### Background & Overlay
- [ ] Use provided background image
- [ ] Add overlay for text legibility

### Hero Elements
- [ ] Center podcast hero-circle.png image
- [ ] Layer "NEW" badge on top-right of circle (absolute positioning) Green & Black text
- [ ] Add title and subtitle (centered) <!-- Techwave , your daily dosee....-->
- [ ] Add two CTAs (gradient + outline) <!-- listen on spotify with icon spotify.png , subscribe(Green) -->
- [ ] Align waveform assets behind/around circle <!-- microphone.png over the hero-circle -->


---

## 5. About + Stats Section

### About
- [ ] Centered section heading
- [ ] Centered paragraph text

### Stats Grid
<!-- 150K+
200+
4.9★
50+ with subtitle -->
- [ ] 4 items in one row (large screens)
- [ ] 2x2 grid (small screens)
- [ ] Add subtle card/background tint 
- [ ] Add icons if available



---

## 6. Why Choose Section

<!-- Why Choose TechWave
Premium Audio Quality - headphone.png
Mobile Friendly    - device.png
Global Community    - location.png
Exclusive Interviews - gradiant thunder icon online
Rich Resource - resource.png -->

### Feature Cards
- [ ] Create 5 feature cards
- [ ] Each card: icon + title + description

### Layout
- [ ] Desktop: grid (2-2-1 or 3-2 based on design)
- [ ] Mobile: single column

### Interactions
- [ ] Add card hover animation (light lift/glow effect)

---

## 7. Featured Episodes Section

### Episode Cards
- [ ] Create 3 episode cards
- [ ] Each card includes:
  - Title
  - Description
  - Duration
  - Embedded YouTube link
  - Thumbnail + play overlay (if assets exist)

### Layout
- [ ] Desktop: 3-column
- [ ] Medium: 2-column
- [ ] Small: single column
- [ ] Consistent padding, border-radius, and shadow

---

## 8. Host Section (Challenge)

### Desktop Layout
- [ ] Two-column layout
- [ ] Left: Host image
- [ ] Right: Bio text + social icons

### Mobile Layout
- [ ] Stack vertically
- [ ] Image on top
- [ ] Text and social icons below

### Content
- [ ] Host bio text
- [ ] Social icons row

---

## 9. Footer

### Elements
- [ ] Centered brand/logo
- [ ] Platform icons/links row
- [ ] Divider line
- [ ] Copyright text

### Responsiveness
- [ ] Ensure readable contrast on dark background
- [ ] Stack vertically on mobile

---

## 10. Responsiveness & Polish

### Breakpoint Testing
- [ ] Verify spacing at ≤576px
- [ ] Verify spacing at >992px
- [ ] Test optional mid-breakpoint (576–992px)

### Typography Adjustments
- [ ] Tweak font sizes for mobile
- [ ] Adjust line-heights for readability
- [ ] Optimize padding for mobile

### Touch-Friendly Elements
- [ ] Ensure CTA buttons are thumb-friendly on mobile

---

## 11. Assets & Layering

### Positioning
- [ ] Layer hero circle + badge + waveform using relative/absolute positioning
- [ ] Use `background-size` and `background-position` to match reference

### Optimization
- [ ] Optimize image sizes
- [ ] Compress images where needed

---

## 12. Accessibility & Semantics

### HTML Structure
- [ ] Use semantic HTML5 elements:
  - `<header>`
  - `<main>`
  - `<section>`
  - `<footer>`

### Accessibility
- [ ] Add alt text for all images
- [ ] Ensure focus states for buttons/links
- [ ] Preserve color contrast (WCAG standards)

---

## 13. Final Checks

### Quality Assurance
- [ ] Cross-browser testing
- [ ] Remove any lorem ipsum text
- [ ] Validate HTML/CSS

### Deployment
- [ ] Deploy to GitHub Pages
- [ ] Verify live responsiveness
- [ ] Test all links and interactions

---

## Notes
- Follow mobile-first or desktop-first approach consistently
- Keep design system consistent (colors, spacing, typography)
- Document any custom CSS variables or utility classes