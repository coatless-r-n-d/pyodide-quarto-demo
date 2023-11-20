# pyodide-quarto-demo

Experiments with generating a standalone [Quarto Document](https://quarto.org/) powered by [Pyodide](https://pyodide.org/en/stable/) for Interactive [Python](https://www.python.org/) right in the web browser.

You can see a live version of the [proof of concept (PoC) document](https://rd.thecoatlessprofessor.com/webR-quarto-demos/webr-quarto-html-demo.html) and its [source](pyodide-quarto-html-demo.qmd).

**Note:** The PoC does lack the ability to handle graphical output.

You can create Pyodide-powered Quarto code cells using the [`quarto-pyodide`](https://github.com/coatless-quarto/pyodide) extension: 

<https://github.com/coatless-quarto/pyodide>

## Background

Pyodide was created in [2018 by Michael Droettboom](https://pyodide.org/en/stable/project/about.html#history) during his time at Mozilla as part of
the [iodide](https://github.com/iodide-project/iodide) project. 

> Pyodide is a Python distribution for the browser ... 
> .. Pyodide makes it possible to install and run Python packages in the browser ...

## Acknowledgements

This repository leans _heavily_ on:

- [Pyodide: Getting Started](https://pyodide.org/en/stable/usage/quickstart.html)

As well as the prior [webR PoC document](https://github.com/coatless-r-n-d/webR-quarto-demos) alongside of the webR developers public-facing examples:

- [Source of Tidyverse Blog Post](https://github.com/tidyverse/tidyverse.org/pull/617/files) and [Minor fix](https://github.com/tidyverse/tidyverse.org/commit/72bb2dd7ca0b2f211498a891aa54f55ddcad5014)
- [webR documentation landing page](https://github.com/r-wasm/webr/blob/53acd8861c44f1f167941d0a40f62b0cc23852da/src/docs/index.qmd#L23-L68) ([Live page](https://docs.r-wasm.org/webr/latest/))
