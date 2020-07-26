.PNONY: all clean

all: spark-sql.html

databases.html:
	R -e "rmarkdown::render('spark-sql.Rmd')"
	
clean:
	rm -f *.log
	rm -rf metastore_db