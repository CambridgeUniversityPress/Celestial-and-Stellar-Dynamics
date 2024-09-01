# Chapter 5: Exoplanetary Systems

Figures from Chapter 5 of Ryden, *Celestial and Stellar Dynamics*.

## Jupyter Notebooks

<dl>
    <dd>Figure 5.2 - RV curve of 51 Peg b
    <dd>Figure 5.3 - RV curves of eccentric exoplanets
    <dd>Figure 5.6 - Mass-Radius relation for exoplanets
    <dd>Figure 5.7 - Transit Timing Variations in WASP-12b
    <dd>Figure 5.8 - Transit Timing Variations in Kepler-419b and Kepler-88b
</dl>

## Data Files

### Figure 5.2 - RV curve of 51 Peg b

`RVs/Birkby2017_table1.txt` is the radial velocity curve of 51 Pegasi b from the compendium of Birkby et al. 2017, AJ, 153, 138 with 
data from thrir Table 1 downloaded from the VizieR cat/J/AJ/153/138.  See the accompanying `RVs/Birkby2017_readme.txt` file for 
details.

### Figure 5.3 - RV curves of eccentric exoplanets

 * `RVs/HD20868_Moutou2009.txt` is HARPS RV data for HD 20868 from Moutou et al. 2009, A&A, 496, 513, Figure 2.
 * `RVs/HD181234_Rickman2019.txt` is CORALIE RV data for HD 181234 from Rickman et al. 2019, A&A, 625, 71, Figure 1.

See the accompanying `RVs/Moutou2019_readme.txt` and `RVs/Rickman2019_readme.txt` files for details.

### Figure 5.6 - Mass-Radius relation for exoplanets

Observed exoplanet masses and radii from a number of sources:
 * `MassRadius/ChenKipping2017_Table1.csv` is a CSV file with the compilation of masses and radii from Chen & Kipping 2017, ApJ, 834, 17, Figure 3, using a slightly filtered version of their Table 1 data from VizieR J/ApJ/834/17 converted by us into CSV for easy parsing with `pandas`
 * `MassRadius/TESS-M-R.csv` is a CSV file with masses and radii for TESS confirmed planets extracted from the exoplanet archive in August 2023
 * `MassRadius/exoplanets_2023Jan31.csv` is a CSV file with masses and radii of confirmed exoplanets from the Exoplanet archive, some overlap with the TESS data
 * `MassRadius/SolarSystem_Major.csv` is a CSV file with masses and radii of major solar system bodies from the JPL Horizons database

Exoplanet models model M-R relations for spheres of pure iron, rock, water, and molecular hydrogen from Li Zeng's website (lweb.cfa.harvard.edu/~lzeng/planetmodels.html)
 * `Zeng_MR_EarthlikeRocky.txt` - Earth-like rocky composition planets
 * `Zeng_MR_PureFe.txt` - pure iron planets
 * `Zeng_MR_PureH2.txt` - pure molecular hydrogen planets
 * `Zeng_MR_PureRock.txt` - pure rock planets
 * `Zeng_MR_PureH2O.txt` - pure water planets

## Artwork

<dl>
    <dd>Figure 5.1 - `Fig5_1.jpg`: schematic of the projected orbit of a star-exoplanet system (PowerPoint original)
    <dd>Figure 5.4 - `Fig5_4.jpg`: annotated schematic of a projected transiting exoplanet orbit (PowerPoint original)
    <dd>Figure 5.5 - `Fig5_5.jpg`: annotated schematic orbit and light-curve of a transiting exoplanet (PowerPoint original)
</dl>

