---
name: Lumina Engineering
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
  secondary: '#0051d5'
  on-secondary: '#ffffff'
  secondary-container: '#316bf3'
  on-secondary-container: '#fefcff'
  tertiary: '#004d70'
  on-tertiary: '#ffffff'
  tertiary-container: '#006693'
  on-tertiary-container: '#b8e0ff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e2dfff'
  primary-fixed-dim: '#c3c0ff'
  on-primary-fixed: '#0f0069'
  on-primary-fixed-variant: '#3323cc'
  secondary-fixed: '#dbe1ff'
  secondary-fixed-dim: '#b4c5ff'
  on-secondary-fixed: '#00174b'
  on-secondary-fixed-variant: '#003ea8'
  tertiary-fixed: '#c9e6ff'
  tertiary-fixed-dim: '#89ceff'
  on-tertiary-fixed: '#001e2f'
  on-tertiary-fixed-variant: '#004c6e'
  background: '#f8f9ff'
  on-background: '#0b1c30'
  surface-variant: '#d3e4fe'
typography:
  headline-xl:
    fontFamily: Space Grotesk
    fontSize: 56px
    fontWeight: '600'
    lineHeight: 64px
  headline-xl-mobile:
    fontFamily: Space Grotesk
    fontSize: 36px
    fontWeight: '600'
    lineHeight: 44px
  headline-lg:
    fontFamily: Space Grotesk
    fontSize: 40px
    fontWeight: '600'
    lineHeight: 48px
  headline-lg-mobile:
    fontFamily: Space Grotesk
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 36px
  headline-md:
    fontFamily: Space Grotesk
    fontSize: 28px
    fontWeight: '500'
    lineHeight: 36px
  headline-sm:
    fontFamily: Space Grotesk
    fontSize: 20px
    fontWeight: '500'
    lineHeight: 28px
  body-lg:
    fontFamily: Geist
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Geist
    fontSize: 15px
    fontWeight: '400'
    lineHeight: 24px
  body-sm:
    fontFamily: Geist
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 20px
  label-md:
    fontFamily: JetBrains Mono
    fontSize: 13px
    fontWeight: '500'
    lineHeight: 18px
  label-sm:
    fontFamily: JetBrains Mono
    fontSize: 11px
    fontWeight: '500'
    lineHeight: 16px
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  gutter: 1.5rem
  margin: 2rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

This design system expresses a sharp, elevated minimalist aesthetic tailored for a high-caliber creative technologist and full-stack engineer. The visual tone balances technical precision with editorial poise, presenting engineering rigor through pristine layout discipline, generous negative space, and typographic restraint. 

The interface should feel architectural, high-performance, and deeply intentional. Rather than relying on loud ornamentation or heavy textures, the UI leverages bright canvas surfaces, razor-sharp vector details, subtle translucent layers, and high-clarity typography. It projects effortless authority, modern sophistication, and craft.

## Colors

The palette establishes an ultra-clean, luminous canvas anchored by slate and charcoal tones, punctuated by royal indigo and electric blue accents.

- **Canvas & Surfaces:** Primary background uses a crisp slate tint `#F8FAFC`, while elevated surfaces and card containers sit on pure `#FFFFFF`. Subtle secondary surface fills utilize `#F1F5F9`.
- **Text & Foreground:** High-contrast legibility is maintained with deep charcoal `#0F172A` for primary headlines and critical metrics, followed by slate `#334155` for body text, and `#64748B` for tertiary captions or inactive states.
- **Accents & Interactions:** Royal Indigo (`#4F46E5`) serves as the signature brand anchor for focal actions, key project tags, and active states. Electric Blue (`#2563EB`) provides interactive vibrance for links, hover transitions, and technical indicators. Sky Blue (`#0EA5E9`) provides precise telemetry highlights and system badges.
- **Borders & Dividers:** Borders avoid heavy outlines, relying instead on diffused, low-contrast slate tints (`#E2E8F0` at 1px solid, or `rgba(15, 23, 42, 0.06)`).

## Typography

The typography system unites technical authority with contemporary design elegance across three specialized typefaces:

- **Headlines (Space Grotesk):** Provides structured geometric personality with a modern digital edge. Large titles set an authoritative, forward-thinking presence while maintaining clean letterforms.
- **Body & Prose (Geist):** Serves as the primary workhorse for case studies, bio summaries, and deep technical write-ups. Its neutral, engineered proportions deliver effortless readability across varying density levels.
- **Labels, Telemetry & Code (JetBrains Mono):** Dedicated to technical metadata, commit hashes, technology tags, architectural diagrams, and micro-labels. Tight, precise, and unmistakably engineered.

## Layout & Spacing

