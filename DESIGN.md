---
name: Industrial Precision
colors:
  surface: '#f8f9fa'
  surface-dim: '#d9dadb'
  surface-bright: '#f8f9fa'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f3f4f5'
  surface-container: '#edeeef'
  surface-container-high: '#e7e8e9'
  surface-container-highest: '#e1e3e4'
  on-surface: '#191c1d'
  on-surface-variant: '#43474f'
  inverse-surface: '#2e3132'
  inverse-on-surface: '#f0f1f2'
  outline: '#737780'
  outline-variant: '#c3c6d1'
  surface-tint: '#3a5f94'
  primary: '#001e40'
  on-primary: '#ffffff'
  primary-container: '#003366'
  on-primary-container: '#799dd6'
  inverse-primary: '#a7c8ff'
  secondary: '#904d00'
  on-secondary: '#ffffff'
  secondary-container: '#fd8b00'
  on-secondary-container: '#603100'
  tertiary: '#161f26'
  on-tertiary: '#ffffff'
  tertiary-container: '#2b343b'
  on-tertiary-container: '#939ca5'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d5e3ff'
  primary-fixed-dim: '#a7c8ff'
  on-primary-fixed: '#001b3c'
  on-primary-fixed-variant: '#1f477b'
  secondary-fixed: '#ffdcc3'
  secondary-fixed-dim: '#ffb77d'
  on-secondary-fixed: '#2f1500'
  on-secondary-fixed-variant: '#6e3900'
  tertiary-fixed: '#dbe4ed'
  tertiary-fixed-dim: '#bfc8d0'
  on-tertiary-fixed: '#141d23'
  on-tertiary-fixed-variant: '#3f484f'
  background: '#f8f9fa'
  on-background: '#191c1d'
  surface-variant: '#e1e3e4'
typography:
  display-lg:
    fontFamily: Vazirmatn
    fontSize: 48px
    fontWeight: '800'
    lineHeight: 64px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Vazirmatn
    fontSize: 32px
    fontWeight: '800'
    lineHeight: 44px
  headline-md:
    fontFamily: Vazirmatn
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 40px
  headline-sm:
    fontFamily: Vazirmatn
    fontSize: 22px
    fontWeight: '700'
    lineHeight: 32px
  body-lg:
    fontFamily: Vazirmatn
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 30px
  body-md:
    fontFamily: Vazirmatn
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 26px
  label-bold:
    fontFamily: Vazirmatn
    fontSize: 14px
    fontWeight: '700'
    lineHeight: 20px
  caption:
    fontFamily: Vazirmatn
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 18px
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  container-max: 1200px
  gutter: 24px
  section-padding-desktop: 80px
  section-padding-mobile: 40px
  stack-sm: 8px
  stack-md: 16px
  stack-lg: 32px
---

## Brand & Style
The design system is engineered for a high-tech construction firm specializing in foam concrete. The brand personality is rooted in **expertise, reliability, and industrial efficiency**. It targets developers and homeowners who value structural integrity and modern engineering.

The visual style is **Corporate Modern with Industrial accents**. It utilizes a structured grid, high-quality whitespace, and precise alignment to evoke a sense of architectural planning. The interface should feel "built"—solid, dependable, and meticulously finished.

## Colors
The palette is dominated by **Navy Blue**, symbolizing structural trust and deep industry experience. **Amber/Orange** is used sparingly but strategically for high-priority calls to action and the interactive calculator, providing a functional contrast against the "concrete" backgrounds.

- **Primary (Navy):** Used for headers, primary buttons, and icon containers.
- **Secondary (Amber):** Reserved for "Calculate Quote," "Call Now," and progress indicators.
- **Background (Light Grey/White):** Mimics the clean, cured finish of high-quality foam concrete.
- **Text (Dark Grey):** Ensures high legibility for technical specifications and contractual details.

## Typography
This design system uses **Vazirmatn** for its clean, geometric Persian glyphs that align with an industrial aesthetic. 

- **Headlines:** Use heavy weights (700-800) to create a clear visual hierarchy and project strength.
- **Body Text:** Maintained at 16px-18px for optimal readability of technical service descriptions.
- **Labels:** Used for the calculator inputs and service categories, utilizing bold weights for clarity at smaller sizes.
- **RTL Support:** Ensure all line-heights account for Persian ascenders and descenders to prevent clipping in cramped UI elements.

## Layout & Spacing
The layout follows a **12-column fluid grid** for desktop, transitioning to a **4-column grid** for mobile. 

- **Rhythm:** A base-8 spacing scale ensures mathematical consistency.
- **Sticky Header:** Should have a height of 80px on desktop and 64px on mobile, utilizing a semi-transparent white background with a backdrop blur to maintain context as the user scrolls.
- **Calculator Layout:** The calculator should utilize a 2-column layout on desktop (inputs on left, results on right) and stack vertically on mobile.
- **Margins:** Desktop margins are fixed at 24px to ensure content doesn't hit the screen edges on smaller laptops.

## Elevation & Depth
To maintain a professional and "grounded" feel, this design system uses **Tonal Layers** and **Low-Contrast Outlines** rather than heavy shadows.

- **Level 0 (Background):** #F8F9FA.
- **Level 1 (Cards/Surface):** #FFFFFF with a 1px border of #E9ECEF.
- **Level 2 (Interactive/Floating):** Used for the Sticky Header and Active Calculator states. Apply a subtle, diffused shadow: `0px 4px 20px rgba(0, 0, 0, 0.05)`.
- **Depth Metaphor:** Elements should feel like slabs—solid and layered rather than floating high above the surface.

## Shapes
The shape language is **Soft (0.25rem)**. This slight rounding takes the "edge" off the industrial aesthetic, making the brand feel modern and approachable without losing the precision of a "square" industrial grid.

- **Standard Buttons:** 0.25rem (4px) corner radius.
- **Service Cards:** 0.5rem (8px) corner radius for a distinct container feel.
- **Inputs:** 4px radius to match buttons, creating a unified form language in the calculator.

## Components
### Buttons
- **Primary:** Navy Blue background, White text. High-contrast, solid.
- **Secondary (CTA):** Amber background, Dark Grey (#333333) text. Used for "Get Quote" and "Calculator Submit."
- **Ghost:** Navy Blue border and text, transparent background. Used for "Learn More."

### Service Cards
- Use a white surface with a 1px #E9ECEF border.
- Icons should be Navy Blue, contained within a light grey circular or square background.
- Include a subtle hover state where the border color shifts to the Primary Navy.

### Calculator Card
- **Header:** Contrast background (Navy) with white text to define the tool area.
- **Inputs:** Large, clear numeric inputs with Persian label text positioned above the field.
- **Result Area:** Highlighted with a light Amber tint (#FFF4E5) to draw the eye to the final calculation.

### Sticky Header
- Stays fixed at the top of the viewport.
- Contains the logo (Right-aligned for RTL), Navigation Links (Center), and a "Call Now" Amber button (Left-aligned).
- Height: 72px.

### Checkboxes & Radios
- Use Primary Navy for checked states.
- Focus rings should use a 2px offset with Primary Navy to ensure accessibility.