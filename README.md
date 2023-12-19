# landscape_evolution_PFDHA
A set of scripts to simulate the effect of landscape evolution on coseismic scarp and quantify the information loss associated with landscape evolution.

<!-- ABOUT THE PROJECT -->
## About The Project
ABSTRACT

<!-- GETTING STARTED -->
## Getting Started

Create a conda environment to run the project using the provided yml file: 

conda env create -f environment.yml

and activate the environment: 

conda activate scarp_erosion

### Prerequisites

The subset of the scripts that measure the geometry of earthquake gates from shapefiles are in Matlab and require the Matlab Mapping Toolbox. Some of the scripts rely on functions downloable from Mathworks. The specific dependencies for each Matlab script to run are listed at the beginning of the corresponding script. The scripts for estimating passing probabilities and event likelihood are available as Python Jupyter Notebooks.

<!-- ROADMAP -->
### Measuring earthquake gate geometry, estimating passing probabilities, and estimating event likelihood

- [ ] To measure the geometry of earthquake gates in a shapefile
    - [ ] Run the "measure_EQgates.m" Matlab script (must run in directory containing shapefiles)
    - [ ] This will output a csv file with the characterized gates
    - [ ] To measure the spacing between earthquake gate, run the "gatespacing.m" script. This script produces a pdf output fitting log-normal and exponential CDFs to the ECDF of the gate spacings.

- [ ] To estimate passing probabilities and event likelihood
    - [ ] Run the "analysis_EQgates_probabilities.ipynb" Jupyter Notebook. Requires the csv containing the gate geometries.
    - [ ] This script estimates passing probability as a function of geometry and event likelihood
    - [ ] This will output the figures in the manuscript.


<!-- CONTACT -->
## Contact

Please report suggestions and issues:

[@_absrp](https://twitter.com/_absrp) - alba@caltech.edu

Project Link: [https://github.com/absrp/passing_probabilities_EQgates](https://github.com/absrp/passing_probabilities_EQgates)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

Manuscript Link: * to be submitted, stay tuned *
