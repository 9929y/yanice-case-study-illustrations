# Visual System

Use this guide for portfolio case-study illustrations. Aim for one memorable, readable idea rather than all-purpose decoration. A process map may contain several necessary stages; a narrative or card image should usually center on one relationship or action.

## Resolve source-style conflicts

Apply the portfolio brief first for the image's job, format, and crop. Use Mesh Gradient Art for color, background, carrier shape, and line weight: full-frame semantic mesh, irregular ivory carrier, bold near-black ink, and sparse tinted accents. Borrow Xiaohei's content analysis, hand-drawn looseness, economy, active human participation, and structure selection. Do not carry over Xiaohei's pure-white-only rule, thin black lines, red/orange/blue annotation scheme, Chinese labels, fixed character, or general ban on formal process maps. A process map is appropriate when the brief needs one.

## Shared visual grammar

- **Mesh field:** Use a soft, opaque, full-bleed, organic mesh of overlapping low-saturation color fields, covering every corner without a white border or transparent edge. Let its color change support the case-study meaning; it is not a generic gradient backdrop. Avoid hard color splits unless the story itself is a clear before/after.
- **Carrier:** Place a generous, irregular ivory shape within or over the color field to hold the main scene. Let it occupy roughly 55–75% of the canvas as a starting point; adjust for aspect ratio, crop, and copy space. It can suggest a workspace, island, lens, page, or threshold. Keep it organic rather than a rounded UI card.
- **Ink:** Draw with confident near-black `#141413` lines, rounded ends, slight hand-drawn variation, and simplified shapes. Keep primary contours dark for readability. Allow only a restrained share of secondary paths, marks, or halos to pick up nearby mesh colors.
- **Palette:** Use ivory `#FAF9F5` and a controlled mix of cactus `#BCD1CA`, sky `#6A9BCC`, oat `#E3DACC`, heather `#CBCADB`, and fig `#C46686` or a close muted coral. Use clay `#D97757` sparingly for pressure, friction, or a meaningful turning point. Rebalance hues to the case study rather than placing every color in every image.
- **People:** Draw recognizable human figures with simplified anatomy, sparse facial detail, hand-drawn near-black contours, and expressive posture or hands. Use restrained palette accents in clothing or objects, not gradient-filled bodies. Choose a different context-appropriate person for each role/project; keep the same person's design consistent across images that depict that person. Do not create a fixed black-creature mascot or generic stock-vector people.
- **Detail:** Keep one dominant relationship and only a few supporting forms. Favor physical, slightly unexpected metaphors over floating icon collections. Leave breathing room and test the concept at thumbnail size.

## Keep a set visually consistent

For a set from one case study, define a compact visual lock before generating: mesh palette and color meanings, shape/scale of the ivory carrier, near-black stroke character, figure abstraction, and crop. Reuse those decisions for both wide images and cards. Change composition to fit placement; do not change the style system. Let each case study choose its own dominant mesh family while retaining the same palette, ink, carrier, and figure grammar across the portfolio. Do not reuse one fixed person as a mascot; retain a person's design only when that same person appears in multiple images of one story.

## Make the gradient mean something

Choose one semantic role before prompting and name it in the prompt. Suitable roles include:

- **Flow or orchestration:** color fields suggest movement between inputs, AI assistance, human judgment, and an outcome.
- **Discovery or clarity:** diffuse or overlapping fields resolve around the insight or decision that gives the experience direction.
- **Connection or trust:** cooler greens and blues carry stable relationships; warm accents identify a barrier or moment where confidence needs support.
- **Creative identity:** oat and fig/coral tones express human taste, brand personality, and possibility; use cooler tones for the system that carries that identity into use.
- **Tension or tradeoff:** keep the overall scene calm and make a small warm area mark the specific source of friction.

These are starting points, not fixed mappings. Keep semantic use consistent within an illustration set. Let the evidence and tone of each case study determine the color meaning. Do not use neon, rainbow, glossy glass, dark cyber-tech backgrounds, heavy glow, or generic purple-blue SaaS lighting.

## Wide narrative illustrations

Use for an image placed inside a case study to explain a pivotal insight, transition, or relationship. For an explicit step-by-step process, use the dedicated process mode below and in `process-flow.md`.

