# latex-docker-kotex
latex-docker + kotex

A lab-exercise template to build a docker image from `blang/latex:ctanbasic`, adding `kotex` packages.

## Commands
To build docker image
```
docker build -t mylatex .
```
To build pdf
```
./latexdockercmd.sh pdflatex main.tex
```

## Links
- https://github.com/blang/latex-docker
- http://wiki.ktug.org/wiki/wiki.php/ko.TeX
