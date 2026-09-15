---
name: Atelier Contact
colors:
  surface: '#f8f9ff'
  surface-dim: '#cbdbf5'
  surface-bright: '#f8f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#eff4ff'
  surface-container: '#e5eeff'
  surface-container-high: '#dce9ff'
  surface-container-highest: '#d3e4fe'
  on-surface: '#0b1c30'
  on-surface-variant: '#45464d'
  inverse-surface: '#213145'
  inverse-on-surface: '#eaf1ff'
  outline: '#76777d'
  outline-variant: '#c6c6cd'
  surface-tint: '#565e74'
  primary: '#000000'
  on-primary: '#ffffff'
  primary-container: '#131b2e'
  on-primary-container: '#7c839b'
  inverse-primary: '#bec6e0'
  secondary: '#0051d5'
  on-secondary: '#ffffff'
  secondary-container: '#316bf3'
  on-secondary-container: '#fefcff'
  tertiary: '#000000'
  on-tertiary: '#ffffff'
  tertiary-container: '#271901'
  on-tertiary-container: '#98805d'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dae2fd'
  primary-fixed-dim: '#bec6e0'
  on-primary-fixed: '#131b2e'
  on-primary-fixed-variant: '#3f465c'
  secondary-fixed: '#dbe1ff'
  secondary-fixed-dim: '#b4c5ff'
  on-secondary-fixed: '#00174b'
  on-secondary-fixed-variant: '#003ea8'
  tertiary-fixed: '#fcdeb5'
  tertiary-fixed-dim: '#dec29a'
  on-tertiary-fixed: '#271901'
  on-tertiary-fixed-variant: '#574425'
  background: '#f8f9ff'
  on-background: '#0b1c30'
  surface-variant: '#d3e4fe'
typography:
  display-xl:
    fontFamily: Plus Jakarta Sans
    fontSize: 56px
    fontWeight: '700'
    lineHeight: 64px
    letterSpacing: -0.03em
  display-xl-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 36px
    fontWeight: '700'
    lineHeight: 44px
    letterSpacing: -0.025em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 26px
    fontWeight: '600'
    lineHeight: 34px
    letterSpacing: -0.015em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 22px
    fontWeight: '600'
    lineHeight: 28px
    letterSpacing: -0.01em
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
    letterSpacing: -0.01em
  body-md:
    fontFamily: Inter
    fontSize: 15px
    fontWeight: '400'
    lineHeight: 24px
    letterSpacing: '0'
  body-sm:
    fontFamily: Inter
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 20px
    letterSpacing: '0'
  label-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 20px
    letterSpacing: -0.005em
  label-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.04em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-mobile: 1rem
  margin: 3rem
  margin-mobile: 1.25rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

This design system embodies high-end digital craftsmanship, architectural restraint, and bespoke editorial precision. Tailored for executive creative directors, design studios, and elite independent consultants, it projects unwavering authority and approachable sophistication.

