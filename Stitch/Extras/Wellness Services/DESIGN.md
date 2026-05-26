---
name: Serene Flow
colors:
  surface: '#f9f9f9'
  surface-dim: '#dadada'
  surface-bright: '#f9f9f9'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f3f3f3'
  surface-container: '#eeeeee'
  surface-container-high: '#e8e8e8'
  surface-container-highest: '#e2e2e2'
  on-surface: '#1a1c1c'
  on-surface-variant: '#504444'
  inverse-surface: '#2f3131'
  inverse-on-surface: '#f0f1f1'
  outline: '#827473'
  outline-variant: '#d4c3c2'
  surface-tint: '#785655'
  primary: '#785655'
  on-primary: '#ffffff'
  primary-container: '#f7cac9'
  on-primary-container: '#755353'
  inverse-primary: '#e8bcbb'
  secondary: '#495f84'
  on-secondary: '#ffffff'
  secondary-container: '#bcd2fd'
  on-secondary-container: '#445a7f'
  tertiary: '#ad2860'
  on-tertiary: '#ffffff'
  tertiary-container: '#ffc6d4'
  on-tertiary-container: '#aa255d'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdad9'
  primary-fixed-dim: '#e8bcbb'
  on-primary-fixed: '#2d1415'
  on-primary-fixed-variant: '#5e3f3e'
  secondary-fixed: '#d6e3ff'
  secondary-fixed-dim: '#b1c7f2'
  on-secondary-fixed: '#001b3d'
  on-secondary-fixed-variant: '#31476b'
  tertiary-fixed: '#ffd9e2'
  tertiary-fixed-dim: '#ffb1c7'
  on-tertiary-fixed: '#3f001c'
  on-tertiary-fixed-variant: '#8d0648'
  background: '#f9f9f9'
  on-background: '#1a1c1c'
  surface-variant: '#e2e2e2'
typography:
  display-lg:
    fontFamily: Libre Caslon Text
    fontSize: 48px
    fontWeight: '400'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Libre Caslon Text
    fontSize: 32px
    fontWeight: '400'
    lineHeight: 40px
  headline-lg-mobile:
    fontFamily: Libre Caslon Text
    fontSize: 28px
    fontWeight: '400'
    lineHeight: 36px
  headline-md:
    fontFamily: Libre Caslon Text
    fontSize: 24px
    fontWeight: '400'
    lineHeight: 32px
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.01em
  label-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  unit: 8px
  container-max: 1280px
  gutter: 24px
  margin-desktop: 64px
  margin-mobile: 20px
  section-gap: 80px
---

## Brand & Style
The design system is built for a holistic wellness platform that bridges the gap between traditional medical precision and the organic flow of yoga practice. The brand personality is serene, nurturing, and authoritative, designed to evoke a sense of calm reliability.

The visual style follows a **Modern Minimalist** approach with **Organic Geometric** influences. It utilizes generous whitespace to reduce cognitive load—essential for users seeking health information or mindfulness—and employs soft, layered surfaces to create a gentle, inviting environment. The aesthetic balances the structured "precision" of healthcare with the "fluidity" of movement.

## Colors
The palette is rooted in a "Natural Dawn" concept, utilizing soft pastels to soothe the user's nervous system.

- **Primary (Rose Quartz):** Used for main surfaces, soft backgrounds, and key brand elements. It represents warmth and human touch.
- **Secondary (Serenity Blue):** Used for depth, secondary actions, and medical-related data visualizations. It provides a cooling, professional contrast to the pinks.
- **Tertiary (Vibrant Magenta):** Reserved for high-priority calls to action, active states, and critical health alerts. Use sparingly to maintain the serene atmosphere.
- **Neutral:** A range of crisp whites and very soft greys ensure legibility and a sense of "clinical cleanliness" without feeling cold.

## Typography
This design system employs a sophisticated pairing to balance wisdom and modern utility.

- **Headlines:** *Libre Caslon Text* brings an editorial, high-end feel that suggests heritage and medical authority. Its graceful serifs should be used for all page titles and section headers.
- **Body & Interface:** *Plus Jakarta Sans* provides a friendly, soft-geometric feel that is highly legible. Its rounded terminals echo the "softness" of the brand while maintaining a professional, systematic structure.
- **Scale:** Maintain high contrast between heading sizes and body text to guide the eye through long-form medical articles or yoga instructions.

## Layout & Spacing
The layout follows a **Fluid Grid** with generous padding to reinforce the "natural flow" narrative.

- **Rhythm:** An 8px base unit governs all spacing.
- **Structure:** Use a 12-column grid for desktop and a 4-column grid for mobile.
- **Whitespace:** Emphasize vertical breathing room. Section gaps should be substantial (80px+) to ensure that medical information or exercise steps do not feel cramped.
- **Alignment:** While the grid is structured, allow for "organic" offsets—such as images overlapping container edges slightly—to break the rigidity of a standard medical portal.

## Elevation & Depth
This design system avoids heavy shadows, instead using **Tonal Layers** and **Soft Ambient Occulsion**.

- **Surfaces:** Depth is primarily communicated through subtle shifts in background color (e.g., a `surface_rose` card on a `background_white` page).
- **Shadows:** When necessary for interactivity (like floating action buttons or active cards), use very large blur radii (30px+) with low-opacity tints of the `secondary_color` (Blue) to simulate a soft glow rather than a harsh drop shadow.
- **Glassmorphism:** Use subtle backdrop blurs (10px - 20px) on sticky navigation bars to maintain a sense of environmental continuity as the user scrolls.

## Shapes
The shape language is defined by **Soft Continuity**. 

- **Corners:** Standard elements like cards and input fields use a 0.5rem (8px) radius. Larger containers or feature sections should use the `rounded-xl` (1.5rem / 24px) setting to feel more organic.
- **Organic Accents:** Incorporate non-functional decorative blobs or "pebble" shapes in the background using the primary and secondary colors at 10-20% opacity to reinforce the yoga/natural theme.

## Components
- **Buttons:** Primary buttons should be pill-shaped or highly rounded using the `tertiary_color` (Vibrant Magenta) for clear conversion. Secondary buttons use a ghost style with a `secondary_color` border.
- **Cards:** Cards should have no border, utilizing a subtle fill (`surface_rose` or `surface_sky`) to define their boundaries.
- **Input Fields:** Use a soft background fill instead of a dark border. Focus states should transition the background color and add a thin `secondary_color` stroke.
- **Chips/Labels:** Use for yoga categories (e.g., "Vinyasa", "Hatha") or medical tags. These should always be pill-shaped with high-contrast text.
- **Progress Indicators:** Use fluid, rounded lines for medical treatment trackers or yoga session progress, avoiding sharp edges.
- **Interactive Lists:** Items should have generous internal padding (16px-24px) to ensure they are easy to tap and read, maintaining the "serene" spatial requirement.