# VibeWeave Design System — Visual Composer Edition

**Current direction**: Ambitious visual + drag-and-drop prompt composition using real 3D game references.

The core experience is now:
- A stunning gallery of 3D (Three.js) game archetypes and mechanics.
- A central composition canvas where references are dragged.
- Live intelligent prompt formation as the user builds their combination.
- One confident "Weave" action that turns the visual composition into a production-ready master prompt.

## Aesthetic Foundation
Still rooted in the premium light Apple-grade direction:
- Warm off-white background
- Generous whitespace
- Refined typography
- Purposeful, restrained motion
- Extremely high craft and attention to micro-details

## Key Experience Shifts (from previous versions)
- From "describe + tune" → "see + compose"
- The 3D gallery is now the primary way users express intent.
- The prompt is no longer written from a form — it emerges from the visual combination the user creates.
- This is much closer to how great game designers actually think.

## Technical Notes
- Single-file experience (Three.js loaded via esm.sh importmap).
- All 3D scenes are lightweight, evocative, and loop beautifully.
- Drag-and-drop is native + enhanced with click-to-add fallback.
- Live prompt preview updates intelligently based on selected references.

## Current State (as of latest shipping)
- Image-based horizontal gallery with 6 real embedded user game-art references (base64, no external files).
- Composition via drag/click + per-visual twists.
- Rich inputs: Core Fantasy, Key Mechanics, free-text "steal/avoid/mechanics ideas" (editable chips).
- Loadable high-quality examples + localStorage custom presets + URL hash sharing for exact vibes.
- Target selector (Godot/Unity/Unreal/General) that tailors the output kit.
- Weave produces full **Starter Prompt Kit**: Main Prompt + Project Rule + Follow-up Prompts, with dedicated copies and 3-file download.
- Live "Emerging Prompt" + real-time slop risk indicator to guide better inputs.
- Chips show twists; click to re-edit.

## Future Refinement Opportunities
- Structured mechanics builder (cards instead of pure text for systems).
- Prompt variations on the fly ("more juice", "stricter scope").
- Richer live spec editor (editable sections instead of derived text).
- Even more built-in examples + community preset import (JSON).
- Engine-specific deeper tailoring and code-gen hints in follow-ups.
- Onboarding tour and "why this fights slop" inline explanations.
- Mobile-first gallery improvements (better swipe, vertical fallback).

This direction is deliberately more ambitious than the previous minimal version because it directly addresses what vibe coders repeatedly ask for: a way to work visually and spatially with game feel references instead of purely through text, while injecting real craft and anti-slop discipline into the resulting prompts.

Every interaction should feel delightful, intentional, and like real creative work is happening.