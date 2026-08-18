# Style system

## Contents

- Core visual grammar
- Era selector
- Palette recipes
- Typography
- Material and image language
- Format and hierarchy
- Prompt construction
- Quality checks
- Failure diagnosis
- Brand and accessibility boundary

## Core visual grammar

Build the poster from a public-space idea, not a pile of London symbols. Strong London transport work usually combines:

1. A short invitation, instruction, destination, or benefit.
2. A single visual transformation: route into object, object into route, type into space, or destination into emblem.
3. A stable geometric scaffold that survives viewing from several metres away.
4. A deliberately limited palette with transport-like signal contrast.
5. A material language that suggests lithography, screenprint, cut paper, mosaic, woven moquette, or disciplined contemporary illustration.

Require high contrast. Build around a dominant colour field, a structural dark, and one or two accents; avoid muddy mid-tones. Use a first-person or slightly elevated view when the scene should feel embedded in a carriage, bus, platform, or escalator.

A useful T01/T22 grammar makes extruded letterforms into physical infrastructure inside a cropped high-angle vehicle environment. The transferable ingredients are occlusion, shallow isometric space, navy/ochre/red/cyan contrast, and grain—not any exact words or scene.

## Era selector

| Era | Use when | Structure | Surface |
|---|---|---|---|
| 1910s–early 1920s | heritage, early rail, civic invitation | illustrated frame, emblem, decorative geometry | stone lithograph, warm paper |
| 1920s–1930s | speed, nightlife, modernity, destinations | Cubist grids, Art Deco rays, monumental flat forms | opaque lithographic inks |
| 1940s–1960s | public service, wit, sightseeing | visual pun, negative space, cut-paper symbol | screenprint, gouache, halftone |
| 1970s–1990s | systems, culture, maps, strong identity | modular grids, map transformations, photography | crisp offset print |
| 2000s–present | inclusion, environment, apps, mode launches | editorial illustration, portrait, isometric scene, bold type | clean vector plus tactile grain |

Use era traits as ingredients, not museum replication. If no era is specified, prefer contemporary structure with one historic print process.

## Palette recipes

Use 3–5 colours plus paper. The hex values are creative starting points, not official TfL specifications. Treat transport red and blue as historical cues, never as an official identity system.

| Name | Colours | Character |
|---|---|---|
| Ochre interchange | `#E3A915` `#122557` `#C62824` `#46A6AE` `#D8D0C3` | energetic, isometric, close to the supplied reference |
| Deco night | `#101C3C` `#6E3158` `#E1AE49` `#F4E8CF` `#C85B4D` | theatre, winter, evening |
| Modernist power | `#202322` `#A8462D` `#26727A` `#E8DFCB` `#E6C738` | technology, speed, infrastructure |
| Park excursion | `#2F7358` `#9FC5C0` `#F0E5CC` `#C94D3D` `#233552` | outdoors, family, calm |
| Mid-century civic | `#E9DFC8` `#181A1D` `#B92E2B` `#244C79` `#E2A72E` | service, clarity, humour |
| Contemporary inclusive | `#F3E8D7` `#DF4C6B` `#23529B` `#F2BE32` `#51A68A` | warm, social, public-facing |
| One-hue field | one vivid subject hue + `#F0E8D8` `#27282B` `#A9A49B` | minimal civic illustration |

Do not lift official mode colours as a complete system. The skill should evoke transport logic without impersonating a live operator.

## Typography

- Historical spirit: geometric capitals, humanist sans, condensed grotesk, or sturdy slab; use broad shapes and careful spacing.
- Contemporary spirit: rounded humanist sans with open counters and friendly proportions.
- Use one display face and one neutral support face at most.
- Keep headline letterforms simple enough to become objects, routes, or apertures.
- Let a dimensional headline use 30–50% of the frame; reserve long copy for a separate flat panel.
- Avoid the exact Johnston/New Johnston/Johnston 100 identity unless the user provides licensed assets and is authorized to use them.
- Never say a generic substitute *is* Johnston. Describe it as `rounded humanist sans with open counters and a civic wayfinding tone`.
- Approximate hierarchy: headline 100 units; support 28–38; destination or action 22–30; footer 12–16.
- Let at least one edge of the headline align to a structural feature: rail, platform, route, window, or colour boundary.

## Material and image language

Choose one primary process and one secondary imperfection:

- Lithograph: opaque flat inks, soft edge, slight colour misregistration.
- Screenprint: bold colour planes, visible mesh grain, occasional ink dropout.
- Gouache: matte paint, dry edge, hand-cut silhouette.
- Cut paper: fibrous edge, shallow physical shadow, colour from paper rather than gradients.
- Linocut: chunky carved line, irregular pressure, high contrast.
- Mosaic: large tessera-like blocks, restrained grout rhythm.
- Moquette: woven loop rhythm translated into print; never reproduce an exact protected seat pattern.
- Contemporary vector: precise geometry softened by one paper or ink layer.
- Photography: preserve truthful photographic pixels; use one photograph and let graphics organize it.

