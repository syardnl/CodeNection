---
name: Calm Cloud
colors:
  surface: '#f0fcf6'
  surface-dim: '#d1ddd7'
  surface-bright: '#f0fcf6'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#eaf6f0'
  surface-container: '#e4f1ea'
  surface-container-high: '#dfebe5'
  surface-container-highest: '#d9e5df'
  on-surface: '#131e1a'
  on-surface-variant: '#3e4945'
  inverse-surface: '#28332f'
  inverse-on-surface: '#e7f4ed'
  outline: '#6e7a75'
  outline-variant: '#bdc9c3'
  surface-tint: '#006b57'
  primary: '#006b57'
  on-primary: '#ffffff'
  primary-container: '#89e2c7'
  on-primary-container: '#006652'
  inverse-primary: '#7ed7bc'
  secondary: '#146b56'
  on-secondary: '#ffffff'
  secondary-container: '#a1efd5'
  on-secondary-container: '#1b6f5a'
  tertiary: '#7f5626'
  on-tertiary: '#ffffff'
  tertiary-container: '#ffc78d'
  on-tertiary-container: '#7a5122'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#9af4d8'
  primary-fixed-dim: '#7ed7bc'
  on-primary-fixed: '#002019'
  on-primary-fixed-variant: '#005141'
  secondary-fixed: '#a4f2d8'
  secondary-fixed-dim: '#88d5bc'
  on-secondary-fixed: '#002018'
  on-secondary-fixed-variant: '#005140'
  tertiary-fixed: '#ffdcbc'
  tertiary-fixed-dim: '#f3bc83'
  on-tertiary-fixed: '#2c1700'
  on-tertiary-fixed-variant: '#643f10'
  background: '#f0fcf6'
  on-background: '#131e1a'
  surface-variant: '#d9e5df'
  mint-surface: '#EFF8F4'
  mint-subtle: '#D5F2E7'
  mint-deep: '#2D5E50'
  canvas-base: '#FAF8F5'
  canvas-elevated: '#FFFFFF'
  text-muted: '#687570'
typography:
  headline-xl:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
  headline-xl-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 26px
    fontWeight: '700'
    lineHeight: 34px
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 22px
    fontWeight: '600'
    lineHeight: 28px
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 24px
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  body-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 16px
  label-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 18px
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
  label-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 11px
    fontWeight: '500'
    lineHeight: 14px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1rem
  margin: 1.25rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

This design system delivers a restorative, emotionally safe digital space for students navigating academic pressure and chronic fatigue. Rejecting cold clinical metrics, gamified urgency, and traditional productivity gamification, the interface acts as a gentle, low-demand companion. The core visual anchor is the soft mint-green cloud blob mascot: a non-verbal, mirror reflection of the user's current capacity rather than a virtual pet demanding upkeep.

The aesthetic merges **Warm Organic Minimalism** with soft, tactile physical calm. It relies on generous breathing room, ultra-soft diffused ambient elevation, warm off-white canvas tones, and charcoal typography. Urgency and distress are de-escalated through quiet tonal shifts within a single mint family—deliberately avoiding high-stress red, amber, and yellow traffic-light signifiers. Every surface feels supportive, grounded, and unmistakably human.

## Colors

The palette is strictly monochromatic in hue, anchored around the soft mint tone of the cloud mascot (`#89E2C7`). Rather than relying on alarmist multi-color status codes (red for overdue, amber for caution), all status feedback, capacity stages, and priorities are conveyed through tonal depth, weight, and proximity within the mint spectrum.

- **Primary (`#89E2C7`)**: The vibrant yet soothing mascot mint, applied to core interactive touches, joyful capacity states, and primary selections.
- **Secondary (`#4D9A83`)**: A grounded, medium-toned forest sage used for interactive focus states, filled progress indicators, and prominent SVG line accents.
- **Neutral (`#27322E`)**: Deep charcoal with a subtle forest undertone, completely avoiding sterile pure black to maintain an approachable, non-intimidating reading contrast.
- **Backgrounds**: Rooted in warm paper-like canvas (`#FAF8F5`) with floating card containers in pure warm white (`#FFFFFF`) or tinted mint-mist (`#EFF8F4`).

## Typography

