# rebound orbit simulations

These notebooks compute the data for a quasi-periodic asteroid (Figure 3.4) and a chaotic asteroid (Figure 3.6)
using the [rebound](https://rebound.readthedocs.io/en/latest/) N-body integrator package
developed by Hanno Rein and collaborators. 

The figures in the main notebooks in this repository work with pre-calculated files for simplicity. Installation of `rebound` is more involved
as it requires local compilation, but if you want to explore `rebound` for yourself or your students, these are the
notebooks that ran rebound for our figures.

## Jupyter Notebooks

 * `Fig3.4 Quasi-periodic Asteroid rebound.ipynb` - version of Figure 3.4 notebook with in-situ rebound simulation
 * `Quasi-periodic Asteroid.ipynb` - computes the orbits and exports the file as ascii text file `quasiAsteroid.txt`
 * `Fig3.7 Chaoitc Asteroid rebound.ipynb` - version of Figure 3.6 notebook with in-situ rebound simulation
 * `Chaotic Asteroid.ipynb` - computes the orbits and exports the file as ascii text file `chaoticAsteroid.txt`

