SHELL:=bash

.PHONY : all

all : pdf

pdf : main.pdf

main.pdf : 
	latexmk -C && latexmk -xelatex main.tex
	latexmk -C && latexmk -xelatex main.tex
	latexmk -C && latexmk -xelatex main.tex

clean :
	latexmk -C

.DELETE_ON_ERROR:

.SECONDARY: