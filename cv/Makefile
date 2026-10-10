.PHONY: all clean

CC = lualatex
RESUME_SRCS = $(shell find resume -name '*.tex')
CV_SRCS = $(shell find cv -name '*.tex')

all: cv.pdf resume.pdf coverletter.pdf

cv.pdf: cv.tex awesome-cv.cls $(CV_SRCS)
	$(CC) $<

resume.pdf: resume.tex awesome-cv.cls $(RESUME_SRCS)
	$(CC) $<

coverletter.pdf: coverletter.tex awesome-cv.cls
	$(CC) $<

clean:
	rm -f *.pdf *.aux *.log *.out
