all:
	pdflatex sensys12.tex
	bibtex sensys12
	pdflatex sensys12.tex
	pdflatex sensys12.tex
#	scp sensys12.pdf r00922051@linux11.csie.org:~/htdocs/a.pdf
#	ln -s $(shell pwd)/sensys12.pdf ~/htdocs/b.pdf
clean:
	/bin/rm -f sensys12.pdf *.dvi *.aux *.ps *~ *.log
	/bin/rm -f *.lot *.lof *.toc *.blg *.bbl url.sty *.out
	/bin/rm -f ~/htdocs/b.pdf
#	ssh r00922051@linux11.csie.org '/bin/rm ~/htdocs/a.pdf'
