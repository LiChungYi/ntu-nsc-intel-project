all:
	pdflatex bigdata.tex
	bibtex bigdata 
	pdflatex bigdata.tex
	pdflatex bigdata.tex
	scp bigdata.pdf r00922051@linux1.csie.org:~/htdocs/a.pdf
clean:
	/bin/rm -f bigdata.pdf *.dvi *.aux *.ps *~ *.log
	/bin/rm -f *.lot *.lof *.toc *.blg *.bbl url.sty *.out
	/bin/rm -f *convert*.pdf
