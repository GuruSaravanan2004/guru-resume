---
name: Kinetic Clarity
colors:
  surface: '#faf9ff'
  surface-dim: '#ccdaff'
  surface-bright: '#faf9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f1f3ff'
  surface-container: '#e9edff'
  surface-container-high: '#e1e8ff'
  surface-container-highest: '#d8e2ff'
  on-surface: '#051a3e'
  on-surface-variant: '#434654'
  inverse-surface: '#1d3054'
  inverse-on-surface: '#edf0ff'
  outline: '#737685'
  outline-variant: '#c3c6d6'
  surface-tint: '#0c56d0'
  primary: '#003d9b'
  on-primary: '#ffffff'
  primary-container: '#0052cc'
  on-primary-container: '#c4d2ff'
  inverse-primary: '#b2c5ff'
  secondary: '#5c5f60'
  on-secondary: '#ffffff'
  secondary-container: '#dee0e2'
  on-secondary-container: '#606365'
  tertiary: '#7b2600'
  on-tertiary: '#ffffff'
  tertiary-container: '#a33500'
  on-tertiary-container: '#ffc6b2'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dae2ff'
  primary-fixed-dim: '#b2c5ff'
  on-primary-fixed: '#001848'
  on-primary-fixed-variant: '#0040a2'
  secondary-fixed: '#e1e2e4'
  secondary-fixed-dim: '#c5c6c8'
  on-secondary-fixed: '#191c1e'
  on-secondary-fixed-variant: '#444749'
  tertiary-fixed: '#ffdbcf'
  tertiary-fixed-dim: '#ffb59b'
  on-tertiary-fixed: '#380d00'
  on-tertiary-fixed-variant: '#812800'
  background: '#faf9ff'
  on-background: '#051a3e'
  surface-variant: '#d8e2ff'
typography:
  display:
    fontFamily: Inter
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  display-mobile:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Inter
    fontSize: 30px
    fontWeight: '600'
    lineHeight: 38px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
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
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 20px
    letterSpacing: 0.01em
  label-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  unit: 8px
  container-max: 1200px
  gutter: 24px
  margin-desktop: 64px
  margin-mobile: 24px
  section-gap: 120px
---

## Brand & Style

The design system is rooted in **Minimalism** with a **Corporate/Modern** finish. It is tailored for professional portfolios where the work must remain the focal point. The brand personality is precise, dependable, and quietly confident. 

The aesthetic prioritizes function over decoration, utilizing generous whitespace to reduce cognitive load. Visual interest is generated through rigorous typographic hierarchy and purposeful use of a singular accent color rather than decorative imagery or complex textures. The emotional response should be one of clarity, efficiency, and professional trust.

## Colors

The palette is strictly functional. 
- **Primary Blue:** Used exclusively for interactive elements, primary actions, and brand highlights. 
- **Secondary Gray:** Utilized for subtle background shifts to define sections or "well" containers.
- **Neutral:** A deep navy-black for maximum legibility in text, ensuring high contrast against the white base.
- **Background:** Pure white is the default surface to maintain a "gallery" feel.

## Typography

This design system utilizes **Inter** for all roles to achieve a systematic, utilitarian aesthetic. 

- **Display & Headlines:** Use tight letter-spacing and bold weights to create a strong visual anchor. 
- **Body Text:** Set with generous line-height to ensure long-form case studies remain readable.
- **Labels:** Used for metadata (dates, categories), often employing uppercase styling for small-scale distinction without adding weight.

## Layout & Spacing

The layout follows a **Fixed Grid** model on desktop, centering content within a 1200px container to maintain line-length control. 

- **Rhythm:** An 8px base unit governs all dimensions.
- **Sectioning:** Large vertical gaps (120px+) separate distinct portfolio sections to allow the content to "breathe."
- **Responsive Behavior:** On mobile, margins shrink to 24px and the 12-column grid collapses to a single column. Vertical spacing is reduced by 40% on mobile devices to maintain momentum.

## Elevation & Depth

This design system rejects heavy shadows in favor of **Low-contrast outlines** and **Tonal layers**. 

- **Surface Strategy:** Depth is communicated by placing white elements on top of light gray (`#F4F5F7`) backgrounds.
- **Outlines:** Borders are 1px thick, using a soft gray (`#DFE1E6`).
- **Shadows:** When necessary for interaction (e.g., a hovered card), use a single, highly diffused "Ambient Shadow": `0 4px 12px rgba(9, 30, 66, 0.05)`.

## Shapes

The shape language is **Soft**. A 0.25rem (4px) base radius is applied to buttons, input fields, and small UI components to take the "edge" off the corporate aesthetic without appearing overly playful. Larger components like cards use a slightly increased radius (8px) to soften the layout's structural grid.

## Components

- **Buttons:** Primary buttons are solid `#0052CC` with white text. Secondary buttons use a 1px outline of the primary color with no fill.
- **Cards:** White background, 1px `#DFE1E6` border. No shadow in default state. On hover, the border color shifts to the primary blue and a subtle ambient shadow appears.
- **Input Fields:** Minimalist 1px gray borders that transition to a 2px primary blue border on focus. Labels sit strictly above the field.
- **Chips/Tags:** Small, light gray backgrounds with `label-sm` typography, used for "Skills" or "Project Categories."
- **Lists:** Clean dividers between items using 1px `#EBECF0`. No bullet points; use primary blue icons for list markers if needed.
- **Project Grid:** A strict 2 or 3 column grid with consistent aspect ratios for project thumbnails to maintain visual alignment.