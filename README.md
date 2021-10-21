# Latex Thesis Template

![Github All Releases](https://img.shields.io/github/downloads/josetv91/Latex-thesis-format/total?logo=GitHub&style=plastic)
![GitHub repo size](https://img.shields.io/github/repo-size/josetv91/Latex-thesis-format)
![GitHub language count](https://img.shields.io/github/languages/count/josetv91/Latex-thesis-format?color=success&logo=CodersRank&logoColor=%23FFFFFF)
[![version](https://img.shields.io/badge/version-1.1-red.svg)](//npmjs.com/package/Latex-thesis-format)

## Requirements
---
Install the following requirements, with at least the said versions:

* [TEXstudio 4.0.0](https://www.texstudio.org/): Download & install it
* [MiKTeX 21.8-x64](https://miktex.org/download): Download & install it
* [Tex Live 20210325](https://ctan.dcc.uchile.cl/systems/texlive/Images/): Download the iso, unrar it and run the install-tl-windows.bat file (takes hours to install all the packages!)

## Set up your texstudio PDF compiler
---
Open the TEXstudio you just downloaded, navigate to `Options>Configure TEXstudio` and enable the `Show Advanced Options` checkbox, located in the left bottom side of the window. Now in the left side of the panel, go to `Build` and configure `Default Compiler` as `txs:///xelatex`. If you choose `txs:///pdflatex`, some packages might not work. 

Before compiling a first test, navigate to [`main.tex`](./main.tex) and comment the chapters that are not yet provided in this repo, like the line:
```TEX
250  %\include{METODOLOGÍA} 
```
This is because the file: `metodologia.tex` doesn't exist yet, although you can create it. Do the same with chapters that have the tag: `\include{something}` that are not present in the repo files.

* You may want to comment chapters when redacting your thesis to speed up the compilation process.


Finally proceed to compile a first test, during compilation if you are prompted with a request to install another package, just accept it and move forward. Might be the case that you will be prompted with the package installation message more than once in the first compilation, just accept all of them, TEXstudio will download them automatically and you just need to confirm all the requests.

## How to use

- Fill your personal information in the [`cover.tex`](./cover.tex) file.
- Begin with the chapter I: [`introducción.tex`](./introducción.tex)
- Continue with the chapter II: [`Marco_Teórico.tex`](./Marco_Teórico.tex)
- Chapter III: Metodología
- Chapter IV: Cálculos y/o aplicaciones y obtención de resultados
- Chapter V: Conclusiones, navigate to [`main.tex`](./main.tex) and add your conclusions from the the line `255` onwards with items.
- Recomendaciones: [`main.tex`](./main.tex)
- Referencias: To be updated
- Anexos: To be updated
---

## Author's Info

- Email: [jose_antoniotv@hotmail.com](jose_antoniotv@hotmail.com)

[//]: # "Comment this line() - Websie - [some](some@pe) "
