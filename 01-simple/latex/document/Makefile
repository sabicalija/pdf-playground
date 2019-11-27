MAKER       = latexmk
MAKER_OPTS ?= -shell-escape
TARGET      = document

all: pdf clean

pdf:
	$(MAKER) $(MAKER_OPTS) -pdf $(TARGET).tex

clean:
	$(MAKER) -c $(TARGET).tex