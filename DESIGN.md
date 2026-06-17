---
name: Kinetic Precision
colors:
  surface: '#131313'
  surface-dim: '#131313'
  surface-bright: '#393939'
  surface-container-lowest: '#0e0e0e'
  surface-container-low: '#1b1b1b'
  surface-container: '#20201f'
  surface-container-high: '#2a2a2a'
  surface-container-highest: '#353535'
  on-surface: '#e5e2e1'
  on-surface-variant: '#c4c5d8'
  inverse-surface: '#e5e2e1'
  inverse-on-surface: '#313030'
  outline: '#8e90a1'
  outline-variant: '#434655'
  surface-tint: '#b8c4ff'
  primary: '#b8c4ff'
  on-primary: '#002486'
  primary-container: '#2251ea'
  on-primary-container: '#d7dcff'
  inverse-primary: '#1b4de6'
  secondary: '#f1bf4c'
  on-secondary: '#3f2e00'
  secondary-container: '#b68a16'
  on-secondary-container: '#372700'
  tertiary: '#ffb59d'
  on-tertiary: '#5d1900'
  tertiary-container: '#b13700'
  on-tertiary-container: '#ffd4c7'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#dde1ff'
  primary-fixed-dim: '#b8c4ff'
  on-primary-fixed: '#001354'
  on-primary-fixed-variant: '#0036bb'
  secondary-fixed: '#ffdf9e'
  secondary-fixed-dim: '#f1bf4c'
  on-secondary-fixed: '#261a00'
  on-secondary-fixed-variant: '#5b4300'
  tertiary-fixed: '#ffdbd0'
  tertiary-fixed-dim: '#ffb59d'
  on-tertiary-fixed: '#390c00'
  on-tertiary-fixed-variant: '#832600'
  background: '#131313'
  on-background: '#e5e2e1'
  surface-variant: '#353535'
  pitch-black: '#000000'
  pure-white: '#FFFFFF'
  surface-glass: rgba(255, 255, 255, 0.05)
  accent-glow: rgba(34, 81, 234, 0.3)
typography:
  headline-xl:
    fontFamily: Plus Jakarta Sans
    fontSize: 64px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-xl-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 40px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.3'
  body-lg:
    fontFamily: Manrope
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Manrope
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-caps:
    fontFamily: JetBrains Mono
    fontSize: 12px
    fontWeight: '500'
    lineHeight: '1.0'
    letterSpacing: 0.1em
  button:
    fontFamily: Plus Jakarta Sans
    fontSize: 15px
    fontWeight: '600'
    lineHeight: '1.0'
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  container-max: 1280px
  gutter: 24px
  margin-mobile: 16px
  stack-sm: 8px
  stack-md: 24px
  stack-lg: 64px
  section-padding: 120px
---

## Brand & Style

This design system embodies a high-tech, creative agency aesthetic characterized by dark-mode sophistication and "kinetic" energy. The brand personality is authoritative yet innovative, catering to high-tier clients in the marketing and technology sectors. 

The visual style is **Corporate Modern with a High-Contrast Digital edge**. It leverages deep obsidian backgrounds to make vibrant blue accents feel luminous. The UI should evoke a sense of professional mastery and "future-ready" thinking. Key elements include subtle dot-grid patterns for structural texture, glowing interactive states, and a focus on clean, high-impact photography. Motion should be used to reinforce precision—think swift, dampened transitions and purposeful hover-trigger reveals.

## Colors

The palette is anchored in a true dark-mode experience. **#1B1B1B** serves as the primary surface color, while **#000000** is reserved for deep backgrounds and high-contrast section breaks. 

**Vibrant Blue (#2251EA)** is the "Action" color, used for primary calls to action, progress indicators, and digital "glow" effects. **Gold (#EAB946)** is used sparingly as a secondary accent for highlighting high-value metrics, premium tiers, or specific success states. Typography primarily utilizes **#FFFFFF** for maximum legibility against the dark canvas, with secondary text pulling back to 70% opacity white.

## Typography

The typography strategy pairs the friendly yet geometric **Plus Jakarta Sans** for headlines with the highly legible, technical **Manrope** for body copy. 

- **Headlines:** Use tight letter spacing and bold weights to create impact. Headline XL should be used for hero sections with a "display" feel.
- **Body:** Manrope ensures that even dense information feels accessible and modern. 
- **Labels:** To lean into the "high-tech" agency vibe, use **JetBrains Mono** (or a similar monospace font) for utility labels, categories, and small metadata. This introduces a subtle developer/precision aesthetic.
- **Contrast:** Maintain high visual hierarchy by ensuring headlines are significantly larger and heavier than body text.

## Layout & Spacing

This design system uses a **12-column fluid grid** for desktop, transitioning to a **4-column grid** for mobile. 

- **Whitespace:** Use generous vertical padding (`section-padding`) to allow components to breathe, emphasizing the "Premium Agency" feel.
- **Consistency:** All spacing should be multiples of 8px. 
- **Dot Grid:** Subtle background patterns (1px dots spaced 24px apart) can be used to define sections or act as a background for cards to imply a structural grid.
- **Alignment:** Content should generally be left-aligned for a modern, architectural feel, though hero sections may utilize centered typography for dramatic effect.

## Elevation & Depth

Hierarchy is established through **Tonal Layers** and **Luminescence** rather than traditional heavy shadows.

1.  **Base Layer:** Pitch Black (#000000) for the main viewport.
2.  **Surface Layer:** Dark Grey (#1B1B1B) for cards and containers.
3.  **Interactive Layer:** Surfaces that are hovered or active should gain a `1px` subtle border of #FFFFFF (at 10% opacity) and a soft blue glow (`box-shadow: 0 0 20px rgba(34, 81, 234, 0.15)`).
4.  **Glassmorphism:** Use for navigation bars and modal overlays—applying a 20px backdrop-blur and a semi-transparent dark fill to maintain context of the content beneath.

## Shapes

The shape language is "Soft-Tech." While the overall layout feels structured and rigid, individual UI components use a **Soft (4px - 8px)** corner radius to feel sophisticated and modern without the aggressive look of sharp 90-degree corners.

- **Buttons/Inputs:** Use the default 0.25rem (4px) radius for a precise, "tooled" look.
- **Cards/Modals:** Use the `rounded-lg` (8px) setting.
- **Icons:** Icons should be stroke-based (2px weight) with slightly rounded terminals to match the font geometry.

## Components

- **Buttons:** Primary buttons use a solid #2251EA fill with white text. Secondary buttons use a transparent background with a 1px white border (20% opacity) that brightens to 100% on hover.
- **Input Fields:** Dark backgrounds (#000000) with a 1px border of #1B1B1B. On focus, the border transitions to #2251EA with a subtle outer glow.
- **Cards:** Cards should not have shadows. Use a subtle border (#FFFFFF, 5% opacity) to define the edge against the background.
- **Chips/Badges:** Use JetBrains Mono for text. Backgrounds should be low-opacity tints of the accent color (e.g., Blue at 10% opacity).
- **Progress Indicators:** Use thin 2px lines. Active states should use the Blue accent with a "pulse" glow animation at the leading edge.
- **Photography:** Images should be high-contrast, often with a slight desaturation or cool-toned color grade to fit the dark UI.