### Design Aesthetic
- **High-End Editorial Minimalism**: Pure whitespace acts as an active layout medium rather than empty canvas.
- **Micro-Tactile Precision**: Razor-sharp, low-contrast divider lines (#e2e8f0) and whisper-thin outlines paired with precise micro-interactions.
- **Architectural Cadence**: Generous breathing room, structural hierarchy, and deliberate typography scale convey luxury without excessive ornament.

## Colors

The palette is engineered around pure chromatic clarity and deep slate contrast, accented with an intentional modern indigo spark.

### Color Logic
- **Canvas Base**: Pure white `#ffffff` forms the pristine foundational background, maintaining museum-grade presentation value.
- **Primary Surface / Text**: Deep Slate `#0f172a` commands high-priority titles, primary buttons, and critical states.
- **Secondary Accent**: Precision Indigo `#2563eb` highlights interactive focus states, verified badges, active linkages, and micro-delights.
- **Supporting Neutrals**:
  - Secondary text / field labels: Slate `#334155`
  - Subtle body & placeholder text: Cool Slate `#64748b`
  - Structural hairline borders: Soft Platinum `#e2e8f0`
  - Recessed input & card fills: Subtle Off-White `#f8fafc`

## Typography

Typography blends the sculptural geometry of **Plus Jakarta Sans** for headlines with the utilitarian readability of **Inter** for forms, metadata, and editorial body copy.

- **Plus Jakarta Sans**: Delivers an approachable modern luxury feel with sculpted joints and tight negative tracking in larger scales.
- **Inter**: Handles all functional data entry, long-form content, validation feedback, and structural metadata without visual interference.
- **Tracking Discipline**: Display titles employ negative tracking (`-0.03em` to `-0.02em`) to bind headline phrases into single cohesive gestures, while uppercase mini labels (`label-sm`) expand slightly (`+0.04em`) to safeguard optical balance.

## Layout & Spacing

The contact page uses an asymmetrical fixed-container grid capped at a maximum width of 1200px.

### Breakpoints & Grid Composition
- **Desktop (>= 1024px)**: 12-column grid. Contact details, direct availability metrics, and trust indicators span 5 columns on the left; the interactive inquiry form occupies 7 columns on the right. Gutter is 24px (`1.5rem`), outer padding is 48px (`3rem`).
- **Tablet (768px - 1023px)**: 8-column layout. Form and direct details stack sequentially with a 40px vertical rhythm.
- **Mobile (< 768px)**: Single-column fluid stack with 20px outer margin (`margin-mobile`), ensuring finger-friendly touch targets with zero horizontal overflow.

## Elevation & Depth

This system intentionally departs from heavy drop shadows, favoring featherlight ambient deflections and hairline structural perimeters.

- **Surface Level 0 (Base Canvas)**: `#ffffff` with no shadow.
- **Surface Level 1 (Card & Floating Containers)**: `#ffffff` backed by a 1px border of `#e2e8f0` and an imperceptible ambient diffusion:
  - `0 1px 3px 0 rgba(15, 23, 42, 0.04), 0 1px 2px -1px rgba(15, 23, 42, 0.02)`
- **Surface Level 2 (Hover / Active Focus States)**: Subtle lift with an indigo-tinted anchor:
  - `0 10px 25px -5px rgba(15, 23, 42, 0.04), 0 8px 10px -6px rgba(15, 23, 42, 0.02)`
- **Focus Rings**: A crisp 2-step focus structure consisting of a 2px offset in `#ffffff` followed by a 2px solid halo in `#2563eb`.

## Shapes

The design uses a restrained, tailored edge system (`roundedness: 1`), keeping edges crisp and intentional rather than overly rounded or juvenile.

- Standard inputs, buttons, and badges use `0.375rem` to `0.5rem` (6px–8px).
- Status chips and availability badges feature full pill radii (`9999px`) to visually contrast against square structural inputs.
- Large editorial cards employ `0.75rem` (12px) paired with 1px border framing.

## Components

### 1. Interactive Inputs & Textareas
- **Resting**: Background `#f8fafc`, 1px solid `#e2e8f0`, text `#0f172a`, font Inter 15px. Generous vertical padding (`0.875rem` / 14px) and horizontal padding (`1rem` / 16px).
- **Hover**: Border transitions to `#cbd5e1`.
- **Focus**: Border shifts to `#0f172a`, background lifts to `#ffffff`, backed by a 3px outer glow `rgba(37, 99, 235, 0.12)`.
- **Labels**: Inter 13px, weight 500, color `#334155`, floating `6px` above the field container with an optional muted `(optional)` suffix in `#94a3b8`.

### 2. Buttons
- **Primary CTA**: `#0f172a` slate background, pure white `#ffffff` text, font Plus Jakarta Sans 14px semi-bold. Height 48px, horizontal padding 24px, subtle border `1px solid #0f172a`. On hover: lifts subtly, transitions background to `#1e293b`.
- **Secondary / Action Links**: Crisp `#ffffff` fill, `1px solid #e2e8f0`, text `#334155`. On hover: border shifts to `#0f172a`, text `#0f172a`.

### 3. Badges & Availability Indicators
- **Availability Pill**: Pill shape (`9999px`), background `#f1f5f9`, border `1px solid #e2e8f0`, font Inter 12px weight 600. Features a 6px pulsing emerald dot (`#10b981`) denoting live project availability ("Available Q3/Q4").
- **Category / Service Tags**: Soft slate background `#f8fafc`, border `#e2e8f0`, text `#475569`. On select: background `#0f172a`, border `#0f172a`, text `#ffffff`.

### 4. Direct Information Cards
- Minimalist contact item blocks (Email, Studio Location, Timezone Clock): 1px border `#e2e8f0`, background `#ffffff`. Subtle left-aligned monochromatic iconography with secondary metadata lines in `#64748b`.