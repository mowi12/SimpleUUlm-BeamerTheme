# 🌳 SimpleUUlm Beamer Theme

The **SimpleUUlm Beamer Theme** is a minimalist and elegant LaTeX template for academic and scientific presentations at
Ulm University. Inspired by the [🍃 SimplePlus Beamer Theme](https://github.com/pm25/SimplePlus-BeamerTheme), it
emphasizes simplicity, clarity, and a clean presentation style while incorporating the official Ulm University
corporate design.

## Usage

1. Get the four theme files:

   - `beamerthemeSimpleUUlm.sty`
   - `beamercolorthemeSimpleUUlm.sty`
   - `beamerfontthemeSimpleUUlm.sty`
   - `beamerinnerthemeSimpleUUlm.sty`

   Download them from the [latest release](https://github.com/mowi12/SimpleUUlm-BeamerTheme/releases/latest)
   (packaged as a zip), or copy them from this repo. Place them in the same directory as your `.tex` file, or in your
   local TeX tree, e.g. `~/texmf/tex/latex/SimpleUUlm/`.

2. Load the theme in your preamble like any other beamer theme:

   ```latex
   \documentclass[aspectratio=169]{beamer}
   \usetheme[faculty=engineering,progressbar]{SimpleUUlm}
   ```

3. Options:

   - `faculty` sets the accent color: `engineering`, `medicine`, `math`, `science`, or `default`.
   - `progressbar` (optional) adds a progress bar under each frame title.

4. Compile with `pdflatex` (or `latexmk -pdf`). The theme requires the `FiraSans` package, which ships with most TeX
   distributions (e.g. TeX Live).

See [`sample.tex`](./sample.tex) for a full example covering lists, blocks, tables, columns, buttons, and citations —
build it with `latexmk -pdf sample.tex` to see the theme in action.

## License

This project is released under the **Unlicense License**, granting you complete freedom to use, modify, and distribute
the template. For more details, see the [LICENSE](./LICENSE) file.
