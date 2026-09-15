---
name: Modern Executive Portfolio
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
  on-surface-variant: '#464554'
  inverse-surface: '#213145'
  inverse-on-surface: '#eaf1ff'
  outline: '#777586'
  outline-variant: '#c7c4d7'
  surface-tint: '#5148d7'
  primary: '#2a14b4'
  on-primary: '#ffffff'
  primary-container: '#4338ca'
  on-primary-container: '#c1beff'
  inverse-primary: '#c3c0ff'
  secondary: '#565e74'
  on-secondary: '#ffffff'
  secondary-container: '#dae2fd'
  on-secondary-container: '#5c647a'
  tertiary: '#003e61'
  on-tertiary: '#ffffff'
  tertiary-container: '#005684'
  on-tertiary-container: '#8fcbff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e3dfff'
  primary-fixed-dim: '#c3c0ff'
  on-primary-fixed: '#100069'
  on-primary-fixed-variant: '#372abf'
  secondary-fixed: '#dae2fd'
  secondary-fixed-dim: '#bec6e0'
  on-secondary-fixed: '#131b2e'
  on-secondary-fixed-variant: '#3f465c'
  tertiary-fixed: '#cce5ff'
  tertiary-fixed-dim: '#93ccff'
  on-tertiary-fixed: '#001d31'
  on-tertiary-fixed-variant: '#004b73'
  background: '#f8f9ff'
  on-background: '#0b1c30'
  surface-variant: '#d3e4fe'
typography:
  display-hero:
    fontFamily: Plus Jakarta Sans
    fontSize: 3.75rem
    fontWeight: '700'
    lineHeight: 4.25rem
    letterSpacing: -0.03em
  display-hero-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 2.25rem
    fontWeight: '700'
    lineHeight: 2.75rem
    letterSpacing: -0.025em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 2.25rem
    fontWeight: '700'
    lineHeight: 2.75rem
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 1.75rem
    fontWeight: '700'
    lineHeight: 2.25rem
    letterSpacing: -0.015em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 1.5rem
    fontWeight: '600'
    lineHeight: 2rem
    letterSpacing: -0.015em
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 1.125rem
    fontWeight: '600'
    lineHeight: 1.625rem
    letterSpacing: -0.01em
  body-lg:
    fontFamily: Inter
    fontSize: 1.125rem
    fontWeight: '400'
    lineHeight: 1.875rem
    letterSpacing: -0.005em
  body-md:
    fontFamily: Inter
    fontSize: 1rem
    fontWeight: '400'
    lineHeight: 1.625rem
    letterSpacing: '0'
  body-sm:
    fontFamily: Inter
    fontSize: 0.875rem
    fontWeight: '400'
    lineHeight: 1.375rem
    letterSpacing: '0'
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 0.875rem
    fontWeight: '600'
    lineHeight: 1.25rem
    letterSpacing: 0.01em
  label-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 0.75rem
    fontWeight: '600'
    lineHeight: 1rem
    letterSpacing: 0.04em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-desktop: 2rem
  margin: 1.25rem
  margin-desktop: 3rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style
This design system embodies refined executive presence, intellectual clarity, and precision engineering. Designed for high-caliber professionals, technologists, and design leaders, the aesthetic rejects superficial ornamentation in favor of scannability, structural hierarchy, and meticulous craft.

The visual direction marries contemporary **Minimalism** with subtle architectural structure:
- **Clean Whitespace:** Generous negative space anchors user focus on accomplishments, case studies, and core proficiencies.
- **Micro-Precision:** Fine-line borders, calibrated slate grays, and targeted indigo accents present an aura of deliberate, high-end production.
- **Confidence & Restraint:** Micro-interactions are brief, crisp, and tactile rather than flashy, signaling deep competence and quiet authority.

## Colors
The palette relies on pure base whites, structured slate grays, and precise electric indigo highlights:

- **Base & Surface:** Pure white (`#ffffff`) serves as the base canvas, paired with subtle off-white slate tiers (`#f8fafc` for card backgrounds and `#f1f5f9` for nested wells/pills) to construct soft, non-intrusive visual separation.
- **Primary Accent (`#4338ca` - Indigo 700):** Applied sparingly to focal interaction targets: primary action buttons, active navigation states, link hovers, and strategic brand badges.
- **Secondary Authority (`#0f172a` - Slate 900):** Anchors headlines, primary text, dark action buttons, and critical structural lines.
- **Tertiary Accent (`#0284c7` - Sky 600):** Reserved for technical indicators, live availability badges, status dots, and subtle secondary metadata.
- **Neutral Stack (`#64748b` - Slate 500):** Dictates secondary descriptive text, metadata, and fine border outlines (`#e2e8f0`).

## Typography
The typographic system pairs the geometric warmth and distinctive letterforms of **Plus Jakarta Sans** for titles, headings, and metric callouts with the utilitarian, highly legible rhythm of **Inter** for long-form narrative body and case study copy.

- **Headlines:** Display and headline levels rely on snug, negative tracking (`-0.015em` to `-0.03em`) and high contrast weights (600–700) to create immediate visual hierarchy on light backdrops.
- **Body:** Standard body copy prioritizes line height (`1.625` to `1.66` ratio) over dense packing, guaranteeing effortless reading across deep case studies and project breakdowns.
- **Labels & Badges:** `label-sm` leverages slight uppercase treatment or positive tracking (`0.04em`) when utilized in status indicators and category dividers.

