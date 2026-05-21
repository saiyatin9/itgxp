---
name: Clinical Precision
colors:
  surface: '#f4fafb'
  surface-dim: '#d5dbdc'
  surface-bright: '#f4fafb'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#eff5f6'
  surface-container: '#e9eff0'
  surface-container-high: '#e3e9ea'
  surface-container-highest: '#dde4e5'
  on-surface: '#161d1e'
  on-surface-variant: '#3e484b'
  inverse-surface: '#2b3133'
  inverse-on-surface: '#ecf2f3'
  outline: '#6e797b'
  outline-variant: '#bec8cb'
  surface-tint: '#E3F4F6'
  primary: '#006572'
  on-primary: '#ffffff'
  primary-container: '#1a7f8e'
  on-primary-container: '#f4fdff'
  inverse-primary: '#7dd3e4'
  secondary: '#835500'
  on-secondary: '#ffffff'
  secondary-container: '#feae2c'
  on-secondary-container: '#6b4500'
  tertiary: '#4d5d66'
  on-tertiary: '#ffffff'
  tertiary-container: '#65767f'
  on-tertiary-container: '#f7fbff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#9eefff'
  primary-fixed-dim: '#7dd3e4'
  on-primary-fixed: '#001f24'
  on-primary-fixed-variant: '#004e59'
  secondary-fixed: '#ffddb4'
  secondary-fixed-dim: '#ffb955'
  on-secondary-fixed: '#291800'
  on-secondary-fixed-variant: '#633f00'
  tertiary-fixed: '#d3e5ef'
  tertiary-fixed-dim: '#b7c9d3'
  on-tertiary-fixed: '#0d1e25'
  on-tertiary-fixed-variant: '#394951'
  background: '#f4fafb'
  on-background: '#161d1e'
  surface-variant: '#dde4e5'
  surface-white: '#FFFFFF'
  text-muted: '#6B8B96'
typography:
  display:
    fontFamily: Fraunces
    fontSize: 56px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Fraunces
    fontSize: 40px
    fontWeight: '600'
    lineHeight: '1.2'
  headline-lg-mobile:
    fontFamily: Fraunces
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Fraunces
    fontSize: 28px
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
  body-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '400'
    lineHeight: '1.5'
  label-bold:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: 0.05em
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '500'
    lineHeight: '1.2'
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  unit: 8px
  gutter: 24px
  margin-desktop: 80px
  margin-mobile: 20px
  max-width: 1280px
---

## Brand & Style

This design system is engineered for ITGxP, an enterprise IT and GxP compliance firm where accuracy and reliability are paramount. The brand personality is "Cool & Regulated"—a blend of clinical precision, industrial trustworthiness, and an airy, light-filled atmosphere. It avoids the chaotic visuals of typical tech startups in favor of a structured, professional, and authoritative aesthetic.

The design style leans heavily into **Minimalism** with a touch of **Corporate Modernism**. It prioritizes heavy white space, clean structural lines, and a high-contrast palette that ensures legibility and focus. Every element is intentional, reflecting the regulated nature of GxP environments where every detail matters. The interface feels "breathable" but strictly organized, moving away from generic SaaS trends to establish a more specialized, institutional presence.

## Colors

The palette is rooted in a clinical "Primary Surface" of pure white and cool off-white, creating a sterile but welcoming environment. 

- **Primary (Teal Blue):** Used as the structural anchor for section tags, accents, borders, and icons. It represents the "Cool" aspect of the brand.
- **Secondary (Amber Yellow):** Reserved strictly for high-priority CTAs, active states, and specific highlights to draw the eye without overwhelming the composure of the layout.
- **Tertiary (Dark Ink):** The "Dark Ink" color provides the necessary weight for typography, ensuring an authoritative voice.
- **Background Tint:** A very light teal is used for background-alternating sections to maintain a sense of depth without resorting to heavy shadows or dark modes. 

**Note:** Dark backgrounds are strictly prohibited, except for the site footer which may utilize the Dark Ink palette. Gradients and purple tones are explicitly excluded.

## Typography

The typography strategy employs a "High-Contrast Pairing" between the authoritative serif and the modern sans-serif.

- **Headlines (Fraunces):** A sturdy, editorial serif that conveys tradition and intellectual authority. Use for all main headings to ground the page.
- **Body & Labels (Plus Jakarta Sans):** A friendly yet precise sans-serif used for all functional text. It ensures clarity in complex data-heavy sections.

Maintain strict hierarchy. Headlines should be in "Dark Ink" (#0E1F26), while secondary body copy should use the "Muted" (#6B8B96) shade to reduce visual noise. Large display type should use tighter letter spacing to maintain a cohesive look.

## Layout & Spacing

This design system utilizes a **Fixed Grid** model on desktop to enforce a sense of structure and containment, while transitioning to a fluid layout for mobile devices. 

- **Grid:** 12-column grid with 24px gutters.
- **Rhythm:** An 8px spacing system guides all internal padding and margins to ensure mathematical consistency.
- **Whitespace:** Emphasize vertical "breathing room" between sections (e.g., 120px to 160px) to maintain the airy, clinical feel.
- **Alignment:** Strictly left-aligned text for body copy to maintain legibility in professional contexts; headings may be centered only in hero sections.

## Elevation & Depth

To maintain a "Clinical" feel, the system avoids traditional soft shadows. Depth is instead communicated through:

- **Structural Outlines:** Use 1px Teal Blue (#1A7F8E) borders for cards and containers to define space.
- **Tonal Layering:** Use the Very Light Teal (#E3F4F6) and Cool Off-White (#F0F6F7) to create distinct horizontal tiers of content.
- **Interactive Lift:** For cards and buttons, a subtle "lift" effect (moving -4px on the Y-axis) is preferred over heavy drop shadows. If a shadow is necessary for an active state, it must be low-opacity and highly diffused, using the Dark Ink color as a tint.

## Shapes

The shape language is **Soft (0.25rem)**. This provides just enough approachable warmth to the design while maintaining a "Sharp" and professional edge. 

- **Standard Elements:** Buttons, input fields, and small containers use a 4px (0.25rem) radius.
- **Cards:** Use the `rounded-lg` (8px / 0.5rem) token to give them a slightly more prominent presence.
- **Pills:** All pill components (tags/labels) should use a fully rounded (32px+) radius to contrast against the otherwise rectilinear grid.

## Components

- **Wordmark:** A text-only mark using Fraunces. "IT" in Dark Ink, "G" in Amber Yellow, and "xP" in Teal Blue. No symbols.
- **Buttons:** 
    - *Primary:* Teal Blue fill with White text.
    - *Secondary/CTA:* Amber Yellow fill with Dark Ink text. 
    - All buttons feature a 4px radius and 600 weight Plus Jakarta Sans.
- **Cards:** White background with a 1px Teal Blue border. On hover, the border weight remains the same but the card lifts. No emojis or decorative iconography; use functional, stroke-based icons only.
- **Pills:** Used for tags. White background with a 1.5px Teal Blue border. Text is set in "Label Bold" (All caps, Plus Jakarta Sans).
- **Input Fields:** White backgrounds, 1px Muted Teal borders. On focus, the border changes to 2px Teal Blue. 
- **Lists:** Bullet points should use small Teal Blue squares instead of circles to emphasize the "IT" and "Precision" aspect.
- **Header:** Sticky with a White background and a thin Teal Blue bottom border for clear separation from content.