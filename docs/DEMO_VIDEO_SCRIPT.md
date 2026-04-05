# Demo Video Script

Target length: 1 to 3 minutes.

## 1. Opening: 10-15 seconds
Show the problem:
- long-form source file;
- manual highlight extraction is slow;
- subtitle/crop/render work is repetitive.

Suggested line:
> This system turns long-form episodes into ranked short-form candidates and vertical-ready clips, with review artifacts for final editorial choice.

## 2. Inputs: 10-15 seconds
Show:
- one source video file;
- one selection manifest or review sheet;
- one final rendered short.

Do not show private source code.

## 3. Workflow: 25-40 seconds
Narrate the flow:
- scene detection and transcript pass;
- candidate generation;
- selector and rerank;
- review pack export;
- vertical render with subtitles and smart crop.

Suggested line:
> The key decision here is that the system does not blindly trust a single score. It creates a strong shortlist, then supports review and finalization.

## 4. Architecture: 15-20 seconds
Show a simplified diagram from `ARCHITECTURE.md`.

Suggested line:
> The project is built as a staged orchestration pipeline: media analysis, ranking, review artifacts, and final rendering.

## 5. Results: 20-30 seconds
Show:
- a review sheet;
- a selection manifest;
- one or two rendered vertical outputs.

Suggested line:
> The strongest part of the system today is not just rendering clips. It is producing a repeatable shortlist that is much faster to finalize than manual scanning of full episodes.

## 6. Closing: 10 seconds
Suggested line:
> The codebase is private, but the architecture, workflow, and product tradeoffs are documented here. I can walk through implementation details in an interview.
