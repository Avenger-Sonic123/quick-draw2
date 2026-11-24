# Quick Draw — Canvas and Timer

An intermediate sketch-game prototype focused on canvas setup and game state.

**Repository created:** 2022-06-14  
**Project status:** Learning project / historical snapshot  
**Earliest recorded commit (author date):** 2022-06-14

## Features and implementation

- Random sketch prompt.
- P5.js drawing canvas.
- Score and timer scaffolding.
- Canvas reset helper.

## Technologies

HTML, CSS, JavaScript, Bootstrap, jQuery, p5.js, ml5.js.

## Project structure

| File | Purpose |
| --- | --- |
| [`C118_predefined_code.css`](C118_predefined_code.css) | Sketch-game styles |
| [`index.html`](index.html) | Main page and user interface |
| [`main.js`](main.js) | Project-specific JavaScript |

Key functions in the source:
- `main.js`: `check_sketch()`, `updateCanvas()`.

## Run or explore locally

```bash
git clone https://github.com/Avenger-Sonic123/quick-draw2.git
cd quick-draw2
python -m http.server 8000
```

Open [http://localhost:8000](http://localhost:8000) in your browser. The local server requires Python 3; browser-based dependencies may also require internet access.

Open the prototype and inspect the canvas and prompt.

## Current status and limitations

No classifier or mouse drawing implementation is included; the timer logic is not a complete timed game.

## Related project snapshots

Other repositories in this project family:
- [quick-draw1](https://github.com/Avenger-Sonic123/quick-draw1) — repository created 2022-06-13
- [quick-draw3](https://github.com/Avenger-Sonic123/quick-draw3) — repository created 2022-07-17

---

Source reference: [`64521cd9`](https://github.com/Avenger-Sonic123/quick-draw2/tree/64521cd9ce354404ba3af97863daec70ec5e40ab) on `main`, verified against GitHub on 2026-11-24. Documentation is based on static source review; runtime behavior has not been tested.
