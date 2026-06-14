---
name: Artisanal Noir
colors:
  surface: '#131313'
  surface-dim: '#131313'
  surface-bright: '#393939'
  surface-container-lowest: '#0e0e0e'
  surface-container-low: '#1c1b1b'
  surface-container: '#201f1f'
  surface-container-high: '#2a2a2a'
  surface-container-highest: '#353534'
  on-surface: '#e5e2e1'
  on-surface-variant: '#d0c5af'
  inverse-surface: '#e5e2e1'
  inverse-on-surface: '#313030'
  outline: '#99907c'
  outline-variant: '#4d4635'
  surface-tint: '#e9c349'
  primary: '#f2ca50'
  on-primary: '#3c2f00'
  primary-container: '#d4af37'
  on-primary-container: '#554300'
  inverse-primary: '#735c00'
  secondary: '#eac249'
  on-secondary: '#3d2f00'
  secondary-container: '#b08c10'
  on-secondary-container: '#352800'
  tertiary: '#d0ceca'
  on-tertiary: '#30312e'
  tertiary-container: '#b4b3af'
  on-tertiary-container: '#454542'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#ffe088'
  primary-fixed-dim: '#e9c349'
  on-primary-fixed: '#241a00'
  on-primary-fixed-variant: '#574500'
  secondary-fixed: '#ffe08b'
  secondary-fixed-dim: '#eac249'
  on-secondary-fixed: '#241a00'
  on-secondary-fixed-variant: '#584400'
  tertiary-fixed: '#e4e2dd'
  tertiary-fixed-dim: '#c8c6c2'
  on-tertiary-fixed: '#1b1c19'
  on-tertiary-fixed-variant: '#474744'
  background: '#131313'
  on-background: '#e5e2e1'
  surface-variant: '#353534'
typography:
  display-lg:
    fontFamily: ebGaramond
    fontSize: 72px
    fontWeight: '500'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: ebGaramond
    fontSize: 48px
    fontWeight: '500'
    lineHeight: '1.2'
  headline-xl:
    fontFamily: ebGaramond
    fontSize: 48px
    fontWeight: '400'
    lineHeight: '1.2'
  headline-md:
    fontFamily: ebGaramond
    fontSize: 32px
    fontWeight: '400'
    lineHeight: '1.3'
  body-lg:
    fontFamily: hankenGrotesk
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
    letterSpacing: 0.01em
  body-md:
    fontFamily: hankenGrotesk
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-caps:
    fontFamily: hankenGrotesk
    fontSize: 12px
    fontWeight: '600'
    lineHeight: '1'
    letterSpacing: 0.15em
  button:
    fontFamily: hankenGrotesk
    fontSize: 14px
    fontWeight: '600'
    lineHeight: '1'
    letterSpacing: 0.1em
spacing:
  base: 8px
  container-max: 1440px
  gutter: 32px
  margin-desktop: 64px
  margin-mobile: 20px
  section-padding: 120px
---

## Brand & Style

The design system is anchored in the concept of "Artisanal Noir"—a fusion of high-end luxury, editorial sophistication, and the raw energy of custom streetwear. It is designed for a discerning audience that values exclusivity and craftsmanship over mass production. 

The aesthetic leans heavily into **Minimalism** with a **High-Contrast** edge. It utilizes expansive whitespace (or "blackspace" in this context) to frame products as gallery pieces. The emotional response should be one of quiet confidence, prestige, and artistic mystery. Every element is intentional, avoiding decorative clutter in favor of structural elegance and metallic accents that suggest a "gold standard" of quality.

## Colors

The palette is strictly curated to evoke a premium, late-night gallery atmosphere. 

- **Primary Gold (#D4AF37):** Used for primary calls to action, active states, and critical branding elements. It represents the "cult" signature.
- **Secondary Deep Gold (#C5A028):** Reserved for hover states and gradient accents to provide depth without breaking the metallic theme.
- **Background (Deep Charcoal #121212):** A rich, near-black that provides more warmth and depth than pure hex #000000, ensuring high-end photography blends seamlessly into the UI.
- **Typography/Surface (Cream #F9F7F2):** Used for body text and secondary icons to provide a softer, more sophisticated contrast than pure white, reducing eye strain in dark mode.

## Typography

This design system employs a high-contrast typographic pairing to balance heritage with modernity.

- **Headlines:** **EB Garamond** provides a literary, authoritative, and artisanal feel. It should be used for all editorial headings and product names. For display sizes, tighter letter-spacing is encouraged to enhance the "fashion magazine" aesthetic.
- **Body & Functional Text:** **Hanken Grotesk** offers a sharp, contemporary clarity that balances the ornate nature of the serif. Its geometric precision ensures legibility for product descriptions and technical specs.
- **Labels:** Small caps with generous tracking (0.15em) are used for categories and metadata to create a rhythmic, organized feel.

## Layout & Spacing

The layout philosophy follows a **Fixed Grid** model with an emphasis on "negative space as a luxury." 

- **Grid:** A 12-column grid for desktop with 32px gutters to allow for large-scale product imagery.
- **Margins:** Wide side margins (64px+) push the content toward the center, creating a focused, intentional browsing experience.
- **Rhythm:** Vertical spacing between sections is aggressive (120px) to ensure each product or story is viewed in isolation, preventing the "cluttered marketplace" feel.
- **Mobile Adaptivity:** On mobile, margins shrink to 20px, and the grid collapses to 2 columns for product feeds to maintain the visual impact of HandDesign details.

## Elevation & Depth

Depth in this design system is created through **Low-Contrast Outlines** and **Tonal Layers** rather than traditional shadows.

1.  **Surfaces:** The primary background is #121212. Elevated cards or drawers use a slightly lighter #1A1A1A to create a subtle "lift."
2.  **Gold Accents:** 1px solid borders in #D4AF37 are used sparingly to highlight active selections or primary product cards. 
3.  **Dividers:** Hairline dividers (0.5px) in low-opacity gold or charcoal define hierarchy without breaking the flow of the page.
4.  **Glassmorphism:** Navigation bars use a high-blur (20px) backdrop filter with a 60% opaque #121212 fill, allowing product colors to bleed through subtly as the user scrolls.

## Shapes

The shape language is **Sharp (0)**. 

To maintain an architectural and high-fashion aesthetic, all buttons, input fields, and image containers utilize 90-degree angles. This severity reinforces the "bold" and "custom" nature of the brand. Rounded corners are strictly prohibited as they dilute the masculine, premium edge of the identity.

## Components

- **Buttons:** Primary buttons are solid Gold (#D4AF37) with Black text, utilizing uppercase Hanken Grotesk. Secondary buttons are "Ghost" style with a 1px Gold border and Gold text. 
- **Product Cards:** Full-bleed imagery with a sharp 1px charcoal border that turns Gold on hover. Product titles (Serif) and prices (Sans) are placed below with generous padding.
- **Inputs:** Underline-only style with Gold focus states, moving away from the "box" look to a more minimal, editorial feel.
- **Chips/Filters:** Simple text-based triggers with a Gold dot indicator for active states, avoiding heavy background fills.
- **Navigation:** Centered logo with wide-tracked Hanken Grotesk links. Hover states utilize a subtle Gold underline that animates from the center.
- **Custom Detail:** Use a "Gold Thread" divider—a thin, horizontal gold line that terminates in a small diamond shape—to separate major editorial sections.