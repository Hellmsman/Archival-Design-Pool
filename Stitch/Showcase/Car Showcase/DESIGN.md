---
name: High-Performance Automotive Identity
colors:
  surface: '#131313'
  surface-dim: '#131313'
  surface-bright: '#393939'
  surface-container-lowest: '#0e0e0e'
  surface-container-low: '#1c1b1b'
  surface-container: '#20201f'
  surface-container-high: '#2a2a2a'
  surface-container-highest: '#353535'
  on-surface: '#e5e2e1'
  on-surface-variant: '#e9bcb5'
  inverse-surface: '#e5e2e1'
  inverse-on-surface: '#313030'
  outline: '#b08781'
  outline-variant: '#5f3f3a'
  surface-tint: '#ffb4a8'
  primary: '#ffb4a8'
  on-primary: '#690000'
  primary-container: '#e60000'
  on-primary-container: '#fff7f5'
  inverse-primary: '#c00000'
  secondary: '#c8c6c5'
  on-secondary: '#313030'
  secondary-container: '#4a4949'
  on-secondary-container: '#bab8b7'
  tertiary: '#fbbc00'
  on-tertiary: '#402d00'
  tertiary-container: '#926c00'
  on-tertiary-container: '#fff7f0'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#ffdad4'
  primary-fixed-dim: '#ffb4a8'
  on-primary-fixed: '#410000'
  on-primary-fixed-variant: '#930100'
  secondary-fixed: '#e5e2e1'
  secondary-fixed-dim: '#c8c6c5'
  on-secondary-fixed: '#1c1b1b'
  on-secondary-fixed-variant: '#474646'
  tertiary-fixed: '#ffdfa0'
  tertiary-fixed-dim: '#fbbc00'
  on-tertiary-fixed: '#261a00'
  on-tertiary-fixed-variant: '#5c4300'
  background: '#131313'
  on-background: '#e5e2e1'
  surface-variant: '#353535'
typography:
  display-lg:
    fontFamily: Space Grotesk
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Space Grotesk
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Space Grotesk
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  headline-md:
    fontFamily: Space Grotesk
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  body-lg:
    fontFamily: Hanken Grotesk
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Hanken Grotesk
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-caps:
    fontFamily: Space Grotesk
    fontSize: 12px
    fontWeight: '700'
    lineHeight: 16px
    letterSpacing: 0.1em
  telemetry-sm:
    fontFamily: Space Grotesk
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 20px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  base: 8px
  xs: 4px
  sm: 12px
  md: 24px
  lg: 48px
  xl: 80px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 64px
---

## Brand & Style

The design system is engineered to evoke the adrenaline of high-performance racing and the precision of elite automotive engineering. Targeting a sophisticated audience of enthusiasts and professionals, the UI prioritizes speed, clarity, and an aggressive technical edge.

The aesthetic follows a **High-Contrast / Modern** approach with a heavy lean into **Dark Mode** by default. Surfaces are treated like carbon fiber and matte finishes—deep, non-reflective, and premium. Interactions should feel instantaneous and mechanical, utilizing high-contrast borders and vibrant accents to guide the user through complex data environments. The emotional response is one of controlled power and absolute reliability.

## Colors

The palette is rooted in the high-stakes world of motorsport. 

- **Primary (Racing Red):** Used sparingly for critical CTAs, active states, and performance metrics. It represents energy and the "redline."
- **Secondary & Neutral (Matte Black & Charcoal):** Form the foundation of the interface. Use `#121212` for the base background and `#1a1a1a` for elevated cards or containers to maintain a deep, immersive environment.
- **Tertiary (Amber):** Reserved for technical alerts, secondary status indicators, and telemetry data. It provides a classic "instrument cluster" feel.
- **Functional White:** Pure white is used for primary labels and headings to ensure maximum legibility against the dark backgrounds.

## Typography

This design system utilizes a dual-font strategy to balance technical aggression with functional readability.

**Space Grotesk** is the voice of the brand. Its geometric quirks and wide apertures feel mechanical and futuristic. Use it for all headlines, buttons, and telemetry data points. All-caps styling should be applied to small labels to mimic industrial stamping.

**Hanken Grotesk** serves as the workhorse for body copy and long-form descriptions. Its contemporary, sharp execution maintains the professional tone while ensuring high legibility during rapid scanning.

For mobile, display sizes are scaled down aggressively to prevent layout overflow while maintaining the "bold" weight profile.

## Layout & Spacing

The layout is built on a **12-column fluid grid** for desktop and a **4-column grid** for mobile. The system uses an 8px base unit, reflecting the precision of a machined part.

- **Desktop:** 64px outer margins with 24px gutters. Elements should snap to the grid to maintain a structured, engineering-led appearance.
- **Mobile:** 16px outer margins. Content blocks should use tight 12px vertical spacing to maximize the information density expected in performance dashboards.
- **Rhythm:** Use generous white space (80px+) between major sections to allow the bold typography to breathe, but keep internal component spacing tight (8px-16px) to feel "packed" and efficient.

## Elevation & Depth

This design system eschews soft, ambient shadows in favor of **Tonal Layers** and **Low-Contrast Outlines**. 

Depth is achieved by stacking lighter shades of charcoal on top of the black base. 
- **Level 0 (Background):** `#121212`.
- **Level 1 (Cards/Panels):** `#1a1a1a` with a subtle 1px border of `#2a2a2a`.
- **Level 2 (Popovers/Modals):** `#222222` with a 1px border of `#333333`.

To emphasize the "High-Performance" nature, use a **primary-tinted inner glow** on active elements or buttons to simulate the illumination of an LED dashboard. Shadows, if used, should be sharp and high-opacity, mimicking direct overhead garage lighting.

## Shapes

The shape language combines the aggressive silhouette of a supercar with the ergonomics of a modern cockpit.

- **Default (0.5rem):** Standard for input fields and small cards.
- **Large (1rem):** Used for primary containers and section wrappers.
- **Extra Large (1.5rem):** Used for featured "hero" elements or main dashboard clusters.

Despite the "high roundness" requested, the geometry must remain purposeful. Avoid full pills for structural elements; instead, use the consistent 1.5rem radius to create a "technical-soft" look that feels engineered rather than "bubbly."

## Components

- **Buttons:** Primary buttons use a solid `#e60000` fill with white `Space Grotesk` caps. Secondary buttons use a heavy 2px border in charcoal with a hover state that reveals an amber glow.
- **Input Fields:** Deep charcoal backgrounds (`#1a1a1a`) with a 1px bottom border that turns Racing Red on focus. Labels are always positioned above in `label-caps`.
- **Telemetry Chips:** Small, rounded-sm containers with amber text and a subtle amber border, used for displaying real-time stats like "RPM" or "PSI."
- **Progress Bars:** High-contrast tracks. The filled portion should be a gradient from Racing Red to Amber to signify intensity or "approaching limits."
- **Cards:** Utilize the Level 1 elevation (`#1a1a1a`). Top corners may occasionally feature a "chamfered" look (angled) or a 1.5rem radius to break the monotony of the grid.
- **Status Indicators:** Use Amber for "Caution/Warning" and Racing Red for "Critical/Stop." Use a pulse animation for active critical errors.