.PHONY: clean

all: pdf

pdf: index
	pdflatex thesis.tex

index: thesis.tex
	pdflatex thesis.tex && makeindex thesis.idx

clean: 
	rm -f *.pdf *.idx *.lof *.aux *.toc *.log *.lot *.fdb_latexmk *.fls
