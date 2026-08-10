---
name: MSO Digital Forge
colors:
  surface: '#0f131c'
  surface-dim: '#0f131c'
  surface-bright: '#353942'
  surface-container-lowest: '#0a0e16'
  surface-container-low: '#181c24'
  surface-container: '#1c2028'
  surface-container-high: '#262a33'
  surface-container-highest: '#31353e'
  on-surface: '#dfe2ee'
  on-surface-variant: '#c1c6d7'
  inverse-surface: '#dfe2ee'
  inverse-on-surface: '#2c3039'
  outline: '#8b90a1'
  outline-variant: '#414755'
  surface-tint: '#aec6ff'
  primary: '#aec6ff'
  on-primary: '#002e6a'
  primary-container: '#4f8eff'
  on-primary-container: '#00275e'
  inverse-primary: '#005ac4'
  secondary: '#8fd8ff'
  on-secondary: '#003548'
  secondary-container: '#00c1fd'
  on-secondary-container: '#004b65'
  tertiary: '#c2c7ce'
  on-tertiary: '#2c3136'
  tertiary-container: '#8c9197'
  on-tertiary-container: '#252a2f'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#d8e2ff'
  primary-fixed-dim: '#aec6ff'
  on-primary-fixed: '#001a42'
  on-primary-fixed-variant: '#004396'
  secondary-fixed: '#c2e8ff'
  secondary-fixed-dim: '#75d1ff'
  on-secondary-fixed: '#001e2b'
  on-secondary-fixed-variant: '#004d67'
  tertiary-fixed: '#dfe3ea'
  tertiary-fixed-dim: '#c2c7ce'
  on-tertiary-fixed: '#171c21'
  on-tertiary-fixed-variant: '#42474d'
  background: '#0f131c'
  on-background: '#dfe2ee'
  surface-variant: '#31353e'
typography:
  display-lg:
    fontFamily: Montserrat
    fontSize: 48px
    fontWeight: '800'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Montserrat
    fontSize: 32px
    fontWeight: '700'
    lineHeight: '1.2'
  headline-lg-mobile:
    fontFamily: Montserrat
    fontSize: 28px
    fontWeight: '700'
    lineHeight: '1.2'
  body-md:
    fontFamily: Montserrat
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  code-label:
    fontFamily: JetBrains Mono
    fontSize: 14px
    fontWeight: '500'
    lineHeight: '1.4'
    letterSpacing: 0.05em
  button-text:
    fontFamily: Montserrat
    fontSize: 14px
    fontWeight: '600'
    lineHeight: '1'
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  unit: 4px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 80px
  container-max: 1280px
---

## Brand & Style

The design system is engineered for a high-performance web development studio. The brand personality is **authoritative, precise, and technologically advanced**. It targets business owners and tech-savvy entrepreneurs who value efficiency and clean code.

The visual style is **Corporate Modern with a "Dev-Mode" edge**. It utilizes a dark-mode first approach to evoke the environment of a code editor, balanced with vibrant electric blues that signify energy and connectivity. The aesthetic incorporates subtle glassmorphism and geometric precision to reflect a sense of structured innovation.

Key atmospheric goals:
- **Professionalism:** Through structured layouts and rigorous typography.
- **Performance:** Through high-contrast elements and "light-speed" gradients.
- **Craftsmanship:** Using monospaced accents to reference the underlying code.

## Colors

The palette is anchored in a deep, nocturnal neutral (`#0B0F17`) to create a high-contrast environment where performance-driven data and code can shine. 

- **Electric Blue (Primary):** Used for primary actions, critical brand moments, and main interactive states.
- **Cyan Glow (Secondary):** Used for accents, gradients, and to indicate successful "live" states or performance metrics.
- **Ghost White (Tertiary/Text):** Provides a crisp, high-legibility surface for body copy and headlines against the dark background.
- **Deep Slate (Neutral):** Used for container backgrounds, borders, and subtle UI layering to provide depth without breaking the dark-mode immersion.

**Gradients:** Use a linear gradient from Primary to Secondary at 45 degrees for high-impact elements like hero buttons or primary cards.

## Typography

The typography system balances the corporate reliability of **Montserrat** with the technical precision of **JetBrains Mono**.

- **Headlines:** Montserrat is utilized in heavy weights (700-800) with slight negative letter spacing for a compact, powerful "billboard" effect.
- **Body:** Montserrat at medium weights ensures readability while maintaining a modern, geometric feel.
- **Technical Accents:** JetBrains Mono is used for labels, status indicators, and small "developer notes" or tags to reinforce the site-building narrative.

All typography should be rendered with optimized legibility for dark backgrounds, utilizing the Tertiary color for primary text and a 60% opacity variant for secondary descriptions.

## Layout & Spacing

The layout follows a **structured fluid grid** based on a 12-column system. 

- **Desktop:** Elements are organized with generous outer margins to focus attention on the central content "stage."
- **Rhythm:** A 4px baseline grid governs all vertical rhythm. Component padding and spacing between sections should always be multiples of 8px.
- **Performance Grids:** For features or services, use a 3-column grid that reflows to a single column on mobile. 
- **The "Code Gap":** Use thin, vertical dividers (1px width, 10% white opacity) to separate content sections, mimicking the vertical indent guides found in code editors.

## Elevation & Depth

Depth in this design system is achieved through **Tonal Layering and Border Glows** rather than traditional soft shadows.

- **Level 0 (Base):** The neutral black background.
- **Level 1 (Cards/Sections):** A slightly lighter shade of the neutral color with a subtle 1px border (`rgba(255, 255, 255, 0.05)`).
- **Level 2 (Interactive/Hover):** Elements lift using a "Blue Edge Glow"—a subtle outer shadow with the primary color at low opacity (15%) and a 1px border that brightens on hover.
- **Overlays:** Use a backdrop blur (12px) with a semi-transparent dark fill to create a glassmorphism effect for navigation bars and modals, maintaining context of the content behind.

## Shapes

The shape language is **Soft yet Precise**. 

- **Standard Radius:** 0.25rem (4px) is the default for buttons and small inputs, providing a professional look that isn't too "bubbly."
- **Container Radius:** 0.75rem (12px) for cards and modals to create a distinct frame for content.
- **Geometric Motifs:** Incorporate 45-degree clipped corners on decorative elements or icons to reference tech-hardware aesthetics and the angles present in the `</>` logo mark.

## Components

### Buttons
- **Primary:** Gradient background (Primary to Secondary), white text, 4px radius. On hover, the gradient shifts or brightness increases.
- **Outline:** 1px Primary color border, transparent background, Primary color text. 

### Inputs
- **Code-Style Fields:** Dark background (Level 1 elevation), 1px border that turns Electric Blue on focus. Use JetBrains Mono for placeholder text to mimic a terminal.

### Cards
- **Feature Cards:** Solid Level 1 background with a top-accent border in Primary Blue. 
- **Performance Cards:** Incorporate subtle grid patterns in the background at 5% opacity to evoke a blueprint or motherboard aesthetic.

### Status Indicators
- Use the `< / >` symbol as a bullet point or decorative prefix for list items.
- Chips/Tags: Small, uppercase JetBrains Mono text inside a subtle Primary color tint background with a 100px radius (pill).

### Navigation
- Sticky top bar with a backdrop blur. Use high-contrast white for links, with an Electric Blue underline appearing on hover.