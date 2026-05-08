---
name: Lumina Spectrum
colors:
  surface: '#15121b'
  surface-dim: '#15121b'
  surface-bright: '#3b3742'
  surface-container-lowest: '#0f0d15'
  surface-container-low: '#1d1a23'
  surface-container: '#211e27'
  surface-container-high: '#2c2832'
  surface-container-highest: '#37333d'
  on-surface: '#e7e0ed'
  on-surface-variant: '#cbc3d7'
  inverse-surface: '#e7e0ed'
  inverse-on-surface: '#322f39'
  outline: '#958ea0'
  outline-variant: '#494454'
  surface-tint: '#d0bcff'
  primary: '#d0bcff'
  on-primary: '#3c0091'
  primary-container: '#a078ff'
  on-primary-container: '#340080'
  inverse-primary: '#6d3bd7'
  secondary: '#c8c6c7'
  on-secondary: '#313031'
  secondary-container: '#4a494a'
  on-secondary-container: '#bab8b9'
  tertiary: '#c8c5cb'
  on-tertiary: '#303034'
  tertiary-container: '#919095'
  on-tertiary-container: '#29292d'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#e9ddff'
  primary-fixed-dim: '#d0bcff'
  on-primary-fixed: '#23005c'
  on-primary-fixed-variant: '#5516be'
  secondary-fixed: '#e5e2e3'
  secondary-fixed-dim: '#c8c6c7'
  on-secondary-fixed: '#1c1b1c'
  on-secondary-fixed-variant: '#474647'
  tertiary-fixed: '#e4e1e7'
  tertiary-fixed-dim: '#c8c5cb'
  on-tertiary-fixed: '#1b1b1f'
  on-tertiary-fixed-variant: '#47464b'
  background: '#15121b'
  on-background: '#e7e0ed'
  surface-variant: '#37333d'
typography:
  display-xl:
    fontFamily: Inter
    fontSize: 72px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.04em
  headline-lg:
    fontFamily: Inter
    fontSize: 48px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.3'
  body-lg:
    fontFamily: Inter
    fontSize: 18px
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
    lineHeight: '1.0'
    letterSpacing: 0.1em
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
  margin: 64px
---

## Brand & Style

The design system is centered on a "Data-Driven Ethereal" aesthetic, specifically tailored for the 'rainbowseed' portfolio. It evokes a sense of high-end precision, technical mastery, and creative fluidity. The personality is sophisticated and forward-thinking, targeting a discerning audience in tech and creative industries.

The style leverages **Glassmorphism** and **Minimalism**. It utilizes deep, infinite black voids as the canvas, upon which vibrant, neon-purple light sources act as atmospheric illuminators. Sharp typography and ultra-fine borders provide a grounding "hardware" feel to the otherwise ethereal, translucent UI elements. The user experience should feel like interacting with a futuristic command deck—highly functional yet visually mesmerizing.

## Colors

The palette is anchored by **Deep Charcoal (#0A0A0B)** for the primary background, ensuring maximum contrast for vibrant highlights. **Vibrant Purple (#8B5CF6)** serves as the primary action and atmospheric color, used in gradients, glows, and interactive states.

A secondary surface color, **#1F1F23**, is used for card backgrounds and container layering. Silver and gray accents (**#E2E8F0** and **#94A3B8**) provide neutral clarity for secondary text and subtle borders. High-contrast white is reserved for primary headlines to ensure a "sharp" typographic finish against the dark backdrop.

## Typography

This design system utilizes **Inter** for its utilitarian precision and exceptional readability in dark environments. Headlines feature tight letter-spacing and heavy weights to create a "sharp" and authoritative presence.

Display text should utilize subtle gradients or remain pure white for maximum impact. Labels and utility text are rendered in uppercase with increased tracking to mimic technical instrumentation. Body copy maintains a generous line height to ensure legibility against the dark, high-contrast backgrounds.

## Layout & Spacing

The layout follows a **Fixed Grid** model for large screens, centering the portfolio content within a maximum width of 1440px to maintain a premium, editorial feel. A 12-column system is used, with generous margins and gutters to provide breathing room.

Whitespace is treated as a premium asset, used intentionally to separate projects and highlight data visualizations. Vertical rhythm is strictly enforced using an 8px base unit, ensuring that even complex "data-driven" sections remain balanced and organized.

## Elevation & Depth

Depth is achieved through **Glassmorphism** and **Tonal Layering** rather than traditional shadows. Surfaces use semi-transparent backgrounds with a high-intensity backdrop-blur (minimum 20px) to create a sense of floating layers.

1.  **Base Layer:** Solid #0A0A0B with atmospheric purple mesh gradients.
2.  **Container Layer:** #1F1F23 at 60% opacity with a 1px "inner-glow" border (#FFFFFF10).
3.  **Active/Hover Layer:** Increased opacity and a subtle outer glow using the primary purple color to simulate light emission.
4.  **Data Elements:** Ultra-thin strokes (0.5px to 1px) used for grid lines and dividers to maintain the "technical" aesthetic.

## Shapes

The shape language combines **Rounded (Level 2)** corners with crisp, 90-degree outer layouts. Containers and buttons use a 0.5rem (8px) radius as standard, while larger cards and glass panels may scale up to 1.5rem (24px) to create a softer, more inviting interface.

Interactive elements like pill-shaped tags use a fully rounded (Level 3) approach to differentiate them from structural layout blocks.

## Components

### Buttons
Primary buttons are pill-shaped with a vibrant purple gradient and high-contrast white text. Secondary buttons use a "Ghost" style: transparent background with a 1px silver border and a subtle purple glow on hover.

### Cards
Portfolio cards utilize the glassmorphic style. They feature a 1px border that is slightly brighter at the top-left to simulate a light source. Content within cards is strictly aligned to a sub-grid.

### Inputs & Search
Input fields are dark, recessed rectangles with #0A0A0B backgrounds and #1F1F23 borders. The focus state triggers a vibrant purple glow and a 1px border transition.

### Chips & Badges
Small, technical-looking chips are used for "skills" or "tags." These feature monochromatic backgrounds with high-letter-spaced uppercase text.

### Data Visualizers
The design system includes custom sparklines, progress rings, and coordinate grids used as decorative or functional data-driven elements, rendered in thin silver strokes with purple accents.