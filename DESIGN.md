---
name: Luminous Editorial
colors:
  surface: '#fff8f6'
  surface-dim: '#e5d7d3'
  surface-bright: '#fff8f6'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#fff1ed'
  surface-container: '#faebe7'
  surface-container-high: '#f4e5e1'
  surface-container-highest: '#eedfdc'
  on-surface: '#211a18'
  on-surface-variant: '#534340'
  inverse-surface: '#372f2c'
  inverse-on-surface: '#fdeeea'
  outline: '#85736f'
  outline-variant: '#d8c2bd'
  surface-tint: '#8b4e40'
  primary: '#884b3e'
  on-primary: '#ffffff'
  primary-container: '#a56355'
  on-primary-container: '#fffbff'
  inverse-primary: '#ffb4a4'
  secondary: '#785832'
  on-secondary: '#ffffff'
  secondary-container: '#fed2a3'
  on-secondary-container: '#795933'
  tertiary: '#396451'
  on-tertiary: '#ffffff'
  tertiary-container: '#527d69'
  on-tertiary-container: '#f5fff7'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdad3'
  primary-fixed-dim: '#ffb4a4'
  on-primary-fixed: '#380d05'
  on-primary-fixed-variant: '#6e372b'
  secondary-fixed: '#ffddb9'
  secondary-fixed-dim: '#e9bf91'
  on-secondary-fixed: '#2b1700'
  on-secondary-fixed-variant: '#5e411d'
  tertiary-fixed: '#beedd4'
  tertiary-fixed-dim: '#a2d1b9'
  on-tertiary-fixed: '#002115'
  on-tertiary-fixed-variant: '#234f3d'
  background: '#fff8f6'
  on-background: '#211a18'
  surface-variant: '#eedfdc'
typography:
  display-lg:
    fontFamily: Playfair Display
    fontSize: 56px
    fontWeight: '400'
    lineHeight: 64px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 36px
    fontWeight: '400'
    lineHeight: 44px
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Playfair Display
    fontSize: 40px
    fontWeight: '500'
    lineHeight: 48px
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 28px
    fontWeight: '500'
    lineHeight: 36px
  headline-md:
    fontFamily: Playfair Display
    fontSize: 28px
    fontWeight: '400'
    lineHeight: 36px
  headline-sm:
    fontFamily: Playfair Display
    fontSize: 22px
    fontWeight: '600'
    lineHeight: 30px
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
    letterSpacing: -0.005em
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 15px
    fontWeight: '400'
    lineHeight: 24px
  body-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 20px
  label-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.06em
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 11px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.12em
  label-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 10px
    fontWeight: '700'
    lineHeight: 14px
    letterSpacing: 0.14em
rounded:
  sm: 0.5rem
  DEFAULT: 1rem
  md: 1.5rem
  lg: 2rem
  xl: 3rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-mobile: 1rem
  margin: 3.5rem
  margin-mobile: 1.25rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

This design system embodies high-end editorial beauty e-commerce, balancing haute couture poise with modern tactile warmth. Tailored for discerning beauty enthusiasts and luxury skincare shoppers, the interface communicates intimacy, prestige, and effortless radiance. 

The aesthetic is Modern Editorial Minimalism enriched with subtle tactile warmth:
- Generous, serene negative space evoking fine-print fashion periodicals and bespoke dressing rooms.
- High-contrast editorial typography paired with razor-sharp utilitarian sans-serif functional tokens.
- Restrained glassmorphic translucency evoking chilled perfume bottles and crystalline compact cases.
- Tactile, deliberate interactions: smooth micro-transitions, gentle hover scales, and pristine metallic accents that avoid garish gloss.

## Colors

The palette draws inspiration from polished rose gold, radiant champagne dust, warm porcelain, and rich espresso pigments.

### Roles and Application
- **Primary Rose Gold (`#B87364`)**: The signature statement color. Used for primary CTAs, active states, key interactive indicators, and delicate decorative elements. Tonal variants include `#C88A7B` for hover/interaction layers and `#D99B8B` for soft accents.
- **Secondary Champagne Gold (`#E4BA8C`)**: Applied to glowing highlights, rating stars, luxury tier indicators, and high-impact editorial badges. The lighter tint (`#F4E5D4`) serves as ambient shimmer backgrounds and highlight washes.
- **Tertiary Soft Sage (`#5E8A75`)**: Strictly reserved for semantic confirmation, organic/clean beauty indicators, and order success states, harmonizing subtly with warm skin tones.
- **Neutral Deep Espresso (`#1E1715`)**: Replaces cold pure black for body and display text, lending depth and organic sophistication. Secondary text relies on Muted Rose Grey (`#7E6F6C`).
- **Surfaces**: Layered upon Warm Nude Porcelain (`#FAF7F5`), Pure White (`#FFFFFF`) for elevated cards, and Pale Blush (`#F9ECE9`) for contextual section backdrops.

## Typography

Typography establishes an intentional tension between editorial romance and clinical precision.

