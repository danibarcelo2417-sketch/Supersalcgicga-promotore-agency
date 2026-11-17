---
name: Underground Cyber-Trap
colors:
  surface: '#131316'
  surface-dim: '#131316'
  surface-bright: '#39393c'
  surface-container-lowest: '#0e0e11'
  surface-container-low: '#1c1b1e'
  surface-container: '#201f22'
  surface-container-high: '#2a2a2d'
  surface-container-highest: '#353438'
  on-surface: '#e5e1e5'
  on-surface-variant: '#e3bdc7'
  inverse-surface: '#e5e1e5'
  inverse-on-surface: '#313033'
  outline: '#aa8892'
  outline-variant: '#5b3f48'
  surface-tint: '#ffb0ca'
  primary: '#ffb0ca'
  on-primary: '#640036'
  primary-container: '#ff479c'
  on-primary-container: '#58002f'
  inverse-primary: '#b90068'
  secondary: '#dfb7ff'
  on-secondary: '#4b007e'
  secondary-container: '#9d05ff'
  on-secondary-container: '#f7e6ff'
  tertiary: '#ddb8ff'
  on-tertiary: '#490081'
  tertiary-container: '#b175ec'
  on-tertiary-container: '#400071'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#ffd9e3'
  primary-fixed-dim: '#ffb0ca'
  on-primary-fixed: '#3e001f'
  on-primary-fixed-variant: '#8d004e'
  secondary-fixed: '#f1daff'
  secondary-fixed-dim: '#dfb7ff'
  on-secondary-fixed: '#2d004f'
  on-secondary-fixed-variant: '#6b00b0'
  tertiary-fixed: '#f0dbff'
  tertiary-fixed-dim: '#ddb8ff'
  on-tertiary-fixed: '#2c0051'
  on-tertiary-fixed-variant: '#62259b'
  background: '#131316'
  on-background: '#e5e1e5'
  surface-variant: '#353438'
typography:
  display-hero:
    fontFamily: Syne
    fontSize: 56px
    fontWeight: '800'
    lineHeight: 64px
    letterSpacing: -0.03em
  display-hero-mobile:
    fontFamily: Syne
    fontSize: 36px
    fontWeight: '800'
    lineHeight: 42px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Syne
    fontSize: 40px
    fontWeight: '800'
    lineHeight: 48px
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Syne
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 34px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Syne
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 36px
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Syne
    fontSize: 20px
    fontWeight: '700'
    lineHeight: 28px
    letterSpacing: 0em
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '500'
    lineHeight: 28px
    letterSpacing: 0em
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 15px
    fontWeight: '400'
    lineHeight: 24px
    letterSpacing: 0em
  body-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 20px
    letterSpacing: 0.01em
  label-lg:
    fontFamily: Space Grotesk
    fontSize: 14px
    fontWeight: '700'
    lineHeight: 18px
    letterSpacing: 0.08em
  label-md:
    fontFamily: Space Grotesk
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.06em
  label-sm:
    fontFamily: Space Grotesk
    fontSize: 10px
    fontWeight: '600'
    lineHeight: 14px
    letterSpacing: 0.1em
rounded:
  sm: 0.5rem
  DEFAULT: 1rem
  md: 1.5rem
  lg: 2rem
  xl: 3rem
  full: 9999px
spacing:
  gutter: 1.25rem
  gutter-desktop: 2rem
  margin: 1.25rem
  margin-desktop: 3rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style
This design system defines an underground, gritty, high-octane visual identity engineered specifically for high-energy music spaces bridging trap and industrial techno. The emotional tone is unapologetic, rave-forward, nocturnal, and tactile—blending street grit with futuristic cyberpunk chrome.

The design movement mixes **High-Contrast Cyberpunk** and **Dark-Mode Glassmorphism** with subtle physical textures: deep void-like canvas surfaces, intense hot-pink laser strikes, liquid chrome borders, and iridescent violet atmospheric emissions. The aesthetic speaks directly to booking agents, festival promoters, artists, and club culture denizens who demand visual swagger without sacrificing layout structure.

## Colors
The palette is built upon stark contrasts rooted in late-night warehouse club settings:

- **Primary (`#FF1493`):** Explosive hot neon pink used for critical CTAs, active status highlights, key brand typography moments, and intense glow effects.
- **Secondary (`#9D00FF`):** Electric rave violet used for secondary callouts, gradient fills, and sub-headings.
- **Tertiary (`#C084FC`):** Vibrant iridescent lilac/lavender used for body highlights, tags, and tertiary interactive components.
- **Neutral (`#050507`):** Pure deep obsidian black canvas that preserves absolute contrast, supported by `#0B0A10` for elevated card containers and `#E2E8F0` for metallic liquid chrome text highlights and specular edges.

