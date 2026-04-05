# Demo Asset Shot List

This file lists the exact public-safe assets worth adding to the showcase repo.

## Recommended Screenshots
Add these to `media/screenshots/`.

### 1. Review Sheet Screenshot
Filename:
- `01_review_sheet_top10.png`

Show:
- filled `review_sheet.csv`
- `review_label`, `keep`, and `notes`
- a few rows with different outcomes (`good`, `bad`, `finalist`)

Why:
- proves the project is built around review-driven finalization, not fake full autonomy.

### 2. Selection Manifest / Audit Screenshot
Filename:
- `02_selection_audit.png`

Show:
- top-ranked clips from a `selection_manifest.json` or `selection_audit.csv/json`
- visible fields like `score_total`, `opening_punch`, `ending_resolution`, `boringness_penalty`, `scene_type`

Why:
- shows the project has real evaluation artifacts and selector diagnostics.

### 3. Final Vertical Clip Frame
Filename:
- `03_vertical_output_frame.png`

Show:
- one final 9:16 frame with subtitles visible
- ideally one frame that demonstrates subtitle styling and crop quality

Why:
- gives a fast visual proof that the pipeline actually renders usable short-form output.

### 4. Architecture Diagram Screenshot
Filename:
- `04_architecture.png`

Show:
- exported architecture diagram from the repo docs
- keep it clean and readable

Why:
- helps recruiters and hiring managers understand this as a systems/orchestration project.

### 5. Optional Metrics / Channel Result Screenshot
Filename:
- `05_results_metrics.png`

Show:
- safe analytics screenshot such as views graph, output count, or other public-safe validation metric
- redact anything sensitive if needed

Why:
- adds product credibility beyond pure engineering description.

## Recommended Videos
Add these to `media/video/` or host externally and link from `README.md`.

### 1. Main Portfolio Demo
Filename:
- `shorts_foundry_demo.mp4`

Target length:
- 60 to 120 seconds

Should show:
- source file input
- selector/review artifact
- final rendered short clip
- short narration of the workflow

This is the most important asset.

### 2. Fast Terminal / Workflow Demo
Filename:
- `selector_workflow_demo.mp4`

Target length:
- 20 to 45 seconds

Should show:
- `select` or `review` command
- generated audit/review files
- quick transition to final outputs

Why:
- shows the project is operational, not just conceptual.

### 3. Before / After Clip Demo
Filename:
- `before_after_vertical_render.mp4`

Target length:
- 15 to 30 seconds

Should show:
- source horizontal scene
- resulting vertical short clip with subtitles

Why:
- this is the easiest way to communicate the value of the system in one glance.

## What To Prioritize First
If you want the minimum useful pack, add these first:
1. `media/screenshots/01_review_sheet_top10.png`
2. `media/screenshots/03_vertical_output_frame.png`
3. `media/screenshots/04_architecture.png`
4. `shorts_foundry_demo.mp4` or an external link to it in `README.md`

## Public-Safe Content Rules
Safe to add:
- diagrams
- review sheets
- manifests
- redacted analytics
- screenshots of final outputs if they do not expose copyrighted source media in a risky way

Do not add:
- copyrighted full source scenes
- raw source episodes
- private code screenshots
- config files, secrets, or internal API details