- **Headlines (`Playfair Display`)**: Emphasize editorial beauty writing. Selected italicized words within headlines convey artistry, luxury formulations, and seasonal collections. Line heights remain tight to preserve compositional unity.
- **Body & Functional UI (`Plus Jakarta Sans`)**: Neutral, open, and supremely legible even at compact mobile specifications.
- **All-Caps Eyebrow Labels**: `label-md` and `label-sm` must be rendered in uppercase with expanded tracking (`0.12em` to `0.14em`) for category indicators, product badges, and table headers.

## Layout & Spacing

A 12-column responsive fluid grid governs desktop and tablet screens, shifting to a 4-column framework on mobile devices.

### Grid & Canvas Adaptation
- **Desktop (1200px+)**: 12 columns, `margin: 3.5rem`, `gutter: 1.5rem`. Editorial product grids utilize asymmetric column distributions (e.g., 5-column showcase alongside 7-column narrative modules).
- **Tablet (768px – 1199px)**: 8 columns, `margin: 2rem`, `gutter: 1.25rem`. Two-column catalog arrangements.
- **Mobile (< 768px)**: 4 columns, `margin: 1.25rem`, `gutter: 1rem`. Full-bleed imagery with contained interactive modules.

Rhythm is expansive; whitespace around imagery must breathe generously to reflect the high-end atelier experience.

## Elevation & Depth

Visual hierarchy eschews aggressive drop shadows in favor of ambient luminescence and frosted planar layering.

- **Subtle Ambient Shadows**: 
  - Resting cards: `0 8px 24px -4px rgba(30, 23, 21, 0.04), 0 2px 6px -2px rgba(30, 23, 21, 0.02)`.
  - Floating navigation / Sticky drawers: `0 16px 36px -6px rgba(30, 23, 21, 0.06), 0 4px 12px -2px rgba(30, 23, 21, 0.03)`.
- **Glassmorphism**: Top navigation bars and floating quick-shop drawers use `background: rgba(250, 247, 245, 0.78)` coupled with `backdrop-filter: blur(16px)` and an ultra-fine border.
- **Low-Contrast Ghost Outlines**: Visual separation uses a single 1px hairline border (`#EAD9D5` at full or 60% opacity) rather than heavy drop shadows, reinforcing porcelain-like crispness.

## Shapes

The interface embraces pill-shaped geometry (`roundedness: 3`) for action-oriented affordances, contrasting with softly architected, refined cards.

- **Buttons & Tags**: Fully rounded pill shapes (`border-radius: 9999px` / Level 3 standard) create an inviting, cosmetic compact appearance.
- **Cards & Visual Containers**: Calibrated to `1rem` (`rounded-lg`) to balance structured elegance without feeling overly circular or juvenile.
- **Swatches & Floating Triggers**: Strictly circular (`50%` radius) echoing physical pan cosmetics and shade bottles.

## Components

### Buttons
- **Primary**: Full pill silhouette. Background features a directional gradient `linear-gradient(135deg, #B87364 0%, #C88A7B 100%)`. Text is Pure White in `label-lg`, center-aligned. Hover transitions bring a subtle luminous lift (`box-shadow: 0 6px 20px rgba(184, 115, 100, 0.35)`).
- **Secondary / Outlined**: Pill silhouette, transparent background, 1px solid `#B87364` border. Text in `#B87364`. Hover state shifts surface to `#F9ECE9`.
- **Tertiary / Text**: Deep espresso text with a 1px under-line offset by 4px, transitioning to primary rose gold on hover.

### Product Cards
- Container built on `#FFFFFF` with a 1px border of `#EAD9D5` and `rounded-lg` corners.
- Media area retains a warm alabaster background (`#F4EFEB`) with aspect ratio `4:5`. On hover, the primary product image undergoes a smooth 1.03 scale transform with a crossfade to application/swatch imagery.
- Bottom actions: Floating quick-add button appearing on desktop hover, fixed as an icon trigger on mobile.

### Shade Swatch Selectors
- Clustered circular discs (24px diameter) with a 2px gap.
- Active state indicated by an external concentric ring: a 1px border spaced 2px away from the swatch color surface using `#B87364`.

### Chips & Badges
- Eyebrow badges (`BESTSELLER`, `CLEAN`, `AWARD WINNER`): Height 24px, pill-shaped, `#FAF7F5` background, 1px `#EAD9D5` border, text styled with `label-sm` in `#7E6F6C`.
- Editorial Glow Badges: Subtle gold gradient background (`linear-gradient(135deg, #F4E5D4 0%, #FAF7F5 100%)`) with text in `#DF9F43`.

### Input Fields
- Understated elegance: `#FFFFFF` fill, 48px height, rounded pill or `0.5rem` soft corners. Border is 1px `#EAD9D5`.
- Focus state: Border transitions to `#B87364` with a 3px diffused outer halo `rgba(184, 115, 100, 0.15)`. Floating placeholder labels set in `body-sm`.

### Checkboxes & Radio Buttons
- Radios: Circular, 18px diameter, border 1.5px `#EAD9D5`. Selected state fills with a solid center dot of `#B87364`.
- Checkboxes: 18px, rounded 4px, displaying a custom rose-gold checkmark on active selection.