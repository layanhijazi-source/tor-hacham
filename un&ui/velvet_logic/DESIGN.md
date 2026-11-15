---
name: Velvet & Logic
colors:
  surface: '#faf9f6'
  surface-dim: '#dbdad7'
  surface-bright: '#faf9f6'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f4f3f1'
  surface-container: '#efeeeb'
  surface-container-high: '#e9e8e5'
  surface-container-highest: '#e3e2e0'
  on-surface: '#1a1c1a'
  on-surface-variant: '#544243'
  inverse-surface: '#2f312f'
  inverse-on-surface: '#f2f1ee'
  outline: '#877273'
  outline-variant: '#dac1c1'
  surface-tint: '#98434c'
  primary: '#98434c'
  on-primary: '#ffffff'
  primary-container: '#d9777f'
  on-primary-container: '#57121d'
  inverse-primary: '#ffb2b7'
  secondary: '#6f5577'
  on-secondary: '#ffffff'
  secondary-container: '#f6d5fd'
  on-secondary-container: '#74597c'
  tertiary: '#216a53'
  on-tertiary: '#ffffff'
  tertiary-container: '#5ca187'
  on-tertiary-container: '#003426'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdadb'
  primary-fixed-dim: '#ffb2b7'
  on-primary-fixed: '#40010e'
  on-primary-fixed-variant: '#7a2c36'
  secondary-fixed: '#f9d8ff'
  secondary-fixed-dim: '#dcbce3'
  on-secondary-fixed: '#281331'
  on-secondary-fixed-variant: '#563e5e'
  tertiary-fixed: '#aaf1d4'
  tertiary-fixed-dim: '#8ed5b9'
  on-tertiary-fixed: '#002117'
  on-tertiary-fixed-variant: '#00513d'
  background: '#faf9f6'
  on-background: '#1a1c1a'
  surface-variant: '#e3e2e0'
typography:
  headline-xl:
    fontFamily: Rubik
    fontSize: 2.5rem
    fontWeight: '600'
    lineHeight: 3rem
  headline-xl-mobile:
    fontFamily: Rubik
    fontSize: 2rem
    fontWeight: '600'
    lineHeight: 2.5rem
  headline-lg:
    fontFamily: Rubik
    fontSize: 2rem
    fontWeight: '600'
    lineHeight: 2.5rem
  headline-lg-mobile:
    fontFamily: Rubik
    fontSize: 1.625rem
    fontWeight: '600'
    lineHeight: 2rem
  headline-md:
    fontFamily: Rubik
    fontSize: 1.5rem
    fontWeight: '500'
    lineHeight: 2rem
  headline-sm:
    fontFamily: Rubik
    fontSize: 1.25rem
    fontWeight: '500'
    lineHeight: 1.75rem
  body-lg:
    fontFamily: Rubik
    fontSize: 1.125rem
    fontWeight: '400'
    lineHeight: 1.75rem
  body-md:
    fontFamily: Rubik
    fontSize: 1rem
    fontWeight: '400'
    lineHeight: 1.5rem
  body-sm:
    fontFamily: Rubik
    fontSize: 0.875rem
    fontWeight: '400'
    lineHeight: 1.25rem
  label-lg:
    fontFamily: Rubik
    fontSize: 0.875rem
    fontWeight: '500'
    lineHeight: 1.25rem
  label-md:
    fontFamily: Rubik
    fontSize: 0.75rem
    fontWeight: '500'
    lineHeight: 1rem
  label-sm:
    fontFamily: Rubik
    fontSize: 0.6875rem
    fontWeight: '500'
    lineHeight: 0.875rem
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-sm: 1rem
  margin: 2rem
  margin-mobile: 1rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style
The design system combines the sensory warmth of premium aesthetics and cosmetic wellness with the clinical efficiency of modern AI scheduling. It bridges two distinct worlds: the customer-facing conversational journey (approachable, human, calming) and the salon professional’s high-density operational cockpit (fluid, precise, organized).

