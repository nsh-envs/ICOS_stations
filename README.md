# This repository is used for analyzing ICOS stations data.
This repository is a part of my PhD project, and the code plots ICOS (Integrated Carbon Observatory Sytem) data from various stations around Europe. 

The data is used to verify DEHM (Danish Eulerian Hemispheric Model) a meso-scale atmospheric transport model. DEHM is part of the CAMS European air quality ensemble forecast. In my PhD project however, I am developing another branch that models CO2 in the atmosphere.

## Files.
### nb\_icos\_stations.ipynb
Notebook that contains the plotting code for ICOS stations.

### nb\_dehm\_stations.ipynb
Notebook that contains the plotting code for DEHM model data at the location of the ICOS stations.

### nb\_both\_stations.ipynb
This file contains the plotting for ICOS stations data together with the DEHM model output at the same locations.

### py\_icos\_stations.py
This file contains an outdated version of the notebook converted to a regular '.py' file.

### lib\_icos.py
This file is supposed to collect all functions in a class object to make an ICOS plotting library.

### stations\_namelist.txt
Names for the particular stations used from ICOS.
