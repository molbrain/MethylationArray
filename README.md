# MethylationArray

**A memo introducing the standard tools and pipelines used in methylation array analysis in our laboratory.**


# DEMO

Using minfi/limma
```R
library(minfi)
library(limma)
```

Using ChAMP
```
library(ChAMP)
```

Using SeSaMe
```R
library(sesame)
```


# Requirement/installation

[R](https://www.r-project.org) environment and [Bioconductor](https://bioconductor.org) packages are required.
Of course, you can use [RStudio](https://posit.co/products/open-source/rstudio/).






# Note

If you would like to analyze the methylation array data with DNA from non-human primates, you must use the annotation of your sample's species.
Please show as follows:
- Common Marmoset (Callithrix jacchus) : [Nakachi et al. Neuropsychopharmacol Rep 2020, doi: 10.1016/j.neures.2017.02.005](https://doi.org/10.1016/j.neures.2017.02.005)
- Crab-eating macaque (Macaca fascicularis) : [Ueda et al. Neurosci Res 2017, doi: 10.1002/npr2.12145](https://doi.org/10.1002/npr2.12145)



