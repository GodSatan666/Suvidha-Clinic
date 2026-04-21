---
name: Clinical Clarity
colors:
  surface: '#f9f9ff'
  surface-dim: '#cfdaf1'
  surface-bright: '#f9f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f0f3ff'
  surface-container: '#e7eeff'
  surface-container-high: '#dee8ff'
  surface-container-highest: '#d8e3fa'
  on-surface: '#111c2c'
  on-surface-variant: '#424752'
  inverse-surface: '#263142'
  inverse-on-surface: '#ebf1ff'
  outline: '#727784'
  outline-variant: '#c2c6d4'
  surface-tint: '#115cb9'
  primary: '#003f87'
  on-primary: '#ffffff'
  primary-container: '#0056b3'
  on-primary-container: '#bbd0ff'
  inverse-primary: '#acc7ff'
  secondary: '#006c4f'
  on-secondary: '#ffffff'
  secondary-container: '#67fcc6'
  on-secondary-container: '#007354'
  tertiary: '#3e4244'
  on-tertiary: '#ffffff'
  tertiary-container: '#56595b'
  on-tertiary-container: '#cdd0d2'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d7e2ff'
  primary-fixed-dim: '#acc7ff'
  on-primary-fixed: '#001a40'
  on-primary-fixed-variant: '#004491'
  secondary-fixed: '#67fcc6'
  secondary-fixed-dim: '#44dfab'
  on-secondary-fixed: '#002116'
  on-secondary-fixed-variant: '#00513a'
  tertiary-fixed: '#e0e3e5'
  tertiary-fixed-dim: '#c4c7c9'
  on-tertiary-fixed: '#191c1e'
  on-tertiary-fixed-variant: '#444749'
  background: '#f9f9ff'
  on-background: '#111c2c'
  surface-variant: '#d8e3fa'
typography:
  headline-xl:
    fontFamily: Manrope
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 48px
  headline-lg:
    fontFamily: Manrope
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
  headline-md:
    fontFamily: Manrope
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
  label-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.05em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  unit: 8px
  container-max: 1280px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 48px
  section-gap: 80px
---

## Brand & Style
The brand personality of the design system centers on three pillars: clinical precision, effortless accessibility, and human-centric care. It targets patients seeking reliable medical information and streamlined appointment management, evoking a sense of calm and institutional trust.

The chosen style is **Corporate / Modern** with a strong emphasis on **Minimalism**. By utilizing generous white space (the "sterile" aspect) balanced with soft, organic UI shapes (the "welcoming" aspect), the design system avoids the coldness of traditional medical software. The interface relies on flat surfaces and subtle depth to guide the user’s eye through complex medical data without cognitive overload.

## Colors
The color palette is anchored by **Medical Blue (#0056B3)**, a high-contrast shade used for primary actions and brand presence to signal authority and stability. **Soft Teal (#20C997)** serves as the secondary accent, reserved for success states, health progress indicators, and supportive call-outs, providing a soothing visual relief.

The background strategy utilizes a "Super White" approach (#FFFFFF) with **Tertiary Slate (#F8FAFC)** used for subtle section differentiation. Neutral tones are kept cool-grey to maintain the sterile, modern aesthetic. Text is rendered in deep charcoal rather than pure black to reduce eye strain and appear more approachable.

## Typography
Typography is optimized for legibility and information hierarchy. **Manrope** is used for headlines; its slightly geometric but open apertures provide a modern, technical feel that remains friendly. **Inter** is the workhorse for body copy and UI labels, chosen for its exceptional readability in dense medical contexts and data-heavy layouts.

The scale prioritizes vertical rhythm. Headline weights are kept at 600 or 700 to establish clear content anchoring, while body text uses a generous 1.5x line height to ensure medical instructions and patient notes are easily digestible.

## Layout & Spacing
The layout follows a **Fixed Grid** model on desktop to maintain a controlled, professional reading experience, transitioning to a fluid model for tablet and mobile. A 12-column system is utilized with generous 24px gutters to prevent information from feeling cramped.

The spacing rhythm is built on an 8px base unit. To achieve the "sterile yet welcoming" feel, vertical padding between sections is intentionally oversized (80px+), allowing the content to breathe and emphasizing the high-quality, unhurried nature of the clinic's care.

## Elevation & Depth
This design system uses **Ambient Shadows** to create a sense of organized layers without the harshness of heavy borders. Shadows are highly diffused (20px to 40px blur) with very low opacity (5-8%) and a slight blue tint (#0056B3 at 5% opacity) to tie into the brand.

Depth is used functionally: 
- **Level 0 (Flat):** Main background.
- **Level 1 (Subtle Shadow):** Cards, input fields, and navigation bars.
- **Level 2 (Deep Shadow):** Modals, dropdowns, and active "floating" elements like appointment triggers.

## Shapes
The shape language is defined by a **Rounded** aesthetic. Standard components like buttons and input fields use a 0.5rem (8px) corner radius. This softens the "sterile" white space, making the interface feel safe and approachable. Large containers and cards utilize the `rounded-lg` (1rem) or `rounded-xl` (1.5rem) tokens to create a modern, app-like feel that distinguishes the clinic from legacy medical portals.

## Components
- **Buttons:** Primary buttons use the Medical Blue background with white text and a subtle 2px bottom-shadow. Accent buttons for "New Appointment" use the Soft Teal.
- **Cards:** White backgrounds with a Level 1 shadow and a 1px Slate border. Cards should not have headers; use typography weight to define sections.
- **Input Fields:** Use a light grey background (#F1F5F9) that turns white on focus with a 2px Medical Blue border. 
- **Chips:** Used for medical tags or status (e.g., "Confirmed," "Lab Results"). These use a low-opacity tint of the Soft Teal or Medical Blue with high-contrast text.
- **Lists:** Clean rows separated by 1px light slate dividers. Use ample 16px vertical padding per row for touch-friendliness.
- **Specialty Components:** 
    - **Progress Trackers:** Minimalist horizontal lines using Soft Teal to show patient journey steps.
    - **Quick-Action FAB:** A floating teal button for emergency contact or immediate booking.