# Editable Vector Output

Read when the user asks for SVG, editable vector layers, Figma/Illustrator reuse, or separated assets. Raster image generation remains the default for ordinary image requests.

## Output contract

- Construct a standalone native SVG directly; do not ask a raster image model to produce editable SVG and do not embed PNG/JPEG artwork.
- Set explicit `width`, `height`, `viewBox`, `role="img"`, and accessible `<title>` and `<desc>` elements.
- Keep gradients, ivory carrier, primary ink, mesh-tinted routes, people, process nodes/props, and optional English text in distinct, clearly named SVG groups.
- Include no scripts, external images, or external font dependencies.
- Use editable paths and shapes for the person and symbols. Prefer native text only for short, exact English labels.

## Style construction

- Cover the entire `viewBox` with an opaque mesh field made from restrained overlapping radial or linear gradients. Keep the color transitions organic and semantic.
- Draw one irregular ivory carrier as a named group. Clip only those marks that should remain inside it; allow meaningful paths to cross its edge.
- Use thick, rounded, slightly imperfect near-black contours as the visual anchor. Add mesh-colored accents only where they communicate a meaningful route, status, or transition.
- Keep a process path readable with open routes, clear arrowheads, and a distinct pattern for optional or return flows. Keep route patterns editable separately from nodes and people.
- For a cleaner process map, use lightly irregular native vector paths. For an explicitly painterly request, use subtle SVG-native organic washes, mild path variation, or low-opacity offset strokes; do not use raster textures or rely on filters that flatten the illustration in design tools.

## Layer naming

Use groups such as:

```xml
<g id="mesh-background">...</g>
<g id="ivory-carrier">...</g>
<g id="primary-ink">...</g>
<g id="mesh-accent-routes">...</g>
<g id="people">...</g>
<g id="process-nodes-and-props">...</g>
<g id="english-labels">...</g>
```

Omit groups that have no content. Preserve individual stage and person subgroups where editing them separately would help.

## Vector QA

- Confirm the SVG is standalone and contains no raster `<image>` elements or external references.
- Confirm mesh, carrier, ink, routes, people, and nodes are separately editable and named clearly.
- Confirm every route and label remains legible at the intended crop and size.
- Confirm English label strings are exact and supported by the case study.
- Confirm SVG opens in a browser and imports cleanly into a vector editor when one is available; describe any tool-specific limitation honestly.
