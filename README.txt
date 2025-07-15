To make this document:
$ latexmk -f -shell-escape -lualatex -aux-directory=aux main.tex

To clean the auxiliary files:
$ rm -rf aux/* svg-inkscape/*
