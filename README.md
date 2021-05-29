LaTeX template for theses at University of Aveiro.
Check the guidelines for [master](https://www.ua.pt/en/sga/page/12810) and [PhD](https://www.ua.pt/en/sga/page/4630) theses.


### LaTeX document generation

You can generate the PDF output file with [latexmk](https://ctan.org/pkg/latexmk) using the following command. Note that, by default, [LuaTeX](https://en.wikipedia.org/wiki/LuaTeX) is used over [pdfTeX](https://en.wikipedia.org/wiki/PdfTeX).

```
$ latexmk -lualatex main.tex
```

Alternatively, you can use [TeXstudio](https://www.texstudio.org/), [Texmaker](https://www.xm1math.net/texmaker/), [Overleaf](https://www.overleaf.com/), [Visual Studio Code](https://code.visualstudio.com/) with [LaTeX Workshop](https://marketplace.visualstudio.com/items?itemName=James-Yu.latex-workshop), or [any other LaTeX IDE](https://tex.stackexchange.com/questions/339/latex-editors-ides).


### Why LuaTeX?

If you are curious why I prefer to use LuaTeX, I encourage you to check these articles:

- [The TeX family tree: LaTeX, pdfTeX, XeTeX, LuaTeX and ConTeXt](https://www.overleaf.com/learn/latex/Articles/The_TeX_family_tree:_LaTeX,_pdfTeX,_XeTeX,_LuaTeX_and_ConTeXt)

- [Are there benefits to use XeTeX or LuaTeX if one is to write documents mainly in English?](https://tex.stackexchange.com/questions/548467/are-there-benefits-to-use-xetex-or-luatex-if-one-is-to-write-documents-mainly-in)

- [Why choose LuaLaTeX over XeLaTeX](https://tex.stackexchange.com/questions/126206/why-choose-lualatex-over-xelatex)

- [Differences between LuaTeX, ConTeXt and XeTeX](https://tex.stackexchange.com/questions/36/differences-between-luatex-context-and-xetex)


### Authors

This code is maintained by me, [Rui Antunes](https://ruiantunes.ai/).
It is based on the original [LaTeX template created by Tomás Oliveira e Silva](http://sweet.ua.pt/tos/TeX.html).

Similar works include the ones by [João Paulo Barraca _et al_.](http://code.ua.pt/projects/latex-ua/repository) and [Fábio Maia _et al_.](https://github.com/detiuaveiro/ua-thesis-template)


### Repository

[https://github.com/ruiantunes/ua-thesis-template](https://github.com/ruiantunes/ua-thesis-template)
