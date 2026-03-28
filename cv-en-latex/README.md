# CV (English) — LaTeX layout

French version: see `../cv-fr-latex/` (same structure, translated `sections/*.tex`).

Structured LaTeX project: `main.tex` loads `preamble.tex` and section files under `sections/`.

## Requirements

- TeX Live (or equivalent) with **XeLaTeX** and `fontspec` (Fira Sans optional; falls back to DejaVu Sans in `preamble.tex` if missing).
- Document class **`extarticle`** at **9pt** (from the `extsizes` bundle, usually in `texlive-latex-recommended`). If `extarticle` is missing, change `main.tex` to `\documentclass[10pt,a4paper]{article}` and add `\AtBeginDocument{\small}` after `\begin{document}` for a smaller look.
- Photo path: `../photo/face_circle.png` relative to this folder (repository root contains `photo/`).

## Build

From `cv-en-latex/`:

```bash
xelatex -interaction=nonstopmode main.tex
```

Output: `main.pdf` in the same directory.

## Layout conventions

- **Order:** `00_header` → `10_summary` → `40_experience` → `20_certifications` → `30_education`.
- **Content** lives in `sections/*.tex` (easy to diff in Git).
- **Style and macros** live in `preamble.tex`.
- **Do not** edit generated files (`main.aux`, `main.log`, `main.out`, `main.pdf`) by hand.

## Optional: ignore build artifacts

Add to your repo `.gitignore` (if desired): `*.aux`, `*.log`, `*.out`, `*.pdf` under this folder.
