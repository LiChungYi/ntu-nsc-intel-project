all:
	pdflatex sensys12.tex
	bibtex sensys12
	pdflatex sensys12.tex
	pdflatex sensys12.tex
	#ln -s $(shell pwd)/sensys12.pdf ~/htdocs/b.pdf
clean:
	/bin/rm -f sensys12.pdf *.dvi *.aux *.ps *~ *.log
	/bin/rm -f *.lot *.lof *.toc *.blg *.bbl url.sty *.out
	/bin/rm -f ~/htdocs/b.pdf
