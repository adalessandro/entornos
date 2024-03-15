#
# Compilación de los latex.
#

all: charla-sl.pdf

charla-sl.pdf: charla-sl.tex
	# Run twice to generate .toc in the first run, then required by pdflatex
	pdflatex -interaction=nonstopmode charla-sl.tex ; pdflatex -interaction=nonstopmode charla-sl.tex

clean:
	rm -f *.out *.log *.toc *.idx *.aux *.nav *.snm *.pdf
