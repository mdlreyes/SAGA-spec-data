# SAGA-spec-data
Repo of SAGA follow-up spectroscopy


<!-- TABLE OF CONTENTS -->
## Table of Contents

* [About](#about)
* [Contact](#contact)
* [Acknowledgements](#acknowledgements)



<!-- ABOUT THE PROJECT -->
## About

This will eventually contain the reduced data from SAGA follow-up spectroscopy.

/tel_instrument_date
* dbsp_params.cfg = config file for DBSP_DRP
* /rdx = outputs from reduction pipeline
  * /Master_[blue/red] = master files used for calibration, wavelength solution files 
  * /Science = blue and red coadds (red includes both telluric corrected and uncorrected)
  * /QA = quality assurance files produced by pypeit
  * /spliced = final spliced spectra (see [DBSP_DRP docs](https://dbsp-drp.readthedocs.io/en/latest/outputs.html) for data model)
  * other folders contain other potentially useful info from data reduction

<!-- CONTACT -->
## Contact

Mia de los Reyes - mdlreyes@stanford.edu



<!-- ACKNOWLEDGEMENTS -->
## Acknowledgements

[README.md template](https://github.com/othneildrew/Best-README-Template)
