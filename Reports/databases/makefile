.PNONY: clean all

all: databases.html

clean:
	rm -f *.html

databases.html:
	R -e "rmarkdown::render('databases.Rmd')"
