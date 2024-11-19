These notebooks are used to process data and generate figures from the Herken et al. manuscript: "Environmental challenge rewires functional connections among human genes"

Data can be found at:

https://app.box.com/folder/171917844113?s=nuwov4kgb55mqfrr7j5a216ot78f4uxn

With the exception of the "clustering_analysis" notebook, all notebooks should run after installing the conda environment "gi_env.yaml" which can also be found at the box folder linked above. The "clustering_analysis" notebook must be run using in the "gi_circos.yaml" environment. 

The first step should be running through the "calulate_genetic_interactions" notebook. This notebook generates paired and single guide phenotype matrices as well as guide and gene level genetic interaction maps, and other important accessory files such as guide to gene keys for all five GI maps from this study using the counts matrixes from the box folder. We recommend writing the outputs from this notebook locally as they are imported and called as variables in most other notebooks. Data not related to genetic interactions needed to run some notebooks are also available in the box folder.

The purpose of each notebook in addition to all figure panels that are generated from plots made in the notebook are listed in the first cell
