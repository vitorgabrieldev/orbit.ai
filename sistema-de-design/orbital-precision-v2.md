---
name: Orbital Precision
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
  on-surface-variant: '#464555'
  inverse-surface: '#213145'
  inverse-on-surface: '#eaf1ff'
  outline: '#777587'
  outline-variant: '#c7c4d8'
  surface-tint: '#4d44e3'
  primary: '#3525cd'
  on-primary: '#ffffff'
  primary-container: '#4f46e5'
  on-primary-container: '#dad7ff'
  inverse-primary: '#c3c0ff'
  secondary: '#006591'
  on-secondary: '#ffffff'
  secondary-container: '#39b8fd'
  on-secondary-container: '#004666'
  tertiary: '#005338'
  on-tertiary: '#ffffff'
  tertiary-container: '#006e4b'
  on-tertiary-container: '#67f4b7'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e2dfff'
  primary-fixed-dim: '#c3c0ff'
  on-primary-fixed: '#0f0069'
  on-primary-fixed-variant: '#3323cc'
  secondary-fixed: '#c9e6ff'
  secondary-fixed-dim: '#89ceff'
  on-secondary-fixed: '#001e2f'
  on-secondary-fixed-variant: '#004c6e'
  tertiary-fixed: '#6ffbbe'
  tertiary-fixed-dim: '#4edea3'
  on-tertiary-fixed: '#002113'
  on-tertiary-fixed-variant: '#005236'
  background: '#f8f9ff'
  on-background: '#0b1c30'
  surface-variant: '#d3e4fe'
typography:
  display-xl:
    fontFamily: Hanken Grotesk
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Hanken Grotesk
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.015em
  headline-lg-mobile:
    fontFamily: Hanken Grotesk
    fontSize: 26px
    fontWeight: '600'
    lineHeight: 34px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Hanken Grotesk
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Hanken Grotesk
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 24px
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
  body-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 16px
  label-md:
    fontFamily: JetBrains Mono
    fontSize: 13px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.01em
  label-sm:
    fontFamily: JetBrains Mono
    fontSize: 11px
    fontWeight: '500'
    lineHeight: 14px
    letterSpacing: 0.02em
  caption:
    fontFamily: Inter
    fontSize: 11px
    fontWeight: '500'
    lineHeight: 14px
    letterSpacing: 0.01em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  canvas-width: 1920px
  gutter-xs: 4px
  gutter-sm: 8px
  gutter-md: 16px
  gutter-lg: 24px
  gutter-xl: 32px
  margin-page: 32px
  col-gap: 16px
---

## Brand & Style

This design system targets high-velocity enterprise operators, systems architects, and executive teams navigating complex data topologies. The aesthetic is engineered, rigorous, and restrained—blending modern enterprise clarity with mathematical density.

- **Movement:** Technical Minimalism and Structured Enterprise Modernism.
- **Tone:** Methodical, high-fidelity, architectural, precise.
- **Emotional Response:** Complete operational command, high cognitive bandwidth, zero clutter.
- **Visual Tenets:** Compact geometry, strict perimeter controls, crisp borders, high-density layouts configured for wide-gamut monitors (1920px canvas).

## Colors

The palette leverages a focused indigo anchor paired with slate neutrals to maintain strict visual ergonomics under heavy analytical workloads.

- **Primary (`#4f46e5`):** Reserved for primary actions, focused operational states, active telemetry highlights, and vital breadcrumbs.
- **Secondary (`#0ea5e9`):** Diagnostic metrics, auxiliary links, and secondary interactive accents.
- **Tertiary (`#10b981`):** Production health checks, verified statuses, and nominal system indicators.
- **Neutrals (Slate spectrum):**
  - Surface Foundation: `#f8fafc` (Canvas background)
  - Surface Card/Panel: `#ffffff`
  - Border Muted: `#e2e8f0`
  - Border Structural: `#cbd5e1`
  - Text Primary: `#0f172a`
  - Text Secondary: `#475569`
  - Text Muted: `#94a3b8`

Color is used sparingly as structural metadata rather than decoration. Interactive states rely on subtle step transitions rather than dramatic color washes.

## Typography

Typography establishes an unambiguous technical hierarchy:

- **Hanken Grotesk** commands headlines and modal framing, delivering sharp modern enterprise presence without consumer-grade roundness.
- **Inter** provides neutral, high-density legibility for multi-column grids, form fields, and documentation panels.
- **JetBrains Mono** surfaces system telemetry, code values, metric tags, status badges, and timestamp feeds.

Line heights are tightly budgeted to maximize vertical data density on large displays while preserving scannability.

## Layout & Spacing

The canvas is engineered specifically for **1920px** wide enterprise displays.

