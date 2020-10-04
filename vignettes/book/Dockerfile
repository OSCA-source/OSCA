FROM bioconductor/bioconductor_docker:devel

RUN mkdir /home/book
COPY . /home/book

RUN R --quiet -e "options(warn=2); BiocManager::install(union(remotes::local_package_deps('/home/book', dependencies=TRUE), 'bookdown'))"

LABEL name="bioconductor/bioconductor_docker_orchestratingsinglecellanalysis" \
      version="1.0.0" \
      url="https://github.com/Bioconductor/OrchestratingSingleCellAnalysis" \
      maintainer="infinite.monkeys.with.keyboards@gmail.com" \
      description="Build environment and contents of the OSCA book" \
      license="Artistic-2.0"

RUN mkdir /home/cache
ENV EXPERIMENT_HUB_CACHE /home/cache/ExperimentHub
ENV EXPERIMENT_HUB_ASK FALSE
ENV ANNOTATION_HUB_CACHE /home/cache/AnnotationHub
ENV XDG_CACHE_HOME /home/cache
