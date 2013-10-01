all: lintao_main.pdf
	@xdg-open $^
lintao_main.pdf: lintao_main.dvi
	@dvipdfmx $^

lintao_main.dvi: lintao_main.tex
	@latex $^
	@latex $^

lintao_main.tex: $(wildcard sub_*.tex)
