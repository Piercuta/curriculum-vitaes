# CV (français) — LaTeX

Même mise en forme que `../cv-en-latex/` : couleurs, séparateurs entre expériences, 9 pt, `extarticle`.

## Compiler

```bash
cd cv-fr-latex
xelatex -interaction=nonstopmode main.tex
```

→ `main.pdf`

## Contenu

Les textes sont dans `sections/*.tex`. Pour **mettre à jour** le CV FR : éditer ces fichiers (pas besoin de tout recoller depuis le PDF).

## Version anglaise

Voir le dossier `../cv-en-latex/` : même structure, autres fichiers `sections/`.

## Babel (optionnel)

Si `texlive-lang-french` (ou équivalent) est installé, vous pouvez ajouter dans `preamble.tex` après `fontspec` :

```latex
\usepackage[french]{babel}
```

pour la typographie française (espaces devant `:` `;` `!`). Sans ce paquet, XeLaTeX avec UTF-8 suffit pour les accents.
