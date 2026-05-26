---
name: Shift & Velocity
colors:
  surface: '#131313'
  surface-dim: '#131313'
  surface-bright: '#3a3939'
  surface-container-lowest: '#0e0e0e'
  surface-container-low: '#1c1b1b'
  surface-container: '#201f1f'
  surface-container-high: '#2a2a2a'
  surface-container-highest: '#353534'
  on-surface: '#e5e2e1'
  on-surface-variant: '#d4c0d7'
  inverse-surface: '#e5e2e1'
  inverse-on-surface: '#313030'
  outline: '#9d8ba0'
  outline-variant: '#504254'
  surface-tint: '#ebb2ff'
  primary: '#ebb2ff'
  on-primary: '#520072'
  primary-container: '#bc13fe'
  on-primary-container: '#ffffff'
  inverse-primary: '#9800d0'
  secondary: '#b9c3ff'
  on-secondary: '#00228a'
  secondary-container: '#0044f4'
  on-secondary-container: '#ccd2ff'
  tertiary: '#cdcd00'
  on-tertiary: '#323200'
  tertiary-container: '#b1b100'
  on-tertiary-container: '#424200'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#f8d8ff'
  primary-fixed-dim: '#ebb2ff'
  on-primary-fixed: '#320047'
  on-primary-fixed-variant: '#74009f'
  secondary-fixed: '#dde1ff'
  secondary-fixed-dim: '#b9c3ff'
  on-secondary-fixed: '#001257'
  on-secondary-fixed-variant: '#0034c0'
  tertiary-fixed: '#eaea00'
  tertiary-fixed-dim: '#cdcd00'
  on-tertiary-fixed: '#1d1d00'
  on-tertiary-fixed-variant: '#494900'
  background: '#131313'
  on-background: '#e5e2e1'
  surface-variant: '#353534'
typography:
  display-lg:
    fontFamily: Space Grotesk
    fontSize: 72px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.04em
  headline-lg:
    fontFamily: Space Grotesk
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Space Grotesk
    fontSize: 32px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Space Grotesk
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.3'
  body-lg:
    fontFamily: Hanken Grotesk
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Hanken Grotesk
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-bold:
    fontFamily: Space Grotesk
    fontSize: 14px
    fontWeight: '600'
    lineHeight: '1.0'
    letterSpacing: 0.1em
  label-mono:
    fontFamily: Space Grotesk
    fontSize: 12px
    fontWeight: '500'
    lineHeight: '1.0'
    letterSpacing: 0.05em
spacing:
  base: 8px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 64px
  stack-sm: 12px
  stack-md: 24px
  stack-lg: 48px
---

## Brand & Style

The design system is engineered to capture the adrenaline and precision of custom automotive culture. It targets high-performance enthusiasts, evoking an emotional response of speed, technical mastery, and "after-dark" urban energy.

The aesthetic blends **High-Contrast / Bold** visuals with **Retro-Neon** influences. It utilizes a "Cyber-Mechanical" approach: combining the raw, technical feel of a performance garage with the glossy, high-fidelity finish of a custom show car. Expect sharp geometry, aggressive linework, and vibrant light-emissions that mimic underglow lighting and dashboard instrumentation.

## Colors

The palette is anchored in a deep charcoal (`#0D0D0D`) to provide a void-like canvas for high-chroma accents. 

- **Primary (Electric Purple):** Used for branding elements, active states, and navigational highlights.
- **Secondary (Deep Blue):** Used for depth, secondary backgrounds, and glossy gradients.
- **Tertiary/Accent (Bright Yellow):** Reserved strictly for primary calls to action (CTAs), warnings, and critical technical data. It must maintain maximum contrast against the dark background.
- **Neutral/Base:** A range of cool grays starting from the base charcoal, moving up to a stark white for high-readability text and thin, structural borders.

Gradients should transition from the Secondary Blue to the Primary Purple at a 45-degree angle to simulate "anodized" metal finishes.

## Typography

This design system uses **Space Grotesk** for all display and technical labeling to leverage its geometric, futuristic apertures. It conveys a sense of engineering and modularity. 

**Hanken Grotesk** is used for body copy to ensure high legibility and a contemporary feel that balances the aggressive nature of the headlines.

**Key Rules:**
- All labels and sub-headers should be set in Uppercase with expanded letter spacing to mimic automotive badging.
- Headlines use a tight, negative letter-spacing for a "heavy-weight" presence.
- Numerical data (performance stats) should always use Space Grotesk Bold to emphasize the technical nature of the content.

## Layout & Spacing

The layout follows a **Fluid 12-Column Grid** for desktop and a **4-Column Grid** for mobile. The system prioritizes "high-density" information layouts, reminiscent of a flight data recorder or racing telemetry.

- **Asymmetry:** Occasional offset elements (e.g., text blocks shifted 1 column over) should be used to create a dynamic, moving feel.
- **Borders as Spacing:** Use 1px or 2px solid white or yellow lines to divide sections rather than relying solely on whitespace. This reinforces the "sharp" design aesthetic.
- **Safe Zones:** High-energy sections (like car galleries) should use the full width of the screen, while technical spec sheets should be contained within the fixed margins.

## Elevation & Depth

Depth in this design system is achieved through **Luminescence** and **Stacking**, rather than traditional soft shadows.

- **Neon Underglow:** Instead of black shadows, use "Glows." Elevated elements like cards or primary buttons should have a subtle outer glow using the Primary (Purple) or Secondary (Blue) color with a 15-20% opacity and a 20px blur.
- **Glassmorphism:** Use semi-transparent surface containers (Background: `rgba(255, 255, 255, 0.05)`) with a `backdrop-filter: blur(12px)`. This creates a "windshield" or "cockpit" effect.
- **Glossy Overlays:** Apply a diagonal linear gradient (white to transparent) at low opacity (5%) over cards to simulate a polished clear-coat finish.
- **Sharp Outlines:** Every container must have a defined border. Top-level containers use a 1px white border at 20% opacity. Interactive elements use 1px Yellow or Purple borders at 100% opacity.

## Shapes

This design system utilizes a **Sharp (0px)** roundedness philosophy. Every corner is a hard 90-degree angle to reflect precision, aggressive aerodynamics, and technical structural integrity. 

**Exceptions:**
- Circular icons are permitted when representing gauges or dials.
- Segmented progress bars (representing RPM or speed) should be rectangular blocks.

## Components

### Buttons
- **Primary Action:** Solid Bright Yellow background with Black text. No border. Sharp corners.
- **Secondary Action:** Transparent background with a 2px Electric Purple border. White text. On hover, the background fills with a Purple-to-Blue gradient.
- **Ghost Action:** White text, no border, becomes Yellow on hover.

### Input Fields
- Dark background (slightly lighter than the base). Bottom-only 2px border in White (inactive) or Yellow (active). 
- Label text should be Uppercase Label-Mono style sitting just above the field.

### Cards
- Background: Near-black or Glassmorphic blur.
- Border: 1px high-contrast edge.
- Accent: A 4px vertical "speed stripe" of the Primary color on the left or right edge.

### Chips & Tags
- Rectangular with 1px borders. Use Primary Purple for "Stock" and Secondary Blue for "Modified" statuses. Use Bright Yellow for "New Record" or "Featured."

### Lists & Tables
- Data-heavy. Use alternating row highlights with a very subtle purple tint. Borders between rows are mandatory.

### Gauges & Progress
- Horizontal bars should be segmented into 10-12 blocks. As the bar fills, the blocks transition from Blue to Purple to Yellow (at 90%+).