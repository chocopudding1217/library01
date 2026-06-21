---
name: Intellectual Explorer
colors:
  surface: '#f7f9fb'
  surface-dim: '#d8dadc'
  surface-bright: '#f7f9fb'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f2f4f6'
  surface-container: '#eceef0'
  surface-container-high: '#e6e8ea'
  surface-container-highest: '#e0e3e5'
  on-surface: '#191c1e'
  on-surface-variant: '#464555'
  inverse-surface: '#2d3133'
  inverse-on-surface: '#eff1f3'
  outline: '#777587'
  outline-variant: '#c7c4d8'
  surface-tint: '#4d44e3'
  primary: '#3525cd'
  on-primary: '#ffffff'
  primary-container: '#4f46e5'
  on-primary-container: '#dad7ff'
  inverse-primary: '#c3c0ff'
  secondary: '#944a00'
  on-secondary: '#ffffff'
  secondary-container: '#fd933d'
  on-secondary-container: '#693300'
  tertiary: '#005349'
  on-tertiary: '#ffffff'
  tertiary-container: '#006d61'
  on-tertiary-container: '#5af3dd'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e2dfff'
  primary-fixed-dim: '#c3c0ff'
  on-primary-fixed: '#0f0069'
  on-primary-fixed-variant: '#3323cc'
  secondary-fixed: '#ffdcc5'
  secondary-fixed-dim: '#ffb783'
  on-secondary-fixed: '#301400'
  on-secondary-fixed-variant: '#713700'
  tertiary-fixed: '#62fae3'
  tertiary-fixed-dim: '#3cddc7'
  on-tertiary-fixed: '#00201c'
  on-tertiary-fixed-variant: '#005047'
  background: '#f7f9fb'
  on-background: '#191c1e'
  surface-variant: '#e0e3e5'
  book-indigo: '#4F46E5'
  discovery-orange: '#FB923C'
  fresh-mint: '#2DD4BF'
  ink-slate: '#1E293B'
  muted-steel: '#64748B'
typography:
  display-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 48px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 38px
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
  body-lg:
    fontFamily: Be Vietnam Pro
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Be Vietnam Pro
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-sm:
    fontFamily: Be Vietnam Pro
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  label-bold:
    fontFamily: Be Vietnam Pro
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.01em
  label-caps:
    fontFamily: Be Vietnam Pro
    fontSize: 12px
    fontWeight: '700'
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
  base: 8px
  container-padding-mobile: 1rem
  container-padding-desktop: 2rem
  gutter: 1rem
  section-gap: 3rem
---

## Brand & Style

The design system is crafted for a teenage audience, balancing academic trust with a sense of digital discovery. The brand personality is **Intellectual, Approachable, and Exploratory**. It moves away from "kiddy" aesthetics toward a more mature "Young Adult" feel—sophisticated enough for high schoolers but vibrant enough to remain engaging.

The chosen style is **Corporate / Modern** with a **Minimalist** lean. It utilizes generous whitespace to reduce cognitive load during book browsing, paired with "friendly-tech" elements like soft shadows and rounded corners. The interface should feel like a digital concierge—organized, clean, and encouraging.

## Colors

The color palette is anchored by **Book Indigo**, a vibrant yet trustworthy primary hue that signals reliability and intellectual depth. **Discovery Orange** is used sparingly as a secondary accent to highlight new arrivals, "surprising" recommendations, and primary calls to action, creating a warm, energetic contrast. **Fresh Mint** serves as a tertiary color, specifically reserved for "Available" statuses and positive feedback loops.

The neutral system relies on a "cool slate" scale to maintain a modern, clean environment. Surfaces are primarily off-white to reduce eye strain during reading, while text uses a deep indigo-tinted slate rather than pure black to soften the visual hierarchy.

## Typography

This design system employs a two-font pairing strategy. **Plus Jakarta Sans** is used for headings; its soft, rounded geometric shapes feel welcoming and optimistic, perfect for a teen-centric product. **Be Vietnam Pro** is used for all body text and labels; it is exceptionally legible at small sizes and provides a contemporary, friendly tone that isn't overly formal.

Line heights are intentionally generous to ensure readability for longer book descriptions. Label styles use slightly increased letter spacing and weight to differentiate them from prose content, aiding in quick scanning of book metadata (e.g., Author, Genre).

## Layout & Spacing

The design system follows a **Mobile-First Fluid Grid** philosophy. On mobile devices, content lives within a single column with 16px side margins. As the screen scales to desktop, the layout shifts to a 12-column system with a max-width of 1200px.

A strict **8px grid** governs all spacing. Vertical rhythm is maintained by using multiples of 8px (e.g., 16px between book title and author, 24px between card groups). Section gaps are kept large (48px or 64px) to create the "airy" feel of a high-end digital library, preventing the interface from feeling cluttered or overwhelming.

## Elevation & Depth

Visual hierarchy is achieved through **Tonal Layers** and **Ambient Shadows**. The background is kept at the lowest level (`#F8FAFC`). Cards and interactive containers are elevated on a white surface (`#FFFFFF`) using a soft, diffused shadow: `0px 4px 20px rgba(30, 41, 59, 0.05)`.

Interactive elements like buttons or active book cards use a secondary elevation state with a slightly more pronounced shadow and a subtle 1px border in a light indigo tint. This creates a tactile, "clickable" quality without the heaviness of traditional skeuomorphism.

## Shapes

The shape language is consistently **Rounded**, reflecting the friendly and approachable brand pillars. 

- **Small Components:** Checkboxes and small tags use a 4px radius.
- **Medium Components:** Input fields and standard buttons use an 8px (0.5rem) radius.
- **Large Components:** Book cards and modal containers use a 16px (1rem) radius.

This progression of roundedness ensures that larger objects feel softer and more inviting, while smaller functional elements remain crisp and precise.

## Components

### Buttons
Primary buttons use a solid **Book Indigo** fill with white text and 8px rounded corners. Secondary buttons use a ghost style with a 1px Indigo border. For "Discovery" actions (like "Surprise Me"), use a solid **Discovery Orange** to draw immediate attention.

### Book Cards
The core of the experience. Cards should feature a vertical layout with a prominent book cover image at the top (using the 16px radius). Below the image, include the title in `headline-sm` and author in `body-sm`. A small "Availability Chip" should be anchored to the bottom-right of the image area.

### Chips & Tags
Used for genre selection and status. Chips should be pill-shaped (`rounded-xl`). Selected genres should use a light indigo background with dark indigo text to show active states without the heaviness of a full color fill.

### Input Fields
Search bars and login fields should have a light grey stroke and a white background. When focused, the stroke should transition to a 2px **Book Indigo** border with a very subtle indigo glow (outer shadow).

### Progress Indicators
Since this is a "Step" service, use a horizontal step indicator for the onboarding flow (Genre selection) to give users a sense of progress through the exploratory phase.