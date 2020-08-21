.PNONY: all clean

all: spark-sql.html

spark-sql.html:
	R -e "rmarkdown::render('spark-sql.Rmd')"
	
clean:
	rm -f *.log
	rm -rf metastore_db
	rm -f *.html