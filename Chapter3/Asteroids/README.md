# Select MPC and AstDyS-2 Asteroid Data

MPC orbit element files were last updated on **2024 Nov 10**.

## Extracted Orbit Element Files

These files contain data derived from these databases:
 * Minor Planet Center (MPC) orbit element database (MPCORB): https://minorplanetcenter.net/iau/MPCORB.html
 * AstDyS-2 database: https://newton.spacedys.com/astdys/

We use simplified snapshots of these databases for the plots generated for the book that pre-select data 
to speed up plotting (rather than reading in all 1.3 million MPCORB data records and sorting in-situ).

We have gzip compressed these files to fit them on GitHub - you will need to unzip them after downloading
the repository before using them.

Data were last extracted in 

## Updating Orbit Element Data

The `procOrb.ipynb` notebook is provided that shows how we derived subsets of the main catalogs for
plotting in the notebooks for Chapter 3.  You will need to retrieve recent copies of these data
files from the MPC database to create updated versions of these files with `procOrb.ipynb`.

### IAU Minor Planet Center (MPC) Orbit Database

Two orbit element data files from the [IAU Minor Planet Center (MPC) orbit database](https://minorplanetcenter.net/data) are
required to regenerate the asteroid and comet orbit element files used for these figures:
<dl>
   <dd>`MPCORB.DAT` - Orbits for all asteroids in the MPC database (updated daily)</dd>
   <dd>`AllCometEls.txt` - Orbits for all comets in the MPC database (updated a few times a month when new comets are identified)</dd>
</dl>

### ESA Asteroid Dynamics AstDyS-2 Database

To update proper orbit elements for asteroids, retrieve the `all.syn` data file from
the [ESA Asteroid Dynamics Site (AstDyS-2)](https://newton.spacedys.com/astdys2).  This
is the catalog of proper orbit elements for Main Belt and Hungaria asteroids.
