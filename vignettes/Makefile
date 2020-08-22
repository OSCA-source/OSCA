all: compiled

# Need to get rebook submitted so this is no longer required.
compiled: 
	for x in $(shell ls book/*.Rmd); do \
		cat $$x | sed "s/rebook/simpleSingleCell/g" > blah; \
		mv blah $$x; \
	done
	cd book && ${R_HOME}/bin/R -e "bookdown::render_book('index.Rmd')"
	rm -rf book/_bookdown_files/

clean: 
	rm -rf *_cache *_files
