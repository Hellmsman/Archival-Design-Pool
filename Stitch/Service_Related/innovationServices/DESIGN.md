---
name: Apex Precision
colors:
  surface: '#f7f9fb'
  surface-dim: '#d8dadc'
  surface-bright: '#f7f9fb'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f2f4f6'
  surface-container: '#eceef0'
  surface-container-high: '#e6e8ea'
  surface-container-highest: '#e0e3e5'
  on-surface: '#191c1e'
  on-surface-variant: '#434656'
  inverse-surface: '#2d3133'
  inverse-on-surface: '#eff1f3'
  outline: '#737688'
  outline-variant: '#c3c5d9'
  surface-tint: '#004ced'
  primary: '#003ec7'
  on-primary: '#ffffff'
  primary-container: '#0052ff'
  on-primary-container: '#dfe3ff'
  inverse-primary: '#b7c4ff'
  secondary: '#565e74'
  on-secondary: '#ffffff'
  secondary-container: '#dae2fd'
  on-secondary-container: '#5c647a'
  tertiary: '#3f4f65'
  on-tertiary: '#ffffff'
  tertiary-container: '#57677e'
  on-tertiary-container: '#d6e6ff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dde1ff'
  primary-fixed-dim: '#b7c4ff'
  on-primary-fixed: '#001452'
  on-primary-fixed-variant: '#0038b6'
  secondary-fixed: '#dae2fd'
  secondary-fixed-dim: '#bec6e0'
  on-secondary-fixed: '#131b2e'
  on-secondary-fixed-variant: '#3f465c'
  tertiary-fixed: '#d3e4fe'
  tertiary-fixed-dim: '#b7c8e1'
  on-tertiary-fixed: '#0b1c30'
  on-tertiary-fixed-variant: '#38485d'
  background: '#f7f9fb'
  on-background: '#191c1e'
  surface-variant: '#e0e3e5'
typography:
  display-xl:
    fontFamily: Hanken Grotesk
    fontSize: 72px
    fontWeight: '800'
    lineHeight: 80px
    letterSpacing: -0.04em
  headline-lg:
    fontFamily: Hanken Grotesk
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Hanken Grotesk
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.01em
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-caps:
    fontFamily: JetBrains Mono
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.1em
  headline-lg-mobile:
    fontFamily: Hanken Grotesk
    fontSize: 36px
    fontWeight: '700'
    lineHeight: 44px
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  container-max: 1280px
  gutter: 32px
  margin-desktop: 64px
  section-gap: 128px
  stack-sm: 8px
  stack-md: 16px
  stack-lg: 24px
---

## Brand & Style

The brand personality is authoritative yet innovative, catering to a professional audience that values technical excellence and reliability. The visual style follows a **Modern Corporate** aesthetic with a heavy emphasis on **Minimalism** to ensure the product remains the focal point. 

The UI should evoke a sense of high-fidelity precision through razor-sharp alignment, generous whitespace, and a limited but high-impact color palette. The goal is to create an atmosphere of "quiet confidence"—where the quality of the product is reflected in the clarity of its digital presentation.

## Colors

The palette is anchored by a deep **Slate Charcoal** (#0F172A) for primary text and structural elements, providing a sophisticated weight to the layout. The primary action color is an **Electric Blue** (#0052FF), chosen for its high energy and professional association.

A secondary background token, `background_history`, is specifically defined for narrative sections. This dark-mode-in-light-mode container uses the charcoal base to create a high-contrast focal point that breaks up long scrolls. All secondary accents use a muted slate to ensure hierarchy isn't compromised by unnecessary visual noise.

## Typography

This design system utilizes a trio of typefaces to establish a clear hierarchy. **Hanken Grotesk** serves as the display face, providing a sharp, contemporary edge for all headlines. **Inter** is used for body copy due to its exceptional legibility and systematic rhythm at various scales. 

For technical metadata, labels, and small UI hints, **JetBrains Mono** is introduced to reinforce the "precision" and "tech-forward" narrative of the product. Use `display-xl` sparingly for hero sections, and ensure all uppercase labels use the monospaced font to differentiate data from prose.

## Layout & Spacing

The layout follows a **Fixed Grid** model for desktop, centered on a 1280px max-width container with a 12-column structure. Spacing is governed by a strict 8px base unit. 

Large-scale vertical separation between major content blocks (Section Gaps) uses a generous 128px to maintain the spacious, premium feel. For product grids, use a 32px gutter to provide breathing room between images and specifications. On mobile, the grid collapses to a single column with 24px side margins.

## Elevation & Depth

To maintain a "High-Fidelity" aesthetic, depth is achieved through **Tonal Layers** and **Low-Contrast Outlines** rather than heavy shadows. 

1. **Surface Level 0 (Canvas):** Pure white (#FFFFFF).
2. **Surface Level 1 (Cards/Inputs):** Subtle border (1px solid #E2E8F0) with no shadow.
3. **Floating Level (Modals/Nav):** A very soft, highly diffused ambient shadow (0px 20px 40px rgba(15, 23, 42, 0.05)) to suggest separation from the canvas without looking "heavy."

Interactive elements like product cards should use a 2px Electric Blue border on hover to signify focus rather than a lift effect.

## Shapes

The design system utilizes a **Soft** shape language. This subtle rounding (0.25rem - 0.75rem) balances the aggressive boldness of the typography, making the professional interface feel approachable and polished. 

Buttons and input fields should strictly adhere to `rounded` (4px), while larger structural components like product images and feature cards can scale up to `rounded-lg` (8px). This creates a nested harmony where larger elements have slightly more radius than the smaller elements contained within them.

## Components

### Navigation & Footer
The header is a "sticky" component using a frosted glass effect (Backdrop Blur: 12px) over a white background at 80% opacity. The footer is substantial, utilizing the `secondary_color_hex` background with `body-md` text in white for high contrast.

### Product Grid
Each product card features a square aspect ratio container for imagery. Pricing should be displayed in `headline-md`, while technical specs use `label-caps`. 

### History Section
A full-width container using `background_history`. Typography inside this section should invert to white. Use a centered `headline-lg` with a limited line length for the narrative copy to ensure readability against the dark background.

### Buttons
- **Primary:** Solid `primary_color_hex` with white text. No gradient.
- **Secondary:** Ghost style with a 1px `secondary_color_hex` border.
- **Micro-interaction:** On hover, primary buttons shift 10% darker; secondary buttons gain a subtle `neutral_color_hex` fill.

### Input Fields
Inputs should be minimalist: a bottom-border only or a light 4-sided stroke. Focus states are marked by a transition to the `primary_color_hex` border and a 2px focus ring.