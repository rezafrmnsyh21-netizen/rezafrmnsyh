---
name: Dark Kinetic Y2K Neubrutalism
colors:
  surface: '#131313'
  surface-dim: '#131313'
  surface-bright: '#3a3939'
  surface-container-lowest: '#0e0e0e'
  surface-container-low: '#1c1b1b'
  surface-container: '#201f1f'
  surface-container-high: '#2a2a2a'
  surface-container-highest: '#353534'
  on-surface: '#e5e2e1'
  on-surface-variant: '#d2c5ab'
  inverse-surface: '#e5e2e1'
  inverse-on-surface: '#313030'
  outline: '#9b9078'
  outline-variant: '#4f4632'
  surface-tint: '#f5bf00'
  primary: '#ffe9b9'
  on-primary: '#3e2e00'
  primary-container: '#ffc700'
  on-primary-container: '#6e5400'
  inverse-primary: '#765b00'
  secondary: '#ffb59e'
  on-secondary: '#5e1700'
  secondary-container: '#ff571a'
  on-secondary-container: '#521300'
  tertiary: '#ebebeb'
  on-tertiary: '#2f3131'
  tertiary-container: '#cecfcf'
  on-tertiary-container: '#565859'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#ffdf94'
  primary-fixed-dim: '#f5bf00'
  on-primary-fixed: '#251a00'
  on-primary-fixed-variant: '#594400'
  secondary-fixed: '#ffdbd0'
  secondary-fixed-dim: '#ffb59e'
  on-secondary-fixed: '#3a0b00'
  on-secondary-fixed-variant: '#852400'
  tertiary-fixed: '#e2e2e2'
  tertiary-fixed-dim: '#c6c6c7'
  on-tertiary-fixed: '#1a1c1c'
  on-tertiary-fixed-variant: '#454747'
  background: '#131313'
  on-background: '#e5e2e1'
  surface-variant: '#353534'
typography:
  display-xl:
    fontFamily: Anton
    fontSize: 112px
    fontWeight: '400'
    lineHeight: 96px
    letterSpacing: 0.02em
  display-xl-mobile:
    fontFamily: Anton
    fontSize: 56px
    fontWeight: '400'
    lineHeight: 54px
    letterSpacing: 0.01em
  display-lg:
    fontFamily: Anton
    fontSize: 72px
    fontWeight: '400'
    lineHeight: 70px
    letterSpacing: 0.02em
  display-lg-mobile:
    fontFamily: Anton
    fontSize: 40px
    fontWeight: '400'
    lineHeight: 42px
    letterSpacing: 0.01em
  headline-lg:
    fontFamily: Anton
    fontSize: 48px
    fontWeight: '400'
    lineHeight: 48px
    letterSpacing: 0.02em
  headline-lg-mobile:
    fontFamily: Anton
    fontSize: 32px
    fontWeight: '400'
    lineHeight: 34px
    letterSpacing: 0.01em
  headline-md:
    fontFamily: Anton
    fontSize: 32px
    fontWeight: '400'
    lineHeight: 36px
    letterSpacing: 0.03em
  headline-sm:
    fontFamily: Space Grotesk
    fontSize: 22px
    fontWeight: '700'
    lineHeight: 28px
    letterSpacing: -0.01em
  body-lg:
    fontFamily: Space Grotesk
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Space Grotesk
    fontSize: 15px
    fontWeight: '400'
    lineHeight: 24px
  body-sm:
    fontFamily: Space Grotesk
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 20px
  label-md:
    fontFamily: Space Mono
    fontSize: 13px
    fontWeight: '700'
    lineHeight: 16px
    letterSpacing: 0.05em
  label-sm:
    fontFamily: Space Mono
    fontSize: 11px
    fontWeight: '700'
    lineHeight: 14px
    letterSpacing: 0.08em
spacing:
  gutter: 1.5rem
  gutter-mobile: 1rem
  margin: 3rem
  margin-mobile: 1.25rem
  space-xs: 0.375rem
  space-sm: 0.75rem
  space-md: 1.25rem
  space-lg: 2rem
  space-xl: 3.5rem
