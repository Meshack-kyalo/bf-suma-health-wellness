# BF Suma Health and Wellness

This is a modern, responsive website designed for **BF Suma Health and Wellness**, using HTML, CSS, and vanilla JavaScript. It promotes wellness products and services with clean visuals and interactive components. Below is a breakdown of key design decisions and customizations.

---

## 🎨 Color System

The color palette centers around **teal** and **gray**, selected for both aesthetics and psychological associations:

- `--teal: #2bb3a3` – primary brand color for energy, vitality, and trust.
- `--teal-dark: #1f8377` – used on hover/scroll to show depth and action.
- `--gray-light: #f7f7f7` and `--gray: #ddd` – provide subtle background contrast.
- `--text-dark: #222` and `--text-light: #fff` – ensure clear legibility on all backgrounds.

**Rationale**: Teal is commonly associated with health and calmness, aligning with the brand's mission of wellness and balance. Gray neutrals were used to reduce visual clutter and maintain focus on content.

---

## 📱 Breakpoint Logic

This layout is built mobile-first, then enhanced for larger screens.

- **Mobile (<768px)**:
  - Stacks all sections in a single column.
  - Navigation converts to a hamburger menu with slide-out vertical links.
  - Hero and form elements are stacked vertically for better readability.

- **Tablet & Desktop (≥768px)**:
  - `.two-column` and `.info-section` become side-by-side flex layouts.
  - `.card-grid` and `.testimonial-grid` use `grid-template-columns: repeat(auto-fit, minmax(250px, 1fr))` for dynamic multi-column responsiveness.
  - Fixed sticky header is shown at all widths with scroll effect.

---

## 🎨 Creative Divergence from Mockup

Beyond applying a unique color scheme, here are key areas where this design extends or differs creatively from the original mockup:

- **Enhanced Imagery**: Images feature hover effects (scale + shadow) for visual engagement.
- **Sticky Header Scroll Behavior**: The header changes background color when scrolling to subtly signal progress.
- **Interactive Buttons**: Action buttons include hover transitions and a JavaScript-powered alert for user feedback.
- **Accordion FAQ Section**: Added for clarity and interactivity not present in the mockup.
- **Image Containers**: Additional styling (rounded corners, drop shadows) improves the visual polish.
- **Responsive Navigation**: Mobile menu toggle behavior goes beyond static mockup expectations.

---

## 🧪 Technologies Used

- HTML5 + semantic tags
- CSS3 with Flexbox, Grid, and custom variables
- Vanilla JavaScript for interactivity and effects

---

## 📃 License

This project is for educational purposes. All content, images, and code are open for review and adaptation.

