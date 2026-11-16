---
name: Luminous Intelligence
colors:
  surface: '#f7f9fb'
  surface-dim: '#d8dadc'
  surface-bright: '#f7f9fb'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f2f4f6'
  surface-container: '#eceef0'
  surface-container-high: '#e6e8ea'
  surface-container-highest: '#e0e3e5'
  on-surface: '#191c1e'
  on-surface-variant: '#434655'
  inverse-surface: '#2d3133'
  inverse-on-surface: '#eff1f3'
  outline: '#737686'
  outline-variant: '#c3c6d7'
  surface-tint: '#0053db'
  primary: '#004ac6'
  on-primary: '#ffffff'
  primary-container: '#2563eb'
  on-primary-container: '#eeefff'
  inverse-primary: '#b4c5ff'
  secondary: '#565e74'
  on-secondary: '#ffffff'
  secondary-container: '#dae2fd'
  on-secondary-container: '#5c647a'
  tertiary: '#006242'
  on-tertiary: '#ffffff'
  tertiary-container: '#007d55'
  on-tertiary-container: '#bdffdb'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dbe1ff'
  primary-fixed-dim: '#b4c5ff'
  on-primary-fixed: '#00174b'
  on-primary-fixed-variant: '#003ea8'
  secondary-fixed: '#dae2fd'
  secondary-fixed-dim: '#bec6e0'
  on-secondary-fixed: '#131b2e'
  on-secondary-fixed-variant: '#3f465c'
  tertiary-fixed: '#6ffbbe'
  tertiary-fixed-dim: '#4edea3'
  on-tertiary-fixed: '#002113'
  on-tertiary-fixed-variant: '#005236'
  background: '#f7f9fb'
  on-background: '#191c1e'
  surface-variant: '#e0e3e5'
typography:
  display-hero:
    fontFamily: Plus Jakarta Sans
    fontSize: 56px
    fontWeight: '800'
    lineHeight: 64px
    letterSpacing: -0.03em
  display-hero-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 36px
    fontWeight: '800'
    lineHeight: 44px
    letterSpacing: -0.025em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 48px
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 36px
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 36px
    letterSpacing: -0.015em
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
    letterSpacing: -0.01em
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
    letterSpacing: -0.005em
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-sm:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.01em
  label-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '700'
    lineHeight: 16px
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
  gutter-mobile: 1rem
  margin: 3rem
  margin-mobile: 1.25rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
  space-2xl: 4rem
---

## Brand & Style

This design system crafts an aura of domestic enchantment grounded in high-precision engineering. Designed for discerning homeowners, tech adopters, and modern families seeking automated peace of mind, the aesthetic strikes a careful balance between high-end architectural clarity and approachable ambient AI. 

The aesthetic is **Modern Architectural Precision** with **Ambient Glass Accents**. It relies on crisp micro-borders, deep confident slate foundations, expansive clean whites, and luminous optical glows that indicate active intelligence without visual clutter. The emotional resonance is calm, hyper-reliable, and quietly powerful—giving the user the immediate feeling that their home is under the vigilant, discreet care of a sophisticated digital presence.

## Colors

The palette establishes sharp hierarchy through distinct contrast roles:

- **Primary (`#2563EB`)**: High-energy electric tech blue used decisively for conversion drivers, focused states, and key navigational milestones.
- **Secondary (`#0F172A`)**: Deep oceanic slate providing typographic gravitas, high-contrast dark sections, hero contrast blocks, and grounding layout structures.
- **Tertiary (`#10B981`)**: Signal emerald deployed exclusively for verified status pings, hardware operational health, security badges, and warranty guarantees.
- **Neutral (`#F8FAFC`)**: Crystalline off-white base that eliminates sterile harshness while ensuring maximum legibility and card separation.

### Functional Roles & Contrast Rules
- **Subtle Surface Stroke**: `#E2E8F0` (Slate-200) in light mode, `#1E293B` (Slate-800) in dark structural sections.
- **Text Primary**: `#0F172A` on neutral surfaces; `#F8FAFC` on deep slate containers.
- **Text Muted**: `#64748B` (Slate-500) for secondary metadata and technical specifications.
- **Interactive Blue Hover**: `#1D4ED8`.
- **Emerald Tint Fill**: `#ECFDF5` with `#059669` text for trust badges.

## Typography

The type system pairs the geometric warmth of **Plus Jakarta Sans** for headlines and interactive indicators with the clarity of **Inter** for dense technical narrative, telemetry data, and long-form readability.

- **Display & Headings**: Set tight with slight negative tracking to deliver punchy, confident product statements.
- **Body Architecture**: Retains generous line-heights for quick scanning on mobile devices during on-the-go review.
- **Labels & Micro-copy**: Employs uppercase or semi-bold styling with positive tracking on small labels (`label-sm`) for status indicators and certification badges.

