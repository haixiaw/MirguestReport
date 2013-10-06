SRCS=$(wildcard sub_*.tex)
srcmain=lintao_main.tex
outpdf=$(patsubst %.tex, %.pdf, $(srcmain))
all: $(outpdf) $(SRCS)
	@xdg-open $< &
$(outpdf): $(srcmain) $(SRCS)
	@pdflatex $<
	@pdflatex $<

$(srcmain): $(SRCS)

.PHONY: all
