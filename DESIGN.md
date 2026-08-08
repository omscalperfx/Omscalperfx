---
name: Aureum Flux
colors:
  surface: '#16130b'
  surface-dim: '#16130b'
  surface-bright: '#3d392f'
  surface-container-lowest: '#110e07'
  surface-container-low: '#1f1b13'
  surface-container: '#231f17'
  surface-container-high: '#2d2a21'
  surface-container-highest: '#38342b'
  on-surface: '#eae1d4'
  on-surface-variant: '#d0c5af'
  inverse-surface: '#eae1d4'
  inverse-on-surface: '#343027'
  outline: '#99907c'
  outline-variant: '#4d4635'
  surface-tint: '#e9c349'
  primary: '#f2ca50'
  on-primary: '#3c2f00'
  primary-container: '#d4af37'
  on-primary-container: '#554300'
  inverse-primary: '#735c00'
  secondary: '#b7c8dd'
  on-secondary: '#223242'
  secondary-container: '#3b4a5c'
  on-secondary-container: '#a9bacf'
  tertiary: '#cbced7'
  on-tertiary: '#2d3137'
  tertiary-container: '#b0b3bb'
  on-tertiary-container: '#41454c'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#ffe088'
  primary-fixed-dim: '#e9c349'
  on-primary-fixed: '#241a00'
  on-primary-fixed-variant: '#574500'
  secondary-fixed: '#d3e4fa'
  secondary-fixed-dim: '#b7c8dd'
  on-secondary-fixed: '#0c1d2c'
  on-secondary-fixed-variant: '#384859'
  tertiary-fixed: '#dfe2eb'
  tertiary-fixed-dim: '#c3c6cf'
  on-tertiary-fixed: '#181c22'
  on-tertiary-fixed-variant: '#43474e'
  background: '#16130b'
  on-background: '#eae1d4'
  surface-variant: '#38342b'
typography:
  headline-xl:
    fontFamily: Montserrat
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Montserrat
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Montserrat
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 34px
  headline-md:
    fontFamily: Montserrat
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
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
  label-sm:
    fontFamily: Geist
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.05em
  data-num:
    fontFamily: Geist
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 24px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  unit: 4px
  gutter: 24px
  margin-desktop: 64px
  margin-mobile: 20px
  container-max: 1440px
---

## Brand & Style

The design system is engineered to evoke a sense of "Institutional Prestige meets Future-Tech." It targets high-stakes forex traders who value precision, community, and enlightenment. The brand personality is authoritative yet spiritually grounded—a blend of data-driven scalping and disciplined mastery.

The visual style is **Glassmorphic & Kinetic**. It utilizes high-end translucent layers, vibrant gold accents, and deep obsidian depths to create a "command center" atmosphere. Motion is a core pillar: interactions should feel like fluid mercury, with smooth transitions, subtle glowing pulses, and a high-refresh-rate aesthetic that reflects the fast-paced nature of forex markets.

## Colors

The palette is derived directly from the logo's metallic and midnight hues. 

- **Primary (Lustrous Gold):** Used for calls to action, active states, and critical data points. It represents wealth and success.
- **Secondary (Obsidian Blue):** The primary surface color for cards and containers, providing a rich, professional backdrop.
- **Neutral Base (True Black):** The canvas. By using deep blacks (#05070A), the gold accents and glass effects achieve maximum luminance.
- **Functional Colors:** Success (Bullish) is represented by an Emerald Green (#00C805), and Danger (Bearish) by a Crimson Red (#FF3B30), both tuned to pop against the dark theme without clashing with the gold primary.

## Typography

Typography balances the geometric strength of **Montserrat** for headlines with the technical precision of **Inter** for readability.

- **Headlines:** Set in Montserrat with tight tracking to give a "locked-in," professional feel.
- **Technical Data:** The **Geist** font is used for labels and trading figures. Its monospaced-adjacent character ensures that price numbers don't jump horizontally as they update in real-time.
- **Hierarchy:** Use heavy weights (700+) for primary headings to anchor the page. Data labels should be small, all-caps, and slightly tracked out to evoke a terminal interface.

## Layout & Spacing

This design system uses a **Fluid Grid** model with high density for data-heavy views and generous whitespace for marketing sections.

- **The 8px Rhythm:** All spacing (padding, margins) must be increments of 4px, with 8px and 16px being the standard increments for component internals.
- **Grid:** A 12-column grid for desktop with 24px gutters. Elements should "float" within the obsidian background, using glassmorphic containers to define groups rather than hard lines.
- **Breakpoints:** 
    - Desktop: 1200px+ (12 columns)
    - Tablet: 768px - 1199px (8 columns)
    - Mobile: <767px (4 columns, margins reduced to 20px)

## Elevation & Depth

Depth is created through light and transparency rather than traditional drop shadows.

- **Glassmorphism:** Primary containers use a 60% opacity fill of `secondary_color_hex` with a `backdrop-filter: blur(20px)`. 
- **Inner Glows:** Instead of outer shadows, use a 1px inner border (stroke) with a linear gradient (Gold to Transparent) at a 45-degree angle to simulate a metallic edge.
- **Z-Axis Hierarchy:**
    - Level 0: Pure black base.
    - Level 1: Subtle textured glass (Cards).
    - Level 2: Interactive elements (Buttons, Hovers) with a subtle golden `box-shadow: 0 0 15px rgba(212, 175, 55, 0.3)`.

## Shapes

The shape language is "Sophisticated Geometric." We avoid sharp, aggressive corners to maintain the "smooth" and "enlightened" brand feel, opting instead for refined radii.

- **Standard Radius:** 0.5rem (8px) for cards and inputs.
- **Pill Shapes:** Used exclusively for tags, status indicators (e.g., "Active Trade"), and the primary floating navigation bar.
- **Decorative Elements:** Circular motifs from the logo should be used as background "orbs" with heavy Gaussian blurs (150px+) to create localized pools of golden light.

## Components

### Primary Buttons
High-contrast gold background with dark navy text. Use a CSS `linear-gradient(135deg, #D4AF37 0%, #FFD700 100%)`. On hover, increase the outer glow and slightly scale the button (1.02x).

### Inputs & Form Fields
Background: `rgba(26, 42, 58, 0.5)` with a 1px border. Focus state should trigger a gold border glow. Labels sit above the field in `label-sm` typography.

### Trading Cards
The cornerstone component. Features a glassmorphic background, a top-aligned metallic "shine" stroke, and integrated real-time sparklines. 

### Chips & Badges
Small, pill-shaped elements. For "Bullish" signals, use a dark green background with emerald text; for "Bearish," a dark red background with crimson text.

### Navigation
A top-fixed, floating glass bar. Active links are indicated by a subtle gold dot underneath the text rather than a underline.