---
name: The Divine Cacao Narrative
colors:
  surface: '#faf9f6'
  surface-dim: '#dbdad7'
  surface-bright: '#faf9f6'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f4f3f1'
  surface-container: '#efeeeb'
  surface-container-high: '#e9e8e5'
  surface-container-highest: '#e3e2e0'
  on-surface: '#1a1c1a'
  on-surface-variant: '#514441'
  inverse-surface: '#2f312f'
  inverse-on-surface: '#f2f1ee'
  outline: '#837471'
  outline-variant: '#d5c2bf'
  surface-tint: '#7f534b'
  primary: '#230804'
  on-primary: '#ffffff'
  primary-container: '#3d1c16'
  on-primary-container: '#b28077'
  inverse-primary: '#f2b9af'
  secondary: '#615e53'
  on-secondary: '#ffffff'
  secondary-container: '#e4dfd1'
  on-secondary-container: '#656357'
  tertiary: '#001500'
  on-tertiary: '#ffffff'
  tertiary-container: '#112b0b'
  on-tertiary-container: '#76956b'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdad4'
  primary-fixed-dim: '#f2b9af'
  on-primary-fixed: '#31120d'
  on-primary-fixed-variant: '#643c35'
  secondary-fixed: '#e7e2d4'
  secondary-fixed-dim: '#cbc6b8'
  on-secondary-fixed: '#1d1c13'
  on-secondary-fixed-variant: '#49473c'
  tertiary-fixed: '#caecbc'
  tertiary-fixed-dim: '#afd0a1'
  on-tertiary-fixed: '#062104'
  on-tertiary-fixed-variant: '#324e2a'
  background: '#faf9f6'
  on-background: '#1a1c1a'
  surface-variant: '#e3e2e0'
typography:
  display-lg:
    fontFamily: EB Garamond
    fontSize: 64px
    fontWeight: '600'
    lineHeight: 72px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: EB Garamond
    fontSize: 40px
    fontWeight: '600'
    lineHeight: 48px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: EB Garamond
    fontSize: 32px
    fontWeight: '500'
    lineHeight: 40px
  headline-sm:
    fontFamily: EB Garamond
    fontSize: 24px
    fontWeight: '500'
    lineHeight: 32px
  body-lg:
    fontFamily: Manrope
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Manrope
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-caps:
    fontFamily: Manrope
    fontSize: 12px
    fontWeight: '700'
    lineHeight: 16px
    letterSpacing: 0.1em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  unit: 8px
  container-max: 1200px
  gutter: 24px
  margin-mobile: 20px
  margin-desktop: 64px
---

## Brand & Style

This design system is built to evoke the high-end, cultural heritage of cacao—shifting from a mere commodity to the "Nectar of the Gods." The aesthetic is **Sophisticated Minimalism** with a **Tactile** edge. It treats digital surfaces as artisanal stationery, emphasizing the texture of tradition through expansive whitespace and rich, organic tones.

The target audience consists of connoisseurs and cultural enthusiasts who value authenticity and luxury. The UI should feel like a personal invitation: warm, exclusive, and deeply rooted in the earth. To achieve this, the system avoids technical coldness in favor of a "humanist-luxe" feel, utilizing subtle textures that suggest handmade paper and the raw matte finish of dark chocolate.

## Colors

The palette is derived from the lifecycle of cacao and the provided brand mark.
- **Deep Cacao (#3D1C16):** Used for primary typography and brand-defining surfaces. It provides the "weight" of luxury and connects directly to the logo's pigment.
- **Creamy Beige (#F5F0E1):** The primary surface color, acting as a softer, more premium alternative to pure white. It mimics high-grade cardstock.
- **Organic Green (#4A6741):** An accent color representing the living cacao plant. It is used sparingly for call-to-actions, success states, and decorative flourishes to keep the design grounded in nature.
- **Paper Neutral (#FAF9F6):** A very light tint used for subtle section differentiation without losing the warm, invitation-like atmosphere.

## Typography

The typographic hierarchy balances the "Divine" with the "Modern."
- **Headlines:** Use **EB Garamond**. Its classical proportions and elegant serifs evoke history, academia, and premium publishing. Large display sizes should use tighter letter spacing to feel more curated.
- **Body & Functional Text:** Use **Manrope**. Its clean, geometric sans-serif structure ensures high legibility and provides a professional contrast to the traditional serif headings.
- **Labels:** Small labels and overlines should use **Manrope Bold** with increased letter spacing to create a sense of hierarchy that feels like an exhibition catalog.

## Layout & Spacing

The layout follows a **Fixed Grid** philosophy to maintain the structured feel of a physical invitation or a luxury editorial spread.
- **Grid:** A 12-column grid for desktop with generous margins (64px) to ensure content feels "framed."
- **Rhythm:** Spacing is strictly based on an 8px scale. High-priority sections should utilize "Negative Space" as a design element—don't be afraid of empty Creamy Beige areas to focus the eye on high-quality cacao imagery.
- **Mobile Adaption:** For mobile, the grid collapses to 4 columns. Headline sizes scale significantly to maintain a "poster" feel even on small screens.

## Elevation & Depth

To avoid a "flat" corporate look, the design system utilizes **Tonal Layers** and **Soft Ambient Shadows**. 
- **Depth Hierarchy:** Instead of traditional dark shadows, use subtle color-tinted shadows (using the Deep Cacao hex at 5-10% opacity) to make elements feel like they are resting on paper.
- **Layering:** Use Creamy Beige for the base, and Paper Neutral for raised containers.
- **Dividers:** Use hairline borders (0.5px) in a slightly darker beige or the primary brown at 15% opacity to separate content without creating visual noise.

## Shapes

The shape language is **Soft (Level 1)**. 
- **Corners:** Standard UI elements like buttons and input fields use a 0.25rem (4px) radius. This provides a subtle "finished" edge that feels more sophisticated and intentional than sharp 0px corners, yet more structured than rounder, "bubbly" styles.
- **Imagery:** Photography of cacao pods or ceremonial settings should be contained in either sharp-edged frames (0px) or very large, soft-radius containers to emphasize a gallery-like presentation.

## Components

### Buttons
- **Primary:** Solid Deep Cacao with Creamy Beige text. No heavy shadows; use a slight lift on hover.
- **Secondary:** Outlined in Deep Cacao (1px) with serif text for a "literary" feel.
- **Tertiary:** Organic Green text with an underline, used for less prominent invitations to act.

### Cards
- Cards should have no borders. Instead, use a subtle background color shift (Paper Neutral) and a soft, spread-out shadow to denote interactivity. Padding should be generous (min 32px).

### Input Fields
- Inputs use a "floating label" style with a bottom border only, or a very light-tinted beige background. This keeps the forms feeling light and elegant, rather than technical.

### Chips & Tags
- Use Organic Green backgrounds with 10% opacity and Deep Cacao text. These represent "organic" attributes (e.g., "Single Origin," "Fair Trade").

### Decorative Elements
- Incorporate thin vertical and horizontal lines (referencing the logo's internal linework) as structural dividers or to frame specific pieces of text to reinforce the brand identity throughout the journey.