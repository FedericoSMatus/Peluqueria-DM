---
name: Warm Boutique Luxury
colors:
  surface: '#fbf9f6'
  surface-dim: '#dbdad7'
  surface-bright: '#fbf9f6'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f5f3f0'
  surface-container: '#efeeeb'
  surface-container-high: '#eae8e5'
  surface-container-highest: '#e4e2df'
  on-surface: '#1b1c1a'
  on-surface-variant: '#4d4541'
  inverse-surface: '#30312f'
  inverse-on-surface: '#f2f0ed'
  outline: '#7e7570'
  outline-variant: '#d0c4be'
  surface-tint: '#615e5c'
  primary: '#000000'
  on-primary: '#ffffff'
  primary-container: '#1d1b1a'
  on-primary-container: '#878381'
  inverse-primary: '#cbc5c3'
  secondary: '#755a26'
  on-secondary: '#ffffff'
  secondary-container: '#ffdb9b'
  on-secondary-container: '#795e2a'
  tertiary: '#000000'
  on-tertiary: '#ffffff'
  tertiary-container: '#2b160e'
  on-tertiary-container: '#9d7d71'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e7e1df'
  primary-fixed-dim: '#cbc5c3'
  on-primary-fixed: '#1d1b1a'
  on-primary-fixed-variant: '#494645'
  secondary-fixed: '#ffdea6'
  secondary-fixed-dim: '#e5c283'
  on-secondary-fixed: '#271900'
  on-secondary-fixed-variant: '#5b4310'
  tertiary-fixed: '#ffdbce'
  tertiary-fixed-dim: '#e4beb1'
  on-tertiary-fixed: '#2b160e'
  on-tertiary-fixed-variant: '#5b4137'
  background: '#fbf9f6'
  on-background: '#1b1c1a'
  surface-variant: '#e4e2df'
typography:
  display-hero:
    fontFamily: Playfair Display
    fontSize: 56px
    fontWeight: '400'
    lineHeight: 64px
    letterSpacing: -0.02em
  display-hero-mobile:
    fontFamily: Playfair Display
    fontSize: 38px
    fontWeight: '400'
    lineHeight: 44px
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Playfair Display
    fontSize: 36px
    fontWeight: '500'
    lineHeight: 44px
    letterSpacing: -0.015em
  headline-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 28px
    fontWeight: '500'
    lineHeight: 34px
    letterSpacing: 0em
  headline-md:
    fontFamily: Playfair Display
    fontSize: 24px
    fontWeight: '500'
    lineHeight: 32px
    letterSpacing: 0em
  title-editorial:
    fontFamily: Playfair Display
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 26px
    letterSpacing: 0.01em
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
    letterSpacing: -0.005em
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 15px
    fontWeight: '400'
    lineHeight: 24px
    letterSpacing: 0em
  body-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 20px
    letterSpacing: 0.005em
  label-prominent:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 18px
    letterSpacing: 0.03em
  label-caps:
    fontFamily: Plus Jakarta Sans
    fontSize: 11px
    fontWeight: '700'
    lineHeight: 16px
    letterSpacing: 0.12em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1.5rem
  margin: 2rem
  space-xs: 0.375rem
  space-sm: 0.75rem
  space-md: 1.25rem
  space-lg: 2rem
  space-xl: 3.5rem
---

## Brand & Style

This design system embodies warm boutique luxury tailored for high-end hospitality and beauty services in metropolitan fashion districts like Palermo Soho. The identity blends timeless European editorial sophistication with warm South American hospitality, exuding relaxation, bespoke craftsmanship, and effortless elegance.

The visual expression leans on an elevated, tactile minimalism:
- **Atmospheric Warmth:** Replacing clinical cool grays and sterile whites with rich bone, cream, linen, and carbon black.
- **Editorial Poise:** High-fashion serif typography paired with airy, disciplined sans-serif controls.
- **Sensory Tactility:** Subtle luminous micro-borders, champagne-tinted frosted glass, soft elevations, and intentional touch targets crafted for friction-free reservation flows.

## Colors

The palette establishes an organic luxury tone that honors hair care, botanical rituals, and architectural boutique interiors:

- **Primary (`#1A1817` - Carbon Black):** Deep, warm charcoal black used for core brand presence, high-priority interactive calls to action, headers, and crisp structural text. Never pure `#000000`.
- **Secondary (`#C8A76B` - Brushed Champagne Gold):** A refined metallic accent applied to badges, rating indicators, active states, active tab lines, and promotional callouts. Its deeper pairing value is `#B89758` for accessible text contrast.
- **Tertiary (`#D9B4A7` - Dusty Terracotta Rose):** A warm, soft highlight for service tags, treatment highlights, subtle tint fills, and festive notifications. Accompanied by `#E8D8CF` as an ultra-soft background wash.
- **Neutral Canvas (`#FAF8F5` - Warm Bone & `#F3EFEA` - Soft Linen):** Foundational surfaces that create warmth and comfort, steering far clear of harsh blue-white screens.

For surface transitions:
- `surface-base`: `#FAF8F5`
- `surface-subtle`: `#F3EFEA`
- `surface-elevated`: `#FFFFFF` with muted warm borders (`rgba(26, 24, 23, 0.06)`)
- `text-muted`: `rgba(26, 24, 23, 0.62)`
- `border-glass`: `rgba(200, 167, 107, 0.22)`

## Typography

The typographic tension pairs the classic haute-couture styling of **Playfair Display** with the clear, modern geometry of **Plus Jakarta Sans**.

