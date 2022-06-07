SHELL:=bash

.PHONY : all

all : pdf

pdf : main.pdf

main.pdf : 
	latexmk -C && latexmk -xelatex -shell-escape main.tex

clean :
	latexmk -C

.DELETE_ON_ERROR:

.SECONDARY: