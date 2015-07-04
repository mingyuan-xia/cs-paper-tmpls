all: *.tex
	pdflatex paper.tex
	bibtex paper
	pdflatex paper.tex
	bibtex paper
	pdflatex paper.tex

clean:
	rm -rf *.aux *.bbl *.log *.blg *.fdb_latexmk *.ent
