# Vývoj aplikací s Backbone.js

## O knize

This is the home of [Developing Backbone.js Applications](http://shop.oreilly.com/product/0636920025344.do), an open-source book about the Backbone.js library for structuring JavaScript applications. It is released under a 
Creative Commons Attribution-Noncommercial-No Derivative Works 3.0 United States License and is currently available for early purchase via O'Reilly if you would like to support the project.

## Přispívání

Oceňujeme veškeré snahy o zlepšení knihy. Vezměte prosím na vědomí, že úložiště je strukturováno následovně:

* chapters - kapitoly - obsahuje značku zdroje pro každou kapitolu. To je kompilováno do HTML, ePub, Mobi a dalších formátů nalezených v kořenovém adresáři projektu.
* build - šablony a metadata pro sestavení knihy
* img - obrazové prostředky pro projekt
* practicals - cvičení - obsahuje zdrojový kód pro cvičení

If you would like to submit pull requests, please feel free to apply them against the relevant markdown file in `chapter`. These can be previewed by running the build script via `make`, which will also generate updated versions of the other formats we support. Please ensure that you are only submitting the modified chapter file for your changes and not the compiled HTML/other format binaries. 

## Recenze

Máte-li zájem o zanechání recenze, abyste s ostatními sdíleli svůj názor na knihu (je to vždycky oceňováno!), Můžete to udělat prostřednictvím [O'Reilly](http://shop.oreilly.com/product/0636920025344/ReviewSubmit.do?sortby=publicationDate?pageId=0636920025344.IP).

## Budování

Knihu můžete vytvořit pomocí značky make nebo make -f Makefile. Výsledkem bude verze HTML, ePub, Mobi, PDF a RTF knihy.

Note: At this time, generating all of the above formats should be straight-forward with the exception of the PDF. We have an open [pull-request](https://github.com/addyosmani/backbone-fundamentals/pull/369) for `xelatex` which is being considered and better guides for working around cross-platform PDF issues will be supplied as time allows.

### Závislosti

* Make
* [Pandoc](https://github.com/jgm/pandoc)
* pdflatex (and recommended latex fonts)

#### Distribuce pro Linux Debian:

<code>apt-get install pandoc texlive-latex-base texlive-fonts-recommended cm-super etoolbox</code>
