---
name: Caperucita Roja Design System
colors:
  surface: '#161311'
  surface-dim: '#161311'
  surface-bright: '#3d3836'
  surface-container-lowest: '#110e0c'
  surface-container-low: '#1e1b19'
  surface-container: '#231f1d'
  surface-container-high: '#2d2927'
  surface-container-highest: '#383431'
  on-surface: '#e9e1dd'
  on-surface-variant: '#dfbfbc'
  inverse-surface: '#e9e1dd'
  inverse-on-surface: '#34302d'
  outline: '#a68a88'
  outline-variant: '#58413f'
  surface-tint: '#ffb3ae'
  primary: '#ffb3ae'
  on-primary: '#68000b'
  primary-container: '#9c2a2a'
  on-primary-container: '#ffb7b1'
  inverse-primary: '#aa3433'
  secondary: '#d1c5b1'
  on-secondary: '#363022'
  secondary-container: '#504839'
  on-secondary-container: '#c3b7a3'
  tertiary: '#fcb5b1'
  on-tertiary: '#502322'
  tertiary-container: '#7a4544'
  on-tertiary-container: '#feb7b4'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#ffdad7'
  primary-fixed-dim: '#ffb3ae'
  on-primary-fixed: '#410004'
  on-primary-fixed-variant: '#891c1e'
  secondary-fixed: '#eee1cc'
  secondary-fixed-dim: '#d1c5b1'
  on-secondary-fixed: '#211b0e'
  on-secondary-fixed-variant: '#4e4637'
  tertiary-fixed: '#ffdad8'
  tertiary-fixed-dim: '#fcb5b1'
  on-tertiary-fixed: '#360e0f'
  on-tertiary-fixed-variant: '#6b3837'
  background: '#161311'
  on-background: '#e9e1dd'
  surface-variant: '#383431'
typography:
  headline-xl:
    fontFamily: Noto Serif
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Noto Serif
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Noto Serif
    fontSize: 24px
    fontWeight: '400'
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
  label-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: '1'
    letterSpacing: 0.1em
spacing:
  unit: 8px
  container-max: 1140px
  gutter: 24px
  margin-edge: 40px
  section-gap: 120px
---

## Brand & Style

This design system establishes a "Dark Folklore" aesthetic—a sophisticated intersection of atmospheric horror and vintage editorial design. It targets an audience that appreciates narrative depth, tactile quality, and a cinematic user experience. 

The style is primarily **Tactile and Minimalist**, leaning into the "old-book" feel through digital textures. It avoids the flat nature of modern SaaS interfaces in favor of depth, utilizing vignettes and organic shadows to evoke the feeling of reading by candlelight in a dense forest. The emotional response is intended to be one of quiet unease paired with premium elegance.

## Colors

The palette is restricted and dramatic to maintain a high-tension atmosphere.
- **Base (#0f0c0a):** A near-black charcoal used for the "void" of the background.
- **Accent (#9c2a2a):** A visceral, desaturated blood red used sparingly for primary actions and critical narrative focus.
- **Typography (#f5e8d3):** A weathered cream that provides high legibility against the dark base without the harshness of pure white.
- **Deep Red (#3d1414):** Used for subtle hover states and low-elevation containers to maintain the monochromatic warmth.

## Typography

The typographic hierarchy centers on the contrast between the authoritative, literary weight of **Noto Serif** and the invisible utility of **Inter**.

Headlines should utilize "Headline-MD" in italics for pull-quotes or atmospheric sub-headers to reinforce the storyteller's voice. Large display type should always be set with tight letter-spacing to feel dense and intentional. Body text requires generous line heights (1.6) to ensure the cream-on-black contrast remains accessible and easy to read for long-form narrative content.

## Layout & Spacing

This design system employs a **Fixed Grid** model to mimic the structural integrity of a printed book. Content is centered with wide "safety" margins to create a sense of isolation and focus. 

The vertical rhythm is expansive. High-level sections are separated by significant gaps (120px+) to allow the atmospheric background effects—such as smoke or vignettes—to breathe. Components should use an 8px base unit, favoring "loose" internal padding to maintain the premium, unhurried feel of a luxury editorial.

## Elevation & Depth

Hierarchy is established through **Tonal Layers** and **Ambient Shadows** rather than traditional lighting. 

1.  **Vignettes:** Every major page section must feature a radial gradient overlay that darkens the edges of the viewport, drawing the eye toward the center content.
2.  **The "Ink" Layer:** Cards and containers use a slightly lighter shade of the background (#1a1614) with a very soft, desaturated red shadow (0px 20px 40px rgba(61, 20, 20, 0.4)). 
3.  **Texture:** A subtle grain or paper-texture overlay should be applied to the entire UI at a low opacity (3-5%) to break the digital perfection of the screen.

## Shapes

The shape language is strictly **Sharp (0px)**. 

To evoke the feel of vintage woodblock printing and classic bookbinding, all containers, buttons, and input fields must have hard 90-degree corners. This sharpness contributes to the "horror" element of the aesthetic, feeling clinical and dangerous compared to the soft, rounded edges of contemporary web design.

## Components

### Buttons
Primary buttons are solid #9c2a2a with cream text, using "Label-SM" typography. They feature a 1px inner border of a lighter red to simulate a "beveled" book edge. Hover states should not brighten; they should deepen in color or trigger a subtle scale-down (98%) to feel tactile.

### Cards
Cards are defined by 1px borders in #3d1414. They do not have backgrounds by default, relying on the vignette effects of the section to provide separation. When grouped, they should be separated by elegant, thin horizontal dividers.

### Inputs
Text fields are "ghost" style—underlined only by a 1px cream line. The focus state transitions the underline to the primary red. Labels sit above the line in uppercase "Label-SM" style.

### Navigation
The navigation bar is pinned and minimalist. It uses a heavy backdrop blur with a semi-transparent black fill. Links are Noto Serif, lowercase, to feel more like chapter headings than a traditional menu.

### Narrative Elements
- **Drop Caps:** The first letter of major sections should be an oversized Noto Serif drop-cap in the primary accent color.
- **Dividers:** Use custom SVG dividers that resemble thorns, vines, or simple hand-drawn ink lines.