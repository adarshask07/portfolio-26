---
name: Adarsh Satpute Portfolio
description: A calm editorial monograph in pale stone, ink-navy and one bottle-green band, set in Caslon and Hanken Grotesk.
colors:
  ground-stone: "#eceeea"
  ink-navy: "#101e2b"
  muted-slate: "#46535c"
  hairline: "#c5cac4"
  bottle-green: "#17352d"
  green-ink: "#e8ede7"
  green-muted: "#a9bbb2"
  green-hairline: "#35564b"
  brass: "#7a5c22"
  brass-light: "#c9a15a"
typography:
  display:
    fontFamily: "Libre Caslon Display, Iowan Old Style, Georgia, serif"
    fontSize: "clamp(3.25rem, 9.2vw, 6rem)"
    fontWeight: 400
    lineHeight: 1
    letterSpacing: "-0.015em"
  headline:
    fontFamily: "Libre Caslon Display, Iowan Old Style, Georgia, serif"
    fontSize: "clamp(1.75rem, 3vw, 2.25rem)"
    fontWeight: 400
    lineHeight: 1.15
  title:
    fontFamily: "Libre Caslon Display, Iowan Old Style, Georgia, serif"
    fontSize: "clamp(1.375rem, 2vw, 1.75rem)"
    fontWeight: 400
    lineHeight: 1.2
  conviction:
    fontFamily: "Libre Caslon Display, Iowan Old Style, Georgia, serif"
    fontSize: "clamp(1.375rem, 2.4vw, 1.875rem)"
    fontWeight: 400
    lineHeight: 1.3
  body:
    fontFamily: "Hanken Grotesk Variable, Helvetica Neue, Arial, sans-serif"
    fontSize: "1.0625rem"
    fontWeight: 400
    lineHeight: 1.65
  label:
    fontFamily: "Hanken Grotesk Variable, Helvetica Neue, Arial, sans-serif"
    fontSize: "0.9375rem"
    fontWeight: 400
    lineHeight: 1.65
rounded:
  focus: "1px"
spacing:
  gutter: "clamp(1.25rem, 4vw, 3.5rem)"
  column-gap: "clamp(1rem, 2vw, 2rem)"
  section: "clamp(3rem, 6vw, 5.5rem)"
  entry: "clamp(1.75rem, 3vw, 2.5rem)"
  max-width: "88rem"
components:
  site-header:
    backgroundColor: "{colors.ground-stone}"
    textColor: "{colors.ink-navy}"
    height: "4rem"
  nav-link:
    textColor: "{colors.ink-navy}"
    typography: "{typography.label}"
    padding: "0.75rem 0"
  nav-link-cta:
    textColor: "{colors.bottle-green}"
  nav-link-hover:
    textColor: "{colors.brass}"
  text-link:
    textColor: "{colors.ink-navy}"
  text-link-hover:
    textColor: "{colors.brass}"
  skip-link:
    backgroundColor: "{colors.bottle-green}"
    textColor: "{colors.green-ink}"
    padding: "0.6rem 1rem"
  band:
    backgroundColor: "{colors.bottle-green}"
    textColor: "{colors.green-ink}"
    padding: "clamp(3.5rem, 7vw, 6rem) 0"
  band-link-hover:
    textColor: "{colors.brass-light}"
---

# Design System: Adarsh Satpute Portfolio

## Overview

**Creative North Star: "The Quiet Monograph"**

One calm editorial page on a 12-column grid. Richness comes from type, spacing and a single deep green band at the foot, not from paint. The mood is European, clean, minimalist, professional and high-class without being fancy. Structure is carried by hairline rules and generous whitespace; there are no cards, gradients, glows or shadows anywhere in the build.

The page reads in two tones: a cool pale-stone field with ink-navy text for the work, then one bottle-green band for credentials and contact. Brass is the only accent and it is rationed to links and focus. A high-contrast Caslon display face sets the name, headings and two pull convictions; a neutral grotesk does all reading.

**Key Characteristics:**
- Pale stone ground, ink-navy text, hairline rules as the only structure
- One bottle-green band closes the page; nothing else is filled
- Brass accent appears only on link underlines, link hover and focus rings
- Serif for voice (name, headings, convictions), sans for reading
- Two-column entry layout: label left, content right, on a 12-column grid
- A single authored load motion; content is visible without it

## Colors

A restrained cool-neutral palette with one deep green field and one metallic accent.

### Primary
- **Bottle Green** (`{colors.bottle-green}`): the closing band, selection highlight, skip link, and the Contact nav link text. The only filled color area on the page.

### Secondary
- **Brass** (`{colors.brass}`): link underlines, link hover color and focus outlines on the stone ground. Passes as text on stone.
- **Light Brass** (`{colors.brass-light}`): the same roles inside the green band, where dark brass would sink.

### Neutral
- **Pale Stone** (`{colors.ground-stone}`): page ground and sticky header (at 94% over the page).
- **Ink Navy** (`{colors.ink-navy}`): primary text and headings.
- **Muted Slate** (`{colors.muted-slate}`): role line, sub-labels, tech lists, skill descriptions, bullet dashes.
- **Hairline** (`{colors.hairline}`): all 1px rules, scrollbar track.
- **Green Ink** (`{colors.green-ink}`): text on the band.
- **Green Muted** (`{colors.green-muted}`): secondary text on the band (credential issuers, contact labels, footer).
- **Green Hairline** (`{colors.green-hairline}`): rules inside the band.

