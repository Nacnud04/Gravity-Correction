# Gravity Correction

This repo contains a single jupyter notebook which can perform a drift correction, free air correction and bouger correction on geophysical gravity measurements.

### This notebook requires:
- A .csv file containing precise GPS measurements (in UTM) for each gravity measurement location. 
- A .txt file containing gravity measurements produced by a CG-5 (or similar) gravimeter.
- A consistent naming schema to match GPS locations and gravity measurements.

### This notebook will break (or need modifications) if:
- There is an unequal number of gravity measurements and GPS measurements.
- The naming convention between the GPS data and gravity data is not consistent.

### This notebook does not support:
- Additionally gravity corrections (tidal, latitude, etc.)
- Use of multiple gravimeters at once.