# Astro100-final-project
This is the GitHub repository for my Astronomy 100 observing project: Classifying Supernova 2026atw.

# Abstract: 
In this paper, I set to classify the previously unclassified supernova transient, SN 2026atw, for my Astronomy 100 final project. Visible from the Fred Lawrence Whipple Observatory in Arizona, the FAST (Fast Spectrograph for the Tillinghast Telescope) spectrometer was used to observe the transient on the night of March 17th, 2026. All of the raw data, in the form of .fits files, were reduced and used to create a spectrum of SN 2026atw, where the presence of Balmer lines immediately classified it as Type II and determined its progenitor as a massive main sequence star turned red supergiant that underwent core collapse. Further measurements on the redshift of the spectrum and calculations were performed, such as the ejecta velocity, and comparing this to the recession velocity and distance to the host galaxy of SN 2026atw. Then, the light curve of SN 2026atw from ATLAS forced photometry was obtained and plotted in absolute magnitude using the redshift of the supernova, where the peak magnitude, phase, and subtype “P” were determined. The measurements and calculations made by me for SN 2026atw were then compared across literature, and then compared to SNID-SAGE’s classification of SN 2026atw, which confirmed that it was a Type IIP supernova. SN 2026atw’s classification was then published on the Transient Name Server for 2026atw (https://www.wis-tns.org/object/2026atw); but further modeling work on the light curve remains to determine the mass and size of the progenitor, as well as the total energy of the supernova explosion.

# Repository contents

## BIAS folder: 
- Contains all BIAS files taken from night of observation, March 17th, 2026. These files were used to create a median master BIAS and reduce the raw data of 0080.2026atw.fits into a usable, flux-calibrated scientific spectrum.
## FLAT folder: 
- Contains FLAT files taken from night of observation, March 17th, 2026. These files were used to create a master FLAT and reduce the raw data of 0080.2026atw.fits into a usable, flux-calibrated scientific spectrum.
## 0054.COMP.fits:
- The Argon lamp of reference wavelengths used to calibrate Hiltner 600's spectrum in 0053.Hiltner600.fits.
## 0080.COMP.fits:
- The Argon lamp of reference wavelengths used to calibrate SN 2026atws's spectrum in 0080.2026atw.fits.
## 0053.Hiltner600.fits: 
- The raw observational data/image taken of the standard star, Hiltner 600. The flux-calibrated spectrum of this star was used to derive a sensistity function to flux-calibrate the spectrum of SN 2026atw.
## fhilt600.dat.txt:
- The known reference fluxes of Hiltner 600. This file was used in the calibration of Hiltner 600's spectrum so that a sensitivity function could be derived.
## 0080.2026atw.fits:
- The raw observational data/image taken of the supernova transient, 2026atw. The flux-calibrated spectrum of this supernova was used in spectral analysis to determine its redshift and type.
## 0080_2026atw_fast_reduction_class.py: 
- The Google CoLab notebook with all of the data reduction and spectral analysis for both Hiltner 600 and SN 2026atw. This is a step by step notebook where the final products are a flux calibrated Hiltner 600 and SN 2026atw spectra. In this file, you'll be able to reduce the raw data from Hiltner 600 and 2026atw, produce their flux-calibrated spectra, and identify Balmer lines in the spectrum of 2026atw that will be used for redshift calculation in Redshift, Light Curves, Galaxy Data-2.ipynb.
## Redshift, Light Curves, Galaxy Data-2.ipynb: 
- The Jupyter notebook with all of the code and steps taken in calculating a redshift and ejecta velocity for 2026atw, recession velocity and redshift for host galaxy, and the light curves of 2026atw and compared SN, 2017hjw and 2023ixf. The data for all of the light curves is contained within this file as url links embededded in the code. Additionally, the peak magnitude, phase, and time of explosoion were calculated in this file. In this notebook, you'll be able to generate plots (and steps taken to achieve the final plots) of the light curves for all three supernovae. You'll also be able to calculate properties of the host galaxy and 2026atw with uncertainty measurements, as well as properties of 2026atw from its light curve with uncertainty measurements.
## Astro_100_Final_Paper.pdf
- This is the final paper that I wrote for this project. Please refer to this pdf for any clarification/necessary deeper explanation on the data files and methodology used in creating the code of these notebooks for their results.

You can contact me at solideaficco@college.harvard.edu for any questions regarding this repository or my paper. Thank you for checking it out, and have fun classifying 2026atw!
