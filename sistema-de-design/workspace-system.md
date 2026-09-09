---
name: Orbit Workspace System
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
  surface-tint: '#4c4ad6'
  primary: '#1f0faf'
  on-primary: '#ffffff'
  primary-container: '#3a35c4'
  on-primary-container: '#b8b8ff'
  inverse-primary: '#c2c1ff'
  secondary: '#712edd'
  on-secondary: '#ffffff'
  secondary-container: '#8b4ef7'
  on-secondary-container: '#fffbff'
  tertiary: '#003c48'
  on-tertiary: '#ffffff'
  tertiary-container: '#005564'
  on-tertiary-container: '#40ceed'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e2dfff'
  primary-fixed-dim: '#c2c1ff'
  on-primary-fixed: '#0b006b'
  on-primary-fixed-variant: '#332cbe'
  secondary-fixed: '#ebddff'
  secondary-fixed-dim: '#d3bbff'
  on-secondary-fixed: '#250059'
  on-secondary-fixed-variant: '#5b00c5'
  tertiary-fixed: '#acedff'
  tertiary-fixed-dim: '#4cd7f6'
  on-tertiary-fixed: '#001f26'
  on-tertiary-fixed-variant: '#004e5c'
  background: '#f8f9ff'
  on-background: '#0b1c30'
  surface-variant: '#d3e4fe'
typography:
  headline-xl:
    fontFamily: Sora
    fontSize: 36px
    fontWeight: '700'
    lineHeight: 44px
    letterSpacing: -0.03em
  headline-xl-mobile:
    fontFamily: Sora
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 36px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Sora
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 36px
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Sora
    fontSize: 22px
    fontWeight: '600'
    lineHeight: 30px
    letterSpacing: -0.015em
  headline-md:
    fontFamily: Sora
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Sora
    fontSize: 16px
    fontWeight: '600'
    lineHeight: 24px
    letterSpacing: -0.005em
  body-lg:
    fontFamily: Sora
    fontSize: 15px
    fontWeight: '400'
    lineHeight: 24px
    letterSpacing: 0em
  body-md:
    fontFamily: Sora
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 20px
    letterSpacing: 0.005em
  body-sm:
    fontFamily: Sora
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 18px
    letterSpacing: 0.01em
  label-lg:
    fontFamily: Sora
    fontSize: 13px
    fontWeight: '600'
    lineHeight: 18px
    letterSpacing: 0.01em
  label-md:
    fontFamily: Sora
    fontSize: 11px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.03em
  label-sm:
    fontFamily: Sora
    fontSize: 10px
    fontWeight: '600'
    lineHeight: 14px
    letterSpacing: 0.04em
  code-md:
    fontFamily: JetBrains Mono
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 18px
    letterSpacing: 0em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  pad-xs: 10px
  pad-sm: 12px
  pad-md: 14px
  pad-lg: 18px
  space-4: 4px
  space-8: 8px
  space-16: 16px
  space-20: 20px
  space-24: 24px
  space-32: 32px
  space-48: 48px
  gutter-desktop: 24px
  margin-desktop: 32px
  gutter-mobile: 14px
  margin-mobile: 14px
---

## Brand & Style
This design system is tailored for an enterprise workspace platform where clarity, density management, and technical confidence converge. The aesthetic draws from high-precision modernism and refined architectural computing interfaces, pairing absolute geometric discipline with subtle cosmic vitality.

Key attributes:
- **Tone:** Authoritative, razor-sharp, forward-looking, and effortlessly organized.
- **Target Audience:** Cross-functional enterprise teams, engineering leadership, and product operators handling intricate data flows and high-context workflows.
- **Emotional Response:** Uncluttered mental clarity, systematic trust, and seamless operational flow.
- **Visual Stance:** Clean, illuminated light mode dominated by crisp neutral tones, elevated by modern deep indigo structure, cosmic violet contextual accents, and precise cyan triggers indicating AI-driven features.

## Colors
The palette balances daylight clarity with deliberate technical accents. Surface tones rely on cool-white structural canvas layers, preventing visual fatigue in data-dense productivity environments.

- **Primary (`#3A35C4` - Deep Orbit Indigo):** Powers high-emphasis interactive states, primary action keys, active tab indicators, and foundational brand cues.
- **Secondary (`#6D28D9` - Cosmic Violet):** Designates structural grouping, project status tags, context switching, and specialized collaboration indicators.
- **Tertiary (`#06B6D4` - Cosmic Cyan AI):** Reserved exclusively for autonomous features, automated completions, intelligent suggestions, and synthetic data insights.
- **Neutrals (`#0F172A` Slate Base through `#F8FAFC` Canvas):** Systemic hierarchy relies on `#0F172A` for primary text, `#475569` for secondary metadata, `#CBD5E1` for delicate hairline borders, and `#F8FAFC` as the foundational background plane.
- **Semantic Feedback:** Success states lean toward `#059669`, warnings settle at `#D97706`, and destructive workflows deploy `#DC2626`.

## Typography
The system uses **Sora** across display, body, and label roles to unify geometric precision and readability. Its distinct counter-forms ensure legibility even at dense metadata sizes.

- **Scale & Rhythm:** Typography is tuned to strict optical sizes. Body sizes feature slightly relaxed line heights to promote scanability across complex multi-column boards and document surfaces.
- **Numbers & Metrics:** Tabular figures (`tnum`) must be enforced for all data grids, financial totals, execution counters, and progress meters.
- **Code & Syntax:** Inline expressions, command terminal blocks, and query identifiers leverage **JetBrains Mono** to maintain a crisp technical tone alongside Sora.

