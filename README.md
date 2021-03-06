# PESTO_pipeline
A pipeline for processing data from the Planètes Extra-Solaires en Transit et Occultations (PESTO) optical telescope located at l’Observatoire du Mont-Mégantic (OMM). 

Work on this pipeline was begun in Summer 2018 by Andy Ramirez-Côté and continued from September 2018 to August 2019 by Valérie Desharnais and Nicholas Vieira. All work was completed under the supervision of Professor D. Haggard and the rest of the Haggard research group at McGill.

# Modules you'll need 
This software makes use of certain modules you may not already have. These are:

astropy -- Widely-used software for astrophysical programming. It's recommended to download the whole thing. 

pyraf -- An industry standard tool for all sorts of astrophysical programming. Used here for stacking images and applying domeflat corrections. 

astrometry.net -- A tool for source detection and astrometric calibration of images (finding world coordinate system solutions).

astroquery -- A tool for querying online catalogues. 

photutils -- Software affiliated with astropy, used specifically for photometry. It's also recommended to download the whole thing. 

# Where to get these modules

astropy: http://docs.astropy.org/en/stable/install.html

pyraf: http://www.stsci.edu/institute/software_hardware/pyraf (Installing this correctly can be very difficult. Follow instructions carefully to download via AstroConda).
If you have access to the irulan server of McGill University, iraf will already be installed. If your institution has a server dedicated to physics/astrophysics, it will probably already have iraf as well. 

astrometry.net: http://astrometry.net/doc/readme.html#installing

astroquery: https://astroquery.readthedocs.io/en/latest/#installation

photutils: https://photutils.readthedocs.io/en/stable/install.html

# How to use this software

Documentation and a step-by-step guide on the use of this software can be seen here: https://github.com/nvieira-valdesharnais-mcgill/PESTO_pipeline/wiki

