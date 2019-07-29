# blue-bookdown-latex-theme
A blue latex theme compatible with R bookdown

## Usage:
In the `_output.yaml` file of your bookdown project folder, make sure to include **template: pdfbook_template**, as shown below:

```
bookdown::pdf_book:
  includes:
    in_header: preamble.tex
  latex_engine: xelatex
  keep_tex: true
  toc: true
  toc_depth: 3
  template: pdfbook_template.tex
```

Derived from The Legrand Orange Book, which can be found here:
https://www.latextemplates.com/template/the-legrand-orange-book

Photos courtesy of https://www.pexels.com/
