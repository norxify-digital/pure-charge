---
name: PureCharge Climate Systems
colors:
  surface: '#f9f9ff'
  surface-dim: '#cfdaf3'
  surface-bright: '#f9f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f0f3ff'
  surface-container: '#e7eeff'
  surface-container-high: '#dee8ff'
  surface-container-highest: '#d7e3fc'
  on-surface: '#101c2e'
  on-surface-variant: '#414752'
  inverse-surface: '#253144'
  inverse-on-surface: '#ecf1ff'
  outline: '#717783'
  outline-variant: '#c1c7d4'
  surface-tint: '#005fae'
  primary: '#005daa'
  on-primary: '#ffffff'
  primary-container: '#1175d2'
  on-primary-container: '#fefcff'
  inverse-primary: '#a5c8ff'
  secondary: '#256d00'
  on-secondary: '#ffffff'
  secondary-container: '#93fb65'
  on-secondary-container: '#287300'
  tertiary: '#00647d'
  on-tertiary: '#ffffff'
  tertiary-container: '#007f9e'
  on-tertiary-container: '#fafdff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d4e3ff'
  primary-fixed-dim: '#a5c8ff'
  on-primary-fixed: '#001c3a'
  on-primary-fixed-variant: '#004785'
  secondary-fixed: '#93fb65'
  secondary-fixed-dim: '#78de4c'
  on-secondary-fixed: '#062100'
  on-secondary-fixed-variant: '#1a5200'
  tertiary-fixed: '#b9eaff'
  tertiary-fixed-dim: '#56d5ff'
  on-tertiary-fixed: '#001f29'
  on-tertiary-fixed-variant: '#004d62'
  background: '#f9f9ff'
  on-background: '#101c2e'
  surface-variant: '#d7e3fc'
typography:
  display-hero:
    fontFamily: Space Grotesk
    fontSize: 56px
    fontWeight: '700'
    lineHeight: 64px
    letterSpacing: -0.02em
  display-hero-mobile:
    fontFamily: Space Grotesk
    fontSize: 38px
    fontWeight: '700'
    lineHeight: 44px
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Space Grotesk
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.015em
  headline-lg-mobile:
    fontFamily: Space Grotesk
    fontSize: 26px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Space Grotesk
    fontSize: 22px
    fontWeight: '600'
    lineHeight: 28px
  headline-sm:
    fontFamily: Space Grotesk
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
  label-lg:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.01em
  label-md:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.02em
  metric-display:
    fontFamily: Space Grotesk
    fontSize: 44px
    fontWeight: '700'
    lineHeight: 48px
    letterSpacing: -0.03em
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
The design system embodies climate mastery, energy intelligence, and pristine environmental purity. Tailored for residential, commercial, and agricultural climate control across Zimbabwe and Sub-Saharan Africa, the aesthetic bridges industrial-grade precision engineering with refreshing domestic comfort.

The design movement is **Airy Modern Precision**: high luminosity, crystalline whitespace, subtle structured elevation, and atmospheric color zoning representing thermal regulation (cooling blues transition seamlessly into sustainable energy greens). Interface elements evoke clean filtered airflow, operational certainty, and modern energy savings without industrial clunkiness.

## Colors
The palette balances cooling aerodynamic tones with high-efficiency energy greens against crisp architectural neutrals.

### Roles & Palettes
- **Primary (`#1E7BD8`)**: Brand Blue governs major interactive drivers, active states, active cooling nodes, and primary system metrics.
- **Deep Accent (`#0B3A82`)**: Navy provides structural authority, high-emphasis icons, and brand anchoring.
- **Secondary (`#4CAF1F`)**: Leaf Green signals sustainable eco-mode, solar generation sync, and optimal efficiency.
- **Accent Highlighters**:
  - **Cyan (`#00C2F0`)**: Rapid chilling, humidity extraction, and dynamic air velocity indicators.
  - **Lime (`#8DC63F`)**: Peak green energy surplus, smart-scheduling highlights.
  - **Deep Green (`#2E7D32`)**: Confirmed normal status, safety compliance flags.
- **Neutrals & Surfaces**:
  - **Ink (`#0F1B2D`)**: High-contrast typography and critical telemetry readouts.
  - **Muted Slate (`#5B6B80`)**: Secondary metadata, inactive states, unit labels.
  - **Border Matrix (`#E3EAF3`)**: Ultra-precise boundary definition preventing visual bleed.
  - **Soft Blue Canvas (`#F2F7FD`)**: Global canvas tint that softens glare under intense sunlight.
  - **Pure Surface (`#FFFFFF`)**: Card surfaces, elevated modals, and dial backplates.

### Signature Dynamic Gradient
- `linear-gradient(135deg, #1E7BD8 0%, #4CAF1F 100%)`: Applied selectively to power toggles, primary conversion actions, hero climate rings, and energy efficiency summary cards.

## Typography
Typography reflects technical authority coupled with extreme legibility under changing ambient light.

