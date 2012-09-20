all:
	pdflatex ipsn13.tex
	bibtex ipsn13
	pdflatex ipsn13.tex
	pdflatex ipsn13.tex
#	scp ipsn13.pdf r00922051@linux11.csie.org:~/htdocs/a.pdf
#	ln -s $(shell pwd)/ipsn13.pdf ~/htdocs/b.pdf
clean:
	/bin/rm -f ipsn13.pdf *.dvi *.aux *.ps *~ *.log
	/bin/rm -f *.lot *.lof *.toc *.blg *.bbl url.sty *.out
	/bin/rm -f ~/htdocs/b.pdf
#	ssh r00922051@linux11.csie.org '/bin/rm ~/htdocs/a.pdf'
