# EcoDataSci-AquaticMarine
Data repository for "Ecological Data Science for Aquatic and Marine Systems: Quantitative Methods, Population Dynamics and Machine Learning in R" (Springer Nature)

Companion data repository for:

> Castillo-Navarro, H. et al. (2026). *Ecological Data Science 
> for Aquatic and Marine Systems: Quantitative Methods, 
> Population Dynamics and Machine Learning in R*. 
> Springer Nature, Use R! Series.

## Data description

All datasets are either:
- **Simulated** with ecologically realistic parameters derived 
  from published literature (see individual metadata files)
- **Real** downloaded from public repositories 
  (ICES DATRAS, RAM Legacy, ERDDAP)

Simulated datasets use fixed random seeds for full 
reproducibility. Parameters are documented in the 
`metadata/` folder with references to the source literature.

## How to load in R

```r
base_url <- "https://raw.githubusercontent.com/
             YOUR_USERNAME/EcoDataSci-AquaticMarine/main/data/"

# Example: Chapter 2 dataset
cpua <- read.csv(paste0(base_url, "cap02_lutjanus_cpua.csv"))
```

## License

Data: Creative Commons Attribution 4.0 (CC BY 4.0)  
Code: MIT License

## Citation

See CITATION.cff or cite as:  
Castillo-Navarro et al. (2026), Springer Nature.

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC_BY_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
