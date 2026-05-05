---
name: Nova AdTech System
colors:
  surface: '#101418'
  surface-dim: '#101418'
  surface-bright: '#36393f'
  surface-container-lowest: '#0b0e13'
  surface-container-low: '#191c21'
  surface-container: '#1d2025'
  surface-container-high: '#272a2f'
  surface-container-highest: '#32353a'
  on-surface: '#e1e2e9'
  on-surface-variant: '#c5c5d9'
  inverse-surface: '#e1e2e9'
  inverse-on-surface: '#2e3036'
  outline: '#8f8fa3'
  outline-variant: '#454556'
  surface-tint: '#bec2ff'
  primary: '#bec2ff'
  on-primary: '#0008a8'
  primary-container: '#3a47ff'
  on-primary-container: '#dedeff'
  inverse-primary: '#3340fa'
  secondary: '#e5b5ff'
  on-secondary: '#4e0078'
  secondary-container: '#a100f0'
  on-secondary-container: '#f7e1ff'
  tertiary: '#00dbe9'
  on-tertiary: '#00363a'
  tertiary-container: '#006f76'
  on-tertiary-container: '#75f4ff'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#e0e0ff'
  primary-fixed-dim: '#bec2ff'
  on-primary-fixed: '#00036b'
  on-primary-fixed-variant: '#0716e5'
  secondary-fixed: '#f4d9ff'
  secondary-fixed-dim: '#e5b5ff'
  on-secondary-fixed: '#30004b'
  on-secondary-fixed-variant: '#7000a8'
  tertiary-fixed: '#7df4ff'
  tertiary-fixed-dim: '#00dbe9'
  on-tertiary-fixed: '#002022'
  on-tertiary-fixed-variant: '#004f54'
  background: '#101418'
  on-background: '#e1e2e9'
  surface-variant: '#32353a'
typography:
  headline-xl:
    fontFamily: Space Grotesk
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: 0.02em
  headline-lg:
    fontFamily: Space Grotesk
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: 0.01em
  headline-md:
    fontFamily: Space Grotesk
    fontSize: 24px
    fontWeight: '500'
    lineHeight: '1.3'
    letterSpacing: 0.01em
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
    letterSpacing: '0'
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.5'
    letterSpacing: '0'
  body-sm:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: '1.4'
    letterSpacing: '0'
  label-md:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: '1'
    letterSpacing: 0.05em
  mono-label:
    fontFamily: DM Mono
    fontSize: 13px
    fontWeight: '400'
    lineHeight: '1'
    letterSpacing: '0'
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  xs: 0.25rem
  sm: 0.5rem
  md: 1rem
  lg: 1.5rem
  xl: 2rem
  2xl: 3rem
  3xl: 4rem
  gutter: 1.5rem
  margin: 2rem
---

## Brand & Style

The design system is engineered for the high-stakes world of AdTech, where speed, precision, and data-density are paramount. It adopts a **Tech Dark** aesthetic that balances enterprise reliability with AI-driven innovation. The visual narrative is built on the concept of "Illuminated Intelligence"—using deep, dark voids as a canvas for vibrant, glowing insights.

The style is a fusion of **Minimalism** and **Glassmorphism**. It utilizes a strict structural grid to maintain order in complex data environments, while employing translucent layers and subtle border glows to evoke a sense of futuristic sophistication. The interface should feel like a high-performance flight deck: authoritative, responsive, and premium.

## Colors

The palette is anchored in deep charcoal and navy neutrals to reduce eye strain during prolonged technical sessions. The primary and secondary colors are derived from the brand's signature gradient, moving from a high-energy electric blue to a deep digital purple.

- **Primary & Secondary:** Used for high-impact interactions, progress indicators, and active states.
- **Surface Neutrals:** Different shades of charcoal define the z-axis. Layer 0 is the deepest black (#0A0C10), while Layer 1 surfaces use #14171C.
- **Accents:** A tertiary cyan is reserved for "success" metrics or AI-driven highlights to differentiate from standard brand actions.
- **Semantic Colors:** Error states utilize the brand's red (#CC0000) but are treated with a slight glow to fit the dark theme.

## Typography

This design system uses a dual-font strategy to balance character with utility. 

**Space Grotesk** is used for headlines. Its geometric, technical nature suits the AdTech theme. To achieve the "high-tech" look requested, headlines should use a wide-set tracking (0.01em to 0.05em) and be set in medium to bold weights.

**Inter** serves as the workhorse for all body copy and UI controls. It provides exceptional legibility at small sizes, crucial for dashboard data. **DM Mono** is selectively applied to numerical data, IDs, and code snippets to reinforce the "engineered" feel of the platform.

## Layout & Spacing

The system employs a **12-column fluid grid** with generous 24px gutters to prevent information density from feeling overwhelming. A 4px baseline grid governs all internal component spacing to ensure mathematical harmony.

Layouts should prioritize a "Dashboard First" philosophy:
- **Primary Sidebars:** Fixed 260px width for navigation.
- **Content Area:** Fluid, with a maximum container width of 1600px for data visualization.
- **Margins:** External page margins are set to 32px (xl) to create breathing room between the hardware bezel and the UI.

## Elevation & Depth

Depth is conveyed through **Tonal Layering** and **Glassmorphism**, rather than traditional drop shadows.

1.  **Base (Level 0):** The foundation background (#0A0C10).
2.  **Surfaces (Level 1):** Cards and panels use #14171C.
3.  **Raised (Level 2):** Hovered states or modals use a semi-transparent version of the surface color with a 20px Backdrop Blur.
4.  **Border Glows:** Instead of shadows, use 1px solid borders at 10% opacity of the Primary color. For active or primary cards, use a subtle "outer glow" (a shadow with 0 offset and high blur) tinted with the primary blue.

## Shapes

The design system uses **Soft** roundedness (4px - 8px) to maintain a professional, high-performance edge. Sharp corners feel too aggressive, while fully rounded shapes feel too consumer-oriented.

- **Buttons & Inputs:** 4px radius (Small) for a precise, "tooled" look.
- **Cards & Modals:** 8px radius (Large) to distinguish structural sections.
- **Data Tags:** 2px radius (Extra Small) to maintain density in lists.

## Components

### Buttons
Primary buttons use the Brand Gradient with white text for maximum contrast. Secondary buttons are "ghost" style with a 1px border glow and no fill. All buttons feature a subtle transition that increases the border glow intensity on hover.

### Glassmorphic Cards
Cards are the primary container. They feature a #14171C fill at 80% opacity, a 1px border (#FFFFFF at 5% opacity), and a backdrop blur of 12px. This creates a premium "head-up display" effect.

### Input Fields
Inputs use a dark fill (#050505) with a bottom-only border or a very subtle 4-sided border. The focus state triggers a primary blue border glow and a slight increase in label brightness.

### Data Visualization
Charts should use the Primary, Secondary, and Tertiary colors against the dark background. Use "Neon" line styles: 2px stroke width with a soft outer glow of the same color to make data "pop" against the dark canvas.

### Status Chips
Status indicators (Active, Paired, Error) use a small circular "lamp" icon that glows, mimicking physical server hardware LEDs.
