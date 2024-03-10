# Allen Coral Atlas
Google Earth Engine code repository

## Background
The Allen Coral Atlas brings together partners from Planet, University of Queensland, Arizona State University's Center for Global Discovery and Conservation Science (GDCS), the National Geographic Society and Vulcan Inc. to take high resolution satellite imagery and advanced analytics to map and monitor the world’s coral reefs in unprecedented detail.  
See the [Allen Coral Atlas website](https://allencoralatlas.org/) for more information.  
See [the organisation repository](https://github.com/CoralMapping/AllenCoralAtlas) for an overview of the resources, citation info, standards and publications arising from the Allen Coral Atlas.  

## Code  
This repo contains all the Google Earth Engine source code that generates the mapping outputs on the Coral Atlas, including maps and validation statistics.  
Several scientific publications cover the methodological and applied background to the mapping code in this repo.  

Due to some particulars of GEE <-> google source git, there are three directories:  
 - `/global_reefs1` (reef regions commenced before March 2021)
 - `/global_reefs2` (reef regions commenced after March 2021)
 - `/global_reefs_modules)` (various helper functions, asset paths, colour palettes etc.)

### Downstream data analysis
This repo covers the data analysis and validaton results from the most recent version of the mapping.
+ https://github.com/mitchest/global-coral-reefs

## Scientific publications
This paper covers the underlying mapping framework that was developed for the geomorphic and benthic mapping component of the Allen Coral Atlas, including image and derived data sources, Google Earth Engine methods and validation approaches.  
+ Lyons et al. (2020) Mapping the world's coral reefs using a global multiscale earth observation framework. *Remote Sensing in Ecology and Evolution*. [DOI:10.1002/rse2.157](https://doi.org/10.1002/rse2.157)  

This paper describes the global scale CNN mapping approach that was integrated into the Allen Coral Atlas geomorphic mapping routine, and contributes to the overall global area estimates.
+ Li et al. (2020) A global coral reef probability map generated using convolutional neural networks. *Coral Reefs*. [doi.org/10.1007/s00338-020-02005-6](https://doi.org/10.1007/s00338-020-02005-6)

This paper provides a summary of the methods and the revised area statistics - as of the current version 2 mapping on the Atlas portal - including implications and impact.
+ Lyons et al. (2024) New global area estimates for coral reefs from high-resolution mapping. *Cell Reports Sustainability*. [DOI:10.1016/j.crsus.2024.100015](https://doi.org/10.1016/j.crsus.2024.100015)


