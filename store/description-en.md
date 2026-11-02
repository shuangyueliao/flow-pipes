# Flow Pipes — Store Submission Materials

## Short description (CrazyGames / GameDistribution / itch.io)

Drag between matching dots to draw glowing pipes and connect every pair.
Cover the whole grid for a perfect star. 30 relaxing levels, one-tap
hints, no timers, no pressure.

## Details

- Genre: Puzzle / Casual / Brain
- Controls: Mouse / Touch — drag from one dot to its twin to draw a pipe.
  Drag over an old pipe to redraw or overwrite it. Keyboard: H hint,
  R reset, Esc level select.
- Features: 30 procedurally generated levels (5×5 → 9×9, 2–8 color pairs,
  each generator-verified to contain a full-board solution), hint item
  (1 per level), perfect star per level, level select with progress saved
  locally, completing pipes get a flowing light effect, procedural
  graphics & WebAudio scale-note sounds, single-file HTML5 (no external
  assets), works offline once loaded.
- Tech: Vanilla JavaScript, Canvas, WebAudio. No frameworks, no tracking.

## Tags
flow, pipes, connect, puzzle, casual, brain, logic, single-file

## CrazyGames submission checklist
- [x] Self-contained index.html (SDK loads only on crazygames domains)
- [x] gameplayStart / gameplayStop / loadingStart / loadingStop / happytime events wired
- [x] Responsive (square canvas scales to viewport, portrait-friendly)
- [x] No external links inside gameplay, no analytics
- [ ] Cover image (16:9) — to be captured from gameplay
- [ ] Screenshots — to be captured from gameplay

## itch.io
- Upload flow-pipes-itch.zip, mark "This file is playable in browser",
  entry file: index.html, viewport 480×480 (square), kind: html
- Pricing: $0 (donations optional)

## GameDistribution
- Upload flow-pipes-gd.zip (index.html only). The GD SDK auto-loads on
  gamedistribution / gd.games domains and is dormant everywhere else.
