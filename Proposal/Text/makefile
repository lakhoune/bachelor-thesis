JOB = thesis

all: $(JOB).pdf

$(JOB).pdf: content/*.tex bibliography/* thesis.tex preamble/*.tex images/*
	pdflatex $(JOB)
	bibtex   $(JOB)
	pdflatex $(JOB)
	pdflatex $(JOB)

	rm *.aux *.log *.out  *.bbl *.blg **/*.aux

deploy: $(JOB).pdf

clean:
	rm -f *~ *bak *.ps *.pdf *.dvi *.log *.aux *.out *.nav *.snm *.toc *.vrb *.bbl *.blg *.lof *.lot
	rm **/*.aux

.PHONY: clean all