---

## Brand & Style

This design system fuses Y2K cyber-nostalgia with high-impact dark neubrutalism and raw editorial anti-design. Built for an unapologetic, high-octane creative portfolio, it conveys hyper-competence, counter-culture rebellion, and tactile craftsmanship. 

The aesthetic is anchored by deep charcoal foundations, broken up by paper-tear collages, electric yellow scribbles, sticker slaps, and hard-edged brutalist containers. It rejects sterile corporate minimalism in favor of visceral energy: aggressive condensed headlines, raw ink stamps, offset hard shadows, and deliberate compositional tension. The interface should feel like an underground design zine translated into a high-performance web experience.

## Colors

The palette operates on high visual tension and deliberate contrast ratios:

- **Canvas & Neutral Base (`#0D0D0D`)**: Deep charcoal void. Must feature a persistent subtle SVG noise grain overlay (3-5% opacity) to provide texture and eliminate digital sterility. Secondary surface tiers leverage `#18181B` and `#27272A`.
- **Primary Accent (`#FFC700`)**: Electric gold/yellow. Reserved for high-priority CTAs, scribbles, hand-drawn vector arrows, active states, and sticker highlights.
- **Secondary Accent (`#FF4D00`)**: Blaze orange. Used for urgent badges, live status beacons, hover state inversion, and utility tags.
- **Paper & Text Highlight (`#FFFFFF`)**: Pure tactile white. Applied to torn-paper containers, primary display typography, and sharp stark border lines.
- **Muted Body (`#A1A1AA`)**: Zinc gray. Softens technical details, extended prose, metadata timestamps, and secondary captions to balance the intensity of the display elements.
- **Border & Inset Neutral (`#3F3F46`)**: Subdued structural divider lines when hard white borders need restraint.

## Typography

The typographic system creates an aggressive dynamic scale:

1. **Display & Impact (`Anton`)**: Rendered exclusively in uppercase. Condensed, massive, and tightly tracked. Used for hero titles, section headings, and kinetic running tickers.
2. **Body & Utility (`Space Grotesk`)**: Provides geometric clarity and high legibility against dark backgrounds. Used for narrative text, case study intros, and feature descriptions.
3. **Labels & Metadata (`Space Mono`)**: Technical, monospaced, all-caps. Applied to tool tags, Adobe software pill indicators, timestamps, and metric readouts.
4. **Handwritten Vector Layer (Caveat / Custom SVG Script)**: Hand-drawn, expressive annotation scripts must be used as non-structural decorative overlays. They sit offset and rotated (`-4deg` to `6deg`) on top of display headlines and paper containers in `#FFC700`, functioning as editorial doodles, asterisks, and contextual remarks.

## Layout & Spacing

The system runs on a 12-column brutalist fluid grid on desktop (scaling to 4 columns on mobile and 8 columns on tablet):

- **Asymmetrical Offsets**: Elements intentionally break standard alignment boundaries. Cards and stickers feature overlapping coordinates (`margin-top: -1.5rem`, absolute positioned pin badges) to break box-model rigidity.
- **Running Tickers**: Full-bleed marquee ribbons running horizontally across section breaks with negative margins, framed by thick 2px borders.
- **Section Rhythm**: Sections are separated by heavy structural dividing lines (`border-bottom: 2px solid #27272A`) or jagged paper-tear SVG edge clips rather than passive white space.

## Elevation & Depth

No ambient, blurred, or diffuse drop shadows are permitted. Depth is created strictly through physical brutalist projection and textural collage:

- **Hard Neubrutalist Drop Shadows**: Solid, 100% opaque shadows with 0 blur. 
  - Standard interactive cards: `4px 4px 0px #000000` (on light surfaces) or `4px 4px 0px #FFC700` (on dark surfaces).
  - Hover elevation: Translates `-2px, -2px` with shadow expanding to `6px 6px 0px`.
  - Active/Pressed: Translates `4px, 4px` with shadow collapsing to `0px 0px 0px`.
