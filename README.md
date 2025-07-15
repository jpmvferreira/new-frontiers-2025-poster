To make this document:
```console
$ latexmk -f -shell-escape -lualatex -aux-directory=aux main.tex
```

To clean the auxiliary files:
```console
$ rm -rf aux/* svg-inkscape/*
```

The rendered version of this document is avaialble in [main.pdf](./main.pdf).

This poster is based on a modification of [andiac/gemini-cam](https://github.com/andiac/gemini-cam), which is itself a fork of [anishathalye/gemini](https://github.com/anishathalye/gemini). I also drew inspiration from [k4rtik/uchicago-poster](https://github.com/k4rtik/uchicago-poster), another fork of the gemini template.

Instead of using my version of this template I recommend you to use the original gemini template, since I wasn't very cautious to document the changes. If you see something that isn't available in the original template, feel free to open an issue.

This repository is MIT licensed.
