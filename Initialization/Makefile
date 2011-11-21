TARGET=Initialization.pdf
INCLUDES=Introduction.tex Description.tex Planning.tex Roles.tex Management.tex Tools.tex Conclusion.tex
ASSETS=
TEXFILE=Initialization.tex

all: $(TARGET)

clean: cleantmp
	rm -f $(TARGET) *.toc *.ind *.dvi

cleantmp:
	rm -f *.log *.out *.aux *.ilg

$(TARGET): $(TEXFILE) $(INCLUDES) $(ASSETS)
	#Once for toc, hyper-refs, etc, and once for good
	pdflatex $(TEXFILE)
	pdflatex $(TEXFILE)
