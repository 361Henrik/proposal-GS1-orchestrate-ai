# Design tokens — ThreeSixtyOne / Lynxeye reference

Extracted from the Lynxeye proposal page so the GS1 site matches exactly.

## Colour
| Token | Hex | Use |
|-------|-----|-----|
| `--page` | `#f8f3ed` | warm off-white page background |
| `--card` | `#fefdf9` | card / panel background |
| `--card-alt` | `#faf6ea` | greyed/inactive card (stage 1, "later") |
| `--green` | `#1f4a39` | deep forest — thesis bar, headings accents, footer |
| `--green-badge` | `#366f5c` | stage number badges, mid-green accents |
| `--gold` | `#c69745` | eyebrow labels (VALUE CREATION UNLOCK), rules |
| `--ink` | `#1c1b18` | body text near-black |
| `--ink-soft` | `#5b5750` | secondary grey text |
| `--line` | `#e4ddd0` | hairline borders |

## Type
- **Display / headlines:** a serif (Lynxeye uses a high-contrast serif).
  Use `Fraunces` or `Playfair Display` (Google) as the closest free match —
  big, tight leading, regular weight for the long headline.
- **Body / labels:** a clean grotesque/sans. Eyebrows are uppercase, letter-
  spaced, gold, small. Body is a neutral sans.
- Eyebrow style: `text-transform: uppercase; letter-spacing: .12em;
  font-size: .72rem; color: var(--gold); font-weight: 700;`

## Components
- **Cards:** ~1px border `--line`, ~14px radius, generous padding (~28px),
  soft shadow. White on the off-white page.
- **Thesis bar:** full-width forest-green band, white text, used once to state
  the central question/claim.
- **Stage badge:** filled circle, green `--green-badge`, white number.
  Inactive stage = grey circle.
- **Staircase:** cards stepped diagonally bottom-left → top-right, joined by
  short green diagonal connector segments.
- **Footer payoff line** under each card: bold ink, short.

## Layout
- Single column, max-width ~1100px, centered, mobile-first stack.
- Section eyebrow (gold) → big serif heading → content.
- Numbered rows for detailed breakdowns (the "questions" pattern), each row a
  number + heading + 3-column sub-grid.
