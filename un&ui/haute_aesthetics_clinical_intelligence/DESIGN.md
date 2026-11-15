---
name: Haute Aesthetics & Clinical Intelligence
colors:
  surface: '#fdf9f3'
  surface-dim: '#dddad4'
  surface-bright: '#fdf9f3'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f7f3ed'
  surface-container: '#f1ede7'
  surface-container-high: '#ebe8e2'
  surface-container-highest: '#e6e2dc'
  on-surface: '#1c1c18'
  on-surface-variant: '#524346'
  inverse-surface: '#31302d'
  inverse-on-surface: '#f4f0ea'
  outline: '#847375'
  outline-variant: '#d7c1c4'
  surface-tint: '#8c4a5a'
  primary: '#2f0211'
  on-primary: '#ffffff'
  primary-container: '#4a1525'
  on-primary-container: '#c57a8b'
  inverse-primary: '#ffb1c2'
  secondary: '#835153'
  on-secondary: '#ffffff'
  secondary-container: '#fcbcbe'
  on-secondary-container: '#79494b'
  tertiary: '#300011'
  on-tertiary: '#ffffff'
  tertiary-container: '#4c1225'
  on-tertiary-container: '#c8778b'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffd9df'
  primary-fixed-dim: '#ffb1c2'
  on-primary-fixed: '#3a0819'
  on-primary-fixed-variant: '#703343'
  secondary-fixed: '#ffdada'
  secondary-fixed-dim: '#f6b6b8'
  on-secondary-fixed: '#341013'
  on-secondary-fixed-variant: '#673a3c'
  tertiary-fixed: '#ffd9e0'
  tertiary-fixed-dim: '#ffb1c3'
  on-tertiary-fixed: '#3c0519'
  on-tertiary-fixed-variant: '#733144'
  background: '#fdf9f3'
  on-background: '#1c1c18'
  surface-variant: '#e6e2dc'
typography:
  display-lg:
    fontFamily: Rubik
    fontSize: 48px
    fontWeight: '400'
    lineHeight: 56px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Rubik
    fontSize: 34px
    fontWeight: '400'
    lineHeight: 42px
    letterSpacing: -0.015em
  headline-lg:
    fontFamily: Rubik
    fontSize: 32px
    fontWeight: '500'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Rubik
    fontSize: 26px
    fontWeight: '500'
    lineHeight: 34px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Rubik
    fontSize: 24px
    fontWeight: '500'
    lineHeight: 32px
    letterSpacing: 0em
  headline-sm:
    fontFamily: Rubik
    fontSize: 20px
    fontWeight: '500'
    lineHeight: 28px
    letterSpacing: 0em
  body-lg:
    fontFamily: Rubik
    fontSize: 17px
    fontWeight: '400'
    lineHeight: 26px
    letterSpacing: 0.01em
  body-md:
    fontFamily: Rubik
    fontSize: 15px
    fontWeight: '400'
    lineHeight: 22px
    letterSpacing: 0.01em
  body-sm:
    fontFamily: Rubik
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 18px
    letterSpacing: 0.015em
  label-lg:
    fontFamily: Rubik
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 20px
    letterSpacing: 0.04em
  label-md:
    fontFamily: Rubik
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.06em
  label-sm:
    fontFamily: Rubik
    fontSize: 11px
    fontWeight: '600'
    lineHeight: 14px
    letterSpacing: 0.08em
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
The design system establishes an atmosphere of bespoke clinical precision paired with restorative sanctuary calm. Developed for high-tier aesthetic clinics, medical spas, and cosmetics booking interfaces, the experience avoids both the sterile impersonality of typical healthcare software and the triviality of casual retail apps. 

The aesthetic style merges **Minimalist Tactility** with **Warm Editorial Luxury**. Surfaces feel physical, warm, and architectural, referencing natural travertine, linen textures, and polished organic stone. The interface radiates discretion, clinical authority, and tailored care. Generous whitespace, razor-sharp typographic hierarchy, and intentional restraint create an aura of exclusivity where appointment scheduling feels like entering a private concierge suite.

## Colors
The palette balances skin-loving warm foundations with deep, high-contrast cosmetic pigment tones:

- **Primary (`#4A1525` / `#5B1E31`)**: Rich, deep imperial burgundy. Serves as the primary anchor for maximum contrast and authority. Applied to primary CTAs, critical data states, high-priority confirmations, and deep structural headers.
- **Secondary (`#C88D8F` / `#DDA7A5`)**: Dusty pink and rose clay. Used for secondary actions, subtle focal highlights, interactive toggles, badge backgrounds, and warm focus accents.
- **Neutral & Surfaces (`#FAF6F0` / `#FDFBF7`)**: Alabaster and warm creme. Forms the foundational canvas, reducing blue-light fatigue and mimicking unbleached cotton and premium textured paper.
- **Surface Accents (`#D8CFC4` / `#E6DFD5`)**: Warm sand. Delivers structural grounding for container cards, borders, divider lines, and neutral interactive states.

### Contrast & State Hierarchy
- **Canvas Base**: `#FAF6F0`
- **Surface Elevated / Cards**: `#FDFBF7` with fine borders tinted in `#D8CFC4`
- **Text & Body**: `#2C181E` (soft blackened plum) ensuring WCAG AAA legibility against creme backgrounds
- **Interactive State Hover**: Deepens from `#5B1E31` to `#4A1525` on dark elements; transitions to subtle dusty pink overlays (`rgba(200, 141, 143, 0.12)`) on light surfaces.

