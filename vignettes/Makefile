all: compiled

compiled: 
	cd book && "${R_HOME}/bin/R" -e "bookdown::render_book('index.Rmd')"
	rm -rf book/_bookdown_files
	find book/ -maxdepth 1 -type f -delete
	mkdir -p ../inst && cp -r book/docs ../inst/

clean: 
	rm -rf book/*_cache book/*_files
