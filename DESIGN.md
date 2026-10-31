---
name: Kinetic Obsidian
colors:
  surface: '#131313'
  surface-dim: '#131313'
  surface-bright: '#3a3939'
  surface-container-lowest: '#0e0e0e'
  surface-container-low: '#1c1b1b'
  surface-container: '#201f1f'
  surface-container-high: '#2a2a2a'
  surface-container-highest: '#353534'
  on-surface: '#e5e2e1'
  on-surface-variant: '#e0c0b1'
  inverse-surface: '#e5e2e1'
  inverse-on-surface: '#313030'
  outline: '#a78b7d'
  outline-variant: '#584237'
  surface-tint: '#ffb690'
  primary: '#ffb690'
  on-primary: '#552100'
  primary-container: '#ff7a24'
  on-primary-container: '#5f2600'
  inverse-primary: '#9d4300'
  secondary: '#c6c6c7'
  on-secondary: '#2f3131'
  secondary-container: '#454747'
  on-secondary-container: '#b4b5b5'
  tertiary: '#7ed0ff'
  on-tertiary: '#00344a'
  tertiary-container: '#00ace9'
  on-tertiary-container: '#003c54'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#ffdbca'
  primary-fixed-dim: '#ffb690'
  on-primary-fixed: '#341100'
  on-primary-fixed-variant: '#783200'
  secondary-fixed: '#e2e2e2'
  secondary-fixed-dim: '#c6c6c7'
  on-secondary-fixed: '#1a1c1c'
  on-secondary-fixed-variant: '#454747'
  tertiary-fixed: '#c5e7ff'
  tertiary-fixed-dim: '#7ed0ff'
  on-tertiary-fixed: '#001e2d'
  on-tertiary-fixed-variant: '#004c6a'
  background: '#131313'
  on-background: '#e5e2e1'
  surface-variant: '#353534'
typography:
  display-hero:
    fontFamily: Space Grotesk
    fontSize: 72px
    fontWeight: '600'
    lineHeight: 76px
    letterSpacing: -0.03em
  display-hero-mobile:
    fontFamily: Space Grotesk
    fontSize: 40px
    fontWeight: '600'
    lineHeight: 44px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Space Grotesk
    fontSize: 44px
    fontWeight: '600'
    lineHeight: 50px
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Space Grotesk
    fontSize: 30px
    fontWeight: '600'
    lineHeight: 36px
    letterSpacing: -0.015em
  headline-md:
    fontFamily: Space Grotesk
    fontSize: 28px
    fontWeight: '500'
    lineHeight: 34px
    letterSpacing: -0.015em
  headline-sm:
    fontFamily: Space Grotesk
    fontSize: 20px
    fontWeight: '500'
    lineHeight: 26px
    letterSpacing: -0.01em
  body-lg:
    fontFamily: Geist
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
    letterSpacing: -0.005em
  body-md:
    fontFamily: Geist
    fontSize: 15px
    fontWeight: '400'
    lineHeight: 24px
    letterSpacing: 0em
  body-sm:
    fontFamily: Geist
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 20px
    letterSpacing: 0em
  label-mono:
    fontFamily: JetBrains Mono
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.06em
  label-mono-sm:
    fontFamily: JetBrains Mono
    fontSize: 11px
    fontWeight: '400'
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
  gutter-sm: 1rem
  gutter-lg: 2rem
  margin: 1.5rem
  margin-md: 3rem
  margin-lg: 5rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

This design system expresses a high-end engineering atelier aesthetic tailored for a high-impact personal web development portfolio and client acquisition studio. The brand balances architectural precision with bespoke digital craftsmanship. 

### Audience & Sentiment
- **Target Audience:** Founders, venture-backed tech startups, creative agencies, and product leaders seeking high-performance frontend architecture and distinct interactive web experiences.
- **Emotional Intent:** Authority, uncompromising engineering discipline, refined taste, and quiet confidence. The interface avoids aggressive neon trends or chaotic visual clutter in favor of mathematical alignment, restrained warmth, and razor-sharp typographic pacing.

