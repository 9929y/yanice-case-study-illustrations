# Yanice Case Study Illustrations

A Codex skill for creating mesh-gradient editorial illustrations for Yanice Yang's product-design case studies. It covers wide case-study narratives, project cards, explicit process maps, journeys, handoffs, before/after scenes, and user states. It keeps the visual language consistent, uses context-specific people, and uses English for any image labels.

## Install in Codex

Clone this repository into Codex's personal skills folder:

```sh
git clone https://github.com/9929y/yanice-case-study-illustrations.git ~/.codex/skills/mesh
```

Replace `9929y` with the GitHub account that owns this repository. Restart or reload Codex if the skill does not appear right away. In Codex, invoke it with `$mesh`, or choose **Yanice Case Study Illustrations** from the skill picker. Codex skills use the `$` skill mention syntax; `/mesh` is not the skill invocation syntax.

To install it for one project only, clone it into that project's `.agents/skills/mesh` folder:

```sh
git clone https://github.com/9929y/yanice-case-study-illustrations.git .agents/skills/mesh
```

Then open that project in Codex and invoke `$mesh`.

## Use in ChatGPT

Cloning a repository does not automatically install a ChatGPT skill. Download the repository as a ZIP, then use **Skills → Create → Upload from your computer** if Skills are enabled for your account or workspace. A workspace administrator can also import it through a GitHub plugin marketplace, which requires a plugin package and workspace-admin access.

After installation, request the image and name its case-study page, placement, and type. For example: “Use `$mesh` to create a wide process illustration for the Lark onboarding case study. Preserve the real sequence and handoffs.” The skill guides the workflow; actual generation uses the image-generation capability available in the active product.

## What's included

- `SKILL.md`: the reusable workflow and visual/style decisions
- `references/visual-system.md`: mesh palette, linework, people, card and wide-image rules
- `references/process-flow.md`: workflow, journey, decision, and handoff composition
- `references/vector-output.md`: guidance for editable SVG when requested
- `agents/openai.yaml`: display name and short description for Codex

The skill references the public `anthropic-mesh-gradient-art` and `ian-xiaohei-illustrations` projects for visual and story-composition guidance. It does not redistribute their artwork or characters.
