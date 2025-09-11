# README.md

- author : Sylvie Dagoret-Campagne
- affiliation : IJCLab/IN2P3/CNRS
- member : DESC, rubin-inkind
- creation date : 2025-06-01
- last update : 2025-06-06 : psf and Ap fluxes
- last update 2025-09-11 : setting up for the RSP (from usdf)

## notebooks adapted to RSP-DP1

- **VISITS01_FindObservationsInButlerRegistry.ipynb** : Extract from butler registry the series of visiits including the information that comes with it.
  	       
- **VISITS02_FindObservationsInButlerRegistryInTractPatch.ipynb** : As above but allocate tract and patch at each visit.
 
- **VISITS03_histosforvisits.ipynb** : Make plots from the visits to find the most visited tract and patches.

- **VISITS04_DeepCoaddFromSelectedTractPatch.ipynb** : Show the DeepCoadd of the most visited tract and patch.

- **VISITS05_SourcesFromVisits.ipynb** : Making Light curves from objects found in the DeepCoadds (**04_DeepCoaddFromSelectedTractPatch.ipynb**)


## To adapt later

- **06_SourcesFromVisitsMultiBands_psfMag.ipynb** : Light curves on psfFlux

- **07_SourcesFromVisitsMultiBands_apMag.ipynb** : Light curves on psfFlux, calibFlux and all Ap fluxes. Generate the resolution file for the next notebook.

- **07b_CheckFluxesCalibrations.ipynb** : Check the calibration of aperture fluxes and which is the best radius for the aperture flux for stars.
