all:
	pdflatex sensys12.tex
	bibtex sensys12
	pdflatex sensys12.tex
	pdflatex sensys12.tex
clean:
	/bin/rm -f sensys12.pdf *.dvi *.aux *.ps *~ *.log
	/bin/rm -f *.lot *.lof *.toc *.blg *.bbl url.sty *.out
