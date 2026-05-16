---
name: Clinical Nexus
colors:
  surface: '#f9f9ff'
  surface-dim: '#d0daf2'
  surface-bright: '#f9f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f0f3ff'
  surface-container: '#e8eeff'
  surface-container-high: '#dfe8ff'
  surface-container-highest: '#d8e3fb'
  on-surface: '#111c2d'
  on-surface-variant: '#41474e'
  inverse-surface: '#273143'
  inverse-on-surface: '#ecf0ff'
  outline: '#72787f'
  outline-variant: '#c1c7cf'
  surface-tint: '#316289'
  primary: '#074469'
  on-primary: '#ffffff'
  primary-container: '#2a5c82'
  on-primary-container: '#a5d4ff'
  inverse-primary: '#9ccbf7'
  secondary: '#3d608a'
  on-secondary: '#ffffff'
  secondary-container: '#abcffe'
  on-secondary-container: '#345881'
  tertiary: '#22435f'
  on-tertiary: '#ffffff'
  tertiary-container: '#3b5b78'
  on-tertiary-container: '#b2d2f4'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#cde5ff'
  primary-fixed-dim: '#9ccbf7'
  on-primary-fixed: '#001d32'
  on-primary-fixed-variant: '#124a6f'
  secondary-fixed: '#d2e4ff'
  secondary-fixed-dim: '#a6c9f8'
  on-secondary-fixed: '#001c37'
  on-secondary-fixed-variant: '#234970'
  tertiary-fixed: '#cee5ff'
  tertiary-fixed-dim: '#a9caeb'
  on-tertiary-fixed: '#001d32'
  on-tertiary-fixed-variant: '#294965'
  background: '#f9f9ff'
  on-background: '#111c2d'
  surface-variant: '#d8e3fb'
typography:
  display-lg:
    fontFamily: Inter
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  title-lg:
    fontFamily: Inter
    fontSize: 20px
    fontWeight: '500'
    lineHeight: 28px
  body-lg:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  label-md:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.05em
  code-md:
    fontFamily: Inter
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 18px
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  sidebar_width: 260px
  container_max_width: 1600px
  gutter: 24px
  margin_desktop: 40px
  unit: 8px
---

## Brand & Style
The design system is engineered for high-stakes clinical environments, prioritizing cognitive ease, precision, and trust. The target audience includes healthcare practitioners, data analysts, and clinical administrators who require rapid data synthesis.

The design style is **Corporate / Modern** with a lean toward **Minimalism**. It utilizes expansive white space to reduce visual noise, ensuring that critical medical data remains the focal point. The aesthetic is clinical but not cold—achieving a balance between professional rigor and user-centric clarity.

## Colors
The palette is rooted in a deep, authoritative blue (`#2a5c82`), signifying stability and medical expertise. 

- **Primary:** Used for key actions, active navigation states, and primary brand elements.
- **Secondary/Tertiary:** Utilized for data visualization accents and secondary UI elements to provide depth without introducing distracting hues.
- **Neutral:** A range of cool grays used for typography and borders, maintaining a high-contrast ratio for accessibility while avoiding the harshness of pure black.
- **Surface Colors:** Employs very light gray-blue washes for container backgrounds to subtly distinguish between content areas.

## Typography
This design system utilizes **Inter** exclusively to leverage its exceptional legibility in data-heavy contexts. The type scale is optimized for high-density information display.

- **Headlines:** Use tighter letter spacing and semi-bold weights to create a clear hierarchy.
- **Body:** Set at 14px for standard data entries to maximize information density while maintaining readability.
- **Labels:** Uppercase with slight tracking for metadata and table headers.
- **Numerical Data:** Tabular figures are preferred for clinical values to ensure vertical alignment in tables.

## Layout & Spacing
The layout follows a **Fixed-Fluid Hybrid** model designed for wide-screen desktop monitors.

- **Persistent Sidebar:** A 260px left-hand navigation remains anchored, providing immediate access to core modules.
- **Grid System:** A 12-column grid with 24px gutters. Dashboard widgets typically span 3, 4, or 6 columns.
- **High-Density Logic:** Uses an 8px base unit. Padding within data tables is reduced to 12px (vertical) to increase visible rows, while page margins are generous (40px) to prevent the UI from feeling claustrophobic.
- **Breakpoints:** Optimized for 1440px and 1920px. On ultra-wide screens, content is capped at 1600px and centered to maintain ergonomic scanning lines.

## Elevation & Depth
Visual hierarchy is achieved through **Tonal Layers** and **Low-Contrast Outlines** rather than heavy shadows.

- **Surface Levels:** The background uses a neutral off-white. Secondary containers (like sidebars or property panels) use a subtle cool-gray fill.
- **Borders:** Elements are defined by 1px solid borders in a light neutral tint (`#e5e9f0`). This provides structure for complex data grids without the "muddiness" of shadows.
- **Active State Elevation:** Only primary modals and floating tooltips use a soft, ambient shadow (15% opacity, 12px blur) to indicate temporary overlay status.

## Shapes
The shape language is **Soft** and restrained.

- **Components:** Standard buttons, input fields, and cards utilize a 4px (0.25rem) corner radius. This provides a modern feel while maintaining the structural "grid-like" efficiency required for clinical software.
- **Data Points:** Small badges and status indicators use a fully rounded (pill) shape to distinguish them from interactive UI components.

## Components
- **Buttons:** Primary buttons are solid `#2a5c82` with white text. Secondary buttons use a 1px border. Interactions are subtle (slight darkening on hover).
- **Data Tables:** The core of the system. Features sticky headers, zebra-striping on hover, and condensed row heights. Column headers use `label-md` styling.
- **Cards/Widgets:** Simple containers with 1px borders. Header areas within cards are separated by a subtle horizontal rule.
- **Input Fields:** Inset borders with a 2px primary blue focus ring. Labels are always persistent (never placeholder-only) for clinical safety.
- **Persistent Sidebar:** Features high-contrast active states. Icons are linear and paired with `body-md` text.
- **Status Chips:** Use a background-tint approach (e.g., light red background with dark red text) for at-a-glance clinical alerts without overwhelming the user.