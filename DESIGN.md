---
name: Cyber-Luxury Trading Identity
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
  on-surface-variant: '#e6bdbc'
  inverse-surface: '#e5e2e1'
  inverse-on-surface: '#313030'
  outline: '#ac8888'
  outline-variant: '#5c3f3f'
  surface-tint: '#ffb3b3'
  primary: '#ffb3b3'
  on-primary: '#680015'
  primary-container: '#dc143c'
  on-primary-container: '#fff1f0'
  inverse-primary: '#bf0030'
  secondary: '#ffffff'
  on-secondary: '#003737'
  secondary-container: '#00fbfb'
  on-secondary-container: '#007070'
  tertiary: '#ffb4a8'
  on-tertiary: '#690000'
  tertiary-container: '#cd3828'
  on-tertiary-container: '#fff1ef'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#ffdad9'
  primary-fixed-dim: '#ffb3b3'
  on-primary-fixed: '#40000a'
  on-primary-fixed-variant: '#920022'
  secondary-fixed: '#00fbfb'
  secondary-fixed-dim: '#00dddd'
  on-secondary-fixed: '#002020'
  on-secondary-fixed-variant: '#004f4f'
  tertiary-fixed: '#ffdad4'
  tertiary-fixed-dim: '#ffb4a8'
  on-tertiary-fixed: '#410000'
  on-tertiary-fixed-variant: '#920703'
  background: '#131313'
  on-background: '#e5e2e1'
  surface-variant: '#353534'
typography:
  display-lg:
    fontFamily: Sora
    fontSize: 72px
    fontWeight: '800'
    lineHeight: 80px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Sora
    fontSize: 40px
    fontWeight: '800'
    lineHeight: 48px
    letterSpacing: -0.01em
  headline-xl:
    fontFamily: Sora
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
  headline-lg:
    fontFamily: Sora
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-md:
    fontFamily: JetBrains Mono
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 20px
    letterSpacing: 0.05em
  label-sm:
    fontFamily: JetBrains Mono
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.1em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  unit: 8px
  container-max: 1440px
  gutter: 24px
  margin-desktop: 64px
  margin-mobile: 20px
  stack-sm: 12px
  stack-md: 24px
  stack-lg: 48px
---

## Brand & Style
The design system establishes a high-stakes, cinematic environment for premium trading education. The brand personality is aggressive yet disciplined, merging the high-tech aesthetics of a cyberpunk future with the exclusivity of luxury finance. The target audience includes sophisticated traders seeking an elite, immersive learning experience.

The visual style is a fusion of **Glassmorphism** and **High-Contrast / Bold** modernism. It utilizes deep spatial depth, 3D layering, and atmospheric neon lighting to create a UI that feels like a futuristic trading floor. Every interface element is treated as a physical, light-emitting object within a dark, multi-dimensional space.

## Colors
The palette is rooted in a "Void Black" foundation to maximize the luminosity of accent colors. 

- **Primary (Crimson Red):** Used for critical actions, bearish indicators, and primary branding. It represents energy, risk, and the "Wolf" spirit.
- **Secondary (Electric Blue):** Used for bullish indicators, data visualization, and interactive highlights. It provides a high-tech, digital contrast to the red.
- **Tertiary (Blood Red):** A deeper, darker red used for subtle background glows and low-priority warning states.
- **Neutrals:** Dark Charcoal and Metallic Gray provide the structural surfaces, ensuring the neon accents pop without causing visual fatigue.
- **Glows:** All interactive elements should feature a 15-30% opacity bloom effect using the Primary or Secondary colors.

## Typography
The typography system balances futuristic geometry with technical precision. 

**Sora** is the display typeface, chosen for its wide, geometric stance and "tech-luxe" feel. It should be used for all major headings and branding. **Inter** handles all body copy to ensure maximum legibility during complex data analysis. **JetBrains Mono** is utilized for labels, data points, and trading figures to evoke a developer-centric, high-accuracy environment.

Headlines should occasionally use uppercase styling with increased letter spacing for a more cinematic, architectural look.

## Layout & Spacing
The layout follows a **Fixed Grid** model on desktop to maintain the precision of a professional terminal, transitioning to a fluid stack on mobile. 

A 12-column grid is used for the main dashboard, while individual educational modules utilize a "Centric Focus" layout with wide margins to emphasize 3D assets. Spacing is generous to allow the "glow" of components to breathe without overlapping. 

**Breakpoints:**
- Mobile: < 768px (4 columns, 20px margins)
- Tablet: 768px - 1280px (8 columns, 40px margins)
- Desktop: > 1280px (12 columns, 64px margins)

## Elevation & Depth
Depth is the core of this design system. It is achieved through **Glassmorphism** and **Ambient Glows**:

1.  **Level 0 (Floor):** Pure black (#000000) with a faint, scrolling neon grid in Electric Blue at 5% opacity.
2.  **Level 1 (Card Base):** Dark Charcoal (#0D0D0D) with a 1px border of Metallic Gray at 20% opacity.
3.  **Level 2 (Floating Glass):** Semi-transparent surfaces (10-15% opacity) with a `backdrop-filter: blur(20px)`. These elements have a top-down linear gradient border to simulate light catching the "edge" of the glass.
4.  **Shadows:** Shadows are replaced by "Glows." Instead of dark offsets, elevated elements emit a soft, diffused bloom of Crimson or Electric Blue, indicating their active state or importance.

## Shapes
The shape language is sharp and technical. While a small radius (0.25rem) is used for standard UI components to keep them professional, specific "action" elements like primary buttons and 3D glass cards use hard geometric angles or very slight chamfers to maintain a futuristic edge.

Interactive elements should use a "Magnetic" hover effect, where the element slightly pulls towards the cursor, reinforcing the 3D physicality of the interface.

## Components

### Magnetic Buttons
Buttons feature a high-gloss finish. The primary button (Crimson Red) has a "Neon Pulse" animation on hover. Use `JetBrains Mono` for button text to maintain the technical aesthetic.

### 3D Glass Cards
Cards are the primary container. They must feature a subtle inner glow and a 1px "Refractive" border. On hover, the card should slightly tilt in 3D space based on the mouse position.

### Animated Trading Charts
Charts should use Electric Blue for gains and Crimson Red for losses. Lines should have a "trailing glow" effect, where the most recent data point emits a small light source.

### Input Fields
Inputs are "Ghost" style—transparent backgrounds with only a bottom border that illuminates in Electric Blue when focused. Labels should be small, uppercase `JetBrains Mono` positioned above the input.

### Glowing Grid
A background component consisting of a 3D perspective grid. The grid lines should flicker slightly to mimic a digital mainframe.

### Progress Chips
Small, pill-shaped indicators for course progress or market status. Use high-saturation colors with a heavy blur shadow (bloom) to make them appear like glowing LEDs.