# landscape_evolution_PFDHA
A set of scripts to simulate the effect of surface processes on surface ruptures and quantify the information loss associated with landscape evolution over time.

<!-- ABOUT THE PROJECT -->
## About The Project
ABSTRACT

<!-- ROADMAP -->
### Scripts contained

- [ ] scarp_erosion_simulation_linear.ipynb
    - [ ] A script that inputs a DEM and, under the user's choice of diffusion conditions, using the linear landlab difussion implementation, generates a synthetic DEM that has experienced landscape evolution over a  user-defined timescale. 
    - [ ] Output 1: synthetic DEM in ascii format

- [ ] scarp_erosion_simulation_nonlinear.ipynb
    - [ ] A script that inputs a DEM and, under the user's choice of diffusion conditions, using the Taylor non-linear landlab difussion implementation for transport-limited landscape evolution, generates a synthetic DEM that has experienced landscape evolution over a  user-defined timescale. 
    - [ ] Output 1: synthetic DEM in ascii format
    - [ ] Output 2: elevation difference between the linear and non-linear solutions for a given time period
    
- [ ] information_loss_bulk.ipynb
    - [ ] A script that inputs a set of DEMs and shapefiles and, under the user's choice of diffusion conditions, generates a synthetic DEM that has experienced landscape evolution over a user-defined timescale, and estimates the information loss at different time-steps. 
    - [ ] Output 1: hillshades showing landscape evolution
    - [ ] Output 2: evolution of measured line length over time
    - [ ] Output 3: evolution of height distribution in DEM with landscape evolution
    - [ ] Output 4: distribution of slopes in the landscape and their evolution over time, and computation of the degradation coefficient
    The results are output as pdf files and into a csv file.
- [ ] degradation_coefficient_length_evolution_comparison.ipynb
    - [ ] Output 1: plot showing the evolution of degradation coefficient and line lenght for each model over time, each fit by different non-linear relationships
      
### Sample pdf output for one location 
<img width="534" alt="image" src="https://github.com/absrp/landscape_evolution_PFDHA/assets/52015046/22ebf383-1d0f-4c49-847a-bee6e5cbada2">

<!-- CONTACT -->
## Contact

Please report suggestions and issues:

Email: alba@caltech.edu, amrodriguezpadilla@gmail.com

Project Link: [https://github.com/absrp/landscape_evolution_PFDHA](https://github.com/absrp/landscape_evolution_PFDHA)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- CONTRIBUTORS -->
## Contributors

Alba M. Rodriguez Padilla (Caltech)

Mindy Zuckerman (ASU)

Ramon Arrowsmith (ASU)
