---
name: MinchaLoved Boutique System
colors:
  surface: '#fff7fa'
  surface-dim: '#efd1ed'
  surface-bright: '#fff7fa'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#ffeffb'
  surface-container: '#ffe7fc'
  surface-container-high: '#fedffb'
  surface-container-highest: '#f8d9f5'
  on-surface: '#271529'
  on-surface-variant: '#4e4449'
  inverse-surface: '#3e2a3f'
  inverse-on-surface: '#ffebfb'
  outline: '#7f7479'
  outline-variant: '#d1c3c9'
  surface-tint: '#765469'
  primary: '#503245'
  on-primary: '#ffffff'
  primary-container: '#69495d'
  on-primary-container: '#e4bbd3'
  inverse-primary: '#e4bbd3'
  secondary: '#715c1a'
  on-secondary: '#ffffff'
  secondary-container: '#fee090'
  on-secondary-container: '#78621f'
  tertiary: '#4c372b'
  on-tertiary: '#ffffff'
  tertiary-container: '#654e41'
  on-tertiary-container: '#e0c0b0'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffd8ed'
  primary-fixed-dim: '#e4bbd3'
  on-primary-fixed: '#2c1324'
  on-primary-fixed-variant: '#5c3d51'
  secondary-fixed: '#fee090'
  secondary-fixed-dim: '#e0c477'
  on-secondary-fixed: '#241a00'
  on-secondary-fixed-variant: '#574401'
  tertiary-fixed: '#fddccb'
  tertiary-fixed-dim: '#e0c0b0'
  on-tertiary-fixed: '#29180d'
  on-tertiary-fixed-variant: '#584235'
  background: '#fff7fa'
  on-background: '#271529'
  surface-variant: '#f8d9f5'
typography:
  display-lg:
    fontFamily: Playfair Display
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 36px
    fontWeight: '700'
    lineHeight: '1.2'
  headline-lg:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.3'
  headline-md:
    fontFamily: Playfair Display
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.3'
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '600'
    lineHeight: '1.4'
    letterSpacing: 0.05em
  caption:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '400'
    lineHeight: '1.4'
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  base: 8px
  xs: 4px
  sm: 12px
  md: 24px
  lg: 40px
  xl: 64px
  container-max: 1200px
  gutter: 24px
  margin-mobile: 16px
---

## Brand & Style

The design system is crafted for a premium preloved fashion marketplace that celebrates the circular economy with a boutique, feminine touch. The brand personality is sophisticated yet approachable, blending high-end editorial aesthetics with the warmth of a curated personal wardrobe.

The visual style is a hybrid of **Modern Minimalism** and **Tactile Luxury**. It prioritizes generous whitespace, soft organic shapes, and delicate decorative elements like line-art florals and brush strokes to create an emotional connection. The UI should evoke the feeling of browsing an upscale vintage boutique—curated, intentional, and timeless. Images are often treated with a "Polaroid" frame aesthetic to emphasize the unique, one-of-a-kind nature of preloved items.

## Colors

This color palette is designed to feel romantic and grounded. 

- **Primary Background (#FFD6F0):** Use this soft lavender for main page backgrounds to establish the feminine brand voice immediately.
- **Primary Brand Color (#69495D):** Reserved for high-priority actions, active states, and brand-defining moments.
- **Accent Gold (#B99F56):** Used sparingly for "Premium" badges, limited edition tags, or special highlights to denote value.
- **Surface (#FFFFFF):** All interactive containers and cards must use pure white to ensure legibility against the lavender background and to provide a "clean" boutique feel.
- **Text:** Headings use a deep, near-black purple for authority, while body text uses a softer mauve-grey to reduce visual fatigue.

## Typography

The typography strategy relies on the contrast between the high-fashion editorial feel of **Playfair Display** and the modern, clean legibility of **Plus Jakarta Sans** (chosen as a high-quality alternative to Poppins for its refined variable weight support).

- **Headings:** Should always be set in Playfair Display. Use "Display" sizes for hero sections and "Headline" sizes for section titles.
- **Body Text:** Use Plus Jakarta Sans for all long-form text and product descriptions.
- **Labels:** Small labels, price tags, and category chips should use uppercase Plus Jakarta Sans with slight letter spacing to maintain a premium feel.

## Layout & Spacing

The layout follows a **Fluid Grid** model with generous margins to mimic the layout of a luxury magazine. 

- **Desktop:** 12-column grid with 24px gutters. Max container width of 1200px to ensure readability.
- **Mobile:** 4-column grid with 16px side margins. 
- **Spacing Rhythm:** Use a baseline of 8px. Components should favor `lg` (40px) and `xl` (64px) vertical spacing to allow the design to "breathe." Avoid crowded clusters; items should feel like they are "on display" in a gallery.
- **Background Patterns:** Use the clothes hanger motif as a subtle, low-opacity (5-10%) watermark in large whitespace areas to add depth without distracting from content.

## Elevation & Depth

This design system uses a **Tonal & Ambient Shadow** approach. Because the primary background is a soft lavender, shadows should not be neutral grey. Instead, use a very low-opacity version of the Primary Brand Color (#69495D) for shadows to keep the palette harmonious.

- **Level 1 (Cards/Buttons):** A soft, highly diffused shadow (e.g., `box-shadow: 0 10px 30px rgba(105, 73, 93, 0.08)`).
- **Level 2 (Modals/Dropdowns):** Increased spread and slightly more opacity to denote significant overlap.
- **Glassmorphism:** Use sparingly for navigation bars or overlay filters, using a backdrop-blur (10px) over white at 80% opacity.

## Shapes

The shape language is defined by **High Roundedness**. All interactive elements, cards, and input fields must use a corner radius of at least 20px.

- **Standard Elements:** 20px radius.
- **Large Cards / Polaroids:** 24px radius.
- **Image Containers:** Images within product cards should have a 16px internal radius to sit comfortably within their 24px parent containers.
- **Polaroid Effect:** Use a white background with a slightly larger bottom padding (e.g., 40px) and a subtle shadow to recreate the iconic photo format for product thumbnails.

## Components

- **Buttons:** Primary buttons use the Deep Purple (#69495D) with white text and 20px-pill rounding. Secondary buttons are White with a Deep Purple border (1px).
- **Cards:** Product cards should appear as "Polaroids." A white surface, a square image aspect ratio, and the product title in Playfair Display centered at the bottom.
- **Chips/Badges:** For sizes or categories, use the Nude (#C6A898) color with a 0.5px border or soft fill.
- **Inputs:** Text fields should be white with a very soft lavender border. On focus, the border transitions to Gold (#B99F56).
- **Lists:** Use delicate line-art icons (flowers or butterflies) as bullet points or decorative accents at the end of lists.
- **Checkboxes/Radios:** Should be custom-styled to be circular, avoiding the "utility" look of default browser elements.