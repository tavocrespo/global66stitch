---
name: Global Electric Fintech
colors:
  surface: '#f9f9ff'
  surface-dim: '#d0daf2'
  surface-bright: '#f9f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f0f3ff'
  surface-container: '#e8eeff'
  surface-container-high: '#dfe8ff'
  surface-container-highest: '#d9e3fb'
  on-surface: '#111c2d'
  on-surface-variant: '#434656'
  inverse-surface: '#273143'
  inverse-on-surface: '#ecf0ff'
  outline: '#737688'
  outline-variant: '#c3c5d9'
  surface-tint: '#004ee7'
  primary: '#0043c8'
  on-primary: '#ffffff'
  primary-container: '#0057ff'
  on-primary-container: '#e5e8ff'
  inverse-primary: '#b6c4ff'
  secondary: '#565e71'
  on-secondary: '#ffffff'
  secondary-container: '#dbe2f9'
  on-secondary-container: '#5c6477'
  tertiary: '#005e33'
  on-tertiary: '#ffffff'
  tertiary-container: '#007943'
  on-tertiary-container: '#98ffba'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dce1ff'
  primary-fixed-dim: '#b6c4ff'
  on-primary-fixed: '#001550'
  on-primary-fixed-variant: '#003ab2'
  secondary-fixed: '#dbe2f9'
  secondary-fixed-dim: '#bfc6dc'
  on-secondary-fixed: '#141b2c'
  on-secondary-fixed-variant: '#3f4759'
  tertiary-fixed: '#70fda7'
  tertiary-fixed-dim: '#51df8e'
  on-tertiary-fixed: '#00210e'
  on-tertiary-fixed-variant: '#00522c'
  background: '#f9f9ff'
  on-background: '#111c2d'
  surface-variant: '#d9e3fb'
typography:
  display:
    fontFamily: Inter
    fontSize: 40px
    fontWeight: '600'
    lineHeight: 48px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Inter
    fontSize: 26px
    fontWeight: '600'
    lineHeight: 34px
    letterSpacing: -0.015em
  headline-md:
    fontFamily: Inter
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 24px
    letterSpacing: -0.005em
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
    fontSize: 16px
    fontWeight: '600'
    lineHeight: 20px
  label-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 18px
  label-sm:
    fontFamily: Inter
    fontSize: 11px
    fontWeight: '500'
    lineHeight: 14px
    letterSpacing: 0.02em
  currency-input:
    fontFamily: Inter
    fontSize: 30px
    fontWeight: '500'
    lineHeight: 36px
    letterSpacing: -0.02em
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
  margin-tablet: 2rem
  margin-desktop: 3rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2rem
---

## Brand & Style

The design system establishes a consumer fintech experience centered on transparency, speed, and absolute financial security. Designed specifically for cross-border remittance and international multi-currency accounts, the UI combines Swiss-style utilitarian clarity with modern neo-banking warmth.

### Visual Aesthetic & Philosophy
- **Modern Minimalist Utility:** Interfaces prioritize cognitive ease. Information density is kept low on critical transactional screens like amount conversion, while key verification states are highlighted using rich contrast.
- **Airy Tactility:** Content rests on luminous off-white canvases (`#F7F8FA`) with pure white card surfaces (`#FFFFFF`). Micro-interactions utilize soft borders and ambient, high-diffusion drop shadows to lift interactive cards smoothly off the background.
- **Electric Accents:** The vibrant electric blue (`#0057FF`) commands the primary action loop, evoking technological velocity, confidence, and digital precision without visual fatigue.

## Colors

The palette leverages a focused set of functional tokens designed to guide remittance flows effortlessly:

- **Primary (`#0057FF`):** Vibrant electric blue used for primary CTA buttons, selected navigation states, interactive toggle badges, active currency indicators, and brand anchoring.
- **Secondary (`#101828`):** Deep obsidian slate used for dominant numerical amounts, primary headers, titles, and high-emphasis labels.
- **Tertiary (`#12B76A`):** Vivid emerald green reserved for positive monetary balances, transfer fee savings, completed transaction receipts, and live market rate gains.
- **Neutral (`#667085`):** Muted cool gray for sub-labels, input helper text, conversion disclaimers, timestamps, and secondary actions.
- **Canvas Base (`#F7F8FA`):** Soft, neutral cool ground providing a sterile backdrop that isolates foreground card surfaces.
- **Surface Card (`#FFFFFF`):** High-clarity white surface for interactive blocks, inputs, and bottom sheets.
- **Border Subtle (`#E4E7EC`):** Whisper-soft divider line used to segment input pairs (e.g., sending vs. receiving currency) and stroke cards cleanly without heavy visual noise.

## Typography

The typographic engine uses **Inter** throughout all tiers to guarantee pristine legibility, especially when rendering dense numerical strings, exchange rates, and small legal disclaimers.

