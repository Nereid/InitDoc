all: Introduction.pdf

clean: cleantmp
	rm Introduction.pdf 2> /dev/null
	rm *.toc 2> /dev/null

cleantmp:
	rm *.log *.out *.aux 2> /dev/null

Introduction.pdf: Introduction.tex
	pdflatex Introduction.tex
