---
name: Alpine Shield
colors:
  surface: '#f9f9f9'
  surface-dim: '#dadada'
  surface-bright: '#f9f9f9'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f3f3f4'
  surface-container: '#eeeeee'
  surface-container-high: '#e8e8e8'
  surface-container-highest: '#e2e2e2'
  on-surface: '#1a1c1c'
  on-surface-variant: '#5e3f3b'
  inverse-surface: '#2f3131'
  inverse-on-surface: '#f0f1f1'
  outline: '#936e69'
  outline-variant: '#e9bcb6'
  surface-tint: '#c0000c'
  primary: '#b5000b'
  on-primary: '#ffffff'
  primary-container: '#e30613'
  on-primary-container: '#fff5f3'
  inverse-primary: '#ffb4aa'
  secondary: '#5d5e64'
  on-secondary: '#ffffff'
  secondary-container: '#dfdfe6'
  on-secondary-container: '#616268'
  tertiary: '#515a61'
  on-tertiary: '#ffffff'
  tertiary-container: '#69727a'
  on-tertiary-container: '#f0f7ff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdad5'
  primary-fixed-dim: '#ffb4aa'
  on-primary-fixed: '#410001'
  on-primary-fixed-variant: '#930007'
  secondary-fixed: '#e2e2e8'
  secondary-fixed-dim: '#c5c6cc'
  on-secondary-fixed: '#191c20'
  on-secondary-fixed-variant: '#45474c'
  tertiary-fixed: '#dbe4ed'
  tertiary-fixed-dim: '#bfc8d0'
  on-tertiary-fixed: '#141d23'
  on-tertiary-fixed-variant: '#3f484f'
  background: '#f9f9f9'
  on-background: '#1a1c1c'
  surface-variant: '#e2e2e2'
typography:
  headline-xl:
    fontFamily: Montserrat
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Montserrat
    fontSize: 32px
    fontWeight: '700'
    lineHeight: '1.25'
  headline-md:
    fontFamily: Montserrat
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.3'
  body-lg:
    fontFamily: Hanken Grotesk
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Hanken Grotesk
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.5'
  label-bold:
    fontFamily: Hanken Grotesk
    fontSize: 14px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: 0.05em
  headline-lg-mobile:
    fontFamily: Montserrat
    fontSize: 28px
    fontWeight: '700'
    lineHeight: '1.2'
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  container-max: 1280px
  gutter: 24px
  margin-desktop: 64px
  margin-mobile: 20px
  stack-sm: 8px
  stack-md: 16px
  stack-lg: 32px
  section-padding: 80px
---

## Brand & Style
The design system for this professional security platform is built on the pillars of **authority, precision, and technological reliability**. It leverages a "Corporate Modern" aesthetic that balances high-impact visual anchors with clinical, functional clarity. 

The target audience—corporate entities, industrial sectors, and high-security residential complexes—requires a UI that feels impenetrable yet accessible. The interface utilizes significant white space to project an image of organized efficiency, while bold blocks of "Swiss Cross" red serve as high-visibility call-to-actions and brand identifiers. The emotional response should be one of "total protection" through advanced technology.

## Colors
The palette is rooted in the Swiss national identity, using **Corporate Red (#E30613)** as the primary driver for brand recognition and user guidance. 

- **Primary Red:** Used for critical actions (CTAs), progress indicators, and key iconography.
- **Anthracite Dark (#2C2E33):** Provides a heavy, grounded anchor for typography and high-contrast background sections (e.g., footers and impact hero sections).
- **Medium Gray (#6C757D):** Reserved for secondary information, meta-data, and borders.
- **Pure White (#FFFFFF):** The primary surface color to ensure maximum readability and a clean, "facility-grade" atmosphere.

## Typography
The system uses a pairing of **Montserrat** and **Hanken Grotesk** to bridge the gap between architectural strength and technical precision. 

- **Headlines:** Montserrat's geometric construction provides the "authority" required for a security brand. Headlines should use tight tracking and bold weights.
- **Body & Labels:** Hanken Grotesk offers superior legibility for long-form content and technical specifications. 
- **Hierarchy:** Maintain a clear distinction between levels. Use uppercase transformations for labels and small buttons to evoke a sense of "operational commands."

## Layout & Spacing
This design system utilizes a **12-column fixed grid** for desktop, ensuring structured alignment that mirrors the precision of security systems. 

- **Grid:** On desktop, the grid is centered with a max-width of 1280px. Gutters are kept at 24px to allow elements breathing room while maintaining a compact, professional feel.
- **Rhythm:** Vertical spacing follows an 8px base unit. Sections are separated by large 80px paddings to allow the brand's premium positioning to shine through whitespace.
- **Mobile:** Transition to a 4-column fluid layout with 20px side margins. Large section headers should scale down using the `mobile` typography tokens to prevent awkward wrapping.

## Elevation & Depth
Depth is used sparingly to maintain a "flat-plus" professional look. 

- **Surface Layers:** The default background is white. Secondary content sections use the Anthracite Dark background to create immediate visual separation.
- **Shadows:** Use "Technical Shadows"—highly diffused, low-opacity (10-15%) neutral shadows. These should only be applied to interactive cards and dropdown menus to indicate lift without feeling "dreamy" or soft.
- **Interaction:** Upon hover, cards should increase their shadow spread slightly (4px to 8px) and may include a 1px interior stroke in Gray Medium to emphasize the "contained" nature of the data.

## Shapes
The shape language is "Calculated Softness." Elements utilize a **0.5rem (8px)** base radius. This specific value is chosen to move away from the aggressive sharpness of traditional industrial design while remaining more serious than the fully-rounded "bubbly" styles found in consumer social apps.

- **Buttons & Inputs:** Consistent 8px corners.
- **Cards:** 16px (rounded-lg) for large containers to provide a softer frame for technical data.
- **Icons:** Use thick strokes (2px) with slightly rounded caps to match the UI's geometry.

## Components
- **Buttons (CTA):** High-impact Primary Red backgrounds with White bold text. Hover state shifts to a slightly darker shade of red (#C20510). Use a minimum height of 48px for a substantial, tactile feel.
- **Cards:** White background with a subtle 1px border (#E9ECEF) and the defined "Technical Shadow." For service cards, use a 4px red top-border accent to tie the component to the brand.
- **Input Fields:** Clean, 1px Gray Medium borders that turn Primary Red on focus. Use Hanken Grotesk for placeholder text to maintain high legibility.
- **Chips/Badges:** Small, uppercase labels used for status (e.g., "ACTIVE," "SECURE"). Use Anthracite backgrounds for neutral status and Red for alerts.
- **Contrast Sections:** Use Anthracite backgrounds with White typography for "Statement Sections" or "Mission/Vision" blocks to create a dramatic break in the scroll.
- **Navigation:** Transparent or White background with sticky behavior. Use Montserrat Medium for links to ensure they carry enough visual weight.