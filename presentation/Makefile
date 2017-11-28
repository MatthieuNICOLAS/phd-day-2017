all:
	pdflatex presentation.tex
	bibtex presentation
	pdflatex presentation.tex
	pdflatex presentation.tex
	$(MAKE) clean

clean:
	rm -rf *.acn *.alg *.glg *.glo *.gls *.glsdefs *.ist *.xdy *.acr *.bbl *.blg *.dvi *.log *.lot *.idx *.toc *.lof *.brf *.out *.fls *.lol *.aux *.nav *.snm *.fdb_latexmk
