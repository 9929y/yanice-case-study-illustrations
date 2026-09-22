# Process and Workflow Illustrations

Read this when a user asks for a process illustration, workflow, system sequence, onboarding journey, handoff map, or before/after flow. The goal is to make the real process easy to follow while retaining the shared mesh-gradient and human editorial style.

## What to carry over from Xiaohei

The Xiaohei references use several clear structures rather than one generic flowchart:

- **Workflow:** inputs on one side, an active processing step in the middle, and outputs on the other. A distinct path color and arrowheads make the primary direction obvious.
- **System detail:** only the few important modules are shown; a character performs one meaningful operation inside the system.
- **Before/after:** a visible old state changes into a better state through a central action or transition.
- **Role/state sequence:** a few moments show how the user or creator's condition changes.
- **Route/map:** one continuous path links a small number of meaningful milestones; feedback can loop back when the source supports it.
- **Short comic sequence:** a few small scenes can explain a human journey, with one action in each scene.

For this portfolio skill, borrow the structural clarity, human participation, unusual physical metaphors, and economy of detail. Do not borrow the fixed Xiaohei creature. Draw a different, context-appropriate human figure and let their gesture operate the key stage: review a result, choose a branch, hand work off, resolve a blocker, or guide a transition.

## Select a structure before prompting

Choose the structure that matches the case-study evidence; do not mix several without a reason.

| Case-study content | Structure | Visual organization |
|---|---|---|
| A linear service or AI workflow | Workflow | Input → processing → output, read left to right or top to bottom |
| A product system with a few key parts | System detail | Show only the 3–5 consequential modules and their connections |
| A redesigned experience | Before/after | Establish the old state, the intervention, and the improved state |
| A user's changing experience | Role/state sequence | Show a few distinct moments and the action that changes the user's state |
| A journey with milestones or a return loop | Route/map | One continuous path with sparse nodes and a feedback path only when real |
| A short handoff or failure/recovery story | Comic sequence | 2–4 scenes, one action or state change per scene |

If the case study describes meaningful branching or human review, show that decision point. Do not flatten it into a linear arrow merely to simplify the drawing. If a branch, metric, or feedback loop is not supported by the source, do not invent it.

## Make the process legible

- Extract only the real stages needed to explain the selected story. Keep labels and nodes sparse; retain additional stages only when removing them would distort the process.
- Give the flow one clear reading direction. Use consistent arrowheads and keep crossings out of the primary route when possible.
- Distinguish primary flow, optional route, and feedback loop using both shape and color: for example, a continuous main route, a dotted optional path, and a dashed return path. Do not rely on color alone.
- Give each node a visual job: source, decision, transformation, human review, handoff, output, or feedback. Avoid rows of identical generic boxes.
- Let a person interact with a consequential node or route. Examples: checking an AI-generated draft before release, redirecting a mismatched source, passing work to a teammate, or helping a user cross an onboarding barrier.
- Use physical metaphors only to clarify the process: sorting trays can show routing, a bridge can show handoff, or a valve can show a decision gate. Keep the actual sequence visible around the metaphor.
- Use no decorative arrows. Every route must communicate direction, dependency, choice, or feedback.

## Integrate the mesh-gradient art direction

- Keep the mesh as a full-frame semantic field behind the process, with an irregular ivory carrier or open ivory lane giving the stages a calm, readable ground. The carrier must not turn into a stack of UI cards.
- Anchor stage drawings, people, and critical symbols with near-black `#141413` hand-drawn contours.
- Let restrained mesh-tinted accents enter the path system. Echo the local field with sky for infrastructure/routing, cactus for trust/stability, heather for analysis or uncertainty, and fig/coral for creative choice. Use clay sparingly for a true friction point, risk, or intervention; do not make every primary route orange by default.
- Keep tinted routes distinct from one another using line patterns or arrow shapes as well as hue. Preserve enough contrast against both the ivory carrier and gradient field.
- Keep near-black as the structural anchor. Let roughly 20–30% of visible strokes carry mesh tint in ordinary cases; a primary route may use a stronger tint when process clarity requires it, while node contours, people, and key symbols remain near-black.
- Avoid technically perfect connector curves, dense node webs, dashboard panels, and polished corporate flowchart styling. Use loose but controlled hand-drawn paths and simplify the symbols.

## Text in process diagrams

- English only. Prefer no title inside the image; the webpage already supplies the case-study title.
- When labels materially improve comprehension, use short English stage names (usually one to three words). Prefer real terms from the case study; translate a source term faithfully when a concise English equivalent is needed.
- Put only the required English strings in the prompt. Never introduce unsupported stages, Chinese characters, pseudo-text, or extra generated annotation.
- If exact spelling is essential and image generation renders labels unreliably, generate the illustration without text and add the labels as a separate editable overlay using an available authoring tool.

## Process prompt blueprint

```text
Create one [wide case-study process image / card crop] for [project and placement].
Show the documented process: [input/source] → [key stages] → [output], including [decision/hand-off/feedback] only when present in the case study. Use a [workflow / system detail / before-after / role-state / route-map / short comic] structure with a clear [left-to-right / top-to-bottom / path] reading order.
Depict a distinct [user / creator / designer / teammate] actively [specific action] at [consequential stage]. Use [one physical metaphor] to make [specific relationship] memorable without obscuring the real order of the process.
Keep the route legible: [continuous primary flow], [optional route if any], [feedback route if any]. Near-black #141413 contours anchor the stages and figure; restrained mesh-tinted path accents express [semantic meaning]. Use a full-frame soft mesh field in [palette colors] and an irregular ivory carrier that grounds the process without forming UI panels.
Include only these short English labels, if any: [exact source terms or faithful English translations]. No other words or title.
Avoid invented steps, branches, labels, or outcomes; pseudo-text; Chinese characters; generic icon rows; dense architecture diagrams; dashboard cards; and copied Xiaohei example compositions.
```

## Process QA

Before delivery, verify:

- A viewer can identify where the process starts, how it moves, and where it ends.
- Required branches, user decisions, handoffs, or feedback loops match the source.
- A real person is involved in a meaningful step, rather than pasted beside the flow.
- Labels, when used, are short, accurate, and English-only.
- The mesh palette contributes atmosphere and state without obscuring route direction.
- The composition is understandable at its intended page size and crop.