The layout is built around a structured 12-column responsive fluid grid with a maximum content container width of 1280px.

- **Breakpoints & Grids:**
  - **Desktop (≥ 1024px):** 12 columns, 24px gutters, 32px safe margins. Focuses on asymmetry, offset case-study layouts, and wide interactive viewports.
  - **Tablet (768px – 1023px):** 8 columns, 20px gutters, 24px safe margins. Two-column card arrangements and collapsed side-rails.
  - **Mobile (< 768px):** 4 columns, 16px gutters, 16px safe margins. Single-column stacks with fluid full-width cards and horizontal scrolling tag rails.
- **Vertical Rhythm:** Content sections are spaced generously using increments of 40px (`space-xl`), 64px, and 96px to allow technical artifacts and portfolio imagery to breathe without feeling sparse.

## Elevation & Depth

This design system avoids heavy skeuomorphic drop shadows, utilizing crisp atmospheric elevation combined with soft, low-contrast boundary lines.

- **Level 0 (Flat Canvas):** `#F8FAFC` base surface with no shadow.
- **Level 1 (Card & Modular Surfaces):** Pure `#FFFFFF` background with a hairline border (`1px solid #E2E8F0`) and an ambient, slate-tinted shadow: `0 1px 3px rgba(15, 23, 42, 0.04), 0 4px 12px rgba(15, 23, 42, 0.03)`.
- **Level 2 (Hovered Cards & Interactive Triggers):** Subtle upward translation (`translateY(-2px)`) accompanied by an expanded, low-opacity drop shadow: `0 8px 24px rgba(79, 70, 229, 0.06), 0 2px 6px rgba(15, 23, 42, 0.04)`.
- **Level 3 (Modals, Overlays, Floating Navbars):** Translucent frosted glass effect using `rgba(255, 255, 255, 0.85)` with `backdrop-filter: blur(12px)`, bordered by `rgba(226, 232, 240, 0.8)`, and an elevated diffuse shadow: `0 16px 40px -8px rgba(15, 23, 42, 0.08)`.

## Shapes

The design system adopts a soft, controlled geometry (`roundedness: 1`). 

- **Base Radii:** Standard interactive components (buttons, text inputs, chips) feature a crisp `0.25rem` (4px) or `0.5rem` (8px for `rounded-lg`) corner radius. 
- **Panels & Cards:** Outer card boundaries and project modules use `0.5rem` to `0.75rem` (8px to 12px) radii, retaining an architectural, precise perimeter that avoids overly bubbly curves.
- **Interactive Badges:** Micro-labels and status indicators use fully circular pills (`rounded-full`) to contrast against the structured grid elements.

## Components

- **Buttons:**
  - *Primary:* Solid `#4F46E5` fill with `#FFFFFF` text, subtle 1px border (`#4338CA`), and sharp 6px radius. On hover, transitions to `#2563EB` with a soft blue ambient glow.
  - *Secondary / Outlined:* Pure `#FFFFFF` fill, 1px border (`#E2E8F0`), `#0F172A` text. On hover, background shifts to `#F8FAFC` with border darkening to `#CBD5E1`.
  - *Ghost / Minimal:* Transparent surface with `#334155` text and monospaced trailing icon. On hover, background shifts to `rgba(79, 70, 229, 0.06)` with text color switching to `#4F46E5`.
- **Chips & Tech Stack Badges:**
  - Compact badges using `label-sm` font (`JetBrains Mono`). Rendered with `#F1F5F9` surface, 1px border in `#E2E8F0`, and text in `#334155`. Interactive filter chips highlight into royal indigo borders with tinted indigo backgrounds (`#EEF2FF`).
- **Cards & Project Artifacts:**
  - Grounded on `#FFFFFF` with a 1px border (`#E2E8F0`) and 8px border radius. Case study cards display an engineered layout: mono metadata headers, high-fidelity project preview, Space Grotesk headline, and Geist body summary.
- **Form Inputs & Search:**
  - Clean `#FFFFFF` fill with 1px border (`#CBD5E1`), 6px radius, and `#0F172A` input text. Focus state employs a crisp double boundary: a 1px `#4F46E5` line with an outer 3px ring of `rgba(79, 70, 229, 0.15)`.
- **Lists & Timeline Elements:**
  - Minimal horizontal borders (`#E2E8F0`) between items. Career and project milestones feature a vertical monospaced timeline spine with active state nodes lit in Electric Blue (`#2563EB`).
- **Terminal & Code Blocks:**
  - Framed in an ultra-crisp slate container (`#0F172A` or light variant `#F8FAFC`), paired with syntax highlighting tuned to Royal Indigo and Electric Blue, rendered in `JetBrains Mono` at `body-sm`.