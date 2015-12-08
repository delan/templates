name = template

$(name).pdf: $(name).tex $(name).bib
	latexmk -pdf $(name)

clean:
	rm -f $(name).aux $(name).bbl $(name).bcf     $(name).blg
	rm -f $(name).fdb_latexmk     $(name).fls     $(name).idx
	rm -f $(name).ilg $(name).ind $(name).lof     $(name).log
	rm -f $(name).lot $(name).out $(name).run.xml $(name).toc

distclean: clean
	rm -f $(name).pdf
