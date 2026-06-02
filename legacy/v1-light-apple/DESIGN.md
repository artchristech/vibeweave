# VibeWeave Design System — Apple 10/10 Light Edition

**Direction**: Apple just shipped a premium prompting product for serious game creators. Calm. Confident. Almost no visible UI friction. The experience feels magical, seamless, and deeply respectful of the user's creative intent. Light theme only. Purposeful motion. Ruthless reduction of controls. Onboarding and flow feel like a native high-end creative tool.

**Status**: Active direction for the next production artifact. Previous dark "workbench" metaphor retired for V1.

## Core Metaphor
A quiet, beautiful creative canvas. You arrive, the tool welcomes you with clarity and taste. You describe your game idea. You optionally tune with minimal, elegant gestures. You press one primary action ("Weave") and something exceptional is crafted for you. The result feels like receiving a precious, well-made artifact.

No "bench full of dials." Power is present but never loud.

## Typography (Apple-grade refinement)
- **Display / Major Headlines**: Refined system display or a light, confident sans with excellent character (e.g., SF Pro Display or equivalent via system-ui with optical sizing). Large sizes (48–72px), generous tracking when appropriate, excellent weight range.
- **Body / Reading**: -apple-system, BlinkMacSystemFont, "Segoe UI", system-ui. 17–19px for primary reading. Warm, highly legible, generous line-height.
- **Mono / Prompts / Code**: SF Mono or "SF Mono", Menlo, ui-monospace. Slightly condensed, excellent in light backgrounds. Used for the final prompt presentation.
- Never Inter as hero. Avoid overly decorative serifs for this product.

## Palette — Light, Warm, Premium
- Background: Soft warm off-white `#f9f7f2` or `#faf8f3`
- Surface / Cards: `#ffffff` with subtle, realistic shadows (multiple layers for depth)
- Elevated surfaces: Slightly warmer or cooler tints with very soft shadows
- Text:
  - Primary: `#1c1c1e` (near black, warm)
  - Secondary: `#3c3c43` (60% opacity equivalent)
  - Tertiary: `#8e8e93`
- Accent (primary action / "Weave" moments): Refined warm blue `#0071e3` or a very tasteful deep indigo. Used extremely sparingly.
- Subtle gold or warm neutral for moments of "craft" if needed, but keep minimal.
- Borders / Dividers: Very subtle `#e5e5e7` or lighter.

The overall feeling should be "expensive paper in perfect light" rather than screen-y.

## Materials & Depth
- Paper-like surfaces with soft, believable shadows (not heavy drop shadows).
- Subtle texture only where it adds tactility (very light grain on main canvas if it serves the metaphor).
- Focus states and hovers are gentle, confident, never flashy.
- The "result" presentation should feel like a beautifully typeset document or a premium note.

## Motion Language (Purposeful, Apple-like)
- All transitions are 280–420ms with refined easing (cubic-bezier that feels natural, like Apple’s).
- Input focus: Soft scale + very subtle shadow lift + border accent.
- Weave action: On press, the button has a confident press state. During processing: elegant, meaningful shimmer or a subtle "thinking" animation that communicates quality (not a spinner).
- Result reveal: Gentle fade + soft upward lift of the content container. Feels like something valuable is being presented to you.
- Control reveal (when user wants more power): Smooth fade + slight scale from a compact state. Never jarring.
- Copy / export confirmations: Subtle, satisfying check or "Copied" that fades elegantly.
- No bouncy springs unless they communicate something physical (e.g., the idea "settling" into the weave).

Respect `prefers-reduced-motion`.

## Experience Principles (Seamless, Onboarding Feel, Less Buttons)
- **First 3 seconds**: User lands on a calm, beautiful, almost minimal screen with a large, inviting idea input as the hero. 3–4 gorgeous, tappable inspiration examples that feel like Apple product cards.
- **Progressive disclosure**: Advanced controls (the dials, references, etc.) are not visible by default. They live behind a single elegant "Tune" or "Craft details" affordance that expands a minimal, beautiful panel. Most users should get excellent results without ever opening it.
- **Primary action**: One confident, large "Weave" button. Everything leads to this moment.
- **Result state**: The prompt is presented cleanly and beautifully. Export actions are obvious but refined (large, clear, native-feeling). The experience of "I got something great" is the emotional peak.
- **Fewer visible elements**: Aim for dramatically lower visual density than the previous prototype. Every control must earn its presence.

## Key Screens / Moments

1. **Onboarding / Creation Canvas** (primary)
   - Large centered or well-composed headline: something like "Describe the game you want to make."
   - Generous, beautiful text input (multi-line, excellent focus treatment).
   - 3–4 elegant inspiration cards below or to the side.
   - One primary "Weave" button.
   - Very subtle "Tune the weave" link or pill that reveals advanced controls.

2. **Processing / Weaving**
   - Elegant, calm loading state. The interface gently dims or the input area transforms subtly. A meaningful animation communicates that sophisticated work is happening.

3. **Result / Artifact View**
   - Smooth transition into a clean, focused presentation of the generated prompt.
   - The prompt text is in a beautiful, readable container (excellent typography, comfortable line length).
   - Export cluster is prominent but tasteful: large "Copy prompt", "Use in Cursor", "Save as CLAUDE.md", etc.
   - Option to "Weave again" or "Adjust" that feels natural.

4. **Advanced Controls** (when revealed)
   - Minimal, elegant, grouped logically.
   - Live preview of how changes affect the weave (if possible) without cluttering the main flow.

## Anti-Patterns (Hard — Apple 10/10 Edition)
- No dark theme for this direction (light only).
- No dense control panels visible by default.
- No "bench" or "instrument" visual language that feels technical and heavy.
- No excessive buttons or chips.
- No purple gradients or "AI" visual clichés.
- No generic card grids.
- Motion is never decorative — it always communicates state or hierarchy.
- Text is never placeholder or low-effort.

## Implementation Notes for the Single-File Artifact
- Still a high-quality, self-contained `index.html`.
- Excellent CSS custom properties for the new light tokens.
- Smooth, performant animations (CSS transitions + small JS where needed).
- The synthesis intelligence (the prompt crafting logic) remains excellent or improves.
- The final artifact must feel like it cost real craft — every detail considered.

## Next
- Visual references generated (Apple-grade light mockups).
- Complete rewrite of the single-file experience following this system.
- Rigorous refinement until it feels like Apple shipped it.

This direction is a deliberate, confident pivot from the previous powerful-but-dense dark instrument. The new VibeWeave should feel like the obvious, premium way sophisticated game creators start their AI-assisted projects.