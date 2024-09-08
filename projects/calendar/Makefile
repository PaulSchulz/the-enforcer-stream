.PHONY: all clean dist-clean

LATEX=lualatex
LATEX_OPTS=-interaction=nonstopmode -halt-on-error

all: lsa-calendar-2025.pdf lsa-calendar-2025-trim.pdf

%.pdf: %.tex
	 $(LATEX) $(LATEX_OPTS) $<

clean:
	@rm -v *.dvi *.ps *.aux *.log *.bbl *.blg *.bcf *.toc

dist-clean:
	@rm lsa-calendar-2025.pdf lsa-calendar-2025-trim.pdf
