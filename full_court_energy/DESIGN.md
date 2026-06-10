---
name: Full Court Energy
colors:
  surface: '#131313'
  surface-dim: '#131313'
  surface-bright: '#393939'
  surface-container-lowest: '#0e0e0e'
  surface-container-low: '#1b1b1b'
  surface-container: '#1f1f1f'
  surface-container-high: '#2a2a2a'
  surface-container-highest: '#353535'
  on-surface: '#e2e2e2'
  on-surface-variant: '#ddc1ae'
  inverse-surface: '#e2e2e2'
  inverse-on-surface: '#303030'
  outline: '#a48c7a'
  outline-variant: '#564334'
  surface-tint: '#ffb77d'
  primary: '#ffb77d'
  on-primary: '#4d2600'
  primary-container: '#ff8c00'
  on-primary-container: '#623200'
  inverse-primary: '#904d00'
  secondary: '#c6c6c7'
  on-secondary: '#2f3131'
  secondary-container: '#454747'
  on-secondary-container: '#b4b5b5'
  tertiary: '#85cfff'
  on-tertiary: '#00344c'
  tertiary-container: '#00b5fc'
  on-tertiary-container: '#004360'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#ffdcc3'
  primary-fixed-dim: '#ffb77d'
  on-primary-fixed: '#2f1500'
  on-primary-fixed-variant: '#6e3900'
  secondary-fixed: '#e2e2e2'
  secondary-fixed-dim: '#c6c6c7'
  on-secondary-fixed: '#1a1c1c'
  on-secondary-fixed-variant: '#454747'
  tertiary-fixed: '#c7e7ff'
  tertiary-fixed-dim: '#85cfff'
  on-tertiary-fixed: '#001e2e'
  on-tertiary-fixed-variant: '#004c6c'
  background: '#131313'
  on-background: '#e2e2e2'
  surface-variant: '#353535'
typography:
  display-lg:
    fontFamily: Anybody
    fontSize: 48px
    fontWeight: '800'
    lineHeight: 52px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Anybody
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Anybody
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 36px
  headline-md:
    fontFamily: Anybody
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 32px
  body-lg:
    fontFamily: Chivo
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Chivo
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-lg:
    fontFamily: Chivo
    fontSize: 14px
    fontWeight: '700'
    lineHeight: 20px
    letterSpacing: 0.05em
  label-sm:
    fontFamily: Chivo
    fontSize: 12px
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
  base: 8px
  container-margin: 20px
  gutter: 12px
  stack-sm: 4px
  stack-md: 16px
  stack-lg: 32px
---

## Brand & Style

The design system is engineered to evoke the high-octane atmosphere of a premium indoor basketball arena. It targets athletes and enthusiasts who demand efficiency, precision, and a professional-grade experience. 

The aesthetic is **High-Contrast / Bold**, utilizing a "Dark Mode by Default" strategy to make the vibrant orange accents pop with maximum intensity. We lean into a clean, athletic minimalism—stripping away unnecessary ornamentation to focus on action, availability, and performance. The visual language is direct, energetic, and authoritative, mirroring the intensity of a game-winning shot.

## Colors

The palette is intentionally restricted to amplify brand recognition and maintain a focused athletic vibe.

- **Primary (Vibrant Orange):** Used for primary actions, active states, and key highlights. It represents the ball and the energy of the court.
- **Neutral (Deep Black):** The foundation. It provides a limitless depth that makes content feel premium and reduces eye strain during evening use.
- **Secondary (Pure White):** Reserved for high-legibility text and critical iconography against the black background.
- **Surface (Deep Gray):** A subtle #121212 or #1A1A1A is used to differentiate cards and containers from the pure black background without breaking the high-contrast rhythm.

## Typography

This design system utilizes a dual-sans-serif approach to balance expression with utility.

- **Anybody** is the voice of the brand. Its variable width and aggressive weights are used for headlines and "hero" moments. It feels fast and technical.
- **Chivo** provides the structural support. Its high legibility and sharp terminals make it perfect for reading court details, booking times, and interface labels.

Use **uppercase styling** for labels and category headers to reinforce the "scoreboard" aesthetic.

## Layout & Spacing

The layout follows a strict 8px rhythm to maintain a disciplined, professional grid. 

- **Mobile First:** Content should be primarily stacked with a 20px safe margin on the horizontal axis.
- **Verticality:** Use generous vertical spacing (`stack-lg`) between logical sections (e.g., "Nearby Courts" vs "Your Bookings") to prevent the UI from feeling cluttered.
- **Grid:** For court listings or time slots, use a 2-column grid with a 12px gutter to maximize information density while maintaining touch targets.

## Elevation & Depth

This design system eschews traditional soft shadows in favor of **Tonal Layering** and **High-Contrast Outlines**.

- **Level 0 (Base):** Pure Black (#000000).
- **Level 1 (Cards/Containers):** Deep Gray (#121212) with a 1px solid border of #1A1A1A.
- **Active State:** When a card or element is selected, the border should switch to the Primary Orange (#FF8C00).
- **Navigation:** The bottom navigation bar is an exception, using a solid Primary Orange background. Icons and text on this bar must be Pure Black (#000000) for maximum accessibility.

## Shapes

The shape language is **Soft (0.25rem/4px)**. 

While the brand is aggressive, perfectly sharp corners feel dated and brittle. A slight 4px radius on buttons and cards provides a modern, "precision-engineered" feel. 
- **Buttons:** Use 4px corner radius for standard buttons.
- **Chips:** Use a full pill-shape (circular ends) for status tags like "Available" or "Outdoor" to contrast against the more rigid card structures.

## Components

- **Buttons:** 
    - **Primary:** Solid Orange (#FF8C00) with Black text. Bold, uppercase labels.
    - **Secondary:** Outline (1px White) with White text.
- **Bottom Navigation:** Solid Orange background. Icons should be minimalist line-art or solid shapes in Black. No blur or transparency.
- **Input Fields:** Black background with a 1px White or Gray border. Upon focus, the border turns Orange.
- **Court Cards:** Use the Level 1 Surface color (#121212). Image headers should have a slight gradient overlay at the bottom to ensure text legibility.
- **Chips:** Small, pill-shaped tags used for "Court Surface" or "Distance." Use a dark gray background with white text for inactive chips, and orange for active ones.
- **Booking Calendar:** A horizontal scrolling row of dates. The "Today" or selected date is highlighted with a solid orange circle or square.