- **Headlines & Metrics (Space Grotesk)**: Chosen for its architectural geometry, sharp proportions, and technical clarity. Numeric readouts for temperatures, power draw (kW), airflow velocity (CFM), and seasonal energy ratings (SEER) rely on this family for immediate recognition.
- **Body & Controls (Inter)**: Delivers universal accessibility, neutral text rhythm, and uncompromised clarity across multi-language installation logs, diagnostics, and schedules.
- **Formatting Protocols**: Numeric decimal readings must keep tabular alignment. Thermostat setpoints and ambient temperatures must display with dedicated degree units styled one step smaller than the integer.

## Layout & Spacing
The layout follows a 12-column fluid grid system across desktop (`>= 1200px`) and 8-column system across tablet (`768px - 1199px`), collapsing into a 4-column system for mobile (`< 768px`).

- **Vertical Rhythm**: Generous whitespace enforces an "airy" feeling reminiscent of well-ventilated rooms. Sections must have clear separation (`space-xl` to `margin`) to prevent diagnostic data density from overwhelming the user.
- **Micro Spacing**: Component internals utilize strict 8pt sub-grids (`space-xs`, `space-sm`, `space-md`) to ensure tactile targeting for service technicians working on handheld devices in bright outdoor settings.
- **Canvas Rule**: The viewport must maintain the baseline `#F2F7FD` background with whitespace cushions along margins to emphasize floating container precision.

## Elevation & Depth
Depth conveys physical enclosure, air distribution tiers, and mechanical states without heavy shadow contamination.

- **Tier 0 (Base Canvas)**: Flat `#F2F7FD`.
- **Tier 1 (Pristine Cards)**: `#FFFFFF` fill resting on a clean `1px solid #E3EAF3` perimeter. Ambient shadow is gossamer: `0 4px 16px rgba(11, 58, 130, 0.04)`.
- **Tier 2 (Active Climate Controllers & Dials)**: `#FFFFFF` surface with `1px solid #1E7BD8` border accent and subtle dual-cast glow: `0 8px 24px rgba(30, 123, 216, 0.10)`.
- **Tier 3 (Floating Overlays, Modals, System Alerts)**: `#FFFFFF` surface with `0 20px 40px rgba(15, 27, 45, 0.08)` and fine border line `#E3EAF3`.
- **Backdrop Treatments**: Modal curtains and drawer backings use an airy glass scrim: `rgba(242, 247, 253, 0.75)` with `backdrop-filter: blur(8px)`.

## Shapes
The shape system prioritizes modern architectural crispness:
- Standard components (buttons, input boxes, metric tiles) use subtle `0.25rem` (4px) corner radiuses.
- Larger spatial units (climate zone cards, diagnostic panels) utilize `rounded-lg` at `0.5rem` (8px).
- Modals, large interactive thermostats, and hero banners scale to `rounded-xl` at `0.75rem` (12px).
- Completely circular geometries (`rounded-full`) are reserved exclusively for mode toggle pills, status indicator pips, and circular ambient temperature dials.

## Components

### Buttons
- **Primary Action**: Signature gradient (`linear-gradient(135deg, #1E7BD8 0%, #4CAF1F 100%)`) with white text, `height: 44px`, `px: 1.5rem`, `roundedness: 1`. Hover scales elevation slightly without changing gradient orientation.
- **Secondary Action**: Solid `#FFFFFF` fill, `1px solid #E3EAF3`, text `#0F1B2D`. Hover shifts border to `#1E7BD8` and tint to `#F2F7FD`.
- **Eco / Boost Quick Switches**: `#0B3A82` background for intense HVAC override modes, `#4CAF1F` for intelligent eco-throttle.

### Chips & Zone Badges
- Compact indicators with `0.25rem` border radius, padding `0.25rem 0.75rem`.
- **Cooling Mode**: Background `rgba(0, 194, 240, 0.12)`, text `#0B3A82`, border `1px solid rgba(0, 194, 240, 0.3)`.
- **Energy Saving / Solar Synchronized**: Background `rgba(76, 175, 31, 0.12)`, text `#2E7D32`, border `1px solid rgba(76, 175, 31, 0.3)`.

### Cards & System Monitoring Panels
- Surfaces are `#FFFFFF` with structural borders (`#E3EAF3`).
- Cards group data clearly: Zone Name (Space Grotesk `headline-sm`), Operational Status Pip, Large Temperature/Humidity display (`metric-display`), and secondary air-quality index along the card footer.

### Input Fields & Selectors
- Standard `44px` height, `#FFFFFF` interior, `1px solid #E3EAF3` perimeter.
- Focus state: `1px solid #1E7BD8` accompanied by `0 0 0 3px rgba(30, 123, 216, 0.15)`. Labels sit outside in Inter `label-md` using `#5B6B80`.

### Toggles, Checkboxes & Radio Controls
- Binary switches: `48px x 26px`. Off state `#E3EAF3` with `#5B6B80` thumb; On state uses `#1E7BD8` or signature gradient thumbing to `#4CAF1F` when tied to green energy modes.
- Radios and Checkboxes utilize clean `2px` border lines with sharp-soft corners (`roundedness: 1`).

### Climate Dial & Sliders
- Linear slider tracks maintain a thin `6px` channel filled with `#E3EAF3` with an active fill using gradient cooling-to-comfort (`#00C2F0` to `#1E7BD8`). Thumb features a solid `#FFFFFF` disk with a `#1E7BD8` centered core.