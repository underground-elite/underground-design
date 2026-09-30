---
name: Cobalt Precision
colors:
  surface: '#0f131d'
  surface-dim: '#0f131d'
  surface-bright: '#353944'
  surface-container-lowest: '#0a0e18'
  surface-container-low: '#171b26'
  surface-container: '#1c1f2a'
  surface-container-high: '#262a35'
  surface-container-highest: '#313540'
  on-surface: '#dfe2f1'
  on-surface-variant: '#c4c5d7'
  inverse-surface: '#dfe2f1'
  inverse-on-surface: '#2c303b'
  outline: '#8e90a0'
  outline-variant: '#434655'
  surface-tint: '#b7c4ff'
  primary: '#b7c4ff'
  on-primary: '#002682'
  primary-container: '#1d4ed8'
  on-primary-container: '#cad3ff'
  inverse-primary: '#2151da'
  secondary: '#adc6ff'
  on-secondary: '#002e6a'
  secondary-container: '#0566d9'
  on-secondary-container: '#e6ecff'
  tertiary: '#a4c9ff'
  on-tertiary: '#00315d'
  tertiary-container: '#005da8'
  on-tertiary-container: '#bdd6ff'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#dce1ff'
  primary-fixed-dim: '#b7c4ff'
  on-primary-fixed: '#001551'
  on-primary-fixed-variant: '#0039b5'
  secondary-fixed: '#d8e2ff'
  secondary-fixed-dim: '#adc6ff'
  on-secondary-fixed: '#001a42'
  on-secondary-fixed-variant: '#004395'
  tertiary-fixed: '#d4e3ff'
  tertiary-fixed-dim: '#a4c9ff'
  on-tertiary-fixed: '#001c39'
  on-tertiary-fixed-variant: '#004883'
  background: '#0f131d'
  on-background: '#dfe2f1'
  surface-variant: '#313540'
typography:
  display-hero:
    fontFamily: Geist
    fontSize: 56px
    fontWeight: '600'
    lineHeight: 64px
    letterSpacing: -0.03em
  display-hero-mobile:
    fontFamily: Geist
    fontSize: 36px
    fontWeight: '600'
    lineHeight: 44px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Geist
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Geist
    fontSize: 26px
    fontWeight: '600'
    lineHeight: 34px
    letterSpacing: -0.015em
  headline-md:
    fontFamily: Geist
    fontSize: 24px
    fontWeight: '500'
    lineHeight: 32px
    letterSpacing: -0.015em
  headline-sm:
    fontFamily: Geist
    fontSize: 18px
    fontWeight: '500'
    lineHeight: 26px
    letterSpacing: -0.01em
  body-lg:
    fontFamily: Geist
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
    letterSpacing: -0.005em
  body-md:
    fontFamily: Geist
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
    letterSpacing: 0em
  body-sm:
    fontFamily: Geist
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 16px
    letterSpacing: 0.01em
  code-md:
    fontFamily: JetBrains Mono
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 18px
    letterSpacing: -0.01em
  label-md:
    fontFamily: JetBrains Mono
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.04em
  label-sm:
    fontFamily: JetBrains Mono
    fontSize: 10px
    fontWeight: '500'
    lineHeight: 14px
    letterSpacing: 0.06em
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
  margin: 2rem
  margin-mobile: 1rem
  margin-desktop: 3rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

This design system embodies high-performance clarity, structural tension, and technical authority. It serves advanced developer tooling, high-frequency financial platforms, and precision cloud infrastructure. The visual philosophy blends technical minimalism with high-contrast functionalism—eschewing decorative fluff, non-functional gradients, and ambient warmth in favor of razor-sharp contrast, mechanical rhythm, and intentional chromatic focus.

The emotional resonance is cool, disciplined, and uncompromisingly capable. Interaction feels immediate, crisp, and predictable. Visual emphasis is entirely directed by a solitary electric blue against stark black and cold, blue-tinted monochrome surfaces.

## Colors

The palette is engineered exclusively with cold spectrum tones: deep obsidian blacks, sharp slate-blues, high-intensity cobalt accents, and stark whites. Warm spectrum pigments (yellows, reds, ambers, greens) are strictly excluded from structural design tokens.

- **Obsidian Dark Baseline**: The root canvas begins at `#000000` for deep viewport layers and steps to `#0B0F19` for elevated view layers and work panels.
- **Electric Blue Focus**: `#1D4ED8` serves as the primary action core, supported by `#3B82F6` for interactive hovers and state indicators, and `#60A5FA` strictly for high-visibility highlights against deep dark surfaces.
- **Monochrome Slate Grayscale**: Midtones are cool and desaturated:
  - Surface Border: `#1E293B`
  - Subtle Surface: `#0F172A`
  - Muted Text / Inactive Icons: `#64748B`
  - Secondary Text: `#94A3B8`
  - High-Contrast Foregrounds / Primary Type: `#F8FAFC` and `#FFFFFF`
- **Functional Semantics**: Information states rely entirely on tonal value, glyph shape, stroke treatment, and contrast shifts rather than multicolored chromatic cues.

## Typography

The typographic hierarchy is split intentionally between two high-precision typefaces: **Geist** for all core interface, structural headings, and body communication; and **JetBrains Mono** for all operational parameters, metrics, system tags, and data grids.

