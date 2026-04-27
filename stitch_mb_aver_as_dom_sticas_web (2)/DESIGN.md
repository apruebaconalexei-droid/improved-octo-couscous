---
name: Professional Maintenance Visual Language
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
  on-surface-variant: '#444651'
  inverse-surface: '#2d3133'
  inverse-on-surface: '#eff1f3'
  outline: '#757682'
  outline-variant: '#c5c5d3'
  surface-tint: '#4059aa'
  primary: '#00236f'
  on-primary: '#ffffff'
  primary-container: '#1e3a8a'
  on-primary-container: '#90a8ff'
  inverse-primary: '#b6c4ff'
  secondary: '#505f76'
  on-secondary: '#ffffff'
  secondary-container: '#d0e1fb'
  on-secondary-container: '#54647a'
  tertiary: '#4b1c00'
  on-tertiary: '#ffffff'
  tertiary-container: '#6e2c00'
  on-tertiary-container: '#f39461'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dce1ff'
  primary-fixed-dim: '#b6c4ff'
  on-primary-fixed: '#00164e'
  on-primary-fixed-variant: '#264191'
  secondary-fixed: '#d3e4fe'
  secondary-fixed-dim: '#b7c8e1'
  on-secondary-fixed: '#0b1c30'
  on-secondary-fixed-variant: '#38485d'
  tertiary-fixed: '#ffdbcb'
  tertiary-fixed-dim: '#ffb691'
  on-tertiary-fixed: '#341100'
  on-tertiary-fixed-variant: '#773205'
  background: '#f7f9fb'
  on-background: '#191c1e'
  surface-variant: '#e0e3e5'
typography:
  h1:
    fontFamily: Manrope
    fontSize: 48px
    fontWeight: '800'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  h2:
    fontFamily: Manrope
    fontSize: 32px
    fontWeight: '700'
    lineHeight: '1.3'
    letterSpacing: -0.01em
  h3:
    fontFamily: Manrope
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.4'
    letterSpacing: '0'
  body-lg:
    fontFamily: Manrope
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
    letterSpacing: '0'
  body-md:
    fontFamily: Manrope
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.5'
    letterSpacing: '0'
  label-caps:
    fontFamily: Manrope
    fontSize: 12px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: 0.05em
  button:
    fontFamily: Manrope
    fontSize: 16px
    fontWeight: '600'
    lineHeight: '1'
    letterSpacing: 0.01em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  base: 8px
  xs: 4px
  sm: 12px
  md: 24px
  lg: 48px
  xl: 80px
  container-max: 1200px
  gutter: 24px
---

## Brand & Style

The brand personality of this design system is rooted in **Reliability, Expertise, and Transparency**. As a domestic repair service, the interface must immediately lower the user's stress by projecting competence and order. 

The aesthetic follows a **Corporate / Modern** style. It utilizes a structured approach to white space and alignment to imply the same precision one expects from a master technician. Visual elements are clean and purposeful, avoiding decorative clutter in favor of high-utility layouts that guide the user toward solving their household issues quickly.

The target audience ranges from homeowners to property managers who value efficiency and professional accountability. The emotional response should be one of "calm resolution"—the feeling that the problem is already being handled by professionals.

## Colors

The palette is anchored by **Deep Navy (Primary)**, a color synonymous with professional stability and corporate trust. This is used for headers, key navigational elements, and primary branding. **Slate Grey (Secondary)** provides a neutral, sophisticated balance for sub-headers and secondary information.

**Safety Orange (Accent)** is used exclusively for high-priority calls to action (CTAs), such as "Request Urgent Repair" or "Book Now." This creates a clear visual hierarchy and ensures that "path to resolution" buttons are unmistakable. 

The background uses a very light **Cool Grey (Neutral)** to reduce eye strain compared to pure white, maintaining a modern, "blueprint" feel.

## Typography

This design system utilizes **Manrope** for all text levels. Manrope was selected for its geometric yet approachable nature, offering excellent legibility in both large headlines and dense technical descriptions.

- **Headlines:** Use heavy weights (700-800) with slight negative letter-spacing to create a "solid" and authoritative presence.
- **Body Text:** Standardizes on a generous 1.5–1.6 line height to ensure that repair details and service descriptions are easy to scan.
- **Labels:** Small caps with increased letter spacing are used for categorizing services (e.g., "PLUMBING", "ELECTRICITY") to provide a clear organizational structure without overpowering the main content.

## Layout & Spacing

This design system employs a **Fixed Grid** model for desktop views to maintain a controlled, professional presentation. A 12-column grid with a 1200px max-width container ensures that content remains readable and does not stretch excessively on wide monitors.

The spacing rhythm is built on an **8px base unit**. Margins and paddings should always be multiples of 8. 
- Large (48px+) vertical spacing should be used between major service sections to emphasize clarity and separation of tasks.
- Tight (12px-16px) spacing is reserved for related form elements or line items within a repair quote.

## Elevation & Depth

To maintain a clean and professional look, depth is communicated through **Tonal Layers** and **Soft Ambient Shadows**. 

- **Surface Levels:** The main background is at Level 0. White cards or content containers sit at Level 1, utilizing a very subtle 1px border (#E2E8F0) rather than a heavy shadow.
- **Elevation Shadows:** Only active elements—like a hovered service card or a functional modal—should cast a shadow. These shadows should be highly diffused (20px-30px blur), low opacity (10%), and slightly tinted with the primary navy color to feel integrated into the environment rather than "floating" unnaturally.
- **Interaction:** Buttons should feel "pressed" on click by removing the shadow and slightly darkening the background color, providing tactile feedback for the user.

## Shapes

The shape language is **Soft (Level 1)**. Elements like buttons, input fields, and cards use a 0.25rem (4px) base radius. Larger containers like image galleries or hero sections may use up to 0.75rem (12px).

This subtle rounding balances the "engineering precision" of sharp corners with the "customer-friendly" nature of rounded edges. It feels modern and digital without appearing "bubbly" or overly casual. All iconography should follow this rule, featuring slightly rounded terminals rather than razor-sharp points.

## Components

### Buttons
- **Primary:** Solid Accent Orange with white text. High contrast for "Emergency" and "Book" actions.
- **Secondary:** Outline Navy with Navy text. Used for "Learn More" or "View All Services."
- **Ghost:** Slate Grey text for low-priority actions like "Cancel" or "Go Back."

### Cards (Service Blocks)
Cards should feature a top-aligned professional photograph of a repair scenario. Text content is left-aligned with a clear H3 heading and a "Starting From" price label in the bottom right corner.

### Inputs & Forms
Forms are critical for a service company. Inputs must have clear, persistent labels (Label-caps style). Focus states are indicated by a 2px Primary Navy border. Error states use the Status Red color for both border and helper text.

### Technician Profiles
Small, circular avatars for staff members, paired with a "Verified Professional" badge (Status Success color) to build immediate user trust.

### Status Indicators
Small, pill-shaped tags used for tracking a repair status: "Scheduled" (Blue), "In Progress" (Orange), and "Completed" (Success Green).