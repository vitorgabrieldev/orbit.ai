---
name: Orbital Precision
colors:
  surface: '#faf8ff'
  surface-dim: '#d2d9f4'
  surface-bright: '#faf8ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f2f3ff'
  surface-container: '#eaedff'
  surface-container-high: '#e2e7ff'
  surface-container-highest: '#dae2fd'
  on-surface: '#131b2e'
  on-surface-variant: '#464555'
  inverse-surface: '#283044'
  inverse-on-surface: '#eef0ff'
  outline: '#777587'
  outline-variant: '#c7c4d8'
  surface-tint: '#4d44e3'
  primary: '#3525cd'
  on-primary: '#ffffff'
  primary-container: '#4f46e5'
  on-primary-container: '#dad7ff'
  inverse-primary: '#c3c0ff'
  secondary: '#00687a'
  on-secondary: '#ffffff'
  secondary-container: '#57dffe'
  on-secondary-container: '#006172'
  tertiary: '#571ac0'
  on-tertiary: '#ffffff'
  tertiary-container: '#6f3dd9'
  on-tertiary-container: '#e3d5ff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e2dfff'
  primary-fixed-dim: '#c3c0ff'
  on-primary-fixed: '#0f0069'
  on-primary-fixed-variant: '#3323cc'
  secondary-fixed: '#acedff'
  secondary-fixed-dim: '#4cd7f6'
  on-secondary-fixed: '#001f26'
  on-secondary-fixed-variant: '#004e5c'
  tertiary-fixed: '#e9ddff'
  tertiary-fixed-dim: '#d0bcff'
  on-tertiary-fixed: '#23005c'
  on-tertiary-fixed-variant: '#5516be'
  background: '#faf8ff'
  on-background: '#131b2e'
  surface-variant: '#dae2fd'
typography:
  display-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 36px
    fontWeight: '700'
    lineHeight: 44px
    letterSpacing: -0.03em
  display-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 36px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 36px
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 22px
    fontWeight: '600'
    lineHeight: 28px
    letterSpacing: -0.015em
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 24px
    letterSpacing: -0.01em
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
    letterSpacing: -0.005em
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
    letterSpacing: 0em
  body-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 16px
    letterSpacing: 0em
  label-metric:
    fontFamily: JetBrains Mono
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.02em
  label-code:
    fontFamily: JetBrains Mono
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0em
  label-action:
    fontFamily: Plus Jakarta Sans
    fontSize: 13px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.01em
  label-badge:
    fontFamily: Plus Jakarta Sans
    fontSize: 11px
    fontWeight: '700'
    lineHeight: 14px
    letterSpacing: 0.04em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  space-2xs: 0.125rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 0.75rem
  space-base: 1rem
  space-lg: 1.5rem
  space-xl: 2rem
  space-2xl: 3rem
  gutter-dashboard: 1.5rem
  sidebar-rail-width: 4.5rem
  sidebar-expanded-width: 16rem
  copilot-drawer-width: 26rem
---

## Brand & Style

This design system establishes an intelligent, high-velocity operational command surface for mission-critical enterprise environments. The aesthetic converges **Modern Enterprise Functionalism** with **Cosmic Subtlety**—balancing the utilitarian density demanded by executive data analysis with the kinetic, luminous polish of generative AI.

The personality balances four distinct attributes:
- **Surgical Precision**: Data-first typography, micro-borders, and disciplined alignment communicate unyielding stability and accuracy.
- **Ambient Intelligence**: AI copilot surfaces feel distinct yet integrated, using restrained prismatic cyan-violet gradients and soft interior luminosity rather than intrusive novelty.
- **Operational Breathability**: Generous micro-rhythms prevent sensory fatigue across complex 12-column analytical dashboards.
- **Structural Contrast**: A dark-anchored workspace rail (slate obsidian) grounds the interface, framing ultra-crisp, high-efficiency light slate work surfaces.

## Colors

The palette employs an architectural tonal model optimized for data density, enterprise trust, and contextual AI highlights.