## Typography
Rubik brings contemporary proportions, gentle curvature, and exceptional native bi-directional support across both Hebrew and Latin scripts. 

- **Display & Headlines**: Generously tracked when small, tightly kerned when large. Display headlines harness Rubik's regular weights to preserve an understated architectural dignity rather than aggressive mass-market boldness.
- **Body & Data**: Medium line heights maintain effortless reading flow during medical reviews, treatment descriptions, and slot selections.
- **Labels & Micro-copy**: Employs uppercase letter spacing (`letterSpacing: 0.04em - 0.08em`) for category stamps, clinical badges, and step trackers to mirror the packaging design of luxury cosmetic brands.

## Layout & Spacing
The layout adheres to a 12-column responsive fluid grid anchored by rhythmic vertical cadence:

- **Desktop (1200px+)**: 12 columns, `gutter: 1.5rem` (24px), outer canvas `margin: 3rem` (48px), max-width bounded at 1440px for appointment dashboards and diagnostic timelines.
- **Tablet (768px - 1199px)**: 8 columns, `gutter: 1.25rem` (20px), outer canvas `margin: 2rem` (32px).
- **Mobile (< 768px)**: 4 columns, `gutter-mobile: 1rem` (16px), outer canvas `margin-mobile: 1.25rem` (20px).

Content density avoids claustrophobic bundling. Spacing tokens isolate treatments, clinician biographies, and consultation preparation notes with rhythmic breathing room, reinforcing a serene medical sanctuary atmosphere.

## Elevation & Depth
Elevation is achieved using ambient, pigment-tinted shadows and tactile micro-borders rather than standard achromatic dropshadows:

- **Surface Strategy**: The page canvas is rendered in warm Creme (`#FAF6F0`). Elevated cards, drawers, and modal sheets use pure Creme Opal (`#FDFBF7`).
- **Ambient Tinted Shadows**: All drop shadows are mixed with deep Burgundy (`rgba(74, 21, 37, 0.04)`) to eliminate muddy grey tones.
  - *Tier 1 (Cards, Selectable Time Chips)*: `0 2px 8px -2px rgba(74, 21, 37, 0.04), 0 1px 3px 0 rgba(74, 21, 37, 0.02)`
  - *Tier 2 (Hover States, Floating Time Slots)*: `0 8px 24px -4px rgba(74, 21, 37, 0.07), 0 2px 6px -1px rgba(74, 21, 37, 0.03)`
  - *Tier 3 (Booking Overlays, AI Recommendation Sheets)*: `0 20px 40px -8px rgba(74, 21, 37, 0.12), 0 4px 12px -2px rgba(74, 21, 37, 0.04)`
- **Structural Borders**: Paired with an ultra-thin 1px border in Sand (`#E6DFD5` or `#D8CFC4`), creating a defined, linen-bound profile.

## Shapes
A curated softness (`roundedness: 1`) provides geometric discipline alongside humanized warmth:

- Base inputs, buttons, and calendar day nodes use standard **soft corner radiuses (0.25rem - 0.375rem / 4px - 6px)** to reflect pharmaceutical and clinical authority.
- Cards, modal containers, and treatment panels scale to **0.5rem - 0.75rem (8px - 12px)**, creating delicate, smooth structural framing.
- Full pills (`rounded-full`) are reserved solely for live status markers (e.g., "AI Optimized", "Specialist Available") and selected date badges, avoiding juvenile over-rounding across the broader workspace.

## Components

### Buttons
- **Primary Action (Book Consultation / Confirm Treatment)**: Rich Burgundy (`#4A1525`) background, Creme (`#FDFBF7`) label, soft 4px radius. Hover shifts to `#5B1E31` accompanied by a micro-elevation lift.
- **Secondary Action (Reschedule / View Clinic Protocol)**: Transparent background, Sand border (`#D8CFC4`), deep burgundy typography. Hover reveals a translucent Dusty Pink fill (`rgba(221, 167, 165, 0.15)`).
- **Subtle / Text Button**: Text in deep burgundy with understated letter-spacing, accompanied by an animated hairline underline on hover.

### Chips & Time-Slot Selectors
- **Default Slot**: Base Creme (`#FDFBF7`) surface, 1px Sand border (`#D8CFC4`), neutral deep plum typography.
- **Selected Slot**: Deep Burgundy fill (`#4A1525`), white/creme text, no border.
- **AI Suggested Slot**: Base surface with a delicate Dusty Pink border (`#C88D8F`) and a micro-badge labeled "AI Match" rendered in 11px uppercase.

### Cards & Treatment Modules
- Built on `#FDFBF7` with a 1px border in `#E6DFD5`. Internal padding strictly guided by `space-lg` (24px).
- Incorporates high-resolution aesthetic media with 1px border containment, paired with clinical breakdown points (downtime, duration, and designated clinician) in balanced grid arrangements.

### Inputs & Date Selection
- Fields use an inset sand tint (`#FAF6F0`) in resting state, shifting to an alabaster fill (`#FDFBF7`) with a 1px Burgundy focus ring (`#5B1E31`).
- Floating labels adopt the `label-md` uppercase styling in muted plum.

### Specialized AI & Scheduling Components
- **Intelligent Consultation Timeline**: A vertical stepper anchored by a hairline Dusty Pink border (`#DDA7A5`), highlighting pre-care regimens, aesthetic analysis, and post-treatment checkups.
- **Biometric / Skin Analysis Insight Card**: Framed with a subtle dual tone: Sand base with a top accent bar in Burgundy, displaying precision confidence scores and automated treatment suggestions with clinical clarity.