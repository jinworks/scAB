
# scAB detects multiresolution cell states with clinical significance by integrating single-cell genomics and bulk sequencing data

## Installation

scAB R package can be easily installed from Github using devtools:  

```
devtools::install_github("jinworks/scAB")
```


### Installation of other dependencies if not automatically installed
- Install [Seurat](https://github.com/satijalab/seurat) using `install.packages('Seurat')`. 
- Install [diptest](https://cran.r-project.org/web/packages/diptest/index.html) using `install.packages('diptest')`.
- Install [multimode](https://cran.r-project.org/web/packages/multimode/index.html) using `install.packages('multimode')`.
- Install [preprocessCore](https://www.bioconductor.org/packages/release/bioc/html/preprocessCore.html) using `if (!require("BiocManager", quietly = TRUE)) install.packages("BiocManager"); BiocManager::install("preprocessCore")`.




