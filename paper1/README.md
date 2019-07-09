### General Notebooks
| Notebook |  Comments | 
|---|---|
| [data_processing.ipynb](https://github.com/moeyensj/atm/blob/master/notebooks/data_processing.ipynb) | Creates sample.db and sample_W3.db from WISE observations and MPC data.  Adds NEOWISE PDS 2016 table and crossmatches. |
| [build_lookup_tables.ipynb](https://github.com/moeyensj/atm/blob/master/notebooks/build_lookup_tables.ipynb) | Builds lookup tables at user-defined wavelengths for  the NEATM, FRM and STM models|
| [W3_investigation.ipynb](https://github.com/moeyensj/atm/blob/master/notebooks/W3_investigation.ipynb) | Prints flux ratio between WISE quadrature formulae and the flux emitted by a black-body (useful for evaluating quadrature formulae) | 

### Validation Notebooks
| Notebook | Comments | Figure(s) in Paper |
|---|---|---|
|[example_Eros.ipynb](https://github.com/moeyensj/atm/blob/master/notebooks/validation/example_Eros.ipynb)| Validates ATM thermal model implementation with 433 Eros example from literature | [Fig 5](https://github.com/moeyensj/atm/blob/master/notebooks/plots/validation_Eros.png) |
|[example_1991EE.ipynb](https://github.com/moeyensj/atm/blob/master/notebooks/validation/example_1991EE.ipynb)| Validates ATM thermal model implementation with 1991 EE example from literature | [Fig 6](https://github.com/moeyensj/atm/blob/master/notebooks/plots/validation_1991EE.png) |
|[example_synthetic_changingNumObservations.ipynb](https://github.com/moeyensj/atm/blob/master/notebooks/validation/example_synthetic_changingNumObservations.ipynb)| Shows how fitting changes with varying numbers of observations and fit parameters | [Fig 1](https://github.com/moeyensj/atm/blob/master/notebooks/plots/validation_synthetic_1obs_2param_SEDs.png), [Fig 2](https://github.com/moeyensj/atm/blob/master/notebooks/plots/validation_synthetic_1obs_2param_NEATM_corner.png), [Fig 3](https://github.com/moeyensj/atm/blob/master/notebooks/plots/validation_synthetic_1obs_3param_NEATM_corner.png), [Fig 4](https://github.com/moeyensj/atm/blob/master/notebooks/plots/validation_synthetic_25obs_3param_NEATM_corner.png) | |

### Analysis Notebooks
| Notebook | Comments | Figure(s) in Paper |
|---|---|---|
|[post_processing.ipynb](https://github.com/moeyensj/atm/blob/master/notebooks/analysis/post_processing.ipynb) | Adds post-processing tables to ATM results databases | - |
|[analysis.ipynb](https://github.com/moeyensj/atm/blob/master/notebooks/analysis/analysis.ipynb)| Compares ATM modeling results with those from NEOWISE | [Fig 10](https://github.com/moeyensj/atm/blob/master/notebooks/plots/chi2_num_obs.png), [Fig 11](https://github.com/moeyensj/atm/blob/master/notebooks/plots/diameter_emissivity_albedo.png), [Fig 12](https://github.com/moeyensj/atm/blob/master/notebooks/plots/CCD_tracks.png)   |
|[analysis_W3.ipynb](https://github.com/moeyensj/atm/blob/master/notebooks/analysis/analysis_W3.ipynb) | Calculates pseudo-absolute magnitude for different WISE bands and builds simple diameter estimator | [Fig 13](https://github.com/moeyensj/atm/blob/master/notebooks/plots/M3_color_albedo.png), [Fig 14](https://github.com/moeyensj/atm/blob/master/notebooks/plots/W3_estimator.png), [Fig 15](https://github.com/moeyensj/atm/blob/master/notebooks/plots/W3_estimator_codes.png) | 
|[analysis_SDSS.ipynb](https://github.com/moeyensj/atm/blob/master/notebooks/analysis/analysis_SDSS.ipynb) | Compares WISE best-fit diameters to those derived using SDSS colors and best-fit albedos from ATM | [Fig 16](https://github.com/moeyensj/atm/blob/master/notebooks/plots/SDSS_diameter_albedo.png), [Fig 17](https://github.com/moeyensj/atm/blob/master/notebooks/plots/SDSS_metallic.png)|
|[single_object.ipynb](https://github.com/moeyensj/atm/blob/master/notebooks/analysis/single_object.ipynb) | Template notebook to run multiple different thermal modeling runs on a single object | - |
|[single_object_25916.ipynb](https://github.com/moeyensj/atm/blob/master/notebooks/analysis/single_object_25916.ipynb) | Runs 10 different thermal modeling runs with varying assumptions on priors and fit configurations for asteroid (25916) | - |
|[single_object_54789.ipynb](https://github.com/moeyensj/atm/blob/master/notebooks/analysis/single_object_54789.ipynb) | Runs 10 different thermal modeling runs with varying assumptions on priors and fit configurations for asteroid (54789) | [Fig 7](https://github.com/moeyensj/atm/blob/master/notebooks/plots/54789_run4b_NEATM_WISE_corner.png), [Fig 8](https://github.com/moeyensj/atm/blob/master/notebooks/plots/54789_run4a_NEATM_WISE_corner.png) |
|[single_object_90367.ipynb](https://github.com/moeyensj/atm/blob/master/notebooks/analysis/single_object_90367.ipynb) | Runs 10 different thermal modeling runs with varying assumptions on priors and fit configurations for asteroid (90367) | - |