## Layout & Spacing
The layout follows a centered, responsive 12-column grid capped at a maximum container width of `1200px` (or `1280px` for wide screen displays), ensuring content never stretches beyond optimal scanning bounds.

- **Desktop (1024px+):** 12-column structure with `2rem` gutters and `3rem` canvas margins. Case studies and skill categories sit in modular 3-column or 4-column balanced distributions.
- **Tablet (768px - 1023px):** 8-column layout with `1.5rem` gutters and `2rem` margins. Skill cards shift into 2-column matrices.
- **Mobile (<768px):** Single-column stacked flow with `1.25rem` outer margins. Dense multi-column lists reflow vertically to safeguard line length and tap-target comfort.
- **Rhythm:** Section-to-section flow relies on multiples of `space-xl` (`5rem` to `7.5rem` on desktop) to maintain an unhurried, editorial pacing.

## Elevation & Depth
This design system eschews heavy, simulated dropshadows in favor of **low-contrast outlines** paired with **ambient micro-shadows**:

- **Borders & Contours:** Cards, inputs, and structural modules sit inside crisp 1px borders using `#e2e8f0` (Slate 200).
- **Surface Elevation:** Interactive modules sit atop pure `#ffffff` against subtle `#f8fafc` page sections or vice versa.
- **Ambient Shadow Token:**
  - *Resting Card:* `0 1px 3px 0 rgba(15, 23, 42, 0.04), 0 1px 2px -1px rgba(15, 23, 42, 0.02)`
  - *Hover Elevation:* `0 10px 25px -5px rgba(15, 23, 42, 0.06), 0 8px 10px -6px rgba(15, 23, 42, 0.03)` with a simultaneous border color transition to `#cbd5e1`.
- **Glass Overlays:** Header navigation bars utilize backdrop blur (`backdrop-filter: blur(12px)`) with an 80% opacity fill (`rgba(255, 255, 255, 0.8)`) and a 1px bottom divider in `#f1f5f9`.

## Shapes
Geometry strikes a balance between contemporary softness and architectural precision:

- **Cards & Panels (`rounded-lg` / 1rem):** Skill containers, case study previews, and modal sheets use a 16px radius for a warm yet orderly appearance.
- **Buttons & Text Inputs (`rounded` / 0.5rem):** Standard action items utilize an 8px radius, matching the inner proportions of nested cards.
- **Badges & Category Pills (Full Pill / 9999px):** Skill tags, metadata chips, and status markers are fully rounded pills, providing an organic visual counterpoint to rectilinear card bounds.

## Components

### Buttons
- **Primary:** Background `#0f172a` (Slate 900), text `#ffffff`, border transparent, radius `0.5rem`, padding `0.75rem 1.5rem`. Hover: background `#4338ca` (Indigo), transform `translateY(-1px)`, transition `all 150ms cubic-bezier(0.4, 0, 0.2, 1)`.
- **Secondary:** Background `#ffffff`, text `#0f172a`, border `1px solid #e2e8f0`. Hover: background `#f8fafc`, border `#cbd5e1`.
- **Ghost/Tertiary:** Background transparent, text `#4338ca`, weight 600. Hover: background `#e0e7ff` at 30% opacity.

### Badge Pills & Status Tags
- **Skill Pill:** Fully rounded (`rounded-full`), padding `0.375rem 0.875rem`, text `label-sm`, background `#f1f5f9`, border `1px solid #e2e8f0`, text color `#334155`. Hover state: background `#e0e7ff`, border color `#c7d2fe`, text color `#4338ca`.
- **Status Indicator Pill:** Light green tint background (`#f0fdf4`), border `1px solid #bbf7d0`, text `#15803d` with a pulsating 6px dot for "Available for Projects".

### Categorized Skill Cards
- **Container:** Background `#ffffff`, border `1px solid #e2e8f0`, radius `1rem`, internal padding `1.75rem`.
- **Header:** Category title in `headline-sm` with an accompanying subtle slate icon well (`2rem x 2rem`, radius `0.5rem`, background `#f8fafc`).
- **Tag Layout:** Flex-wrap layout with `0.5rem` gap hosting skill pills.
- **Micro-Interaction:** Hovering the card triggers a subtle elevation shadow and smooth `translateY(-2px)` transition.

### Project & Case Study Cards
- **Layout:** High-ratio visual thumbnail followed by metadata row (date, client, role), `headline-md` title, descriptive body snippet, and pill tags.
- **Hover:** Smooth image scale (`1.02x` over `300ms`) contained within the card's clipped `rounded-lg` boundary.

### Form Inputs & Controls
- **Text Inputs:** Pure white background, `1px solid #e2e8f0`, text `#0f172a`, placeholder `#94a3b8`, radius `0.5rem`, height `2.75rem`, padding `0 0.875rem`. Focus: border color `#4338ca`, ring `2px rgba(67, 56, 202, 0.15)`, outline none.
- **Checkboxes & Radios:** Unchecked border `#cbd5e1`, checked background `#4338ca` with crisp white checkmark glyph.