### Named Rules
**The Rationed Brass Rule.** Brass marks only what can be followed or focused: links, hover, focus ring. It never fills a surface or colors headings.

**The One Field Rule.** Exactly one saturated field exists, the green band, and it sits at the foot. Do not add a second.

## Typography

**Display Font:** Libre Caslon Display (with Iowan Old Style, Georgia, serif), self-hosted at 400
**Body Font:** Hanken Grotesk Variable (with Helvetica Neue, Arial, sans-serif), self-hosted

**Character:** A sharp, high-contrast Caslon for voice paired with a clean humanist grotesk for reading. Headings are never bolded; the serif's own weight is enough.

### Hierarchy
- **Display** (400, clamp 3.25rem to 6rem, line-height 1, -0.015em): the name in the hero only.
- **Headline** (400, clamp 1.75rem to 2.25rem, 1.15): section titles; band headings (contact up to 2.5rem, 1.2).
- **Title** (400, clamp 1.375rem to 1.75rem, 1.2): entry titles (project or role).
- **Conviction** (400, clamp 1.375rem to 1.875rem, 1.3, max 24em): the two hero statements.
- **Body** (400, 1.0625rem, 1.65): running text; entry ledes step up to 1.1875rem at 1.55; hero role and summary scale to 1.25rem. Bullet lists cap at 68ch, summary at 40em.
- **Label** (400, 0.9375rem): nav, sub-lines, tech lists, links, dates (tabular numerals). Footer 0.875rem. Skill terms are 600 weight. Sentence case throughout.

### Named Rules
**The Serif Speaks Rule.** Caslon is for the name, headings and convictions only. Anything read at length is Hanken Grotesk.

**The No Shouting Rule.** No uppercase, no letter-spaced small labels, no bold headings. Hierarchy comes from size, face and space.

## Layout

A 12-column grid (column gap clamp 1rem to 2rem) inside a centered wrap of max 88rem with a fluid gutter (clamp 1.25rem to 3.5rem). The hero name spans all 12 columns. Sections use a fixed split: title in columns 1 to 3, body in 4 to 12. Entries repeat that split in a 9-column subgrid: head in 1 to 3, body in 4 to 9. Skills use the same label-and-content rhythm. In the band, credentials take columns 1 to 6 and contact 8 to 12.

Rhythm is vertical and rule-driven: sections pad clamp 3rem to 5.5rem with a 1px top rule; entries pad clamp 1.75rem to 2.5rem with a rule between them. The hero is the loosest (up to 9rem top). The header is sticky, 4rem minimum, with a bottom hairline.

Below 52rem every split collapses to one column, convictions stack, and the three optional nav links hide, leaving the name mark and Contact.

## Elevation & Depth

Flat. There are no shadows, gradients or blurs at rest. Depth is conveyed by hairline rules and by the single change of field from stone to green. The sticky header is separated by a hairline, not a shadow.

### Named Rules
**The Hairline Rule.** Separation is a 1px rule in Hairline (or Green Hairline in the band). Never a shadow, card or tinted panel.

## Shapes

Rectilinear and unrounded. No component has a border radius; the only rounding is a 1px radius on the focus ring. Forms are defined by rules and whitespace. Bullets are 0.5rem by 1px dashes in Muted Slate, not dots. No icons, images or ornaments ship.

## Components

### Navigation
Sticky header on translucent stone with a bottom hairline. Left: the name as a Caslon mark (1.25rem, no underline). Right: text links at 0.9375rem with transparent underlines that draw in on hover; Contact is set in Bottle Green with a brass underline. Link padding of 0.75rem vertical keeps tap targets generous. A skip link slides in on focus.

### Links
Inherit text color, with a 1px brass underline offset 0.28em. Hover turns text brass and the underline to currentColor over 0.3s on the expo-out ease. Focus shows a 2px brass outline, 4px offset (light brass in the band).

### Entries
Not cards. A hairline-topped row: Title and muted sub-line on the left, lede, dash-bulleted points and a muted tech line on the right, with an optional link row. The first entry in a group has no top rule.

### Skills List
A definition list in the same label-and-content split: 600-weight term left, muted description right, hairline between rows.

### Green Band
The closing footer: Credentials list and Contact definition list (6.5rem label column) separated by Green Hairline rules, text in Green Ink with Green Muted for secondary lines, and a copyright row beneath a rule.

### Motion
One authored load moment: elements with the rise class fade up 0.75rem and unblur over 1.1s on the expo-out curve (cubic-bezier(0.16, 1, 0.3, 1)), staggered 110ms per step. Only under no-preference reduced motion; content is visible without it.

## Do's and Don'ts

### Do:
- **Do** separate content with 1px hairline rules and generous padding.
- **Do** set the name, headings and convictions in Libre Caslon Display at weight 400.
- **Do** limit brass to link underline, link hover and focus; use Light Brass on green.
- **Do** keep one green band at the foot and nothing else filled.
- **Do** use the label-left, content-right split on the 12-column grid for new sections, collapsing to one column below 52rem.
- **Do** keep motion to the single load rise and respect reduced-motion.

### Don't:
- **Don't** add shadows, gradients, glows or rounded corners.
- **Don't** introduce card grids or tinted panels; use ruled rows.
- **Don't** add a second accent color or a second filled field.
- **Don't** use uppercase or letter-spaced labels, bolded headings, section numbers or icons.
- **Don't** set long reading text in the serif.
