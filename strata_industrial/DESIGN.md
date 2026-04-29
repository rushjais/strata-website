---
name: Strata Industrial
colors:
  surface: '#121416'
  surface-dim: '#121416'
  surface-bright: '#37393b'
  surface-container-lowest: '#0c0e10'
  surface-container-low: '#1a1c1e'
  surface-container: '#1e2022'
  surface-container-high: '#282a2c'
  surface-container-highest: '#333537'
  on-surface: '#e2e2e5'
  on-surface-variant: '#e2bfb0'
  inverse-surface: '#e2e2e5'
  inverse-on-surface: '#2f3133'
  outline: '#a98a7d'
  outline-variant: '#5a4136'
  surface-tint: '#ffb693'
  primary: '#ffb693'
  on-primary: '#561f00'
  primary-container: '#ff6b00'
  on-primary-container: '#572000'
  inverse-primary: '#a04100'
  secondary: '#b9c7e0'
  on-secondary: '#233144'
  secondary-container: '#3c4a5e'
  on-secondary-container: '#abb9d2'
  tertiary: '#c6c6c7'
  on-tertiary: '#2f3131'
  tertiary-container: '#989999'
  on-tertiary-container: '#2f3132'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#ffdbcc'
  primary-fixed-dim: '#ffb693'
  on-primary-fixed: '#351000'
  on-primary-fixed-variant: '#7a3000'
  secondary-fixed: '#d5e3fd'
  secondary-fixed-dim: '#b9c7e0'
  on-secondary-fixed: '#0d1c2f'
  on-secondary-fixed-variant: '#3a485c'
  tertiary-fixed: '#e2e2e2'
  tertiary-fixed-dim: '#c6c6c7'
  on-tertiary-fixed: '#1a1c1c'
  on-tertiary-fixed-variant: '#454747'
  background: '#121416'
  on-background: '#e2e2e5'
  surface-variant: '#333537'
typography:
  h1:
    fontFamily: Space Grotesk
    fontSize: 40px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  h2:
    fontFamily: Space Grotesk
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: -0.01em
  h3:
    fontFamily: Space Grotesk
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.3'
    letterSpacing: 0em
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
    letterSpacing: 0em
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.5'
    letterSpacing: 0em
  label-caps:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '700'
    lineHeight: '1'
    letterSpacing: 0.1em
  mono-data:
    fontFamily: Space Grotesk
    fontSize: 14px
    fontWeight: '500'
    lineHeight: '1'
    letterSpacing: 0.05em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  base: 4px
  unit-1: 4px
  unit-2: 8px
  unit-4: 16px
  unit-6: 24px
  unit-8: 32px
  unit-12: 48px
  margin-mobile: 16px
  margin-tablet: 24px
  gutter: 16px
---

## Brand & Style

The design system is engineered for high-stakes field environments where reliability and precision are paramount. It adopts an **Industrial-Modern** aesthetic, blending the utilitarian aesthetics of heavy machinery with the sophisticated intelligence of an AI copilot.

The brand personality is authoritative yet assistive—functioning less like a software application and more like a high-performance power tool. The UI utilizes a "Blueprint" philosophy, featuring subtle grid lines and technical alignment to evoke architectural stability. Micro-interactions are intentionally mechanical, providing haptic-like visual feedback that mimics physical toggle switches and calibrated instruments. Imagery focuses on "The Expert at Work," using high-contrast photography of technicians in rugged environments to ground the digital experience in physical reality.

## Colors

This design system utilizes a high-visibility, dark-mode-first palette optimized for both low-light utility rooms and bright outdoor environments.

- **Safety Orange (#FF6B00):** Reserved exclusively for primary actions, critical alerts, and active AI listening states. It demands immediate attention against the dark backdrop.
- **Charcoal Gray (#1A1C1E):** The foundational surface color. It reduces eye strain and provides a deep, non-distracting canvas for data.
- **Slate (#334155):** Used for secondary surfaces, inactive states, and structural elements like headers or sidebars.
- **Crisp White (#FFFFFF):** Applied to primary typography and iconography to ensure maximum legibility and "glanceability" in the field.

## Typography

The typography strategy prioritizes structural integrity and rapid information processing. 

**Space Grotesk** is used for headlines to provide a technical, geometric edge that feels engineered. Its distinct letterforms remain legible even when viewed at an angle or on vibrating handheld devices.

**Inter** serves as the workhorse for body text and labels. It is selected for its neutral, systematic character and exceptional performance at small sizes within complex technical manuals. All labels and metadata should use a slightly increased letter-spacing to ensure characters do not bleed together in high-brightness outdoor conditions.

## Layout & Spacing

This design system employs a **Fixed Grid** model based on an 8px rhythmic scale, reinforced by visible structural markers.

- **The Technical Grid:** Subtle 1px lines (Slate at 20% opacity) should occasionally be visible to delineate major layout sections, mimicking a blueprint or technical drawing.
- **Touch Targets:** Minimum touch target size is 48x48px to accommodate gloved hands or movement.
- **Padding:** Generous internal padding (unit-6) is used within cards to ensure text never feels cramped against borders. 
- **Alignment:** All elements must snap strictly to the grid; centered layouts are avoided in favor of strong left-aligned blocks to maintain the "architectural" feel.

## Elevation & Depth

Hierarchy is established through **Bold Borders** and **Tonal Layering** rather than traditional shadows, which can feel too "soft" for an industrial tool.

- **Primary Surface:** Charcoal Gray (#1A1C1E).
- **Secondary Surface (Cards/Modules):** Slate (#334155) with a 1px solid border of White at 10% opacity.
- **Active Elevation:** When an element is focused or active, it does not "float"; instead, its border thickness increases or changes to Safety Orange.
- **Overlays:** Modals and tooltips use a slight backdrop blur (10px) combined with a thicker 2px border to separate the AI copilot’s "intelligence layer" from the base technical data.

## Shapes

The shape language is "Soft-Industrial." While sharp 0px corners feel overly aggressive, high roundedness feels too consumer-focused. 

The system uses a **0.25rem (4px) base radius** for cards, buttons, and input fields. This provides a "milled" look—similar to machined metal parts that have had their sharp edges professionally deburred. Icons should follow this logic, using consistent stroke weights and slight corner rounding to match the UI components.

## Components

- **Primary Action Buttons:** Solid Safety Orange background with White uppercase text. Features a subtle "pressed" state where the button shrinks by 2% to simulate a mechanical click.
- **Information Cards:** Dark Slate background with a thin border. Header area of the card is separated by a 1px horizontal rule.
- **AI Vision Viewport:** A dedicated component with "crosshair" corner brackets in Safety Orange to indicate active scanning.
- **Voice Feedback Waveform:** A monochromatic (White) animated line that appears in the top navigation bar when the AI is processing audio.
- **Input Fields:** Outlined style only. The border is Slate when inactive and Safety Orange when focused. Labels always sit above the field in "Label-Caps" typography.
- **Status Chips:** Small, rectangular tags with a background opacity of 20% of the status color (e.g., Green for "Optimal", Yellow for "Review Required").
- **Iconography:** Line-based, 2px stroke weight. Specific custom icons for:
    - **Voice:** A stylized frequency bar.
    - **Vision:** An eye within a viewfinder frame.
    - **Manuals:** A geometric blueprint/document fold.