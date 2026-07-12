---
name: Midnight Champagne
colors:
  surface: '#f9f9ff'
  surface-dim: '#cfdaf2'
  surface-bright: '#f9f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f0f3ff'
  surface-container: '#e7eeff'
  surface-container-high: '#dee8ff'
  surface-container-highest: '#d8e3fb'
  on-surface: '#111c2d'
  on-surface-variant: '#45464d'
  inverse-surface: '#263143'
  inverse-on-surface: '#ecf1ff'
  outline: '#76777d'
  outline-variant: '#c6c6cd'
  surface-tint: '#565e74'
  primary: '#000000'
  on-primary: '#ffffff'
  primary-container: '#131b2e'
  on-primary-container: '#7c839b'
  inverse-primary: '#bec6e0'
  secondary: '#735c00'
  on-secondary: '#ffffff'
  secondary-container: '#fed65b'
  on-secondary-container: '#745c00'
  tertiary: '#000000'
  on-tertiary: '#ffffff'
  tertiary-container: '#1b1c1a'
  on-tertiary-container: '#848481'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dae2fd'
  primary-fixed-dim: '#bec6e0'
  on-primary-fixed: '#131b2e'
  on-primary-fixed-variant: '#3f465c'
  secondary-fixed: '#ffe088'
  secondary-fixed-dim: '#e9c349'
  on-secondary-fixed: '#241a00'
  on-secondary-fixed-variant: '#574500'
  tertiary-fixed: '#e3e2df'
  tertiary-fixed-dim: '#c7c7c3'
  on-tertiary-fixed: '#1b1c1a'
  on-tertiary-fixed-variant: '#464744'
  background: '#f9f9ff'
  on-background: '#111c2d'
  surface-variant: '#d8e3fb'
typography:
  display-lg:
    fontFamily: Libre Caslon Text
    fontSize: 48px
    fontWeight: '400'
    lineHeight: 56px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Libre Caslon Text
    fontSize: 36px
    fontWeight: '400'
    lineHeight: 44px
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Libre Caslon Text
    fontSize: 32px
    fontWeight: '400'
    lineHeight: 40px
  headline-sm:
    fontFamily: Hanken Grotesk
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.01em
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
    fontWeight: '700'
    lineHeight: 20px
    letterSpacing: 0.05em
  label-sm:
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
  base: 8px
  container-max: 1280px
  gutter: 24px
  margin-mobile: 20px
  margin-desktop: 40px
---

## Brand & Style

This design system embodies a "Modern Prestige" aesthetic, blending the authority of institutional finance with the warmth of a luxury editorial. The brand personality is poised, elite, and intentional, targeting a high-net-worth or professional audience that values precision and understated elegance.

The design style is **Minimalist-Luxurious**, characterized by:
- **Generous Whitespace:** Providing room for content to breathe, signaling exclusivity.
- **High-Contrast Sophistication:** Deep, saturated darks against creamy, warm surfaces to create a sense of depth and weight.
- **Refined Materiality:** Subtle use of semi-transparent layers and fine-lined borders rather than heavy shadows.
- **Professional Warmth:** Moving away from "tech-cold" blues into a more human, curated palette of champagne and sapphire.

## Colors

The palette is anchored by **Midnight Sapphire**, a deep, saturated navy that provides a foundational weight to the UI. **Champagne Gold** serves as the sole accent for primary calls to action and critical status highlights, ensuring high visual interest without overwhelming the senses.

Surfaces utilize a tiered warmth strategy: the base application background is a creamy **Alabaster**, while elevated containers use a **Pure White** to pop against the subtle warmth. Semantic colors are intentionally muted to maintain the professional tone: "Rose Dust" for errors and "Cool Slate" for inactive states, preventing jarring bright reds or flat grays from breaking the premium atmosphere.

## Typography

The typographic scale uses a sophisticated pairing of a serif display face and a sharp, contemporary grotesque. **Libre Caslon Text** provides the "Prestige" element, used for large headlines and editorial moments. Its high-contrast strokes and classical proportions evoke tradition and trust.

**Hanken Grotesk** handles all functional and body text. It is chosen for its exceptional clarity and modern geometry. To maintain the luxurious feel, labels use increased letter spacing and uppercase styling to denote hierarchy without relying on heavy colors. All body text is set in "Midnight Ink" (#020617) to ensure maximum legibility against the warm paper-like backgrounds.

## Layout & Spacing

The layout follows a **Fixed Grid** philosophy on desktop to preserve the intentional whitespace of the design narrative. On larger screens, the content is centered within a 1280px max-width container, utilizing a 12-column grid.

Spacing follows an 8px rhythmic scale. To reinforce the feeling of luxury, vertical rhythm is emphasized with generous padding (padding-y) in sections, often exceeding standard utility-first scales to create an "airy" feel. On mobile, margins tighten to 20px, and complex multi-column grids collapse into a single-column stack, prioritizing typography legibility and vertical flow.

## Elevation & Depth

Hierarchy is established through **Tonal Layering** and **Fine Outlines** rather than aggressive shadows. 

- **Level 0 (Base):** Alabaster cream background (#F9F7F2).
- **Level 1 (Cards/Panels):** Pure White surfaces with a delicate 1px border in a low-opacity version of Cool Slate.
- **Level 2 (Floating):** Low-opacity, ultra-diffused shadows (e.g., 20px blur, 4% opacity) are reserved for dropdowns and modals to suggest they are hovering just above the surface.

This approach keeps the interface feeling "flat but layered," akin to high-end stationery or architectural drafting.

## Shapes

The shape language is **Soft** but disciplined. A 0.25rem (4px) base radius is used for buttons and input fields to provide a hint of approachability without losing the professional, "sharp-suit" edge. Larger containers like cards may use the `rounded-lg` (8px) token to softly frame content, but the overall geometry remains structural and clean.

## Components

### Buttons
- **Primary:** Solid Midnight Sapphire with White text. Transitions to Champagne Gold on hover.
- **Secondary:** Transparent background with a 1px Midnight Sapphire border.
- **Tertiary:** Text-only in Midnight Sapphire with a Champagne Gold underline on hover.

### Input Fields
Inputs use a "Minimalist Ledger" style: a Pure White background, a subtle bottom-border by default, and a full border only on focus. The focus state uses a 1px Champagne Gold ring.

### Cards
Cards are Pure White with no shadow, defined by a 1px "Cool Slate" (low opacity) border. Header areas within cards should use the creamy Alabaster for a slight tonal shift.

### Chips & Tags
Chips use a "Cool Slate" background with "Midnight Ink" text for a low-profile look. Status chips for "Success" or "Action Required" utilize Champagne Gold with high-contrast text.

### Navigation
The navigation bar should be sticky and use a backdrop-blur (Glassmorphism) with an Alabaster tint to maintain visibility while scrolling through content. Links utilize the `label-md` typographic style.