- **Primary Canvas Grid:** Fixed 1920px boundary wrapper (`max-w-[1920px] mx-auto`) structured with a 16-column layout on wide screens, dropping to 12 columns at smaller desktop viewports.
- **Rhythm:** Standard 8pt base grid with a 4px half-step for micro-alignment within inputs and badges.
- **Margins & Gutters:**
  - Exterior horizontal margin: `32px`
  - Grid column gutters: `16px`
  - Vertical pane distribution: Multi-split horizontal viewports (e.g., 280px persistent sidebar, dynamic workspace canvas, optional 360px contextual telemetry drawer).
- **Responsive Adaptations:**
  - **1920px (Target Desktop):** Full multi-panel layout enabled side-by-side with no tabbed collapse required.
  - **1440px - 1680px:** Collapsible inspector drawers, fluid middle data grid.
  - **1024px - 1280px:** Sidebar collapses to icon mode (64px width); secondary panels shift to flyovers.
  - **Mobile (<768px):** Linear stacked view with drawer navigations and compressed `headline-lg-mobile` treatments.

## Elevation & Depth

This system intentionally eliminates atmospheric and diffuse shadows. Depth is communicated strictly via tonal surface shifts and micro-borders:

- **Surface Tiers:**
  - Level 0 (Canvas): `#f8fafc`
  - Level 1 (Panels & Cards): `#ffffff` with a mandatory `1px solid #e2e8f0` border.
  - Level 2 (Flyouts & Dropdowns): `#ffffff` with `1px solid #cbd5e1` and a hyper-subtle directional cast: `0px 2px 4px -1px rgba(15, 23, 42, 0.06), 0px 4px 6px -1px rgba(15, 23, 42, 0.04)`.
  - Level 3 (Modals): `#ffffff` with `1px solid #94a3b8` and `0px 8px 16px -4px rgba(15, 23, 42, 0.08)`.
- **Zero Glassmorphism:** No backdrop blur or translucency. Interfaces maintain 100% opacity for instant legibility and rendering performance.

## Shapes

To sustain strict enterprise precision, soft rounded visual tropes are forbidden. The design system enforces hard caps on curvature:

- **Strict Radius Enforcement:** Only three border radius values exist across the entire token pipeline:
  - **`4px` (Subtle):** Exclusively for status badges, metric pills, chip elements, tooltips, and table row selection indicators.
  - **`6px` (Interactive):** Form controls, inputs, textareas, selects, and standard action buttons.
  - **`8px` (Container):** Maximum allowable radius across the entire system. Used exclusively for cards, dialog modals, flyout menus, and structural workspace panels.
- **Prohibited:** Any usage of `rounded-lg` (12px+), `rounded-xl`, `rounded-2xl`, `rounded-3xl`, or `rounded-full` is strictly disallowed.

## Components

### Buttons
- **Shape & Geometry:** Radius strictly `6px`. Height standard: `36px` (Default), `32px` (Compact / Table action).
- **Primary:** Background `#4f46e5`, text `#ffffff`, border `1px solid transparent`. Hover: `#4338ca`. Active: `#3730a3`.
- **Secondary:** Background `#ffffff`, text `#0f172a`, border `1px solid #cbd5e1`. Hover: Background `#f1f5f9`.
- **Destructive:** Background `#ffffff`, text `#dc2626`, border `1px solid #fca5a5`. Hover: Background `#fef2f2`.

### Chips, Tags & Badges
- **Shape & Geometry:** Radius strictly `4px`. Never pill-shaped or rounded-full.
- **Typography:** `label-sm` (JetBrains Mono, 11px, 500 weight).
- **Colors:** Low-saturation backgrounds with high-contrast text (e.g., `#e0e7ff` with `#3730a3` text for primary tags; `#ecfdf5` with `#065f46` for operational metrics). Border `1px solid currentColor` at 20% opacity.

### Input Fields & Controls
- **Shape & Geometry:** Radius strictly `6px`. Height `36px`.
- **Structure:** Surface `#ffffff`, border `1px solid #cbd5e1`, font `body-md`. Focus state: border `#4f46e5` with `0 0 0 1px #4f46e5` ring (no diffuse glow).
- **Checkboxes & Radios:**
  - Checkbox: `16px x 16px`, radius `4px`, border `1px solid #94a3b8`. Checked: `#4f46e5`.
  - Radio: `16px x 16px`, standard circle allowed only for the fundamental radio icon standard, or styled as a `4px` segmented square toggle.

### Cards, Modals & Workspace Panels
- **Shape & Geometry:** Radius strictly `8px`.
- **Surface Treatment:** `#ffffff` background with `1px solid #e2e8f0`. Header sections separated by `1px solid #f1f5f9`.
- **Padding:** Compact `16px` on utility widgets; structured `24px` on canvas-grade workspace blocks.

### Tables & Dense Grids
- Flat rows with bottom borders (`1px solid #f1f5f9`), row height `40px`, active/selected state highlighted with a `2px` left border in `#4f46e5` on a `#f8fafc` row background.