- **Paper-Tear Clipping**: Select white feature cards utilize a bottom or top jagged mask (`clip-path: polygon(...)`) simulating hand-ripped newsprint, sitting over the dark canvas.
- **Layer Stacking**: Physical hierarchy is communicated via overlapping z-indices: Canvas (0) -> Noise (1) -> Neubrutalist Cards (10) -> Annotation Scripts & Stickers (20) -> Floating Cursors & Sticky Pill Nav (30).

## Shapes

The primary geometry is sharp (`roundedness: 0`), enforcing crisp industrial edges across cards, buttons, media frames, and inputs.

- **Selective Pill Inversion**: Badges, status chips, software tags, and marquee pills are strictly fully rounded (`border-radius: 9999px`) to create extreme contrast against the razor-sharp container architecture.
- **Tilt Angles**: Sticker chips and tactile badges apply micro-rotations (e.g., `-2deg`, `3deg`, `-5deg`) to emulate physical desk decals.

## Components

### Buttons
- **Primary**: Background `#FFC700`, text `#0D0D0D`, 2px solid `#FFFFFF` border, sharp corners. Hard shadow: `4px 4px 0px #FFFFFF`. Text is uppercase `Space Mono` bold. Hover shifts position `-2px, -2px` with shadow expanding to `6px 6px`. Active shifts `+4px, +4px` with shadow flush (`0px 0px`).
- **Secondary / Inverted**: Background `#0D0D0D`, text `#FFFFFF`, 2px solid `#FFFFFF` border. Hard shadow: `4px 4px 0px #FF4D00`.
- **Tape Button**: Background `#FFFFFF`, text `#0D0D0D`, slight `-1.5deg` rotation, raw edges, mono typography.

### Cards & Paper Tear Containers
- **Dark Neubrutalist Card**: `#18181B` surface, 2px solid `#3F3F46` or `#FFFFFF` border, hard shadow `6px 6px 0px #000000`.
- **Torn Paper Card**: Surface `#FFFFFF`, text `#0D0D0D`, top or bottom edge rendered with a jagged SVG tear path. Holds case study deep dives or high-priority editorial pieces. Monospaced metadata tags in black with yellow highlights.

### Adobe & Tool Badges
- **Software Badges (Ps, Ai, Id, Pr, Ae)**: Square or squircle micro-containers (32x32px or 36x36px), 2px solid border matching the application's signature color (e.g., `#31A8FF` for Ps, `#FF9A00` for Ai, `#EA3636` for Id), filled with deep tone backgrounds, bold condensed label centered. Offset rotated `-3deg` to `4deg`.

### Chips, Pills & Stickers
- **Pill Badges**: Pill-shaped (`rounded-full`), 1.5px solid border, uppercase `Space Mono` 11px. `#FF4D00` with white text for "HOT / LIVE", `#FFC700` with black text for "FEATURED".
- **Doodle Stickers**: Graphic vector badges (stars, retro smiley faces, barcodes, hand-drawn circle marks) scattered across container margins, interacting with hover triggers (scaling `1.1` and rotating `12deg`).

### Form Inputs
- Fields use `#18181B` fill with a crisp 2px solid `#3F3F46` border, scaling to 2px solid `#FFC700` upon focus.
- Placeholder text in `#A1A1AA`. Label rendered in uppercase `Space Mono` with an electric yellow asterisk (`*`).
- Selection controls (Checkboxes/Radio): Raw 0px square boxes, 2px solid `#FFFFFF`. Checked state filled with solid `#FF4D00` or `#FFC700` with a stark black check icon.

### Lists & Marquees
- **Interactive Index List**: Full-width bordered rows (`border-b: 2px solid #27272A`). Hovering a row inverts background to `#FFC700`, text switches to `#0D0D0D`, and projects a floating project thumbnail preview under the cursor.
- **Kinetic Ribbon**: Continuous marquee strip, border-top/bottom 2px solid `#FFFFFF`, text running in `Anton` display style with repeating starburst dividers (`✦`).