# Contributing to the projet

Every commit that includes a change to the .tex file must also include the compiled PDF

## How to compile a .tex file into a PDF 

### VSCode

Install the [LaTeX Workshop](https://open-vsx.org/vscode/item?itemName=James-Yu.latex-workshop) extension. It compiles the `.tex` file automatically on save and outputs the PDF alongside it. No extra setup needed.

### Other editors / command line

Make sure you have `latexmk` installed (included in most TeX distributions like TeX Live or MiKTeX), then run:

```sh
latexmk -pdf "Research Paper: USA-China Rivalry Over Superintelligence.tex"
```

This outputs the PDF in the same directory as the `.tex` file.