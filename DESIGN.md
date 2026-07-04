---
name: Golden Care Identity
colors:
  surface: '#fbf9f9'
  surface-dim: '#dbdad9'
  surface-bright: '#fbf9f9'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f5f3f3'
  surface-container: '#efeded'
  surface-container-high: '#e9e8e7'
  surface-container-highest: '#e4e2e2'
  on-surface: '#1b1c1c'
  on-surface-variant: '#4d4635'
  inverse-surface: '#303031'
  inverse-on-surface: '#f2f0f0'
  outline: '#7f7663'
  outline-variant: '#d0c5af'
  surface-tint: '#735c00'
  primary: '#735c00'
  on-primary: '#ffffff'
  primary-container: '#d4af37'
  on-primary-container: '#554300'
  inverse-primary: '#e9c349'
  secondary: '#5f5e5e'
  on-secondary: '#ffffff'
  secondary-container: '#e2dfde'
  on-secondary-container: '#636262'
  tertiary: '#5f5e5b'
  on-tertiary: '#ffffff'
  tertiary-container: '#b5b3af'
  on-tertiary-container: '#464542'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffe088'
  primary-fixed-dim: '#e9c349'
  on-primary-fixed: '#241a00'
  on-primary-fixed-variant: '#574500'
  secondary-fixed: '#e5e2e1'
  secondary-fixed-dim: '#c8c6c5'
  on-secondary-fixed: '#1c1b1b'
  on-secondary-fixed-variant: '#474746'
  tertiary-fixed: '#e5e2dd'
  tertiary-fixed-dim: '#c8c6c2'
  on-tertiary-fixed: '#1c1c19'
  on-tertiary-fixed-variant: '#474743'
  background: '#fbf9f9'
  on-background: '#1b1c1c'
  surface-variant: '#e4e2e2'
typography:
  display-lg:
    fontFamily: Montserrat
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Montserrat
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Montserrat
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  title-md:
    fontFamily: Montserrat
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
  body-lg:
    fontFamily: Montserrat
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Montserrat
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-sm:
    fontFamily: Montserrat
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.05em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  container-max: 1200px
  gutter: 24px
  margin-desktop: 64px
  margin-mobile: 20px
  stack-sm: 8px
  stack-md: 16px
  stack-lg: 32px
---

## Brand & Style

This design system establishes a high-end dental boutique identity that bridges the gap between clinical excellence and luxury hospitality. The brand personality is prestigious, meticulous, and reassuring, targeting a clientele that values both health and aesthetic perfection.

The visual style is **Corporate / Modern** with a strong emphasis on **Minimalism**. By utilizing expansive white space and precise metallic accents, the UI evokes the sterility of a world-class clinic and the warmth of a luxury spa. The goal is to provide a "concierge" digital experience that feels calm, organized, and exclusively professional.

## Colors

The palette is anchored by **Metallic Gold (#D4AF37)**, extracted directly from the brand mark to symbolize quality and premium care. This is paired with a clinical **Absolute White (#FFFFFF)** base to maintain a feeling of hygiene and clarity.

- **Primary Gold**: Used for key calls-to-action, active states, and decorative brand elements.
- **Deep Onyx**: Provides high-contrast legibility for typography, ensuring the interface remains grounded and professional.
- **Ivory Neutral**: A soft, warm off-white used for subtle section backgrounds to prevent visual fatigue and add a layer of sophistication beyond pure white.
- **Slate Gray**: Reserved for secondary information and disabled states, maintaining a neutral, unobtrusive presence.

## Typography

The design system utilizes **Montserrat** exclusively to achieve a clean, geometric, and modern architectural feel. The typeface’s wide apertures and generous x-height offer excellent legibility in clinical contexts.

Headlines use tighter tracking and heavier weights to convey authority and confidence. Body text maintains standard tracking for optimal readability. Labels and small metadata employ uppercase styling with increased letter spacing to mirror the aesthetic of luxury signage and premium packaging.

## Layout & Spacing

The layout follows a **Fixed Grid** philosophy on desktop to maintain a controlled, editorial feel, transitioning to a fluid model on mobile devices. 

- **Desktop**: A 12-column grid with a 1200px max-width. Large 64px outer margins are used to "frame" the content, reinforcing the premium aesthetic.
- **Tablet**: An 8-column grid with 32px margins.
- **Mobile**: A 4-column grid with 20px margins.

Spacing follows a strict 8px base unit. Vertical rhythm is generous; significant "white space" between sections is encouraged to reduce cognitive load and emphasize the "clean" nature of the brand.

## Elevation & Depth

Visual hierarchy is achieved through **Tonal Layers** and **Ambient Shadows**. This design system avoids heavy shadows in favor of subtle depth that feels light and airy.

- **Flat Surface**: The primary background is pure white.
- **Subtle Tier**: Secondary containers (like appointment cards) use the Ivory Neutral background with a very soft, high-diffusion shadow (0px 4px 20px rgba(0,0,0,0.04)) to appear slightly lifted.
- **Interactive States**: Gold elements may use a soft gold-tinted glow (outer shadow) when hovered to simulate a metallic reflection.
- **Outlines**: 1px borders in a very light gray (#E0E0E0) are used for form inputs to maintain a crisp, clinical structure without adding visual weight.

## Shapes

The shape language is **Soft (0.25rem)**. This slight rounding takes the "edge" off the clinical environment, making the UI feel more approachable and modern without losing the precision associated with medical care.

Large components like "Book Appointment" hero sections or featured service cards may use `rounded-lg` (0.5rem) to feel more inviting, while primary buttons maintain a tighter, more professional `rounded-md` (0.25rem).

## Components

### Buttons
Primary buttons are solid Gold with White text, using a medium weight. Secondary buttons use a Gold 1px outline with Gold text. All buttons feature a subtle transition effect on hover, increasing the brightness of the gold.

### Input Fields
Inputs are clean with 1px light gray borders. On focus, the border transitions to Gold. Labels sit above the field in `label-sm` style for maximum clarity.

### Cards
Cards are used for service listings and dentist profiles. They feature an Ivory background, no border, and a soft ambient shadow. Imagery within cards should be high-brightness and professional.

### Chips & Status Indicators
Used for "Available" slots or "Specialty" tags. These use the Ivory background with Gold text in `label-sm` to maintain a refined, non-disruptive presence.

### Navigation
The header is sticky with a blurred white background. Navigation links are Deep Onyx, turning Gold on hover. A "Book Now" primary button is always present in the top right.