# FSE Apps · Version 2

Created: September 20, 2026

## Purpose

This is a self-contained, GitHub Pages-ready version of the FSE Apps launcher. It preserves the original six hosted tools and adds hosted cards for:

- Requirements & Criteria Evaluator
- Problem Framing Challenger

The original `../FSE Apps/` deliverable remains unchanged.

## Main entry file

Open `index.html` through a local web server.

## Source and reference files

- `../FSE Apps/index.html` — visual and interaction reference for this version.
- `assets/fse-ideation-logos.png` — deployable ideation/team icon strip.
- `assets/engineering-app-logos.png` — deployable engineering icon strip.
- `assets/mad-hatter-logo.png` — deployable Mad Hatter logo.
- `assets/problem-framing-challenger-logo.png` — deployable Problem Framing logo.
- `assets/requirements-criteria-evaluator-logo.png` — deployable Requirements & Criteria logo.

## Open locally

Start a static server from this folder. For example:

```powershell
python -m http.server 4173
```

Then open `http://localhost:4173/`.

## Hosting note

Upload both `index.html` and the complete `assets/` folder to the root of the `fse-tools` repository. The relative `assets/...` paths are designed to work locally and at `https://bsundar8-premguru.github.io/fse-tools/`.
