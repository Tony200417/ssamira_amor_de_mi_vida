---
name: Luminous Keepsake
colors:
  surface: '#fbf9f1'
  surface-dim: '#dcdad2'
  surface-bright: '#fbf9f1'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f5f4ec'
  surface-container: '#f0eee6'
  surface-container-high: '#eae8e0'
  surface-container-highest: '#e4e3db'
  on-surface: '#1b1c17'
  on-surface-variant: '#50443e'
  inverse-surface: '#30312c'
  inverse-on-surface: '#f3f1e9'
  outline: '#82746d'
  outline-variant: '#d4c3bb'
  surface-tint: '#7a5642'
  primary: '#7a5642'
  on-primary: '#ffffff'
  primary-container: '#dcae96'
  on-primary-container: '#62412e'
  inverse-primary: '#ecbda4'
  secondary: '#735c00'
  on-secondary: '#ffffff'
  secondary-container: '#fed65b'
  on-secondary-container: '#745c00'
  tertiary: '#855324'
  on-tertiary: '#ffffff'
  tertiary-container: '#eaaa73'
  on-tertiary-container: '#6a3d0f'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdbca'
  primary-fixed-dim: '#ecbda4'
  on-primary-fixed: '#2e1506'
  on-primary-fixed-variant: '#603f2d'
  secondary-fixed: '#ffe088'
  secondary-fixed-dim: '#e9c349'
  on-secondary-fixed: '#241a00'
  on-secondary-fixed-variant: '#574500'
  tertiary-fixed: '#ffdcc1'
  tertiary-fixed-dim: '#fbb980'
  on-tertiary-fixed: '#2e1500'
  on-tertiary-fixed-variant: '#693c0e'
  background: '#fbf9f1'
  on-background: '#1b1c17'
  surface-variant: '#e4e3db'
typography:
  display-handwritten:
    fontFamily: cursive
    fontSize: 48px
    fontWeight: '400'
    lineHeight: '1.2'
    letterSpacing: 0.02em
  headline-lg:
    fontFamily: Noto Serif
    fontSize: 32px
    fontWeight: '400'
    lineHeight: '1.3'
  body-md:
    fontFamily: Newsreader
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  label-sm:
    fontFamily: Newsreader
    fontSize: 14px
    fontWeight: '600'
    lineHeight: '1.4'
    letterSpacing: 0.05em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  unit: 8px
  margin-page: 40px
  gutter-canvas: 24px
  stack-sm: 12px
  stack-md: 24px
---

## Brand & Style

This design system is anchored in the emotional resonance of a handwritten journal and the tactile joy of physical scrapbooking. It targets a demographic that values intentionality, memory-keeping, and high-aesthetic curation. The goal is to evoke a sense of quiet intimacy and "slow living" through a digital medium.

The design style is **Tactile Skeuomorphism**. It moves away from the sterile flatness of modern software, instead embracing the "perfectly imperfect" qualities of physical objects. By layering realistic textures—such as deckled-edge paper, subtle grain, and semi-transparent washi tape—the UI invites the user to feel as though they are touching their memories. The aesthetic is romantic and nostalgic, yet polished enough to feel like a premium, heirloom-quality product.

## Colors

The palette is designed to feel warm, aged, and expensive. 

- **Ivory (#FFFDF5):** The foundation. This is used for all primary backgrounds to simulate high-quality cotton paper.
- **Dusty Rose (#DCAE96):** The primary brand color. It provides a soft, romantic touch used for interactive elements and highlights.
- **Champagne Gold (#D4AF37):** Used sparingly for "jewelry" moments—borders, icons, and sophisticated accents that suggest a gilded edge.
- **Warm Sepia (#704214) & Deep Charcoal (#363636):** Used for typography to ensure high readability while avoiding the harshness of pure black, maintaining the vintage ink aesthetic.

## Typography

This design system utilizes a tiered typography approach to balance romanticism with legibility. 

- **Handwritten Accent:** While not explicitly in the token set, a custom cursive font (resembling Great Vibes) is reserved for personal notes, dates, and sign-offs to simulate a human hand.
- **Headlines:** `Noto Serif` provides a sophisticated, timeless structure for page titles and section headers.
- **Body & Labels:** `Newsreader` is utilized for its literary, classic feel. It ensures that long-form memories are comfortable to read, mimicking the experience of reading a vintage novel. 

Text should never be pure black; use the Warm Sepia or Deep Charcoal tokens to maintain the ink-on-paper illusion.

## Layout & Spacing

The layout follows a **Fixed Canvas** philosophy. Instead of a standard rigid grid, the design system treats the screen as a physical page. 

- **Organic Alignment:** Elements are often slightly offset or rotated (1-2 degrees) to mimic the way photos are placed by hand.
- **Generous Margins:** Wide "paper" margins allow the content to breathe, emphasizing the premium nature of the scrapbook.
- **Layered Stacking:** Elements should overlap naturally. A photo may be partially covered by a strip of washi tape or a dried flower, requiring a thoughtful use of z-index and spacing to maintain usability.

## Elevation & Depth

Depth in this design system is achieved through **Tactile Layering** rather than standard material elevation.

1.  **Soft Ambient Shadows:** Use very diffused, low-opacity shadows with a slight warm tint (matching the Sepia tone) to make photos and "paper scraps" lift off the background.
2.  **Inner Shadows:** Use subtle inner shadows on "wells" or photo slots to create the illusion of mounting corners or recessed frames.
3.  **Texture Overlays:** Apply a global, low-opacity grain texture across the entire UI to kill the "digital" flatness.
4.  **Z-Axis Narrative:** Lower layers represent the background paper; middle layers represent photos and ticket stubs; the top layer is reserved for "fastened" items like tape, pins, or pressed flowers.

## Shapes

The shape language is organic and varied. While the base `roundedness` is set to **Soft (1)** for standard UI containers, specific decorative elements should use unique masks:

- **Deckled Edges:** Use irregular, torn-paper masks for the edges of card elements.
- **Polaroid Frames:** Strict rectangular shapes with thick bottom borders for photo containers.
- **Washi Tape:** Rectangular strips with "torn" zig-zag ends.
- **Circular Seals:** Used for "saved" or "verified" states, resembling wax seals with irregular, melted perimeters.

## Components

- **Buttons:** Styled as "Labels" or "Wax Seals." Primary buttons use the Dusty Rose color with a subtle letterpress effect. Secondary buttons should look like minimalist gold-rimmed tags.
- **Cards (Memory Blocks):** These are the core components. They should feature a "paper grain" texture, soft shadows, and a "mounting corner" or "tape" graphic to visually anchor them to the background.
- **Input Fields:** Designed to look like ruled notebook paper lines. The focus state should involve a subtle "ink bleed" or a color change to the underline.
- **Washi Tape (Chips):** Use for tags or categories. Each chip should be semi-transparent with a subtle "sticky" texture and torn edges.
- **Glimmer Micro-interactions:** When a user hovers over a "Gold" accented element, a subtle sparkling shimmer should traverse the surface.
- **Transitions:** Page turns should use a soft "cross-dissolve" or a "sliding paper" animation rather than standard digital snaps.