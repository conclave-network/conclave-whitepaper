.PHONY: clean

all: pdf

pdf: index
	pdflatex whitepaper.tex

index: whitepaper.tex
	pdflatex whitepaper.tex && makeindex whitepaper.idx

clean: 
	rm -f *.pdf *.idx *.lof *.aux *.toc *.log *.lot *.fdb_latexmk *.fls
