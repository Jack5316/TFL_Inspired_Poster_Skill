---
name: create-tfl-inspired-posters
description: Create original London transport-inspired posters, standalone illustrations, repeat patterns, and fictional transit logo or mark concepts. Use for TfL, London Underground, Tube, bus, rail, urban-mobility, destination, event, safety, service, or travel visuals; roundel-inspired or geometric transit marks; vintage, modernist, Art Deco, decade-specific 1920s–1960s, photographic 1980s–1990s, neo-deco 2000s, or contemporary LED, digital, immersive, and anamorphic campaigns; and requests referencing Edward McKnight Kauffer, Abram Games, Hans Schleger or Zero, Edward Bawden, Horace Taylor, or Tom Purvis. Produce artistic homages and new compositions rather than exact replicas or apparently official TfL materials.
---

# Create TfL-Inspired Visuals

Produce a finished visual, not only a prompt. Preserve the hundred-year London transport tradition of concise communication, strong public-space legibility, geometric order, visual wit, and an invitation to move through the city.

## Load the right references

- Read `references/template-atlas.md` for every creation. Select one named template or combine at most two.
- Read `references/style-system.md` for era, palette, typography, texture, format, and brand-safety decisions.
- Read `references/campaign-recipes.md` for rapid briefs in eight common lanes: dimensional-type safety, classic destination, cultural venue, seasonal, abstract power, moquette/pattern, promotional service, and digital/immersive work.
- Read `references/output-modes.md` for standalone illustration, seamless pattern, logo/mark concepts, decade selection, or requests naming historical London Transport artists.
- Read `references/historical-phases.md` whenever a user asks for a period, decade, historical progression, heritage remix, photographic corporate campaign, neo-deco revival, or digital/immersive future.
- Read `references/vector-starters.md` for editable SVG delivery, exact-text fallback, or when a deterministic layout is more useful than a generated raster image.
- Read `references/copy-patterns.md` whenever copy is missing, weak, long, or must be arranged precisely.
- Read `references/research-notes.md` only when explaining the historical basis or refreshing the skill with new research.

## Workflow

1. Inspect every supplied image. Use `view_image` for local files before making visual judgments. Treat reference images as evidence for composition, palette, material, camera angle, and mood; do not assume their provenance.
2. Extract a compact brief: output mode, subject, audience, message, destination or action, requested era, required wording, format, and whether the output is a one-off or a series.
3. Classify the mood lane and historical phase: punchy dimensional type, classic elegant modernism, vibrant contemporary illustration, atmospheric seasonal, abstract system, pattern-led, photographic corporate, neo-deco craft, digital/immersive, or clear service promotion. Choose a template from the atlas or a matching campaign recipe. If the user gives no era, choose the structure that best converts the subject into a transport metaphor; do not default mechanically to a roundel or Tube map.
4. Build a six-slot generation brief: era anchor; subject and story; technique; 3–5 colour palette; typography and exact text; format and finish. Then add template ID, composition, metaphor, accessibility constraints, originality boundary, and exclusions.
5. Choose the rendering path. Generate raster artwork directly with `image_gen.imagegen`; omit image references unless the user supplied them. For photo-based reinterpretation, include only the required source images. For an explicit SVG request, repeated exact-text failure, or layout-system deliverable, adapt the nearest original starter in `assets/vector-starters/` and follow `references/vector-starters.md`. Never trace an official roundel.
6. Inspect the result. Regenerate once if the headline is misspelled, key text is unreadable, the hierarchy is weak, or the result looks like an official TfL notice. Prefer correcting the prompt over explaining a flawed output.
7. Return the finished image or requested vector mark with a one-sentence note naming the template family and output mode. When another pass would be useful, offer at most three meaningful variation axes: dominant colour, viewpoint, texture level, repeat scale, or flat versus deeply extruded type.

