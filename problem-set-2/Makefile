target=ps1

$(target).pdf: $(target).tex
	xelatex $(target).tex

all: $(target).pdf

clean:
	rm $(target).aux $(target).log 2> /dev/null

clean-all: 
	rm $(target).aux $(target).log $(target).pdf 2> /dev/null
