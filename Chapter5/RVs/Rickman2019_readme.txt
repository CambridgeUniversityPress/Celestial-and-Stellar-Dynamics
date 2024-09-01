J/A+A/625/A71      Radial velocity measurements for 7 stars     (Rickman+, 2019)
================================================================================
The CORALIE survey for southern extrasolar planets.
XVIII. Three new massive planets and two low-mass brown dwarfs at greater than
5 AU separation.
    Rickman E.L., Segransan D., Marmier M., Udry S., Bouchy F., Lovis C.,
    Mayor M., Pepe F., D.Queloz, Santos N.C., Allart R., Bonvin V., Bratschi P.,
    Cersullo F., Chazelas B., Choplin A., Conod U., Deline A., Delisle J.-B.,
    Dos Santos L.A., Figueira P., Giles H.A.C., Girard M., Lavie B., Martin D.,
    Motalebi F., Nielsen L.D., Osborn H., Ottoni G., Raimbault M., Rey J.,
    Roger T., Seidel J.V., Stalport M., Suarez Mascareno A., Triaud A.,
    Turner O., Weber L., Wyttenbach A.
    <Astron. Astrophys. 625, A71 (2019)>
    =2019A&A...625A..71R        (SIMBAD/NED BibCode)
================================================================================
ADC_Keywords: Stars, double and multiple ; Exoplanets ; Radial velocities
Keywords: techniques: radial velocities - planets and satellites: detection -
          binaries: visual - planetary systems

Abstract:
    Since 1998, a planet-search around main sequence stars within 50pc in
    the southern hemisphere has been underway with the CORALIE
    spectrograph at La Silla Observatory.

    With an observing time span of more than 20 years, the CORALIE survey
    is able to detect long-term trends in data with masses and separations
    large enough to select ideal targets for direct imaging. Detecting
    these giant companion candidates will allow us to start bridging the
    gap between radial-velocity-detected exoplanets and directly imaged
    planets and brown dwarfs.

    Long-term precise Doppler measurements with the CORALIE spectrograph
    reveal radial-velocity signatures of massive planetary companions and
    brown dwarfs on long-period orbits.

    In this paper we report the discovery of new companions orbiting
    HD 181234, HD 13724, HD 25015, HD 92987 and HD 50499. We also report
    updated orbital parameters for HD 50499b, HD 92788b and HD 98649b. In
    addition, we confirm the recent detection of HD 92788c. The newly
    reported companions span a period range of 15.6 to 40.4 years and a
    mass domain of 2.93 to 26.77 MJup, the latter of which straddles the
    nominal boundary between planets and brown dwarfs.

    We report the detection of five new companions and updated parameters
    of four known extrasolar planets. We identify at least some of these
    companions to be promising candidates for imaging and further
    characterisation.

Description:
    Radial velocity measurements for HD181234, HD25015, HD50499, HD92788,
    HD98649, HD13724, HD92987. In addition, H-alpha time series data for
    HD25015, with the date of the measurement in Julian days [JD], the
    H-alpha index and the error on the H-alpha index. Each file has the
    date of the measurement in Julian days [JD], the radial velocity
    measurement in m/s and the error on the radial velocity measurement.

File Summary:
--------------------------------------------------------------------------------
 FileName      Lrecl  Records   Explanations
--------------------------------------------------------------------------------
ReadMe            80        .   This file
stars.dat         34        7  *List of studied stars
rv.dat           102      815   Radial velocities
--------------------------------------------------------------------------------
Note on stars.dat: only HD25015 have H-alpha time series.
--------------------------------------------------------------------------------

