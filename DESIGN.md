---
name: Sacred Editorial
colors:
  surface: '#fcf9f8'
  surface-dim: '#dcd9d9'
  surface-bright: '#fcf9f8'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f6f3f2'
  surface-container: '#f0eded'
  surface-container-high: '#eae7e7'
  surface-container-highest: '#e4e2e1'
  on-surface: '#1b1c1c'
  on-surface-variant: '#41484b'
  inverse-surface: '#303030'
  inverse-on-surface: '#f3f0f0'
  outline: '#71787c'
  outline-variant: '#c0c8cc'
  surface-tint: '#366476'
  primary: '#003645'
  on-primary: '#ffffff'
  primary-container: '#1b4d5e'
  on-primary-container: '#8ebdd1'
  inverse-primary: '#9fcde2'
  secondary: '#924a28'
  on-secondary: '#ffffff'
  secondary-container: '#ffa278'
  on-secondary-container: '#783615'
  tertiary: '#31312e'
  on-tertiary: '#ffffff'
  tertiary-container: '#484844'
  on-tertiary-container: '#b7b6b2'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#baeafe'
  primary-fixed-dim: '#9fcde2'
  on-primary-fixed: '#001f29'
  on-primary-fixed-variant: '#1a4c5d'
  secondary-fixed: '#ffdbcd'
  secondary-fixed-dim: '#ffb596'
  on-secondary-fixed: '#360f00'
  on-secondary-fixed-variant: '#753413'
  tertiary-fixed: '#e4e2dd'
  tertiary-fixed-dim: '#c8c6c2'
  on-tertiary-fixed: '#1b1c19'
  on-tertiary-fixed-variant: '#474744'
  background: '#fcf9f8'
  on-background: '#1b1c1c'
  surface-variant: '#e4e2e1'
typography:
  display-lg:
    fontFamily: Playfair Display
    fontSize: 64px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 40px
    fontWeight: '700'
    lineHeight: '1.2'
  headline-xl:
    fontFamily: Playfair Display
    fontSize: 48px
    fontWeight: '600'
    lineHeight: '1.2'
  headline-xl-mobile:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.3'
  headline-md:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '500'
    lineHeight: '1.4'
  body-lg:
    fontFamily: Inter
    fontSize: 20px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-caps:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: '1.5'
    letterSpacing: 0.1em
  quote:
    fontFamily: Playfair Display
    fontSize: 28px
    fontWeight: '400'
    lineHeight: '1.5'
spacing:
  unit: 8px
  container-max: 1140px
  gutter: 32px
  margin-desktop: 64px
  margin-mobile: 20px
  section-gap: 128px
---

## Brand & Style

This design system is anchored in a **European Boutique Publishing** aesthetic, blending the timeless authority of classical literature with the breathing room of modern minimalism. The brand personality is intellectual, compassionate, and spiritually grounded. It seeks to evoke a sense of "quiet restoration"—a calm, contemplative atmosphere that mirrors the book's theme of rebuilding and healing.

The visual style is strictly **Flat UI**, eschewing all gradients, shadows, and skeumorphism in favor of structural clarity and typographic excellence. Hierarchy is established through scale, weight, and the deliberate use of the terracotta accent against a muted, high-end background. The overall impression should be one of a premium, physical book transformed into a digital experience.

## Colors

The palette is derived from the tactile elements of the book cover: the deep teal-blue of the sky/canvas and the warm, earthy tones of the stones and title text.

- **Primary (#1B4D5E):** Used for navigation, headers, and secondary UI elements to maintain a deep, professional anchor.
- **Accent (#D27D56):** Reserved strictly for primary calls to action (CTAs), highlights, and critical emphasis. It represents the warmth of the "family" and "Jesus."
- **Background (#F9F7F2):** An off-white cream that softens the screen's glow, providing a more "paper-like" reading experience compared to pure white.
- **Text (#2D2D2D):** A charcoal neutral that provides high legibility without the harshness of pure black.

## Typography

The typography strategy relies on the contrast between the expressive, high-contrast **Playfair Display** and the functional, neutral **Inter**. 

Headlines should be treated with editorial care, often utilizing the `display-lg` for hero sections and `quote` for testimonials or biblical excerpts. The `label-caps` role is critical for categorization and small eyebrow headers, adding a sophisticated "metadata" feel common in high-end journals. Use generous line heights (1.6x) for body text to ensure a relaxed, comfortable reading pace.

## Layout & Spacing

This design system employs a **Fixed Grid** model on desktop to mimic the centered, structured nature of a book page. The content is contained within a 1140px central column with generous 64px external margins to prevent visual clutter.

- **Desktop (1200px+):** 12-column grid, 32px gutters.
- **Tablet (768px - 1199px):** 8-column grid, 24px gutters, 40px margins.
- **Mobile (<767px):** 4-column grid, 16px gutters, 20px margins.

**The "Breath" Principle:** Vertical spacing between major sections (`section-gap`) is intentionally large (128px) to encourage the user to pause and reflect between content blocks. Avoid packing elements tightly; let the off-white background dominate the negative space.

## Elevation & Depth

To maintain the flat, boutique aesthetic, this design system **avoids shadows entirely**. Instead, hierarchy and depth are communicated through **Tonal Layers** and **Low-Contrast Outlines**.

- **Primary Surface:** The cream background (#F9F7F2).
- **Secondary Surface:** Slight shifts in container color (e.g., a very pale version of the primary teal at 5% opacity) can be used to distinguish secondary content areas.
- **Outlines:** Use 1px solid borders in the primary color (#1B4D5E) at 15-20% opacity for cards and input fields. This creates "ghost borders" that define shape without introducing weight or 3D depth.

## Shapes

The design system uses a **Sharp (0)** roundedness level. All buttons, image containers, and input fields must have 0px corner radii. This reinforces the "architectural" and "editorial" feel, referencing the sharp corners of a hardcover book and printed layouts. 

The only exception to the sharp rule is the use of circular icons or profile images, which should be perfectly round to contrast against the rigid structural grid.

## Components

### Buttons
- **Primary:** Solid terracotta (#D27D56) background, sharp corners, white text. No shadow. On hover, darken the terracotta slightly.
- **Secondary:** Transparent background, 2px solid primary teal (#1B4D5E) border, teal text. 
- **Ghost:** Primary teal text, no border. Used for navigation and less important actions.

### Input Fields
- **Styling:** Underline-only (bottom border) or a thin 1px primary-teal outline at 20% opacity. Use Inter for input text and Playfair Display for field labels to maintain the editorial contrast.

### Cards
- **Structure:** No shadows. Use the primary-teal "ghost border" (1px, 15% opacity). Content should have generous internal padding (40px) to maintain the minimalist tone.

### Lists
- Use custom bullets: a small terracotta square or a simple horizontal line (Em-dash) in primary teal to signal an editorial bullet point.

### Quotes & Testimonials
- Large, italicized Playfair Display text. Centered. Use a small horizontal line in terracotta above the quote as a decorative flourish.

### Images
- All images should have a subtle 1px inner border in the primary color to "frame" them like a gallery piece. Use "recessed" padding (e.g., an image within a slightly larger cream container) to create an art-book look.