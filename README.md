# landscape_evolution_PFDHA
A set of scripts to simulate the effect of surface processes on surface ruptures and quantify the information loss associated with landscape evolution over time.

<!-- ABOUT THE PROJECT -->
## About The Project
ABSTRACT

<!-- ROADMAP -->
### Scripts contained

- [ ] scarp_erosion_simulation.ipynb
    - [ ] A script that inputs a DEM and, under the user's choice of diffusion conditions, generates a synthetic DEM that has experienced landscape evolution over a  user-defined timescale. Linear diffusion is the only diffusion implementation available as of June 2024. 
    - [ ] Output 1: synthetic DEM in ascii format

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
<img width="476" alt="image" src="https://github.com/absrp/landscape_evolution_PFDHA/assets/52015046/4392e6e8-6aef-40c5-abc4-7f32a2cc80c1">


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
