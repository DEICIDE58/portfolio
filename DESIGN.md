---
name: Modern Technical Portfolio
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
  on-surface-variant: '#434655'
  inverse-surface: '#283044'
  inverse-on-surface: '#eef0ff'
  outline: '#737686'
  outline-variant: '#c3c6d7'
  surface-tint: '#0053db'
  primary: '#004ac6'
  on-primary: '#ffffff'
  primary-container: '#2563eb'
  on-primary-container: '#eeefff'
  inverse-primary: '#b4c5ff'
  secondary: '#006a61'
  on-secondary: '#ffffff'
  secondary-container: '#86f2e4'
  on-secondary-container: '#006f66'
  tertiary: '#0051b1'
  on-tertiary: '#ffffff'
  tertiary-container: '#0f69dc'
  on-tertiary-container: '#edf0ff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dbe1ff'
  primary-fixed-dim: '#b4c5ff'
  on-primary-fixed: '#00174b'
  on-primary-fixed-variant: '#003ea8'
  secondary-fixed: '#89f5e7'
  secondary-fixed-dim: '#6bd8cb'
  on-secondary-fixed: '#00201d'
  on-secondary-fixed-variant: '#005049'
  tertiary-fixed: '#d8e2ff'
  tertiary-fixed-dim: '#adc6ff'
  on-tertiary-fixed: '#001a42'
  on-tertiary-fixed-variant: '#004395'
  background: '#faf8ff'
  on-background: '#131b2e'
  surface-variant: '#dae2fd'
typography:
  display:
    fontFamily: Inter
    fontSize: 3.25rem
    fontWeight: '800'
    lineHeight: 3.75rem
    letterSpacing: -0.03em
  display-mobile:
    fontFamily: Inter
    fontSize: 2.25rem
    fontWeight: '800'
    lineHeight: 2.75rem
    letterSpacing: -0.025em
  headline-lg:
    fontFamily: Inter
    fontSize: 2.25rem
    fontWeight: '700'
    lineHeight: 2.75rem
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Inter
    fontSize: 1.75rem
    fontWeight: '700'
    lineHeight: 2.25rem
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Inter
    fontSize: 1.5rem
    fontWeight: '600'
    lineHeight: 2rem
    letterSpacing: -0.015em
  headline-sm:
    fontFamily: Inter
    fontSize: 1.25rem
    fontWeight: '600'
    lineHeight: 1.75rem
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
    lineHeight: 1.65rem
    letterSpacing: '0'
  body-sm:
    fontFamily: Inter
    fontSize: 0.875rem
    fontWeight: '400'
    lineHeight: 1.45rem
    letterSpacing: '0'
  label-md:
    fontFamily: Inter
    fontSize: 0.875rem
    fontWeight: '600'
    lineHeight: 1.25rem
    letterSpacing: 0.01em
  label-sm:
    fontFamily: Inter
    fontSize: 0.75rem
    fontWeight: '600'
    lineHeight: 1rem
    letterSpacing: 0.05em
  code:
    fontFamily: JetBrains Mono
    fontSize: 0.875rem
    fontWeight: '500'
    lineHeight: 1.5rem
    letterSpacing: '0'
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
---

## Brand & Style

This design system is tailored for an emerging Information Technology professional. It balances rigorous technical credibility with modern, polished product design sensibilities. The aesthetic avoids distracting decorative gimmicks in favor of crystal-clear structure, purposeful typographic hierarchy, and meticulous alignment.

### Target Audience & Tone
- **Audience:** Engineering managers, technical recruiters, startup founders, and academic peers evaluating technical acumen and interface craft.
- **Tone & Perception:** Capable, structured, forward-thinking, and reliable. The experience conveys an engineer who values both deep systems knowledge and interface precision.

### Design Movement
- **Modern Technical / Functional Minimalism:** Clean canvas backgrounds, crisp structural containment, refined hairline borders, and purposeful chromatic accents that guide user attention directly to project metrics, technical stacks, and interactive demonstrations.

## Colors

The color palette leverages high contrast and calibrated chromatic temperatures to ensure sustained readability and immediate functional clarity.

### Functional Palette Roles
- **Primary (`#2563EB` - Interactive Indigo/Blue):** Reserved for primary interactive controls, active navigation indicators, key links, and focal action points.
- **Secondary (`#0D9488` - Technical Teal):** Denotes technical competencies, verified skills, system status badges, and academic achievements.
- **Tertiary (`#3B82F6` - Electric Sky):** Used for hover states, focus rings, subtle linear gradients, and interactive timeline accents.
- **Neutral Surface & Text (`#0F172A` & Slate Spectrum):**
  - Text Primary: `#0F172A` (Slate 900) for uncompromised typographic contrast against light surfaces.
  - Text Secondary: `#475569` (Slate 600) for metadata, supporting body copy, and secondary labels.
  - Text Muted: `#94A3B8` (Slate 400) for timestamps, structural icons, and placeholders.
  - Border Hairline: `#E2E8F0` (Slate 200) for structural division and card contours.
  - Surface Primary: `#FFFFFF` (White) for card and container elevation.
  - Canvas Base: `#F8FAFC` (Slate 50) for overall canvas backdrops.

## Typography

The typographic engine is built around `Inter` to provide neutral, systematic rendering across all viewport densities and device operating systems. Generous line-heights prevent cognitive fatigue when reading technical project breakdowns, architecture logs, and academic project narratives.