## Layout & Spacing

The layout model is a flexible, mobile-first responsive grid structured to enforce airiness and architectural breathing room.

- **Mobile (< 768px)**: 4-column layout with `1.25rem` outer margins and `1rem` gutters. Touch targets adhere to a strict minimum hit area of 48px.
- **Tablet (768px - 1024px)**: 8-column layout with `2rem` outer margins and `1.25rem` gutters.
- **Desktop (> 1024px)**: 12-column layout capped at a maximum width of `1280px` centered, utilizing `3rem` margins and `1.5rem` gutters.
- **Vertical Cadence**: Component sections breathe with `space-2xl` on mobile and expand dynamically up to `6rem` on desktop viewports to spotlight hardware models and performance charts without cognitive overload.

## Elevation & Depth

Visual hierarchy is maintained via a combination of low-contrast surface borders and diffused ambient illumination:

- **Level 0 (Flat Ground)**: Base surface `#F8FAFC` without drop shadows.
- **Level 1 (Card Resting)**: 1px continuous stroke of `#E2E8F0` coupled with an ambient drop shadow: `0px 4px 20px -2px rgba(15, 23, 42, 0.05)`.
- **Level 2 (Hover / Active Cards)**: 1px border highlighted with `#CBD5E1` and an elevated shadow: `0px 12px 32px -4px rgba(15, 23, 42, 0.08)`.
- **Level 3 (Modal / Sticky Mobile Drawer)**: Borderless or fine-line `#E2E8F0` with structural depth: `0px 24px 48px -8px rgba(15, 23, 42, 0.14)`.
- **Luminous Glow (AI Active State)**: Radial drop shadow using the primary accent: `0px 0px 30px rgba(37, 99, 235, 0.25)`.
- **Dark Mode / Deep Slate Container Rules**: Inside `#0F172A` modules, borders shift to `rgba(255, 255, 255, 0.08)` and elevations rely on tonal lifting via `#1E293B` backgrounds rather than cast shadows.

## Shapes

The design system adopts a balanced **Rounded (`2`)** profile. 
- Standard interactables and compact inputs use `0.5rem` (`8px`) radius to remain sharp, technical, and grounded.
- Larger feature showcases, interactive dashboards, and feature cards scale to `rounded-lg` (`1rem` / `16px`) and `rounded-xl` (`1.5rem` / `24px`) to feel friendly and tactile.
- Trust pills, warranty badges, and primary action buttons make selective use of pill bounds (`9999px`) to invite touch interactions on handheld screens.

## Components

### Buttons
- **Primary CTA**: Background `#2563EB`, text `#FFFFFF`, font `label-md`. Rounded pill or `0.5rem` radius. Subtle hover state to `#1D4ED8` with a soft blue ambient underglow.
- **Secondary CTA**: Neutral background, border 1px `#0F172A`, text `#0F172A`. On dark surfaces: transparent background with 1px border `#F8FAFC` and white text.
- **Mobile Sticky CTA**: Fixed bottom container spanning full viewport width with a backdrop-blur of `12px`, holding a full-width Primary CTA for instant access.

### Badges & Warranty Pills
- **Security & Warranty Badges**: Background `#ECFDF5`, 1px solid stroke of `rgba(16, 185, 129, 0.3)`, text `#065F46`, font `label-sm`. Prefixed with an emerald dot or lock icon.
- **AI Telemetry Indicator**: Background `rgba(37, 99, 235, 0.1)`, text `#2563EB`, pulsing indicator dot at 8px diameter.

### Cards
- **Feature & Capability Cards**: Base background `#FFFFFF`, border 1px solid `#E2E8F0`, padding `space-lg` to `space-xl`. Smooth transition on elevation and border tone upon touch or hover.
- **Dark Inverted Cards (Genie Core Specs)**: Deep slate `#0F172A` background, border 1px solid `#1E293B`, internal copy in `#F8FAFC` and `#94A3B8`.

### Input Fields
- Surface `#FFFFFF`, border 1px solid `#CBD5E1`, text `#0F172A`, placeholder `#94A3B8`. Focus ring: 2px offset ring in `#2563EB`. Height calibrated for touch accessibility at 48px minimum.

### Checkboxes & Radios
- Native sizes 20x20px with a 4px border radius. Unchecked state: 1.5px border `#94A3B8`. Checked state: `#2563EB` fill with crisp white vector checkmark.

### Live Status Ping (Specialty Component)
- Real-time indicator displaying device connection: concentric ring animation emitting from a solid `#10B981` node, accompanied by single-line typography in `label-sm` denoting 99.99% automated uptime.