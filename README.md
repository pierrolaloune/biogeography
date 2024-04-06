# Biogeography Research Repository
## Overview
This repository serves as a comprehensive resource for researchers and enthusiasts in the field of **biogeography**. It is structured into four main directories, each focusing on a critical area of biogeography: 
1. beta diversity
2. bioregionalisation
3. clustering
4. modeling dispersal patterns ('modeling_dp').
The repository includes datasets, R scripts, and methodologies designed to advance the study of species distribution, ecological diversity, and the processes driving the geographical organization of biological diversity.

## Contents
### Beta Diversity (beta_diversity)
Description:This section focuses on the analysis of beta diversity, which measures the change in species composition across different environments or geographical areas. The scripts and datasets here are used to calculate and visualize beta diversity indices among various habitats or regions.
**Key Scripts**:
- beta_div_calculation.R: Calculates beta diversity indices.
- beta_div_visualization.R: Generates visualizations of beta diversity across different areas.
### Bioregionalisation (bioregionalisation)
Description: Bioregionalisation involves delineating spatially distinct areas that differ significantly in their species compositions. This section contains methods and algorithms for identifying and mapping these unique biological regions.
**Key Scripts**:
- bioregionalisation_analysis.R: Analyzes spatial data to identify distinct bioregions.
- map_generation.R: Creates detailed maps showing the boundaries and characteristics of identified bioregions.
### Clustering (clustering)
Description: This directory applies clustering algorithms to biogeographical data to uncover patterns of similarity or dissimilarity among species or regions, aiding in the understanding of ecological and evolutionary processes.
**Key Scripts**:
- species_clustering.R: Clusters species based on ecological or genetic similarities.
- region_clustering.R: Identifies clusters of geographically or ecologically similar regions.
### Modeling Dispersal Patterns (modeling_dp)
Description: Focuses on the modeling of species dispersal patterns to predict changes in distribution in response to various environmental factors or over time. This section includes models that simulate dispersal mechanisms and potential shifts in species ranges.
**Key Scripts**:
- dispersal_modeling.R: Models the dispersal patterns of species under different scenarios.
- range_shift_analysis.R: Analyzes potential shifts in species ranges due to climate change or other factors.
Installation
Ensure you have R installed on your machine (visit CRAN for the latest version). Some scripts may require additional R packages, which can be installed as follows:
```
install.packages(c("sp", "raster", "dismo", "vegan", "ade4"))
```

## Contributing
Contributions are welcome! If you're interested in contributing, please follow these steps:
1. Fork the repository.
2. Create a new branch for your feature or fix.
3. Commit your changes.
4. Push to the branch.Submit a pull request.

## License
This project is licensed under the MIT License. See the LICENSE file in the root directory for details.

## Contact
For questions or suggestions, please open an issue on this repository, or contact pierrebdef@gmail.com
