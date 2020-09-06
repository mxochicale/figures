INKSCAPE?=inkscape	# Inkscape (svg support)
#References
#https://scaron.info/blog/makefiles-for-latex.html

FIGURES_SVG=$(wildcard svgpath/*.svg)
FIGURES_PNG=$(subst svgpath/,versions/,$(FIGURES_SVG:.svg=.png))
FIGURES_PDF=$(subst svgpath/,versions/,$(FIGURES_SVG:.svg=.pdf))

all:	$(FIGURES_PNG) $(FIGURES_PDF)

# Pattern rule for converting SVG to PNG
versions/%.png: svgpath/%.svg
	$(INKSCAPE) --export-filename $(@) $(<)

versions/%.pdf: svgpath/%.svg
	$(INKSCAPE) --export-filename $(@) $(<)


viewpng:
	eog $(FIGURES_PNG)

clean:  ##  output figure files
	rm -f $(FIGURES_PNG) $(FIGURES_PDF)

