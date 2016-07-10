base=a-2016-guias
num=
NAME=${base}-${num}

all:
	pdflatex ${NAME}.tex
	pdflatex ${NAME}.tex

clean:
	rm -f *.aux *.lof *.log *.lot *.out *.toc *.nlo *.bbl *.blg *.brf *.ilg *.ind *.nls *.bak
 
del:
	make clean
	rm -f ${NAME}.pdf
