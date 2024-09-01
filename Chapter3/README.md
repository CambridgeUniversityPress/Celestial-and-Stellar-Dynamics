# Chapter 3: Resonances and Chaos

Figures from Chapter 3 of Ryden, *Celestial and Stellar Dynamics*.

## Jupyter Notebooks

<dl>
    <dd>Figure 3.1 - Asteroid Belt Kirkwood Gaps
    <dd>Figure 3.3 - Hilda 3:2 resonant family asteroids
    <dd>Figure 3.4 - Quasi-periodic test asteroid
    <dd>Figure 3.6 - Chaotic test asteroid
    <dd>Figure 3.8 - Asteroid dynamical families
    <dd>Figure 3.9 - Asteroid families in osculating and proper elements 
    <dd>Figure 3.10 - Jupiter Tisserand parameters
</dl>

## Data Files

### Figure 3.1 - Asteroid Belt Kirkwood Gaps

`Asteroids/MPC_Kirkwood.csv` is a CSV file with orbit elements from the MPCORB database for all asteroids in the Main Belt plus the 
Hungarias, Hildas, and Jupiter Trojans. All are brighter than H=16. This is faster than reading all roughly 1.3 million entries in the full MPCORB database.

### Figure 3.3 - Hilda 3:2 resonant family asteroids

`Asteroids/MPC_Hildas.csv` is a CSV file with orbit elements from the MPCORB database for the Hilda family asteroids
(see the `procOrb.ipynb` notebook in the `SolSys` folder for how these are extracted).

### Figure 3.4 - Quasi-periodic test asteroid

`quasiAsteroid.txt` is a 3-column ascii text format file with a commented header containing a pre-computed rebound calculation for a test "asteroid" mass
in a quasi-periodic orbit in a system with the Sun and Jupiter.

### Figure 3.6 - Chaotic test asteroid

`chaoticAsteroid.txt` is a 3-column ascii text format file with a commented header containing a pre-computed rebound calculation for a test "asteroid" mass
in a chaotic (near-resonance) orbit in a simple system with the Sun and Jupiter.

### Figure 3.8 and 3.9 - Asteroid dynamical families 

`Asteroids/AstDyS-2_all.txt` is an ascii text file with proper orbit elements of Main Belt and Hungaria asteroids from the AstDyS-2 
database (https://newton.spacedys.com/astdys/, file all.syn), which we rename AstDyS-2_all.txt to distinguish it from other files in 
the Asteroids/ folder.  We make a brightness cut of all asteroids brighter than H=14.5, which corresponds to a size of roughly 3-5km 
for typical values of asteroid geometric albedo (see https://cneos.jpl.nasa.gov/tools/ast_size_est.html at the JPL Center for 
Near Earth Studies for a useful table).

### Figure 3.10 - Jupiter Tisserand parameters

`Asteroids/MPC_MainBeltPlus.csv` is a CSV file with orbit elements from the MPCORB database of all asteroids in the Main Belt
plus the Hungarias, Hildas, and Jupiter Trojans brighter than H=16.

`Asteroids/MPC_AllCometEls.txt` is comet orbit data from AllCometEls.txt from the MPC. Here we use a fixed-width file and setup
with a table of the widths from https://www.minorplanetcenter.net/iau/info/CometOrbitFormat.html to read in the data.  Data are
slightly edited relative to the MPC originals for clarity and renamed to distinguish it from the other files we provide.

### Important Note about asteroid databases:

The contents of the `Asteroids/` folder are all gzip compressed to fit on GitHub.  Once you download them onto your computer
you need to unzip them (`gunzip`) before you can run the notebooks.

## Artwork

<dl>
    <dd>Figure 3.2 - `Fig3_2.jpg`: Schematic of the orbits of Mars and Jupiter with labels (from original PowerPoint)
    <dd>Figure 3.5 - `Fig3_5.png`: Surface of section for the quasi-periodic orbit examined in Figure 3.4 (original provided by Carl Murray)
    <dd>Figure 3.7 - `Fig3_7.png`: Surface of section for the chaotic orbit examined in Figure 3.6 (original provided by Carl Murray)
    <dd>Figure 3.11 - `Fig3_11.jpg`: Schematic of the Io, Europa, and Ganymede Laplace resonance (from original PowerPoint)
</dl>

