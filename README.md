# Peculiar Velocities Covariance Matrix


## TODO
- [x] Write further speed-ups of the $C_{ij}$ elements and the covariance matrix calculation.
- [x] Improve the grid sampling for more speed.
- [x] Update the $P(k)$ interpolator to be in log-log and cubic.
- [x] Write a hybrid covariance matrix calculation that uses interpolator for far-spaced elements and direct calculation for close-spaced elements.
- [x] Add growth factor prefactors to the $C_{ij}$ calculation.
- [x] Add a function that constructs the covariance matrix from a set of observations.
- [x] Add a function that gradually writes to a file when sampling the interpolator grid, so that the jobs can be interrupted.
- [x] Fix bug in $\ell$ factors.
- [x] Improve spacing in $k$ so that it is linear at high $k$.