Use color deliberately: avoid muddy gradients by keeping the neon tones pure and pairing them with high-opacity pure black and crisp metallic whites.

## Typography
The typography strategy sets up an intense dialogue between club-poster expressiveness and razor-sharp modern precision:

- **Headlines (`Syne`):** Heavyweight, wide, avant-garde grotesque with angular character cuts. Used uppercase for punchy statements, hero titles, artist names, and agency headers to echo rave flyers.
- **Body (`Plus Jakarta Sans`):** Warm, contemporary, geometric readability against obsidian backdrops. Keeps tracklists, bios, contract terms, and manifestos effortless to scan.
- **Labels & Micro-copy (`Space Grotesk`):** Technical, monospaced-adjacent flair suited for track timestamps, metadata, role tags, and techno-club badges. Set uppercase with positive tracking.

## Layout & Spacing
The layout employs an adaptable fluid grid:
- **Mobile (<768px):** Single-column stacked flow with a 4-column sub-grid, `1.25rem` screen margins, and compact gutters.
- **Tablet (768px - 1024px):** 8-column fluid grid, balancing artist rosters and booking cards in split arrangements.
- **Desktop (>1024px):** 12-column grid maxing out at `1440px` with `2rem` gutters and `3rem` section margins.

Spacing follows vertical rhythm tokens where cards and media blocks breathe through tight micro-spacing internally (`space-sm`, `space-md`) paired with cinematic, expansive layout breaks (`space-xl` and larger) between content tiers.

## Elevation & Depth
Depth is created through luminous contrast rather than traditional dropshadows:

1. **Base Layer:** `#050507` matte canvas void.
2. **Surface Containers:** Semi-translucent dark glass (`rgba(11, 10, 16, 0.75)`) backed by `backdrop-filter: blur(16px)`.
3. **Chrome & Iridescent Outlines:** Card perimeters leverage a 1px border gradient transitioning from metallic silver (`rgba(226, 232, 240, 0.35)`) into neon pink (`rgba(255, 20, 147, 0.4)`) and dark violet.
4. **Neon Bloom:** Interactive highlights and active states feature diffuse multi-stage outer glows: `0 0 16px rgba(255, 20, 147, 0.45), 0 0 32px rgba(157, 0, 255, 0.25)`.

## Shapes
The visual identity embraces a high-contrast juxtaposition: ultra-rounded pill shapes (`roundedness: 3`) for badges, CTAs, avatar rings, and teaser buttons, set against structured rectangular modular grids. 

- Artist thumbnails and media avatars are rendered as pure circles with luminous multi-ring gradients.
- Notification badges and status pills use maximal rounding (`9999px`).
- Deep surface cards use rounded corners (`1.5rem` to `2rem`) to soften the aggressive neon accents and retain a polished, modern finish.

## Components

### Buttons
- **Primary Cyber-Pill:** Fully rounded (`rounded-full`), filled with primary neon pink (`#FF1493`) or a dual gradient (`#FF1493` to `#9D00FF`). Text is set in bold uppercase `Space Grotesk` or `Syne`. Glows on hover with an intensified neon shadow.
- **Liquid Chrome Outline:** Fully rounded transparent button with a 1.5px iridescent silver/chrome border, white text, and subtle inner glow on hover.

### Chips & Badges
- Pill-shaped tags (`rounded-full`) with `rgba(255, 20, 147, 0.12)` fill, `#FF1493` text, and a crisp 1px border. Used for genres ("TRAP", "TECHNO", "EXCLUSIVE") and live booking statuses.

### Artist Roster & Cards
- **Artist Circle Avatar:** Circular frame enclosed in a dual neon stroke (neon pink into violet). On hover, scales up with an intense neon aura.
- **Glass Glassmorphism Card:** Dark translucent surface (`#0B0A10` at 80% opacity with 16px blur) bounded by a metallic hairline border. Used for tour schedules, bio cards, and service highlights.

### Input Fields & Controls
- Form inputs feature obsidian background fills, metallic muted text (`#E2E8F0`), and a 1px subtle chrome perimeter that ignites into an electric pink glow when focused.
- Checkboxes and toggles utilize pill forms with hot-pink active fills.

### Dashed "And More" Indicators
- Circular or pill-shaped callout elements using broken dashed borders (`2px dashed #FF1493`) containing centered bold display text, directly matching street flyer conventions for lineup announcements.