- **Playfair Display:** Preserved strictly for high-impact brand statements, section headers, service names, and hero banners. Always maintain generous line heights to prevent overlapping ascenders and descenders.
- **Plus Jakarta Sans:** Handles all transactional operations, interactive buttons, appointment calendars, pricing lists, metadata, and form controls. Its humanist curves complement the warm salon environment without compromising legibility.
- **`label-caps` Rule:** When rendering uppercase kicker titles or category tags (e.g., "BALAYAGE & COLORACIÓN"), use `label-caps` with wide letter-spacing (`0.12em`) to induce an editorial magazine feel.

## Layout & Spacing

The layout philosophy uses a disciplined responsive 12-column grid system paired with intentional, generous negative space to evoke relaxation:

- **Desktop (>= 1024px):** 12 columns, `margin: 3.5rem`, `gutter: 1.5rem`. Max layout container width: 1240px centered.
- **Tablet (768px – 1023px):** 8 columns, `margin: 2rem`, `gutter: 1.25rem`.
- **Mobile (< 768px):** 4 columns, `margin: 1.25rem`, `gutter: 1rem`.

Rhythm instructions:
- Sections must breathe: separate major thematic sections (e.g., stylist profiles, ritual menus, booking picker) with `space-xl` (or multiples of it).
- Booking cards and selection tiles use compact interior spacing (`space-md`) coupled with generous exterior grouping margins to prevent decision fatigue.

## Elevation & Depth

Visual hierarchy is maintained through subtle ambient warmth and luminous translucent overlays rather than heavy artificial drop shadows:

- **Level 0 (Flat):** Native background surfaces (`#FAF8F5` or `#F3EFEA`).
- **Level 1 (Card & Service Tile):** Pure white container `#FFFFFF` with a hairline warm border `1px solid rgba(26, 24, 23, 0.05)` and an ambient, ultra-soft shadow: `0 4px 20px -2px rgba(26, 24, 23, 0.04)`.
- **Level 2 (Interactive Floating / Dropdowns / Sticky Nav):** Glassmorphic surface crafted with `background: rgba(250, 248, 245, 0.85)`, backdrop filter blur of `16px`, bordered by `1px solid rgba(200, 167, 107, 0.25)`, and shadow `0 12px 32px -4px rgba(26, 24, 23, 0.08)`.
- **Level 3 (Modals & Booking Drawer):** `background: #FFFFFF`, hairline border `1px solid rgba(26, 24, 23, 0.08)`, cast with a warm deep-tinted shadow `0 24px 48px -12px rgba(26, 24, 23, 0.16)`.

## Shapes

The interface embraces a gentle, welcoming shape language centered on rounded luxury:

- Standard cards, interactive blocks, and schedule pickers employ `rounded-2xl` (1.25rem / 20px) to mirror organic interior curves and boutique architecture.
- Small interactive utility items (chips, time badges, action pills) use `rounded-full` for instant touch recognition.
- Text inputs and form fields use standard `rounded-lg` (0.75rem / 12px) to preserve structure and clean vertical alignment.
- Image containers featuring hair styling transformations feature soft continuous rounded corners with an internal warm inset stroke (`inset 0 0 0 1px rgba(255, 255, 255, 0.2)`).

## Components

### Buttons
- **Primary (Booking / Action Priority):** Carbon black background (`#1A1817`), bone white text (`#FAF8F5`), minimum height `52px` for comfortable tap targets. Border radius `9999px` (pill) or `14px`. Hover state subtly raises the element with a faint champagne shadow: `0 8px 20px rgba(26, 24, 23, 0.18)`.
- **Secondary (Boutique Outlined):** Transparent background, `1.5px` border in `#1A1817` or `#C8A76B`, text in `#1A1817`. On hover: fills with `#F3EFEA` or solid gold.
- **Tertiary / Ghost:** No border or fill, `14px` bold text in `#1A1817` with a delicate underline animation expanding from center.

### Chips & Filter Pills
- Filter pills (e.g., category selection like "Balayage", "Corte & Styling", "Tratamientos"):
  - Inactive: Background `#FFFFFF`, border `1px solid rgba(26, 24, 23, 0.08)`, text `#1A1817` (`body-sm`).
  - Active: Background `#1A1817`, text `#FAF8F5`, border `1px solid #1A1817`.

### Service & Price Cards
- High-comfort cards (`rounded-2xl`, background `#FFFFFF`, ambient shadow).
- Header presents service name in `title-editorial` (`Playfair Display`), duration (e.g., "90 min") in `body-sm` muted text, and price tagged with warm champagne accent `#C8A76B`.
- Bottom slot incorporates a direct "Reservar Turno" micro-CTA button.

### Form Inputs & Date/Time Pickers
- Input height `48px`, background `#FFFFFF` or `#F3EFEA`, border `1px solid rgba(26, 24, 23, 0.12)`, radius `12px`.
- Focus state: Border shifts to brushed gold `#C8A76B` with a `0 0 0 3px rgba(200, 167, 107, 0.15)` ring glow.
- Calendar slots: Selected time slot turns `#1A1817` with `#FAF8F5` text; unavailable slots take `opacity: 0.35` with line-through styling.

### Radio & Stylist Selectors
- Stylist selector cards feature circular portrait avatars (`64px x 64px`) with a fine gold ring indicator (`2px solid #C8A76B`) when chosen.
- Checkboxes & radios replace standard browser controls with custom brushed champagne accents and smooth scale-in checks.