- **Currency Inputs (`currency-input`):** Sized generously at `30px` (or `40px` on larger viewport states) with a balanced `500` medium weight, ensuring zeroes and decimals stay legible at a glance without crowding the currency selector.
- **Micro Disclaimers (`body-sm` / `label-sm`):** Optimized for regulatory footnotes (e.g., entity registration, intermediary disclosures) using `#667085` at `12px` and `11px` to maintain compliance without cluttering the transactional focus.
- **Headlines:** Tightly tracked (`-0.01em` to `-0.02em`) to produce a confident, institutional modern fintech impression.

## Layout & Spacing

The layout is built around mobile-first utility, scaling comfortably into responsive viewports while maintaining an app-shell discipline:

- **Mobile Viewport (320px – 480px):** Employs an exact `1.25rem` (20px) outer canvas margin. Content flows vertically with a single primary action anchored fixed to the bottom viewport (safe-area compliant).
- **Tablet & Web (481px+):** Centers financial workflows within a constrained max-width card container (max 480px for transfer cards; 720px for verification dashboards), transitioning gutters to `1.5rem` and outer canvas margins up to `3rem`.
- **Rhythm & Stacking:** 
  - Dual input modules (Transfer Out / Transfer In) stack tightly inside a single unified card or separated by micro-gutters (`space-xs` = 4px).
  - Floating swap buttons rest precisely on the horizontal divider separating the twin amount inputs.
  - Form field groupings and rate calculation breakdowns use standard `space-md` (16px) step intervals.

## Elevation & Depth

This system avoids heavy drop shadows, instead using airy ambient diffusion combined with hairline borders to maintain crispness:

- **Level 0 (Flat Ground):** `#F7F8FA` clean viewport base with no shadows.
- **Level 1 (Card & Module Surface):** `#FFFFFF` cards with a crisp `1px solid #E4E7EC` border and an ambient shadow: `0px 2px 8px rgba(16, 24, 40, 0.04)`.
- **Level 2 (Floating Action & Modals):** Currency swap badge icons, elevated action bars, and dropdown popovers: `0px 8px 24px rgba(16, 24, 40, 0.08)`, bounded by a subtle `1px solid rgba(228, 231, 236, 0.8)`.
- **Level 3 (Bottom Sheets & Drawers):** High-layer transactional summary sheets: `0px -8px 32px rgba(16, 24, 40, 0.12)`, fully occluding background canvas.

## Shapes

The interface embraces modern soft curvature based on the roundedness setting:

- **Standard Elements (`0.5rem` / 8px):** Subtle tags, utility icons, list row items, and internal currency flag tags.
- **Primary Cards & Containers (`rounded-xl` / `1rem` - `1.5rem` / 16px - 24px):** Main conversion containers, card surfaces, and input split-modules utilize generous `1.25rem` to `1.5rem` corners to create an inviting, consumer-friendly enclosure.
- **Pill Controls (`rounded-full` / 9999px):** Primary bottom CTAs ("Continuar"), currency selector pills, quick balance chips, and floating direction-swap badges (`40px x 40px` circular buttons).

## Components

### Currency Converter & Input Card
- **Structure:** A unified container (`#FFFFFF`, border `1px solid #E4E7EC`, radius `1.25rem`) partitioned into two interactive zones: "Tú envías" (You send) and "Tu contacto recibe" (Recipient receives).
- **Divider & Swap Trigger:** A centered horizontal border (`#E4E7EC`) interrupted precisely in the middle by a circular floating swap pill (`36px x 36px`, background `#EEF4FF`, icon `#0057FF`, shadow Level 1).
- **Input Field:** Zero-border numeric input, large `currency-input` typography (`#101828`), right-aligned with the currency selector.
- **Currency Dropdown Selector:** Pill-shaped tap target displaying a circular national flag, ISO code (`COP`, `USD`, `EUR`) in semi-bold Inter, and a subtle chevron icon (`#667085`).

### Buttons
- **Primary CTA:** Full-width pill (`height: 52px`, `rounded-full`), `#0057FF` solid background, text in white `label-lg`. Disabled state uses a clean desaturated fill (`#E4E7EC`) with muted text (`#98A2B3`), preventing high-contrast jumpiness.
- **Ghost & Navigation Items:** Clean, unbordered circular icon buttons (`40px`) with `#101828` or `#667085` back arrows and question marks.

### Rate Breakdown & Meta Details
- Minimal vertical stack (`space-sm` gaps). Left side indicates fee, exchange rate, and guaranteed arrival time in `body-sm` (`#667085`); right side aligns values in `body-sm` (`#101828`).

### Status Badges & Chips
- Rounded pills (`py-1`, `px-3`, radius `9999px`) featuring small currency indicators, transfer statuses (`#ECFDF3` background with `#12B76A` text for "Completado"), and live FX rate indicators.