See also:
 J/A+A/356/590  : CORALIE survey for extrasolar planets. II (Udry+, 2000)
 J/A+A/375/205  : CORALIE survey for extrasolar planets. V (Naef+ 2001)
 J/A+A/379/999  : CORALIE survey for extrasolar planets. VI (Santos+ 2001)
 J/A+A/388/632  : CORALIE survey for extrasolar planets. VII (Pepe+, 2002)
 J/A+A/390/267  : CORALIE survey for extrasolar planets. VIII (Udry+, 2002)
 J/A+A/392/215  : CORALIE survey for extrasolar planets. IX (Santos+ 2002)
 J/A+A/406/373  : CORALIE survey for extrasolar planets. XI (Santos+, 2003)
 J/A+A/415/391  : CORALIE survey for extrasolar planets. XII (Mayor+, 2004)
 J/A+A/447/1159 : CORALIE survey for extrasolar planets. XIV (Eggenberger+ 2006)
 J/A+A/480/L33  : CORALIE survey for extrasolar planets. XV (Tamuz+ 2008)
 J/A+A/511/A45  : CORALIE survey for extrasolar planets. XVI (Segransan+, 2010)

Byte-by-byte Description of file: stars.dat
--------------------------------------------------------------------------------
   Bytes Format Units   Label     Explanations
--------------------------------------------------------------------------------
   1-  8  A8    ---     Name      Star name
  12- 13  I2    h       RAh       Simbad right ascension (J2000)
  15- 16  I2    min     RAm       Simbad right ascension (J2000)
  18- 22  F5.2  s       RAs       Simbad right ascension (J2000)
      24  A1    ---     DE-       Declination sign (J2000)
  25- 26  I2    deg     DEd       Declination (J2000)
  28- 29  I2    arcmin  DEm       Declination (J2000)
  31- 34  F4.1  arcsec  DEs       Declination (J2000)
--------------------------------------------------------------------------------

Byte-by-byte Description of file: rv.dat
--------------------------------------------------------------------------------
   Bytes Format Units   Label     Explanations
--------------------------------------------------------------------------------
   1-  8  A8    ---     Name      Star name
  11- 17  A7    ---     Code      Instrument + year code
  19- 21  A3    ---     DRS       DRS
  23- 40 F18.12 d       RJD       The Julian date of when the radial
                                   velocity measurement was taken (JD-2400000)
  46- 58  F13.6 m/s     RV        Radial velocity measurement
  61- 70  F10.6 m/s   e_RV        Error on the radial velocity
  79- 86  F8.6  ---     Ha        ? H{alpha} measurement (1)
  95-102  F8.6  ---   e_Ha        ? Error on the H{alpha} measurement (1)
--------------------------------------------------------------------------------
Note (1): only for HD25015.
--------------------------------------------------------------------------------

Acknowledgements:
    Emily Rickman, emily.rickman(at)unige.ch

References:
   Queloz et al.,      Paper I    2000A&A...354...99Q
   Udry et al.,        Paper II   2000A&A...356..590U, Cat. J/A+A/356/590
   Santos et al.,      Paper III  2000A&A...356..599S
   Santos et al.,      Paper IV   2000A&A...361..265S
   Santos et al.,      Paper V    2001A&A...375..205S, Cat. J/A+A/375/205
   Santos et al.,      Paper VI   2001A&A...379..999S, Cat. J/A+A/379/999
   Pepe et al.,        Paper VII  2002A&A...388..632P, Cat. J/A+A/388/632
   Udry et al.,        Paper VIII 2002A&A...390..267U, Cat. J/A+A/390/267
   Santos et al.,      Paper IX   2002A&A...392..215S, Cat. J/A+A/392/215
   Udry et al.,        Paper X    2003A&A...407..679U
   Santos et al.,      Paper XI   2003A&A...406..373S, Cat. J/A+A/406/373
   Mayor et al.,       Paper XII  2004A&A...415..391M, Cat. J/A+A/415/391
   Correia et al.,     Paper XIII 2005A&A...440..751C
   Eggenberger et al., Paper XIV  2006A&A...447.1159E, Cat. J/A+A/447/1159
   Tamuz et al.,       Paper XV   2008A&A...480L..33T, Cat. J/A+A/480/L33
   Segransan et al.,   Paper XVI  2010A&A...511A..45S, Cat. J/A+A/511/A45
   Marmier et al.,     Paper XVII 2013A&A...551A..90M

================================================================================
(End)   Emily Rickman [UNIGE, Switzerland], Patricia Vannier [CDS]   06-May-2019
