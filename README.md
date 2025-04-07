# This is my resume in latex

Based on [AltaCV](https://www.overleaf.com/latex/templates/altacv-template/trgqjpwnmtgv) template, inspired by [ylorenzati's](https://github.com/ylorenzati/resume) work.


Using [MiKteX](https://miktex.org) compiler is recommended to build it. Once ready, just use:
```bash
$ pdflatex main.tex
```


To convert it to HTML using pdf2htmlEX container:
```bash
docker run -ti --rm -v `pwd`:/pdf bwits/pdf2htmlex pdf2htmlEX --zoom 1.4 main.pdf resume.htm
```

Online publication is done automatically thanks to Github Pages (index.htm being the entry point).

