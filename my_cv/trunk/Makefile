# # cfr Linux & C # 35 (?)
# SRCS = $(wildcard *.ps)
# # SRCS = cv.tex
# all : $(SRCS:.ps=.pdf)

# %.pdf : %.ps
# 	ps2pdf $^ $@

cv : cv.dvi
	dvips cv.dvi -o ;
	dvipdf cv.dvi

cv.dvi : cv.tex
	latex cv.tex;

.PHONY : clean, allclean

clean :
	rm -f *~ cv.aux cv.dvi cv.log *~ # cv.pdf

allclean :
	rm -f cv.aux cv.dvi cv.log *~ cv.pdf cv.ps

################################################################

# help:
# 	@echo 'Type "make it " if you like Italian version'
# 	@echo 'Type "make eng" if you like English version'

# #---------------------------------------------------------------
# # cfr Linux & C # 35 (?)
# SRCS = $(wildcard *.ps)

# all : $(SRCS:.ps=.pdf)

# %.pdf : %.ps
# 	ps2pdf $^ $@
# #---------------------------------------------------------------
# # it : it.gmazza.tex
# # 	pdflatex it.gmazza.tex #;
# #-------
# it : it.gmazza.dvi
# 	dvips it.gmazza.dvi -o
# #       dvipdf tesi.dvi -o
# #       echo "LA MIA TESI ..." ;

# it.gmazza.dvi : it.gmazza.tex
# 	latex it.gmazza.tex;
# #	latex domanda.tex  # Baudoin 21
# #---------------------------------------------------------------
# # eng : eng.gmazza.tex
# # 	pdflatex eng.gmazza.tex #;
# #-------
# eng : eng.gmazza.dvi
# 	dvips eng.gmazza.dvi -o
# #       dvipdf tesi.dvi -o
# #       echo "LA MIA TESI ..." ;

# eng.gmazza.dvi : eng.gmazza.tex
# 	latex eng.gmazza.tex;
# #	latex domanda.tex  # Baudoin 21
# #---------------------------------------------------------------

# .PHONY : clean

# clean :
# 	rm -f *~ *.gmazza.aux *.gmazza.dvi *.gmazza.log *~ # it.gmazza.pdf eng.gmazza.pdf


# # help:
# # 	@echo 'Type "make mp=0 md" or"make mp=1 md"'
# # 	@echo 'where "mp" stands for multi-processor and "md" is the target:'
# # 	@echo '       mp=0    (for single processor - workstation)'
# # 	@echo '       mp=1    (for cluster with LAM/MPI)'
# # 	@echo 'Type "make depend" on apona everytime you include a new ".h"'
