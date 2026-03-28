# CV (English) — LaTeX layout

Structured LaTeX project: `main.tex` loads `preamble.tex` and section files under `sections/`.

## Requirements

- TeX Live (or equivalent) with **XeLaTeX** and `fontspec` (Fira Sans optional; falls back to DejaVu Sans in `preamble.tex` if missing).
- Photo path: `../photo/face_circle.png` relative to this folder (repository root contains `photo/`).

## Build

From `cv-en-latex/`:

```bash
xelatex -interaction=nonstopmode main.tex
```

Output: `main.pdf` in the same directory.

## Layout conventions

- **Content** lives in `sections/*.tex` (easy to diff in Git).
- **Style and macros** live in `preamble.tex`.
- **Do not** edit generated files (`main.aux`, `main.log`, `main.out`, `main.pdf`) by hand.

## Optional: ignore build artifacts

Add to your repo `.gitignore` (if desired): `*.aux`, `*.log`, `*.out`, `*.pdf` under this folder.
