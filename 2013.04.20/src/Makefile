
all: lintao_2013_04.tex
	@xelatex $^
	@xelatex $^
	@xdg-open $(patsubst %.tex, %.pdf, $^)

lintao_2013_04.tex: $(wildcard sub_*.tex)