## Layout & Spacing
Layouts follow a fluid-responsive 12-column grid system paired with strict inner-component padding tokens: **10px, 12px, 14px, and 18px**.

- **Padding Philosophy:**
  - `10px`: Compact controls, contextual menus, tooltips, nested badges, and tight table cells.
  - `12px`: Standard form inputs, compact list items, and segment headers.
  - `14px`: Default buttons, floating panels, and standard data cells.
  - `18px`: Primary card body padding, flyout modals, and summary module tiles.
- **Grid Structure:**
  - **Desktop (>= 1280px):** 12 columns with 24px gutters and 32px safe margins. Layout leverages fluid dashboard work areas bounded by fixed 240px utility sidebars.
  - **Tablet (768px - 1279px):** 8 columns with 18px gutters and 24px margins. Navigation collapses to an icon rail or off-canvas drawer.
  - **Mobile (< 768px):** 4 columns with 14px gutters and 14px margins. Complex multi-pane panels collapse into tabbed cards.
- **Card Spacing Rhythm:** Cards maintain an outer separation gap of 16px or 20px, creating breathing space against the compact interior paddings.

## Elevation & Depth
Depth is constructed through subtle structural hairline borders combined with soft ambient light separation. Heavy drop shadows are omitted in favor of clean edge definition.

- **Surface Baseline:** `#FFFFFF` resting on `#F8FAFC` background.
- **Border Architecture:** All panels, cards, and interactive controls apply a 1px solid border using `#E2E8F0` (`rgba(226, 232, 240, 0.85)`).
- **Ambient Shadow Levels:**
  - **Level 0 (Flat):** Resting panels, canvas items, and table rows. Defined strictly by 1px stroke (`#E2E8F0`).
  - **Level 1 (Card Rest):** `0 1px 3px 0 rgba(15, 23, 42, 0.04), 0 1px 2px -1px rgba(15, 23, 42, 0.02)`.
  - **Level 2 (Hover / Active):** `0 4px 12px -2px rgba(58, 53, 196, 0.06), 0 2px 6px -1px rgba(15, 23, 42, 0.04)`.
  - **Level 3 (Overlay / Modal / Menu):** `0 12px 28px -4px rgba(15, 23, 42, 0.08), 0 4px 10px -2px rgba(15, 23, 42, 0.03)`.
- **AI Glowing Elevation:** When AI states are triggered, cyan glow accents replace neutral outlines with `box-shadow: 0 0 0 1px #06B6D4, 0 4px 16px rgba(6, 182, 212, 0.15)`.

## Shapes
Geometry is bounded strictly by three micro-radii to maintain an architectural, technical edge: **4px, 6px, and 8px**.

- **`4px` (Micro/Inner elements):** Checkbox boxes, radio focus rings, tags, mini chips, breadcrumbs, inner button icons, and tooltips.
- **`6px` (Interactive elements):** Default buttons, input fields, dropdown trigger buttons, tab items, and segment controllers.
- **`8px` (Containers & Sheets):** Main cards, modal dialogues, floating action sheets, side panels, and popover menus.
- **Rule of Nesting:** If a child element resides inside an 8px card, its inner corner radius must not exceed 4px or 6px, preventing optical clipping and maintaining parallel curvature.

## Components

### Buttons
- **Primary:** Background `#3A35C4`, text `#FFFFFF`, border-radius `6px`, padding `10px 14px`. Hover: `#312E81`.
- **Secondary:** Background `#F1F5F9`, text `#0F172A`, border `1px solid #E2E8F0`, border-radius `6px`, padding `10px 14px`.
- **AI Action:** Background `linear-gradient(135deg, #3A35C4 0%, #06B6D4 100%)`, text `#FFFFFF`, border-radius `6px`, padding `10px 14px`.
- **Ghost/Tertiary:** Background transparent, text `#475569`, border-radius `6px`, padding `10px 12px`. Hover: `#F8FAFC`.

### Chips & Badges
- **Structure:** Height 24px, border-radius `4px`, padding `4px 10px`, font size `11px`, font weight `600`.
- **Status Types:** Neutral (`#F1F5F9` / `#475569`), Cosmic Violet (`#EDE9FE` / `#6D28D9`), Cyan AI (`#CFFAFE` / `#0E7490`).

### Input Fields & Controls
- **Input Fields:** Height 38px, border-radius `6px`, border `1px solid #CBD5E1`, padding `10px 12px`, background `#FFFFFF`. Active focus: outline `2px solid #3A35C4` with `2px` offset.
- **Checkboxes & Radios:** Outer dimension 16px x 16px, border-radius `4px` (checkbox) or circle (radio), active fill `#3A35C4`, check/dot color `#FFFFFF`.

### Cards & Surfaces
- **Specification:** Background `#FFFFFF`, border `1px solid #E2E8F0`, border-radius `8px`, body padding `18px`, Level 1 ambient elevation.
- **Card Header:** Separated by a 1px baseline border (`#F1F5F9`), padding-bottom `12px`, margin-bottom `14px`.

### Lists & Data Grids
- **Rows:** Height 44px, padding `10px 14px`, hairline divider `1px solid #F1F5F9`. Hover background `#F8FAFC`.
- **Headers:** Font size `11px`, font weight `600`, letter-spacing `0.03em`, text color `#64748B`, background `#F8FAFC`, uppercase transform.

### Iconography
- **Style:** 1.5px stroke width, geometric, non-filled outline icons matching Sora's geometry. Default bounding boxes: 16px (micro) and 20px (action).