# landscape_evolution_PFDHA
A set of scripts to simulate the effect of landscape evolution on coseismic scarp and quantify the information loss associated with landscape evolution.

<!-- ABOUT THE PROJECT -->
## About The Project
ABSTRACT

<!-- ROADMAP -->
### Scripts contained

- [ ] scarp_erosion_simulation.ipynb
    - [ ] A script that inputs a DEM and, under the user's choice of diffusion conditions, generates a synthetic DEM that has experienced landscape evolution over a  user-defined timescale. Linear diffusion is the only diffusion implementation available as of April 2024. 
    - [ ] Output 1: synthetic DEM is ascii format

- [ ] information_loss_analysis.ipynb
    - [ ] A script that inputs a DEM and shapefiles and, under the user's choice of diffusion conditions, generates a synthetic DEM that has experienced landscape evolution over a user-defined timescale, and estimates the information loss at different time-steps.
    - [ ] Output 1: distribution of slopes in the landscape and their evolution over time, as well as a map of the elevation difference over time
    - [ ] Output 2: computation and plotting of the degradation coeffient over time and fitting of a power-law relationship through it
    - [ ] Output 3: measuring and plotting the change in mapped line length over time from the input shapefiles at each time step

We define the degradation coefficient $\phi$ as:

$$
\phi = mean(\frac{\sum{slope_{t0}}}{\sum{slope_{t}}})
$$

### Sample model 
<img width="744" alt="Screenshot 2024-04-26 at 6 54 01 PM" src="https://github.com/absrp/landscape_evolution_PFDHA/assets/52015046/3fd9fae5-212e-47c6-87d6-e6a5ef073e18">


<!-- CONTACT -->
## Contact

Please report suggestions and issues:

[@_absrp](https://twitter.com/_absrp) - alba@caltech.edu

Project Link: [https://github.com/absrp/landscape_evolution_PFDHA](https://github.com/absrp/landscape_evolution_PFDHA)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- CONTRIBUTORS -->
## Contributors

Alba M. Rodriguez Padilla (Caltech)
Mindy Zuckerman (ASU)
Ramon Arrowsmith (ASU)
