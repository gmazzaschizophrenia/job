lettera2 : lettera2.dvi
	dvips lettera2.dvi -o ;
	dvipdf lettera2.dvi

lettera2.dvi : lettera2.tex head.tex
	latex lettera2.tex;

.PHONY : clean, allclean

clean :
	rm -f *~ lettera2.aux lettera2.dvi lettera2.log *~ # lettera2.pdf

allclean :
	rm -f lettera2.aux lettera2.dvi lettera2.log *~ lettera2.pdf lettera2.ps

