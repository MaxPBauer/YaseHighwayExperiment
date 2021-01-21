# YaseHighwayExperiment dataset

This is the corresponding dataset presented in the paper: TODO ADD WHEN RELEASED.
The dataset contains the results of the 1200 test runs.
Hereby the traffic agent densities and advisory speed limits were varied.  

### Test run metrics
For each test run a animalistic evaluation file documents basic metrics such as the computation time, traveled distance, time duration and more.
### Collision gifs
If a collision occurred while a test run, the simulation was stopped and an additional minimalistic GIF was created.
This GIF allows to get a rough estimation of the collision type without given away the simulator specific details.
The GIF contains the last 5 seconds before the collision and is centered on one of the participating collision partners.
As the collisions mainly occur at the border of the radius of interest, the GIF often contains often black sequences and flacky vehicles due to respwans.
## Remarks:
* The commutated computation time is not equal to the actual computation time, as the test run parallelized on 20 cores.