### Typographic Hierarchy Rules
- **Display & Section Headers:** Rely on negative letter spacing and bold weights to project confidence and structure without decorative flourish.
- **Body Text:** Uses a calibrated 1.65–1.875 multiplier relative to font size to guarantee accessibility and effortless scannability.
- **Labels & Microcopy:** Utilize tighter tracking or subtle uppercase formatting with expanded tracking (`0.05em`) when applied to technical category tags and data tables.
- **Monospaced Code Elements:** Use `JetBrains Mono` for repository metrics, terminal snippets, API signatures, and versioning labels.

## Layout & Spacing

Layout and spatial distribution follow a disciplined 8pt grid logic (with 4pt sub-steps for micro-alignments).

### Grid System & Max Widths
- **Desktop Grid:** 12-column fluid grid locked to a max width of `1200px` for optimal reading measure and visual stabilization on high-resolution screens.
- **Tablet Grid (640px – 1024px):** 6-column fluid grid, `gutter: 1.5rem`, outer margins `2rem`.
- **Mobile Grid (< 640px):** 4-column fluid grid, `gutter: 1rem`, outer canvas margin `1.25rem`.

### Vertical Rhythm
- Global section separation maintains a generous `space-xl` to `4rem` rhythm to ensure clear demarcation between portfolio segments (e.g., Hero, Featured Projects, Technical Skills Matrix, and Contact).
- Interactive target boundaries strictly enforce a minimum height and width of `44px` on all touch-capable viewports.

## Elevation & Depth

Visual depth is achieved through layered structural surfaces, crisp hairline borders, and soft ambient shadows. Heavy skeuomorphism and opaque drop shadows are avoided to maintain an airy, modern digital presence.

### Layer Hierarchy
- **Base Canvas (`#F8FAFC`):** The structural foundation behind content cards and sections.
- **Card/Container Surface (`#FFFFFF`):** Sits directly atop the canvas, framed with a 1px border (`#E2E8F0`).
- **Floating Overlays & Menus:** Elevated using higher blur-radius ambient shadows with a cold slate tint (`rgba(15, 23, 42, 0.06)`).

### Elevation Tokens
- **Level 0 (Flat):** `border: 1px solid #E2E8F0; box-shadow: none;`
- **Level 1 (Card Rest):** `border: 1px solid #E2E8F0; box-shadow: 0 1px 3px 0 rgba(15, 23, 42, 0.04), 0 1px 2px -1px rgba(15, 23, 42, 0.04);`
- **Level 2 (Card Hover / Dropdown):** `border: 1px solid #CBD5E1; box-shadow: 0 10px 15px -3px rgba(15, 23, 42, 0.06), 0 4px 6px -4px rgba(15, 23, 42, 0.04);`
- **Level 3 (Modal / Floating Utility):** `border: 1px solid #CBD5E1; box-shadow: 0 20px 25px -5px rgba(15, 23, 42, 0.08), 0 8px 10px -6px rgba(15, 23, 42, 0.04);`

## Shapes

The design system adopts a balanced roundedness standard (`roundedness: 2`). This choice delivers contemporary warmth while retaining the clean discipline expected of an IT engineering platform.

### Corner Radius Standards
- **Base Components (0.5rem / 8px):** Buttons, inputs, inline code blocks, badges, and notification toasts.
- **Intermediate Elements (0.75rem / 12px):** Dropdown containers, technical parameter panels, and skill pills.
- **Large Surfaces (1rem / 16px):** Project cards, architecture visualizers, and hero spotlight containers.
- **Pills / Circular (`9999px`):** Skill tags, status indicators, and avatar cutouts.

## Components

### Buttons
- **Primary:** Background `#2563EB`, text `#FFFFFF`, radius `0.5rem`, min-height `44px`, padding `0.75rem 1.5rem`. Hover: `#1D4ED8`. Active: scale transform `0.98`. Focus: `2px solid #3B82F6` outline with `2px` offset.
- **Secondary / Outline:** Background `#FFFFFF`, border `1px solid #E2E8F0`, text `#0F172A`. Hover: background `#F8FAFC`, border `#CBD5E1`.
- **Ghost / Link:** Transparent background, text `#2563EB`, subtle underline transition on hover.

### Badges & Skill Chips
- **Tech Stack Badges:** Background `#F0FDFA` (Teal 50), border `1px solid #CCFBF1`, text `#0F766E` (Teal 700), font-weight `600`, font-size `0.75rem`, padding `0.25rem 0.625rem`, radius `9999px`.
- **Status Indicators:** Flex row with a pulse dot (`#0D9488`) followed by label text (`Available for Internship / Junior Roles`).

### Cards & Project Showcases
- **Structure:** Surface `#FFFFFF`, border `1px solid #E2E8F0`, padding `1.5rem` to `2rem`, border-radius `1rem`.
- **Hover Behavior:** Smooth transition (`transform 200ms ease, box-shadow 200ms ease, border-color 200ms ease`); translates `-2px` on the Y-axis with Level 2 elevation on pointer hover.
- **Project Card Schema:** Top badge row (category + live status), title (`headline-md`), excerpt (`body-md`), technical stack list (flex-wrapped pills), and split footer (GitHub repository link and Live Demo link).

### Form Controls & Input Fields
- **Input / Textarea:** Minimum touch height `44px`, background `#FFFFFF`, border `1px solid #E2E8F0`, radius `0.5rem`, padding `0.625rem 1rem`, typography `body-md`. Focus state transitions border to `#2563EB` with a soft box-shadow ring: `0 0 0 3px rgba(37, 99, 235, 0.15)`.

### Code Blocks & Architecture Walkthroughs
- Background `#0F172A` with contrasting light text `#F8FAFC`, radius `0.75rem`, padding `1.25rem`, with inline copy triggers and header metadata (e.g., file name and runtime tag).