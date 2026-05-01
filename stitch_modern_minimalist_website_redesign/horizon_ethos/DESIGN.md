---
name: Horizon Ethos
colors:
  surface: '#fcf9f8'
  surface-dim: '#dcd9d9'
  surface-bright: '#fcf9f8'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f6f3f2'
  surface-container: '#f0eded'
  surface-container-high: '#eae7e7'
  surface-container-highest: '#e5e2e1'
  on-surface: '#1c1b1b'
  on-surface-variant: '#3e494b'
  inverse-surface: '#313030'
  inverse-on-surface: '#f3f0ef'
  outline: '#6e797b'
  outline-variant: '#bdc9cb'
  surface-tint: '#006875'
  primary: '#006875'
  on-primary: '#ffffff'
  primary-container: '#78d6e6'
  on-primary-container: '#005d68'
  inverse-primary: '#76d4e4'
  secondary: '#5d5f5f'
  on-secondary: '#ffffff'
  secondary-container: '#dddddd'
  on-secondary-container: '#606161'
  tertiary: '#5f5e5e'
  on-tertiary: '#ffffff'
  tertiary-container: '#cac8c7'
  on-tertiary-container: '#545453'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#9af0ff'
  primary-fixed-dim: '#76d4e4'
  on-primary-fixed: '#001f24'
  on-primary-fixed-variant: '#004f58'
  secondary-fixed: '#e2e2e2'
  secondary-fixed-dim: '#c6c6c6'
  on-secondary-fixed: '#1a1c1c'
  on-secondary-fixed-variant: '#454747'
  tertiary-fixed: '#e5e2e1'
  tertiary-fixed-dim: '#c8c6c5'
  on-tertiary-fixed: '#1c1b1b'
  on-tertiary-fixed-variant: '#474746'
  background: '#fcf9f8'
  on-background: '#1c1b1b'
  surface-variant: '#e5e2e1'
typography:
  display:
    fontFamily: Space Grotesk
    fontSize: 64px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Space Grotesk
    fontSize: 48px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Space Grotesk
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.3'
  headline-sm:
    fontFamily: Space Grotesk
    fontSize: 24px
    fontWeight: '500'
    lineHeight: '1.4'
  body-lg:
    fontFamily: Work Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Work Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  body-sm:
    fontFamily: Work Sans
    fontSize: 14px
    fontWeight: '400'
    lineHeight: '1.5'
  label-lg:
    fontFamily: Work Sans
    fontSize: 14px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: 0.05em
  label-md:
    fontFamily: Work Sans
    fontSize: 12px
    fontWeight: '500'
    lineHeight: '1.2'
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  base: 8px
  xs: 4px
  sm: 12px
  md: 24px
  lg: 48px
  xl: 80px
  container-max: 1280px
  gutter: 24px
  margin: 32px
---

## Brand & Style

This design system is built on the principles of **Minimalism** and **Corporate Modernism**. It prioritizes clarity and high-trust interactions for a professional services environment. The aesthetic is defined by intentional whitespace, which acts as a structural element rather than empty space, guiding the user's focus toward key value propositions.

The emotional response should be one of "Technical Precision" and "Atmospheric Calm." By combining the technical edge of geometric typography with a soft, airy color palette, the UI communicates innovation backed by established reliability. Transitions are characterized by smooth, eased-out motion to reinforce a premium, high-touch service feel.

## Colors

The color strategy utilizes a high-clarity white base to ensure the "minimalist feel" requested. The primary brand color, a vibrant cyan-blue (#78D6E6), is reserved for primary actions, success states, and critical brand accents to ensure it retains its visual impact without overwhelming the user.

Neutrality is handled through a tiered system of grays. The secondary clean gray (#EBEBEB) is used for structural dividers and subtle background shifts, while the tertiary near-black (#1A1A1A) provides the necessary contrast for high-legibility typography and grounded UI elements. This palette ensures a crisp, high-contrast environment that feels both modern and authoritative.

## Typography

The typographic system uses a dual-font approach to balance technical character with institutional readability. **Space Grotesk** is utilized for headings and display text; its geometric terminals and modern apertures signal innovation and forward-thinking. 

For the body and functional text, **Work Sans** provides a highly legible, neutral foundation. It serves as a superior alternative for professional service contexts where "Open Sans" was originally considered, offering a more grounded and contemporary feel. Large-scale headings should utilize tight letter-spacing and aggressive line-heights to create a strong visual hierarchy against the surrounding white space.

## Layout & Spacing

This design system employs a **Fixed Grid** model for desktop, centered within the viewport to maintain a sense of order and institutional stability. The grid consists of 12 columns with a 24px gutter. 

Vertical rhythm is governed by an 8px base unit. To achieve the "ample white space" look, section padding should default to the `xl` (80px) variable. Elements within a card or container should use the `md` (24px) unit for internal breathing room. Use asymmetrical spacing (e.g., more space above a heading than below) to clearly group related content and establish a natural reading flow.

## Elevation & Depth

To maintain a "crisp" and "high-trust" aesthetic, this design system avoids heavy shadows in favor of **Low-contrast outlines** and **Tonal layers**. Depth is communicated through subtle shifts in background color rather than simulated physical distance.

- **Surface Tier 1:** Pure white (#FFFFFF) for the main background.
- **Surface Tier 2:** Light grey (#EBEBEB) for secondary containers or card backgrounds.
- **Borders:** 1px solid strokes using a 10% opacity version of the neutral color (#1A1A1A).
- **Interactive Depth:** On hover, elements should not "lift" with shadows but rather transition their border color or background slightly. Use a subtle backdrop blur (8px) for fixed navigation bars to create a glass-like layering effect without losing the minimalist structure.

## Shapes

The shape language is **Soft**, utilizing a 0.25rem (4px) base radius for standard components. This provides a subtle approachability while maintaining the sharp, professional lines associated with high-end service firms. 

Larger containers, such as modal windows or feature cards, may scale up to a "Large" (8px) radius, but should never reach "Pill" or "Circular" territory unless used for utility icons or tags. This geometric discipline ensures the UI feels architectural rather than organic.

## Components

### Buttons
- **Primary:** Solid Primary Blue (#78D6E6) with Neutral Black (#1A1A1A) text. 0.25rem radius.
- **Secondary:** Transparent background with a 1px solid Neutral (#1A1A1A) border.
- **Hover State:** Smooth 200ms transition. Primary buttons should darken by 5% on hover; secondary buttons should fill with a 5% opacity neutral tint.

### Cards
Cards are defined by a 1px solid border (#EBEBEB) and zero shadow. They use 24px internal padding. The "Professional" look is achieved by keeping card backgrounds white or a very light tint of the secondary gray.

### Input Fields
Inputs use a 1px solid border in the secondary gray. Upon focus, the border transitions to the Primary Blue (#78D6E6) with a very soft, 2px outer glow of the same color to highlight the active state.

### Interactive Elements
- **Chips/Tags:** Small, light gray (#EBEBEB) backgrounds with uppercase label-md typography.
- **Smooth Scrolling:** All anchor links and page transitions must utilize a `cubic-bezier(0.25, 1, 0.5, 1)` easing function to reinforce the high-end, smooth feel.
- **Checkboxes/Radios:** Square-format (0.125rem radius) for checkboxes to match the geometric theme, using the primary blue for the checked state.