The design system uses **Plus Jakarta Sans** across all typography levels. Its gently sculpted geometric terminals, wide apertures, and warm proportions evoke reassurance without tipping into novelty or informality.

Text density must remain deliberately low. Screens prioritize spacious typography with generous line-heights over multi-line text blocks. Avoid clinical jargon ("metrics," "algorithms," "score ratios") in favor of conversational clarity ("What are we feeling today?", "Your capacity looks full").

## Layout & Spacing

Designed mobile-first around a fluid panel layout inspired by modern communication surfaces, the structure utilizes a bottom floating navigation dock and panel-based modules. 

- **Outer Margins**: A constant `1.25rem` (20px) padding secures a comfortable breathing perimeter on mobile devices.
- **Rhythm**: Vertical content groups follow an 8pt spatial grid, favoring larger gaps (`space-lg` to `space-xl`) between content tiers to reduce cognitive load and prevent feelings of crowding.
- **Form Factor Adaptation**: On larger screens or tablets, panels do not stretch arbitrarily wide; instead, content centers inside a constrained single card column (max 480px width) to preserve the intimate, conversational feel of a personal handheld companion.

## Elevation & Depth

Visual hierarchy is achieved strictly without hard outlines, harsh dividing rules, or rigid containment borders. Instead, depth is conveyed through **tonal transitions** and **diffused ambient shadows**.

- **Level 0 (Canvas Base)**: Matte `#FAF8F5` surface.
- **Level 1 (Card & Modules)**: Pure `#FFFFFF` surfaces lifted with an ultra-soft, low-opacity ambient drop shadow: `0 8px 24px rgba(39, 50, 46, 0.04)`.
- **Level 2 (Floating Modals & Mascot Containers)**: `0 16px 36px rgba(39, 50, 46, 0.07)`, paired with subtle mint undertones (`rgba(137, 226, 199, 0.15)`).
- **Crisis Banner & Floating Overlays**: Seamless backdrop blur (`backdrop-filter: blur(12px)`) layered over a 90% white or mint-tinted fill to keep focus clear and grounded.

## Shapes

The shape system embraces soft, organic curves derived directly from the lobes of the cloud mascot. Sharp 90-degree corners are completely absent.

- Standard cards, interactive tiles, and panels adopt a generous `1rem` (16px) corner radius (`rounded-lg`).
- Floating utility sheets, dialogs, and Mascot hero wells leverage an expansive `1.5rem` to `2rem` (24px to 32px) curvature (`rounded-xl`).
- Buttons, chips, and progress pills utilize continuous full curvature (`rounded-full`) for friendly, pillowy tactile comfort.

## Components

### Buttons
- **Primary**: Full-pill height (48px touch target), filled with `#89E2C7`, labeled in `#27322E` semi-bold text. No borders, accompanied by a soft mint ambient glow on press.
- **Secondary / Ghost**: Pill shape filled with `#EFF8F4` or completely transparent with `#4D9A83` text.
- **Action Trio (Accept / Adjust / Keep Anyway)**:
  - *Accept*: Mint-tinted pill button.
  - *Adjust*: Neutral soft-tonal pill.
  - *Keep Anyway*: Low-contrast text-only action that validates autonomy without visual shame or red penalties.

### Cards & Panels
- Soft `#FFFFFF` surfaces with 16px padding and `1rem` border radius. Zero border strokes.
- Internal separation between sub-items is handled purely via `space-sm` or `space-md` whitespace gaps, never divider lines.

### Inputs & Check-ins
- **Daily State Selector ("What are we feeling today?")**: Replaces standard sliders and emoji with custom SVG line icons displaying 4 subtle emotional/capacity postures matching the cloud mascot (e.g., energized, grounded, slow, dim).
- **Fields**: Background-tinted capsules (`#EFF8F4`) with 16px vertical padding, floating placeholder text in `#687570`, transitioning to a subtle mint glow on active focus.

### Iconography
- Custom vector line icons with a consistent 1.75px stroke width and rounded joins (`stroke-linecap="round"`). 
- No standard unicode emoji appear in the interface.

### Mascot Frame
- Rendered in a centered, clean circular or cloud-shaped backdrop well. Responsive to capacity states via animated expression paths rather than clinical percentage numbers.