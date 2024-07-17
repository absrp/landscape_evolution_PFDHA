<!-- ABOUT THE PROJECT -->
## About The Project
A set of scripts to simulate the effect of surface processes on surface ruptures and quantify the information loss associated with landscape evolution over time. Includes options to simulate surface processes with linear and non-linear diffusion, implemented using open-access code landlab.

### Installation
Building the conda environment from the yaml file:
```
conda env create -f scarp_erosion.yml
conda activate scarp_erosion
```
<!-- ROADMAP -->
### Scripts contained

- [ ] scarp_erosion_simulation_linear.ipynb
    - [ ] A script that inputs a DEM and, under the user's choice of diffusion conditions, using the linear landlab diffusion implementation, generates a synthetic DEM that has experienced landscape evolution over a  user-defined timescale. 
    - [ ] Output 1: synthetic DEM in ascii format

- [ ] scarp_erosion_simulation_nonlinear.ipynb
    - [ ] A script that inputs a DEM and, under the user's choice of diffusion conditions, using the Taylor non-linear landlab diffusion implementation for transport-limited landscape evolution, generates a synthetic DEM that has experienced landscape evolution over a  user-defined timescale. 
    - [ ] Output 1: synthetic DEM in ascii format
    - [ ] Output 2: elevation difference between the linear and non-linear solutions for a given time period
    
- [ ] information_loss_bulk.ipynb
    - [ ] A script that inputs a set of DEMs and shapefiles and, under the user's choice of diffusion conditions, generates a synthetic DEM that has experienced landscape evolution over a user-defined timescale, and estimates the information loss at different time-steps. 
    - [ ] Output 1: hillshades showing landscape evolution
    - [ ] Output 2: evolution of measured line length over time
    - [ ] Output 3: evolution of height distribution in DEM with landscape evolution
    - [ ] Output 4: distribution of slopes in the landscape and their evolution over time, and computation of the degradation coefficient
Includes option to save the outputs as pdf files for each DEM in a csv file compiling all measured line lengths and degradation coefficients. Must select yes in the first cell.

- [ ] degradation_coefficient_length_evolution_comparison.ipynb
    - [ ] Output 1: plot showing the evolution of degradation coefficient and line lenght for each model over time, each fit by different non-linear relationships

- [ ] soil_flux_slope_exploration.ipynb
    - [ ] Output 1: plot showing the relationship between soil flux and slope under different transport laws. Includes linear diffusion, and non-linear solutions from Di Michieli Vitturi and Arrowsmith (2013) and Ganti (2013).
    
<!-- CONTACT -->
## Contact

Please report suggestions and issues:

Email: alba@caltech.edu, amrodriguezpadilla@gmail.com

Project Link: [https://github.com/absrp/landscape_evolution_earthquake_ruptures](https://github.com/absrp/landscape_evolution_earthquake_ruptures)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- CONTRIBUTORS -->
## Contributors

Alba M. Rodriguez Padilla (Caltech)

Mindy Zuckerman (ASU)

Ramon Arrowsmith (ASU)
