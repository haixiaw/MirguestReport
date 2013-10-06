SRCS=$(wildcard sub_*.tex)
srcmain=lintao_main.tex
outpdf=$(patsubst %.tex, %.pdf, $(srcmain))
outdvi=$(patsubst %.tex, %.dvi, $(srcmain))
all: $(outpdf) $(SRCS)
	@xdg-open $< &
$(outpdf): $(outdvi) $(SRCS)
	@dvipdfmx $<

$(outdvi): $(srcmain) $(SRCS)
	@latex $<
	@latex $<

$(srcmain): $(SRCS)

.PHONY: all