### Core Architecture
- **Primary (`#4F46E5` / `#4338CA`)**: The authoritative brand anchor. Applied strictly to primary commitment actions, selected states, and core navigational affordances.
- **Secondary (`#06B6D4`) & Tertiary (`#8B5CF6`)**: The generative AI and telemetry spectrum. Reserved exclusively for AI Copilot interfaces, predictive metrics, vector queries, and automated workflows. These may merge via linear gradient `135deg, #8B5CF6 0%, #06B6D4 100%`.
- **Neutral Base (`#0F172A`)**: The slate obsidian tone utilized for persistent navigation panels, dark contextual tooltips, and deep telemetry views.

### Functional Surface Token Rules
- **Canvas Base**: Light mode canvas rests on `#F8FAFC`, while elevated workspace cards sit on pure `#FFFFFF`.
- **Structural Borders**: Card edges and table delimiters utilize `#E2E8F0` with deliberate `1px` crispness. Secondary dividers use `#F1F5F9`.
- **Operational Status**:
  - **Success / Healthy**: Emerald `#10B981` (Surface: `#ECFDF5`, Border: `#A7F3D0`) for active telemetry syncs and positive delta KPIs.
  - **Warning / Pending**: Amber `#F59E0B` (Surface: `#FFFBEB`, Border: `#FDE68A`) for integration latency and pending reviews.
  - **Critical / Interrupted**: Rose `#EF4444` (Surface: `#FEF2F2`, Border: `#FECACA`) for data pipeline failures.

## Typography

Typography prioritizes tabular clarity and structural density. `Plus Jakarta Sans` delivers a clean, geometric humanism suited for analytical interfaces, while `JetBrains Mono` provides optical alignment across high-throughput data tables and financial KPI values.

### Formatting Rules
- **Tabular Alignment**: All numbers inside data tables, trend badges, and KPI values must enforce CSS `font-variant-numeric: tabular-nums lining-nums`.
- **Information Hierarchy**: Never use font weight to solve poor hierarchy alone. Rely on tone shifting (`#0F172A` primary text, `#64748B` secondary text, `#94A3B8` tertiary captions).
- **Label Capitalization**: `label-badge` tokens are strictly styled with uppercase transformation and tracking expansion (`0.04em`).

## Layout & Spacing

This design system uses a deterministic **8pt mathematical grid** with a nested **4pt sub-grid** dedicated to dense component internals (badges, input paddings, table cells).

### Spatial Architecture
- **Multi-Tenant Global Sidebar**: Fixed position rail on the left. Collapsible between `sidebar-rail-width` (72px) and `sidebar-expanded-width` (256px).
- **Executive Viewport**: 12-column fluid grid system pinned to a maximum container width of `1680px`. Column gutters hold rigidly at `1.5rem` (`24px`).
- **AI Copilot Overlay**: Anchored right-side floating drawer spanning `copilot-drawer-width` (416px) with an edge-offset of `1.5rem`, preventing canvas occlusion via automatic main stage contraction.

### Breakpoint Matrix
- **Desktop Wide (≥1440px)**: 12-column standard canvas with persistent copilot and expanded telemetry.
- **Desktop (1024px - 1439px)**: 12-column grid, AI Copilot transforms into an overlay slide-out; dashboard cards re-stack from 4 columns to 2 columns.
- **Tablet / Mobile (<1023px)**: Grid collapses to single or double columns. The global navigation folds into a bottom-sheet action bar.

## Elevation & Depth

Visual depth is achieved through **low-contrast boundary rings paired with ultra-diffused atmospheric shadows**, steering clear of heavy drop shadows to preserve enterprise cleanliness.

### Depth Layers
1. **Canvas Tier (Elevation 0)**: `#F8FAFC`. Zero elevation. Default background for operational workspaces.
2. **Surface Tier (Elevation 1)**: White `#FFFFFF` cards wrapped in a hairline stroke: `box-shadow: 0 0 0 1px rgba(15, 23, 42, 0.06), 0 1px 2px -1px rgba(15, 23, 42, 0.08)`.
3. **Elevated / Hover Tier (Elevation 2)**: Dynamic cards and data widgets upon focus or hover: `box-shadow: 0 0 0 1px rgba(99, 102, 241, 0.12), 0 10px 15px -3px rgba(15, 23, 42, 0.05), 0 4px 6px -4px rgba(15, 23, 42, 0.03)`.
4. **Floating Popover & Copilot (Elevation 3)**: Dropdowns, contextual menus, and workspace switchers: `box-shadow: 0 0 0 1px rgba(15, 23, 42, 0.08), 0 20px 25px -5px rgba(15, 23, 42, 0.08), 0 8px 10px -6px rgba(15, 23, 42, 0.03)`.

