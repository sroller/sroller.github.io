%.pdf : %.md
	pandoc $< -o $@ --variable documentclass=scrartcl --pdf-engine=xelatex -V fontfamily=libertine

all: 2018-report-part1.pdf 2018-report-part1.de.pdf

