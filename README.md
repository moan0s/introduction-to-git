# Introduction to git
A very limited introduction to the usage of git

## Creating PDFs from source
Everything in this repo is written in markdown. If you want to have a PDF (which you can print
out) you can install [pandoc](https://pandoc.org/) (`sudo apt install pandoc`) and execute 
```bash
$ pandoc introduction_to_git.md --toc -o print_introduction_to_git.pdf
```
