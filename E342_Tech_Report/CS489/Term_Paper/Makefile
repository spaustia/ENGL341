-all: final.tex final.bib
	pdflatex final.tex && \
	bibtex final && \
	pdflatex final.tex && \
	pdflatex final.tex
.PHONY: clean
clean:
	rm -f final.aux final.bbl final.blg final.log final.out final.pdf
