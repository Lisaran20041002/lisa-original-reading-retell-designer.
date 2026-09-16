---
name: lisa-original-reading-retell-designer
description: Turn English reading textbook pages or PDFs into illustration-first retell worksheets with source-grounded characters, event art, visual task scaffolds, progressive language support, and handmade storybook styling. Use when the final student worksheet must contain real embedded illustrations rather than text-only plans or placeholders.
metadata:
  short-description: Create Lisa-style retell worksheets
---

# Lisa Original Reading · Retell Designer

Use this skill when the user provides a reading lesson, textbook screenshot, or PDF and wants a retell worksheet, teaching sequence, or related instructional illustrations.

## Non-negotiable operating rules

Run the Teaching Engine and Visual Engine separately, then merge them only after both pass review. Do not output a final worksheet when either review fails.

**Never deliver a text-only worksheet.** A list of sections, student copy, image prompts, layout instructions, empty drawing boxes, icons, colored tables, or decorative shapes does not satisfy the visual requirement. The student-facing deliverable must contain actual, relevant illustrations or drawings embedded in the worksheet.

**Illustrations come before worksheet generation.** Complete source diagnosis, Character Lock, Scene Lock, visual asset planning, image generation, and image inspection before writing or laying out the final worksheet. Do not start the final document/deck/canvas build until the required image files exist locally and have passed Visual QA. If image generation is unavailable or fails, pause and report the blocker; do not silently fall back to a text-only worksheet.

Use a textbook-growth principle: the worksheet should feel as if it grows from the reading. Extract the source-grounded characters, relationships, props, places, event sequence, and emotional change; regenerate them as original teaching illustrations; then use those illustrations to reveal and organize the story from trunk to branches across the retell tasks. Preserve facts, not the textbook's exact composition or copyrighted illustration style.

## Teaching Engine

1. Inspect the source and preserve only facts supported by the original text/images.
2. Diagnose audience, language load, narrative structure, key characters, setting, conflict/change, and teachable vocabulary.
3. Convert the narrative into `understanding → selecting → organizing → expressing`.
4. Select task modules from the text rather than filling a fixed template. Prefer a progression such as big picture, character/setting noticing, key-event selection, sequencing, change/meaning, supported retell, less-supported retell, and final independent retell.
5. Reuse the source language wherever it helps learners. Keep cognition medium and language load medium-low unless the user specifies otherwise.
6. Remove support gradually: modeled recognition → choices/frames → ordered prompts → keywords → independent oral output.

## Visual Engine

Before any illustration prompt, create a Character Lock and Scene Lock. Record stable appearance, identity markers, relationships, setting, recurring props, and facts that must not change. When the source provides clear visual evidence, derive these locks from the textbook characters and setting instead of inventing generic children.

Create a Visual Asset Map that connects each planned task to a specific visual function. The minimum asset family is:

- one portrait or recognizable visual for every core character;
- four to six independent event illustrations covering the retell spine;
- three or more prop, location, or relationship spot illustrations when those details support vocabulary or comprehension;
- one deliberately selected distractor image when the worksheet includes event selection.

Short texts may reuse a generated event illustration in sequencing and less-supported retell, but do not let one contact sheet or four repeated pictures carry the entire worksheet. Generate enough distinct art that visual evidence participates throughout the learning sequence.

Generate and inspect the complete asset family before composing the worksheet. Re-stage the teaching meaning; never redraw a textbook panel literally or use a screenshot as the worksheet illustration. Each generated file must be saved into the project or deliverable workspace before it is embedded.

Direct the visual style as: soft watercolor-and-colored-pencil storybook illustration, visible dry-brush texture, uneven pigment, matte printed-paper finish, hand-drawn imperfect outlines, warm ivory paper, muted dusty pastel palette, restrained terracotta/sage/powder-blue/faded-mustard/blush accents, rich-but-not-neon characters, and generous natural whitespace.

Let the learning action determine the visual form. Do not place every task in identical rounded cards or a symmetrical grid. Use collage paper, tape, brush marks, hand-drawn arrows, labels, plants, fences, and small props locally and purposefully.

Use three text layers: storybook display lettering for the main title, clean handwritten worksheet text for task headings/body, and loose annotation handwriting for prompts and notes.

## Visual integration gate

Before final layout, verify all of the following:

1. Actual image files exist for the Character Lock, key events, and supporting props/places.
2. Each image has been visually inspected for factual accuracy, character consistency, cropping safety, and classroom readability.
3. Every major learning phase uses visual evidence: understand, select, organize, and express.
4. Illustrations are placed inside the tasks, not collected as a decorative gallery detached from the questions.
5. The page has visual rhythm comparable to a richly illustrated children's worksheet: characters, event cards, sequencing pictures, and small spot art are distributed intentionally.

If any check fails, return to image generation or visual editing before document generation.

## Worksheet assembly

Only after the visual integration gate passes, write the final student copy and assemble the worksheet around the approved assets. Let the images determine task scale, grouping, and page breaks. Do not design a text-heavy worksheet first and retrofit a few pictures afterward.

For ordinary narrative lessons, aim for these visualized task types when supported by the source: big-picture comprehension with a scene, character matching with portraits, key-event selection with illustrated cards, picture sequencing, illustrated language/prop noticing, supported retell with images and sentence frames, less-supported retell with a picture strip, and independent retell with a visual story map.

## Forbidden visual direction

`flat vector illustration, corporate infographic, Canva worksheet template, glossy 3D cartoon, Pixar-like rendering, neon colors, rainbow gradient, glassmorphism, UI cards, perfectly symmetrical grid, identical rounded rectangles, stock education icons, generic smiling children, robot/AI imagery, overly clean digital lines, sterile white background, excessive decorations, random stickers, unrelated characters, photorealistic images, textbook screenshots used as worksheet illustrations`

## Required output package for a worksheet task

The primary deliverable is a finished, visually verified student worksheet file with the generated illustrations embedded. When requested or useful, also provide a teacher/answer version. Keep source diagnosis, locks, asset map, prompts, and QA as production records or a concise handoff summary; never substitute them for the illustrated worksheet itself. If source quality is insufficient, stop and ask for a clearer source instead of inventing content.

## Failure lessons incorporated

- A pedagogically sound outline is not a worksheet when it contains no actual artwork.
- Empty drawing boxes, colored tables, and layout styling are not substitutes for illustrations.
- Adding four pictures after a text-first layout produces low visual density and weak integration.
- Reusing one image set everywhere makes tasks feel repetitive; portraits, event scenes, props, locations, and distractors serve different teaching purposes.
- Late image insertion causes oversized pages, awkward whitespace, and forced compression. Generate and inspect the asset system first so page architecture grows around it.
- Visual QA must evaluate quantity, distribution, instructional function, consistency, and print readability, not only whether an image exists.

Read the supporting files as needed:

- [SOP.md](SOP.md) for the complete production procedure.
- [WORKFLOW.md](WORKFLOW.md) for AI/Lisa ownership and handoffs.
- [references/visual-rules.md](references/visual-rules.md) for detailed visual constraints.
- [references/locks-and-checklists.md](references/locks-and-checklists.md) for lock schemas and QA checklists.
- [assets/REFERENCE_INDEX.md](assets/REFERENCE_INDEX.md) for the local source-material map.

