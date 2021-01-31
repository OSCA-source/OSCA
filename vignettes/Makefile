all: compiled

compiled: 
	rm -rf book/ && cp -r ../inst/book book
	cd book && "${R_HOME}/bin/R" -e "bookdown::render_book('index.Rmd')"
	mkdir ../inst/doc && mv book/docs ../inst/doc/book
	rm -rf book/
