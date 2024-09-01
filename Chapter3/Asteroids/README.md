# Select MPC and AstDyS-2 Asteroid Data

Processed data derived from
 * Minor Planet Center (MPC) orbit element database (MPCORB): https://minorplanetcenter.net/iau/MPCORB.html
 * AstDyS-2 database: https://newton.spacedys.com/astdys/

We use simplified snapshots of these databases for the plots generated for the book that pre-select data 
to speed up plotting (rather than reading in all 1.3 million MPCORB data records and sorting in-situ).

We have to gzip compress these to put them onto GitHub - you will need to unzip them after downloading
the repository before using them.