### Design Movement
- **Minimal High-Tech Studio:** Rooted in Swiss architectural grid structure fused with contemporary dark-mode minimalism.
- **Key Characteristics:** 
  - Deep slate and charcoal planes layered using nuanced luminosity shifts instead of drop shadows.
  - Razor-thin 1px structural outlines defining boundaries and cards.
  - Calculated, single-source bursts of warm incandescent orange (`#FF7A24`) reserved exclusively for interactive triggers, focal milestones, and high-value conversion elements.
  - Abundant breathing room that allows work showcase case studies to present as museum-grade gallery pieces.

## Colors

The palette establishes an obsidian canvas engineered to maximize focus and reduce visual fatigue, while establishing distinct tonal tiers for structural depth.

### Palette Architecture
- **Primary Accent (`#FF7A24`):** An incandescent, warm vivid amber-orange. Reserved for core calls to action, selected active states, critical status indicators, and subtle directional indicators. Never used across large filled surfaces.
- **Neutral Canvas (`#111111`):** The foundational viewport floor. Imparts heavy, grounded visual depth.
- **Secondary Surfaces:**
  - `Surface Tier 1 (#1A1A1A)`: Primary card surfaces, elevated containers, and input wells.
  - `Surface Tier 2 (#222222)`: Interactive hover highlights, chip backgrounds, navigation headers, and segmented panels.
- **Micro-Border Accent (`#303030`):** The structural line color. All bounding boxes, grid lines, dividers, and framing elements must use this crisp, low-contrast tone.
- **Typographic Scale:**
  - `Primary Text (#F5F5F5)`: High-legibility crisp white for primary headers, active titles, and high-emphasis body text.
  - `Muted Secondary Text (#A1A1A1)`: Mid-tone slate grey for secondary body, technical specifications, and navigational links.
  - `Tertiary / Meta Text (#666666)`: De-emphasized timestamps, line numbers, and architectural labels.

### Usage Protocol
- Prohibit multi-stop gradients across backgrounds. 
- The accent color must not exceed 5% of viewport real estate at any given time.
- Accent hover states transition toward `#FF8D42` with zero outline blur.

## Typography

Typographic hierarchy relies on the interplay between technical precision and human-scale legibility:

1. **Display & Headings (Space Grotesk):** Provides architectural character with structural letterforms. Headings utilize tight, negative letter spacing to project an engineered, confident tone.
2. **Body & Prose (Geist):** Handles conversational descriptions, service details, and technical case study breakdowns with neutral, balanced clarity.
3. **Labels, Metadata & Code Metrics (JetBrains Mono):** Dedicated to technical metadata, stack tags, metrics, step numbers, and micro-labels. Always rendered with uppercase formatting where specified to amplify systematic rigor.

## Layout & Spacing

The layout model enforces a rhythmic, modular grid built around maximum content width constraints of `1280px` to guarantee legibility and spatial proportion on ultrawide monitors.

### Grid Framework
- **Desktop (1024px+):** 12-column fluid grid, `gutter-lg` (2rem / 32px), with `margin-lg` (5rem / 80px) outer edge boundary padding.
- **Tablet (768px – 1023px):** 8-column fluid grid, `gutter` (1.5rem / 24px), with `margin-md` (3rem / 48px) margins.
- **Mobile (Below 768px):** 4-column fluid grid, `gutter-sm` (1rem / 16px), with `margin` (1.5rem / 24px) screen edges.

### Layout Principles
- **Generous Sectional Rhythm:** Vertical intervals between major studio showcase chapters must utilize substantial spacing (`space-xl` scaled dynamically or up to 6rem–8rem in layout containers) to isolate each project or service package.
- **Strict Baseline Multiples:** All internal padding, element margins, and stack alignments adhere to an 8px scale (`space-xs` = 4px, `space-sm` = 8px, `space-md` = 16px, `space-lg` = 24px, `space-xl` = 40px).
- **Asymmetrical Compositions:** Editorial case studies alternate split layouts (6:6 or 7:5 columns), pairing live code artifacts and architectural schematics against narrative typography.

## Elevation & Depth

This design system rejects heavy diffuse drop shadows and standard blur techniques. Depth is communicated strictly through surface layering and microscopic border definitions.

### Tonal Tiers
- **Floor (`#111111`):** The primary view base.
- **Layer 1 (`#1A1A1A`):** Case study cards, experience cards, and persistent navigation bars.
- **Layer 2 (`#222222`):** Dropdowns, tooltips, interactive card hover surfaces, and command palettes.