If the user asks for a prompt rather than a finished image, return the phase or mode label, the assembled generation prompt, a 3–5 colour palette with hex values, and one likely failure to watch. Do not replace a requested finished visual with prompt-only output.

Do not pause for questions when the supplied theme is sufficient. Infer tasteful copy and a format. Ask only when a missing exact name, date, price, or mandatory wording would materially change the poster.

## Composition rules

- Use one dominant idea readable at platform distance: one metaphor, one focal object, or one headline construction.
- Keep the primary headline to 2–7 words and no more than two typographic voices.
- Let the headline occupy roughly 30–50% of the frame when it is the hero. For dimensional-type work, integrate letters into doors, rails, seats, stairs, escalators, platform edges, or vehicle structure.
- Reserve 8–12% quiet margin and keep critical text away from trim edges.
- Make transit visible through motion, route, rhythm, interchange, ticket, platform, vehicle, destination, or public-space cues; London landmarks are optional.
- For promotional work, sell the destination, experience, or human benefit before showing transport hardware. For safety or service work, make the requested action the dominant visual idea.
- Include at least five of these signatures: short headline, limited palette, geometric structure, asymmetric balance, flat or shallow depth, tactile print texture, visual pun, compact service line.
- Default posters to portrait 2:3. Use 16:9 for digital motion frames, 3:2 for carriage panels, 1:1 for marks or social output, and square seamless tiles for patterns.
- When given multiple images for one output, synthesize their shared visual evidence into one composition unless the user explicitly asks for a collage.

## Typography and exact text

- Put exact requested text in quotation marks inside the generation prompt and label it `render exactly once`.
- Use mixed case for friendly information and all caps only for short commands or monumental word-objects.
- Use a rounded humanist sans, geometric display sans, condensed grotesk, or sturdy slab according to the chosen era. Never claim to use New Johnston; it is an exclusive TfL typeface.
- If more than 18 words are required, split them into headline, support line, and small footer. Do not ask image generation to render paragraphs.
- If image generation repeatedly corrupts mandatory text, generate a clean text-free art field with reserved panels, then typeset the exact copy with an available local font in a deterministic graphics workflow.

## Originality and brand boundary

- Create London-transport-inspired art, not an exact copy of a museum poster, living campaign, or supplied reference.
- Do not reproduce the official TfL roundel, exact Tube map, service marks, uniforms, or apparently authoritative wayfinding unless the user supplies authorized assets and explicitly requests their use.
- For roundel-inspired marks, change the geometry, proportions, bar placement, palette, and wording enough to create a distinct fictional identity. Never use `TRANSPORT FOR LONDON` as the wordmark by default.
- Do not present generated service, fare, safety, or disruption information as real. When the poster names TfL or could be mistaken for official communication, add a discreet `UNOFFICIAL CONCEPT` or `FAN POSTER` footer.
- Do not imitate one artist's exact signature. Combine a period's design grammar with a new subject, spatial logic, and palette.
- Use generic phrases such as `LONDON TRANSIT`, `CITY LINES`, or a user-provided fictional operator when a brand block is useful.

## Variation strategy

For multiple outputs, vary the structural family before varying decoration:

- Variant A: object or type as infrastructure
- Variant B: flat symbolic visual pun
- Variant C: map or system abstraction
- Variant D: contemporary civic illustration or photo-led layout

Keep the campaign constant through one headline system, one recurring accent colour, one footer grid, and one texture family. Do not make nominal variants by merely swapping colours.

For a requested series, prefer 3–4 posters with complementary scenes and one locked type treatment. Change the dominant structural idea only when the user requests exploratory concepts rather than a unified campaign.

## Quality bar

Reject or regenerate work that has generic travel-postcard collage, random London icons, more than one dominant metaphor, pseudo-map clutter, illegible microtype, glossy 3D rendering without print character, a non-seamless pattern that was requested as a tile, or a copied official identity. The final result should feel commissioned for a public transport environment: immediate, intelligent, warm, and memorable.