- **Weight Pairing**: Headlines utilize semi-bold (`600`) weights with tight tracking (`-0.02em` to `-0.03em`) to anchor layouts securely. Body layers use regular (`400`) weight for maximum legibility against dark slate backdrops.
- **Monospace Discipline**: JetBrains Mono handles all non-narrative micro-copy: timestamps, status tokens, system logs, numerical readouts, and form labels. Uppercase transformations (`label-sm`, `label-md`) must always include positive letter spacing (`0.04em` to `0.06em`) for rapid scanning.

## Layout & Spacing

The structural backbone uses a fluid 12-column grid system paired with strict mathematical layout gutters. 

- **Grid Breakpoints**:
  - **Desktop (>= 1280px)**: 12 columns, `margin-desktop` (3rem), `gutter-lg` (2rem). Content maxes at 1440px wide or docks seamlessly as full-bleed dashboard modules.
  - **Tablet (768px - 1279px)**: 8 columns, `margin` (2rem), `gutter` (1.5rem). Secondary sidebars collapse into rail menus.
  - **Mobile (< 768px)**: 4 columns, `margin-mobile` (1rem), `gutter-sm` (1rem). Multi-column tables and parameter blocks stack linearly.
- **Spatial Rhythm**: All component spacing adheres to an absolute 4px/8px incremental cadence. Gaps between related operational controls use `space-xs` (4px) or `space-sm` (8px). Container internal paddings sit consistently at `space-md` (16px) or `space-lg` (24px).

## Elevation & Depth

This system avoids heavy drop shadows and fuzzy ambient light. Depth is communicated strictly via **tonal stratification** and **subtle, high-precision slate borders** (low-contrast outlines).

1. **Layer 0 (Canvas Base)**: Deepest surface at `#000000`. Used for root application viewports, empty backdrops, and navigation frame rail borders.
2. **Layer 1 (Card & Module Surfaces)**: Obsidian container at `#0B0F19`, wrapped with a precise 1px stroke of `#1E293B`.
3. **Layer 2 (Floating Modals, Drawers, Flyouts)**: Elevated obsidian at `#0F172A`, bounded by a 1px stroke of `#334155`. Accompanied only by a restrained, non-diffuse dark occlusion: `0 8px 24px -4px rgba(0, 0, 0, 0.8)`.
4. **Active/Focus Elevation**: Active selection is never depicted with a shadow; instead, an inner or outer hairline border transitions instantly to Electric Blue `#3B82F6` or `#1D4ED8`.

## Shapes

The design uses a restrained, compact rounding architecture (`roundedness: 1`). Controls, badges, inputs, and container modules employ a subtle 4px (`0.25rem`) corner radius. Larger modal wrappers and overarching panels scale to a maximum of 8px (`0.5rem`). 

Pill shapes and full roundings are reserved solely for live status dots and telemetry counters. This sharp geometric restraint reinforces the technical, industrial character of the product.

## Components

### Buttons
- **Primary**: Solid Cobalt Blue background (`#1D4ED8`), white text (`#FFFFFF`, `label-md`), 4px corner radius, padding `8px 16px`. Hover switches to Electric Blue (`#3B82F6`). Active state scales to `#1E40AF`.
- **Secondary**: Deep obsidian surface (`#0B0F19`), hairline border (`1px solid #1E293B`), text `#F8FAFC`. Hover sets border to `#3B82F6` and background to `#0F172A`.
- **Ghost/Outline**: Purely transparent, text `#94A3B8`, hover foreground `#FFFFFF` with `#0F172A` background tint.

### Chips & Badges
- Constructed with `label-sm` (JetBrains Mono).
- Inactive/Neutral: `#0F172A` fill, `#1E293B` border, `#94A3B8` text.
- Highlighted/Active: `#0B0F19` fill, `#1D4ED8` 1px border, `#60A5FA` text with a 4px solid electric blue indicator dot on the left.

### Input Fields
- Dark fill (`#000000` or `#0B0F19`), height 36px, `1px solid #1E293B` border, text `#F8FAFC` (`body-md`), placeholder `#64748B`.
- Focus state: Hairline 1px stroke changes to `#3B82F6` with zero outer shadow glow. Invalid/Error state uses high-contrast pure white text, a crisp solid white outline, and an accompanying glyph indicator.

### Checkboxes & Radio Buttons
- 16x16px boxes, 2px border of `#334155` over an obsidian center.
- Checked state: `#1D4ED8` solid background, pure `#FFFFFF` geometric checkmark icon. Radios use a centered 6px pure white disc on a cobalt fill.

### Cards & Panels
- Background `#0B0F19` with a strict `1px solid #1E293B` outer contour. Padding `space-lg` (24px).
- Optional card header: Separated by a horizontal 1px stroke of `#1E293B`, featuring Geist semi-bold titles alongside JetBrains Mono metadata flags.

### Data Tables & Code Terminals
- Rows feature alternating border bottoms (`1px solid #0F172A`).
- Row hover produces a unified row background shift to `#0F172A`.
- Monospaced numerical values are aligned right; column headers are displayed in uppercase `label-sm` with `#64748B` styling.