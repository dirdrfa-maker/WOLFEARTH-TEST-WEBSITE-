---
name: Apex Predator Aesthetic
colors:
  surface: '#131314'
  surface-dim: '#131314'
  surface-bright: '#3a393a'
  surface-container-lowest: '#0e0e0f'
  surface-container-low: '#1c1b1c'
  surface-container: '#201f20'
  surface-container-high: '#2a2a2b'
  surface-container-highest: '#353436'
  on-surface: '#e5e2e3'
  on-surface-variant: '#e8bcb6'
  inverse-surface: '#e5e2e3'
  inverse-on-surface: '#313031'
  outline: '#ae8782'
  outline-variant: '#5e3f3b'
  surface-tint: '#ffb4aa'
  primary: '#ffb4aa'
  on-primary: '#690003'
  primary-container: '#e61919'
  on-primary-container: '#fffbff'
  inverse-primary: '#c0000b'
  secondary: '#98cbff'
  on-secondary: '#003354'
  secondary-container: '#00a2fd'
  on-secondary-container: '#003558'
  tertiary: '#fbbc09'
  on-tertiary: '#402d00'
  tertiary-container: '#956e00'
  on-tertiary-container: '#fffbff'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#ffdad5'
  primary-fixed-dim: '#ffb4aa'
  on-primary-fixed: '#410001'
  on-primary-fixed-variant: '#930006'
  secondary-fixed: '#cfe5ff'
  secondary-fixed-dim: '#98cbff'
  on-secondary-fixed: '#001d33'
  on-secondary-fixed-variant: '#004a77'
  tertiary-fixed: '#ffdea0'
  tertiary-fixed-dim: '#fbbc09'
  on-tertiary-fixed: '#261a00'
  on-tertiary-fixed-variant: '#5c4300'
  background: '#131314'
  on-background: '#e5e2e3'
  surface-variant: '#353436'
typography:
  display-lg:
    fontFamily: Anton
    fontSize: 72px
    fontWeight: '400'
    lineHeight: 80px
    letterSpacing: 0.02em
  headline-xl:
    fontFamily: Anton
    fontSize: 48px
    fontWeight: '400'
    lineHeight: 56px
    letterSpacing: 0.03em
  headline-xl-mobile:
    fontFamily: Anton
    fontSize: 32px
    fontWeight: '400'
    lineHeight: 40px
  headline-md:
    fontFamily: Anton
    fontSize: 24px
    fontWeight: '400'
    lineHeight: 32px
  body-lg:
    fontFamily: Geist
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Geist
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-data:
    fontFamily: JetBrains Mono
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 20px
    letterSpacing: 0.05em
  label-sm:
    fontFamily: Geist
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
spacing:
  unit: 4px
  container-max: 1440px
  gutter: 24px
  margin-desktop: 64px
  margin-mobile: 16px
---

## Brand & Style

This design system is built for "Wolfearth School Trade," targeting a demographic that values high-performance, intensity, and competitive edge. The brand personality is aggressive, decisive, and commanding. It draws heavily from **High-Contrast / Bold** and **Cyberpunk-inspired Modernism**, utilizing a "dark mode by default" philosophy to create a focused, high-stakes trading environment.

The UI should evoke a sense of power and predatory precision. We achieve this through:
- **Sharp Geometry:** Mirroring the jagged, aggressive lines of the wolf logo.
- **Kinetic Energy:** Using vibrant accent colors against obsidian backdrops to draw focus to critical data.
- **High-Performance Cues:** Subtle glows and neon "status" indicators that suggest a live, breathing market ecosystem.

## Colors

The palette is engineered for maximum visual impact and immediate cognitive processing of financial data.

- **Primary (Blood Red):** Used for critical actions, sell signals, and high-urgency alerts. It is the color of the "hunt."
- **Secondary (Electric Blue):** Used for buy signals, progress indicators, and interactive elements. It provides a technical, digital contrast to the primal red.
- **Tertiary (Wolf Eye Gold):** Reserved for highlights, warnings, or special achievement tiers.
- **Neutrals:** A range of "Obsidian" blacks (#050505) and "Charcoal" grays (#1A1A1C) are used for surfaces to ensure the accent colors "pop" with maximum intensity.

## Typography

The typographic scale is designed for readability and dominance. 

- **Headlines:** Uses **Anton** for its condensed, impactful, and aggressive stature. Headlines should frequently use `uppercase` to maintain the authoritative voice.
- **Body:** Uses **Geist** for a clean, technical, and highly legible experience during long reading sessions or complex data analysis.
- **Data/Labels:** Uses **JetBrains Mono** for all numerical data, tickers, and price points. The monospaced nature ensures that fluctuating numbers do not cause layout shifts and feel "engineered."

## Layout & Spacing

The design system utilizes a **12-column fluid grid** with a tight, efficient spacing rhythm.

- **Density:** The UI is high-density, maximizing the information visible on-screen at once. 
- **Grid Models:** On desktop, use a 12-column grid with 24px gutters. On mobile, transition to a 4-column grid with 16px margins.
- **Rhythm:** All spacing is based on a 4px baseline unit. Internal component padding should be tight (e.g., 8px or 12px) to maintain the "high-performance dashboard" feel.

## Elevation & Depth

In a dark, aggressive UI, traditional shadows are replaced by **Tonal Layering** and **Luminescence**.

- **Surface Levels:** 
    - **L0 (Base):** #050505 (Pure black background).
    - **L1 (Cards/Panels):** #0D0D0E (Subtle dark gray).
    - **L2 (Popovers/Modals):** #161618 (Slightly lighter, with a subtle border).
- **Glow Effects:** Critical elements (like active trade buttons or "Live" indicators) utilize a `0px 0px 15px` outer glow in the primary or secondary color to simulate a digital screen effect.
- **Borders:** Instead of heavy shadows, use 1px solid borders (#222) to define edges. For active states, these borders should glow with the primary accent color.

## Shapes

The shape language is strictly **Sharp (0px)**. 

To mirror the aggressive "fangs" and "claws" of the brand's wolf mascot, all buttons, input fields, cards, and containers must have 90-degree corners. Rounded corners are prohibited as they soften the brand's "predatory" edge. 

For decorative elements, use diagonal "cut-outs" or chamfered corners (45-degree angles) on buttons and tabs to reinforce the high-tech, aggressive aesthetic.

## Components

- **Buttons:** Primary buttons use a solid #E61919 background with white Anton text. Use a "cut-corner" clip-path on the top-right to add aggression. Hover states should trigger a red outer glow.
- **Input Fields:** Obsidian background (#0A0A0B) with a 1px #333 border. On focus, the border changes to Electric Blue with a subtle inner glow.
- **Cards:** No background color or a very dark gray (#0D0D0E). Use a top-accent border (2px) in the secondary color to denote category.
- **Chips/Status:** For "Success" or "Buy," use Electric Blue text with a subtle 10% opacity blue background. For "Danger" or "Sell," use Blood Red.
- **Data Viz:** Charts should use high-contrast lines. Area charts should use gradients that fade from the accent color at the top to transparent at the bottom.
- **Lists:** High-density rows with 1px divider lines (#1A1A1C). Use JetBrains Mono for all numeric values in the list.