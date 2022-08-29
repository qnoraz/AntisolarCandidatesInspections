## Presentation

This repository contains data used for the published study:
https://arxiv.org/abs/2208.12297  
Title: Hunting for anti-solar differentially rotating stars using the Rossby number - An application to the Kepler field  
Authors: Q. Noraz, S. N. Breton, A. S. Brun, R. A. García, A. Strugarek, A. R. G. Santos, S. Mathur, L. Amard  

## Description

You will find in this repository data used for the individual inspections of anti-solar candidates of the Noraz et al. (2022b) (A&A) study.
These anti-solar candidates are 99 Kepler targets, which were first selected with their high Rossby values, calculated with the analytical formula from the same study.
In order to keep the most reliable one, we first performed visual check of the Kepler field of view, with the 2MASS data base (https://kasoc.phys.au.dk/).
Then, then we performed additional rotation anaylsis of the light-curves in order to ensure the reliability of the detected Prot in Santos et al. (2019, 2021).

## Material

You can find a summary plot of the different rotation analysis for each targets in the 'FigsRot' folder.  
The five related light curves can be found for each target in .fits files located in the 'LC' folder:  
- the three KEPSEISMIC light-curves used in Santos et al. (2019, 2021) and obtained with KADACS (García et al. 2011) for cutoff periods at 20, 55 and 80 days (./KADACSxxd/ with xx the period value),  
- the PDC-MAP light-curve (Jenkins et al. 2010; Smith et al. 2012; Stumpe et al. 2012) (./PDC54d/),  
- the additional KEPSEISMIC light-curve cutted off at 80 days, and which has been detrended from the long-term Kepler modulation (./Fold80d).  

The Jupiter Python notebook 'READ_KEPSEISMIC_FITS_FILES' give you an example of plot you can make with such .fits files.  
Finally, Table C.1 of Noraz et al. (2022b) is made available in its full and machine-readable form : see TableC1v2.txt .

## Requirements

The Python Notebook is written for Python 3. If used on your personal machine, the following packages are required:  
- astropy  
- matplotlib  
