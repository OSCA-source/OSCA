all: compiled

compiled: 
	cd book && "${R_HOME}/bin/R" -e "bookdown::render_book('index.Rmd')"
	rm -rf book/_bookdown_files/
	mkdir -p ../inst && mv book/docs ../inst/

clean: 
	rm -rf *_cache *_files
