# Harmonic Lines

A browser tool for drawing animated mathematical curves (Lissajous figures, harmonographs, roses, spirographs and wave bundles) with optional pixel-block "weathering", in a custom purple / indigo / orange / stone palette.

Everything runs in a single `index.html`: Canvas 2D draws the curves, WebGL2 applies the block, smear and grain effects. There are no dependencies and no build step.

## Features

- **Curves:** five families, each driven by two frequencies, a phase and a modulation amount; the phase drifts so shapes keep morphing.
- **Chart grid:** rows step through frequency ratios (1:1 → 5:6), columns sweep the phase.
- **Lines:** nested, phase-shifted or offset copies of each curve.
- **Color:** a 36-swatch palette, seven preset color schemes, and solid / per-line / flowing-dash / gradient coloring.
- **Weathering:** pixel blocks that ease in and out, a Line / Both / Blocks-only view, smear, temporal smoothing, grain, paper tooth, trails and stop-motion.
- **Export:** PNG at up to 4× scale; video as WebM (VP9 or VP8) or MP4, up to 3840 px on the long side.

## Run locally

Open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8000
```

Then visit http://localhost:8000.

**Shortcuts:** `space` pauses, `r` randomizes.
