---
name: Clinical Nexus
colors:
  surface: '#f9f9ff'
  surface-dim: '#cfdaf2'
  surface-bright: '#f9f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f0f3ff'
  surface-container: '#e7eeff'
  surface-container-high: '#dee8ff'
  surface-container-highest: '#d8e3fb'
  on-surface: '#111c2d'
  on-surface-variant: '#41474e'
  inverse-surface: '#263143'
  inverse-on-surface: '#ecf1ff'
  outline: '#72787f'
  outline-variant: '#c1c7cf'
  surface-tint: '#316289'
  primary: '#074469'
  on-primary: '#ffffff'
  primary-container: '#2a5c82'
  on-primary-container: '#a5d4ff'
  inverse-primary: '#9ccbf7'
  secondary: '#006e1c'
  on-secondary: '#ffffff'
  secondary-container: '#91f78e'
  on-secondary-container: '#00731e'
  tertiary: '#5a3b00'
  on-tertiary: '#ffffff'
  tertiary-container: '#76510e'
  on-tertiary-container: '#fac67a'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#cde5ff'
  primary-fixed-dim: '#9ccbf7'
  on-primary-fixed: '#001d32'
  on-primary-fixed-variant: '#124a6f'
  secondary-fixed: '#94f990'
  secondary-fixed-dim: '#78dc77'
  on-secondary-fixed: '#002204'
  on-secondary-fixed-variant: '#005313'
  tertiary-fixed: '#ffddb0'
  tertiary-fixed-dim: '#f1be72'
  on-tertiary-fixed: '#281800'
  on-tertiary-fixed-variant: '#614000'
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
  headline-lg-mobile:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  headline-md:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 20px
    letterSpacing: 0.01em
  label-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.05em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  base: 8px
  xs: 4px
  sm: 12px
  md: 24px
  lg: 48px
  xl: 64px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 80px
---

## Brand & Style

The design system is engineered for a city-wide medical infrastructure, prioritizing **trust, efficiency, and calmness**. The brand personality is clinical yet compassionate, stripping away unnecessary decorative elements to focus on rapid information retrieval and task completion. 

The visual style follows a **Modern Corporate Minimalism** approach. It leverages generous whitespace to reduce cognitive load for patients and practitioners alike, while utilizing subtle depth cues to guide the eye toward critical actions. The interface should feel expansive, clean, and meticulously organized, evoking the precision of a modern healthcare facility.

## Colors

This design system utilizes a palette rooted in psychological safety. 

- **Primary (Medical Blue):** Used for core navigation, primary actions, and branding. It conveys authority and reliability.
- **Secondary (Healthy Green):** Reserved for positive outcomes, health metrics, and "success" states.
- **Neutral (Charcoal):** Applied to typography and iconography to ensure AAA accessibility against the light backgrounds.
- **Background (Light Grey):** A cool-toned off-white that reduces screen glare compared to pure white, essential for long-term usage by staff.

Surface colors should be layered primarily through the background grey, with white (`#FFFFFF`) reserved for cards and elevated containers to create a clear "island" layout effect.

## Typography

**Inter** is the sole typeface for this design system, chosen for its exceptional legibility in both large-scale headlines and small-scale data tables. 

The hierarchy is strictly enforced to ensure users can scan medical records or hospital lists quickly. Headlines utilize a semi-bold weight and tighter letter spacing for a modern, authoritative feel. Body text uses standard tracking and a generous line height (1.5x) to ensure readability for users under stress or with visual impairments. Labels for data points and captions should use Medium weights to distinguish them from standard body copy.

## Layout & Spacing

The layout follows a **Fixed-Fluid Hybrid** model. On desktop, content is contained within a 1280px max-width container to prevent line-lengths from becoming unreadable. On mobile, a standard 4-column grid is used.

The spacing rhythm is built on an **8px linear scale**. 
- **Margins:** 16px on mobile, scaling to 80px on large desktops.
- **Gutters:** 24px consistent across all breakpoints to maintain a high-airflow aesthetic.
- **Section Spacing:** Use `lg` (48px) or `xl` (64px) to separate distinct medical modules (e.g., separating "Upcoming Appointments" from "Recent Results").

## Elevation & Depth

This design system uses **Ambient Shadows** to create a soft, non-threatening sense of hierarchy. 

Depth is communicated through three primary tiers:
1.  **Level 0 (Floor):** The `#F8FAFC` background. 
2.  **Level 1 (Cards):** White surfaces with a very soft, diffused shadow (`0 4px 20px rgba(30, 41, 59, 0.05)`). These are the primary containers for profile info and search results.
3.  **Level 2 (Overlays/Modals):** A more pronounced shadow to indicate focus (`0 12px 40px rgba(30, 41, 59, 0.12)`).

Avoid harsh borders. Instead, use the contrast between the white card and the grey background to define boundaries.

## Shapes

The shape language is defined by **Softened Geometrics**. A standard radius of `0.5rem` (8px) is applied to all primary components like input fields, buttons, and small cards. 

Large containers, such as profile cards or map sheets, utilize `rounded-lg` (16px) to appear more welcoming and "human." Interactive elements like chips or badges should use the full pill-shape (999px) to clearly distinguish them from actionable buttons.

## Components

### Buttons & Call-to-Action
- **Primary:** Solid `Medical Blue` with white text. High-contrast, 8px corner radius.
- **Secondary:** Outlined `Medical Blue` (1px) with a subtle light-blue hover state.
- **Success:** Solid `Healthy Green` for "Confirm Appointment" or "Payment Complete" actions.

### Search & Inputs
Search bars should span the full width of their container, featuring a leading magnifying glass icon in a muted charcoal. Use a white background even when placed on white cards to signify interactivity via the 8px radius and a subtle 1px border (`#E2E8F0`).

### Profile Cards
Profile cards for doctors or patients should utilize a Level 1 elevation. The layout should be "Left-Heavy," featuring a circular avatar, followed by name (Headline-MD) and specialty (Label-MD).

### Map Pins
Map pins for hospitals use a "Teardrop" shape in `Medical Blue`. When active, the pin should scale up slightly and reveal a small white dot in the center.

### Lists
Lists for medical records or history should use a "Divided" style rather than boxed. Use a 1px separator (`#F1F5F9`) and provide at least 16px of vertical padding between items to maintain the minimalist, airy feel.