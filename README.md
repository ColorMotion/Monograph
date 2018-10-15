## Compilation

Running `latexmk -pdf` in this folder will generate `main.pdf`. Some useful development flags are `latexmk -pv` (preview) and `latexmk -pvc` (live preview).

`latexmk -pvc -view=none -pdf -pdflatex="pdflatex -synctex=1 -interaction=nonstopmode"` continuosly regenerates a PDF whenever the input file is changed, with SyncTeX enabled.