### Structural Micro-Borders
- Elevation hierarchy is bounded by a uniform `1px solid #303030` stroke across all surface edges.
- On card hover or focused element elevation, the border transitions via a 150ms cubic curve to `#FF7A24` (or `#4A4A4A` for secondary targets), without shifting element coordinates or introducing heavy outer glows.

### Restrained Lighting
- When floating modals or contextual flyouts require separation from the page context, use a crisp, un-tinted hard shadow offset: `0px 8px 24px rgba(0, 0, 0, 0.6)`. Backdrop filters over scrolling canvas content utilize `backdrop-filter: blur(12px)` over `#111111CC` (80% opacity neutral).

## Shapes

The shape system adopts a **Soft (`1`)** geometry profile to maintain an engineered, mechanical precision without appearing brittle or raw.

### Corner Radii
- **Standard Components (`0.25rem` / 4px):** Applied to form inputs, small action buttons, tag chips, and micro-badges.
- **Medium Panels (`rounded-lg` / `0.5rem` / 8px):** Applied to case study cards, code blocks, quote containers, and interactive modular panels.
- **Large Overlays (`rounded-xl` / `0.75rem` / 12px):** Applied exclusively to modal dialogs, full-viewport drawered panels, and screen takeovers.
- **Exceptions:** Status indicator dots and directional icon disc wrappers may use complete 50% circular boundaries (`9999px`).

## Components

### Buttons
- **Primary Action (Client Inquiries, Lead Conversions):** 
  - Background: `#FF7A24`. Text: `#111111` (Space Grotesk, 600 weight).
  - Border: 1px solid `#FF7A24`. Radius: `0.25rem`.
  - Padding: `0.75rem 1.5rem`.
  - Hover: Background `#FF8D42`, transform: none (no floating or scale shifts; absolute stability).
- **Secondary Action (Explore Case Study, Documentation):**
  - Background: `#1A1A1A`. Text: `#F5F5F5`.
  - Border: 1px solid `#303030`.
  - Hover: Border color `#FF7A24`, text `#F5F5F5`, surface transitions to `#222222`.
- **Tertiary / Ghost:** 
  - Background: Transparent. Text: `#A1A1A1`.
  - Hover: Text `#FF7A24`.

### Input Fields & Textareas
- Surface: `#1A1A1A`.
- Border: 1px solid `#303030`.
- Text: `#F5F5F5` (Geist). Placeholder: `#666666`.
- Height: 44px (Inputs), dynamic min-height 120px (Textareas). Padding: `0.75rem 1rem`.
- Focus State: Border color `#FF7A24` with zero outer ring or glow. Label stays crisp above the field in `JetBrains Mono` at 11px uppercase (`#A1A1A1`).

### Chips & Tech Stack Badges
- Background: `#1A1A1A`.
- Border: 1px solid `#303030`.
- Text: `#A1A1A1` (JetBrains Mono, 11px, tracking 0.08em).
- Padding: `0.25rem 0.625rem`.
- Active / Filtered: Border `#FF7A24`, text `#FF7A24`, background `#222222`.

### Cards (Case Studies & Service Offerings)
- Background: `#1A1A1A`.
- Border: 1px solid `#303030`.
- Internal Spacing: `space-lg` (24px) to `space-xl` (40px).
- Interaction: On mouseover, 1px border transitions from `#303030` to `#4A4A4A`. When featuring an active demo or client win, an accent pip (`#FF7A24`, 6px circle) designates active operational status.

### Form Selection (Checkboxes & Radios)
- Box / Circle: 18px × 18px.
- Background: `#1A1A1A`. Border: 1px solid `#303030`.
- Checked State: Border `#FF7A24`, fill `#FF7A24`, inner check indicator `#111111`.

### Bespoke Studio Components
- **Client Metric KPI Block:** Stacked layout featuring display numeric telemetry (Space Grotesk, 44px, `#F5F5F5`) paired with a mono metric descriptor (`JetBrains Mono`, 11px, `#A1A1A1`, uppercase).
- **Interactive Terminal / Code Snippet Block:** Background `#0E0E0E`, bordered by `#303030`, with a micro header bar carrying window dots in `#303030` and a right-aligned branch or file status token in `#FF7A24`.
- **Availability Beacon:** A pulse-ring micro indicator (7px circle `#FF7A24`) accompanied by "AVAILABLE FOR Q3/Q4 ENGAGEMENTS" set in `label-mono`.