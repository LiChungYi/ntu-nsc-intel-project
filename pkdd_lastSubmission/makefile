all:
	pdflatex pkdd.tex
	bibtex pkdd 
	pdflatex pkdd.tex
	pdflatex pkdd.tex
clean:
	/bin/rm -f pkdd.pdf *.dvi *.aux *.ps *~ *.log
	/bin/rm -f *.lot *.lof *.toc *.blg *.bbl url.sty *.out
	/bin/rm -i *convert*.pdf