### Copilot Luminous Depth
AI surfaces utilize an ambient halo technique: an underlying radial blurred aura (`filter: blur(40px)`) tinted with `rgba(139, 92, 246, 0.12)` and `rgba(6, 182, 212, 0.08)` to communicate contextual computing presence without harsh barriers.

## Shapes

The design system standardizes on a modern, refined curved geometry (`roundedness: 2`). Radii scale proportionally with component volume to ensure geometric harmony:

- **Micro Radii (4px - 6px)**: Checkboxes, table tags, micro progress bars, and status indicators.
- **Component Radii (`0.5rem` / 8px)**: Standard buttons, text inputs, dropdown triggers, and integration badges.
- **Card & Surface Radii (`1rem` / 16px)**: KPI cards, analytical charts, integration connector tiles, and document previews.
- **Container / Drawer Radii (`1.5rem` / 24px)**: Outer workspace switchers, modal dialogues, and the AI Copilot side-drawer frame.
- **Pill Geometry (`9999px`)**: Copilot quick-prompt triggers, online sync indicator dots, and interactive filter pills.

## Components

### Buttons
- **Primary**: Solid `#4F46E5` background, text `#FFFFFF`, radius `8px`, height `36px` (compact) or `40px` (standard). Hover: `#4338CA`. Active state scales subtly (`scale(0.98)`).
- **AI Action Variant**: Gradient background (`linear-gradient(135deg, #4F46E5, #7C3AED)`), white text, with an inline micro-sparkle icon.
- **Secondary / Ghost**: Neutral surface `#FFFFFF`, border `1px solid #E2E8F0`, text `#1E293B`. Hover: `#F8FAFC` background with border `#CBD5E1`.

### KPI & Metric Cards
- White `#FFFFFF` card with `16px` radius and `1px solid #E2E8F0` border.
- Layout: Top row accommodates metric label (`body-sm`) and contextual menu or time-range selector. Middle row contains `label-metric` tabular numerical value. Bottom row accommodates a status badge (`+12.4% vs last week`) paired with a dynamic micro-sparkline.

### Integration Connector Cards
- Outer structural container with an inner `48px` rounded integration brand avatar box.
- Features a top-right real-time status pill:
  - Green pulse indicator for `Healthy` / `Synced`.
  - Amber dot for `Delayed Sync` (with latency value in `JetBrains Mono`).
- Bottom zone contains a two-column distribution: Last sync timestamp and an inline toggle switch.

### AI Copilot Drawer & Pill
- **Docked Search / Prompt Bar**: Pill-shaped (`9999px`) container sitting above the bottom canvas edge. Subtle multi-color internal ring: `border: 1px solid rgba(139, 92, 246, 0.4)`.
- **Copilot Side-Drawer**: Frosted panel with `rgba(255, 255, 255, 0.95)` fill and `backdrop-filter: blur(12px)`. AI responses feature a gentle left border line with a cyan-to-violet vertical gradient.

### Multi-Tenant Workspace Switcher
- Placed in the top-left sidebar node. Trigger features a double-stacked monogram icon, active workspace name, organization tier badge (`Enterprise`), and a vertical chevron icon.
- Expands to a floating popover displaying active tenant context with direct switching, tenant creation affordances, and domain sync metadata.

### Form Inputs & Checkboxes
- **Input Fields**: Height `40px`, background `#FFFFFF`, border `1px solid #CBD5E1`, text `#0F172A`. Focused state: border `#4F46E5` and an exterior focus halo `0 0 0 3px rgba(79, 70, 229, 0.15)`.
- **Checkboxes**: Dimension `18x18px`, `4px` radius. Active state: `#4F46E5` fill with pure white path checkmark.