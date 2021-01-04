all: tenx-unfiltered-pbmc4k.md muraro-pancreas.md segerstolpe-pancreas.md zeisel-brain.md bach-mammary.md lun-416b.md grun-hsc.md tenx-filtered-pbmc3k-4k-8k.md lawlor-pancreas.md nestorowa-hsc.md paul-hsc.md grun-pancreas.md tenx-repertoire-pbmc8k.md pijuan-embryo.md about-the-contributors.md analysis-overview.md bibliography.md getting-datasets.md hca-bone-marrow.md index.md installation.md interoperability.md learning-r.md messmer-hesc.md nuclei-analysis.md protein-abundance.md sce-class.md big-data.md droplet-processing.md interactive.md normalization.md reduced-dimensions.md cell-annotation.md doublet-detection.md clustering.md feature-selection.md quality-control.md cell-cycle.md data-integration.md marker-detection.md trajectory.md merged-hsc.md merged-pancreas.md repertoire-seq.md sample-comparisons.md

tenx-unfiltered-pbmc4k.md: tenx-unfiltered-pbmc4k.Rmd
	R -e "knitr::knit('tenx-unfiltered-pbmc4k.Rmd')"

muraro-pancreas.md: muraro-pancreas.Rmd
	R -e "knitr::knit('muraro-pancreas.Rmd')"

segerstolpe-pancreas.md: segerstolpe-pancreas.Rmd
	R -e "knitr::knit('segerstolpe-pancreas.Rmd')"

zeisel-brain.md: zeisel-brain.Rmd
	R -e "knitr::knit('zeisel-brain.Rmd')"

bach-mammary.md: bach-mammary.Rmd
	R -e "knitr::knit('bach-mammary.Rmd')"

lun-416b.md: lun-416b.Rmd
	R -e "knitr::knit('lun-416b.Rmd')"

grun-hsc.md: grun-hsc.Rmd
	R -e "knitr::knit('grun-hsc.Rmd')"

tenx-filtered-pbmc3k-4k-8k.md: tenx-filtered-pbmc3k-4k-8k.Rmd
	R -e "knitr::knit('tenx-filtered-pbmc3k-4k-8k.Rmd')"

lawlor-pancreas.md: lawlor-pancreas.Rmd
	R -e "knitr::knit('lawlor-pancreas.Rmd')"

nestorowa-hsc.md: nestorowa-hsc.Rmd
	R -e "knitr::knit('nestorowa-hsc.Rmd')"

paul-hsc.md: paul-hsc.Rmd
	R -e "knitr::knit('paul-hsc.Rmd')"

grun-pancreas.md: grun-pancreas.Rmd
	R -e "knitr::knit('grun-pancreas.Rmd')"

tenx-repertoire-pbmc8k.md: tenx-repertoire-pbmc8k.Rmd
	R -e "knitr::knit('tenx-repertoire-pbmc8k.Rmd')"

pijuan-embryo.md: pijuan-embryo.Rmd
	R -e "knitr::knit('pijuan-embryo.Rmd')"

about-the-contributors.md: about-the-contributors.Rmd
	R -e "knitr::knit('about-the-contributors.Rmd')"

analysis-overview.md: analysis-overview.Rmd
	R -e "knitr::knit('analysis-overview.Rmd')"

bibliography.md: bibliography.Rmd
	R -e "knitr::knit('bibliography.Rmd')"

getting-datasets.md: getting-datasets.Rmd
	R -e "knitr::knit('getting-datasets.Rmd')"

hca-bone-marrow.md: hca-bone-marrow.Rmd
	R -e "knitr::knit('hca-bone-marrow.Rmd')"

index.md: index.Rmd
	R -e "knitr::knit('index.Rmd')"

installation.md: installation.Rmd
	R -e "knitr::knit('installation.Rmd')"

interoperability.md: interoperability.Rmd
	R -e "knitr::knit('interoperability.Rmd')"

learning-r.md: learning-r.Rmd
	R -e "knitr::knit('learning-r.Rmd')"

messmer-hesc.md: messmer-hesc.Rmd
	R -e "knitr::knit('messmer-hesc.Rmd')"

nuclei-analysis.md: nuclei-analysis.Rmd
	R -e "knitr::knit('nuclei-analysis.Rmd')"

protein-abundance.md: protein-abundance.Rmd
	R -e "knitr::knit('protein-abundance.Rmd')"

sce-class.md: sce-class.Rmd
	R -e "knitr::knit('sce-class.Rmd')"

big-data.md: big-data.Rmd tenx-unfiltered-pbmc4k.md
	R -e "knitr::knit('big-data.Rmd')"

droplet-processing.md: droplet-processing.Rmd tenx-unfiltered-pbmc4k.md
	R -e "knitr::knit('droplet-processing.Rmd')"

interactive.md: interactive.Rmd tenx-unfiltered-pbmc4k.md
	R -e "knitr::knit('interactive.Rmd')"

normalization.md: normalization.Rmd zeisel-brain.md
	R -e "knitr::knit('normalization.Rmd')"

reduced-dimensions.md: reduced-dimensions.Rmd tenx-unfiltered-pbmc4k.md zeisel-brain.md
	R -e "knitr::knit('reduced-dimensions.Rmd')"

cell-annotation.md: cell-annotation.Rmd tenx-unfiltered-pbmc4k.md muraro-pancreas.md segerstolpe-pancreas.md zeisel-brain.md bach-mammary.md
	R -e "knitr::knit('cell-annotation.Rmd')"

doublet-detection.md: doublet-detection.Rmd bach-mammary.md
	R -e "knitr::knit('doublet-detection.Rmd')"

clustering.md: clustering.Rmd tenx-unfiltered-pbmc4k.md lun-416b.md
	R -e "knitr::knit('clustering.Rmd')"

feature-selection.md: feature-selection.Rmd tenx-unfiltered-pbmc4k.md segerstolpe-pancreas.md lun-416b.md
	R -e "knitr::knit('feature-selection.Rmd')"

quality-control.md: quality-control.Rmd tenx-unfiltered-pbmc4k.md zeisel-brain.md lun-416b.md
	R -e "knitr::knit('quality-control.Rmd')"

cell-cycle.md: cell-cycle.Rmd lun-416b.md grun-hsc.md
	R -e "knitr::knit('cell-cycle.Rmd')"

data-integration.md: data-integration.Rmd tenx-filtered-pbmc3k-4k-8k.md
	R -e "knitr::knit('data-integration.Rmd')"

marker-detection.md: marker-detection.Rmd tenx-unfiltered-pbmc4k.md lun-416b.md lawlor-pancreas.md
	R -e "knitr::knit('marker-detection.Rmd')"

trajectory.md: trajectory.Rmd nestorowa-hsc.md
	R -e "knitr::knit('trajectory.Rmd')"

merged-hsc.md: merged-hsc.Rmd grun-hsc.md nestorowa-hsc.md paul-hsc.md
	R -e "knitr::knit('merged-hsc.Rmd')"

merged-pancreas.md: merged-pancreas.Rmd muraro-pancreas.md segerstolpe-pancreas.md lawlor-pancreas.md grun-pancreas.md
	R -e "knitr::knit('merged-pancreas.Rmd')"

repertoire-seq.md: repertoire-seq.Rmd tenx-repertoire-pbmc8k.md
	R -e "knitr::knit('repertoire-seq.Rmd')"

sample-comparisons.md: sample-comparisons.Rmd pijuan-embryo.md
	R -e "knitr::knit('sample-comparisons.Rmd')"
