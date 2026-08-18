# Copy patterns

Use copy as part of the picture. Prefer one active phrase over a descriptive sentence.

## Headline patterns

| Purpose | Pattern | Examples |
|---|---|---|
| Destination | `[PLACE], THIS WAY` | `RIVER, THIS WAY` |
| Invitation | `GO [VERB]` | `GO WANDER` |
| Benefit | `[BENEFIT], BY [MODE]` | `MORE NIGHT, BY RAIL` |
| Command | `[VERB] THE [NOUN]` | `TAKE THE TURN` |
| Time | `[TIME] IS YOURS` | `SUNDAY IS YOURS` |
| Discovery | `FIND [NOUN]` | `FIND THE GREEN` |
| Connection | `[A] MEETS [B]` | `CITY MEETS RIVER` |
| Service | `[ADJECTIVE] [JOURNEY]` | `QUIETER JOURNEYS` |
| Cultural | `[EVENT] BY [MODE]` | `ART BY NIGHT BUS` |
| Wordplay | transform a travel idiom | `MAKE TRACKS` / `CHANGE YOUR VIEW` |

Do not reuse famous historic slogans merely for recognisability. Write new subject-specific lines.

## Copy hierarchy

Use at most these four layers:

1. Headline: 2–7 words.
2. Support: 4–12 words.
3. Destination/action: one place, date, or URL-like fictional cue.
4. Concept footer: `UNOFFICIAL CONCEPT` when needed.

If the user provides a paragraph, compress it into a headline and one support line. Preserve mandatory names, dates, and numbers exactly.

## Tone by era

- 1920s–1930s: declarative, brisk, aspirational: `THE BRIGHT CITY`, `OUT AFTER SIX`.
- 1940s–1960s: witty, economical, service-minded: `ROOM TO ROAM`, `A SHORT WAY FARTHER`.
- 1970s–1990s: cultured, system-aware: `ART CHANGES HERE`, `THE CITY, CONNECTED`.
- Contemporary: human, inclusive, direct: `YOUR WAY ACROSS`, `MORE CITY FOR EVERYONE`.

Use these as tone models, not mandatory slogans.

## Quick phrase bank

Prefer original, context-specific phrases. These short options are starting points:

- Safety and behaviour: `HOLD ON`, `WATCH YOUR STEP`, `KEEP CLEAR`, `LOOK UP`, `RIDE KIND`, `STAY AWARE`, `MAKE ROOM`, `TAKE CARE`.
- Travel and promotion: `HIT THE ROAD`, `GO EXPLORE`, `JOURNEY ON`, `ALL CHANGE`, `HOP ON`, `NIGHT LINES`, `CITY AHEAD`, `OUT YOU GO`.
- Destination and atmosphere: `THE RIVER`, `PARKS & GARDENS`, `BRIGHT LIGHTS`, `COUNTRY ESCAPE`, `CITY HEART`, `AFTER DARK`, `SUMMER OUTSIDE`.

Use recognisable live-system phrases such as `MIND THE GAP`, `WAY OUT`, or `CLOSING DOORS` only when the user explicitly requests them. Keep the result clearly unofficial and do not pair them with a copied roundel, map, or operational layout.

## Footer patterns

Keep footers generic unless the user provides authorized real information:

```text
CITY LINES • WEEKEND ROUTES
LONDON TRANSIT CONCEPT • SUMMER 2026
TAKE THE BLUE ROUTE • EXIT AT RIVERSIDE
UNOFFICIAL CONCEPT
```

Never invent a real fare, disruption, safety rule, station closure, accessibility status, or operating date.

## Exact-text prompt block

```text
Render the headline exactly once as: "[HEADLINE]".
Render the support line exactly once as: "[SUPPORT]".
Do not add any other words, logos, labels, numbers, signatures, or watermark.
```

If exact rendering fails, shorten the text before changing the visual concept. For mandatory long copy, reserve a clean panel and typeset it deterministically after image generation.
