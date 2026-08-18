# TfL-Inspired Poster Skill

An agent skill for creating original London transport-inspired posters, standalone illustrations, repeat patterns, and fictional transit marks.

It produces finished visuals in the hundred-year London transport tradition: concise communication, strong public-space legibility, geometric order, and visual wit. Work is treated as artistic homage, not official TfL material.

## Install

Clone this repository into your agent's skills directory:

```bash
git clone https://github.com/Jack5316/TFL_Inspired_Poster_Skill.git create-tfl-inspired-posters
```

Or copy the folder so `SKILL.md` sits at the skill root.

## What's inside

| Path | Role |
| --- | --- |
| `SKILL.md` | Workflow, composition rules, brand boundary, and quality bar |
| `references/` | Template atlas, style system, campaign recipes, historical phases, copy patterns, output modes |
| `assets/vector-starters/` | Editable SVG starters for deterministic layouts |
| `agents/openai.yaml` | ChatGPT / Codex skill interface |

## Use

Ask the agent to create a London transport-inspired poster, illustration, pattern, or fictional mark. Give a subject, destination, era, or mood if you have one. The skill will pick a template family, assemble a brief, and return a finished visual.