The design style is **Warm Modern Luxury with Glass Nuances**:
- **Tactile Softness**: Creamy off-white foundational canvas paired with dusty rose and terracotta tones removes the sterile coldness typical of enterprise SaaS.
- **Precision AI Craft**: AI flows, WhatsApp interactions, and automated slot allocations are presented with high-clarity tokens, soft glowing mint accents, and polished surface elevation.
- **RTL-Native Ergonomics**: Tailored natively for right-to-left layout dynamics, maintaining rhythmic balance across calendar grids, conversational threads, and statistical summaries without awkward asymmetrical flips.

## Colors
The palette balances cosmetic sensuality with crisp functional clarity:

- **Primary (`#D9777F` - Dusty Rose)**: Anchors key actions, active calendar slot selections, and primary touchpoints. Emits luxury and approachability without overpowering readability.
- **Secondary (`#3D2645` - Deep Plum Mauve)**: The structural spine. Replaces harsh true black for typography, high-priority navigation bars, headers, and prominent container borders. Offers contrast with an editorial edge.
- **Tertiary (`#4E937A` - Muted Sage Emerald)**: Applied for confirmed booking milestones, WhatsApp automation triggers, and positive revenue signals. Derived to complement the warm rose rather than clash.
- **Neutral (`#FAF9F6` - Alabaster Pearl)**: Base viewport canvas. Layered upward with pure white (`#FFFFFF`) for elevated cards and `#F3EFEA` for structural grouping frames and table headers.

### Semantic Tones & Accents
- **AI Intelligence & WhatsApp Accent**: `#25D366` is tuned down into `#2FA866` for system icons, conversational avatars, and automated response indicators to harmonize with the deep plum palette.
- **Status Tones**:
  - *מאושר (Confirmed)*: Soft Sage background (`#EDF7F2`), Sage foreground (`#2D6A4F`).
  - *בהמתנה (Pending)*: Amber Blush background (`#FFF5EB`), Terracotta foreground (`#C86146`).
  - *מבוטל (Canceled)*: Muted Crimson background (`#FDF0EE`), Crimson foreground (`#B84A39`).
  - *הועבר לטיפול אנושי (Handed to Human)*: Lavender Plum background (`#F4EEF7`), Deep Mauve foreground (`#5A3866`).

## Typography
Typography is set entirely in **Rubik**, optimized for native Hebrew rendering with soft curves, geometric stability, and open counters.

- **RTL Baseline**: All alignments defaults to `text-align: right` with optical margins compensating for Hebrew diacritics and initial character weights.
- **Numbers & Metrics**: Digits in currency (`₪`), time indicators (`14:30`), and duration spans preserve uniform tabular figures (`font-variant-numeric: tabular-nums`) so calendar columns and price lists do not visually shift.
- **Weight Restraint**: Weights are constrained primarily to `400` (Body text, conversational messages) and `500`/`600` (Labels, navigation items, calendar cards). The `700` weight is reserved exclusively for primary statistical summaries.

## Layout & Spacing
The layout employs an asymmetrical split-pane system tailored for concurrent workflows:

1. **Dashboard Split-Screen (Desktop)**:
   - **Primary Canvas (65-70%)**: Multi-chair appointment schedule, weekly timetable, client rosters, and financial performance.
   - **Live Intelligence Rail (30-35%)**: Dynamic simulation pane displaying live customer WhatsApp booking dialogues, real-time AI negotiation states, and pending override requests.
2. **Breakpoints & Adaptation**:
   - **Desktop (1280px+)**: Dual-pane grid active with pinned right-hand sidebar for navigation and floating intelligence panel.
   - **Tablet (768px - 1279px)**: Schedule collapses to a 3-day view; intelligence rail moves to an off-canvas drawer toggled via floating action indicator.
   - **Mobile (< 768px)**: Single-column view with bottom sticky navigation; calendar collapses to single-day vertical timeline with time-block chips.

## Elevation & Depth
Depth relies on warm ambient luminescence rather than generic neutral drop shadows:

- **Level 0 (Canvas Base)**: Flat `#FAF9F6`. No shadow.
- **Level 1 (Cards & Schedule Units)**: Layered with `#FFFFFF` background, a 1px border of `rgba(61, 38, 69, 0.06)`, and an ambient shadow: `0 4px 20px -2px rgba(61, 38, 69, 0.04)`.
- **Level 2 (Hovered Cards & Interactive Dropdowns)**: Lifted using `0 8px 24px -4px rgba(61, 38, 69, 0.08)` with a subtly warmed border tint (`rgba(217, 119, 127, 0.20)`).
- **Level 3 (Modals & Intelligence Feed Drawers)**: High-altitude glassmorphism overlay using `backdrop-filter: blur(12px)`, background `rgba(255, 255, 255, 0.88)`, and depth cast: `0 20px 40px -8px rgba(61, 38, 69, 0.16)`.
- **Active AI Ambient Glow**: Elements currently modified or monitored by the automated agent feature a breathing radial glow: `box-shadow: 0 0 0 1px rgba(78, 147, 122, 0.2), 0 0 16px 0 rgba(78, 147, 122, 0.12)`.

## Shapes
The shape language uses balanced curvature (`roundedness: 2`, base radius `0.5rem` / `8px`) to reflect cosmetic softness while retaining structural clarity in dense calendar grids:

- **Base Inputs & Small Badges**: `0.5rem` (8px) for comfortable form controls and tight status tags.
- **Standard Cards, Chat Bubbles, Modals**: `1rem` (16px) for client records, WhatsApp speech bubbles, and modal dialogues.
- **Action Pills & Micro-Toggles**: `9999px` (Full Pill) for filter buttons, calendar date switchers, and treatment category toggles.
- **WhatsApp Chat Asymmetry**: Client speech bubbles have rounded corners of `16px 16px 4px 16px`; AI outgoing bubbles use `16px 16px 16px 4px` to indicate conversational direction in RTL.

## Components

### Buttons
- **Primary**: Solid Dusty Rose (`#D9777F`) fill, `#FFFFFF` text. Hover state shifts to `#C96770` with soft vertical elevation (`0 4px 12px rgba(217, 119, 127, 0.25)`). Active state scales to `0.98`.
- **Secondary / Ghost**: Deep Plum (`#3D2645`) text with 1px border `rgba(61, 38, 69, 0.15)`. Hover fills with `rgba(61, 38, 69, 0.04)`.
- **AI Action Button**: Emerald-tinted button (`#4E937A`) with an inline sparkle icon on the right side of the label for RTL text flows.

### Status Chips & Badges
- Pill-shaped (`rounded-full`), padded `0.25rem 0.75rem`, set in `label-md`.
- **מאושר (Confirmed)**: Emerald text `#2D6A4F`, background `#EDF7F2`.
- **בהמתנה (Pending)**: Terracotta text `#C86146`, background `#FFF5EB`.
- **מבוטל (Canceled)**: Muted red text `#B84A39`, background `#FDF0EE`.
- **הועבר לטיפול אנושי (Human Handover)**: Deep mauve text `#5A3866`, background `#F4EEF7`, accompanied by an attention dot indicator.

### Input Fields
- Flat pearl background (`#FFFFFF`) with 1px border (`rgba(61, 38, 69, 0.12)`).
- RTL-native layout: Label, placeholder, and leading icons align to the right edge. Trailing action triggers (e.g., date pickers, clear icon) anchor to the left edge.
- Focus state switches border to Dusty Rose (`#D9777F`) and applies a subtle outer ring (`box-shadow: 0 0 0 3px rgba(217, 119, 127, 0.15)`).

### Dual-Perspective Panel (Owner Dashboard vs. WhatsApp Simulator)
- **Salon Management Card**: Structured white surface showing client name, cosmetic treatment type (e.g., טיפול פנים, עיצוב גבות), assigned staff member, time slot, and price tag.
- **WhatsApp Simulation Feed**: Encapsulated within a mobile mockup container with an emerald-tinted header (`#075E54` / `#128C7E`), displaying incoming customer messages and outgoing automated AI responses with time stamps and delivery checkmarks (`✓✓`). Includes a floating action bar for the salon owner to take over the conversation instantly.

### Calendar Grid Components
- **Time Columns**: Clean vertical lines with 15/30/60-minute interval markers in Deep Plum 30% opacity.
- **Slot Reservation Blocks**: Tinted cards matching the assigned specialist's assigned hue, bounded by a prominent right-hand colored accent border (4px) to respect RTL visual weight.