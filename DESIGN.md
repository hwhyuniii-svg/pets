---
name: Nordic Shelter System
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
  on-surface-variant: '#45474c'
  inverse-surface: '#2e3132'
  inverse-on-surface: '#f0f1f2'
  outline: '#76777c'
  outline-variant: '#c6c6cc'
  surface-tint: '#585e6c'
  primary: '#030813'
  on-primary: '#ffffff'
  primary-container: '#1a202c'
  on-primary-container: '#828796'
  inverse-primary: '#c1c6d7'
  secondary: '#545f72'
  on-secondary: '#ffffff'
  secondary-container: '#d5e0f7'
  on-secondary-container: '#586377'
  tertiary: '#000b07'
  on-tertiary: '#ffffff'
  tertiary-container: '#10241d'
  on-tertiary-container: '#778d83'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dde2f3'
  primary-fixed-dim: '#c1c6d7'
  on-primary-fixed: '#161c27'
  on-primary-fixed-variant: '#414754'
  secondary-fixed: '#d8e3fa'
  secondary-fixed-dim: '#bcc7dd'
  on-secondary-fixed: '#111c2c'
  on-secondary-fixed-variant: '#3c475a'
  tertiary-fixed: '#d1e8dd'
  tertiary-fixed-dim: '#b5ccc1'
  on-tertiary-fixed: '#0b1f18'
  on-tertiary-fixed-variant: '#374b43'
  background: '#f8f9fa'
  on-background: '#191c1d'
  surface-variant: '#e1e3e4'
typography:
  display-lg:
    fontFamily: Inter
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Inter
    fontSize: 28px
    fontWeight: '600'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Inter
    fontSize: 24px
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
  label-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '500'
    lineHeight: '1.4'
    letterSpacing: 0.05em
  caption:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '400'
    lineHeight: '1.4'
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  base: 8px
  container-max: 1200px
  gutter: 24px
  margin-desktop: 64px
  margin-mobile: 20px
  stack-sm: 12px
  stack-md: 32px
  stack-lg: 80px
---

## Brand & Style

This design system is built upon the principles of **Nordic Minimalism**, specifically tailored for a modern Estonian animal shelter. The brand personality is disciplined, ethical, and profoundly calm. It seeks to replace the typical "emotional chaos" of animal rescue with a sense of architectural order, reliability, and high-trust professionalism. 

The visual language emphasizes transparency and clarity, using generous whitespace to allow the photography of the animals to serve as the primary emotional driver. The style is clean and high-contrast, leaning into a "Gallery" aesthetic where the UI acts as a sophisticated frame for the content. The target audience includes urban professionals and families in Tallinn who value structured, efficient, and compassionate service.

## Colors

The color palette is rooted in the Estonian landscape—cool, muted, and sophisticated. 

- **Primary (#1A202C):** A deep charcoal/blue-black used for primary actions, high-level headings, and structural elements. It provides the "anchor" for the design.
- **Secondary (#4A5568):** A muted slate grey for sub-navigation and secondary text, maintaining hierarchy without the harshness of pure black.
- **Accent/Sage (#8DA399):** A very muted, desaturated green used sparingly for success states, adoption availability badges, or "warm" calls to action. This prevents the UI from feeling clinical.
- **Surface & Background:** We utilize a stark white (#FFFFFF) for cards and content containers, layered over a soft off-white (#F9FAFB) background to create subtle depth without relying on shadows.

## Typography

The design system uses **Inter** exclusively to ensure maximum legibility and a systematic, modern feel across both Latin and Cyrillic scripts. 

- **Headlines:** Set with tighter letter-spacing and bold weights to create a strong, architectural presence.
- **Body Text:** Uses a generous line-height (1.6) to ensure long-form Russian text remains readable and airy.
- **Labels:** Small caps or uppercase with increased letter-spacing are used for metadata (e.g., animal age, breed, location) to provide a distinct visual rhythm.
- **Alignment:** Consistent left-alignment is preferred to maintain a clean "axis" throughout the layout.

## Layout & Spacing

The layout philosophy is a **fixed-width centered grid** for desktop and a fluid single-column for mobile. 

- **Grid:** A 12-column grid with 24px gutters. Content should feel "un-crowded."
- **Rhythm:** We use a strict 8px base unit. Vertical rhythm is driven by large "breathing spaces" (80px+) between major sections to prevent visual fatigue.
- **Margins:** Desktop margins are generous (64px) to reinforce the minimalist, gallery-like feel. 
- **Adaptation:** On mobile, padding is reduced to 20px, and complex grids collapse into a vertical stack. Multi-column animal listings transition from a 3-column or 4-column layout on desktop to a 1-column or 2-column layout on mobile.

## Elevation & Depth

To maintain the Nordic aesthetic, this design system avoids heavy shadows and traditional skeuomorphism. Depth is achieved through:

1.  **Tonal Layering:** Using the slight contrast between the Background (#F9FAFB) and Surface (#FFFFFF) to define interactive areas.
2.  **Low-Contrast Outlines:** Instead of shadows, cards and input fields use a 1px solid border in `#E2E8F0`. This creates a crisp, technical look.
3.  **Active States:** When an element is hovered or focused, the border color darkens to the Primary or Secondary color, rather than "lifting" off the page.
4.  **Flat Interaction:** Buttons remain flat. We prioritize color shifts and precise typography over artificial 3D depth.

## Shapes

The shape language is **architectural and precise**. 

We use a "Soft" rounding (4px / 0.25rem) for UI elements like buttons, input fields, and tags. This subtle radius removes the "aggression" of sharp corners—making the brand feel approachable—while maintaining a modern, disciplined silhouette. Larger containers like image carousels or cards also follow this 4px rule to ensure consistency.

## Components

### Buttons
- **Primary:** Solid `#1A202C` background with white Inter Medium text. No shadow. 4px radius.
- **Secondary:** Transparent background with a 1px `#1A202C` border. 
- **Tertiary:** Text-only with a subtle underline or arrow icon, used for "Read More" links.

### Cards (Animal Profiles)
- White background, 1px `#E2E8F0` border.
- High-quality imagery takes up the top 60% of the card.
- Text content is left-aligned with consistent 24px internal padding.
- Use **Labels** for metadata like "Tallinn, Estonia" or "2 years old."

### Input Fields
- 1px `#E2E8F0` border, 4px radius.
- Labels are placed above the field in **label-md** style.
- Focus state: Border changes to `#1A202C`.

### Chips / Status Badges
- Used for animal status (e.g., "В приюте", "Нашел дом").
- Small text, uppercase, subtle `#F3F4F6` background or a very light tint of the Sage accent.

### Lists
- Clean, unstyled bullet points or custom icons (minimalist chevron or dash).
- Generous vertical padding between list items (16px) to maintain the airy feel.

### Navigation
- Simple horizontal top-bar. 
- High contrast. Active links are marked with a subtle 2px bottom border in Primary charcoal.