Avoid generic vintage filters, all-over distress, sepia, fake folds, random scratches, lens flare, chrome 3D, and glossy advertising renders.

## Format and hierarchy

| Placement | Ratio | Guidance |
|---|---:|---|
| Classic poster / bus shelter | 2:3 portrait | default; one hero at 55–75% of area |
| Four-sheet / landscape panel | 3:2 | widen the metaphor, do not add more ideas |
| Digital escalator panel | 9:16 | headline high, focal object central, safe bottom footer |
| Digital screen | 16:9 | one two-second read; no tiny text |
| Social square | 1:1 | crop structurally; do not shrink a portrait poster |
| Campaign pair | two 2:3 panels | lock headline and footer positions |

Keep a 10% text-safe zone. Use negative space as an active shape. Place small identity or concept text in a consistent bottom corner, never as a false official endorsement.

## Prompt construction

Fill these six slots before adding exclusions: `era anchor`; `subject and story`; `technique`; `3–5 colour palette`; `typography and exact text`; `format and finish`. Use destination-first storytelling for travel promotion and action-first storytelling for safety or operational concepts.

Use this expanded sequence:

```text
Create one finished [ratio] portrait poster, an original London public-transport-inspired concept.
Base structure: [template ID and name].
Composition: [large shapes, crop, angle, focal hierarchy, negative space].
Metaphor: [subject becomes route/object/type/space].
Render this exact text once: "[HEADLINE]". Secondary text: "[DETAIL]".
Typography: [character, case, dimensional role, placement].
Palette: [3–5 named colours or hex values].
Print language: [one process] with [one imperfection].
Mood: [three adjectives].
Keep: public-space legibility, broad forms, deliberate margins.
Exclude: official TfL logo, exact Tube map, New Johnston, extra text, mockup frames, photoreal CGI, copied poster composition.
Add a discreet "UNOFFICIAL CONCEPT" footer only if TfL is named.
```

If a source image is supplied, add a short evidence list: `preserve [orientation/object/colour relationship]; reinterpret [secondary detail]`. Do not let the prompt become an inventory of every visible item.

## Quality checks

Check before delivery:

- Headline is correct, present once, and readable at thumbnail size.
- A viewer can describe the visual idea in one sentence.
- The focal subject occupies at least half the perceptual weight.
- Palette has a dominant field, a structural dark, and no more than two accents.
- London/transport feeling comes from system logic and movement, not a random skyline.
- Texture is subtle and tied to a print method.
- No official logo, exact map, false fare, live safety instruction, or deceptive service claim appears.
- The work differs structurally from any supplied or researched reference.

Regenerate if three or more checks fail. If only footer microtext is imperfect and nonessential, do not overwork the image.

## Failure diagnosis

Fix the failed design slot instead of regenerating blindly.

| Symptom | Likely cause | Targeted correction |
|---|---|---|
| Garbled or duplicated headline | too much in-image copy or weak exact-text instruction | cut to 2–5 words, request it exactly once, or move copy to the SVG path |
| Generic travel-poster look | no precise phase, process, or transport metaphor | name one historical phase, one plausible print process, and one transformation |
| Orange-and-teal palette drift | colours described only as `retro` or `vintage` | state 3–5 named colours or hex values and identify the dominant field |
| Heritage work looks glossy | no physical print language | add one process and one imperfection: lithograph plus misregistration, or linocut plus uneven pressure |
| Digital work looks like a screensaver | no stable reading state or architectural anchor | reserve a true-black message zone and connect broad light forms to platform, tunnel, or gateway geometry |
| Word-object looks pasted on | scale, occlusion, and light disagree with the scene | share one vanishing point, one shadow direction, and at least one believable overlap |
| Poster resembles an official notice | identity cues accumulated | remove roundel-like geometry, real names, route colours, operational wording, and official footer structure |
| Square or accidental crop | format slot is missing | state ratio and placement explicitly; rebuild the composition rather than merely cropping |

## Brand and accessibility boundary

TfL's roundel is a trademark and its typeface is controlled. Inspiration should come from commissioning philosophy and public-communication clarity, not counterfeit identity. Use generic marks or none.

For public information concepts, maintain strong figure-ground contrast, avoid using colour as the only code, keep labels short, and avoid dense high-frequency stripes that can create visual discomfort. Never imply that a generated accessibility diagram or route is operationally current.
