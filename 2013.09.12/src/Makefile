
all: lintao_dyb_gentool.tex
	@xelatex $^
	@xelatex $^
	@xdg-open $(patsubst %.tex, %.pdf, $^)

lintao_dyb_gentool.tex: $(wildcard sub_*.tex)
