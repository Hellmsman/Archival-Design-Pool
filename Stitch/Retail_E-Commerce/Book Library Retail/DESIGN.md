---
name: Literary Muse
colors:
  surface: '#f8f9fa'
  surface-dim: '#d9dadb'
  surface-bright: '#f8f9fa'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f3f4f5'
  surface-container: '#edeeef'
  surface-container-high: '#e7e8e9'
  surface-container-highest: '#e1e3e4'
  on-surface: '#191c1d'
  on-surface-variant: '#434749'
  inverse-surface: '#2e3132'
  inverse-on-surface: '#f0f1f2'
  outline: '#747879'
  outline-variant: '#c3c7c8'
  surface-tint: '#586062'
  primary: '#181f21'
  on-primary: '#ffffff'
  primary-container: '#2d3436'
  on-primary-container: '#959c9f'
  inverse-primary: '#c1c8ca'
  secondary: '#556064'
  on-secondary: '#ffffff'
  secondary-container: '#d6e2e6'
  on-secondary-container: '#596468'
  tertiary: '#410800'
  on-tertiary: '#ffffff'
  tertiary-container: '#651503'
  on-tertiary-container: '#ee7a5e'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dde4e6'
  primary-fixed-dim: '#c1c8ca'
  on-primary-fixed: '#161d1f'
  on-primary-fixed-variant: '#41484a'
  secondary-fixed: '#d9e4e9'
  secondary-fixed-dim: '#bdc8cd'
  on-secondary-fixed: '#131d21'
  on-secondary-fixed-variant: '#3e484c'
  tertiary-fixed: '#ffdad2'
  tertiary-fixed-dim: '#ffb4a3'
  on-tertiary-fixed: '#3d0700'
  on-tertiary-fixed-variant: '#812914'
  background: '#f8f9fa'
  on-background: '#191c1d'
  surface-variant: '#e1e3e4'
typography:
  display-lg:
    fontFamily: Literata
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Literata
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Literata
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  headline-sm:
    fontFamily: Literata
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
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
  label-md:
    fontFamily: Hanken Grotesk
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
  caption:
    fontFamily: Hanken Grotesk
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  base: 4px
  xs: 4px
  sm: 8px
  md: 16px
  lg: 24px
  xl: 32px
  xxl: 48px
  container-max: 1280px
  gutter: 24px
  margin-mobile: 16px
---

## Brand & Style

The design system is engineered for a premium digital library and bookstore experience, catering to bibliophiles and researchers who value intellectual depth and aesthetic clarity. The brand personality is scholarly yet contemporary—acting as a quiet, sophisticated backdrop that allows book cover art and literary content to remain the focal point.

The visual style merges **Minimalism** with **Modern Corporate** precision. It utilizes expansive white space and a structured hierarchy to evoke the feeling of a high-end physical bookstore. The emotional response is one of calm focus, reliability, and discovery. While the core interface remains neutral and disciplined, vibrant accents are strategically applied to margins and showcase borders to celebrate the diversity of the collection.

## Colors

The palette is anchored by a sophisticated neutral foundation. The background utilizes a subtle grey (`#F5F6F7`) with very soft, large-radius radial gradients to prevent visual flatness. Content containers are strictly pure white (`#FFFFFF`) to ensure maximum legibility and a "paper-like" quality.

The primary color is a deep, charcoal grey used for structural text and navigation elements. The tertiary color—a muted coral—serves as a functional accent for interactive states or call-to-actions. For book showcases, the design system employs a dynamic border strategy: the margins of book cards should pull vibrant colors from the book's cover art using a dominant color extraction algorithm, creating a colorful, personalized frame for every title.

## Typography

This design system pairs the scholarly elegance of **Literata** with the technical precision of **Hanken Grotesk**. 

**Literata** is reserved for headlines, titles, and editorial quotes. It provides the "literary" soul of the system, offering exceptional legibility for long-form reading and a high-contrast, professional appearance in display sizes.

**Hanken Grotesk** handles all functional UI, body copy, and metadata. Its contemporary, sharp grotesque character provides a necessary modern counterpoint to the serif headings, ensuring that the interface feels like a high-performance tool rather than a legacy archive.

## Layout & Spacing

The layout follows a **Fixed Grid** philosophy for desktop to maintain the disciplined structure of a library. A 12-column grid is used with a 1280px maximum container width. For mobile, the system transitions to a fluid single-column layout with 16px side margins.

Spacing follows a 4px base unit to ensure tight alignment in data-heavy views (like search results) while allowing for generous "breathable" margins in editorial views. Gutters are kept wide (24px) to emphasize the separation of distinct literary works. Use `xxl` (48px) spacing between major sections to reinforce a premium, unhurried browsing experience.

## Elevation & Depth

Hierarchy is established through **Tonal Layers** and **Low-Contrast Outlines** rather than aggressive shadows. 

The background layer is the soft grey surface. The primary interactive layer (cards, menus) consists of pure white surfaces with a 1px border of `rgba(0,0,0,0.05)`. 

To indicate elevation or "lift" on hover, use a highly diffused ambient shadow: `0px 10px 30px rgba(0,0,0,0.04)`. This creates a subtle sense of floating without breaking the clean, minimalist aesthetic. Depth is further suggested through the use of soft background gradients that give the impression of a gently lit physical space.

## Shapes

The shape language is defined as **Soft (ROUND_FOUR)**. This equates to a base radius of 4px for standard elements like buttons and input fields, and up to 12px for larger containers and book cards.

This subtle rounding strikes a balance between the "architectural" feel of sharp corners and the "friendly" feel of fully rounded shapes. It maintains a professional, editorial tone while softening the overall digital experience. Book cover images should strictly follow the `rounded-lg` (8px) token to mimic the slight natural rounding of a physical book spine and corners.

## Components

### Buttons
Primary buttons use the deep charcoal (`#2D3436`) with white text and a 4px radius. Secondary buttons should be "ghost" style with a 1px neutral border. Interactive states should involve a slight darkening of the background color.

### Book Showcase Cards
The signature component. These are white surfaces with a 1px internal border. The "margin" or "frame" of the card should feature a 4px wide color-vibrant border on the left edge (mimicking a spine) or a full-frame soft glow that extracts its hue from the book's cover art.

### Input Fields
Fields are minimalist, using a subtle light-grey background (`#F5F6F7`) and no border until focused. On focus, a 1px charcoal border appears. Labels use `label-md` in Hanken Grotesk, positioned above the field for clarity.

### Lists & Tables
Used for library archives. These use horizontal dividers only (1px, light grey). Rows should have a subtle hover state using the primary grey at 2% opacity.

### Chips & Tags
Used for genre categorization. These are small, pill-shaped elements with light grey backgrounds and `caption` typography. They should not use vibrant colors unless the tag represents a "High Priority" or "New" status.