---
name: Atelier de Style
colors:
  surface: '#f9f9f9'
  surface-dim: '#dadada'
  surface-bright: '#f9f9f9'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f3f3f3'
  surface-container: '#eeeeee'
  surface-container-high: '#e8e8e8'
  surface-container-highest: '#e2e2e2'
  on-surface: '#1a1c1c'
  on-surface-variant: '#444748'
  inverse-surface: '#2f3131'
  inverse-on-surface: '#f1f1f1'
  outline: '#747878'
  outline-variant: '#c4c7c7'
  surface-tint: '#5f5e5e'
  primary: '#000000'
  on-primary: '#ffffff'
  primary-container: '#1c1b1b'
  on-primary-container: '#858383'
  inverse-primary: '#c8c6c5'
  secondary: '#5f5e5a'
  on-secondary: '#ffffff'
  secondary-container: '#e5e2dc'
  on-secondary-container: '#656460'
  tertiary: '#000000'
  on-tertiary: '#ffffff'
  tertiary-container: '#261900'
  on-tertiary-container: '#a17f3b'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e5e2e1'
  primary-fixed-dim: '#c8c6c5'
  on-primary-fixed: '#1c1b1b'
  on-primary-fixed-variant: '#474746'
  secondary-fixed: '#e5e2dc'
  secondary-fixed-dim: '#c9c6c1'
  on-secondary-fixed: '#1c1c18'
  on-secondary-fixed-variant: '#474743'
  tertiary-fixed: '#ffdea5'
  tertiary-fixed-dim: '#e9c176'
  on-tertiary-fixed: '#261900'
  on-tertiary-fixed-variant: '#5d4201'
  background: '#f9f9f9'
  on-background: '#1a1c1c'
  surface-variant: '#e2e2e2'
typography:
  display-lg:
    fontFamily: Playfair Display
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.3'
  headline-md-mobile:
    fontFamily: Playfair Display
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.3'
  title-sm:
    fontFamily: Be Vietnam Pro
    fontSize: 18px
    fontWeight: '600'
    lineHeight: '1.5'
    letterSpacing: 0.05em
  body-lg:
    fontFamily: Be Vietnam Pro
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.7'
  body-sm:
    fontFamily: Be Vietnam Pro
    fontSize: 14px
    fontWeight: '400'
    lineHeight: '1.6'
  label-caps:
    fontFamily: Be Vietnam Pro
    fontSize: 12px
    fontWeight: '600'
    lineHeight: '1.0'
    letterSpacing: 0.1em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  unit: 4px
  container-max: 1200px
  gutter: 24px
  margin-desktop: 64px
  margin-mobile: 20px
  section-gap: 120px
---

## Brand & Style

The design system is rooted in the "New Minimalist" movement—a fusion of high-fashion editorial aesthetics and functional modernism. It targets a discerning audience seeking a bespoke, high-end personal styling experience. The UI must feel like an invitation into a private boutique: quiet, confident, and curated.

The emotional response should be one of "effortless elegance." By leveraging heavy whitespace and a restricted color palette, we allow high-quality photography and typography to command the user's attention. The interface acts as a silent frame for the stylist’s work, emphasizing craftsmanship and individual expression.

## Colors

The palette is architectural and restrained. 
- **Primary (Deep Charcoal):** Used for primary text and structural elements to provide weight and authority.
- **Secondary (Soft Beige):** The foundational surface color for containers and backgrounds to evoke the warmth of high-quality fabrics like linen and cashmere.
- **Tertiary (Elegant Gold):** Applied sparingly for interactive accents, subtle dividers, or status indicators to provide a sense of luxury.
- **Neutral:** Pure white and soft greys are used for absolute clarity in input fields and base backgrounds.

High contrast is maintained between text and background to ensure the Korean typography remains sharp and legible.

## Typography

This design system utilizes a high-contrast typographic pairing. **Playfair Display** provides the editorial "voice," used for headlines and prominent quotes to mimic fashion magazine layouts. 

For functional text and body copy, **Be Vietnam Pro** is selected for its contemporary, clean proportions which complement the complex strokes of Korean characters (Hangul) without feeling cluttered. 

- Use `display-lg` for hero sections and impact statements.
- Use `label-caps` for small metadata, category tags, and navigation items to add a touch of modern utility.
- Line heights are intentionally generous (1.7x for body) to ensure readability and a "breathing" layout.

## Layout & Spacing

The layout philosophy follows a **Fixed Grid** model on desktop to maintain an editorial feel, centered within the viewport. 

- **Desktop (1440px+):** 12-column grid with 24px gutters and 64px side margins. Large "section-gaps" of 120px are used to separate different content clusters, reinforcing the premium feel.
- **Mobile:** 4-column fluid grid with 20px side margins. 

Spacing is used as a functional element to group related items. Elements should "float" within the Soft Beige (`secondary`) background, utilizing the `section-gap` to prevent visual overwhelm.

## Elevation & Depth

This design system avoids heavy drop shadows in favor of **Tonal Layers** and **Low-Contrast Outlines**. 

Depth is achieved by:
- **Layering:** Placing Soft Beige containers over Neutral backgrounds.
- **Keyline Borders:** Using very thin (1px) borders in either Gold (tertiary) or a muted version of Charcoal to define cards and sections.
- **Subtle Blurs:** If a modal or overlay is required, use a light backdrop blur (Glassmorphism) to keep the background context visible while maintaining focus.

Shadows, if used for floating action buttons or menus, must be extremely diffused (30px+ blur) and low opacity (5-10%) to appear as ambient lighting rather than a physical shadow.

## Shapes

The shape language is "Soft" (0.25rem base). This subtle rounding takes the edge off the brutalist tendencies of a high-fashion grid, making the brand feel more approachable and tailored. 

- **Primary Buttons:** Subtle rounding (4px) to maintain a sharp, professional look.
- **Images:** Strictly sharp (0px) or slightly rounded (4px) to mimic printed lookbooks.
- **Input Fields:** Consistent 4px corners to align with the button style.

## Components

- **Buttons:** Primary buttons use a solid Deep Charcoal background with white text. Ghost buttons use a 1px Gold border with Charcoal text. Padding should be generous (16px vertical, 32px horizontal).
- **Cards:** Elevated through a simple 1px Soft Beige border or a subtle tonal shift. No heavy shadows. Images within cards should have a 3:4 aspect ratio (editorial standard).
- **Chips/Tags:** Used for style categories (e.g., #Minimal, #AvantGarde). These should use `label-caps` typography and a light beige background.
- **Input Fields:** Minimalist design with only a bottom-border or a very faint 4px-rounded stroke. Labels always appear above the field in `label-caps`.
- **Dividers:** Use the Gold (tertiary) color at 0.5px thickness to separate major sections without breaking the visual flow.
- **Imagery:** All photos should follow a consistent "high-key" lighting style with a slightly desaturated or warm-toned filter to match the Beige/Gold palette.