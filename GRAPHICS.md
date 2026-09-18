# Graphics triage — content chapters only

Intro (`00-*`) and summary (`03-*`) chapters are out of scope. Stock `qa.png` / ROI logo left as-is.

## How to read Markdown comments

| Comment tag | Who acts | What to do |
| :--- | :--- | :--- |
| `<!-- HUMAN SCREENSHOT: ... -->` | Human | Capture real product UI; replace the orange dashed SVG placeholder with a PNG; update the Markdown path to `.png` |
| `<!-- ANTIGRAVITY / NANO BANANA ... -->` | Antigravity | Generate illustration per prompt advice; replace the green dashed SVG placeholder with a PNG; update the Markdown path to `.png` |
| Existing conceptual `.svg` (no dashed banner) | Done | Keep unless you want a style refresh |

## SVG created here (teachable diagrams)

### Course 01
- `ch01-tokens-chunks.svg` — tokens as counted chunks
- `ch02-traffic-light-data.svg` — green/yellow/red upload guidance
- Plus prior: genai loop, context desk, projects, MasterClass path, POCC, deliverable chain

### Course 02
- `ch01-tab-tax-math.svg` — switching cost napkin math
- `ch02-narrow-vs-wide-scope.svg` — extension scope
- Plus prior: product family, extensions concept, upload vs extension, Cowork glimpse

### Course 03
- `ch01-sandbox-lifecycle.svg` — create → work → destroy
- `ch02-injection-defense.svg` — pause/reject loop
- Plus prior: ask vs delegate, approval modes, guardrails, Code glimpse

### Course 04
- `ch01-cli-vs-desktop-code.svg` — why CLI for org-cloud routing
- `ch02-five-point-review.svg` — AI diff checklist
- Plus prior: git basics, MasterClass path, code loop, cloud trust, agent teams

## Antigravity / Nano Banana (illustration)

| Course | Placeholder SVG | Target PNG | Theme |
| :--- | :--- | :--- | :--- |
| 01 | `ch01-office-analogy.svg` | `ch01-office-analogy.png` | Briefing a colleague |
| 01 | `ch01-jordan-friday.svg` | `ch01-jordan-friday.png` | Friday status crunch |
| 01 | `ch02-plausible-wrong.svg` | `ch02-plausible-wrong.png` | Fluent but false |
| 02 | `ch01-context-switching.svg` | `ch01-context-switching.png` | Tab tax mood split |
| 02 | `ch02-downloads-trap.svg` | `ch02-downloads-trap.png` | Downloads catch-all |
| 03 | `ch01-sandbox-cleanroom.svg` | `ch01-sandbox-cleanroom.png` | Ephemeral clean room |
| 03 | `ch02-prompt-injection.svg` | `ch02-prompt-injection.png` | Malicious PDF whisper |
| 04 | `ch01-inherited-codebase.svg` | `ch01-inherited-codebase.png` | Maze → clear path |
| 04 | `ch02-secrets-in-prompt.svg` | `ch02-secrets-in-prompt.png` | Block secrets poster |

Full prompt advice lives in the HTML comments above each image in the chapter Markdown.

## Human screenshots (product UI)

| Course | Placeholder SVG | Capture |
| :--- | :--- | :--- |
| 01 | `ch01-claude-ai-workspace.svg` | Claude.ai home + history |
| 01 | `ch02-file-upload.svg` | Upload + grounded question |
| 01 | `ch02-chart-in-chat.svg` | In-chat chart |
| 02 | `ch01-quick-entry.svg` | Quick Entry over an app |
| 02 | `ch01-sync.svg` | Same thread web + Desktop |
| 02 | `ch01-extension-installed.svg` | Extension enabled |
| 02 | `ch02-permission-review.svg` | Permission panel |
| 03 | `ch01-cowork-session.svg` | Cowork session chrome |
| 03 | `ch01-cowork-scope.svg` | Scoped folder/connector |
| 03 | `ch01-cleanup-plan.svg` | Plan before execute |
| 03 | `ch02-computer-use.svg` | Browser use + mid approval |
| 04 | `ch01-cli-cloud-connected.svg` | CLI org-cloud success |
| 04 | `ch01-docs-plan.svg` | Docs plan/diff |
| 04 | `ch02-diff-review.svg` | PR/diff review |

Use fictional sample data only. After capture: save PNG beside the SVG, flip the Markdown `![...](...svg)` to `.png`, leave or delete the placeholder SVG.
