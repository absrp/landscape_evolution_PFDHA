# landscape_evolution_PFDHA
A set of scripts to simulate the effect of landscape evolution on coseismic scarp and quantify the information loss associated with landscape evolution.

<!-- ABOUT THE PROJECT -->
## About The Project
ABSTRACT

<!-- GETTING STARTED -->
## Getting Started

Create a conda environment to run the project using the provided yml file: 
```
conda env create -f environment.yml
```
and activate the environment: 
```
conda activate scarp_erosion
```
<!-- ROADMAP -->
### Scripts contained

- [ ] To measure the geometry of earthquake gates in a shapefile
    - [ ] Run the "measure_EQgates.m" Matlab script (must run in directory containing shapefiles)
    - [ ] This will output a csv file with the characterized gates
    - [ ] To measure the spacing between earthquake gate, run the "gatespacing.m" script. This script produces a pdf output fitting log-normal and exponential CDFs to the ECDF of the gate spacings.


<!-- CONTACT -->
## Contact

Please report suggestions and issues:

[@_absrp](https://twitter.com/_absrp) - alba@caltech.edu

Project Link: [https://github.com/absrp/landscape_evolution_PFDHA](https://github.com/absrp/landscape_evolution_PFDHA)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

