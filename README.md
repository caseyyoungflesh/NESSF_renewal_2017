# NESSF_renewal_2017

All scripts required to run analyses included in NASA Earth and Space Science Fellowhsip (NESSF) 2017 renewal for C Youngflesh.

_RENEWAL: Environmental forcing of Antarctic food web dynamics - a multi-tiered approach emploing multispectral imagery, field spectroscopy, and stable isotope analysis_

&nbsp;

Scripts are numbered in the order in which they should be run:

 * 1-process-data.R - Processes data
 * 2-convolve_spectra.R - Convolves lab collected spectra to Landsat bands
 * 3-PLSR.R - Examines relationship between convolved spectra and dN as obtained by SIA
 * 4-predict-dN.R - Predicts dN values based on PLSR analyses
 * 5-run-hierarchical-model.R - Runs hierarchical model to look at change in predicted dN over time and space
 
