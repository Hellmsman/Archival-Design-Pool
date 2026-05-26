---
name: Technical Precision
colors:
  surface: '#f9f9f9'
  surface-dim: '#dadada'
  surface-bright: '#f9f9f9'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f3f3f3'
  surface-container: '#eeeeee'
  surface-container-high: '#e8e8e8'
  surface-container-highest: '#e2e2e2'
  on-surface: '#1b1b1b'
  on-surface-variant: '#504532'
  inverse-surface: '#303030'
  inverse-on-surface: '#f1f1f1'
  outline: '#827660'
  outline-variant: '#d4c5ab'
  surface-tint: '#795900'
  primary: '#795900'
  on-primary: '#ffffff'
  primary-container: '#ffbf00'
  on-primary-container: '#6d5000'
  inverse-primary: '#fbbc00'
  secondary: '#016e21'
  on-secondary: '#ffffff'
  secondary-container: '#99f899'
  on-secondary-container: '#0f7427'
  tertiary: '#545e76'
  on-tertiary: '#ffffff'
  tertiary-container: '#bec9e5'
  on-tertiary-container: '#49546b'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdfa0'
  primary-fixed-dim: '#fbbc00'
  on-primary-fixed: '#261a00'
  on-primary-fixed-variant: '#5c4300'
  secondary-fixed: '#99f899'
  secondary-fixed-dim: '#7edb7f'
  on-secondary-fixed: '#002105'
  on-secondary-fixed-variant: '#005316'
  tertiary-fixed: '#d7e2ff'
  tertiary-fixed-dim: '#bbc6e2'
  on-tertiary-fixed: '#101b30'
  on-tertiary-fixed-variant: '#3c475d'
  background: '#f9f9f9'
  on-background: '#1b1b1b'
  surface-variant: '#e2e2e2'
typography:
  headline-xl:
    fontFamily: Space Grotesk
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 48px
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
  body-md:
    fontFamily: Space Grotesk
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  code-sm:
    fontFamily: Space Mono
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  label-caps:
    fontFamily: Space Grotesk
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.05em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  base: 8px
  gutter: 16px
  margin-mobile: 16px
  margin-desktop: 32px
  max-width: 1280px
---

## Brand & Style
The design system is engineered for a code learning platform that balances high-utility developer tools with an approachable educational flow. The style is **Technical Minimalism**—drawing inspiration from modern IDEs and version control interfaces. 

It prioritizes information density and structural clarity through the use of crisp black borders, a vibrant high-contrast palette, and purposeful whitespace. The aesthetic is intentionally "un-designed" to feel like a tool rather than a toy, fostering a sense of professional competence in the learner. The emotional response should be one of focus, clarity, and systematic progress.

## Colors
The palette is built on a foundation of structural black and technical blues, punctuated by high-visibility functional colors. 

- **Structural Black (#000000):** Used for borders, primary headings, and critical UI outlines to provide a "blueprint" feel.
- **Action Amber (#FFBF00):** Reserved for primary calls to action, main navigation highlights, and high-priority learning milestones.
- **Progress Green (#90EE90):** Used for secondary actions, "Run Code" triggers, and success states.
- **Technical Blues:** A range of blues (from #F8FAFC for surfaces to #1B263B for text and icons) provides the systematic backdrop that defines the "IDE" aesthetic.

## Typography
The typography utilizes **Space Grotesk** to provide a clean, geometric, and technical feel that remains highly readable at various weights. Its distinctive letterforms mirror the precision of code. 

For monospaced requirements—such as code snippets, terminal outputs, and metadata labels—**Space Mono** (or JetBrains Mono) is employed to maintain the developer-centric atmosphere. 

Headers should utilize tight letter-spacing to appear more impactful, while body text remains open for legibility during long reading sessions.

## Layout & Spacing
The design system follows a **Fixed-Fluid Hybrid** layout model. On desktop, the main content area (such as the code editor and lesson instructions) conforms to a 12-column fluid grid to maximize the use of widescreen monitors, while secondary sidebars remain fixed at 280px.

- **Spacing Rhythm:** Based on an 8px base unit. Consistent use of 8px, 16px, and 24px increments creates a predictable hierarchy.
- **Breakpoints:**
  - Mobile: < 768px (Single column, 16px margins).
  - Tablet: 768px - 1024px (2-column layout for editor/sidebar).
  - Desktop: > 1024px (12-column grid, 32px margins).

## Elevation & Depth
In alignment with its "Technical Minimalism," this design system eschews soft, ambient shadows in favor of **Tonal Layers** and **Structural Outlines**.

- **Primary Depth:** Achieved through 1px solid black borders (#000000). Elements do not "float"; they are "contained."
- **Secondary Depth:** Uses background color shifts. A surface might sit on a `#F8FAFC` background, while a sidebar or header uses `#E2E8F0` to distinguish its role.
- **Interactive States:** When an element is pressed or active, it may use a "hard shadow" (2px 2px 0px #000000) to simulate a physical push, rather than a blurred elevation.

## Shapes
The shape language is "Soft-Mechanical." We use a conservative border-radius of **4px (0.25rem)** for most components (buttons, inputs, cards). This provides enough softness to feel modern while maintaining the rigid, systematic grid required for a technical learning environment. 

Tags and "Status" indicators may use a slightly more rounded 8px radius, but the overall system avoids pill shapes to keep the aesthetic professional and structured.

## Components
- **Buttons:** 
  - *Primary:* Amber (#FFBF00) background, black text, 1px black border. 
  - *Secondary:* Light Green (#90EE90) background, black text, 1px black border.
  - *Ghost:* No background, black border, blue-grey text.
- **Input Fields:** White background, 1px black border. Labels are in `label-caps` using `Space Mono`. Focus state uses a 2px Amber border.
- **Cards:** White background, 1px black border, no shadow. Headers within cards should have a 1px bottom border to separate content cleanly.
- **Code Editor:** Surfaces use a very light blue (#F1F5F9). Line numbers and gutter elements are rendered in a muted slate blue.
- **Progress Bars:** Background is `background_accent`, with the fill using either Amber (course progress) or Green (correct answers).
- **Navigation:** Top-bar navigation uses a 1px bottom border and fixed height of 64px. Active links are underlined with a 2px Amber stroke.