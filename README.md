[![DOI](https://zenodo.org/badge/257904489.svg)](https://zenodo.org/badge/latestdoi/257904489)

# Note

The data and code in this repository relates to the following paper in review:

McKenna C. M., A. C. Maycock, P. M. Forster, C. J. Smith, K. B. Tokarska, Stringent mitigation substantially reduces risk of unprecedented near-term warming rates, Nature Climate Change, in review.

The data was processed with funding from the European Union’s CONSTRAIN project as part of the Horizon 2020 Research and Innovation Programme under grant agreement number 820829.


# FaIR data

## Temperature
Time-series of annual global surface air temperature (GSAT) anomalies for 500 FaIR simple climate model simulations using historical emissions and future emissions scenarios (NDCs, SSP1-1.9, SSP1-2.6, SSP3-7.0, and SSP5-8.5). Anomalies are calculated with respect to 1850-1900. The 500 simulations were generated from a broad uncertainty analysis of possible futures, based on lines of evidence for ECS, TCR, and ERF that reflect our latest understanding since IPCC SR1.5. Files listed use two different time-series of aerosol ERF: the default CMIP6 aerosol ERF, or the aerosol ERF from AR5.

## Emissions
Time-series of emissions for each emissions scenario; the SSP datasets were obtained from https://www.rcmip.org/ and the NDCs dataset was provided by Joeri Rogelj. Units are given for all major GHGs and SLCFs, and for minor GHGs the unit is kilotons/year.

## ECS, TCR, and ERF
Distributions of ECS, TCR, and ERF, used to generate each set of 500 simulations. Also contains time-series of the ERF, both for its total and for individual forcing agents. Both versions of the aerosol ERF time-series described above are given.


# Constrained CMIP6 data

Warming trends and anomalies for 2021-2040, using a constraint based on the observed warming trend for 1981-2017 (based on Tokarska et al., Sci Adv. 2020: https://doi.org/10.1126/sciadv.aaz9549). Trends and anomalies are calculated from CMIP6 GSAT data for the future emissions scenarios SSP1-2.6, SSP3-7.0, and SSP5-8.5. See Tokarska et al. 2020 for further details on the CMIP6 and observational data used. Data are provided both as a raw text file, and in a form for use with the relevant Python code provided.


# Observation-based data

Time-series of annual global mean surface temperature from different observational datasets, which are used to calculate observed temperature trends over the historical period. Datasets were downloaded from the following links:   

HadCRUT4.6.0.0: https://crudata.uea.ac.uk/cru/data/temperature/HadCRUT4-gl.dat

Berkeley Earth Land-Ocean: http://berkeleyearth.lbl.gov/auto/Global/Land_and_Ocean_summary.txt

Cowtan-Way version 2 updated with HadSST3: https://www-users.york.ac.uk/~kdc3/papers/coverage2013/had4_krig_annual_v2_0_0.txt

GISTEMP version 4: https://data.giss.nasa.gov/gistemp/tabledata_v4/GLB.Ts+dSST.csv


# Internal variability data

Observation-based estimates of internal variability in 20-year GSAT trends and anomalies. This data is provided here in processed form only for use with the relevant Python code provided. The raw data used to calculate these are based on Haustein et al. (2019; https://doi.org/10.1175/JCLI-D-18-0555.1) and were provided by Karsten Haustein. 


# Analysis and figure code

Python code used to conduct the analysis and produce the figures/tables. Any additional data required to run this code (e.g. the CMIP6 pre-industrial control simulation GSAT data), and not listed above, is provided in the folder for the relevant figure/table.





