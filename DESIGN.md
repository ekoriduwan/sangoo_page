---
name: Sangoo Hyper-Social Finance
colors:
  surface: '#f9f9f9'
  surface-dim: '#dadada'
  surface-bright: '#f9f9f9'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f3f3f3'
  surface-container: '#eeeeee'
  surface-container-high: '#e8e8e8'
  surface-container-highest: '#e2e2e2'
  on-surface: '#1b1b1b'
  on-surface-variant: '#4d4632'
  inverse-surface: '#303030'
  inverse-on-surface: '#f1f1f1'
  outline: '#7f775f'
  outline-variant: '#d0c6ab'
  surface-tint: '#705d00'
  primary: '#705d00'
  on-primary: '#ffffff'
  primary-container: '#ffd600'
  on-primary-container: '#705d00'
  inverse-primary: '#e9c400'
  secondary: '#b70052'
  on-secondary: '#ffffff'
  secondary-container: '#e50069'
  on-secondary-container: '#fffbff'
  tertiary: '#00629e'
  on-tertiary: '#ffffff'
  tertiary-container: '#bedcff'
  on-tertiary-container: '#00629f'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffe170'
  primary-fixed-dim: '#e9c400'
  on-primary-fixed: '#221b00'
  on-primary-fixed-variant: '#544600'
  secondary-fixed: '#ffd9df'
  secondary-fixed-dim: '#ffb1c1'
  on-secondary-fixed: '#3f0018'
  on-secondary-fixed-variant: '#8f003f'
  tertiary-fixed: '#cfe5ff'
  tertiary-fixed-dim: '#9acbff'
  on-tertiary-fixed: '#001d34'
  on-tertiary-fixed-variant: '#004a79'
  background: '#f9f9f9'
  on-background: '#1b1b1b'
  surface-variant: '#e2e2e2'
typography:
  headline-xl:
    fontFamily: Lexend
    fontSize: 48px
    fontWeight: '800'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Lexend
    fontSize: 32px
    fontWeight: '800'
    lineHeight: '1.2'
  headline-lg-mobile:
    fontFamily: Lexend
    fontSize: 28px
    fontWeight: '800'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Lexend
    fontSize: 24px
    fontWeight: '700'
    lineHeight: '1.3'
  body-lg:
    fontFamily: Lexend
    fontSize: 18px
    fontWeight: '500'
    lineHeight: '1.5'
  body-md:
    fontFamily: Lexend
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.5'
  label-bold:
    fontFamily: Lexend
    fontSize: 14px
    fontWeight: '700'
    lineHeight: '1'
    letterSpacing: 0.05em
  label-sm:
    fontFamily: Lexend
    fontSize: 12px
    fontWeight: '600'
    lineHeight: '1'
spacing:
  unit: 8px
  gutter: 16px
  margin-mobile: 20px
  margin-desktop: 40px
  stack-sm: 8px
  stack-md: 16px
  stack-lg: 32px
---

## Brand & Style

This design system is built on the principles of **Neobrutalism**, specifically tailored for a younger demographic that views finance as a social, active part of their lifestyle rather than a passive chore. It rejects the clinical, "safe" aesthetics of traditional fintech in favor of raw energy, high-impact visuals, and unapologetic presence.

The brand personality is **audacious, kinetic, and transparent**. It utilizes heavy graphical strokes and high-saturation palettes to create a "social media for money" atmosphere. The UI should feel like a physical object—tactile, chunky, and deliberate—inducing an emotional response of confidence and excitement. 

Key stylistic pillars:
- **High-Contrast Definition:** Every interactive element is bounded by thick, dark strokes.
- **Hard Depth:** Shadows are never blurred; they are solid, offset blocks of color or black.
- **Intentional Friction:** Large, bold components prioritize clarity and "vibe" over data density.

## Colors

The color strategy for this design system revolves around a "Vivid-Primary" palette. Unlike traditional apps that use color for status only, this system uses color as a structural and social tool.

- **Primary (Electric Yellow):** The main brand signal. Used for primary actions and "Money In" states.
- **Secondary (Vibrant Pink):** The social signal. Used for community features, peer-to-peer interactions, and notifications.
- **Tertiary (Electric Blue):** Used for savings, stability, and long-term financial goals.
- **Quaternary (Lime Green):** Used for growth, rewards, and successful transaction states.
- **Neutral (Absolute Black/White):** Every component must be outlined in `#000000` to maintain the Neobrutalist aesthetic. Use pure white for card backgrounds to let the vivid accent colors pop.

## Typography

Typography in this design system is loud and functional. **Lexend** was chosen specifically for its history in improving reading proficiency and its unique, wide geometric stance that fits the Neobrutalist aesthetic perfectly.

- **Headlines:** Must always be Heavy (800) or Bold (700) weight. Large headlines should use tight tracking to emphasize the "blocky" feel.
- **Body:** Kept clean but never light. Use Medium (500) for important information to ensure it holds its own against thick borders.
- **Labels:** Use uppercase for functional labels (buttons, tabs) to increase their presence as UI "objects."
- **Scale:** Maintain a significant contrast between headline sizes and body text to establish a clear hierarchy in data-heavy financial views.

## Layout & Spacing

This design system uses a **fixed-fluid hybrid grid**. While the layout expands to fill the screen, components behave like rigid tiles.

- **The 8px Rhythm:** All spacing must be multiples of 8px. Gutters are strictly 16px to maintain a dense, energetic feel.
- **Container Strategy:** Use a 12-column grid for desktop and a 4-column grid for mobile.
- **Padding:** Internal component padding should be generous (minimum 16px) to ensure that the thick 2px-4px borders do not crowd the content.
- **Alignment:** Use "Hard-Start" alignment—flush left for most text and headers to emphasize the vertical grid lines created by stacked cards.

## Elevation & Depth

In this design system, elevation is not simulated with light and air (blur); it is simulated with **physical displacement**.

- **Hard Shadows:** Use solid black `#000000` shadows with 100% opacity. 
- **The "Shift" Rule:** Depth is created by offsetting a shadow by 4px or 8px on both the X and Y axes. 
- **State Changes:** When an element is pressed or "active," the shadow offset should decrease (e.g., from 4px to 0px), visually pushing the component into the page.
- **Borders:** All containers must have a solid black border. Use `2px` for small components (chips, inputs) and `4px` for large containers (cards, modals).

## Shapes

The shape language is strictly **Geometric and Sharp (0)**. 

By using 0px border radii, the design system leans into the "Brutalist" aspect of its name, creating a UI that feels architectural and structural. 

- **Exceptions:** Icons may use rounded terminals for playfulness, but their containers must remain rectangular.
- **Strokes:** All shapes are defined by their stroke. If a shape has a fill, it must also have a black border. Never use "borderless" colored shapes.

## Components

- **Buttons:** Large, rectangular, and filled with primary or secondary colors. They must have a 2px black border and a 4px black hard shadow. Text is bold and centered.
- **Cards:** White or very light gray background with a 4px black border. Use a 8px hard shadow to indicate high priority (e.g., total balance card).
- **Input Fields:** Thick 2px borders. On focus, the background shifts from white to the tertiary blue or primary yellow, and the hard shadow appears.
- **Chips/Badges:** Use a 2px border with a 0px shadow. These are the only small elements allowed to have a vivid background color without being a primary action.
- **Lists:** Transaction items should be separated by thick 2px horizontal lines. Each list item acts as a "flat card"—interactive but without a shadow until hovered or pressed.
- **Social Feed Cards:** These combine vivid headers (using the secondary pink) with white body areas to differentiate "Money Talk" from "Money Math."