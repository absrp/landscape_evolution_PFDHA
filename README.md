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

- [ ] scarp_erosion_simulation.ipynb
    - [ ] A script that inputs a DEM and, under the user's choice of diffusion conditions, generates a synthetic DEM that has experienced landscape evolution over a     user-defined timescale

- [ ] information_loss_analysis.ipynb
    - [ ] A script that inputs a DEM and, under the user's choice of diffusion conditions, generates a synthetic DEM that has experienced landscape evolution over a     user-defined timescale, and estimates the information loss at different time-steps.
    - [ ] Output 1: distribution of slopes in the landscape and their evolution over time, as well as a map of the elevation difference over time
    - [ ] Output 2: computation and plotting of the degradation coeffient over time and fitting of a power-law relationship through it

We define the degradation coefficient $\phi$ as:
$$
\begin{equation}
\phi = mean(\frac{slope_{t0}}{slope_{t}})
\end{equation}
$$
  
- [ ] length_loss_analysis.ipynb
    - [ ] A script that inputs a series of shapefiles mapping scarps at different timescales and estimates the length of scarp map at every time
    - [ ] Output 1: plot of the change in mapped length over time


<!-- CONTACT -->
## Contact

Please report suggestions and issues:

[@_absrp](https://twitter.com/_absrp) - alba@caltech.edu

Project Link: [https://github.com/absrp/landscape_evolution_PFDHA](https://github.com/absrp/landscape_evolution_PFDHA)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

