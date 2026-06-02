# VibeWeave — Visual Prompt Composer

**Pick real game art directions. Compose your vibe. Get elite starting prompts.**

Single-file, self-contained tool that helps game developers turn rough ideas into strong, production-grade prompts for Claude, Cursor, etc. — so you get dramatically less slop.

## What it does

- Horizontal scrolling gallery of real game-art references (realistic 3D, stylized 3D, isometric, hand-drawn 2D, modern pixel, atmospheric pixel — all your actual generated images, base64-embedded).
- Drag or tap to add visual directions to "Your Game".
- For each direction, describe the specific game twist in that visual language.
- Live "Emerging Prompt" updates in real time.
- "Weave" produces a dense, craft-heavy master prompt + suggested next prompts + ready-to-use exports.

## How to use

Just open `index.html` (double-click or `open index.html`).

- Scroll or use arrows on the gallery.
- Click or drag cards into the canvas.
- Fill in the "what kind of game..." twist for each.
- Hit **Weave Final Prompt** when ready.

Exports: Copy full prompt, save as CLAUDE.md, or export Cursor rule.

## Design direction

Premium, calm, Apple-grade light experience. The power comes from *what visual directions you combine* and the specific twists you describe. The tool handles the translation into a high-signal prompt.

See `DESIGN.md` for the system.

## Legacy

The previous clean single-input "Apple just shipped a prompting product" version lives in:

`legacy/v1-light-apple/`

## Philosophy

Vibe coders think visually. This tool lets you compose concrete art directions first, then layers your specific game intent on top — resulting in prompts that actually produce intentional, high-feel game design instead of generic slop.

## Current status

Fully working prototype. Images are embedded (no external assets). Ready for iteration on prompt quality, richer inputs, and stronger anti-slop craft.