- Default to landscape 16:9 when the page placement is unknown.
- Let the scene move across the frame when sequence matters, or use a centered/off-center focal cluster when the insight is relational rather than chronological.
- Make the direction of change visible through gesture, path, object transformation, scale, or color transition. Use no more stages than needed to make the idea clear.
- Keep the focal scene large enough to read and leave quiet space around it. Unless a process map is explicitly requested, avoid multiple labeled steps, boxed panels, chart-like nodes, and literal dashboard mockups.
- Use a close crop or scene detail instead of cramming a complete case study into one image.

## Project-card illustrations

Use for a portfolio grid or project overview where a visitor scans several projects quickly.

- Match the card's real crop when available; otherwise use a landscape 4:3 composition.
- Reduce the case study to one recognizable object/person/action that can be read at small size. Keep the focal form bold and uncluttered.
- Carry the same mesh, ivory, and ink language as the wider case-study art, but let each project have its own dominant color balance or metaphor so the cards remain distinguishable.
- Preserve enough quiet area for the website's card title or crop. Do not render the project name into the artwork unless explicitly requested.

## Process illustrations

When the image's job is to explain a process, use an explicit sequence of stages and routes. Xiaohei's references demonstrate that flows can stay playful and hand-drawn while showing concrete inputs, processing, outputs, and feedback. Do not hide the sequence inside an ambiguous metaphor. See `process-flow.md` for the full process-map grammar.

## Prompt blueprint

Adapt this outline to the specific story; do not paste placeholders into a final prompt.

```text
Create one original editorial illustration for [case study and placement].
Show [one user problem, design insight, or product change] through the metaphor of [single concrete action/relationship].
A distinct person [specific active gesture] with [object/system that represents the change]. Make [sequence/contrast/relationship] readable at [wide 16:9 narrative / card crop / specified aspect ratio].
Use a full-bleed, soft organic mesh field whose colors express [semantic role], an irregular ivory #FAF9F5 carrier, and bold, simplified, hand-drawn near-black #141413 linework. Use a restrained selection of [palette colors]; allow only a few secondary routes or marks to echo the nearby mesh. Keep the scene spacious, human, and legible at display size.
No text by default. If exact words are required, include only: [verbatim English text].
Avoid dashboards, product UI panels, generic stock-vector people, cute mascots, logos, invented metrics, gibberish text, Chinese characters, photorealism, 3D, neon, rainbow gradients, heavy glow, and copied reference compositions. Do not reject a clear process map when one is requested; style its stages, routes, and people in the shared visual language. For exact wording, create the artwork without text and add a controlled overlay when available.
```

## Quality check

Accept an illustration only when:

- It communicates one case-study insight without explanatory labels.
- The person acts in the scene and the action communicates the change.
- A requested process reads in the correct order, with necessary decisions, handoffs, outputs, and feedback visible; an unrequested diagram has not been added to a narrative image.
- The mesh palette and ivory carrier feel like one intentional visual system.
- The gradient reinforces the meaning instead of competing with the drawing.
- Across a set, the mesh treatment, ink character, carrier, and figure abstraction remain consistent while each image fits its purpose.
- The crop, aspect ratio, and focal scale suit the actual case-study placement.
- Text is absent or short, exact, and English-only.
- No project facts, UI, logos, or outcomes have been invented.

## Reference provenance

- Mesh palette, semantic color fields, carrier, ink hierarchy, and vector approach are adapted from the [Mesh Gradient Art skill](https://github.com/9929y/anthropic-mesh-gradient-art/blob/main/SKILL.md), its [style specification](https://github.com/9929y/anthropic-mesh-gradient-art/blob/main/references/style-spec.md), and [SVG guide](https://github.com/9929y/anthropic-mesh-gradient-art/blob/main/references/svg-output.md).
- Story-anchor selection, process structures, active character roles, and anti-repetition rules are informed by Xiaohei's [composition patterns](https://github.com/helloianneo/ian-xiaohei-illustrations/blob/main/ian-xiaohei-illustrations/references/composition-patterns.md), [character guide](https://github.com/helloianneo/ian-xiaohei-illustrations/blob/main/ian-xiaohei-illustrations/references/xiaohei-ip.md), and [QA checklist](https://github.com/helloianneo/ian-xiaohei-illustrations/blob/main/ian-xiaohei-illustrations/references/qa-checklist.md).
- This skill does not bundle or reproduce either repository's example artwork or fixed character. The mesh repository's bundled reference images are deliberately not redistributed because its notice does not establish their upstream license.
