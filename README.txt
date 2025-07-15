To make this document:
$ latexmk -f -shell-escape -lualatex -aux-directory=aux main.tex

To clean the auxiliary files:
$ rm -rf aux/* svg-inkscape/*

This poster is based on a modification of [andiac/gemini-cam](https://github.com/andiac/gemini-cam), which is itself a fork of [anishathalye/gemini](https://github.com/anishathalye/gemini). I also drew inspiration from [k4rtik/uchicago-poster](https://github.com/k4rtik/uchicago-poster), another fork of the gemini template.

If you are interested in using this template, I recommend you to use the original gemini template and add the missing features there, as I wasn't very cautious to document the changes I made on this template.

This repository is MIT licensed.
