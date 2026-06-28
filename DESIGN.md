---
name: Luminous Artistry
colors:
  surface: '#fff8f7'
  surface-dim: '#f2d2d5'
  surface-bright: '#fff8f7'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#fff0f1'
  surface-container: '#ffe9ea'
  surface-container-high: '#ffe1e4'
  surface-container-highest: '#fbdbde'
  on-surface: '#281719'
  on-surface-variant: '#4d4635'
  inverse-surface: '#3f2b2e'
  inverse-on-surface: '#ffeced'
  outline: '#7f7663'
  outline-variant: '#d0c5af'
  surface-tint: '#735c00'
  primary: '#735c00'
  on-primary: '#ffffff'
  primary-container: '#d4af37'
  on-primary-container: '#554300'
  inverse-primary: '#e9c349'
  secondary: '#b60059'
  on-secondary: '#ffffff'
  secondary-container: '#e30071'
  on-secondary-container: '#fffbff'
  tertiary: '#675d4e'
  on-tertiary: '#ffffff'
  tertiary-container: '#beb19f'
  on-tertiary-container: '#4d4436'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffe088'
  primary-fixed-dim: '#e9c349'
  on-primary-fixed: '#241a00'
  on-primary-fixed-variant: '#574500'
  secondary-fixed: '#ffd9e1'
  secondary-fixed-dim: '#ffb1c4'
  on-secondary-fixed: '#3f001a'
  on-secondary-fixed-variant: '#8f0044'
  tertiary-fixed: '#efe0cd'
  tertiary-fixed-dim: '#d2c4b2'
  on-tertiary-fixed: '#221a0f'
  on-tertiary-fixed-variant: '#4f4538'
  background: '#fff8f7'
  on-background: '#281719'
  surface-variant: '#fbdbde'
typography:
  headline-xl:
    fontFamily: Playfair Display
    fontSize: 64px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Playfair Display
    fontSize: 48px
    fontWeight: '600'
    lineHeight: '1.2'
  headline-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '500'
    lineHeight: '1.3'
  body-lg:
    fontFamily: DM Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: DM Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-md:
    fontFamily: DM Sans
    fontSize: 14px
    fontWeight: '500'
    lineHeight: '1.2'
    letterSpacing: 0.05em
  label-sm:
    fontFamily: DM Sans
    fontSize: 12px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: 0.1em
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
  margin-desktop: 64px
  margin-mobile: 20px
  stack-sm: 16px
  stack-md: 32px
  stack-lg: 80px
---

## Brand & Style
This design system embodies "Luminous Artistry," a brand identity rooted in luxury, curation, and editorial excellence. The aesthetic is a sophisticated blend of **Minimalism** and **Glassmorphism**, creating a high-end digital gallery feel. It targets a discerning audience that values aesthetics, craftsmanship, and exclusivity.

The emotional response should be one of calm inspiration and premium quality. By utilizing generous white space (negative space), refined typography, and a soft, warm color palette, the UI feels breathable and curated. Visual interest is maintained through subtle depth, translucent overlays, and precise alignment that mirrors high-end print magazines.

## Colors
The palette is built on a foundation of warm, inviting neutrals to create a sense of effortless luxury. 
- **Backgrounds:** Use the cream (#F5E6D3) for primary page containers and the pastel pink (#FADADD) for secondary sections or decorative cards to create a soft, rhythmic depth.
- **Primary Actions:** Use the Refined Gold (#D4AF37) for high-intent actions and primary buttons.
- **Vibrant Accents:** Use the Vibrant Fuchsia (#FF007F) sparingly for conversion-critical elements, such as "Buy Now" or "Subscribe" CTAs, ensuring they pop against the soft background.
- **Typography:** Deep charcoal or rich bronze should be used for text to maintain legibility against the cream and pink surfaces.

## Typography
The typography strategy relies on a classic serif/sans-serif pairing. **Playfair Display** provides the editorial "Artistry" of the brand, used for large headlines and evocative quotes. Its high contrast strokes evoke luxury and tradition.

**DM Sans** acts as the functional workhorse, providing a clean, geometric contrast that ensures clarity in body copy and interface labels. All labels and small captions should utilize increased letter spacing and uppercase styling to maintain a sophisticated, architectural feel.

## Layout & Spacing
The layout follows a **Fixed Grid** philosophy on desktop to preserve the curated, "framed" look of an art gallery.
- **Desktop:** 12-column grid with a 1280px max-width. Use wide margins (64px) to emphasize exclusivity.
- **Mobile:** 4-column fluid grid with 20px margins.
- **Spacing Rhythm:** Use a 8px base unit. Section vertical spacing should be aggressive (stack-lg) to allow the content to breathe and prevent the UI from feeling "crowded."

## Elevation & Depth
This design system uses **Glassmorphism** and **Tonal Layers** rather than heavy shadows to indicate hierarchy.
- **Surface Depth:** Use subtle backdrop blurs (10px - 20px) on navigation bars and floating modals to maintain a sense of lightness.
- **Shadows:** When necessary, use "Ambient Shadows"—very low opacity (4-8%) with a large blur radius, tinted with a hint of the secondary pink color to keep the shadow "warm" rather than grey.
- **Outlines:** Use 1px solid borders in a slightly darker shade of the background (e.g., a dark cream border on a cream background) to define card boundaries without introducing harsh contrast.

## Shapes
Shapes are kept **Soft (0.25rem)** to balance the traditional elegance of the serif typography with a modern digital feel. Avoid fully rounded "pill" shapes for buttons to maintain a more formal, high-fashion aesthetic. 

Cards and containers should use the default `rounded-lg` (0.5rem) for a gentle, approachable edge that still feels structured.

## Components
- **Buttons:** Primary buttons use the Gold (#D4AF37) with white or deep bronze text. Conversion-focused buttons use Fuchsia (#FF007F). All buttons use a 1px tracking increase.
- **Input Fields:** Use a minimal "underline" style or a very light cream fill with a 1px border. Focus states should transition the border color to Gold.
- **Cards:** Utilize the cream background with a very soft ambient shadow. Images within cards should have a subtle 0.5s zoom-in hover effect to emphasize the "Artistry" aspect.
- **Chips/Badges:** Use the pastel pink background with fuchsia text for high-visibility tags (e.g., "New Collection").
- **Navigation:** A sticky top-bar with a glassmorphic background blur and a fine 1px bottom border in gold.