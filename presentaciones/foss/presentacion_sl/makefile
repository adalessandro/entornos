#
# Compilación de los latex.
#




charla-sl.pdf: charla-sl.tex
	pdflatex -interaction=nonstopmode charla-sl.tex

pdf: charla-sl.pdf

view: pdf
	evince charla-sl.pdf

clean:
	rm -f *.out *.log *.toc *.idx *~

clean_out:
	rm -f *.pdf *.dvi *.tar.gz

dist:
	tar czvf charla-sl.tar.gz makefile *.tex *.sty *.dvi *.pdf *.dia *.xmi *.eps
